

**SPARXSTAR**

DVE Trust Architecture

**Three-Token Governance Model**

*Personal Policy Token · Group Policy · Release Receipt*

| Document ID | DVE-TRUST-001 |
| :---- | :---- |
| **Status** | NORMATIVE — Locked |
| **Date** | 2026-05-02 |
| **Author** | Starisian Technologies / Max Barrett |
| **Relates To** | PAM-002 · Ouroboros CO-001 · Mḗh₁n̥s v3.1 |
| **Classification** | CONFIDENTIAL · PATENT PENDING |

**PURPOSE:** This document defines the three cryptographic instruments that govern sovereign data flow in the SPARXSTAR platform. PAM-001 defined only the Release Receipt (GovernanceToken). PAM-002 locked the ArtifactGovernanceDeclaration. This document locks the Personal Policy Token, Group Policy, and the complete token resolution chain — closing the last major gap in the governance architecture.

*Starisian Technologies · May 2026 · CONFIDENTIAL · PATENT PENDING*

# **PART I — Why Three Tokens**

The platform requires three distinct cryptographic instruments at different points in the data lifecycle. These are not variants of the same object. They serve fundamentally different purposes, have different owners, different lifetimes, and different consumers. Conflating them is a design error.

| Token | Minted By | Consumed By | Lifetime |
| :---- | :---- | :---- | :---- |
| **Personal Policy Token** | Sky Eshu at intake | Mḗh₁n̥s PolicyResolver | Short — minutes |
| **Group Policy** | Community authority (declarative) | Mḗh₁n̥s PolicyResolver | Standing — until amended |
| **Release Receipt (GovernanceToken)** | Mḗh₁n̥s TokenMinter | Dheghom TokenValidator | 60–3600s, one-time |

The Personal Policy Token answers: 'What does this individual contributor want to happen to this data?' The Group Policy answers: 'What does the community authority require?' The Release Receipt answers: 'Has this specific payload cleared the governance Sieve?' All three are required for the complete governance chain. The Release Receipt cannot be minted without the first two being resolved.

# **PART II — Personal Policy Token**

## **2.1 What It Is**

The Personal Policy Token is a short-lived, individual governance instrument minted by Sky Eshu at the moment a contributor initiates a release. It captures the contributor's declared personal governance preferences for a specific submission — AI opt-in or opt-out, sharing scope, royalty preferences — and carries them forward to Mḗh₁n̥s for policy resolution.

The Personal Policy Token is NOT a session token, a device token, or an identity token. Helios and Sirus handle those. The Personal Policy Token is exclusively a governance preference instrument — what the individual contributor wants done with this specific submission at this specific moment.

## **2.2 Who Mints It**

Sky Eshu mints the Personal Policy Token immediately before handing the ExecutionContext to Mḗh₁n̥s. The minting occurs after the contributor clicks Release — not at session start, not at draft save. The token represents the contributor's preferences at the moment of submission.

**ARCHITECTURAL RULE:** Sky Eshu mints. Mḗh₁n̥s evaluates. Dheghom validates the Release Receipt. No component mints a token that it also evaluates or consumes.

## **2.3 Field Set**

The Personal Policy Token is a signed JSON document with the following fields:

| Field | Type | Description |
| :---- | :---- | :---- |
| **ppt\_id** | UUID v4 | Unique token identifier |
| **transaction\_id** | UUID v4 | Matches ExecutionContext.transaction\_id |
| **identity\_id** | string | Contributor UUID from Helios/Sirus. Never name. |
| **authority\_id** | string | null | Linked community authority. Null for independent creators. |
| **ai\_consent** | enum | denied | internal\_only | commercial — AI training preference |
| **sharing\_scope** | enum | private | community | public — default sharing preference |
| **royalty\_preference** | string | null | Contributor's declared royalty split preference for this submission |
| **voice\_reconstruction\_consent** | enum | prohibited | community\_only | authorized\_use — voice reconstruction opt-in/out |
| **tk\_labels\_asserted** | string\[\] | WIPO Traditional Knowledge labels the contributor is asserting for this submission |
| **issued\_at** | int | Unix timestamp of minting |
| **expires\_at** | int | Unix timestamp. Default: issued\_at \+ 300 (5 minutes). |
| **signature** | string | HMAC-SHA256 over canonical signing material using SKY\_ESHU\_SIGNING\_KEY |

