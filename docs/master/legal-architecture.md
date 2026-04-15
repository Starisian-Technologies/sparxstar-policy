# Legal Architecture

> Defines the layered legal architecture model for the SPARXSTAR policy repository.

---

## Metadata

| Field | Value |
|---|---|
| Version | 0.1.0 |
| Date | 2026-04-12 |
| Status | scaffolding |
| Maintainer | Starisian Technologies Legal |

---

## Architecture Overview

The SPARXSTAR legal policy system is organized as a four-layer hierarchical architecture. Lower layers inherit from and are constrained by higher layers.

```
┌─────────────────────────────────────────────────────────────┐
│  LAYER 1: Master Terms of Service                           │
│  Umbrella legal constitution governing all properties       │
├─────────────────────────────────────────────────────────────┤
│  LAYER 2: Policy Modules                                    │
│  Incorporated by reference into Master Terms                │
├─────────────────────────────────────────────────────────────┤
│  LAYER 3: Regional Jurisdiction Overlays                    │
│  Modify specific provisions for named jurisdictions         │
├─────────────────────────────────────────────────────────────┤
│  LAYER 4: Cultural Protocol Overlays                        │
│  Govern TK / sacred content; override commerce defaults     │
└─────────────────────────────────────────────────────────────┘
```

---

## Layer 1: Master Terms of Service

**Purpose**: Umbrella legal constitution. All subsidiary policies incorporate into and are governed by Master Terms.

**Scope**: All platform properties, services, users, content, and transactions.

**Key provisions**:
- Platform identity definition
- Governing law (California) and venue (Los Angeles County)
- Incorporation of all subsidiary policy modules by reference
- User account rules
- Content ownership framework
- Indemnification
- Limitation of liability
- Arbitration and dispute resolution
- Modification and termination procedures

**File**: `policies/master-terms/master-terms-of-service.md`

**Dependency**: None — all other policies depend on this.

---

## Layer 2: Policy Modules

Policy modules are standalone legal documents incorporated by reference into the Master Terms. Each module governs a specific platform function or subject matter area.

### Module Catalog

| Module | File | Function |
|---|---|---|
| Privacy Policy | `policies/privacy/privacy-policy.md` | User data collection, use, disclosure |
| Cookie Policy | `policies/cookies/cookie-policy.md` | Tracking technologies and consent |
| Community Policy | `policies/community/community-policy.md` | User conduct and behavioral standards |
| Content Policy | `policies/content/content-policy.md` | Content eligibility, prohibited categories, AI training, takedown |
| AI Chat Policy | `policies/ai-policy/ai-chat-policy.md` | AI feature use and processing rights |
| Copyright Policy | `policies/ip/copyright-policy.md` | Copyright ownership and DMCA |
| Trademark Policy | `policies/ip/trademark-policy.md` | Trademark use rules |
| IP + DMCA / DRM Compliance Policy | `policies/ip/ip-dmca-drm-policy.md` | IP enforcement and DRM |
| Consent Policy | `policies/consent/consent-policy.md` | Layered consent architecture |
| Terms of Sale | `policies/commerce/terms-of-sale.md` | Commerce transactions |
| Shipping and Return Policy | `policies/commerce/shipping-return-policy.md` | Physical goods logistics |
| Event Ticket Policy | `policies/events/event-ticket-policy.md` | Event ticketing |
| Music Distribution Terms | `policies/music/music-distribution-terms.md` | Music distribution and royalties |
| Streaming and Ebook Terms of Use | `policies/licensing/streaming-ebook-terms.md` | Digital content access |
| Artifact Policy | `policies/artifact/artifact-policy.md` | Cultural artifact intake |
| Tracking and Third-Party Licensing Policy | `policies/licensing/tracking-third-party-policy.md` | Third-party tracking |

### Module Dependency Rules

1. All modules incorporate the Master Terms by reference.
2. Modules may cross-reference other modules where subject matter overlaps.
3. In case of conflict between modules, the Master Terms prevail.
4. In case of conflict between modules at the same level, the more specific module governs.

---

## Layer 3: Regional Jurisdiction Overlays

Overlays modify specific provisions of Layer 1 or Layer 2 documents for named jurisdictions. Overlays do not replace the underlying document; they annotate or supplement it.

### Active Overlays

