---
version: 0.1.0
date: 2026-04-18
status: drafting
jurisdiction: California
supersedes: none
policyType: master
dependsOnMasterTerms: false
sourceModels:
  - OpenAI Terms of Service (structural reference — AI/data/use complexity)
  - Microsoft Services Agreement (structural reference — platform/legal structure)
  - Google Terms of Service (structural reference — layered service language)
  - YouTube Terms of Service (structural reference — user-submitted content logic)
---

# Master Terms of Service

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
> **Master Terms note:** This document governs all PLATFORM activity. SITE OWNER-level policies may supplement but may not override PLATFORM OPERATOR-level rules on infrastructure, security, enforcement, AI processing, or data handling.

---

## Plain Language Summary

*Layer 1 — Human Readable. Written at Grade 8 reading level. Uses "you" and "we". Short sentences. No passive voice where avoidable.*

> What this policy means for you.

> **Who is "we" in this document?**
> On Platform Domains (*.sparxstar.com), **"we"** and **"us"** refer to **PLATFORM OPERATOR** (Starisian Technologies, LLC), which is also the SITE OWNER.
> On Mapped Custom Domains, the baseline PLATFORM rules are from PLATFORM OPERATOR; end-user-facing obligations belong to SITE OWNER (the Client Operator for that domain).
> References to "the seller," "the operator," or "the site owner" in this summary refer to SITE OWNER unless otherwise stated.

**What we do:** PLATFORM OPERATOR (Starisian Technologies, LLC) runs the SPARXSTAR PLATFORM and provides technology, hosting, and services to websites and apps built on top of it.

**What you can do:** END USERS may use the PLATFORM and any site built on it to create accounts, post content, buy products, and use features offered by that site.

**What is not allowed:** END USERS may not use the PLATFORM for illegal activity, abuse, spam, harassment, or to violate anyone's rights.

---

When you use the SPARXSTAR platform — or any website or app powered by SPARXSTAR — you are agreeing to these terms. SPARXSTAR is a technology platform run by Starisian Technologies, LLC. We provide the infrastructure that other businesses and creators use to run their own sites and services.

The site or brand you are visiting may be a separate business that uses our platform. That business is called the "operator." They set their own rules for their site, but those rules must stay within the limits we set. Think of us like a shopping mall — the stores inside make their own choices, but mall rules still apply everywhere.

We are not the seller of products or services on sites operated by third-party operators. If you buy something from a site powered by SPARXSTAR, the seller is that site's operator, not us. We may handle some backend tasks like hosting, payments processing, or shipping support, but that does not make us the business you are dealing with. The invoice and the contact information on the site tell you who the seller is.

When you post content — such as photos, writing, music, or other creative work — you keep ownership of that work. You give us permission to host it, display it, and use it to operate the platform. We may also use content to improve our services, including AI systems, but we do not claim to own your original creative work.

---

## Full Legal Text

*Layer 2 — Legally Enforceable. In the event of any conflict between this section and the Plain Language Summary above, this section governs.*

---

### 1. Definitions

As used in these Master Terms of Service, the following terms have the meanings set forth below. Defined terms are capitalized throughout this document.

**1.1 "Company"** means Starisian Technologies, LLC, a limited liability company organized under the laws of the State of California, and its successors and permitted assigns. The Company operates under the brand name SPARXSTAR.

**1.2 "Platform"** means the SPARXSTAR platform, including all technology infrastructure, software, APIs, tooling, hosting environments, processing systems, AI systems, databases, content delivery networks, payment processing integrations, fulfillment integrations, support systems, and related services operated, provided, or subcontracted by the Company, whether accessed via a SPARXSTAR-branded domain or a mapped client custom domain.

**1.3 "Services"** means any and all products, features, functions, tools, applications, platforms, APIs, content, data, or services offered, operated, hosted, processed, or provided by or through the Company or the Platform, including but not limited to hosting, publishing, e-commerce, streaming, ticketing, digital distribution, AI-assisted tools, community features, analytics, and support services.

**1.4 "User"** means any natural person who accesses, browses, registers, or uses the Platform or any Services, whether authenticated or unauthenticated.

**1.5 "End User"** means a User who accesses or uses Services through a site, application, or product operated by a Client Operator, rather than directly through a Company-branded domain.

