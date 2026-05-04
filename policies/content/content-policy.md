---
version: 0.1.0
date: 2026-04-18
status: drafting
jurisdiction: California
supersedes: none
policyType: module
dependsOnMasterTerms: true
sourceModels:
  - YouTube Terms of Service
  - OpenAI Usage Policy
  - Local Contexts TK Labels
---

# Content Policy

> **Layer 1 — Plain Language Summary**
> **Layer 2 — Full Legal Text**
> **Layer 4 — Attestation Record** (added when `status: active`)

*This document is a draft for lawyer review. It has not been reviewed by legal counsel and does not constitute legal advice.*

---


## Role Labels

The following role labels define the legal actors in this document. Where domain-based rendering applies, **SITE OWNER** resolves to the public-facing entity for the active domain. All other labels are fixed.

| Label | Legal Definition | Resolved Identity |
|---|---|---|
| **PLATFORM** | The SPARXSTAR technical platform, infrastructure, APIs, processing systems, AI systems, databases, and hosting environment. | SPARXSTAR (always) |
| **PLATFORM OPERATOR** | The legal entity that owns, operates, and is legally responsible for the PLATFORM. | Starisian Technologies, LLC (always) |
| **SITE OWNER** | The public-facing website owner or site operator responsible for the site on the active domain. | SPARXSTAR on Platform Domains (*.sparxstar.com); the applicable Client Operator on Mapped Custom Domains |
| **END USER** | The visitor, user, customer, attendee, buyer, or other natural person accessing and using the site or service. | Varies by domain and context |
| **SERVICE PROVIDER** | Any third-party contractor, subcontractor, vendor, processor, cloud host, AI provider, payment processor, logistics provider, shipper, printer, moderation service, or support provider engaged by PLATFORM OPERATOR or SITE OWNER to perform backend functions. | Varies |

> **Rendering note:** On Platform Domains (`*.sparxstar.com` and other Company-operated domains), SITE OWNER and PLATFORM OPERATOR are both Starisian Technologies, LLC, and PLATFORM is SPARXSTAR. On Mapped Custom Domains, SITE OWNER resolves to the Client Operator for the end-user-facing layer; PLATFORM and PLATFORM OPERATOR remain unchanged.
>
> In clauses that assign legal responsibility to a specific named entity, the full legal name (Starisian Technologies, LLC) is used in lieu of the PLATFORM OPERATOR label.

### Defined Term Cross-Reference

The following cross-reference maps terms used in the Full Legal Text to their Role Label equivalents:

| Term in Full Legal Text | Role Label Equivalent |
|---|---|
| "the Company" / "Company" | PLATFORM OPERATOR (Starisian Technologies, LLC) |
| "the Platform" / "Platform" | PLATFORM (SPARXSTAR infrastructure) |
| "Client Operator" / "Operator" | SITE OWNER (on Mapped Custom Domains) |
| "User" / "End User" | END USER |
| "Subcontractor" | SERVICE PROVIDER |

---
> **Content note:** PLATFORM OPERATOR enforces content standards at the PLATFORM layer on all domains. SITE OWNER may impose supplemental content rules on their site but may not override PLATFORM-level prohibitions.

---

## Plain Language Summary

*Layer 1 — Human Readable. Written at Grade 8 reading level. Uses "you" and "we". Short sentences. No passive voice where avoidable.*

> What this policy means for you.

> **Who is "we" in this document?**
> **"We"** and **"us"** in this Content Policy refer to **PLATFORM OPERATOR** (Starisian Technologies, LLC) enforcing content standards at the PLATFORM layer.
> On Mapped Custom Domains, SITE OWNER may impose supplemental content rules, but may not override PLATFORM-level prohibitions.

**What PLATFORM OPERATOR does:** PLATFORM OPERATOR establishes and enforces the rules about what content may exist on the PLATFORM and how it may be used.

**What you can do:** END USERS and SITE OWNERS may submit, publish, and distribute content that they have the rights to and that complies with this policy.

