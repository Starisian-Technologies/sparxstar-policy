---
version: 0.1.0
date: 2026-04-18
status: drafting
jurisdiction: California
supersedes: none
policyType: module
dependsOnMasterTerms: true
sourceModels:
  - OpenAI Usage Policy
  - Anthropic Acceptable Use Policy
---

# AI Chat and AI Use Policy

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
> **AI note:** PLATFORM OPERATOR operates AI systems at the PLATFORM layer. AI processing occurs on all domains using PLATFORM infrastructure regardless of SITE OWNER branding.

---

## Plain Language Summary

*Layer 1 — Human Readable. Written at Grade 8 reading level. Uses "you" and "we". Short sentences. No passive voice where avoidable.*

> What this policy means for you.

> **Who is "we" in this document?**
> **"We"** and **"us"** in this AI Chat and AI Use Policy refer to **PLATFORM OPERATOR** (Starisian Technologies, LLC) operating AI systems at the PLATFORM layer.
> AI processing occurs through PLATFORM infrastructure on all domains, including Mapped Custom Domains, regardless of SITE OWNER branding.

**What PLATFORM OPERATOR does:** PLATFORM OPERATOR provides AI-assisted features including chat, generation, translation, and language processing, and may use submitted content to improve AI systems.

**What you can do:** END USERS may use AI features for lawful personal and business purposes as permitted by this policy and applicable SITE OWNER terms.

**What is not allowed:** Using AI features to deceive, impersonate, generate illegal content, bypass platform systems, or violate any END USER's rights.

---

### What AI Features Do We Offer?

The SPARXSTAR platform uses artificial intelligence in several ways. We use AI to help you write and edit, translate content between languages, analyze the meaning of words and cultural materials, index and search content, recommend content you might like, and build structured databases of language and cultural knowledge. AI West Africa (AIWA) is a part of our ecosystem that focuses especially on using AI for language processing, content aggregation, and translation — particularly for African languages and cultural materials.

### Words vs. Databases — What We Own

Here is something important to understand. Individual words are not owned by anyone — not by you, not by us. A word is a public linguistic fact. But when we build a structured database of words, meanings, relationships, and contexts — organizing them carefully and creating something that did not exist before — that database is our intellectual property. The same applies to our semantic maps (organized networks of meaning), curated lexicons, and the structured outputs our AI systems produce. We do not own the words; we own the organized structure.

### How We May Use Your Content for AI

When you submit content to the platform — songs, writing, recordings, images — we may use it to improve our AI systems. This is called AI training. We will ask for your consent before we do this, and you can opt out through your account settings. There are some hard limits though: sacred cultural content (TK Red), restricted traditional knowledge content (TK Yellow pending community review), and sacred content of any kind will never be used for AI training, full stop. These limits exist in our system and cannot be turned off.

There is also a difference between training and inference. Training means we use your content to teach the AI system over time. Inference means the AI is processing your input right now, in real time, to give you a result — like a translation or a search result. Inference happens every time you use an AI feature; training is a separate process that requires your consent.

### Word Extraction for AIWA Services

If you use services connected to AI West Africa (AIWA), word extraction may be a required part of the service. This means our systems will identify, analyze, and record individual words and their meanings from your content as part of how the service works. By using these services, you agree to this process. Again — we do not own the individual words we extract; we own the structured database we build from them.

### Who Owns AI Outputs?

When you use our AI tools and give a prompt or input, the output may be co-owned — by you (for the creative input you gave) and by us (for the platform systems that generated it), depending on the specific terms that apply to the service you used. We will specify ownership for each AI service. Platform AI outputs that are not based on your specific content or prompts belong entirely to us.

### What You Cannot Use AI For

You cannot use our AI tools to: deceive or defraud anyone, generate child sexual abuse material, impersonate real people in misleading ways, spread disinformation, attack our systems or others' systems, or get around our platform safety rules. We enforce these limits technically and will suspend or terminate accounts that violate them.

### AI and Your Rights

If an AI system is making a decision that affects your account — like a content review decision — you have the right to know that AI was involved. You can request human review of AI-assisted decisions that affect you. We are committed to transparency about where and how AI operates on our platform.

---

## Full Legal Text