**1.6 "Operator"** or **"Client Operator"** means any business, individual, organization, or entity that has contracted with the Company to use the Platform as infrastructure for operating their own site, application, storefront, community, or service. A Client Operator is a separate legal entity from the Company and is responsible for their own site-level terms, policies, and customer relationships.

**1.7 "Content"** means any text, data, images, photographs, audio, video, music, software code, documents, files, metadata, structured data, annotations, translations, or other materials, in any form or medium.

**1.8 "User Content"** means Content that a User submits, uploads, creates, posts, publishes, transmits, or otherwise provides to or through the Platform or Services.

**1.9 "Platform Content"** means Content created, generated, owned, licensed, structured, annotated, or curated by the Company, including but not limited to software, documentation, platform-generated outputs, structured datasets, semantic mappings, curated lexicons, analytics outputs, and AI-generated content produced by or through Company systems.

**1.10 "Operator Content"** means Content provided to the Platform by a Client Operator for use in connection with their site or services, including product listings, descriptions, branding, marketing materials, and operator-specific configurations.

**1.11 "Account"** means a registered user profile created by a User on the Platform or on a site operated by a Client Operator using Platform infrastructure.

**1.12 "Subcontractor"** means any employee, contractor, subcontractor, vendor, affiliate, third-party service provider, AI provider, cloud infrastructure provider, payment processor, logistics provider, printer, shipper, moderation service, support service provider, or other party engaged by the Company to perform any function or provide any service in connection with the Platform or Services.

**1.13 "Platform Domain"** means any domain or subdomain under sparxstar.com or other domains operated directly by the Company.

**1.14 "Mapped Custom Domain"** means a domain owned and configured by a Client Operator and mapped to the Platform infrastructure, appearing to End Users as the Client Operator's branded site.

**1.15 "Effective Date"** means the date on which a User first accesses, uses, or registers on the Platform or Services, whichever is earliest.

**1.16 "Affiliate"** means, with respect to a party, any entity that directly or indirectly controls, is controlled by, or is under common control with that party, where "control" means ownership of more than fifty percent (50%) of the voting securities or equivalent controlling interest.

**1.17 "Applicable Law"** means all applicable local, state, national, and international laws, regulations, rules, orders, directives, and standards, including but not limited to data protection laws, consumer protection laws, intellectual property laws, export control laws, and anti-money laundering laws.

**1.18 "AI-Assisted Output"** means any text, image, audio, video, code, translation, transcription, annotation, classification, structured data record, or other material produced in whole or in part by an AI System operating on the Platform, whether in response to a User input, as part of an automated pipeline, or as a Platform-initiated generation. The term "AI-Assisted Outputs" as used in these Terms has the same meaning as defined in the AI Chat and AI Use Policy (Section 1.1) and is incorporated herein by reference.

---

### 2. Scope and Applicability

**2.1 Agreement.** These Master Terms of Service ("Terms") constitute a legally binding agreement between You and the Company governing Your access to and use of the Platform and Services. By accessing or using the Platform in any manner, You agree to be bound by these Terms. If You do not agree, You must not use the Platform or Services.

**2.2 Policy Hierarchy.** These Terms are the baseline governing document for the Platform. The following hierarchy applies:

  (a) **Company platform-level policies** — including these Terms, the Privacy Policy, the Cookie Policy, the Content Policy, the Acceptable Use Policy, and other Company-issued platform-level documents — form the baseline applicable to all use of the Platform regardless of domain or operator.

  (b) **Client Operator site-level policies** — including any site-specific terms of service, sale terms, shipping policies, return policies, or community standards published by a Client Operator — apply to the End User relationship with that Client Operator, and are supplemental to Company platform-level policies.

  (c) Client Operator site-level policies may impose additional requirements or restrictions, but may not reduce, override, or waive: (i) Company platform-level security, infrastructure, and enforcement rules; (ii) Company data handling and privacy policies at the platform layer; (iii) Company rules governing AI processing; (iv) Company rules governing abuse prevention and moderation; or (v) any other Company-level rule expressly designated as non-waivable.

