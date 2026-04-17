---
version: 1.0.0
date: 2026-04-12
status: active
---

# Policy Authoring Specification v1.0

**Canonical document for policy authoring across all SPARXSTAR / AIWA / Starisian Technologies policy instruments.**

---

## Purpose

This specification defines how every policy in this repository must be structured. It ensures that human-readable text intended for lawyers, artists, and users coexists with machine-readable metadata in a single, version-controlled document.

A policy is not a single-layer text file. A policy is a **Policy Bundle** — a linked set of layers that serve different audiences simultaneously.

---

## The Policy Bundle Model

Every policy instrument in this repository is a **Policy Bundle**. A Policy Bundle is the smallest complete, enforceable policy unit. It is authored as a single Markdown file with a defined four-layer structure.

```
┌─────────────────────────────────────────────────────────┐
│  Policy Bundle                                          │
│                                                         │
│  Layer 1 — Human Readable (plain language summary)      │
│      ↓ accurately summarized by                         │
│  Layer 2 — Legal Full Text (enforceable prose)          │
│      ↓ normalized into                                  │
│  Layer 3 — Machine Metadata (YAML front-matter)         │
│      ↓ optionally attested by                           │
│  Layer 4 — Blockchain Attestation (hash + timestamp)    │
└─────────────────────────────────────────────────────────┘
```

Layers 1, 2, and 3 are **required** for every policy. Layer 4 is optional and used when immutable public attestation is required.

---

## Layer Definitions

### Layer 1 — Human Readable Layer

**Audience:** Artists, contributors, customers, and any person who did not study law.

**Purpose:** A plain-language explanation of what the policy means in practice. This is the version that users see, that is audited for accessibility, and that is handed to a lawyer as the starting point for refinement.

**Requirements:**
- Written at a Grade 8 reading level or lower.
- Uses short sentences. No passive voice where avoidable.
- States what the company does, what the user can do, and what is not allowed — in that order.
- Uses "you" and "we" throughout.
- Must accurately represent Layer 2 without contradiction.
- This layer is the **primary deliverable** for lawyer review and legal editing.

**Format in the document:**

```markdown
## Plain Language Summary

> What this policy means for you.

**What we do:** [one sentence]

**What you can do:** [one sentence]

**What is not allowed:** [one sentence]

[2–4 paragraphs of plain-language explanation]
```

---

### Layer 2 — Legal Full Text Layer

**Audience:** Lawyers, compliance officers, regulators, courts.

**Purpose:** The formal, legally enforceable version of the policy. This is the binding document. Layer 1 must accurately summarize Layer 2; Layer 2 governs in all disputes.

**Requirements:**
- Precise and unambiguous legal language.
- Organized by clause with numbered or lettered sections.
- Includes jurisdiction, governing law, and effective date.
- Identifies who the policy applies to ("Covered Parties").
- Includes definitions of key terms used in the policy.
- Includes enforcement mechanisms and remedies.
- References jurisdiction overlays where applicable.

**Format in the document:**

```markdown
## Full Legal Text

> This section is the legally binding policy text. In the event of any conflict between this section and the Plain Language Summary above, this section governs.

### 1. Definitions

...

### 2. Scope and Applicability

...

### 3. [Policy-Specific Clauses]

...

### N. Governing Law and Jurisdiction

...
```

---

### Layer 3 — Machine Metadata Layer

**Audience:** Internal tooling, automated validators, policy management systems, CI/CD pipelines.

**Purpose:** Structured, machine-readable metadata that enables automated validation, version tracking, and cross-policy dependency management.

**Requirements:**
- YAML front-matter block at the top of every policy file.
- All fields defined in `schemas/policy-manifest.schema.json` must be present.
- `status` must reflect the current lifecycle stage of the document.
- `version` must be updated whenever Layer 1 or Layer 2 changes.

**Format:**

