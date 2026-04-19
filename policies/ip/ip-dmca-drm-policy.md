---
version: 0.1.0
date: 2026-04-18
status: drafting
jurisdiction: California
supersedes: none
policyType: module
dependsOnMasterTerms: true
sourceModels:
  - YouTube/Google DMCA Framework
  - GitHub Takedown Structure
  - WIPO Principles
  - 17 U.S.C. § 512
---

# Intellectual Property Digital Millennium Copyright Act Digital Rights Management Compliance Policy

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
> **IP/DMCA note:** PLATFORM OPERATOR is the designated DMCA agent for the PLATFORM. SITE OWNER is responsible for their own content compliance. PLATFORM OPERATOR may take down content on any domain where a valid DMCA notice is received.

---

## Plain Language Summary

> **Who is "we" in this document?**
> **"We"** and **"us"** in this IP, DMCA, and DRM Compliance Policy refer to **PLATFORM OPERATOR** (Starisian Technologies, LLC) administering IP enforcement and DMCA compliance at the PLATFORM layer.
> SITE OWNER is responsible for their domain's content compliance. PLATFORM OPERATOR may take down content on any domain using PLATFORM infrastructure upon receipt of a valid DMCA notice, regardless of which SITE OWNER operates that domain.

**What this policy is about**

This policy explains how PLATFORM OPERATOR protects intellectual property (IP) on the SPARXSTAR PLATFORM, how PLATFORM OPERATOR handles copyright takedown requests under the Digital Millennium Copyright Act (DMCA), and why END USERS may not bypass digital rights management (DRM) technology on the PLATFORM.

**What is intellectual property?**

Intellectual property (IP) refers to creations of the mind — such as songs, books, videos, artwork, software, inventions, and brand names — that the law protects as belonging to their creators. The main types of IP protection relevant to the PLATFORM are copyright (protecting creative works) and related rights (protecting performances, recordings, and broadcasts).

**What is DRM?**

Digital Rights Management, or DRM, refers to technologies that control how digital content can be accessed, copied, or shared. When content on the PLATFORM is protected by DRM, that protection exists to respect the rights of the content creator. END USERS are not allowed to bypass or disable DRM protection — doing so is illegal under the DMCA and violates this policy.

**What is a DMCA takedown notice?**

The DMCA is a US law that protects platforms like the PLATFORM from being liable for content users upload, as long as PLATFORM OPERATOR responds properly when it receives a report of copyright infringement. If someone reports that your content infringes their copyright, PLATFORM OPERATOR will remove the content and notify you.

**How to report copyright infringement**

If someone has uploaded your work without permission, you can send PLATFORM OPERATOR a formal DMCA takedown notice. Your notice must include:

1. A description of the copyrighted work
2. The location of the infringing copy on the PLATFORM (URL)
3. Your contact information
4. A statement that you believe the use is not authorized
5. A statement confirming the information is accurate, under penalty of perjury
6. Your signature

PLATFORM OPERATOR will remove the content quickly and notify the person who uploaded it.

**How to dispute a takedown (counter-notice)**

If your content was removed by mistake — because the complaining person was wrong — you can send PLATFORM OPERATOR a counter-notice. Your counter-notice must include:

1. A description of the content that was removed
2. A statement under penalty of perjury that the removal was a mistake
3. Your consent to be sued in federal court in California if the complainant disagrees
4. Your contact information and signature

After PLATFORM OPERATOR receives your counter-notice, it will notify the original complainant. If they do not take court action within 10 to 14 business days, PLATFORM OPERATOR will restore your content.

**Cultural content exception**

If content may be part of a traditional cultural or indigenous heritage tradition, PLATFORM OPERATOR will take extra care before removing it. PLATFORM OPERATOR may delay a takedown to consult relevant cultural frameworks and ensure it is not removing something that deserves special protection.

**What happens to repeat infringers?**

If an END USER repeatedly infringes copyright on the PLATFORM, PLATFORM OPERATOR will suspend or permanently terminate the account.

**Words are not owned — but organized systems are**

We do not own individual words. No one does. But organized databases of words, linguistic datasets, semantic mappings, and other structured systems that we build are our proprietary property.

---

## Full Legal Text

### Section 1 — Definitions

For purposes of this Intellectual Property Digital Millennium Copyright Act Digital Rights Management Compliance Policy ("IP/DMCA/DRM Policy"), the following terms have the meanings set forth below:

