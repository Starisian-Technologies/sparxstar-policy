---
version: 0.1.0
date: 2026-04-18
status: drafting
jurisdiction: California
supersedes: none
policyType: module
dependsOnMasterTerms: true
sourceModels:
  - Google Consent Framework
  - OpenAI Disclosure Style
  - GDPR Consent Requirements
---

# Consent Policy

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
> **Consent note:** This document governs PLATFORM-level consent. SITE OWNER consent obligations for their customer relationship are separate and may supplement this policy.

---

## Plain Language Summary

*Layer 1 — Human Readable. Written at Grade 8 reading level. Uses "you" and "we". Short sentences. No passive voice where avoidable.*

> What this policy means for you.

> **Who is "we" in this document?**
> **"We"** and **"us"** in this Consent Policy refer to **PLATFORM OPERATOR** (Starisian Technologies, LLC) administering PLATFORM-level consent.
> On Mapped Custom Domains, SITE OWNER may have separate consent obligations for the end-user relationship. SITE OWNER consent obligations supplement this policy and do not supersede PLATFORM-level consent rules.

**What PLATFORM OPERATOR does:** PLATFORM OPERATOR operates a layered consent system that gives END USERS control over how their data and content are collected, processed, and used.

**What you can do:** END USERS can review, grant, restrict, and withdraw consent at any time through PLATFORM consent settings.

**What is not allowed:** SITE OWNER may not override PLATFORM-level consent defaults or bypass the consent mechanisms required by applicable law.

---

### How Consent Works Here

When you use the SPARXSTAR platform, we need your permission for different things. We always try to ask at the right moment — not buried in pages of sign-up text. This is called "just-in-time" consent: we ask when it matters.

We use four layers to explain what we are asking. The first layer is the simplest — a short icon or audio note. The second is a short plain summary like this one. The third is full legal text below. The fourth layer is the platform's technical system that enforces your choices automatically.

### What We Ask Permission For

We ask your permission for six main things: (1) collecting your data, (2) cookies and tracking tools, (3) using AI to process your content, (4) sending you marketing messages, (5) using content that involves cultural heritage or sacred traditions, and (6) making purchases. For most of these, you can say no and still use the platform in a limited way. For some services, consent is required to proceed.

### Cultural and Sacred Content

Some content on this platform comes from communities and traditions, not just individual people. If content belongs to a cultural community — like a traditional song, a ceremony recording, or sacred knowledge — then the community itself may need to give permission. You cannot give consent for content that belongs to your community unless you are an authorized representative. If content is sacred or ceremonially restricted, only a designated elder or authorized community leader can approve its use. A student recording a ceremony does not override the elder's authority over that knowledge.

We use three labels for this:
- **TK Green** — open for use with standard permission.
- **TK Yellow** — restricted; community review required.
- **TK Red** — sacred or closed; elder authorization required.

### How to Withdraw Consent

You can withdraw any consent you have given at any time by going to your account settings under "Privacy and Consent." Withdrawal does not undo anything that already happened before you withdrew. But we will stop using your data for the purpose you withdrew consent for, going forward.

### When in Doubt, We Restrict

If we are not sure what you have consented to — or if something is unclear — we treat it as the most restricted option. We do not assume permission. We default to protecting your rights and the rights of any community the content belongs to.

---

## Full Legal Text

*Layer 2 — Legally Enforceable. In the event of any conflict between this section and the Plain Language Summary above, this section governs.*

---

### 1. Definitions

For the purposes of this Consent Policy, the following definitions apply:

**1.1 "Agreement"** means these Terms and any other policies, agreements, or documents incorporated by reference into the relationship between the Company, any Operator, and the User.

**1.2 "AI Processing Consent"** means affirmative User consent authorizing the Platform to apply artificial intelligence systems — including machine learning models, natural language processing pipelines, semantic analysis tools, and related computational methods — to User Content or User-generated inputs for purposes including but not limited to: classification, transcription, translation, semantic indexing, sentiment analysis, entity extraction, structured dataset generation, and content recommendation.