## **2.4 Canonical Signing Material**

The signing material is newline-delimited key=value pairs in this exact order. Timestamps are Unix integers as plain decimal strings.

v=v1

ppt\_id={ppt\_id}

transaction\_id={transaction\_id}

identity\_id={identity\_id}

authority\_id={authority\_id}          ← empty string if null

ai\_consent={ai\_consent}

sharing\_scope={sharing\_scope}

voice\_reconstruction\_consent={voice\_reconstruction\_consent}

tk\_labels\_asserted={json\_sorted\_array}

expires\_at={unix\_integer}

issued\_at={unix\_integer}

## **2.5 TTL and Expiry**

The default TTL is 300 seconds (5 minutes). This is sufficient for the Release Gate to complete including Mḗh₁n̥s policy evaluation, GovernanceToken minting, and Dheghom write. If the Release Gate fails or times out, the Personal Policy Token expires and a new submission must be initiated. This prevents replay attacks where a token from a prior submission is reused with a different payload.

## **2.6 What It Does NOT Carry**

* Session credentials — those are Helios/Sirus domain

* Device identity — that is the ContextPulse domain

* Payload content — that travels in ExecutionContext separately

* Community authority rules — those are Group Policy domain

* Final governance decision — that is the Release Receipt domain

# **PART III — Group Policy**

## **3.1 What It Is**

Group Policy is the standing governance declaration of a community authority — a sovereign tribe, creative guild, record label, academic institution, or any other collective body that has completed the Collective Onboarding flow. It is not a token in the same sense as the Personal Policy Token or Release Receipt. It is a set of structured JSON policy files that Mḗh₁n̥s resolves at release time for any member of the authority.

Group Policy is persistent and standing. It does not expire. It is amended through the community's Constitutional governance process. It is the expression of collective sovereignty over data — what the community requires of all submissions from its members, regardless of individual preference.

## **3.2 Group Policy Supersedes Personal Policy**

**GOVERNING RULE:** When a contributor belongs to a community authority, Group Policy supersedes Personal Policy Token preferences in the direction of restriction. A community's AI opt-out overrides a member's AI opt-in. An individual's AI opt-out always stands even if the community permits AI. The resolution is: take the most restrictive of Group and Personal on every dimension.

This is not punitive — it is sovereignty. A contributor who submits sacred knowledge under tribal authority is submitting under the community's law, not only their own. The community's governance stands above individual preference because the community holds the authority over that knowledge.

## **3.3 Group Policy Structure**

Group Policy is expressed as JSON policy files loaded by the PolicyRegistry from the /policies/authority/{authority\_id}/ directory. Each policy file is a standard Mḗh₁n̥s policy document (see Mḗh₁n̥s v3.1 Section 9). Group Policy files are generated from the Collective Onboarding flow and may also be hand-crafted by authorized community governance officers using the Policy Builder UI.

| Dimension | Resolution Rule |
| :---- | :---- |
| **AI training consent** | Most restrictive wins. Community denial overrides individual consent. Individual denial always honored even if community permits. |
| **Sharing scope** | Most restrictive wins. Community community\_only overrides individual public. Individual private always honored. |
| **TK label enforcement** | Community rules for TK labels always apply to all submissions. Individual assertions add to community assertions, never remove. |
| **Royalty splits** | Community tithe (if declared) is enforced first. Individual royalty preferences apply within remaining distribution. |
| **Voice reconstruction** | Most restrictive wins. Community prohibition overrides individual consent. Individual prohibition always honored. |
| **Vault routing** | Community-declared vault constraints take precedence. Individual may restrict further within community-allowed vaults. |

## **3.4 Independent Creators — No Group Policy**