1.1 **"Intellectual Property" or "IP"** means legally recognized rights arising from creative, inventive, or commercial endeavors, including without limitation: copyright, neighboring and related rights, database rights, moral rights, trademark, trade secret, patent, and rights in Traditional Knowledge, as recognized under applicable United States law, applicable international law, and applicable African regional intellectual property frameworks.

1.2 **"DMCA"** means the Digital Millennium Copyright Act, as codified at 17 U.S.C. §§ 512, 1201–1205, and 1301–1332, and any regulations promulgated thereunder by the United States Copyright Office and other agencies.

1.3 **"Digital Rights Management" or "DRM"** means any technological measure, system, mechanism, or access control technology that effectively controls access to, or the copying, distribution, or use of, a copyrighted work or protected content, as contemplated by 17 U.S.C. § 1201 et seq.

1.4 **"DRM Technology"** means any specific technological implementation of DRM, including encryption, access control systems, copy protection schemes, digital watermarks, license management systems, regional access controls, and any other technology that controls or limits access to or use of protected content.

1.5 **"Circumvention"** means the act of defeating, bypassing, removing, deactivating, descrambling, decrypting, or otherwise avoiding, circumventing, or impairing a DRM Technology or access control measure, as defined in 17 U.S.C. § 1201(a)(3)(A) and § 1201(b)(2)(A).

1.6 **"Designated Agent"** means the agent designated by Starisian Technologies to receive DMCA takedown notifications and counter-notices pursuant to 17 U.S.C. § 512(c)(2), as registered with the United States Copyright Office in accordance with 37 C.F.R. § 201.38.

1.7 **"Takedown Notice"** means a written notification of claimed copyright infringement submitted to the Designated Agent in accordance with 17 U.S.C. § 512(c)(3) and Section 4 of this Policy.

1.8 **"Counter-Notice"** means a written counter-notification submitted by a User pursuant to 17 U.S.C. § 512(g)(3) disputing a Takedown Notice and requesting restoration of removed content, in accordance with Section 5 of this Policy.

1.9 **"Repeat Infringer"** means a User who has had content removed from the Platform on two (2) or more occasions pursuant to valid DMCA Takedown Notices, or who has otherwise repeatedly engaged in copyright infringement on the Platform, as determined by Starisian Technologies in its reasonable discretion consistent with its obligations under 17 U.S.C. § 512(i)(1)(A).

1.10 **"Safe Harbor"** means the limitations on liability for online service providers set forth in 17 U.S.C. § 512, including the safe harbors for transitory digital network communications (§ 512(a)), system caching (§ 512(b)), storage of information at direction of users (§ 512(c)), and information location tools (§ 512(d)).

1.11 **"Structured Dataset"** means any organized collection of data, linguistic entries, semantic associations, annotations, classifications, or curated materials that has been compiled, arranged, or derived by or through the Platform's systems, and in which the Platform holds protectable intellectual property rights as a compilation or database under applicable law, regardless of whether individual constituent elements are themselves protectable.

1.12 **"Traditional Knowledge" or "TK"** means the knowledge, innovations, and practices of indigenous and local communities embodying traditional lifestyles relevant for the conservation and sustainable use of biological diversity, and including traditional cultural expressions (TCEs) such as music, art, designs, ceremonies, narratives, and names, as recognized under the TK Label Framework, WIPO's Intergovernmental Committee on Genetic Resources, Traditional Knowledge and Folklore (IGC), and applicable national and international frameworks.

1.13 **"TK Label Framework"** means the Traditional Knowledge (TK) Labels and Biocultural Labels system developed by Local Contexts, used by indigenous communities to manage and communicate cultural and research permissions regarding TK and TCEs.

1.14 **"Platform"** means the SPARXSTAR platform and associated services operated by Starisian Technologies, including all subdomains, APIs, applications, and integrated services.

1.15 **"User"** means any individual or entity who accesses, registers for, or uses the Platform.

1.16 **"Starisian Technologies"** means Starisian Technologies, the legal entity that owns and operates the Platform.

1.17 **"WIPO"** means the World Intellectual Property Organization.

1.18 **"WIPO Copyright Treaty"** or **"WCT"** means the WIPO Copyright Treaty adopted in Geneva on December 20, 1996, and as amended or supplemented from time to time.

1.19 **"User Content"** means any content, data, works of authorship, materials, information, or other submissions that a User uploads, posts, transmits, publishes, or otherwise makes available on or through the Platform.

---

### Section 2 — Scope and Application

**2.1 Scope**