**1.3 "Authorized Community Representative"** means an individual formally recognized by a cultural community, indigenous group, or traditional knowledge-holding body as having the authority to grant or withhold consent on behalf of that community with respect to culturally affiliated content, including Traditional Knowledge Content.

**1.4 "Authorized Elder"** means an individual formally recognized within a cultural or traditional knowledge community as holding spiritual, ceremonial, or custodial authority over Sacred Content, including the authority to approve or prohibit the reproduction, distribution, processing, or commercialization of that Sacred Content.

**1.5 "Client Operator" or "Operator"** means any business or individual entity that has entered into a separate agreement with the Company to deploy, configure, or brand a Platform instance or subdomain and to offer Platform-based services to End Users under the Operator's identity.

**1.6 "Company"** means Starisian Technologies, LLC, a California limited liability company, the owner and operator of the Platform infrastructure.

**1.7 "Consent"** means a freely given, specific, informed, and unambiguous indication of a Data Subject's or User's agreement to the processing, use, or sharing of their personal data, content, or rights, expressed by a statement or by a clear affirmative action, as applicable under this Policy.

**1.8 "Consent Record"** means a timestamped, system-generated log entry recording the nature of consent obtained, the method by which it was obtained, the version of the disclosure presented, the identity of the consenting party (to the extent known), and any subsequent modification or withdrawal of that consent.

**1.9 "Consent Withdrawal"** means the unilateral, prospective revocation by a User, Data Subject, or Authorized Community Representative of previously granted Consent, effective upon receipt of a valid withdrawal request by the Platform, without prejudice to processing already completed prior to withdrawal.

**1.10 "Cookie Consent"** means consent, governed by applicable telecommunications and privacy law, to the placement, reading, or use of cookies, pixels, session identifiers, device fingerprints, or other tracking technologies on the User's device for purposes other than strictly necessary platform functionality.

**1.11 "Data Subject"** means any natural person whose personal data is collected, processed, or stored through the Platform, whether or not such person has created an account.

**1.12 "Designated Sacred Authority"** means an Authorized Elder or formally designated ceremonial authority whose express authorization is required before Sacred Content or TK Red Content may be submitted, processed, licensed, or commercially exploited on or through the Platform.

**1.13 "DVE Governance"** means the platform's Dynamic Values Enforcement system, which is the technical enforcement layer that translates consent records, content classifications, and policy rules into automated access controls, processing permissions, and distribution restrictions applied at the system level.

**1.14 "Explicit Consent"** means consent that is specific, unambiguous, and affirmatively confirmed through a positive act (including but not limited to: checking an unchecked checkbox, signing a form, or clicking a clearly labeled affirmative button). Explicit Consent cannot be obtained through pre-checked boxes, implied conduct, or silence.

**1.15 "GDPR"** means Regulation (EU) 2016/679 of the European Parliament and of the Council on the protection of natural persons with regard to the processing of personal data, as amended or superseded.

**1.16 "Implicit Consent"** means consent that the Platform infers from a User's conduct, where such inference is permitted by applicable law and disclosed in advance. Implicit Consent may not be used as a basis for processing sensitive personal data, Sacred Content, TK Yellow Content, TK Red Content, or any category of data or content for which Explicit Consent is required under this Policy or applicable law.

**1.17 "Informed Consent"** means Consent that is preceded by a clear, accurate, and sufficient disclosure of: (a) the identity of the party requesting consent; (b) the specific purpose for which consent is sought; (c) the nature of the data, content, or rights involved; (d) any third parties with whom the data or content may be shared; and (e) the consequences of granting or withholding consent.

**1.18 "Just-in-Time Consent"** means Consent that is solicited and obtained at or immediately prior to the point of action that requires it, rather than obtained in bulk at account registration or through forward consent for future, undefined uses.

**1.19 "Minor"** means any natural person under the age of thirteen (13) years as defined under the Children's Online Privacy Protection Act (COPPA), or such higher age threshold as required by applicable jurisdiction.

