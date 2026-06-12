---
version: 0.1.0
date: 2026-06-12
status: drafting
jurisdiction: California; Republic of The Gambia
supersedes: none
policyType: module
dependsOnMasterTerms: true
sourceModels:
  - GDPR Article 9 (Special Categories of Personal Data)
  - The Gambia Personal Data Protection and Privacy Act 2025 (working summary — pending counsel confirmation)
  - Illinois Biometric Information Privacy Act (BIPA) (structural reference)
  - ISO/IEC 24745:2022 (Biometric Information Protection)
---

# Audio Recording and Biometric Data Policy

> **Layer 1 — Plain Language Summary**
> **Layer 2 — Full Legal Text**
> **Layer 4 — Attestation Record** (added when `status: active`)

*This document is a draft for lawyer review. It has not been reviewed by legal counsel and does not constitute legal advice. Legal characterizations of The Gambia's Personal Data Protection and Privacy Act (2025) are working assumptions pending counsel confirmation and must not be stated as law in customer-facing or compliance material until confirmed.*

---

## Role Labels

The following role labels define the legal actors in this document. Where domain-based rendering applies, **SITE OWNER** resolves to the public-facing entity for the active domain. All other labels are fixed.

| Label | Legal Definition | Resolved Identity |
|---|---|---|
| **PLATFORM** | The SPARXSTAR technical platform, infrastructure, APIs, processing systems, AI systems, databases, and hosting environment. | SPARXSTAR (always) |
| **PLATFORM OPERATOR** | The legal entity that owns, operates, and is legally responsible for the PLATFORM. | Starisian Technologies, LLC (always) |
| **SITE OWNER** | The public-facing website owner or site operator responsible for the site on the active domain. | SPARXSTAR on Platform Domains (`*.sparxstar.com`); the applicable Client Operator on Mapped Custom Domains |
| **END USER** | The visitor, user, customer, attendee, buyer, contributor, or other natural person accessing and using the site or service. | Varies by domain and context |
| **CONTRIBUTOR** | An END USER who submits audio recordings, voice samples, or other acoustic content to the Platform. | Subset of END USER |
| **SERVICE PROVIDER** | Any third-party contractor, subcontractor, vendor, processor, cloud host, AI provider, transcription provider, or acoustic processing service engaged by PLATFORM OPERATOR or SITE OWNER to perform backend functions. | Varies |

> **Rendering note:** On Platform Domains (`*.sparxstar.com` and other Company-operated domains), SITE OWNER and PLATFORM OPERATOR are both Starisian Technologies, LLC. On Mapped Custom Domains, SITE OWNER resolves to the Client Operator for the end-user-facing layer; PLATFORM and PLATFORM OPERATOR remain unchanged.

### Defined Term Cross-Reference

| Term in Full Legal Text | Role Label Equivalent |
|---|---|
| "the Company" / "Company" | PLATFORM OPERATOR (Starisian Technologies, LLC) |
| "the Platform" / "Platform" | PLATFORM (SPARXSTAR infrastructure) |
| "Client Operator" / "Operator" | SITE OWNER (on Mapped Custom Domains) |
| "User" / "End User" | END USER |
| "Contributor" | CONTRIBUTOR |
| "Service Provider" / "Subprocessor" | SERVICE PROVIDER |

---

## Plain Language Summary

*Layer 1 — Human Readable. Written at Grade 8 reading level. Uses "you" and "we". Short sentences.*

> What this policy means for you.

**What we do:** We process voice recordings to support language documentation and transcription services, and we separate what you said (your contribution) from the recording itself (the audio file), applying strict rules about how long we keep the audio file.

**What you can do:** You can contribute voice recordings, know exactly what we keep, withdraw your consent at any time, and ask us to destroy the raw audio file while keeping the language contribution you made.

**What is not allowed:** We do not keep a raw audio recording of a child's voice, and we do not keep any adult's voice recording without that person's explicit, informed consent.

---

### Your Voice Is Personal Data

Your voice is unique. Like a fingerprint, it can identify you. That means voice recordings are treated as sensitive personal data — more protected than ordinary information.

We operate language documentation services that rely on voice recordings. We take the sensitivity of voice data seriously. This policy explains how we handle it.