This IP/DMCA/DRM Policy governs all intellectual property rights enforcement activities on the Platform, including:

  (a) Copyright and related rights compliance under United States law (17 U.S.C. et seq.) and applicable international copyright law;

  (b) DMCA takedown notice and counter-notice procedures under 17 U.S.C. § 512;

  (c) DRM compliance and anti-circumvention obligations under 17 U.S.C. § 1201 et seq.;

  (d) Database and compilation rights where applicable under United States and international law;

  (e) Moral rights where applicable under applicable international and national law;

  (f) Traditional Knowledge protections and cultural heritage considerations;

  (g) Structured dataset and language corpus rights as proprietary platform assets.

**2.2 Relationship to Other Policies**

This IP/DMCA/DRM Policy operates in conjunction with, and supplements, the Platform's Copyright Policy and Trademark Policy. In the event of a conflict between this Policy and the Copyright Policy or Trademark Policy with respect to a specific subject matter, the more specific provision shall control. All three policies are modules of and are incorporated into the Platform's Master Terms of Service.

**2.3 Applicability to All Users**

This Policy applies to all Users of the Platform, including registered and unregistered users, regardless of the User's jurisdiction of residence or the jurisdiction in which the User's uploaded content originated. By accessing or using the Platform, each User agrees to comply with this Policy.

---

### Section 3 — Intellectual Property Rights Framework

**3.1 Copyright**

Starisian Technologies recognizes and respects copyright protection as established under the United States Copyright Act (17 U.S.C. § 101 et seq.) and applicable international copyright law, including the Berne Convention for the Protection of Literary and Artistic Works, the WIPO Copyright Treaty, and the Agreement on Trade-Related Aspects of Intellectual Property Rights (TRIPS). Copyright protects original works of authorship fixed in a tangible medium of expression, including literary, musical, dramatic, pictorial, graphic, audiovisual, and architectural works, and sound recordings.

**3.2 Neighboring and Related Rights**

The Platform recognizes neighboring rights and related rights — including rights of performers, producers of phonograms, and broadcasting organizations — as established under applicable national law and international instruments, including the International Convention for the Protection of Performers, Producers of Phonograms and Broadcasting Organizations (Rome Convention) and the WIPO Performances and Phonograms Treaty (WPPT).

**3.3 Database Rights**

Where applicable under United States law (as protectable compilations under 17 U.S.C. § 101) and, where applicable, under the national laws of jurisdictions that recognize sui generis database rights (including European Union member states under Directive 96/9/EC), the Platform asserts database rights in structured datasets, organized corpora, and curated lexicons developed by or through the Platform.

**3.4 Moral Rights**

The Platform acknowledges moral rights of authors — including the rights of attribution and integrity — as recognized under applicable international and national law, including Article 6bis of the Berne Convention, and applicable national laws that implement or recognize moral rights (such as the Visual Artists Rights Act of 1990 (VARA), 17 U.S.C. § 106A, and applicable foreign law). While United States law provides limited recognition of moral rights outside the visual arts context, the Platform will endeavor to respect authors' attribution and integrity interests in appropriate circumstances.

**3.5 Traditional Knowledge Protections**

The Platform recognizes Traditional Knowledge (TK) and Traditional Cultural Expressions (TCEs) as subject to special protection considerations under the TK Label Framework, WIPO IGC frameworks, and applicable national and regional IP frameworks. The Platform is committed to respecting TK community rights and will apply the cultural content review procedures described in Section 8 when evaluating IP enforcement actions that may affect TK-labeled or culturally sensitive content.

**3.6 Structured Dataset and Language Corpus Rights**

The Platform's structured linguistic datasets, semantic mappings, curated lexicons, terminological databases, annotated corpora, and other proprietary structured systems are proprietary assets of the Platform protected as compilations and databases under applicable law. The Platform's rights in such structured assets arise from the original selection, coordination, arrangement, and curation of such materials as a whole. Individual words are not owned by the Platform; however, structured linguistic datasets, semantic mappings, curated lexicons, annotations, and proprietary arrangements created through the Platform are proprietary assets of the Platform. No claim of Platform ownership is made to individual words, morphemes, phonemes, grammatical rules, or other elements of language that are in the public domain.

**3.7 No Claim to Individual Words**

Starisian Technologies expressly does not claim copyright, database right, trademark, or any other form of intellectual property protection in individual words, morphemes, phonemes, or other atomic units of language. Individual words are in the public domain and are not subject to any Platform IP claim. DMCA process and other IP enforcement mechanisms on this Platform are not available for claims to individual words; no such claims will be accepted or processed.