**What is not allowed:** Content that is illegal, abusive, rights-infringing, mislabeled, or classified as restricted without proper authorization.

---

### What Content Can You Submit?

You can submit content you created yourself. You can also submit content you have the legal right to upload — for example, if you have a license from the copyright owner. Before you submit anything, ask yourself: "Do I have the right to put this here?" If the answer is no or you are not sure, do not submit it.

We need accurate information about your content. When you upload music, text, images, or other works, you must tell us the correct artist name, title, language, and origin. Inaccurate metadata can cause problems for rights holders and communities. We may reject or remove content with false or missing metadata.

### What Is Not Allowed?

Some content is absolutely not allowed, no matter what. This includes child sexual abuse material, content designed to cause physical harm, content that promotes genocide, content that impersonates others in a harmful way, and content that violates the law. We will remove this content and may report it to authorities.

Other content is not allowed because it infringes on someone else's rights. If you upload music, images, or text that belongs to someone else and you do not have a license, we may remove it. If we get a formal copyright complaint, we must respond to it.

### The TK Label System

Some content comes from cultural communities and traditional knowledge. We use three labels:

- **TK Green** means the community has said this content is open for sharing on the platform with proper credit.
- **TK Yellow** means the content is restricted. A community representative must review and approve how it is used.
- **TK Red** means the content is sacred or closed. A designated elder or sacred authority must authorize any platform use. We will not put TK Red content on the platform without that authorization. We will not use it to train AI systems. We will not sell it or license it commercially.

### How We Process Your Content

When you submit content to the platform, we may analyze it. For some services — especially those connected to AI West Africa (AIWA) and our language platform — analyzing the words and meanings in your content is a required part of the service. This is called word extraction and meaning analysis. Words themselves are not owned by us. But if we build a structured database from many works — combining words, meanings, contexts, and relationships — that database is our property.

### AI Training

Standard content you submit may be used to improve our AI systems, subject to your consent settings. However, TK Red, sacred, and restricted TK Yellow content will never be used for AI training — no matter what. These protections are hard-coded into our system.

### How to Appeal

If we remove your content and you believe it was a mistake, you can appeal. Instructions for appealing are available in your account settings under "Content Decisions."

---

## Full Legal Text

*Layer 2 — Legally Enforceable. In the event of any conflict between this section and the Plain Language Summary above, this section governs.*

---

### 1. Definitions

For the purposes of this Content Policy, the following definitions apply:

**1.1 "AI-Generated Content"** means any content — including text, images, audio, video, code, or other expressive or functional material — that is produced in whole or in substantial part by an artificial intelligence system, including large language models, image generation models, audio synthesis systems, and similar computational tools, whether or not combined with human editing or curation.

**1.2 "AI Training"** means the use of content as input data for the purpose of training, fine-tuning, evaluating, or improving machine learning models, neural networks, or other artificial intelligence systems.

**1.3 "Attribution"** means the crediting of the author, creator, community of origin, or rights holder in a manner that is accurate, appropriately prominent, and consistent with the applicable license, cultural protocol, or community requirement.

**1.4 "Client Operator" or "Operator"** means any business or individual entity that has entered into a separate agreement with the Company to deploy, configure, or brand a Platform instance or subdomain.

**1.5 "Company"** means Starisian Technologies, LLC, a California limited liability company.

**1.6 "Content"** means any data, information, material, or communication submitted to, stored on, transmitted through, displayed on, or generated by the Platform, including but not limited to: text, audio recordings, musical compositions, sound recordings, audiovisual works, images, photographs, graphics, video, code, documents, metadata, tags, annotations, translations, transcriptions, and structural or semantic representations derived therefrom.

**1.7 "Derivative Work"** means a work that is based upon one or more pre-existing works, including but not limited to: translations, musical arrangements, dramatizations, fictionalizations, motion picture versions, sound recordings, art reproductions, abridgments, condensations, or any other form in which a work may be recast, transformed, or adapted, as defined under 17 U.S.C. § 101 and applicable intellectual property law.