### Two Things at Once: Your Contribution and Your Recording

When you record yourself speaking, two things happen. First, you contribute to a language record — the words, sounds, and meaning you expressed. Second, you create a raw audio file that contains your voice.

We treat these two things differently.

Your **language contribution** — the transcript, translation, alignment, acoustic pattern data, and revision history — is preserved as part of the language record we are building together. This is what makes the work valuable. We do not delete it.

Your **raw audio file** (the recording itself) is treated as a biometric asset. We only keep it if you are a verified adult and you have given us explicit consent to retain it. Otherwise, we process it to extract your language contribution and then destroy the audio file.

### Default: Process and Destroy

For most contributors — everyone whose consent we have not positively confirmed, and all children — we use a "process and destroy" approach.

We receive your recording, extract everything valuable for the language record (transcript, translation, acoustic patterns), and then delete the raw audio file. We keep a record that the file was destroyed. We never keep a raw recording of a child's voice.

### Vault Retention: Only With Explicit Consent

If you are a verified adult and you give us explicit consent for biometric retention, we can retain your audio file in a secure vault. Even then, your identity is stored separately from your recording. We serve the audio only through temporary, expiring links. We never expose a permanent link to your raw audio.

You can withdraw this consent at any time. When you do, we will destroy the stored audio file and add a destruction record.

### What We Do Keep (Always)

Whether your audio is destroyed or retained, we always preserve:

- The transcript and translation of what you said
- Acoustic pattern data (pitch, tone, rhythm — features designed to support language learning tools without recreating your voice; whether this data qualifies as biometric data under applicable law is subject to legal review — see the Full Legal Text, Section 7.4)
- Metadata about when and how the contribution was made
- A record of what consents you gave and when
- If your audio was destroyed: a destruction receipt that proves it was deleted

This is your language contribution. It stays part of the record.

### Children and Young People

We treat any contributor whose age we cannot verify as a minor. We never store a raw voice recording of a child. We never use a child's voice for AI training.

A child may contribute to a language record. Their words and sounds matter. But the audio file is processed and destroyed. The language contribution remains.

### Your Rights

Depending on where you live, you may have rights including:

- The right to know what data we hold about you
- The right to access your data
- The right to correct inaccurate data
- The right to withdraw consent and have your audio file destroyed
- The right to object to certain types of processing
- The right to a human review of automated decisions that affect you significantly

To exercise any of these rights, contact us at the address in Section 14 of the Full Legal Text.

### AI Training

We only use audio recordings for AI model training if you have separately and explicitly consented to that use. Acoustic pattern data extracted from destroyed recordings is not used for AI training in a way that could reconstruct or identify you. The language contribution (text-based data) may be used for language model training subject to the terms of the AI Chat and AI Use Policy and your consent settings.

---

## Full Legal Text

> This section is the legally binding policy text. In the event of any conflict between this section and the Plain Language Summary above, this section governs.

---

### 1. Definitions

For the purposes of this Policy, the following definitions apply:

**"Acoustic Blueprint"** means an acoustic feature representation extracted from a Voice Recording, comprising pitch contour, nasalization coefficient, vowel formants, and per-token duration data, designed to support phonetic modeling without reconstituting the underlying Voice Recording or identifying the Contributor; whether an Acoustic Blueprint constitutes Biometric Data under applicable law depends on its re-identifiability characteristics and is subject to legal review as described in Section 7.4.

**"Biometric Data"** means personal data resulting from specific technical processing relating to the physical characteristics of a natural person that allows or confirms the unique identification of that person, including voice recordings, acoustic biometrics, and derived acoustic patterns that individually or in combination can identify a natural person.

**"Company"** means Starisian Technologies, LLC, and its affiliates, subsidiaries, and authorized operators.

**"Consent Reference"** means an opaque pointer to a consent record held in the upstream consent management system (Helios), comprising an opaque consent identifier, a rotating pseudonymous subject identifier, a verified-adult flag, a biometric retention consent flag, an AI training consent flag, and a consent resolution timestamp. The Consent Reference contains no directly identifying personal data.

**"Contribution"** means the language data derived from a Voice Recording and preserved as part of the Platform's language corpus, including but not limited to: transcripts, translations, alignment data, Acoustic Blueprints, revision history entries, confidence metadata, and Destruction Receipts.