*Layer 2 — Legally Enforceable. In the event of any conflict between this section and the Plain Language Summary above, this section governs.*

---

### 1. Definitions

For the purposes of this AI Chat and AI Use Policy, the following definitions apply:

**1.1 "AI-Assisted Output"** means any text, image, audio, video, code, translation, transcription, annotation, classification, structured data record, or other material produced in whole or in part by an AI System operating on the Platform, whether in response to a User input, as part of an automated pipeline, or as a Platform-initiated generation.

**1.2 "AI Feature"** means any user-accessible capability, tool, interface, or workflow on the Platform that employs an AI System to process inputs and produce outputs for Users, including but not limited to: chat assistance, content generation, translation, language analysis, content recommendation, semantic search, content indexing, Word Extraction, and AI-assisted content review.

**1.3 "AI Output Ownership"** means the allocation of intellectual property rights — including copyright, database rights, and related rights — in AI-Assisted Outputs between the User, the Company, and any applicable Client Operator, as determined by Section 11 of this Policy and applicable law.

**1.4 "AI System"** means any machine learning model, neural network, large language model, natural language processing pipeline, image recognition system, audio analysis model, recommendation engine, or other computational system that learns from data and produces outputs without being explicitly programmed for each specific task, whether developed by the Company or licensed from a third-party AI provider.

**1.5 "AIWA"** or **"AI West Africa"** means the Gambian-based publishing, aggregation, and language technology initiative operating within the SPARXSTAR ecosystem, partly owned by Starisian Technologies, LLC, which uses AI systems for content aggregation, translation, language processing, and cultural heritage documentation.

**1.6 "Authorized Community Representative"** means an individual formally recognized by a cultural community or traditional knowledge-holding body as having the authority to grant or withhold consent on behalf of that community with respect to culturally affiliated content.

**1.7 "Client Operator" or "Operator"** means any business or individual entity that has entered into a separate agreement with the Company to deploy, configure, or brand a Platform instance or subdomain.

**1.8 "Company"** means Starisian Technologies, LLC, a California limited liability company, the owner and operator of the Platform.

**1.9 "Curated Lexicon"** means an organized, annotated collection of words, terms, phrases, or linguistic units, together with definitions, contextual meanings, usage examples, cultural notes, language metadata, and semantic relationships, that has been assembled, structured, or curated by or through Platform systems or the AIWA initiative.

**1.10 "Designated Sacred Authority"** means an elder or formally designated ceremonial authority whose express authorization is required before Sacred Content or TK Red Content may be processed, distributed, or used in any form on or through the Platform.

**1.11 "DVE Governance"** means the Platform's Dynamic Values Enforcement system, the technical enforcement layer that operationalizes consent records, content classifications, and policy rules as automated access controls, processing permissions, AI pipeline authorizations, and distribution restrictions.

**1.12 "Inference"** means the real-time application of a trained AI System to a User's input or content for the purpose of producing an output — including but not limited to: generating a response to a chat prompt, translating a text, classifying content, recommending related material, or extracting structural data — without altering the underlying model weights of the AI System.

**1.13 "Platform"** means the SPARXSTAR platform infrastructure, services, APIs, applications, and associated services operated by Starisian Technologies, LLC.

**1.14 "Sacred Content"** means any content identified as TK Red, or equivalently designated by a cultural community or Designated Sacred Authority as holding sacred, ceremonially restricted, or spiritually sensitive status, the processing or use of which requires Designated Sacred Authority authorization.

**1.15 "Semantic Mapping"** means a structured representation of the relationships between words, concepts, entities, or meanings — including synonym relationships, semantic similarity scores, ontological hierarchies, conceptual graphs, and topic clusters — created, maintained, or curated by Platform systems, whether derived from User Content, publicly available linguistic data, or AI System outputs.

**1.16 "Structured Dataset"** means a systematically organized collection of data records — including word definitions, semantic relationships, content classifications, linguistic annotations, cultural notes, translation pairs, and other structured representations of linguistic or cultural information — compiled, curated, or created by or through Platform systems as a distinct proprietary asset.

**1.17 "TK Content"** means any content associated with Traditional Knowledge, indigenous cultural heritage, oral traditions, or community-held cultural expressions subject to Traditional Knowledge label designations.