A contributor who completed Collective Onboarding as 'Independent Creator' and is not linked to an authority\_id has no Group Policy. In this case, Personal Policy Token preferences are the most senior governance layer, below only the Global CARE Principles pack which always runs. The PolicyResolver treats the absence of Group Policy as a pass-through — no group restrictions are applied, individual preferences govern.

# **PART IV — Token Resolution Chain**

## **4.1 The Complete Flow**

This is the complete token resolution chain from submission to vault write. It was locked in a prior session and recorded in platform memory. This document formalizes it.

| Step | Action |
| :---- | :---- |
| **1** | Contributor clicks Release. Sky Eshu reads the contributor's governance preferences from the session and mints the Personal Policy Token. The token is short-lived (300s default). |
| **2** | Sky Eshu passes the ExecutionContext to Mḗh₁n̥s. The ExecutionContext carries: the draft payload, the Personal Policy Token, and the Sirus context (identity\_id, authority\_id, session\_id, device\_id, behavior\_flags, geo\_zone). |
| **3** | Mḗh₁n̥s PolicyResolver reads authority\_id from the Sirus context. If authority\_id is present, it loads Group Policy files from /policies/authority/{authority\_id}/. If authority\_id is null, Group Policy is empty. |
| **4** | Mḗh₁n̥s PolicyResolver resolves the effective governance posture: Group Policy preferences are applied first. Personal Policy Token preferences are applied within Group Policy constraints. On every dimension, the most restrictive value wins. |
| **5** | The resolved posture informs the ExecutionContext that is passed to the PolicyDispatcher. The PolicyDispatcher runs Global → Authority → Ability → Individual policy packs in order. |
| **6** | If any policy returns QUARANTINE, the payload is saved to sealed\_archive with forced draft status. No Release Receipt is minted. The Personal Policy Token is consumed and invalidated. |
| **7** | If all policies PASS or REROUTE, Mḗh₁n̥s GovernanceTokenMinter mints the Release Receipt (GovernanceToken). The Release Receipt carries: authority\_id, identity\_id, ability\_id, packs\_enforced, payload\_hash, HMAC signature, and a short TTL (60–3600s based on connectivity tier from ContextPulse.network\_effective\_type). |
| **8** | The Release Receipt is passed to Dheghom alongside the payload. Dheghom TokenValidator runs all three gates: signature integrity, payload hash match, expiry check. If all pass, the payload is written to the vault and post\_status is set to 'publish'. |
| **9** | The Release Receipt is stored as post meta (governance\_token, token\_expiry). The AI training pipeline reads only posts with post\_status='publish' and a valid, non-expired governance\_token. Draft records are permanently invisible. |
| **10** | Mḗh₁n̥s also mints the ArtifactGovernanceDeclaration (locked in PAM-002) alongside the Release Receipt. Dheghom stores the Declaration permanently in the spx\_declarations table. It does not expire. |

## **4.2 Mḗh₁n̥s PolicyResolver — New Component**

The PolicyResolver is a new Mḗh₁n̥s component not yet defined in the Mḗh₁n̥s v3.1 spec. It sits between Sky Eshu's handoff and the PolicyDispatcher. Its sole job is to resolve the effective governance posture from the Personal Policy Token and Group Policy before the PolicyDispatcher runs.

class PolicyResolver

{

    public function resolve(

        PersonalPolicyToken $personalToken,

        string              $authorityId,

        SirusContext        $context

    ): ResolvedGovernancePosture

    {

        // Load Group Policy files for this authority

        $groupPolicies \= empty($authorityId)

            ? \[\]

            : $this-\>authorityRepository-\>loadFor($authorityId);

        // Resolve effective posture — most restrictive wins on every dimension

        return new ResolvedGovernancePosture(

            ai\_consent: $this-\>mostRestrictive(

                $personalToken-\>ai\_consent,

                $this-\>extractGroupAiConsent($groupPolicies)

            ),

            sharing\_scope: $this-\>mostRestrictive(

                $personalToken-\>sharing\_scope,

                $this-\>extractGroupSharingScope($groupPolicies)

            ),

            // ... resolve all dimensions

        );

    }

}