**1.8 "DVE Governance"** means the Platform's Dynamic Values Enforcement system, the technical layer that operationalizes content classifications, consent records, and policy rules as automated access controls, processing permissions, and distribution restrictions.

**1.9 "Metadata"** means structured descriptive, administrative, or rights-related data associated with a piece of Content, including but not limited to: title, authorship, performer credits, genre, language, geographic origin, date of creation, ISRC codes, ISWC codes, ISBN codes, rights ownership information, licensing terms, TK labels, and any other identifiers or descriptors attached to or associated with the Content.

**1.10 "Platform"** means the SPARXSTAR platform infrastructure, services, APIs, applications, and associated services operated by Starisian Technologies, LLC.

**1.11 "Platform Content"** means Content generated, produced, curated, or published by the Company or its licensees in the Company's capacity as a platform operator, including structured datasets, semantic mappings, curated lexicons, editorial curation, and AI-generated outputs produced by Platform systems.

**1.12 "Prohibited Content"** means any Content falling within the categories enumerated in Section 5 of this Policy, the submission, hosting, distribution, or use of which is prohibited under this Policy.

**1.13 "Sacred Content"** means any Content identified as TK Red under the Local Contexts Traditional Knowledge Labels framework, or identified through equivalent community-recognized designation, as holding sacred, ceremonially restricted, or spiritually sensitive status within a cultural community's traditions.

**1.14 "Structured Dataset"** means a systematically organized collection of data points — including word meanings, semantic relationships, content classifications, linguistic mappings, cultural annotations, or other structured representations derived from Content analysis — that is created, curated, compiled, or maintained by the Platform as a distinct proprietary asset.

**1.15 "TK Content"** means any Content associated with Traditional Knowledge, indigenous cultural heritage, oral traditions, traditional ecological knowledge, customary expressions, or community-held cultural heritage that may be subject to communal ownership rights, customary laws, or Traditional Knowledge label designations.

**1.16 "TK Green Content"** means TK Content designated by an Authorized Community Representative or rights-holding individual as open for use on the Platform subject to applicable submission terms and attribution requirements.

**1.17 "TK Red Content"** means TK Content designated as sacred, ceremonially restricted, or closed, the submission, processing, distribution, or commercialization of which requires express prior authorization from a Designated Sacred Authority.

**1.18 "TK Yellow Content"** means TK Content designated as restricted or culturally sensitive, the commercial use, AI processing, or broad distribution of which requires authorization from an Authorized Community Representative.

**1.19 "User"** means any natural person who accesses or uses the Platform, whether through a direct Company-operated interface or through a Client Operator-branded interface.

**1.20 "User Content"** means Content submitted, uploaded, posted, transmitted, or otherwise made available on or through the Platform by a User, excluding AI-Generated Content produced solely by Platform systems without User input.

**1.21 "Word Extraction"** means the process by which the Platform's systems identify, isolate, parse, annotate, and index individual words, morphemes, phrases, or other linguistic units from User Content or AI-Generated Content for purposes including but not limited to: linguistic analysis, language model training, lexicographic database construction, semantic indexing, and translation.

---

### 2. Scope and Applicability

**2.1 General Scope.** This Content Policy governs all Content submitted to, hosted on, processed by, distributed through, or generated on the Platform. It applies to all Users, Client Operators, and third parties who interact with Content through Platform systems.

**2.2 Distinction from Community Policy.** This Policy governs what Content may exist on the Platform and how Content may be used. The Community Policy governs behavioral conduct between Users. Both policies apply concurrently. Content that violates this Policy may be removed regardless of whether the User's conduct also violates the Community Policy.

**2.3 Operator Scope.** Client Operators may implement additional content restrictions for their platform deployments. Client Operators may not reduce below the minimum prohibitions and standards set forth in this Policy. All content submitted through a Client Operator's deployment remains subject to this Policy at the Platform layer.

**2.4 Relationship to Master Terms.** This Policy supplements and is incorporated into the Master Terms of Service. In the event of conflict, the Master Terms of Service govern.