**1.20 "Parental Consent"** means verifiable consent provided by a Minor's parent or legal guardian, obtained through a method that reasonably verifies the consenting party's status as a parent or guardian under COPPA and applicable law, authorizing the collection or use of the Minor's personal data.

**1.21 "Platform"** means the SPARXSTAR platform infrastructure, services, APIs, applications, content management systems, and associated services operated by Starisian Technologies, LLC.

**1.22 "Sacred Content"** means any content — including but not limited to: recordings, texts, images, symbols, ceremonies, prayers, or other expressive or documentary works — that a cultural community or Designated Sacred Authority has identified as holding sacred, ceremonially restricted, or spiritually sensitive status within that community's traditions, and which is classified as TK Red under the Local Contexts Traditional Knowledge Labels framework or any substantially equivalent classification system recognized by the Platform.

**1.23 "TK Content"** means any content associated with Traditional Knowledge, including oral histories, traditional songs, craft knowledge, medicinal knowledge, ceremonial practices, visual cultural heritage, indigenous language materials, and other expressions of cultural heritage that may be subject to communal rights, customary laws, or Traditional Knowledge labels.

**1.24 "TK Green Content"** means TK Content that an Authorized Community Representative or rights-holding individual has designated as open for use on the Platform pursuant to applicable submission terms, subject to proper attribution.

**1.25 "TK Red Content"** means TK Content designated as sacred, ceremonially restricted, or closed, requiring express authorization from a Designated Sacred Authority before any Platform submission, processing, distribution, or commercial use is permitted.

**1.26 "TK Yellow Content"** means TK Content designated as restricted, culturally sensitive, or subject to community review, requiring authorization from an Authorized Community Representative before commercial use, AI training, or broad distribution.

**1.27 "User"** means any natural person who accesses or uses the Platform, whether through a direct Company-operated interface or through a Client Operator-branded interface.

---

### 2. Scope and Applicability

**2.1 General Scope.** This Consent Policy governs all Consent interactions arising from or related to use of the Platform, including but not limited to: data collection and processing, cookie deployment, AI processing, marketing communications, commerce transactions, and the submission, use, and processing of TK Content and Sacred Content.

**2.2 Platform-Wide Application.** This Policy applies to: (a) Users accessing the Platform directly through Company-operated domains and subdomains; (b) Users accessing the Platform through Client Operator-branded interfaces; (c) Client Operators in their capacity as deployers of Platform consent mechanisms; and (d) third parties whose data may be submitted to the Platform by Users.

**2.3 Operator Responsibility.** Where the Platform is deployed through a Client Operator's custom domain, the Client Operator bears primary responsibility for ensuring that Consent mechanisms presented to End Users comply with all applicable laws in the jurisdictions where the Operator does business. The Company's Consent infrastructure establishes minimum standards. Client Operators may implement more restrictive consent requirements but may not reduce below the standards set forth in this Policy.

**2.4 Subdomain Default.** Where a User accesses the Platform through a SPARXSTAR-branded subdomain, this Policy and all Company consent mechanisms are primary, and the User's direct counterparty for Consent purposes is the Company.

**2.5 Relationship to Master Terms.** This Policy supplements and is incorporated into the Master Terms of Service. In the event of a conflict between this Policy and the Master Terms of Service regarding Consent obligations, the Master Terms of Service govern.

**2.6 Relationship to Privacy Policy.** This Policy governs how Consent is obtained and recorded. The Privacy Policy governs what data is collected, how it is processed, and how Data Subject rights may be exercised. Both documents apply concurrently.

---

### 3. Consent Architecture — Four Layers

**3.1 Overview.** The Platform employs a four-layer Consent architecture designed to ensure that Users receive disclosure in a form appropriate to their context, device, accessibility needs, and level of engagement with the Platform.

**3.2 Layer A — Icon and Audio Disclosures.** Layer A consists of non-textual notice mechanisms, including privacy icons, visual consent indicators, audio consent disclosures, and accessibility-compliant notifications. Layer A serves to provide initial awareness of data practices to Users regardless of literacy level or reading preference. Layer A disclosures alone do not constitute Informed Consent and are not sufficient for consent to sensitive processing activities.