---

### Section 4 — DMCA Compliance and Takedown Procedure

**4.1 Service Provider Status**

Starisian Technologies operates the Platform as a service provider within the meaning of 17 U.S.C. § 512(k)(1) and intends to maintain its eligibility for the Safe Harbor protections afforded to online service providers under 17 U.S.C. § 512. Starisian Technologies' compliance with the DMCA notice-and-takedown procedure set forth in this Section 4 is integral to its Safe Harbor qualification.

**4.2 Designated Agent**

Starisian Technologies has designated an agent to receive notifications of claimed copyright infringement and counter-notices pursuant to 17 U.S.C. § 512(c)(2). The Designated Agent's contact information is as follows:

> **DMCA Designated Agent**
> Starisian Technologies
> [Legal Department / Designated Agent Name — To Be Completed]
> [Mailing Address — To Be Completed]
> [Email Address — To Be Completed]
> [Phone Number — To Be Completed]

Starisian Technologies' Designated Agent is registered with the United States Copyright Office in accordance with 17 U.S.C. § 512(c)(2) and 37 C.F.R. § 201.38.

**4.3 Safe Harbor Conditions**

To maintain its Safe Harbor status under 17 U.S.C. § 512, Starisian Technologies operates in accordance with the following conditions:

  (a) **Lack of Knowledge** — The Platform does not have actual knowledge of infringing activity and is not aware of facts or circumstances from which infringing activity is apparent, with respect to content stored or transmitted at the direction of users, absent actual notice of a specific infringement;

  (b) **No Financial Benefit from Infringement** — The Platform does not financially benefit from infringing activity it has the right and ability to control;

  (c) **Expeditious Response** — Upon receiving a valid DMCA Takedown Notice, the Platform removes or disables access to the allegedly infringing material expeditiously;

  (d) **Repeat Infringer Policy** — The Platform maintains and implements a policy for terminating the accounts of Users who are Repeat Infringers, in accordance with Section 4.8;

  (e) **Standard Technical Measures** — The Platform accommodates and does not interfere with standard technical measures used by copyright owners to identify or protect their works, as contemplated by 17 U.S.C. § 512(i)(2).

**4.4 Required Elements of a Valid DMCA Takedown Notice**

A written DMCA Takedown Notice submitted to the Designated Agent must include all six (6) statutory elements required by 17 U.S.C. § 512(c)(3):

  **(1) Identification of the Copyrighted Work** — An identification of the copyrighted work claimed to have been infringed, or, if multiple copyrighted works at a single online site are covered by a single notification, a representative list of such works at that site. The identification should be sufficiently specific to allow Starisian Technologies to locate the work.

  **(2) Identification of the Infringing Material** — An identification of the material that is claimed to be infringing or to be the subject of infringing activity, and that is to be removed or access to which is to be disabled. The identification must include information reasonably sufficient to permit Starisian Technologies to locate the material, including the specific URL, post identifier, or other precise locator for each item of allegedly infringing content.

  **(3) Contact Information** — Information reasonably sufficient to permit Starisian Technologies to contact the complaining party, including the name, address, telephone number, and, if available, electronic mail address of the complaining party or its authorized representative.

  **(4) Good Faith Belief Statement** — A statement that the complaining party has a good faith belief that use of the material in the manner complained of is not authorized by the copyright owner, its agent, or applicable law. This statement must reflect an actual good faith assessment; submitting a notice without such belief may constitute misrepresentation under 17 U.S.C. § 512(f).

  **(5) Accuracy and Authorization Statement** — A statement that the information in the notification is accurate, and under penalty of perjury, that the complaining party is authorized to act on behalf of the owner of an exclusive right that is allegedly infringed.

  **(6) Signature** — A physical or electronic signature of a person authorized to act on behalf of the owner of an exclusive right that is allegedly infringed.

**4.5 Where to Submit Takedown Notices**

Takedown Notices must be submitted to the Designated Agent at the contact information set forth in Section 4.2. Notices submitted through general Platform support channels, user reporting tools, or non-DMCA contact forms may not receive expeditious DMCA handling. Starisian Technologies recommends using the designated DMCA email address to ensure prompt processing.

**4.6 Platform Response Timeline**

