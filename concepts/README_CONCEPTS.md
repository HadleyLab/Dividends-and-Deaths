# Concepts — Canonical Ontology Manual

## Purpose
Lock the book’s meaning layer so it can scale without drift.

## Scope
Applies to all chapters, protocols, figures, captions, and editorial passes.

If a term does conceptual work in prose, it must be defined here.
Nothing in this directory is illustrative.

## Related Documents
- Root context and directory map: `README.md`
- Governance invariants: `book/README_BOOK.md`
- Execution protocols: `protocols/README_PROTOCOLS.md`
- Governed prose bundles: `chapters/README_CHAPTERS.md`

---

## Non-Negotiables

- Concepts override prose when conflicts arise.
- Concepts may not be redefined casually or implicitly.
- Closed sets remain closed unless governance changes.
- Any concept that touches harm must remain death-bound.

If a passage violates a concept definition, the passage is wrong.

## Update Triggers

- a concept category changes
- the required concept file structure changes
- a concept is added to or removed from the canonical index

---

## Role in the System (Read This When Confused)

Layered system:
- `book/` — governance: what must remain true
- `concepts/` — ontology: what is allowed to exist and what it means
- `protocols/` — execution: how work is done
- `chapters/` — output: governed prose

Concepts sit **below governance** and **above execution**.

---

## Concept Categories (Closed Sets)

Every concept belongs to **one and only one** category:
- Vocabulary
- System Primitives
- Lenses
- Governance Constructs
- Policy Context

If a concept cannot be cleanly classified, it is not ready for canon.

---

## Canonical Concept Structure (Required)

Every concept file must include:
- `## Purpose`
- `## Scope`
- `## Canonical Definition`
- `## Usage / Placement Rules`
- `## Relationship to Canonical Concepts`
- `## Reusable Phrase (Canonical)`
- `## Death-Bound Clarification`

Concepts are definitions, not essays.

---

## Death-Bound Requirement (Non-Negotiable)

Any concept that touches harm, exclusion, disparity, error, automation, or scale
**must** explicitly explain how misuse, absence, or failure contributes to patient harm or death.

---

## Naming and Files

- Filenames use `snake_case`.
- Concept names are stable and reusable.
- Redefinition inside prose is forbidden.

---

## Canonical Index (Authoritative)

Authoritative definitions:
- `concept_vocabulary.md`
- `concept_geometry_of_medicine.md`
- `concept_three_engines.md`
- `concept_digital_maya.md`
- `concept_maat.md`
- `concept_healthcare_data_laws.md`

Closed sets remain closed unless book governance is explicitly revised.

---

## Author–Concept Contract

- The author supplies synthesis and invention.
- The canon supplies constraint and memory.
- Neither replaces the other.

Episodes without concepts become anecdote.
Concepts without episodes become abstraction.