---

### 3. Content Eligibility Requirements

**3.1 Rights and Authorization Requirement.** Users may submit only Content: (a) that they created themselves; (b) for which they hold sufficient intellectual property rights to grant the licenses required by the Master Terms of Service and applicable Operator agreements; or (c) for which they have obtained a valid license, permission, or authorization from the rights holder(s) that permits submission to the Platform on the applicable terms.

**3.2 Representation Upon Submission.** By submitting Content to the Platform, the User represents and warrants that: (a) the User has the right to submit the Content under the applicable terms; (b) the Content does not infringe any copyright, trademark, patent, trade secret, right of publicity, privacy right, or other intellectual property or proprietary right of any third party; (c) the Content complies with all applicable laws; and (d) the Content does not fall within any Prohibited Content category.

**3.3 Metadata Accuracy Requirements.** Users must provide accurate and complete Metadata for submitted Content, including: (a) correct artist, author, performer, or creator name(s); (b) correct title; (c) correct language of performance or composition; (d) correct geographic origin where applicable; (e) accurate rights ownership information; and (f) applicable TK label designations where the Content involves Traditional Knowledge.

**3.4 Consequences of Inaccurate Metadata.** Submission of Content with materially false, misleading, or incomplete Metadata constitutes a violation of this Policy and the Master Terms of Service. The Platform may reject, remove, or restrict content submitted with inaccurate Metadata, suspend the submitting User's account, and pursue any other remedies available under the applicable agreements.

**3.5 Context and Meaning Requirements.** For Content submitted to Platform services that include linguistic analysis, semantic processing, or AI-assisted indexing — including all AIWA-aligned services — Users must provide sufficient contextual information to enable accurate processing and classification. Content submitted without adequate context may be processed less accurately, subject to default restrictive classification, or returned to the User for additional information.

**3.6 TK Content Eligibility.** TK Content is subject to the authorization requirements set forth in Sections 7 and 8 of this Policy in addition to the general eligibility requirements of this Section.

---

### 4. Platform License for Submitted Content

**4.1 License Grant.** By submitting User Content to the Platform, the User grants to the Company and its applicable Client Operators a non-exclusive, royalty-free (unless otherwise specified in applicable Operator agreements), worldwide, sublicensable (to the extent necessary for Platform operation and as further specified herein), transferable (in connection with a corporate transaction involving the Company) license to: host, store, reproduce, distribute, perform, display, transmit, index, translate, analyze, process, create derivative works of, and otherwise use the User Content for the purpose of operating, improving, and providing the Platform and related services.

**4.2 Scope of License.** Without limiting Section 4.1, the Platform license includes the right to: (a) create and maintain Structured Datasets derived from User Content; (b) perform Word Extraction and linguistic analysis; (c) create semantic mappings, lexicographic annotations, and metadata structures derived from User Content; (d) translate User Content where authorized; (e) apply AI systems to User Content subject to applicable Consent settings; (f) promote and market User Content within the Platform and through applicable distribution channels; and (g) sublicense rights to third-party service providers to the extent necessary for Platform infrastructure operation.

**4.3 User Ownership Retained.** The license granted in Section 4.1 does not transfer ownership of User Content to the Company. Users retain ownership of their original works. Nothing in this Policy or the Master Terms of Service shall be construed as a work-made-for-hire arrangement for Content created by standard Users prior to or independently of Platform engagement.

**4.4 Structured Dataset Ownership.** Notwithstanding Section 4.3, Structured Datasets, semantic mappings, curated lexicons, derived analytical outputs, and other Platform-generated representations created from or derived through Platform processing of User Content are proprietary Platform assets belonging to the Company. The inclusion of elements derived from a User's Content in a Structured Dataset does not entitle the User to ownership of or compensation from the Structured Dataset absent a separate agreement.