Upon receipt of a complete and valid Takedown Notice:

  (a) Starisian Technologies will review the notice to assess whether it satisfies all statutory requirements under 17 U.S.C. § 512(c)(3);

  (b) If the notice is complete and valid, Starisian Technologies will expeditiously remove or disable access to the identified content. "Expeditiously" under the DMCA means as promptly as is reasonably practicable in good faith, which Starisian Technologies interprets to mean within one (1) to three (3) business days for standard cases, subject to the cultural content review exception in Section 8;

  (c) Starisian Technologies will notify the User whose content was removed or disabled of the takedown action and provide the User with a copy of the Takedown Notice or a summary of its material contents, except where such disclosure is prohibited by applicable law or court order.

**4.7 Incomplete Notices**

If a submitted Takedown Notice fails to substantially comply with the requirements of 17 U.S.C. § 512(c)(3), Starisian Technologies may, at its discretion: (a) notify the submitting party of the deficiencies and request supplemental information; or (b) decline to process the notice. Starisian Technologies has no obligation under the DMCA to act upon materially deficient notices and such action (or inaction) shall not affect Starisian Technologies' Safe Harbor status.

**4.8 Repeat Infringer Policy**

Consistent with 17 U.S.C. § 512(i)(1)(A), Starisian Technologies maintains and implements a policy for the termination of accounts of Repeat Infringers:

  (a) Starisian Technologies tracks DMCA Takedown Notices received and the accounts associated with the content identified in each notice;

  (b) Upon a User's second DMCA-related content removal within any twelve (12) month period, Starisian Technologies may issue a formal warning to the User;

  (c) Upon a User's third or subsequent DMCA-related content removal, Starisian Technologies may suspend or permanently terminate the User's account, at Starisian Technologies' reasonable discretion;

  (d) Starisian Technologies reserves the right to terminate a User's account upon fewer removals if the nature or scale of the infringement warrants immediate termination;

  (e) Account termination decisions will be documented and maintained in Starisian Technologies' internal records for purposes of Safe Harbor compliance.

---

### Section 5 — Counter-Notice Procedure

**5.1 User's Right to Dispute**

A User whose content has been removed or disabled pursuant to a DMCA Takedown Notice may submit a Counter-Notice to the Designated Agent if the User believes in good faith that the content was removed or disabled as a result of mistake or misidentification of the material to be removed.

**5.2 Required Elements of a Valid Counter-Notice**

A valid Counter-Notice submitted pursuant to 17 U.S.C. § 512(g)(3) must include all of the following elements:

  **(1) Identification of Removed Content** — Identification of the material that has been removed or to which access has been disabled, and the location at which the material appeared before it was removed or access to it was disabled. This should include the specific URL or other identifier that was in place before removal.

  **(2) Statement Under Penalty of Perjury** — A statement under penalty of perjury that the User has a good faith belief that the material was removed or disabled as a result of mistake or misidentification of the material to be removed or disabled.

  **(3) Consent to Jurisdiction** — The User's name, address, and telephone number, and a statement that the User consents to the jurisdiction of the Federal District Court for the judicial district in which the User's address is located, or if the User's address is outside of the United States, for any judicial district in which Starisian Technologies may be found, and that the User will accept service of process from the person who provided the original DMCA Takedown Notice or an agent of such person.

  **(4) Signature** — A physical or electronic signature of the User or the User's authorized representative.

**5.3 Submission of Counter-Notice**

Counter-Notices must be submitted to the Designated Agent at the contact information set forth in Section 4.2. Counter-Notices submitted through general support channels may experience delays.

**5.4 Platform's Obligation to Forward Counter-Notice**

Upon receipt of a valid Counter-Notice, Starisian Technologies shall promptly provide the original complaining party (the party who submitted the Takedown Notice) with a copy of the Counter-Notice, and inform the complaining party that Starisian Technologies will restore access to the removed material in ten (10) to fourteen (14) business days from the date of the Counter-Notice unless the complaining party files an action seeking a court order to restrain the User from engaging in infringing activity relating to the material on the Platform and provides Starisian Technologies with notice of such court action.

**5.5 Restoration Timeline**

Starisian Technologies will restore access to the removed or disabled content within ten (10) to fourteen (14) business days after receiving a valid Counter-Notice, unless:

  (a) The original complaining party has provided Starisian Technologies with notice that it has filed an action in federal district court seeking a court order to restrain the User from engaging in infringing activity relating to the material; or

  (b) A court having jurisdiction over the matter has issued an order restraining restoration of the content.

**5.6 No Guarantee of Restoration**

Nothing in this Section 5 obligates Starisian Technologies to restore content that independently violates the Platform's Terms of Service, Community Standards, or other applicable policies, regardless of the outcome of the DMCA counter-notice process.

---