**2.3 Domain-Based Policy Application.**

  (a) **Platform Domains (*.sparxstar.com and Company-operated domains):** Company policies are primary. All Users accessing Services through a Platform Domain are dealing directly with the Company as the platform operator. Company-facing terms, disclosures, and policies apply in full.

  (b) **Mapped Custom Domains:** Where a Client Operator has mapped a custom domain to the Platform, Client Operator site-level policies are primary for the End User relationship with that Client Operator. However, Company platform-level policies continue to apply at the infrastructure, processing, and enforcement layer regardless of which domain is displayed to the End User.

  (c) The Company does not represent that End Users on Mapped Custom Domains are Company customers. The End User relationship on a Mapped Custom Domain is between the End User and the Client Operator.

**2.4 Incorporation of Additional Policies.** The following additional policies are incorporated into these Terms by reference and form part of the overall agreement governing use of the Platform: Privacy Policy; Cookie Policy; Content Policy; Acceptable Use Policy; and any other policies published by the Company and designated as Platform policies. In the event of conflict between these Terms and an incorporated policy, these Terms govern unless the incorporated policy expressly states otherwise.

**2.5 Eligibility.** The Platform and Services are intended for Users who are at least thirteen (13) years of age. Users between thirteen (13) and eighteen (18) years of age may only use the Platform with the consent and supervision of a parent or legal guardian. By using the Platform, You represent and warrant that You meet these eligibility requirements. The Company does not knowingly provide Services to children under thirteen (13) without verified parental consent in compliance with the Children's Online Privacy Protection Act ("COPPA") and applicable law.

**2.6 Business Users.** If You use the Platform on behalf of a company, organization, or other legal entity, You represent and warrant that You have authority to bind that entity to these Terms, and "You" refers to that entity. The entity and the individual accessing the Platform on its behalf are jointly and severally responsible for compliance with these Terms.

---

### 3. The Platform and Company's Role

**3.1 Platform as Infrastructure Provider.** The Company operates the Platform as technology and infrastructure. The Company's role is analogous to a technology infrastructure provider that enables third-party businesses to operate their own sites, storefronts, communities, and services. The provision of infrastructure, hosting, processing, fulfillment support, payment support, shipping support, content delivery, moderation assistance, AI processing, or any other backend function by the Company does not make the Company the seller, merchant of record, publisher, advertiser, employer, or public-facing operator of any Client Operator site.

**3.2 Seller Identity.** The seller of any goods or services on a Client Operator site is the Client Operator or the business entity publicly identified on that site as the seller, including but not limited to the name and contact information shown on invoices, checkout pages, product listings, and site branding. Users seeking remedies related to purchases from a Client Operator site should direct those inquiries to the Client Operator, not to the Company.

**3.3 Company's Limited Liability for Client Operator Activities.** The Company is not responsible for the acts, omissions, products, services, content, representations, or policies of Client Operators or their End Users. The Company does not endorse any Client Operator, their business, their products, or their content. The Company does not guarantee the performance, quality, accuracy, or legality of any Client Operator offering.

**3.4 Backend Fulfillment.** The Company may, at the election of a Client Operator, perform backend fulfillment functions including but not limited to order processing, print-on-demand production, drop-shipping coordination, digital file delivery, ticket delivery, email dispatch, and customer support routing. Performance of any such backend function does not:
  (a) make the Company the seller or merchant of record;
  (b) create a direct contractual relationship between the Company and the End User with respect to that purchase;
  (c) impose on the Company any obligation to issue refunds, accept returns, or provide warranty directly to the End User; or
  (d) make the Company the employer, principal, or sponsor of the Client Operator's business.

---

### 4. Accounts

**4.1 Account Registration.** To access certain features of the Platform or Services, You may be required to create an Account. You agree to provide accurate, current, and complete information when creating an Account and to update such information as necessary to keep it accurate.

**4.2 Account Security.** You are responsible for maintaining the confidentiality and security of Your Account credentials. You are responsible for all activity that occurs under Your Account, whether or not authorized by You. You agree to notify the Company promptly if You become aware of any unauthorized access to or use of Your Account.

**4.3 Single Account.** Unless expressly authorized by the Company, each User may maintain only one Account. Creating multiple Accounts to circumvent moderation decisions, bans, or platform restrictions is prohibited.

**4.4 Account Transfers.** Accounts are personal and non-transferable unless the Company expressly authorizes transfer in writing.

