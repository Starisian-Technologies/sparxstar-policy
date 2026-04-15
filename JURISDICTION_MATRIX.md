# JURISDICTION MATRIX

> Tracks governing jurisdiction, operational compliance overlays, and conflict fallback logic for all platform policies.

---

## Metadata

| Field | Value |
|---|---|
| Version | 0.1.0 |
| Date | 2026-04-12 |
| Status | scaffolding |
| Maintainer | Starisian Technologies Legal |

---

## Jurisdiction Model Overview

The platform operates under a layered jurisdiction model:

```
PRIMARY GOVERNING LAW: California, United States
VENUE: Los Angeles County, California
OPERATIONAL OVERLAY: Gambia
FUTURE OVERLAYS: EU/GDPR, UK, ECOWAS, Africa Regional
```

California law governs all matters unless an operational overlay explicitly modifies a specific clause for a named jurisdiction.

---

## Jurisdiction Catalog

---

### California (Primary)

| Field | Value |
|---|---|
| Jurisdiction | California, United States |
| Role | Master governing law jurisdiction |
| Venue | Los Angeles County Superior Court |
| Arbitration | California arbitration rules; AAA or JAMS |
| Consumer Protection | California Consumer Privacy Act (CCPA); California Automatic Renewal Law |
| Privacy Framework | CCPA / CPRA |
| IP Framework | United States federal copyright and trademark law; California state IP provisions |
| Governing Policies | All policies — California is the default governing law |
| Status | `active` — all policies must conform to California standards |
| Conflict Rule | California law supersedes any conflicting provision unless a named overlay explicitly governs a specific matter |

#### California-Specific Requirements

| Requirement | Policy Impacted |
|---|---|
| CCPA consumer rights (access, deletion, opt-out of sale) | Privacy Policy; Cookie Policy |
| CCPA "Do Not Sell My Personal Information" | Privacy Policy; Tracking and Third-Party Licensing Policy |
| California automatic renewal disclosures | Terms of Sale; Music Distribution Terms |
| California DMCA designated agent registration | IP + DMCA / DRM Compliance Policy |
| California biometric data restrictions | Privacy Policy |
| Los Angeles County venue clause | Master Terms; Terms of Sale; Event Ticket Policy |

---

### United States Federal (Supporting)

| Field | Value |
|---|---|
| Jurisdiction | United States Federal |
| Role | Supporting federal law framework |
| Federal Laws Applicable | DMCA (17 U.S.C. § 512); CAN-SPAM; COPPA; FTC Act |
| Governing Policies | IP + DMCA / DRM Compliance Policy; Privacy Policy (COPPA provisions); Community Policy |
| Status | `active` — federal law applies where applicable |

#### US Federal Requirements

| Requirement | Policy Impacted |
|---|---|
| DMCA safe harbor (17 U.S.C. § 512) | IP + DMCA / DRM Compliance Policy |
| COPPA (children under 13 data restrictions) | Privacy Policy |
| CAN-SPAM (email marketing) | Privacy Policy |
| FTC endorsement and disclosure rules | Community Policy; AI Chat Policy |

---

### Gambia (Operational Overlay)

| Field | Value |
|---|---|
| Jurisdiction | Republic of The Gambia |
| Role | Operational compliance overlay |
| Governing Law | California governs; Gambia overlay modifies specific operational requirements |
| Applicable Laws | Gambia Information and Communication Act; Gambia Data Protection Act (placeholder); Gambia Companies Act |
| Governing Policies | Privacy Policy (data handling); Community Policy; Terms of Sale; Commerce overlay |
| Status | `planned` — overlay drafting required |
| Conflict Rule | Where Gambia law imposes a higher compliance standard, the Gambia standard applies for operations within Gambia; California governs all other matters |

#### Gambia-Specific Requirements (Placeholder)

| Requirement | Policy Impacted | Notes |
|---|---|---|
| Gambia Data Protection Act compliance | Privacy Policy | Requires legal research confirmation |
| Local content requirements | Community Policy | Placeholder — research required |
| Payment method localization | Terms of Sale | Africa-specific payment methods |
| Operator licensing | Master Terms | Research required for applicable licenses |

> **Note**: Gambia operational overlay requires in-country legal counsel review before publication.

---

### International (Global Use)

| Field | Value |
|---|---|
| Jurisdiction | International |
| Role | Global conflict fallback logic |
| Governing Law | California governs; international users subject to California law unless a specific named overlay applies |
| Status | `planned` |

#### International Conflict Fallback Logic

