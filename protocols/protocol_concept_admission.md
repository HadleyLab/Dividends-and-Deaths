# Concept Admission Protocol — Canonical Admission

## Purpose
Admit, revise, or reject a concept so it becomes canonical ontology.

## Scope
Applies to any new or revised concept intended for use in chapters, figures, or analysis.

If a concept does not pass this protocol, it may not appear in prose.

## Inputs
- `concepts/README_CONCEPTS.md`
- `book/spine.md`
- `book/emotional_arc.md`
- `concepts/concept_vocabulary.md`
- related concept files in `concepts/`
- `protocols/protocol_asset_registration.md` (if the concept appears in a chapter)

## Outputs
- New or updated standalone file in `concepts/`
- Updated `concepts/README_CONCEPTS.md` index entry
- Updated `concepts/concept_vocabulary.md` with the concept name and canonical phrases

## Procedure

### Step 1 — Concept Classification (Required)
Every concept must be classified as **one** of:
- Vocabulary
- System Primitive
- Lens
- Governance Construct
- Policy Context

If a concept does not fit one category cleanly, it is not ready.

### Step 2 — Closed-Set Check
- Confirm the concept does **not** violate an existing closed set.
- If it proposes an addition to a closed set, stop. Governance revision is required.

### Step 3 — Create or Update the Concept File
Create or revise a standalone file in `concepts/` using the canonical structure:
- `# Title`
- `## Purpose`
- `## Scope`
- `## Canonical Definition`
- `## Usage / Placement Rules`
- `## Relationship to Canonical Concepts`
- `## Reusable Phrase (Canonical)`
- `## Death-Bound Clarification`

All sections are required.

### Step 4 — Death-Bound Test (Non-Negotiable)
The concept must explicitly answer:
> How does misuse, absence, or failure of this concept contribute to patient harm or death?

If this cannot be stated clearly, the concept fails intake.

### Step 5 — Engine and Geometry Mapping
Declare the concept’s relationship to:
- Discovery / Care / Information engines
- Geometry of Medicine
- Digital Māyā
- Ma’at

Concepts that float outside this system are not admissible.

### Step 6 — Index and Vocabulary Update
- Add the concept to `concepts/README_CONCEPTS.md` with a one-line description.
- Add the concept name and canonical phrases to `concepts/concept_vocabulary.md`.

### Step 7 — Narrative Asset Registration (If Applicable)
If the concept appears in a chapter:
- log it using `protocols/protocol_asset_registration.md`
- update the relevant `chapter_NN_scene.md` to reference the asset

---

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
- Concepts are definitions, not essays.
- Precision is mandatory; elegance is optional.

## Non-Negotiables
- Concepts override prose when conflicts arise.
- Closed sets remain closed unless governance is revised.
- Every concept that touches harm must remain death-bound.
- If a concept cannot be governed, it does not belong.

## Update Triggers
- Any change to concept categories or required structure
- Any update to closed sets or governance constraints