**3.3 Layer B — Plain Language Summaries.** Layer B consists of plain language summaries written at an accessible reading level. Layer B disclosures identify the party requesting consent, describe the purpose of the proposed processing in plain terms, summarize the User's key rights, and present the consent mechanism in a clear and usable format. Layer B summaries are displayed at the point of Consent solicitation and are stored with the corresponding Consent Record.

**3.4 Layer C — Full Legal Text.** Layer C consists of the binding legal text set forth in this Policy and in any applicable supplementary Consent notice. Layer C governs the legal effect of Consent. In the event of any inconsistency between Layer B summaries and Layer C legal text, Layer C governs.

**3.5 Layer D — DVE Governance Enforcement.** Layer D is the Platform's technical enforcement system. Upon recording of a Consent or Consent Withdrawal, the DVE Governance system automatically updates access permissions, processing authorizations, distribution restrictions, and data handling rules applicable to the relevant User, content, or dataset. Layer D does not substitute for legal Consent; it operationalizes Consent records in the platform's technical architecture.

---

### 4. Consent Types and Requirements

**4.1 Data Collection Consent.**

(a) The Platform collects personal data as described in the Privacy Policy. Consent to data collection is required for data processing activities that are not otherwise authorized by law (such as legitimate interest or contractual necessity), as specified in the Privacy Policy.

(b) Consent to data collection is Explicit Consent. Users must affirmatively select or confirm their consent choices. Pre-checked boxes, assumed consent from continued use alone, and silence do not constitute valid data collection consent for purposes requiring Explicit Consent.

(c) Consent to data collection may be granted on a purpose-specific basis. Users may consent to certain data collection purposes while declining others, subject to the limitation that certain data collection is necessary for platform functionality and cannot be declined without affecting access.

**4.2 Cookie and Tracking Consent.**

(a) Strictly necessary cookies — those required for basic platform functionality, security, and session integrity — are deployed without separate consent, as disclosed in the Cookie Policy.

(b) Non-essential cookies and tracking technologies — including analytics cookies, behavioral tracking pixels, advertising identifiers, and preference cookies — require opt-in Consent before deployment. The Platform will not deploy non-essential cookies until affirmative Cookie Consent is obtained.

(c) Cookie Consent is obtained through the Platform's cookie consent banner and preference center, presented to new Users and to returning Users upon material changes to cookie practices. The banner presents Layer A and Layer B disclosures. Full details are available in the Cookie Policy (Layer C).

(d) Users may modify or withdraw Cookie Consent at any time through the cookie preference center accessible from all platform pages.

**4.3 AI Processing Consent.**

(a) The Platform may apply AI systems to User Content and User inputs for the purposes described in the AI Chat and AI Use Policy. AI Processing Consent governs this use.

(b) AI Processing Consent is Explicit Consent. Users must affirmatively authorize AI processing beyond what is strictly necessary for core platform functionality.

(c) AI processing for the purpose of training machine learning models requires separate, distinguishable consent from AI processing for inference and real-time feature delivery.

(d) AI Processing Consent for TK Yellow Content requires authorization from an Authorized Community Representative in addition to, or in substitution of, individual User consent. AI Processing Consent for TK Red Content and Sacred Content is not available; such content is excluded from AI processing pursuant to Section 6.4.

(e) Upon withdrawal of AI Processing Consent, the Platform will cease applying AI training pipelines to the User's content prospectively. Previously generated model weights are not affected by withdrawal, as disaggregation of individual contributions from trained model weights is technically infeasible at the time of this drafting.

**4.4 Marketing Communications Consent.**

(a) The Platform may send marketing, promotional, and non-transactional communications to Users who have provided contact information.

(b) Marketing communications consent operates on an opt-out basis for Users who have voluntarily provided contact information in the course of using Platform services, subject to applicable law. Where applicable law requires opt-in consent for commercial electronic messages (including but not limited to the EU ePrivacy Directive and CASL), opt-in Explicit Consent will be obtained.