**4.5 Individual Words.** The Platform does not claim ownership of individual words, morphemes, public language facts, or common linguistic elements extracted from Content. Ownership of Platform assets attaches to Structured Datasets, semantic mappings, curated lexicons, and other organized, curated, or analytically processed collections — not to individual words or phrases in isolation.

---

### 5. Prohibited Content

**5.1 Absolute Prohibitions.** The following categories of Content are absolutely prohibited on the Platform under all circumstances. No exception, license, community authorization, or override exists for these categories:

(a) **Child Sexual Abuse Material (CSAM).** Any sexual or sexualized depiction of minors, as defined under 18 U.S.C. § 2256 and applicable law. The Platform has a zero-tolerance policy for CSAM and will report all known or suspected CSAM to the National Center for Missing and Exploited Children (NCMEC) and applicable law enforcement.

(b) **Non-Consensual Intimate Imagery (NCII).** Images, video, or other intimate depictions of identifiable individuals distributed without the subject's consent, including so-called "revenge pornography" and non-consensual deepfake intimate imagery.

(c) **Content Facilitating Violence or Terrorism.** Content that facilitates, incites, instructs, recruits for, or promotes acts of terrorism, mass violence, or organized violent extremism, including content that glorifies such acts.

(d) **Content Promoting Genocide or Ethnic Cleansing.** Content that promotes, incites, or calls for acts of genocide, ethnic cleansing, or systematic persecution based on race, ethnicity, national origin, religion, or other protected characteristics.

(e) **Content That Violates Applicable Law.** Content that is illegal in the jurisdiction of the Company, the applicable Client Operator, or the User, including but not limited to: content that defames identifiable individuals, violates export control laws, or constitutes criminal conduct.

**5.2 Rights-Infringing Content.** The Platform prohibits: (a) Content that infringes the copyright, trademark, trade secret, patent, or other intellectual property rights of any third party; (b) Content that violates the right of publicity or privacy rights of any identifiable individual; and (c) Content submitted in bad faith to circumvent rights enforcement mechanisms.

**5.3 Fraudulent and Deceptive Content.** The Platform prohibits: (a) Content that impersonates any person, entity, or brand in a manner likely to deceive Users; (b) Content that contains materially false or misleading statements of fact intended to deceive; (c) Metadata submitted with the intent to deceive the Platform or other Users about the origin, ownership, or nature of the Content; and (d) AI-Generated Content represented as human-created work without appropriate disclosure.

**5.4 Malicious Technical Content.** The Platform prohibits: (a) malware, spyware, ransomware, trojans, and other malicious software; (b) phishing materials designed to fraudulently obtain credentials or personal information; (c) code or scripts designed to exploit, disrupt, or attack Platform systems or third-party systems; and (d) technical exploits designed to circumvent Platform security, access controls, or rights management systems.

**5.5 Additional Prohibited Categories.** The Platform reserves the right to designate additional categories of prohibited content by amendment to this Policy, by Platform-specific supplementary terms, or by Client Operator configuration within the limits permitted by applicable law and this Policy.

---

### 6. AI-Generated Content Submissions

**6.1 Eligibility.** AI-Generated Content may be submitted for certain Platform services, subject to the disclosure requirements of this Section and any additional requirements in applicable service terms.

**6.2 Mandatory Disclosure.** Users who submit AI-Generated Content must: (a) accurately label the Content as AI-generated at the time of submission; and (b) not represent AI-generated output as original human-created work in Metadata, promotional materials, or platform listings.

**6.3 Rights in AI-Generated Content.** Users who submit AI-Generated Content represent and warrant that: (a) they have the right to submit the AI-generated output under the applicable AI service's terms of use; (b) the output does not incorporate unlicensed third-party rights; and (c) the output does not constitute Prohibited Content.

**6.4 Platform AI-Generated Content.** Platform Content generated by the Company's own AI systems — including AI-generated structured data, translations, semantic maps, and indexed representations — is owned by the Company as Platform Content. Such outputs do not constitute User Content.