### Section 6 — Digital Rights Management (DRM) Compliance

**6.1 Anti-Circumvention Prohibition**

In accordance with 17 U.S.C. § 1201, Users are strictly prohibited from engaging in any of the following conduct on or through the Platform:

  (a) **Circumventing Access Controls** — Circumventing, bypassing, removing, deactivating, descrambling, decrypting, or otherwise defeating any technological measure that effectively controls access to a work protected under title 17 of the United States Code, whether such measure is applied to Platform Content, third-party content on the Platform, or any other content accessible through the Platform;

  (b) **Circumventing Copy Protection** — Circumventing, bypassing, removing, deactivating, or otherwise defeating any technological measure that effectively protects a right of a copyright owner in a work protected under title 17;

  (c) **Distributing Circumvention Tools** — Manufacturing, importing, offering to the public, providing, or otherwise trafficking in any technology, product, service, device, component, or part thereof that: (i) is primarily designed or produced for the purpose of circumventing DRM Technology; (ii) has only limited commercially significant purpose or use other than to circumvent DRM Technology; or (iii) is marketed for use in circumventing DRM Technology;

  (d) **Removing or Altering DRM** — Removing, altering, forging, or falsifying any DRM Technology, digital watermark, rights management information, or access control measure embedded in or affixed to any Platform Content or third-party content on the Platform;

  (e) **Unauthorized Access** — Accessing, downloading, copying, or using Platform Content or third-party content on the Platform beyond the scope of any license granted to the User, or through means not authorized by Starisian Technologies.

**6.2 Permitted Exceptions**

Notwithstanding Section 6.1, the following limited exceptions may apply to the anti-circumvention prohibition, subject to the conditions and procedures set forth in this Section 6.2:

  (a) **Lawful Fair Use and Other Copyright Exceptions** — To the extent that circumvention of a particular DRM Technology is necessary to exercise a lawful fair use right under 17 U.S.C. § 107, or other applicable statutory copyright exception (such as 17 U.S.C. §§ 108–122), and the User qualifies for such exception under applicable law, the Platform acknowledges that such circumvention may be lawful under 17 U.S.C. § 1201(c)(1). Users asserting this exception are solely responsible for ensuring their conduct falls within the scope of the applicable copyright exception and for compliance with all applicable law.

  (b) **Accessibility Accommodation** — Starisian Technologies may, in its discretion, grant individual Users accommodations for circumventing specific DRM Technologies where necessary to enable access for Users with disabilities, consistent with applicable accessibility law and Starisian Technologies' accessibility policies. Requests for accessibility accommodations must be submitted through the Platform's accessibility accommodation request process.

  (c) **Platform-Authorized Access** — Nothing in Section 6.1 prohibits a User from accessing Platform Content through technological means expressly authorized by Starisian Technologies, including through authorized APIs, player technologies, or download features provided by Starisian Technologies for authorized content.

**6.3 Consequences of DRM Violations**

Violation of Section 6.1 may result in: (a) immediate termination of the User's access to the Platform; (b) civil liability under 17 U.S.C. § 1203, including actual damages or statutory damages of between $200 and $2,500 per act of circumvention (or up to $25,000 for willful circumvention of access controls); (c) criminal liability under 17 U.S.C. § 1204 for willful violations; and (d) such other remedies as are available under applicable law.

---

### Section 7 — Anti-Abuse Provisions

**7.1 False DMCA Notices**

Submitting a knowingly false or materially misleading DMCA Takedown Notice or Counter-Notice constitutes misrepresentation under 17 U.S.C. § 512(f) and may subject the submitting party to liability for: (a) damages, including costs and attorneys' fees, suffered by any affected User, Starisian Technologies, or other affected party as a result of the false notice; and (b) civil or criminal penalties under applicable law for perjury or fraud.

**7.2 Account Consequences for False Notices**

Starisian Technologies reserves the right to suspend or permanently terminate the account of any User or third party who submits false, fraudulent, materially misleading, or abusive DMCA Takedown Notices or Counter-Notices, as determined by Starisian Technologies in its reasonable discretion.

**7.3 Abuse Prevention Measures**

Starisian Technologies may implement additional safeguards to prevent abuse of the DMCA process, including: (a) rate-limiting of notice submissions from a single source; (b) requiring identity verification for notice submitters; (c) rejecting notices submitted in apparent bad faith; and (d) coordinating with law enforcement authorities where appropriate.

**7.4 No DMCA Claims for Individual Words**