(c) Users may opt out of marketing communications at any time by: (i) using the unsubscribe link in any marketing message; (ii) updating communication preferences in account settings; or (iii) submitting a request to the contact information in Section 16 of this Policy.

(d) Opt-out of marketing communications does not affect transactional or service communications required for account management, security, or contractual performance.

**4.5 TK Cultural Content Consent — Escalating Authorization Framework.**

(a) **Standard Content (User-Level Consent).** For content created by an individual User from their own original authorship with no communal cultural heritage dimension, standard User Consent as described in this Policy is sufficient.

(b) **Community-Owned Cultural Content (Authorized Community Representative).** Where User Content incorporates, depicts, references, or derives from cultural heritage, traditional knowledge, oral traditions, traditional designs, or community-owned cultural expressions, the submission of such content to the Platform requires authorization from an Authorized Community Representative of the relevant cultural community, in addition to the individual User's consent. Individual users may not unilaterally grant consent on behalf of a cultural community.

(c) **TK Yellow Content (Community Review Required).** Submission, processing, and distribution of TK Yellow Content requires affirmative authorization from an Authorized Community Representative. The Platform will implement a community review workflow for content submitted with a TK Yellow designation. Pending community review, TK Yellow Content will be treated as TK Red under the Default Restrictive Behavior standard in Section 8.

(d) **TK Red Content and Sacred Content (Designated Sacred Authority Required).** Submission of TK Red Content or Sacred Content to the Platform requires express prior written authorization from a Designated Sacred Authority. The Platform will not accept submission of TK Red Content or Sacred Content without verified authorization documentation. No secondary authorization, including authorization from community representatives who are not Designated Sacred Authorities, is sufficient for TK Red or Sacred Content.

(e) **Student and Documentary Recordings.** The fact that an individual recorded, documented, or captured Sacred Content does not confer on that individual the right to consent to its Platform use. The spiritual, ceremonial, and cultural authority of Designated Sacred Authorities over Sacred Content is not diminished by the act of recording. A student recording a ceremony, a documentary filmmaker capturing a sacred ritual, or an academic researcher transcribing restricted oral knowledge does not acquire consent authority over Sacred Content.

(f) **Conflicting Claims.** Where competing consent claims exist over TK Content — such as disputes between individual Users and community representatives — the Platform will default to the most restrictive treatment pending resolution of the dispute through the applicable dispute process.

**4.6 Minor and Parental Consent.**

(a) The Platform does not knowingly provide services to Minors without Parental Consent. Users must be at least thirteen (13) years of age to create an account or use the Platform.

(b) Where a Client Operator's platform serves Users who may include Minors, the Client Operator is responsible for implementing age verification and Parental Consent mechanisms that comply with COPPA and all other applicable laws.

(c) If the Company discovers that a Minor has provided personal data without Parental Consent, the Company will promptly delete such data from Company systems and, where technically feasible, notify the relevant Client Operator.

(d) Parental Consent must be verifiable. Acceptable methods of verification include, at minimum: (i) signed written consent form submitted via postal mail or electronic submission with verification; (ii) credit card transaction for the sole purpose of verification (with no charge); (iii) a toll-free telephone call with Company staff; or (iv) such other method as may be prescribed by FTC regulation under COPPA.

(e) Parental Consent does not authorize collection of data beyond what is described in the relevant Parental Consent disclosure. Parental Consent is specific to the disclosed purposes.

**4.7 Commerce Transaction Consent.**

(a) Before completing a purchase, subscription, license, or other commerce transaction through the Platform, the User must affirmatively confirm: (i) agreement to the applicable Terms of Sale; (ii) acknowledgment of the specific goods, services, or licenses being acquired; (iii) acknowledgment of the total price, including applicable taxes and fees; and (iv) agreement to any applicable subscription or recurring billing terms.

(b) Commerce transaction consent is obtained through the Platform's checkout flow. A completed checkout confirmation constitutes Explicit Consent to the transaction and its terms.