**6.5 Impersonation Prohibition.** AI-Generated Content that replicates the voice, likeness, artistic style, or identity of a real person in a manner that could deceive a reasonable person as to the authenticity or endorsement of the output is prohibited as Fraudulent and Deceptive Content under Section 5.3.

---

### 7. Sacred and Culturally Restricted Content

**7.1 TK Label Framework.** The Platform uses the Local Contexts Traditional Knowledge Labels framework (or a substantially equivalent system) to classify culturally affiliated Content. The three primary classifications are TK Green, TK Yellow, and TK Red, as defined in Section 1.

**7.2 TK Green Content.** TK Green Content is eligible for standard Platform submission under applicable submission terms. Submission requires: (a) accurate attribution to the community of origin; (b) compliance with any specific conditions set by the Authorized Community Representative at the time of authorization; and (c) standard User eligibility requirements under Section 3.

**7.3 TK Yellow Content.** TK Yellow Content is subject to the following requirements: (a) submission requires authorization from an Authorized Community Representative of the relevant cultural community; (b) distribution is restricted to the scope authorized by the community representative; (c) commercial use requires explicit community approval; (d) AI Training is not permitted for TK Yellow Content without express Authorized Community Representative consent; and (e) pending community review, TK Yellow Content is treated as TK Red under the Default Restrictive Behavior standard.

**7.4 TK Red Content.** TK Red Content is subject to the following requirements: (a) submission requires express prior written authorization from a Designated Sacred Authority; (b) the Platform will not accept TK Red Content submissions without verified Designated Sacred Authority authorization documentation; (c) TK Red Content is not eligible for AI Training under any circumstances; (d) the Platform will not commercially exploit TK Red Content; (e) distribution of TK Red Content is limited to the specific scope authorized by the Designated Sacred Authority; and (f) any authorization previously granted by a Designated Sacred Authority may be revoked, with prospective effect, upon written notice.

**7.5 Non-Commercial Rule for TK Red and Restricted Sacred Content.** Notwithstanding any other provision of this Policy or the Master Terms of Service, the Platform will not commercially exploit TK Red Content or Sacred Content. This restriction applies regardless of purported authorization from parties other than a verified Designated Sacred Authority.

**7.6 Student and Documentary Recordings.** As set forth in the Consent Policy, the fact that an individual recorded, documented, filmed, or transcribed Sacred Content does not grant that individual the right to submit or authorize Platform use of that content. Designated Sacred Authorities retain cultural and spiritual authority over Sacred Content independent of the act of documentation.

**7.7 Misclassification.** Deliberate submission of TK Red or TK Yellow Content with a false TK Green or non-TK classification constitutes a material violation of this Policy. The Platform may permanently suspend accounts that engage in deliberate TK misclassification and may seek additional remedies under applicable law and community agreements.

---

### 8. Content Processing and Transformation

**8.1 Platform Processing Rights.** Subject to applicable Consent settings, TK restrictions, and the limitations of this Policy, the Platform may: (a) analyze, index, classify, and organize User Content; (b) translate User Content into other languages; (c) create machine-readable representations of User Content, including transcriptions, structural annotations, and semantic maps; (d) create Derivative Works of User Content for the purpose of providing Platform services, such as summaries, previews, and accessibility formats; (e) perform Word Extraction and linguistic analysis; and (f) build and maintain Structured Datasets incorporating representations derived from User Content.

**8.2 Word Extraction — Mandatory for Certain Services.** For Platform services connected to AIWA and DVE-aligned language systems, Word Extraction and meaning analysis are mandatory components of the service. Users submitting Content to these services consent to Word Extraction as a condition of use. The Platform's rights in extracted individual words are limited as set forth in Section 4.5.

**8.3 Structured Datasets.** Structured Datasets created from or derived through Platform processing of User Content are proprietary Platform assets. The compilation, organization, and curation of linguistic data into a Structured Dataset constitutes original work by the Platform, independent of the individual words or expressions it contains.

**8.4 Translation.** The Platform may translate User Content where the User has granted translation rights or where translation is a condition of the applicable service. Translated versions of User Content created by Platform systems are Platform Content with respect to the translation layer, without affecting User ownership of the underlying original Content.