**1.18 "TK Red Content"** means TK Content designated as sacred, ceremonially restricted, or closed, the processing or use of which requires Designated Sacred Authority authorization.

**1.19 "TK Yellow Content"** means TK Content designated as restricted or culturally sensitive, the commercial use, AI processing, or broad distribution of which requires Authorized Community Representative authorization.

**1.20 "Training Data"** means content — including User Content, Platform Content, licensed third-party content, or publicly available data — used as input to train, fine-tune, validate, test, or otherwise improve an AI System's model weights, parameters, or performance.

**1.21 "Training"** means the process of exposing an AI System to Training Data in order to develop or refine the AI System's model weights, parameters, or capabilities, distinct from Inference, which operates on a pre-trained model without modifying its underlying weights.

**1.22 "User"** means any natural person who accesses or uses the Platform, whether through a direct Company-operated interface or through a Client Operator-branded interface.

**1.23 "Word Extraction"** means the process by which Platform AI Systems identify, isolate, parse, annotate, and index individual words, morphemes, phrases, tokens, or other linguistic units from User Content, AI-Assisted Outputs, or other Platform data for purposes including but not limited to: lexicographic database construction, linguistic analysis, language model training, semantic indexing, translation memory construction, and cultural heritage documentation.

---

### 2. Scope and Applicability

**2.1 General Scope.** This Policy governs the use of all AI Features on the Platform, including but not limited to: AI chat assistants, AI-assisted content generation, AI translation services, AI-powered semantic search, AI content indexing, AI Word Extraction and linguistic analysis, AI content classification and moderation, AI-assisted content review and recommendation, and AI-generated Structured Datasets.

**2.2 AIWA Services.** This Policy applies to all AI Features provided through or in connection with AIWA. AIWA-specific disclosures are set forth in Section 14 of this Policy.

**2.3 Relationship to Other Policies.** This Policy supplements and is incorporated into the Master Terms of Service, the Content Policy, the Consent Policy, and the Privacy Policy. In the event of conflict, the Master Terms of Service govern.

**2.4 Operator Deployments.** Client Operators that deploy AI Features as part of their Platform deployment are bound by this Policy. Client Operators may restrict AI Feature availability for their users but may not configure AI Features to operate in a manner that violates this Policy.

---

### 3. Permitted Uses of AI Features

**3.1 Content Creation and Assistance.** Users may use AI Features to: (a) draft, edit, and improve written content; (b) generate creative works including text, images, audio, and other media formats where such generation is authorized by applicable service terms; (c) receive AI-assisted feedback on content quality, structure, or style; and (d) generate AI-assisted translations of content they have the right to translate.

**3.2 Language and Linguistic Services.** Users may use AI Features to: (a) translate content between supported languages; (b) receive linguistic analysis, grammar assistance, and language learning support; (c) access AI-assisted lexicographic resources and language databases; and (d) contribute to language documentation projects through AIWA-integrated services.

**3.3 Content Discovery and Organization.** Users may use AI Features to: (a) search Platform content through AI-enhanced semantic search; (b) receive AI-generated content recommendations; (c) organize and tag their own content using AI-assisted classification; and (d) access AI-generated summaries, previews, and accessibility representations of content.

**3.4 Research and Analysis.** Users may use AI Features to: (a) conduct research using Platform language resources; (b) access AI-generated analytical insights about content they have rights to analyze; and (c) build applications through Platform APIs that incorporate AI Feature outputs, subject to API terms of service.

---

### 4. Prohibited Uses of AI Features

**4.1 Deception and Fraud.** Users may not use AI Features to: (a) generate content designed to deceive, defraud, or manipulate other Users, third parties, or the public; (b) create synthetic identities, fake accounts, or fraudulent credentials; (c) generate fraudulent reviews, ratings, endorsements, or testimonials; (d) produce disinformation or deliberately false factual claims intended to mislead; or (e) generate deepfakes or synthetic media designed to misrepresent a real person's statements, actions, or likeness without that person's consent.

**4.2 Illegal Content Generation.** Users may not use AI Features to generate: (a) child sexual abuse material (CSAM) or any sexual or sexualized depiction of minors; (b) content that facilitates, incites, or instructs acts of terrorism, mass violence, or organized violent extremism; (c) content promoting genocide or ethnic cleansing; (d) malware, phishing materials, or code designed to compromise computer systems; (e) content that violates applicable export control or sanctions laws; or (f) any other content that constitutes a criminal offense under applicable law.