(c) Commerce transaction consent does not substitute for any other Consent requirement applicable to the underlying content or service.

---

### 5. Just-in-Time Consent

**5.1 Principle.** The Platform is designed to obtain Consent at or immediately before the point at which the processing, use, or action requiring Consent occurs. Consent is not obtained in bulk during account registration for purposes unrelated to account creation.

**5.2 Contextual Disclosure.** Just-in-Time Consent notices disclose, at minimum: (a) the specific action for which Consent is sought; (b) the party requesting Consent; (c) a plain language description of what the User is agreeing to; and (d) the means of granting or declining Consent.

**5.3 Non-Bundled Consent.** Consent to distinct processing purposes is not bundled as a condition of a single interaction where individual purposes can reasonably be presented separately. Consent to data collection is not bundled with consent to AI training in a single, undifferentiated acknowledgment.

**5.4 No Coercive Design.** The Platform will not use interface design patterns intended to obscure, pressure, or manipulate Users into granting Consent they would not otherwise provide. This prohibition includes but is not limited to: (a) making decline buttons significantly harder to locate than accept buttons; (b) deploying multiple pop-ups or confirmation dialogs designed to exhaust the User into consenting; and (c) implying false consequences for declining non-essential consent.

---

### 6. Consent for Sacred and TK Content — Special Rules

**6.1 Platform Gatekeeping.** The Platform operates as a gatekeeper for Sacred Content and TK Red Content. Without verified Designated Sacred Authority authorization on file, the Platform will not accept, process, distribute, or commercially exploit such content.

**6.2 Authorization Documentation.** Authorized Community Representatives and Designated Sacred Authorities submitting authorization for TK Content will be required to provide: (a) documentation establishing their authorization role within the relevant community; (b) a description of the content authorized; (c) the scope and conditions of authorization; and (d) any time limits, distribution restrictions, or prohibited uses attached to the authorization.

**6.3 Revocability.** Consent and authorization provided by Authorized Community Representatives and Designated Sacred Authorities may be withdrawn prospectively. Upon receipt of a valid withdrawal, the Platform will cease new distribution and processing of the relevant TK Content and Sacred Content, and will take commercially reasonable steps to remove existing distributions where technically feasible.

**6.4 AI Exclusion.** TK Red Content, Sacred Content, and TK Yellow Content pending community review are categorically excluded from AI training pipelines. This exclusion operates at the DVE Governance layer and cannot be overridden by individual User consent. See also the AI Chat and AI Use Policy.

**6.5 Non-Commercialization.** The Platform will not commercially exploit TK Red Content or Sacred Content under any circumstance. This restriction applies regardless of any purported authorization by any party other than a verified Designated Sacred Authority and operates even where Designated Sacred Authority authorization for limited Platform presence has been obtained.

---

### 7. Consent Withdrawal

**7.1 Right to Withdraw.** A User, Authorized Community Representative, or Designated Sacred Authority may withdraw Consent at any time, for any or no reason, using the mechanisms described in Section 7.2.

**7.2 Withdrawal Mechanisms.** Consent Withdrawal may be effected through any of the following mechanisms: (a) account settings Privacy and Consent dashboard; (b) opt-out links included in relevant communications; (c) written request submitted to the contact information in Section 16; (d) cookie preference center for Cookie Consent withdrawal; or (e) such other mechanisms as the Platform may make available.

**7.3 Prospective Effect.** Consent Withdrawal takes effect prospectively. Withdrawal does not: (a) undo processing that was completed prior to receipt of the withdrawal request; (b) require deletion of Consent Records (which must be retained per Section 9); or (c) affect processing that is authorized on a legal basis other than Consent (such as contractual necessity or legitimate interest).

**7.4 Effect on Platform Access.** Where Consent is a prerequisite for a particular platform feature or service, Consent Withdrawal may result in reduced access to or loss of that feature or service. The Platform will notify the User of any such consequence before confirming the withdrawal, where technically practicable.