---

### 5. Acceptable Use

**5.1 Permitted Use.** You may access and use the Platform and Services solely for lawful purposes and in accordance with these Terms, Applicable Law, and any applicable Client Operator policies.

**5.2 Prohibited Conduct.** You agree not to:

  (a) Use the Platform for any unlawful purpose or in violation of Applicable Law;

  (b) Post, transmit, or distribute Content that is defamatory, fraudulent, deceptive, threatening, harassing, abusive, obscene, or that violates any third party's rights;

  (c) Infringe or misappropriate any intellectual property rights, including copyright, trademark, patent, trade secret, or right of publicity;

  (d) Engage in spam, phishing, unsolicited commercial messaging, or deceptive marketing practices;

  (e) Distribute malware, viruses, bots, spyware, or other harmful code;

  (f) Attempt to gain unauthorized access to any system, network, account, or data;

  (g) Interfere with or disrupt the Platform, its infrastructure, or other Users' use of the Platform;

  (h) Scrape, crawl, extract, or mass-download Platform data without express written authorization from the Company;

  (i) Circumvent, disable, or interfere with any security, access control, or usage limitation feature of the Platform;

  (j) Use the Platform to facilitate or promote any conduct that the Company, in its reasonable discretion, determines to be harmful, abusive, exploitative, or contrary to the interests of the platform community;

  (k) Impersonate any person, entity, or brand, or misrepresent Your affiliation with any person or entity;

  (l) Use the Platform or Services in any manner that could damage, disable, overburden, or impair the Platform or interfere with any other party's use.

**5.3 Client Operator Compliance.** Client Operators are additionally bound by the Client Operator Agreement and any applicable platform compliance policies, including policies governing content moderation, data handling, use of AI tools, and prohibited verticals.

---

### 6. User Content and Intellectual Property

**6.1 User Ownership.** You retain all ownership rights in and to Your original User Content. These Terms do not transfer ownership of User Content to the Company.

**6.2 License Grant to the Company.** By submitting, uploading, or posting User Content to or through the Platform, You grant the Company a non-exclusive, worldwide, royalty-free, transferable, sublicensable (through multiple tiers) license to use, host, store, reproduce, process, modify for formatting purposes, translate, create derivative works from, display, perform, distribute, transmit, index, analyze, annotate, and otherwise exploit Your User Content in connection with:
  (a) the operation, maintenance, and improvement of the Platform and Services;
  (b) the delivery of Services to You and to other Users;
  (c) AI-assisted processing, quality assurance, moderation, and platform safety functions;
  (d) training, fine-tuning, and improving AI and machine learning systems operated by or on behalf of the Company;
  (e) building structured datasets, semantic mappings, curated lexicons, metadata structures, and other proprietary data assets of the Company, subject to the limitations in Section 6.6 below;
  (f) marketing and promotional activities, subject to applicable opt-out rights; and
  (g) any other purpose reasonably related to providing Services.

**6.2.1 Platform License to User for AI-assisted outputs.** Subject to the User's compliance with these Master Terms and applicable service terms, the Company grants the User a worldwide, non-exclusive, royalty-free license to use, reproduce, distribute, and create derivative works from AI-assisted outputs generated in response to that User's prompts, as described in the AI Chat and AI Use Policy, to the extent the Company holds any rights in such outputs and to the extent permitted by applicable law. This license is subject to the restrictions and conditions set forth in the AI Chat and AI Use Policy, including Section 9.

**6.3 License Duration.** The license granted in Section 6.2 continues for as long as the applicable User Content remains on the Platform. Where the Company retains derived works, structured datasets, or AI outputs generated from User Content, the license to those derivative works and outputs continues after removal of the original User Content, subject to applicable privacy, consumer protection, and data protection laws.

**6.4 Client Operator Sublicense.** Where User Content is submitted through a Client Operator site, the Company may sublicense the rights described in Section 6.2 to the applicable Client Operator for the limited purpose of operating and displaying the applicable site and Services.

**6.5 Work-Made-for-Hire Exclusion.** The license granted in Section 6.2 is not a work-made-for-hire arrangement with respect to ordinary platform Users. User Content submitted by Users in the ordinary course of platform use is not considered a work made for hire for the Company. Work-made-for-hire arrangements, where applicable, are limited to Company employees, contracted production parties, and expressly commissioned works governed by a separate written agreement designating the work as such.