**"Contributor"** means any User who submits a Voice Recording to the Platform.

**"Destruction Receipt"** means an append-only, permanent audit record attesting to the destruction of a Voice Recording Carrier, including: the recording identifier, a cryptographic hash of the destroyed bytes, the destruction timestamp, the identifiers of jobs that processed the Carrier prior to destruction, the reason for destruction, and a pointer to the canonical derivative.

**"DVE"** means the Data Validation and Enforcement governance layer of the Platform, which enforces content classification, retention rules, and consent policy.

**"Ephemeral Retention"** means a Retention Class under which the Voice Recording Carrier is destroyed immediately upon completion of all authorized processing jobs, or upon expiry of the maximum processing TTL, whichever occurs first.

**"Platform"** means all websites, applications, APIs, and services operated by the Company, including SPARXSTAR, AIWA, and associated Starisian Technologies properties.

**"Retention Class"** means the classification assigned to a Voice Recording at intake that governs the retention and destruction of the Carrier. Valid values are "Ephemeral," "Vault," and "Transient Processing."

**"Transient Processing"** means a Retention Class applicable to any Voice Recording that is in-flight between upload and completion of processing jobs, applicable to both Ephemeral and Vault Carriers during processing. Carriers in Transient Processing are retained only as long as a dependent processing job requires them and are swept on a maximum processing TTL.

**"User"** means any individual or entity that accesses, registers with, or uses the Platform in any capacity.

**"Vault Retention"** means a Retention Class under which a Voice Recording Carrier from a verified adult Contributor who has given explicit biometric retention consent is retained in a secure, identity-decoupled store, accessible only via time-limited access URLs.

**"Voice Recording"** means any audio recording of a human voice submitted to the Platform by or on behalf of a Contributor, including field recordings, game-session audio, scholarly recordings, archive imports, and pure-vocalization samples.

**"Voice Recording Carrier"** or **"Carrier"** means the raw audio file constituting a Voice Recording, as distinct from the Contribution derived from it.

---

### 2. Scope and Applicability

**2.1** This Policy applies to all Voice Recordings submitted to the Platform and to all Biometric Data derived from Voice Recordings, regardless of the submission method, source type, or Platform feature used.

**2.2** This Policy applies to all Contributors globally, subject to the jurisdiction overlays in Section 13.

**2.3** This Policy is incorporated by reference into the SPARXSTAR Master Terms of Service. Acceptance of the Master Terms of Service constitutes acceptance of this Policy.

**2.4** This Policy supplements the Platform's Privacy Policy and Consent Policy. In the event of conflict between this Policy and the Privacy Policy or Consent Policy regarding Voice Recordings and Biometric Data, this Policy governs.

**2.5** Client Operators who enable Platform audio features on Mapped Custom Domains are bound by this Policy and may not configure their integration in a manner that reduces Contributor protections below the standards established here.

---

### 3. Retention Class Framework

**3.1 Default Retention Class.** The default Retention Class for all Voice Recordings is Ephemeral. A Voice Recording is assigned Ephemeral Retention unless the Platform has positively resolved, at the time of intake, all of the following conditions:

(a) the Contributor is a verified adult (age verification performed by the upstream identity and consent management system);

(b) the Contributor has given explicit, informed, affirmative biometric retention consent; and

(c) the consent resolution is current (not expired, not revoked).

Absence of a positive resolution on any condition results in Ephemeral Retention. The Platform fails closed to Ephemeral.

**3.2 Vault Retention.** A Voice Recording may be assigned Vault Retention only when all conditions in Section 3.1 are positively resolved. Vault Carriers are retained in a secure, identity-decoupled store. Access to a Vault Carrier is provided only through time-limited access URLs issued by the Platform's vault access service. No permanent audio path or direct file reference is exposed through any Platform API, endpoint, or user interface.

**3.3 Transient Processing.** All Voice Recordings, regardless of their assigned Retention Class, are classified as Transient Processing while in-flight between upload and completion of all dependent processing jobs. Carriers in Transient Processing are retained only on storage infrastructure that is not web-accessible, and are subject to the maximum processing TTL defined in Section 4.3.