**4.3 Impersonation.** Users may not use AI Features to: (a) generate content that impersonates a real, identifiable person in a manner likely to deceive a reasonable person; (b) generate content that falsely represents an AI-generated output as the original creative work of a specific human artist, author, or creator without that person's consent; or (c) generate content that impersonates the Company, AIWA, any Client Operator, or any representative thereof.

**4.4 Platform Circumvention.** Users may not use AI Features to: (a) circumvent, bypass, or disable Platform safety systems, content moderation pipelines, access controls, or rights management systems; (b) probe, extract, or reverse-engineer AI model weights, training data, or system architecture through adversarial prompting or other technical methods; (c) use AI Features to automate actions on the Platform in violation of applicable rate limits, terms of service, or API terms; or (d) generate inputs designed to cause AI Systems to produce outputs that violate this Policy or applicable law.

**4.5 Harm to Individuals.** Users may not use AI Features to: (a) generate content designed to harass, intimidate, threaten, or harm a specific individual; (b) generate content that constitutes non-consensual intimate imagery of identifiable individuals; (c) generate content that discloses private information about an identifiable individual without consent; or (d) generate content that incites others to commit violence against specific individuals or groups.

**4.6 AI Output Misrepresentation.** Users may not: (a) represent AI-Assisted Outputs as entirely human-created work in contexts where such misrepresentation would be material (including academic submissions governed by academic integrity policies, publication submissions requiring original authorship representations, and legal filings); or (b) submit AI-Assisted Outputs to the Platform labeled as non-AI content where accurate AI labeling is required by the Content Policy.

---

### 5. Training vs. Inference — Operational Distinction

**5.1 Inference Operations.** Every time a User activates an AI Feature — including sending a message to an AI chat tool, requesting a translation, performing a semantic search, or triggering an AI content analysis — Inference occurs. Inference processes the User's input in real time using a pre-trained AI System and returns an output without modifying the AI System's underlying model weights.

**5.2 Consent for Inference.** For AI Features that are integral to Platform services the User has agreed to use, Inference may occur without separate, feature-specific consent, as part of the service delivery. The existence of AI-powered features in a service is disclosed at the Platform level and in applicable service terms.

**5.3 Training Operations.** Training occurs when User Content or other Platform data is used as Training Data to develop, fine-tune, or improve an AI System's model weights or parameters. Training is a distinct operation from Inference and requires separate Consent, as governed by the Consent Policy Section 4.3.

**5.4 Default Training Consent.** For Users who have not adjusted their AI training consent settings, the Platform's default is: (a) Platform-generated structured data and aggregated anonymized outputs may be used for AI improvement; and (b) individual User Content is not used for AI Training without affirmative User consent. Users may review and adjust their Training consent settings in the account settings Privacy and Consent dashboard.

**5.5 No Reconstruction Guarantee.** The Platform does not guarantee that AI processing is lossless or that full original content can be reconstructed from AI-processed, trained, or indexed forms. AI systems compress, transform, and generalize Training Data during the training process. Once Training has occurred, individual content contributions cannot be isolated or extracted from trained model weights.

---

### 6. Structured Dataset Rights

**6.1 Platform Ownership.** Structured Datasets created by the Platform — including Semantic Mappings, Curated Lexicons, translation memories, linguistic annotation databases, cultural knowledge graphs, and other organized collections of AI-processed information — are proprietary Platform assets belonging to the Company.

**6.2 Original Compilation Work.** The compilation, organization, curation, annotation, and structuring of data into a Structured Dataset constitutes original intellectual work by the Platform. Platform ownership of Structured Datasets arises from this compilation and structuring work, independent of any individual data point or word the Dataset contains.

**6.3 No Ownership of Individual Words.** The Platform does not claim ownership of individual words, morphemes, phrases, public language facts, linguistic rules, or common expressions, regardless of whether they appear in a Structured Dataset. Individual words extracted from User Content are not owned by the Platform. Ownership attaches to the organized Dataset, not to its atomic linguistic components.