**8.5 Processing Integrity.** The Platform does not guarantee lossless reproduction of User Content through AI processing pipelines. AI-processed or machine-transformed versions of User Content may differ from the original in form, structure, or completeness. The Platform is not liable for differences arising from AI transformation that occur within the scope of authorized processing.

---

### 9. AI Training Eligibility

**9.1 Standard Content.** User Content that is not TK Content, Sacred Content, or otherwise restricted under this Policy is eligible for use in AI Training, subject to the User's Consent settings as described in the AI Chat and AI Use Policy and the Consent Policy.

**9.2 Opt-Out Mechanism.** Users may opt out of AI Training use of their Content through their account settings. Opt-out applies prospectively to new AI Training runs after the opt-out is recorded. Previously trained model weights are not disaggregated upon opt-out, as disaggregation is not technically feasible at this time.

**9.3 Absolute AI Training Exclusions.** The following categories of Content are categorically excluded from AI Training regardless of User consent settings, Operator configuration, or any other authorization:

(a) TK Red Content;
(b) Sacred Content;
(c) TK Yellow Content pending community review;
(d) TK Yellow Content for which the Authorized Community Representative has not provided express written consent to AI Training;
(e) Content of Minors collected without valid Parental Consent.

**9.4 DVE Enforcement.** AI Training exclusions for TK Red, Sacred, and restricted TK Yellow Content are enforced at the DVE Governance layer and cannot be overridden through Platform configuration, API access, or other technical means.

---

### 10. Rights Clearance for Complex Media

**10.1 Music Submissions.** Users submitting musical Content must hold or have cleared: (a) mechanical rights for the underlying musical composition (if applicable); (b) master recording rights (if submitting a sound recording); (c) sync rights (if submitting audiovisual content incorporating music); and (d) performer rights and artist credits as required by applicable law. Users must provide accurate ISRC codes (for sound recordings) and ISWC codes (for musical compositions) where applicable.

**10.2 Sample Clearance.** User Content that incorporates samples from third-party recordings or compositions must be accompanied by documentation of sample clearance from the relevant rights holders. Uncleared samples constitute rights-infringing Content under Section 5.2.

**10.3 Image and Visual Content.** Users submitting images, photographs, or visual artwork must hold or have cleared: (a) copyright in the image; (b) model release rights for identifiable individuals depicted; and (c) property release rights where legally required.

**10.4 Video Content.** Users submitting video must hold or have cleared all rights in: (a) the underlying audiovisual work; (b) any musical content synchronized to the video; (c) any third-party visuals, clips, or footage incorporated; and (d) any rights of publicity for identifiable individuals.

**10.5 Text and Written Works.** Users submitting written works — including books, articles, poems, lyrics, scripts, and oral history transcriptions — must hold copyright in the submitted work or have a valid license to submit it to the Platform.

---

### 11. Content Removal and Enforcement

**11.1 Grounds for Removal.** The Platform may remove or restrict Content that: (a) falls within any Prohibited Content category; (b) is reported as infringing under the DMCA takedown process (see IP / DMCA Policy); (c) is determined to violate this Policy; (d) lacks required TK authorization; (e) was submitted with materially false Metadata; or (f) is subject to a valid legal order requiring removal.

**11.2 Notice Before Removal.** Where practicable and where not prohibited by law or urgency, the Platform will notify the submitting User of the grounds for removal and the right to appeal before removing Content. For Absolute Prohibited Content (CSAM, terrorism facilitation, and similar categories), removal is immediate and without prior notice.

**11.3 DMCA Process.** Copyright infringement claims are governed by the IP / DMCA Policy, which sets forth the procedures for submitting takedown notices, counter-notices, and the Platform's response obligations under the Digital Millennium Copyright Act.