**3.4 Retention Class Immutability at Intake.** The Retention Class assigned at intake governs the Carrier throughout its lifecycle. The Platform does not upgrade a Carrier from Ephemeral to Vault based on consent events that occur after intake. A new submission is required to apply a Vault Retention Class.

---

### 4. Carrier Destruction

**4.1 Ephemeral Destruction Obligation.** For Voice Recordings assigned Ephemeral Retention, the Platform must destroy the Carrier as soon as all dependent processing jobs have reached a terminal state (completed or permanently failed). A processing job that fails does not defer destruction: the Carrier is destroyed regardless, the Destruction Receipt records which processing jobs completed prior to destruction, and if no lawful derivative was produced, the asset is flagged for manual review. Indefinite retention of an Ephemeral Carrier is not permitted under any operational circumstance.

**4.2 Vault Destruction on Consent Withdrawal.** For Voice Recordings assigned Vault Retention, the Platform must destroy the Carrier upon receipt of a valid consent withdrawal or account deletion request, subject to the same constraints on technical feasibility as set out in the AI Chat and AI Use Policy §6.5.1 for dataset license survival. A Destruction Receipt is issued upon destruction.

**4.3 Maximum Processing TTL.** The Platform maintains a scheduled sweep process that destroys any Ephemeral or Transient Processing Carrier that has exceeded the maximum processing TTL, regardless of processing job state. The maximum processing TTL is a platform configuration parameter set by the Company and must not exceed the period reasonably necessary for completion of authorized processing under normal operating conditions. The TTL sweep is a backstop mechanism; it reduces but does not replace dependency-gated destruction under Section 4.1.

**4.4 Destruction Receipts.** The Platform must issue a Destruction Receipt for every destroyed Carrier. Destruction Receipts are append-only records and are never deleted. The Destruction Receipt is part of the Contribution and is preserved as a permanent audit artifact.

**4.5 Destruction Standard.** App-layer deletion of a Carrier must render the Carrier unreadable. The Company acknowledges that app-layer deletion alone may not constitute provable secure erasure on copy-on-write, snapshotted, or backed-up infrastructure. Prior to enabling Vault Retention for any Contributor, the Platform must implement either: (a) storage architecture that ensures Carriers never durably reach shared disk in cleartext; or (b) encryption-at-rest with a per-Carrier key that is destroyed immediately upon processing completion, such that key destruction constitutes data destruction. This is a go/no-go gate for Vault Retention enablement.

---

### 5. Minors and Unverified Contributors

**5.1 Absolute Prohibition on Minor Carrier Retention.** No Voice Recording Carrier of a minor Contributor may be retained beyond the completion of authorized processing. This rule applies regardless of: any consent provided by a parent, guardian, or third party; any Operator configuration; any API access; or any other purported permission. This is a platform safety rule. It is not contingent on any specific statutory requirement, although it is designed to be consistent with the conservative legal posture described in Section 13.

**5.2 Age Verification.** Age verification is performed by the upstream identity and consent management system. The Platform treats any Contributor whose verified-adult status has not been positively resolved as a minor for purposes of this Policy and applies Ephemeral Retention.

**5.3 No AI Training on Minor Recordings.** No Voice Recording Carrier, Acoustic Blueprint, or other Biometric Data derived from a minor Contributor may be used for AI model training.

**5.4 Contribution Preservation.** The prohibition on Carrier retention in Section 5.1 does not apply to the Contribution derived from a minor's Voice Recording. The transcript, translation, alignment data, and other language data derived from a minor's contribution may be preserved as part of the Platform's language corpus in accordance with the Platform's consent framework, subject to applicable law and the terms of the Consent Policy.

---

### 6. Identity Decoupling

**6.1 No Co-location of Identity and Carrier.** Contributor identity — including any pseudonymous identifier — must not be stored in the same database table, storage bucket, or data store as a Voice Recording Carrier or Acoustic Blueprint. Voice Recording assets are keyed by recording identifier and dialect metadata only.

**6.2 Pseudonymous Subject References.** Any reference from a Contribution to a natural person is mediated through the Consent Reference, using a rotating pseudonymous subject identifier whose mapping to a real identity is maintained exclusively by the upstream consent management system. The Platform stores only the opaque Consent Reference identifier, not the subject's name, contact information, device identifier, or other directly identifying data alongside audio or acoustic data.