**6.4 User Contribution to Datasets.** The inclusion of representations derived from a User's Content in a Structured Dataset does not: (a) entitle the User to ownership of the Dataset; (b) entitle the User to compensation from the Dataset absent a separate written agreement; or (c) constitute a transfer of any rights in the underlying User Content to the Platform beyond the license granted in the Master Terms of Service.

**6.5 API Access.** Access to Platform Structured Datasets through APIs is subject to separate API terms of service and, where applicable, commercial licensing agreements.

**6.5.1 Survival of Dataset License.** The license granted in Section 6.5 with respect to User Content already incorporated into Structured Datasets, model training corpora, embeddings, statistical relationships, or trained model weights survives termination of the User's account or withdrawal of consent, to the extent that removal, retraining, reweighting, or disaggregation is not reasonably technically feasible, would require disproportionate effort or cost, or would materially impair the integrity, security, or operation of existing systems or models. Following a valid deletion request or withdrawal of consent, the Company will cease using the affected User Content for new model training or new Structured Dataset creation to the extent reasonably practicable. The Company will not use such surviving license rights to add new User Content to Structured Datasets following a valid withdrawal of consent or account deletion. Upon request, the Company will confirm in writing that no new processing of the User's Content has occurred following the withdrawal date. Nothing in this Section limits any non-waivable rights the User holds under applicable privacy or data protection law.

---

### 7. Word Extraction and Meaning Analysis

**7.1 General Authorization.** By using Platform AI Features that include linguistic processing — including translation, language analysis, semantic search, and content indexing — Users authorize the Platform to perform Word Extraction on their inputs and submitted content to the extent necessary for delivering the requested service.

**7.2 Mandatory Word Extraction for AIWA Services.** For Platform services that are integrated with AIWA — including but not limited to: African language translation services, cultural heritage documentation tools, oral history processing, indigenous language lexicographic services, and AIWA-connected publishing tools — Word Extraction and meaning analysis are mandatory components of the service. Users submitting Content to these services consent to Word Extraction as a condition of using the service.

**7.3 Word Ownership Limitation.** The Platform's rights in Word Extraction outputs are limited to the Structured Dataset level. The Platform: (a) does not own individual words or morphemes extracted from Content; (b) does not claim that public language facts revealed by Word Extraction are proprietary; and (c) does own the Curated Lexicons, Semantic Mappings, and Structured Datasets built from Word Extraction outputs.

**7.4 Extracted Meanings and Cultural Knowledge.** Where Word Extraction uncovers or documents culturally specific meanings, community-held knowledge, or indigenous language features, such extracted meanings may inform AIWA language resources. Community-level authorization requirements for TK Content under the Content Policy and Consent Policy apply to culturally specific meanings and knowledge, even in extracted form.

**7.5 Disclosure.** The Platform discloses which services involve Word Extraction and linguistic analysis in the applicable service-level descriptions and in the Layer B plain language summaries presented at the point of service enrollment.

**7.6 DVE Provenance Tracking.** The Platform's DVE Governance layer maintains content provenance records throughout the Word Extraction and processing pipeline to ensure that TK classifications and consent restrictions assigned at the point of ingestion are preserved and enforced at every stage of processing and output.

**7.6.1 Provenance Tracking Requirement.** Where Word Extraction involves or may involve TK Content, the Platform's technical systems are designed to track content provenance through the extraction pipeline in order to ensure that TK classifications and restrictions applicable at the point of ingestion are preserved and enforced at the point of output. The Company will implement reasonable technical and organizational measures designed to prevent TK-restricted extracted outputs from surfacing in general lexicons, public datasets, or AI systems from which the applicable TK restrictions have been removed. This obligation applies regardless of whether the TK classification was assigned by the User at submission or identified by Platform systems during processing.

---

### 8. Sacred and TK Content — AI Exclusion

**8.1 Categorical AI Training Exclusion.** The following categories of content are categorically excluded from AI Training regardless of User consent settings, Operator configuration, Authorized Community Representative authorization, or any other purported permission:

(a) TK Red Content;
(b) Sacred Content;
(c) TK Yellow Content pending Authorized Community Representative review;
(d) TK Yellow Content for which the Authorized Community Representative has not expressly consented to AI Training in writing.