**6.6 Language, Data, and Dataset Rights.**

  (a) The Company does not claim ownership of individual words, common phrases, or information that is part of the public domain or that represents uncopyrightable facts or language.

  (b) The Company does claim proprietary rights in: (i) structured linguistic datasets compiled, curated, annotated, or derived through the Platform; (ii) semantic mappings and curated lexicons produced by or through the Platform; (iii) metadata structures, taxonomies, and ontologies created by or for the Company; (iv) translations produced by or through Company systems to which the Company holds rights; (v) derived analytical outputs and AI-generated outputs produced by Company systems; and (vi) any other proprietary arrangement or structure that constitutes an original work of authorship or a protectable trade secret.

**6.7 Platform Content.** Platform Content is owned by or licensed to the Company. You may not copy, reproduce, distribute, modify, reverse-engineer, or exploit Platform Content except as expressly permitted by these Terms or by the Company in writing.

**6.8 Feedback.** If You provide suggestions, ideas, feedback, or recommendations regarding the Platform or Services ("Feedback"), You grant the Company an irrevocable, non-exclusive, worldwide, royalty-free license to use, incorporate, and exploit such Feedback without restriction or compensation to You.

**6.9 Representations Regarding User Content.** You represent and warrant that: (a) You own or have all necessary rights, licenses, and permissions to submit User Content and to grant the rights described in this Section 6; (b) Your User Content does not infringe any third-party rights; and (c) Your User Content complies with these Terms and Applicable Law.

---

### 7. Subcontracting and Service Providers

**7.1 Unrestricted Right to Subcontract.** The Company has the unrestricted right to use employees, Affiliates, contractors, Subcontractors, vendors, AI providers, cloud infrastructure providers, payment processors, logistics companies, printers, shippers, moderators, support providers, and any other service providers to perform any part of the Platform operations, Services, or any other function or obligation under these Terms. The Company may engage Subcontractors without prior notice to Users or Client Operators unless expressly required otherwise.

**7.2 No Third-Party Beneficiary Rights.** Subcontractors engaged by the Company do not have any obligations directly to Users or Client Operators by virtue of these Terms. Users and Client Operators have no recourse against Subcontractors under these Terms.

**7.3 Responsibility for Subcontractors.** The Company remains responsible for the performance of its obligations under these Terms notwithstanding the engagement of Subcontractors, except to the extent that failures are caused by events beyond the Company's reasonable control.

---

### 8. Third-Party Services and Links

**8.1 Third-Party Integrations.** The Platform may integrate with or link to third-party services, websites, platforms, or tools. These third-party services are governed by their own terms and privacy policies. The Company does not control, endorse, or assume responsibility for any third-party service or its content, privacy practices, or reliability.

**8.2 User Responsibility.** Your use of any third-party service in connection with the Platform is at Your sole risk. You are responsible for reviewing and agreeing to the terms of any third-party service You use.

---

### 9. Payments and Commerce

**9.1 Payment Processing.** The Platform may facilitate payment processing services through third-party payment processors. Payment transactions are subject to the terms and policies of the applicable payment processor. The Company does not guarantee the availability or security of any third-party payment processing service.

**9.2 Operator as Seller.** When You purchase goods or services through a Client Operator site, the Client Operator is the seller. The Company's processing of payment data or transaction data in connection with that purchase is a technical service provided to the Client Operator and does not make the Company the merchant of record, the seller, or the contracting party for that purchase.

**9.3 Disputes and Chargebacks.** Purchase disputes, chargebacks, refund requests, warranty claims, and similar consumer matters arising from transactions with Client Operators should be directed to the applicable Client Operator. The Company is not a party to those transactions and does not accept responsibility for Client Operator fulfillment obligations.

---

### 10. Privacy and Data

**10.1 Privacy Policy.** The Company's collection, use, and processing of personal data is governed by the Privacy Policy, which is incorporated into these Terms by reference. By using the Platform, You consent to the Company's data practices as described in the Privacy Policy.