**7.5 Processing Timeline.** Consent Withdrawal requests will be processed within thirty (30) days of receipt. Where technically feasible, Consent Withdrawal will take effect sooner. The Platform will confirm the processing of the withdrawal to the User at the contact information on file.

---

### 8. Default Restrictive Behavior

**8.1 Ambiguity Standard.** Where User intent with respect to Consent is ambiguous — including where Consent records are incomplete, corrupted, or missing; where a User's consent status for a particular purpose cannot be determined; or where a Consent request has been presented but no response recorded — the Platform will default to the most restrictive treatment applicable to the situation.

**8.2 Application to TK Content.** Where the classification of TK Content as TK Green, TK Yellow, or TK Red is unclear or disputed, the Platform will treat the content as TK Red pending resolution of the classification question.

**8.3 Application to Minors.** Where the Platform cannot determine whether a User is a Minor, the Platform will apply the most restrictive data handling practices consistent with COPPA compliance.

**8.4 No Inferred Consent.** The Platform does not infer Consent from: (a) continued platform use after presentation of a consent notice where no affirmative response was given; (b) prior consent for a different purpose; (c) social media accounts or external profiles; or (d) third-party data suggesting likely preferences.

---

### 9. Consent Record-Keeping

**9.1 Retention.** The Platform maintains Consent Records for a minimum period of three (3) years from the date of the relevant Consent, Consent modification, or Consent Withdrawal, or for such longer period as required by applicable law.

**9.2 Record Contents.** Each Consent Record contains, at minimum: (a) a unique identifier for the Consent event; (b) the timestamp of the Consent event (UTC); (c) the User or other consenting party identifier; (d) the version of the consent notice presented; (e) the method of consent (e.g., checkbox, button click, signed form); (f) the specific purpose(s) consented to; and (g) any subsequent modification or withdrawal, with timestamp.

**9.3 Immutability.** Consent Records are stored in a manner that prevents retroactive modification. Modifications to Consent status create new Consent Record entries; they do not overwrite prior entries.

**9.4 User Access.** Users may request a copy of their Consent Records by submitting a request to the contact information in Section 16. The Platform will respond to such requests within thirty (30) days.

**9.5 Operator Records.** Client Operators that deploy their own Consent mechanisms on top of Platform infrastructure are responsible for maintaining their own Consent Records in compliance with applicable law. Such records supplement, and do not replace, Company-maintained Consent Records at the Platform layer.

---

### 10. Platform vs. Client Operator Consent Responsibilities

**10.1 Company Responsibilities.** The Company is responsible for: (a) providing Consent infrastructure, mechanisms, and Layer A through Layer D disclosures for platform-level processing; (b) maintaining Consent Records for Company-side processing activities; (c) enforcing Consent at the DVE Governance layer; and (d) ensuring that baseline Consent standards are met for all Platform deployments.

**10.2 Client Operator Responsibilities.** Client Operators are responsible for: (a) configuring Consent mechanisms appropriately for the jurisdictions and user populations they serve; (b) ensuring that any additional data collection or processing performed by the Operator — beyond Platform-standard processing — is covered by adequate Consent obtained from End Users; (c) maintaining Consent Records for Operator-side processing; and (d) complying with all applicable laws governing Consent in the Operator's territory.

**10.3 Layered Accountability.** The Company and Client Operators operate as legally distinct entities for Consent purposes. A Client Operator's Consent practices do not bind the Company, and the Company's Consent practices do not relieve Client Operators of their independent Consent obligations.

**10.4 Operator Agreement.** Client Operators are required, as a condition of Platform deployment, to execute a Data Processing Agreement that specifies the respective Consent responsibilities of each party and the technical mechanisms by which Consent data is shared between Platform systems and Operator systems.

---

### 11. CCPA Opt-Out and California Consumer Rights

**11.1 Right to Opt Out of Sale/Sharing.** California residents have the right to opt out of the "sale" or "sharing" of their personal information as those terms are defined under the California Consumer Privacy Act (CCPA) and the California Privacy Rights Act (CPRA). The Platform provides a "Do Not Sell or Share My Personal Information" link accessible from all platform pages.