```
IF user jurisdiction has a named overlay in this matrix:
  → Apply named overlay for specified provisions
  → California governs all other provisions

IF user jurisdiction has no named overlay:
  → California law governs all provisions
  → International user accepts California venue

IF mandatory consumer law in user jurisdiction conflicts with California terms:
  → Mandatory consumer law of user jurisdiction applies to that specific provision only
  → All other provisions governed by California
```

#### General International Requirements

| Requirement | Policy Impacted |
|---|---|
| Language accessibility | All user-facing policies |
| Local currency disclosure | Terms of Sale; Event Ticket Policy |
| International payment methods | Terms of Sale |
| Cross-border data transfer disclosures | Privacy Policy |

---

### European Union / GDPR (Future Placeholder)

| Field | Value |
|---|---|
| Jurisdiction | European Union |
| Role | Future overlay — not yet active |
| Status | `planned` |
| Priority | After California and Gambia overlays complete |

#### EU/GDPR Placeholder Requirements

| Requirement | Policy Impacted | Notes |
|---|---|---|
| GDPR lawful basis for processing | Privacy Policy | Placeholder |
| Data subject rights (access, deletion, portability, objection) | Privacy Policy | Placeholder |
| Data Protection Officer (DPO) appointment | Privacy Policy | Research required |
| Cookie consent (ePrivacy Directive) | Cookie Policy | Placeholder |
| Standard contractual clauses (SCCs) for data transfers | Privacy Policy | Placeholder |
| GDPR Article 13/14 transparency notices | Privacy Policy | Placeholder |

> **Note**: EU/GDPR overlay requires specialist GDPR counsel before drafting.

---

### United Kingdom (Future Placeholder)

| Field | Value |
|---|---|
| Jurisdiction | United Kingdom |
| Role | Future overlay — not yet active |
| Status | `planned` |
| Priority | Low — after EU overlay |

#### UK-Specific Placeholder Requirements

| Requirement | Policy Impacted | Notes |
|---|---|---|
| UK GDPR (post-Brexit) compliance | Privacy Policy | Placeholder |
| ICO registration | Privacy Policy | Research required |
| UK Online Safety Act (if applicable) | Community Policy | Monitor legislative status |

---

### ECOWAS / West Africa Regional (Future Placeholder)

| Field | Value |
|---|---|
| Jurisdiction | ECOWAS Member States |
| Role | Future regional overlay — not yet active |
| Status | `planned` |
| Priority | Low — after Gambia overlay |

#### ECOWAS Placeholder Requirements

| Requirement | Policy Impacted | Notes |
|---|---|---|
| ECOWAS data protection framework | Privacy Policy | Placeholder |
| Regional e-commerce regulations | Terms of Sale | Research required |
| Regional content regulations | Community Policy | Research required |
| Cross-border payment frameworks | Terms of Sale | Research required |

---

### Africa Regional (Broader Future Placeholder)

| Field | Value |
|---|---|
| Jurisdiction | African Union member states (general) |
| Role | Broader regional placeholder |
| Status | `planned` |
| Priority | Long-term |

#### Africa Regional Placeholder Requirements

| Requirement | Policy Impacted | Notes |
|---|---|---|
| African Union Convention on Cyber Security and Personal Data Protection (Malabo Convention) | Privacy Policy | Placeholder |
| National data protection laws per country | Privacy Policy | Country-by-country research required |
| Cultural heritage protection frameworks | Artifact Policy; Governance Protocols | WIPO-aligned |

---

## Jurisdiction Conflict Resolution Table

| Scenario | Rule |
|---|---|
| No jurisdiction overlay exists | California law governs |
| Named overlay exists for specific provision | Overlay governs that provision; California governs all others |
| Mandatory local consumer law is more protective | Mandatory local law applies to that provision only |
| International user disputes venue | California venue controls unless mandatory local law overrides |
| Cultural/TK content dispute | Cultural governance protocol governs; jurisdiction overlay secondary |
| DMCA takedown in non-US jurisdiction | US DMCA procedure followed; local notice procedures may supplement |

---

## Overlay Drafting Status

| Jurisdiction | Overlay Status | Legal Counsel Required |
|---|---|---|
| California | Active baseline — all policies | Internal |
| United States Federal | Active baseline — specific policies | Internal |
| Gambia | Planned | In-country counsel required |
| EU / GDPR | Placeholder | GDPR specialist required |
| United Kingdom | Placeholder | UK counsel required |
| ECOWAS | Placeholder | Regional counsel required |
| Africa Regional | Placeholder | Long-term |

---

*Each jurisdiction overlay must be reviewed by qualified legal counsel in the applicable jurisdiction before publication.*