| Jurisdiction | Status | Scope |
|---|---|---|
| California (baseline) | Active | All policies |
| United States Federal | Active | DMCA, COPPA, CAN-SPAM |

### Planned Overlays

| Jurisdiction | Status | Scope |
|---|---|---|
| Gambia | Planned | Data, content, commerce |
| EU / GDPR | Placeholder | Privacy, cookies |
| United Kingdom | Placeholder | Privacy |
| ECOWAS | Placeholder | Commerce, data |
| Africa Regional | Placeholder | Cultural heritage, data |

### Overlay Conflict Resolution

```
IF California provision conflicts with named overlay:
  → Named overlay governs for that provision in that jurisdiction
  → California governs all other provisions

IF mandatory local consumer law is more protective:
  → Mandatory local law applies to that provision only
```

See [`JURISDICTION_MATRIX.md`](../../JURISDICTION_MATRIX.md) for full conflict resolution logic.

---

## Layer 4: Cultural Protocol Overlays

Cultural protocol overlays govern content subject to Traditional Knowledge (TK) restrictions, sacred use limitations, and community withdrawal rights. These overlays operate independently of and may override commercial licensing defaults.

### TK Label Framework (Placeholder)

| Label | Color | Access Level |
|---|---|---|
| TK Label — Open | Green | Public access permitted |
| TK Label — Restricted | Yellow | Community-restricted access |
| TK Label — Sacred | Red | Elder authorization required; commercial use prohibited |

### Cultural Governance Provisions (Placeholder)

| Provision | Status |
|---|---|
| Sacred withdrawal rights | Planned |
| Seasonal content restrictions | Planned |
| Elder override authority | Planned |
| Cultural erasure prevention duty | Planned |
| Repatriation rights | Planned |

See [`governance/`](../../governance/) for governance framework scaffolding.

---

## Policy Inheritance Diagram

```
Master Terms of Service
│
├─── [incorporates] Privacy Policy
│      └─── [overlays] CCPA (California)
│      └─── [placeholder] GDPR (EU)
│      └─── [placeholder] Gambia Data Protection
│
├─── [incorporates] Cookie Policy
│      └─── [overlays] CCPA opt-out requirements
│
├─── [incorporates] Community Policy
│      └─── [overlays] Cultural Protocol (TK content)
│
├─── [incorporates] AI Chat Policy
│      └─── [overlays] Cultural Protocol (TK exclusion from AI training)
│
├─── [incorporates] Copyright Policy
│      └─── [overlays] DMCA (US Federal)
│
├─── [incorporates] Artifact Policy
│      └─── [overlays] Cultural Protocol (TK labels; withdrawal rights)
│      └─── [overlays] Gambia operational rules
│
├─── [incorporates] Consent Policy
│      └─── [overlays] Cultural Protocol (consent escalation)
│      └─── [overlays] CCPA consent requirements
│
└─── [incorporates] All other modules
```

---

## Version Control Architecture

Every policy document must include the following front-matter metadata block:

```markdown
---
version: [semver e.g. 1.0.0]
date: [ISO 8601 date]
status: [planned | drafting | review | approved | active | archived]
jurisdiction: [primary jurisdiction]
supersedes: [prior version or "none"]
---
```

YAML front matter is mandatory and supersedes any human-readable metadata table format.

Symbols are not permitted in canonical policy titles. Use full words (e.g., `and` instead of `&` or `+`). Symbols may appear in UI display text, marketing copy, or navigation labels, but never in canonical document titles, manifest entries, or cross-reference tables.

Version history is maintained per document and logged in [`docs/version-history/`](../version-history/).

---

## Platform Identity (Legal Definition)

The platform is defined for legal purposes as:

> **"A modular language-centered governed digital infrastructure platform."**

The platform is simultaneously:
- A language processing system
- A creator economy platform
- A rights governance system
- A cultural preservation infrastructure
- A commerce marketplace
- An AI processing environment

This definition must be present in the Master Terms and referenced in all subsidiary policies where platform scope is relevant.

---

*This architecture document is the authoritative reference for all policy drafting decisions. For the individual policy document structure (Policy Bundle format, four-layer authoring model, and drafting workflow), see [`docs/policy-authoring/POLICY_AUTHORING_SPEC.md`](../policy-authoring/POLICY_AUTHORING_SPEC.md).*