**10.2 Platform-Level Data Processing.** The Company processes data at the platform level for all domains using Platform infrastructure, including Mapped Custom Domains, for the purposes of platform security, fraud prevention, abuse detection, analytics, AI processing, and platform operations. This platform-level processing occurs regardless of which domain a User accesses.

**10.3 Client Operator Data Responsibilities.** Client Operators are independently responsible for their data collection practices with respect to their End Users and are separate data controllers for the End User relationship. Client Operators must comply with all Applicable Laws regarding data collection, use, and disclosure in their own right.

---

### 11. Disclaimer of Warranties

**11.1 AS-IS BASIS.** THE PLATFORM AND SERVICES ARE PROVIDED ON AN "AS IS" AND "AS AVAILABLE" BASIS WITHOUT WARRANTIES OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, TITLE, NON-INFRINGEMENT, ACCURACY, RELIABILITY, COMPLETENESS, OR AVAILABILITY.

**11.2 NO GUARANTEE OF UPTIME OR AVAILABILITY.** THE COMPANY DOES NOT WARRANT THAT THE PLATFORM OR SERVICES WILL BE UNINTERRUPTED, ERROR-FREE, SECURE, OR FREE FROM VIRUSES OR OTHER HARMFUL COMPONENTS. THE COMPANY DOES NOT GUARANTEE THE ACCURACY, COMPLETENESS, OR RELIABILITY OF ANY CONTENT ON THE PLATFORM.

**11.3 AI-GENERATED CONTENT.** AI-ASSISTED FEATURES AND OUTPUTS ARE PROVIDED AS-IS AND MAY CONTAIN ERRORS, INACCURACIES, OR OUTDATED INFORMATION. THE COMPANY DOES NOT WARRANT THAT AI-GENERATED OUTPUTS ARE ACCURATE, COMPLETE, APPROPRIATE, OR FIT FOR ANY PARTICULAR PURPOSE. USERS ARE SOLELY RESPONSIBLE FOR EVALUATING AND VERIFYING AI-GENERATED OUTPUTS BEFORE RELYING ON THEM.

**11.4 CLIENT OPERATOR REPRESENTATIONS.** THE COMPANY MAKES NO WARRANTIES REGARDING THE REPRESENTATIONS, PRODUCTS, SERVICES, QUALITY, ACCURACY, OR LEGALITY OF ANY CLIENT OPERATOR OFFERING.

---

### 12. Limitation of Liability

**12.1 EXCLUSION OF CONSEQUENTIAL DAMAGES.** TO THE FULLEST EXTENT PERMITTED BY APPLICABLE LAW, IN NO EVENT SHALL THE COMPANY, ITS AFFILIATES, OFFICERS, DIRECTORS, EMPLOYEES, AGENTS, LICENSORS, OR SUBCONTRACTORS BE LIABLE FOR ANY INDIRECT, INCIDENTAL, SPECIAL, CONSEQUENTIAL, PUNITIVE, OR EXEMPLARY DAMAGES, INCLUDING BUT NOT LIMITED TO LOSS OF PROFITS, REVENUE, DATA, GOODWILL, BUSINESS OPPORTUNITY, OR OTHER INTANGIBLE LOSSES, ARISING OUT OF OR IN CONNECTION WITH THESE TERMS OR YOUR USE OF OR INABILITY TO USE THE PLATFORM OR SERVICES, EVEN IF THE COMPANY HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGES.

**12.2 CAP ON LIABILITY.** TO THE FULLEST EXTENT PERMITTED BY APPLICABLE LAW, THE COMPANY'S TOTAL CUMULATIVE LIABILITY TO YOU FOR ANY CLAIMS ARISING OUT OF OR IN CONNECTION WITH THESE TERMS OR YOUR USE OF THE PLATFORM OR SERVICES SHALL NOT EXCEED THE GREATER OF: (A) THE AMOUNT YOU PAID TO THE COMPANY (NOT TO A CLIENT OPERATOR) IN THE TWELVE (12) MONTHS PRECEDING THE CLAIM; OR (B) ONE HUNDRED UNITED STATES DOLLARS (USD $100).

**12.3 ESSENTIAL BASIS.** THE LIMITATIONS IN THIS SECTION 12 REFLECT A REASONABLE ALLOCATION OF RISK BETWEEN THE PARTIES AND ARE AN ESSENTIAL BASIS OF THE BARGAIN BETWEEN THE PARTIES. THE COMPANY WOULD NOT PROVIDE THE PLATFORM OR SERVICES ABSENT THESE LIMITATIONS.