**8.2 DVE Enforcement.** The AI Training exclusions in Section 8.1 are enforced at the DVE Governance layer. These exclusions cannot be overridden through User settings, Operator configuration, API access, or any other technical mechanism.

**8.3 AI Inference Restrictions for Sacred Content.** For TK Red Content and Sacred Content that has been authorized for limited Platform presence by a Designated Sacred Authority, AI Inference operations are limited to the scope expressly authorized by the Designated Sacred Authority. The Platform will not apply AI analysis, indexing, or processing to TK Red or Sacred Content beyond the authorized scope without obtaining additional authorization.

**8.4 No Commercialization Through AI.** The Platform will not use AI Systems to commercialize, monetize, or derive commercial value from TK Red Content, Sacred Content, or restricted TK Yellow Content, whether through direct sale of AI outputs, licensing of AI-generated derivatives, or inclusion of such content in commercial AI products or services.

---

### 9. AI Output Ownership

**9.1 User-Prompted Outputs.** For AI-Assisted Outputs generated in response to specific User prompts or User-submitted inputs: (a) the User retains all rights they hold in the original prompt, input content, and any creative contributions they made to the output; (b) to the extent the AI-Assisted Output constitutes a copyrightable work under applicable law, the allocation of rights between the User and the Platform is governed by the applicable service terms for the specific AI Feature used; (c) where no specific service terms address the ownership of AI-Assisted Outputs, the Company disclaims ownership of such Outputs to the extent they are legally capable of private ownership and grants the User a non-exclusive license to use those Outputs as set out in Section 6.2.1 of the Master Terms of Service.

**9.2 Platform-Generated Outputs.** AI-Assisted Outputs generated by Platform systems autonomously — without a specific User prompt and not derived from a specific User's Content — are Platform Content owned by the Company. This includes: (a) Platform-generated Structured Datasets; (b) Semantic Mappings and Curated Lexicons; (c) abstracted, aggregated, or statistically transformed forms of AI-Assisted Outputs incorporated into Structured Datasets, Semantic Mappings, and other Platform systems, provided that such incorporation does not reproduce the User's original expressive content in a manner reasonably capable of identifying the originating User or reproducing protectable expressive elements of the original content; and (d) AI-generated editorial curation, promotional content, and platform communications.

**9.3 No Copyright in AI Training Data Inputs Alone.** The submission of content as Training Data does not, by itself, give the User any ownership rights in AI-Assisted Outputs generated by the trained model, absent a separate agreement.

**9.4 Limitations of AI Copyright.** To the extent that AI-Assisted Outputs lack sufficient human authorship to qualify for copyright protection under applicable law, such outputs are not copyrighted. The Company makes no warranty as to the copyrightability of AI-Assisted Outputs provided to Users.

**9.5 Third-Party Rights in Outputs.** AI-Assisted Outputs may incorporate or be derived from third-party content. Users are responsible for reviewing AI-Assisted Outputs for potential third-party rights issues before publishing, distributing, or commercially exploiting such outputs.

---

### 10. Transparency and User Rights

**10.1 Disclosure of AI Use.** The Platform will disclose to Users: (a) which Platform features and services employ AI Systems; (b) the general categories of data used to train the AI Systems used in each feature; (c) whether and how User Content may be used for AI Training; and (d) changes to AI System use that materially affect Users, with appropriate notice.

**10.2 Right to Know About AI Decisions.** Where an AI System makes or substantially influences a decision that has a significant effect on a User — including content removal decisions, account restriction decisions, and access control decisions — the User has the right to: (a) be informed that AI was involved in the decision; (b) receive a plain language explanation of the factors the AI System weighed; and (c) request human review of the decision.

**10.3 Human Review Request.** Users may request human review of AI-assisted decisions that affect their accounts or content by submitting a request through the account settings "Content Decisions" section or by contacting the Legal Department at the information in Section 17. Human review requests will be addressed within a commercially reasonable time.

**10.4 AI System Updates.** The Platform may update, replace, or modify the AI Systems used to deliver Platform features. Material changes to AI System capabilities or data practices will be communicated to Users through platform notifications and Policy updates.

---

### 11. No Full Reconstruction Promise

**11.1 Lossy Processing.** The Platform does not guarantee that AI processing of User Content is lossless. AI systems — including transcription models, translation models, summarization models, and embedding models — may alter, compress, simplify, or transform Content in ways that make full reconstruction of the original from the processed form impossible or impractical.