**11.2 No Sale to Third Parties Without Opt-Out Mechanism.** The Platform will not sell or share personal information with third parties for cross-contextual behavioral advertising without providing Users a clear and conspicuous opt-out mechanism.

**11.3 Additional California Rights.** California residents have the right to: (a) know what personal information is collected; (b) delete personal information; (c) correct inaccurate personal information; (d) limit use of sensitive personal information; and (e) non-discrimination for exercising privacy rights. These rights are further described in the Privacy Policy.

---

### 12. GDPR Consent Requirements Placeholder

**12.1 GDPR Applicability.** Where Users are located in the European Economic Area (EEA), the United Kingdom, or Switzerland, the General Data Protection Regulation (GDPR) and applicable national implementing legislation impose additional requirements on Consent, including requirements that Consent be: freely given, specific, informed, unambiguous, demonstrable, and separately obtained for each distinct purpose.

**12.2 Lawful Basis.** For EEA, UK, and Swiss Users, the Company will document the lawful basis for each processing activity in a Records of Processing Activities (ROPA) document. Where Consent is relied upon as the lawful basis, the requirements of this Policy and GDPR Article 7 must both be satisfied.

**12.3 Overlay Document.** A GDPR-specific Consent Overlay document is pending drafting and legal review. Upon completion, such overlay will take precedence over provisions of this Policy that are inconsistent with GDPR requirements for affected Users.

| Jurisdiction | Overlay Document | Key Modification |
|---|---|---|
| European Union (GDPR) | Pending — overlay document not yet created | Placeholder — drafting required |
| United Kingdom (UK GDPR) | Pending — overlay document not yet created | Placeholder — drafting required |
| Republic of The Gambia | Pending — overlay document not yet created | Placeholder — drafting required |

---

### 13. Consent and Minors — COPPA Compliance

**13.1 No Service to Under-13.** The Platform does not knowingly provide services to children under 13 years of age without verifiable Parental Consent. The Platform does not knowingly collect personal information from children under 13 without Parental Consent.

**13.2 Age Gates.** Where required by law or Platform policy, age verification gates will be implemented to prevent submission of personal data by Minors without Parental Consent.

**13.3 Discovery and Deletion.** If the Company discovers that personal data of a Minor has been collected without Parental Consent, the Company will: (a) notify the relevant Client Operator (if applicable); (b) delete the Minor's personal data from Company systems within a commercially reasonable time; and (c) where feasible, notify the Minor's parent or guardian.

**13.4 Operator COPPA Obligations.** Client Operators whose platforms are directed at children or who have actual knowledge of collecting personal information from children must comply independently with COPPA, implement required Parental Consent mechanisms, and not rely solely on Company-platform age gates as their compliance mechanism.

---

### 14. Enforcement and Compliance

**14.1 DVE Enforcement.** Consent is technically enforced through the DVE Governance system, which automatically applies the permissions and restrictions recorded in the Consent Record to data processing, content access, AI pipelines, distribution channels, and marketing systems.

**14.2 Policy Violations.** Violation of this Consent Policy by a User may result in suspension or termination of Platform access, removal of offending content, and reporting to appropriate authorities where required by law.

**14.3 Operator Non-Compliance.** A Client Operator's material non-compliance with Consent obligations under this Policy or the applicable Data Processing Agreement may result in suspension of the Operator's Platform deployment rights.

---

### 15. Governing Law and Jurisdiction

This Policy is governed by the laws of the State of California, United States, without regard to its conflict-of-law provisions.

| Jurisdiction | Overlay Document | Key Modification |
|---|---|---|
| European Union (GDPR) | Pending — overlay document not yet created | Placeholder — drafting required |
| Republic of The Gambia | Pending — overlay document not yet created | Placeholder — drafting required |

---

### 16. Changes to This Policy

The Company reserves the right to amend this Policy at any time. Material changes will be communicated to Users by platform notification and by updating the `date` field in the YAML metadata above. Continued use of the Platform following notice of a change constitutes acceptance of the updated Policy.

---

### 17. Contact

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