**12.4 EXCEPTIONS.** Nothing in this Section 12 limits liability for: (a) fraud or willful misconduct; (b) death or personal injury caused by gross negligence; or (c) any liability that cannot be excluded or limited under Applicable Law.

---

### 13. Indemnification

**13.1 User Indemnification.** You agree to defend, indemnify, and hold harmless the Company and its Affiliates, officers, directors, employees, agents, licensors, and Subcontractors from and against any claims, liabilities, damages, losses, costs, and expenses (including reasonable attorneys' fees) arising out of or in connection with:
  (a) Your use of the Platform or Services;
  (b) Your User Content;
  (c) Your breach of these Terms or any representation or warranty herein;
  (d) Your violation of any third-party rights, including intellectual property rights or privacy rights;
  (e) Your violation of Applicable Law; or
  (f) Any dispute between You and any other User or Client Operator.

**13.2 Client Operator Indemnification.** Client Operators additionally agree to indemnify the Company for claims arising from their site operations, their End Users' use of the site, their Operator Content, and their failure to comply with Applicable Law or their contractual obligations to End Users.

**13.3 Control of Defense.** The Company reserves the right, at its own expense, to assume exclusive defense and control of any matter subject to indemnification by You. You agree not to settle any such matter without the Company's prior written consent.

---

### 14. Account Suspension and Termination

**14.1 Company's Right to Suspend or Terminate.** The Company may suspend, restrict, or terminate Your Account and access to the Platform or Services at any time, with or without cause, and with or without prior notice, including but not limited to:
  (a) Breach of these Terms or any incorporated policy;
  (b) Conduct that the Company determines, in its reasonable discretion, to be harmful, abusive, or contrary to the interests of the platform community;
  (c) Fraudulent, deceptive, or illegal activity;
  (d) Failure to pay applicable fees;
  (e) Requests from law enforcement or government agencies;
  (f) Prolonged inactivity; or
  (g) Legal or regulatory requirements.

**14.2 Effect of Termination.** Upon termination of Your Account:
  (a) Your right to access and use the Platform and Services terminates immediately;
  (b) The Company may delete Your Account and associated data subject to applicable data retention obligations;
  (c) Provisions of these Terms that by their nature should survive termination shall survive, including without limitation Sections 6 (User Content and Intellectual Property), 11 (Disclaimer of Warranties), 12 (Limitation of Liability), 13 (Indemnification), 15 (Dispute Resolution), and 16 (Governing Law).

**14.3 User Right to Terminate.** You may terminate Your Account at any time by following the account deletion process provided by the Platform or by submitting a written termination request to the Company. Termination of Your Account does not affect any obligations incurred prior to termination.

---

### 15. Dispute Resolution and Arbitration

**15.1 Informal Resolution.** Before initiating formal dispute resolution, You agree to attempt to resolve any dispute informally by contacting the Company with a written description of the dispute. The Company will attempt to resolve disputes informally within thirty (30) days of receiving written notice.

**15.2 Binding Arbitration.** If informal resolution is unsuccessful, except as provided in Section 15.4, You and the Company agree that any dispute, claim, or controversy arising out of or relating to these Terms or the Platform (including claims of breach, tort, statute, fraud, or misrepresentation) shall be resolved by binding arbitration administered by JAMS under its applicable commercial arbitration rules, rather than in court.

**15.3 Arbitration Procedure.** The arbitration shall be conducted by a single arbitrator in the State of California, unless the parties agree otherwise. The arbitrator's award shall be final and binding and may be entered as a judgment in any court of competent jurisdiction. The Federal Arbitration Act governs the interpretation and enforcement of this arbitration provision.

**15.4 Exceptions to Arbitration.** Either party may seek: (a) provisional or emergency injunctive relief from a court of competent jurisdiction to prevent irreparable harm; (b) relief in small claims court for qualifying claims; and (c) enforcement of the arbitration award.

**15.5 Class Action Waiver.** TO THE FULLEST EXTENT PERMITTED BY APPLICABLE LAW, YOU WAIVE ANY RIGHT TO BRING OR PARTICIPATE IN ANY CLASS, COLLECTIVE, OR REPRESENTATIVE ACTION OR PROCEEDING IN CONNECTION WITH ANY DISPUTE ARISING UNDER THESE TERMS.

**15.6 Waiver of Jury Trial.** TO THE FULLEST EXTENT PERMITTED BY APPLICABLE LAW, BOTH PARTIES WAIVE ANY RIGHT TO A JURY TRIAL IN CONNECTION WITH ANY DISPUTE ARISING UNDER THESE TERMS.

**15.7 Time Limitation.** Any claim or dispute under these Terms must be filed within one (1) year of the date the claim arose, or it is permanently barred.

---

### 16. Governing Law and Jurisdiction

**16.1 Governing Law.** These Terms and all matters arising out of or relating to them shall be governed by and construed in accordance with the laws of the State of California, United States of America, without regard to conflict of law principles that would require application of the laws of any other jurisdiction.

**16.2 Venue.** For any proceedings not subject to arbitration under Section 15, each party irrevocably submits to the exclusive personal jurisdiction and venue of the state and federal courts located in the County of Los Angeles, State of California.

**16.3 Export Compliance.** You represent and warrant that You are not located in, under the control of, or a national or resident of any country subject to United States embargo or sanctions, and that You are not on any restricted or prohibited persons list. You agree to comply with all applicable export control and sanctions laws.

---

### 17. Modifications to the Platform and Services

**17.1 Right to Modify.** The Company reserves the right to modify, suspend, discontinue, add, or remove any feature, function, or element of the Platform or Services at any time with or without notice. The Company shall not be liable to You or any third party for any modification, suspension, or discontinuation of Services.

**17.2 Maintenance.** The Company may perform scheduled or emergency maintenance that temporarily interrupts access to the Platform. The Company will use reasonable efforts to minimize disruption.

---

### 18. Changes to These Terms

**18.1 Amendment Right.** The Company reserves the right to amend, update, or replace these Terms at any time. The Company will provide notice of material changes by: (a) updating the version number and date in the document header; (b) posting a notice on the Platform; or (c) sending notice to the email address associated with Your Account, at the Company's discretion.

**18.2 Continued Use.** Your continued access to or use of the Platform or Services after the effective date of any amendment constitutes Your acceptance of the amended Terms. If You do not agree to the amended Terms, You must stop using the Platform and Services and may terminate Your Account.

**18.3 Version History.** Prior versions of these Terms are maintained in the Company's policy version repository for reference.

---

### 19. General Provisions

**19.1 Entire Agreement.** These Terms, together with all incorporated policies and any applicable Client Operator agreements, constitute the entire agreement between You and the Company regarding the subject matter hereof and supersede all prior or contemporaneous agreements, representations, and understandings.

**19.2 Severability.** If any provision of these Terms is held invalid, unenforceable, or void by a court of competent jurisdiction, that provision shall be modified to the minimum extent necessary to make it enforceable, and the remaining provisions shall continue in full force and effect.

**19.3 Waiver.** No waiver of any right or provision of these Terms shall be effective unless in writing. No waiver shall constitute a waiver of any other right or provision or a continuing waiver.

**19.4 Assignment.** You may not assign or transfer Your rights or obligations under these Terms without the Company's prior written consent. The Company may assign or transfer its rights and obligations under these Terms without restriction, including in connection with a merger, acquisition, or sale of assets.

**19.5 Force Majeure.** The Company shall not be liable for any delay or failure in performance resulting from causes beyond its reasonable control, including acts of God, natural disasters, governmental actions, labor disputes, internet outages, or cyberattacks.

**19.6 Notices.** Notices to the Company must be submitted in writing through the contact method designated in Section 20. Notices to Users may be delivered by email, in-platform notification, or posting on the Platform.

**19.7 Headings.** Section headings are for reference only and do not affect the interpretation of these Terms.

**19.8 Language.** These Terms are written in English. Any translation provided is for convenience only. In the event of conflict between the English version and any translation, the English version governs.

---

### 20. Contact

**Starisian Technologies, LLC**
Legal Department
[Contact information — to be completed before publication]

For platform legal inquiries, please use the official contact form or designated legal inquiry channel published on the Company's website.

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