**11.2 No Liability for Processing Transformations.** The Platform is not liable for: (a) differences between original User Content and AI-processed representations of that Content; (b) loss of nuance, cultural meaning, or contextual detail in AI-generated translations; (c) inaccuracies in AI-generated transcriptions or classifications; or (d) any other transformation or loss of fidelity that occurs within the scope of authorized AI processing.

**11.3 Originals Preservation Recommendation.** Users are strongly advised to retain originals of all Content they submit to the Platform and not to rely on Platform systems for primary archival preservation of valuable works.

---

### 12. Prohibited AI Use Enforcement

**12.1 Technical Enforcement.** Prohibited uses of AI Features are enforced through DVE Governance controls, content safety classifiers, automated moderation pipelines, and access controls embedded in AI Feature APIs.

**12.2 Account Consequences.** Violation of the Prohibited Uses in Section 4 may result in: (a) immediate suspension or termination of AI Feature access; (b) suspension or termination of the User's Platform account; (c) removal of violating Content; and (d) reporting to applicable law enforcement or regulatory authorities where required by law.

**12.3 No Circumvention.** Any technical attempt to circumvent AI safety systems, content filters, or prohibited use controls is itself a violation of this Policy, regardless of whether the attempt succeeds in producing prohibited content.

---

### 13. Third-Party AI Services

**13.1 Disclosure.** The Platform may use third-party AI service providers — including large language model APIs, image generation APIs, and audio processing APIs — to deliver certain AI Features. The use of third-party AI services is disclosed at the service level.

**13.2 Third-Party Terms.** Use of AI Features powered by third-party providers may be subject to those providers' terms of service and acceptable use policies in addition to this Policy. Where a third-party provider imposes additional restrictions on content types or use cases, those restrictions apply within the relevant AI Feature.

**13.3 Data Processing Roles and Safeguards.** Third-party AI service providers that process User inputs on behalf of the Company act as data processors or sub-processors, as applicable under applicable law. The Company will seek to maintain data processing agreements or equivalent contractual safeguards with such providers that: (a) restrict the provider's use of User data to the purpose of delivering the contracted service; (b) prohibit the provider from using User data for the provider's own model training without separate User consent; (c) address cross-border data transfer requirements under applicable law, including standard contractual clauses where required for transfers to or from the European Economic Area; and (d) require the provider to implement appropriate technical and organizational security measures. Where commercially available third-party AI providers are used solely for transient inference processing and not for provider-side model training, the Company does not treat such transient processing as incorporation into Platform Structured Datasets. Users who wish to avoid third-party AI processing may disable the relevant AI Features where such an option is made available.

---

### 14. AIWA-Specific Disclosures

**14.1 AIWA Mission.** AI West Africa (AIWA) is a Gambian-based publishing and aggregation initiative within the SPARXSTAR ecosystem, partly owned by Starisian Technologies, LLC. AIWA uses AI systems for: content aggregation across African languages; automatic and assisted translation; indigenous and regional language processing and documentation; lexicographic database construction; oral history transcription and indexing; and cultural heritage content structuring.

**14.2 Mandatory Processing Disclosure.** Content submitted through AIWA-integrated services is subject to mandatory Word Extraction, linguistic analysis, language tagging, and semantic indexing as described in Section 7.2. These processing activities are core to AIWA's language documentation mission and are disclosed to Users at point of service enrollment.

**14.3 Language Resource Building.** AIWA's language databases, Curated Lexicons, and Semantic Mappings are built from content processed through AIWA services, subject to applicable consent and TK protection requirements. These databases are designed to support African language preservation, translation, and accessibility.

**14.4 Cultural Sensitivity Protocols.** AIWA operates with heightened sensitivity to cultural heritage, traditional knowledge, and the rights of African communities. All TK Content protections set forth in this Policy, the Content Policy, and the Consent Policy apply to AIWA services. AIWA will not commercially exploit culturally restricted content and will observe community authorization requirements as a condition of operation.

**14.5 Translation Rights.** AI-generated translations produced by AIWA systems are Platform Content with respect to the translation layer, without affecting User ownership of original-language source content. Translation outputs from AIWA may be used within AIWA's language databases and services subject to applicable terms.