The DMCA process is not available for claims of rights in individual words, morphemes, phonemes, or other unprotectable elements of language. Starisian Technologies will not process DMCA Takedown Notices that purport to assert copyright in individual words or public domain language elements. Such notices will be rejected as legally insufficient.

---

### Section 8 — Cultural Content Review

**8.1 Traditional Knowledge and Cultural Heritage**

Starisian Technologies recognizes that some User Content on the Platform may be subject to Traditional Knowledge (TK) protections, TK Label Framework designations, indigenous cultural heritage protections, or other cultural preservation considerations that operate outside the scope of conventional Western IP frameworks. In recognition of these protections, Starisian Technologies maintains the following cultural content review procedures.

**8.2 Triggering Cultural Content Review**

Before executing a DMCA Takedown with respect to User Content that is, or that Starisian Technologies reasonably believes may be:

  (a) Labeled with a TK Label or Biocultural Label under the TK Label Framework;

  (b) Identified by the User or by a community stakeholder as constituting a Traditional Cultural Expression (TCE), traditional knowledge, or indigenous cultural heritage material;

  (c) Associated with metadata, artist designations, or contextual indicators suggesting origin in a specific indigenous or traditional community;

Starisian Technologies may, at its discretion, undertake a supplemental cultural content review to assess whether: (i) the TK Label Framework or other applicable cultural heritage framework is implicated; (ii) removal would conflict with Starisian Technologies' commitments to cultural preservation and respect for indigenous rights; and (iii) the DMCA process is the appropriate mechanism for resolving the dispute.

**8.3 Delay for Cultural Review**

Starisian Technologies reserves the right to delay execution of a DMCA Takedown for a reasonable period, not to exceed thirty (30) calendar days from the date of receipt of the Takedown Notice, to conduct a cultural content review pursuant to Section 8.2. Starisian Technologies will notify the complaining party of any such delay and the reason therefor within a reasonable time after initiating the review.

**8.4 DMCA Process Does Not Override TK Community Rights**

Starisian Technologies will not use the DMCA process, or the threat or execution of a DMCA Takedown, as a mechanism to override legitimate TK community rights in Traditional Knowledge or Traditional Cultural Expressions. Where the cultural content review process reveals that a Takedown Notice is being used to suppress or misappropriate TK content in a manner inconsistent with the rights of the originating community, Starisian Technologies may decline to execute the Takedown or may pursue alternative dispute resolution.

**8.5 Non-Waiver**

The cultural content review process described in this Section 8 does not constitute a waiver of the complaining party's rights under the DMCA, nor does it create any additional rights for Users whose content is under review beyond those available under applicable law. Starisian Technologies retains full discretion to proceed with a DMCA Takedown after completing the cultural content review, subject to applicable law.

---

### Section 9 — International Considerations

**9.1 WIPO Copyright Treaty Compliance**

Starisian Technologies acknowledges and respects its obligations under the WIPO Copyright Treaty (WCT), the WIPO Performances and Phonograms Treaty (WPPT), and related international instruments, as implemented through United States law and applicable foreign law. Starisian Technologies' anti-circumvention provisions (Section 6) are designed to be consistent with the obligations set forth in Article 11 of the WCT and Article 18 of the WPPT.

**9.2 Cross-Border Enforcement Coordination**

Where a DMCA Takedown dispute involves parties or content subject to the laws of a jurisdiction other than the United States, Starisian Technologies will endeavor to apply internationally recognized IP principles and will cooperate with rights holders, enforcement authorities, and relevant international bodies as required by applicable law.

**9.3 Berne Convention and TRIPS**

Starisian Technologies operates in accordance with the principles of the Berne Convention for the Protection of Literary and Artistic Works and the Agreement on Trade-Related Aspects of Intellectual Property Rights (TRIPS), which establish minimum international standards for copyright protection and enforcement.

**9.4 Gambia and African Jurisdiction Overlay**

In connection with AI West Africa (AIWA) operations and Platform activities conducted in or in relation to the Republic of The Gambia, the Economic Community of West African States (ECOWAS) region, and other African jurisdictions:

  (a) Starisian Technologies acknowledges that additional local copyright law obligations may apply, including under the laws of The Gambia and applicable regional African IP frameworks;

  (b) AIWA-specific content and operations are subject to applicable Gambian law and any applicable African regional intellectual property frameworks administered by ARIPO (African Regional Intellectual Property Organization) or OAPI (African Intellectual Property Organization), in addition to the general provisions of this Policy;

  (c) Starisian Technologies will endeavor to align its IP enforcement practices with applicable African regional standards to the extent not inconsistent with United States law;

  (d) TK and cultural heritage content originating from West African communities will be treated in accordance with the cultural content review provisions of Section 8 and applicable African and international TK protection frameworks.