**6.3 Game and Anonymous Source Payloads.** For Voice Recordings submitted through game interfaces and other anonymous source paths, no identity is associated with the recording at all. The Platform uses only an install-scoped ephemeral token for spam filtering purposes, which does not map to any persistent identity.

**6.4 Processing Pipeline Isolation.** Job descriptors, processing queue entries, and processing result records associated with a Voice Recording must carry only the opaque recording identifier and the opaque Consent Reference identifier. They must not carry the pseudonymous subject identifier, the verified-adult flag, the biometric retention consent flag, or any other personal data from the Consent Reference.

**6.5 No Permanent Audio Access Endpoints.** The Platform must not expose any API endpoint, webhook, or user interface surface that returns a filesystem path, a direct file URL, or any other permanent reference to a Voice Recording Carrier. Access to Vault Carriers is provided exclusively through time-limited access URLs as described in Section 3.2.

---

### 7. Acoustic Blueprints

**7.1 Purpose and Scope.** An Acoustic Blueprint is an acoustic feature representation extracted from a Voice Recording, designed to support phonetic modeling, prosody learning, and tone-sandhi analysis for the Platform's language learning and corpus-building services without reconstituting the underlying Carrier. The legal characterization of Acoustic Blueprints as non-biometric is subject to the limitation in Section 7.4.

**7.2 Extraction Obligation for Ephemeral Carriers.** For Voice Recordings assigned Ephemeral Retention, Acoustic Blueprint extraction must be completed before Carrier destruction. The Acoustic Blueprint becomes the canonical acoustic artifact for the Contribution.

**7.3 Client-Supplied Blueprints.** The Platform may accept Acoustic Blueprints computed by client applications (including game clients) in lieu of a Voice Recording Carrier. A client-supplied Blueprint may be accepted without server-side verification of the underlying Carrier in ephemeral game capture contexts where the Carrier is not transmitted to the Platform. The Platform must not require the Carrier to reach the server for ephemeral game payloads that arrive as Blueprints.

**7.4 Re-identifiability Limitation.** The Company acknowledges that the legal characterization of Acoustic Blueprints as non-biometric depends on the re-identifiability characteristics of the specific feature set used. The Company will seek legal review of the re-identifiability risk of the Acoustic Blueprint feature set in use before making any representations that Acoustic Blueprints fall outside the definition of Biometric Data under applicable law.

---

### 8. Consent

**8.1 Consent for Biometric Retention.** The Company will obtain explicit, informed, affirmative consent from each Contributor before assigning Vault Retention to a Voice Recording. Consent for biometric retention is separate from and in addition to any general terms of service acceptance or data processing consent. The Company will present the consent request in plain language at the time the relevant feature is used (just-in-time consent), not buried in sign-up flows.

**8.2 Consent for AI Training.** Consent for biometric retention does not constitute consent for use of Voice Recordings in AI model training. The Company will obtain separate, explicit consent before using a Voice Recording in AI model training. This consent is governed by the AI Chat and AI Use Policy and the Consent Policy.

**8.3 Withdrawal of Consent.** A Contributor may withdraw biometric retention consent at any time through Platform consent settings. Upon a valid withdrawal:

(a) the Platform will assign an Ephemeral Retention class to the affected Carrier and initiate Carrier destruction under Section 4.2;

(b) the Platform will cease using the affected Contributor's Voice Recordings for new AI Training corpus creation, to the extent reasonably practicable; and

(c) the Contribution derived from the affected Voice Recordings will not be deleted unless a separate deletion request is made under applicable privacy law.

**8.4 Consent Records.** The Company will maintain records of each consent grant, scope, and withdrawal in the upstream consent management system. The opaque Consent Reference identifier for each Voice Recording provides a link to the consent record. Consent records are not stored alongside Carrier or Blueprint data.

**8.5 Consent Portability.** The Company will, upon request by a Contributor, provide a human-readable summary of the consent records associated with that Contributor's Voice Recordings.

---

### 9. Corpus Export and AI Training Eligibility

**9.1 Export Eligibility Gate.** A Voice Recording or derived data may be included in a corpus export for AI model training only if all of the following conditions are met:

(a) the Contribution has reached a consensus weight at or above the Platform's export threshold, as determined by the revision history and authority weighting system;

(b) the Contributor's AI training consent flag is confirmed as true in the Consent Reference;

(c) the Contribution is not subject to a governance block, TK restriction, or export-eligibility restriction under the Platform's DVE governance layer or the AI Chat and AI Use Policy;

(d) for audio export (TTS-grade corpus): the Carrier is assigned Vault Retention and the Carrier is available; and

(e) for text-only or Blueprint-only export: the Retention Class requirement in (d) does not apply — Ephemeral and Blueprint-only Contributions are eligible for text and acoustic feature export only.

**9.2 No Direct Biometric Export for Ephemeral Assets.** A Voice Recording Carrier that has been destroyed under Ephemeral Retention is not available for audio export under any circumstances. No process, retroactive consent, or retroactive Retention Class change restores a destroyed Carrier.

**9.3 Versioned Corpus Snapshots.** Corpus exports produce versioned, immutable snapshots. AI model training is performed from snapshots, not from live submission data. Snapshot provenance records identify which Contributions, consent states, and Retention Classes were applicable at snapshot time. A snapshot may be revoked as a unit if a consent revocation or data integrity event is discovered after the snapshot was taken.

**9.4 TK and Sacred Content Exclusions.** Voice Recordings subject to TK Red, Sacred, or restricted TK Yellow classification under the DVE governance layer are categorically excluded from corpus export, regardless of consent settings. This exclusion is enforced at the DVE layer and cannot be overridden by Operator configuration or API access.

---

### 10. Data Processing Roles

**10.1 Controller.** The Company acts as data controller in respect of Voice Recordings and Biometric Data submitted directly to Company-operated Platform services.

**10.2 Processor Obligations.** Service Providers that process Voice Recordings or Biometric Data on behalf of the Company act as data processors or subprocessors, as required by applicable law. The Company will seek to maintain data processing agreements or equivalent contractual safeguards with such providers that:

(a) restrict the provider's use of Voice Recordings and Biometric Data to the purpose of delivering the contracted service;

(b) prohibit the provider from using Voice Recordings or Biometric Data for the provider's own model training, product development, or commercial purposes without separate Contributor consent;

(c) require the provider to implement appropriate technical and organizational security measures for Biometric Data;

(d) address cross-border data transfer requirements under applicable law, including standard contractual clauses or equivalent transfer mechanisms where required; and

(e) require the provider to notify the Company promptly upon becoming aware of any unauthorized access to, or loss or destruction of, Voice Recordings or Biometric Data.

**10.3 Client Operator Processing.** Client Operators who integrate Platform audio features through APIs or SDKs do so as independent data controllers in respect of their end-user relationships. Client Operators are responsible for maintaining their own lawful basis for processing and their own consent infrastructure for their end users, which must not reduce protections below the standards of this Policy.

---

### 11. Security

**11.1 Technical Safeguards.** The Company will implement technical and organizational measures appropriate to the sensitivity of Biometric Data, including:

(a) access controls limiting Carrier access to authorized processing systems;

(b) encryption of Carriers at rest and in transit;

(c) audit logging of access to Vault Carriers;

(d) physical and logical isolation of Carrier storage from identity stores; and

(e) periodic review and testing of destruction mechanisms.

**11.2 Breach Notification.** In the event of unauthorized access to, or loss or destruction of, Voice Recordings or Biometric Data, the Company will notify affected Contributors and applicable supervisory authorities in accordance with applicable law.

**11.3 Infrastructure Prerequisites.** The Company acknowledges that certain security assurances depend on infrastructure capabilities that may not be available in all deployment configurations. In particular:

(a) provable secure erasure of Carriers on copy-on-write or snapshotted storage requires infrastructure-level solutions beyond app-layer deletion; and

(b) Vault Retention must not be enabled until the Company can demonstrate either never-durably-written storage architecture or encryption-with-key-destruction for Carriers.

These are operational go/no-go gates, not aspirational goals.

---

### 12. User Rights

**12.1 Rights Available.** Subject to applicable law and the limitations in Section 12.2, Contributors have the following rights regarding their Voice Recordings and Biometric Data:

(a) the right to know what Voice Recordings and Biometric Data the Company holds about them;

(b) the right to access a copy of their Contribution (transcript, Blueprint, consent records, and Destruction Receipts);

(c) the right to correct inaccurate transcripts or metadata;

(d) the right to withdraw biometric retention consent and have the Carrier destroyed under Section 4.2;

(e) the right to request deletion of the Contribution under applicable privacy law, subject to the survival and feasibility limitations in the AI Chat and AI Use Policy §6.5.1; and

(f) the right to a human review of any automated decision that significantly affects the Contributor's rights in relation to their Voice Recording or Contribution.

**12.2 Limitations.** Destruction of a Carrier under this Policy does not require the Company to delete the Contribution, except to the extent required by a valid data deletion request under applicable privacy or data protection law and subject to the technical feasibility and proportionality limitations in the AI Chat and AI Use Policy §6.5.1. Nothing in this Policy limits any non-waivable right a Contributor holds under applicable law.

**12.3 Exercising Rights.** To exercise any right under this Section, a Contributor must submit a request to the contact identified in Section 14. The Company will respond within the time period required by applicable law.

---

### 13. Jurisdiction Overlays

**13.1 Governing Law.** This Policy is governed by the laws of the State of California, United States, without regard to its conflict-of-law provisions, except to the extent mandatory provisions of another jurisdiction's law apply to a particular Contributor.

**13.2 The Gambia Overlay.** Platform operations involving Voice Recordings collected from Contributors located in the Republic of The Gambia are subject to the data protection framework applicable in The Gambia. Public summaries of The Gambia's Personal Data Protection and Privacy Act (2025) indicate that it treats biometric data as sensitive personal data and grants rights including erasure, objection, transparency, data protection impact assessments, and breach notification. This characterization is a working assumption pending legal counsel confirmation. Any obligation under this Policy that applies "as required by applicable law" encompasses obligations under The Gambia's framework as confirmed by qualified counsel.

**13.3 European Union and United Kingdom Overlay.** To the extent the Platform processes Biometric Data of individuals located in the European Economic Area or the United Kingdom, such processing is subject to the General Data Protection Regulation (GDPR) or UK GDPR as applicable. Biometric Data as defined in this Policy constitutes a special category of personal data under GDPR Article 9. The Company will maintain a lawful basis for processing such data, conduct data protection impact assessments where required, and comply with applicable transfer restrictions.

**13.4 United States State Law Overlay.** To the extent the Platform processes Biometric Data of individuals whose rights are governed by U.S. state biometric privacy statutes (including the Illinois Biometric Information Privacy Act and equivalent state laws), the Company will comply with the notice, consent, retention, and destruction requirements of those statutes. The Platform's Retention Class framework and Destruction Receipt mechanism are designed to support compliance with such statutes.

**13.5 Jurisdiction-Specific Overlays.** Detailed jurisdiction-specific modifications to this Policy will be maintained in overlay documents as they are developed. Until such overlays are published, this Section provides the binding jurisdictional framework.

---

### 14. Changes to This Policy

The Company reserves the right to amend this Policy at any time. Material changes — including changes to the Retention Class framework, destruction obligations, or consent requirements — will be communicated to Contributors by platform notification and email to the address associated with their account, with a minimum notice period of thirty (30) days before the change takes effect. Continued use of Platform audio features after the effective date of a change constitutes acceptance of the updated Policy.

---

### 15. Contact

Questions regarding this Policy, including requests to exercise rights under Section 12, may be directed to:

**Starisian Technologies, LLC**
Legal Department
[Contact method — to be completed before publication]

---

## Attestation Record

*Layer 4 — Added when `status` is promoted to `active`. Do not populate during drafting or review.*

| Field | Value |
|---|---|
| Version | — |
| SHA-256 Hash | — |
| Attested Date | — |
| Attestation Method | — |
| Attested By | — |

---

*This document is a draft for lawyer review. It has not been reviewed by legal counsel and does not constitute legal advice. Legal characterizations of applicable statutes — including The Gambia's Personal Data Protection and Privacy Act (2025), GDPR, and U.S. state biometric privacy laws — are working assumptions pending counsel confirmation and must not be cited as verified legal authority in customer-facing or compliance material until confirmed.*