## **4.3 ResolvedGovernancePosture**

The PolicyResolver produces a ResolvedGovernancePosture object. This is not a token — it is an internal Mḗh₁n̥s working object. It is appended to the ExecutionContext before the PolicyDispatcher runs, so that policy rules can reference the resolved posture directly using condition types in the JSON policy grammar.

A new condition type is added to the JSON policy grammar to support this:

| Condition Type | Evaluates |
| :---- | :---- |
| **resolved\_ai\_consent\_is** | resolved\_posture.ai\_consent \=== value |
| **resolved\_sharing\_scope\_is** | resolved\_posture.sharing\_scope \=== value |
| **resolved\_voice\_reconstruction\_is** | resolved\_posture.voice\_reconstruction\_consent \=== value |
| **personal\_token\_valid** | PersonalPolicyToken present, not expired, signature valid |
| **personal\_token\_expired** | PersonalPolicyToken is absent or expired |

# **PART V — Complete Token Comparison**

| Property | Personal Policy Token | Group Policy | Release Receipt |
| :---- | :---- | :---- | :---- |
| **Minted by** | Sky Eshu | Community authority (declarative, not minted at runtime) | Mḗh₁n̥s GovernanceTokenMinter |
| **Consumed by** | Mḗh₁n̥s PolicyResolver | Mḗh₁n̥s PolicyResolver \+ PolicyDispatcher | Dheghom TokenValidator |
| **Lifetime** | 300s default, configurable | Standing until community amends | 60–3600s, connectivity-tiered, one-time |
| **Expires** | Yes. Hard expiry. | No. Amended, not expired. | Yes. Hard expiry. Replay prevention. |
| **Signed** | Yes. HMAC-SHA256. | No. File-based declaration. | Yes. HMAC-SHA256. |
| **Covers** | Individual contributor preferences for this submission | Community requirements for all member submissions | Governance clearance for this specific payload |
| **Stored** | Not persisted. Used transiently in Release Gate. | /policies/authority/{id}/ files \+ spx\_policy\_packs table | post meta: governance\_token \+ token\_expiry |
| **Superseded by** | Group Policy on restriction dimensions | Nothing — senior governance layer | Nothing — terminal governance event |
| **Fallback if absent** | Release Gate refuses — token is required | Personal Policy Token governs. Independent creator path. | DAL refuses all writes. No bypass. |

# **PART VI — Implementation Requirements**

## **6.1 Sky Eshu**

* Must mint a PersonalPolicyToken before calling Mḗh₁n̥s::dispatch()

* Must read contributor governance preferences from the session object (set during onboarding and confirmed at release time)

* Must sign the token using SKY\_ESHU\_SIGNING\_KEY (minimum 32 bytes, stored in WP constants, never in code)

* Must include the transaction\_id that matches the ExecutionContext being submitted

* Must not reuse a PersonalPolicyToken across submissions — one token per Release Gate invocation

## **6.2 Mḗh₁n̥s**

* Must implement PolicyResolver as a new component (not yet in v3.1 spec — this document defines it)

* PolicyResolver must validate the PersonalPolicyToken signature before reading its values

* PolicyResolver must validate the PersonalPolicyToken has not expired

* PolicyResolver must load Group Policy files for the authority\_id from SirusContext

* PolicyResolver must produce a ResolvedGovernancePosture using most-restrictive-wins on every dimension

* ResolvedGovernancePosture must be appended to ExecutionContext before PolicyDispatcher runs

* PolicyDispatcher must halt immediately if PersonalPolicyToken is invalid or expired — QUARANTINE the submission

## **6.3 Ouroboros**

* PersonalPolicyToken must be added as a new DTO: Starisian\\Sparxstar\\Infrastructure\\DTOs\\PersonalPolicyToken

* PersonalPolicyToken signing material builder must be added: Starisian\\Sparxstar\\Infrastructure\\Utils\\PersonalPolicyTokenSigningMaterial

* ResolvedGovernancePosture must be added as a new DTO: Starisian\\Sparxstar\\Infrastructure\\DTOs\\ResolvedGovernancePosture