---

### Section 10 — Structured Dataset and Language Corpus Rights

**10.1 Proprietary Structured Assets**

The Platform's structured linguistic datasets, semantic mappings, curated lexicons, terminological databases, annotated corpora, ontological frameworks, and other organized systems of linguistic or knowledge data are proprietary assets of Starisian Technologies protected as compilations and databases under applicable United States and international law. These assets are the product of substantial investment of resources, original selection and arrangement, and platform-specific curation, and are protected independently of the copyright status of their individual constituent elements.

**10.2 Individual Words Not Owned**

Starisian Technologies does not claim any intellectual property rights in individual words, morphemes, phonemes, or other atomic units of language, which are and remain in the public domain. The Platform's rights in its structured datasets arise exclusively from the original selection, coordination, arrangement, and curation of materials as a whole, not from any claim to the individual linguistic elements contained therein.

**10.3 User License for Dataset Inclusion**

By submitting User Content that includes linguistic data, annotations, translations, glosses, or related materials to the Platform, Users grant Starisian Technologies the right to incorporate such materials into the Platform's structured datasets and language corpora in accordance with the license grant set forth in the Platform's Copyright Policy. The Platform's rights in resulting structured compilations arise from the Platform's original arrangement, not from ownership of the User's underlying linguistic expression.

**10.4 DMCA Not Applicable to Individual Word Claims**

The DMCA process is not a mechanism for asserting claims to individual words or public domain language elements. Starisian Technologies will not process, and expressly disclaims any obligation to process, DMCA Takedown Notices that purport to assert copyright or other IP rights in individual words, dictionary definitions (considered as facts), phonological or grammatical structures, or other unprotectable elements of language.

**10.5 Misuse of IP Process for Language Appropriation**

Any attempt to use the DMCA process or other IP enforcement mechanism available through the Platform to claim, control, or restrict access to individual words, public language facts, or unprotectable linguistic elements shall be considered an abuse of the IP enforcement process and may result in rejection of the notice, suspension of the submitting party's account, and such other remedies as are available under applicable law.

---

### Section 11 — General Provisions

**11.1 Relationship to Master Terms**

This IP/DMCA/DRM Policy is a module of and is incorporated into the Platform's Master Terms of Service. In the event of any conflict between this Policy and the Master Terms, the Master Terms shall control unless this Policy expressly provides otherwise with respect to a specific subject matter.

**11.2 Modifications**

Starisian Technologies reserves the right to modify this IP/DMCA/DRM Policy at any time. Modifications will be effective upon posting of the revised policy to the Platform or upon notice to Users as required by applicable law or the Master Terms. Continued use of the Platform following notice of modifications constitutes acceptance of the revised policy.

**11.3 Designated Agent Updates**

Starisian Technologies will maintain a current and accurate registration of its Designated Agent with the United States Copyright Office and will update the Designated Agent contact information on the Platform as required by 37 C.F.R. § 201.38. Users should check the Platform's legal page for the most current Designated Agent contact information.

**11.4 Record Retention**

Starisian Technologies will maintain records of Takedown Notices received, Counter-Notices received, and actions taken in response thereto, for such period as is required by applicable law and as is reasonably necessary to support the Platform's Safe Harbor compliance and Repeat Infringer policy.

**11.5 Contact**

Questions regarding this IP/DMCA/DRM Policy, DMCA notices, counter-notices, and DRM compliance matters may be directed to Starisian Technologies at the contact information provided on the Platform's legal page or to the Designated Agent at the address set forth in Section 4.2.

**11.6 Severability**

If any provision of this IP/DMCA/DRM Policy is found to be unenforceable or invalid under applicable law, that provision shall be modified to the minimum extent necessary to make it enforceable, and the remaining provisions shall continue in full force and effect.

**11.7 No Legal Advice**

This IP/DMCA/DRM Policy does not constitute legal advice. Users and rights holders with questions about their specific legal situation should consult qualified legal counsel.

---

## Attestation Record

| Field | Value |
|---|---|
| Version | — |
| SHA-256 Hash | — |
| Attested Date | — |
| Attestation Method | — |
| Attested By | — |

---

*This document is a draft for lawyer review. It has not been reviewed by legal counsel and does not constitute legal advice. All policy documents must be reviewed and approved by qualified legal counsel before publication.*