**11.4 Appeals Process.** Users whose Content has been removed under this Policy (other than for Absolute Prohibited Content) may submit an appeal within thirty (30) days of the removal notice. Appeals must be submitted through the account settings under "Content Decisions" and must state the specific grounds for the appeal. The Platform will review appeals within a commercially reasonable time and notify the User of the outcome.

**11.5 Repeat Infringement.** The Platform will terminate accounts of Users who are repeat infringers of intellectual property rights, in compliance with the Platform's repeat infringer policy under the DMCA.

---

### 12. Relationship to Community Policy

**12.1 Distinct Scope.** This Content Policy governs what Content may exist on the Platform and how it may be used. The Community Policy governs behavioral conduct between Users — how Users treat each other, anti-harassment rules, community standards, and moderation. Both policies apply concurrently.

**12.2 Behavioral Violations Involving Content.** Content submitted as part of a behavioral violation — such as targeted harassment, doxxing, or threats — is subject to both this Policy (for content removal) and the Community Policy (for conduct consequences).

**12.3 Cross-Reference.** Users are encouraged to review both the Content Policy and the Community Policy to understand the full scope of platform rules.

---

### 13. AIWA-Specific Content Rules

**13.1 AI West Africa Integration.** AIWA (AI West Africa) is a Gambian-based publishing and aggregation initiative that operates as part of the SPARXSTAR ecosystem. Content submitted through AIWA-integrated services may be subject to additional processing requirements, including mandatory Word Extraction, language tagging, and linguistic analysis as described in Section 8.2.

**13.2 Language Documentation.** AIWA services prioritize language documentation, cultural heritage preservation, and multilingual content indexing. Content submitted to AIWA-integrated services may contribute to language documentation databases and lexicographic resources subject to applicable consent settings.

**13.3 Cultural Content Standards.** AIWA services impose the full TK Content requirements of this Policy, with particular emphasis on protecting West African and Gambian cultural heritage from unauthorized commercial exploitation.

---

### 14. Governing Law and Jurisdiction

This Policy is governed by the laws of the State of California, United States, without regard to its conflict-of-law provisions.

| Jurisdiction | Overlay Document | Key Modification |
|---|---|---|
| European Union (GDPR) | Pending — overlay document not yet created | Placeholder — drafting required |
| Republic of The Gambia | Pending — overlay document not yet created | Placeholder — drafting required |

---

### 15. Changes to This Policy

The Company reserves the right to amend this Policy at any time. Material changes will be communicated to Users by platform notification and by updating the `date` field in the YAML metadata above. Continued use of the Platform following notice of a change constitutes acceptance of the updated Policy.

---

### 16. Contact

**Starisian Technologies, LLC**
Legal Department
[Contact information — to be completed before publication]

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

*This document is a draft for lawyer review. It has not been reviewed by legal counsel and does not constitute legal advice. All policy documents must be reviewed and approved by qualified legal counsel before publication.*

---

### 17. Disclaimer of Warranty Regarding Content

**17.1 User-Submitted Content.** The Company does not pre-screen all User Content before it is published or distributed on the Platform. The Company makes no representation or warranty regarding the accuracy, legality, appropriateness, or quality of User Content. Presence of Content on the Platform does not constitute endorsement of that Content by the Company.

**17.2 Monitoring Limitations.** The Platform employs automated and human moderation systems to detect Prohibited Content. These systems are not infallible. The presence of Content that violates this Policy does not constitute the Company's approval of, knowledge of, or consent to that Content.

**17.3 Third-Party Content.** The Platform may display or make accessible third-party content through integrations, embeds, links, or aggregation services. The Company is not responsible for third-party content and does not endorse it.

---

### 18. Indemnification

Users agree to indemnify, defend, and hold harmless the Company, its officers, directors, employees, agents, licensors, Client Operators, and successors from and against any and all claims, damages, losses, liabilities, costs, and expenses (including reasonable attorneys' fees) arising from or relating to: (a) User Content submitted to the Platform; (b) breach of the representations and warranties in Section 3.2; (c) violation of any applicable law or third-party right in connection with User Content; or (d) any claim that User Content infringed the rights of a third party.