* New condition types (resolved\_ai\_consent\_is etc.) must be documented in system/spx-vocab.json

## **6.4 This is PAM-002-P9**

**MIGRATION PHASE:** Implementation of the Personal Policy Token, Group Policy resolution, and PolicyResolver constitutes PAM-002-P9. It follows PAM-002-P4 (Mḗh₁n̥s primary build). Sky Eshu cannot call the PolicyResolver until Mḗh₁n̥s is built. The Ouroboros DTO additions (PersonalPolicyToken, ResolvedGovernancePosture) can begin immediately as part of a CO-002 change.

# **PART VII — Security Properties**

## **7.1 Why the Personal Policy Token Must Be Signed**

Sky Eshu runs in a WordPress environment alongside arbitrary plugins, themes, and third-party code. Any of that code could attempt to forge governance preferences — claiming AI opt-in when the contributor chose opt-out, or claiming no TK labels when sacred knowledge was submitted. The signature on the Personal Policy Token makes forgery detectable. Mḗh₁n̥s rejects any token whose signature does not verify against SKY\_ESHU\_SIGNING\_KEY.

## **7.2 Why the Personal Policy Token Must Expire**

A token that does not expire can be captured and replayed against a different payload. The contributor submits sacred knowledge, the token is captured, and a different payload is later submitted with the same token claiming the same contributor preferences. The short TTL (300 seconds default) closes this window. By the time an attacker could replay the token, it has expired.

## **7.3 Why Group Policy Is Not a Token**

Group Policy is standing law, not a transient credential. Making it a token would create a situation where the community's governance could be bypassed by waiting for the token to expire. Group Policy is persistent, file-based, and resolved from disk at every Release Gate invocation. It cannot expire because community law does not expire.

## **7.4 Threat Model**

| Threat | Mitigation |
| :---- | :---- |
| **Rogue plugin forges AI opt-in preferences** | PersonalPolicyToken signature check. Invalid signature → QUARANTINE. |
| **Replay attack: reuse prior submission's token with new payload** | Short TTL (300s). Payload hash in Release Receipt. Any payload mismatch → Dheghom rejects. |
| **Community member bypasses Group Policy restrictions** | PolicyResolver loads Group Policy from authority files, not from user input. Most-restrictive-wins is enforced in code, not by convention. |
| **Sky Eshu mints token with wrong identity\_id** | identity\_id comes from Sirus context (Helios-verified). Sky Eshu cannot forge it. Any mismatch with the session identity causes PolicyResolver to reject. |
| **Token reuse across multiple submissions** | transaction\_id in PersonalPolicyToken must match ExecutionContext.transaction\_id. Each Release Gate invocation has a unique transaction\_id. |

# **PART VIII — Document Record**

| Document ID | DVE-TRUST-001 |
| :---- | :---- |
| **Locks** | Personal Policy Token field set and signing material |
| **Locks** | Group Policy resolution model and supersession rules |
| **Locks** | PolicyResolver as a required Mḗh₁n̥s component |
| **Locks** | Complete token resolution chain (Steps 1–10) |
| **Locks** | New Ouroboros DTOs: PersonalPolicyToken, ResolvedGovernancePosture |
| **Locks** | New JSON policy condition types for resolved posture |
| **Migration Phase** | PAM-002-P9 — after Mḗh₁n̥s primary build (PAM-002-P4) |
| **Ouroboros Change** | CO-002 — adds PersonalPolicyToken and ResolvedGovernancePosture DTOs |
| **Next amendment** | DVE-TRUST-002 — required if PersonalPolicyToken field set changes or signing material format changes |

**FINAL NOTE:** The Personal Policy Token is the contributor's voice in the governance chain. When a Gambian musician submits a recording, her token carries her decision about what happens to that recording. When a Cahuilla elder submits a song, her token carries the TK labels she is asserting and her choice about AI training. The Group Policy is the community's voice. Mḗh₁n̥s holds both in tension and produces the most protective outcome. The Release Receipt is the proof that the system honored both. This is not a technical formality. It is how a century of data exploitation ends.