```yaml
---
version: 0.1.0
date: 2026-04-12
status: drafting
jurisdiction: California
supersedes: none
policyType: module
dependsOnMasterTerms: true
sourceModels:
  - Meta Community Standards
  - Reddit Content Policy
---
```

---

### Layer 4 — Blockchain Attestation Layer (Optional)

**Audience:** Auditors, external parties requiring proof of policy state at a given time.

**Purpose:** An immutable, timestamped record of the policy content hash at a specific version. Provides cryptographic proof that a policy existed in a specific state on a specific date.

**When required:**
- When a policy is promoted to `active` status and will be publicly enforced.
- When a legal dispute may require proof of the policy state at a specific time.
- When required by a jurisdiction overlay (e.g., GDPR accountability documentation).

**Format in the document (appended at promotion to active):**

```markdown
## Attestation Record

| Field | Value |
|---|---|
| Version | 1.0.0 |
| SHA-256 Hash | [hash of Layer 2 full text at this version] |
| Attested Date | 2026-XX-XX |
| Attestation Method | [on-chain / timestamp authority / internal audit log] |
| Attested By | [authorized signatory role] |
```

---

## Policy Lifecycle Stages

Every policy moves through the following stages, reflected in the `status` field:

| Stage | Description | Who Acts |
|---|---|---|
| `planned` | Policy identified, scope defined, no text yet | Governance lead |
| `drafting` | Layer 1 and Layer 2 being written | Policy author (@copilot initial draft) |
| `review` | Draft under lawyer review and editing | External legal counsel |
| `approved` | Lawyer-approved, awaiting deployment | Legal + governance sign-off |
| `active` | Publicly enforced; blockchain attestation added if required | Authorized signatory |
| `archived` | Superseded or retired; no longer enforced | Governance lead |

---

## Authoring Workflow

The following workflow governs how a policy moves from `planned` to `active`:

```
1. Governance lead identifies policy need → adds entry to POLICY_MANIFEST.md
2. @copilot authors initial Layer 1 (plain language draft) + Layer 2 structure
3. Layer 1 draft exported and sent to lawyer for editing
4. Lawyer returns edited text → Layer 2 finalized
5. Layer 1 updated to accurately reflect Layer 2
6. Internal review: POLICY_MANIFEST.md status updated to `approved`
7. Policy published → status updated to `active`
8. Layer 4 attestation record added (if required)
```

---

## Naming Rules

These rules apply to all canonical policy titles used in YAML front-matter, `POLICY_MANIFEST.md`, `CLAUSE_MATRIX.md`, `JURISDICTION_MATRIX.md`, and document H1 headings.

1. **No symbols in policy titles.** Use full words: `and` not `&`, `or` not `/`, `and` not `+`.
2. **Hyphenate compound modifiers.** `Third-Party` not `Third Party`.
3. **Title Case** for all policy names.
4. **No abbreviations** in the canonical title. `Digital Millennium Copyright Act` not `DMCA` in the title.

---

## File Structure Requirements

Each policy file must follow this structure, in order:

```
[YAML front-matter — Layer 3]

# [Policy Title]

## Plain Language Summary     ← Layer 1

## Full Legal Text            ← Layer 2

## Attestation Record         ← Layer 4 (when status = active)
```

See `docs/policy-authoring/POLICY_BUNDLE_TEMPLATE.md` for the canonical template.

---

## Relationship to the Schema

`schemas/policy-bundle.schema.json` validates the Layer 3 machine metadata (YAML front-matter fields). The schema does not validate Layer 1 or Layer 2 content — those layers are reviewed by humans and lawyers.

The prior `schemas/policy-manifest.schema.json` validated a flat manifest representation of policy entries. That file remains valid for the root `POLICY_MANIFEST.md` document but does not govern the structure of individual policy files. Individual policy files are governed by this specification.

---

*This specification is maintained by the Starisian Technologies governance team. Changes require governance lead approval and must be reflected in `POLICY_MANIFEST.md`.*
