# Concept Intake Protocol — Canonical Admission

## Purpose
Admit, revise, or reject a concept so that it becomes **canonical ontology** within *Dividends & Deaths*.

This protocol exists to prevent conceptual drift, enforce closed sets, and ensure that every concept introduced into prose is **death-bound, reusable, and governed**.

## Scope
Applies to any **new or revised concept** intended for use in chapters, figures, or analysis.

If a concept does not pass this protocol, it **may not appear in prose**.

## Inputs
- `concepts/README_concepts.md` (canonical ontology rules)
- `book/spine.md` (throughline and contracts)
- `book/emotional_arc.md` (death and grief constraints)
- `concepts/concept_vocabulary.md`
- Related concept files in `concepts/`
- `protocols/protocol_narrative_asset.md` (if the concept appears in a chapter)

## Outputs
- A new or updated standalone file in `concepts/`
- Updated `concepts/README_concepts.md` index entry
- Updated `concepts/concept_vocabulary.md` with:
  - the concept name
  - any canonical phrases or reuse language

## Concept Classification (Required)
Every concept must be classified as **one** of the following:

- **Vocabulary** — a core term or phrase with a fixed meaning
- **System Primitive** — a structural element (e.g., engines, geometry)
- **Lens** — a framing device with placement rules (e.g., Digital Māyā)
- **Governance Construct** — an enforceable constraint (e.g., Ma’at, custody)
- **Policy Context** — legal or regulatory framing tied to chapters

If a concept does not fit one category cleanly, it is not yet ready.

## Procedure

### Step 1 — Closed-Set Check
- Confirm the concept does **not** violate an existing closed set (e.g., engines, primitives).
- If it proposes an addition to a closed set, **stop**. Governance revision is required.

### Step 2 — Create or Update the Concept File
Create or revise a standalone file in `concepts/` using the canonical structure:

- `# Title`
- `## Purpose`
- `## Scope`
- `## Canonical Definition`
- `## Usage / Placement Rules`
- `## Relationship to Canonical Concepts`
- `## Reusable Phrase (Canonical)`
- `## Death-Bound Clarification`

All sections are required unless explicitly noted otherwise.

### Step 3 — Death-Bound Test (Non-Negotiable)
The concept **must** explicitly answer:

> How does misuse, absence, or failure of this concept contribute to patient harm or death?

If this cannot be stated clearly, the concept fails intake.

### Step 4 — Engine and Geometry Mapping
The concept must declare its relationship to:
- **Discovery / Care / Information** engines
- **Geometry of Medicine** (embedding, separation, distance)
- **Digital Māyā** (representation without custody)
- **Ma’at** (enforceable alignment)

Concepts that float outside this system are not admissible.

### Step 5 — Index and Vocabulary Update
- Add the concept to `concepts/README_concepts.md` with a one-line description.
- Add the concept name and any canonical phrases to `concepts/concept_vocabulary.md`.

### Step 6 — Narrative Asset Registration (If Applicable)
If the concept appears in a chapter:
- Log it using `protocols/protocol_narrative_asset.md`.
- Update the relevant `chapter_NN_scene.md` to reference the asset.

## Checks (Pass / Fail)

- [ ] Concept classification declared
- [ ] Closed-set integrity preserved
- [ ] Canonical file structure complete
- [ ] Death-bound clarification explicit
- [ ] Engine and geometry relationships declared
- [ ] README index updated
- [ ] Vocabulary updated
- [ ] Narrative asset logged (if used)

Failure on any check means the concept is **not canonical**.

## Notes
- Concepts are **definitions**, not essays.
- Do not smuggle arguments, metaphors, or emotion into concept files.
- Precision is mandatory; elegance is optional.

## Non-Negotiables

- Concepts override prose when conflicts arise.
- Closed sets remain closed unless governance is revised.
- Every concept that touches harm must remain death-bound.
- If a concept cannot be governed, it does not belong in this book.