---

### 15. Governing Law and Jurisdiction

This Policy is governed by the laws of the State of California, United States, without regard to its conflict-of-law provisions.

| Jurisdiction | Overlay Document | Key Modification |
|---|---|---|
| European Union (GDPR / AI Act) | Pending — overlay document not yet created | Placeholder — drafting required |
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

---

### 18. Disclaimer of Warranties for AI Features

**18.1 No Accuracy Guarantee.** AI-Assisted Outputs are generated by probabilistic systems and may be inaccurate, incomplete, outdated, biased, or otherwise unsuitable for reliance in professional, legal, medical, financial, academic, or safety-critical contexts. The Platform makes no warranty, express or implied, regarding the accuracy, completeness, reliability, fitness for a particular purpose, or correctness of any AI-Assisted Output.

**18.2 No Professional Advice.** AI-Assisted Outputs do not constitute legal advice, medical advice, financial advice, professional consulting, or any other form of regulated professional advice. Users should not rely on AI-Assisted Outputs as a substitute for qualified professional judgment.

**18.3 Translation Limitations.** AI-generated translations are provided as a convenience and may not be accurate, particularly for low-resource languages, culturally specific terminology, idiomatic expressions, or sacred or ceremonially significant language. Users should not rely on AI-generated translations for legal, medical, ceremonial, or safety-critical purposes without human expert review.

**18.4 Cultural Representation.** AI Systems may reflect biases present in their training data. AI-generated representations of cultural knowledge, indigenous language, or traditional practices may be inaccurate or culturally insensitive. The Platform encourages community experts and Authorized Community Representatives to flag inaccuracies in AI-generated cultural content.

---

### 19. Indemnification

Users agree to indemnify, defend, and hold harmless the Company, its officers, directors, employees, agents, licensors, Client Operators, and successors from and against any and all claims, damages, losses, liabilities, costs, and expenses (including reasonable attorneys' fees) arising from or relating to the User's fraudulent, unlawful, grossly negligent, or intentionally wrongful: (a) use of AI Features in violation of this Policy; (b) generation of AI-Assisted Outputs in response to User prompts that violate applicable law or third-party rights; (c) misrepresentation of AI-Assisted Outputs as human-created works; or (d) conduct that causes demonstrable harm to a third party through the use of AI Features.

> *Note to legal counsel: The scienter threshold has been updated from "knowing or intentional" to "fraudulent, unlawful, grossly negligent, or intentionally wrongful" to preserve enforceability against serious misuse (including negligent IP infringement and reckless misuse) without requiring proof of subjective intent. Review whether this is consistent with the indemnification scope in the Master Terms of Service.*

---

### 20. Limitation of Liability

**20.1 Mutual Cap on Damages.** To the maximum extent permitted by applicable law, the total aggregate liability of either party to the other arising out of or related to this Policy or the use of AI Features — whether based on contract, tort, statute, or any other legal theory — shall not exceed the greater of: (a) the total fees paid by the User to the Company in the twelve (12) months immediately preceding the event giving rise to the claim; or (b) five hundred United States dollars (USD $500).

**20.2 Exclusion of Consequential Damages.** To the maximum extent permitted by applicable law, neither party shall be liable to the other for any indirect, incidental, special, consequential, exemplary, or punitive damages, including but not limited to: loss of profits, loss of revenue, loss of data, loss of goodwill, business interruption, or cost of substitute services, even if that party has been advised of the possibility of such damages.

**20.3 Essential Basis.** The parties acknowledge that the limitations of liability in this Section reflect a reasonable allocation of risk and are an essential basis of the bargain between the parties. The Company would not provide AI Features on the terms set forth in this Policy without these limitations.

**20.4 Exceptions.** The limitations in Sections 20.1 and 20.2 do not apply to: (a) liability arising from a party's gross negligence or willful misconduct; (b) a party's indemnification obligations under Section 19; (c) violations of Section 4.2 (Illegal Content Generation); (d) liability arising from a party's material breach of confidentiality obligations; (e) liability arising from a party's material breach of applicable data protection or privacy obligations; (f) liability arising from a party's infringement of the other party's intellectual property rights; or (g) liability that cannot be limited under applicable law.

