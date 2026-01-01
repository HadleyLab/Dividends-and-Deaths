# Chapter Build Protocol — Governed Execution

## Purpose
Draft or revise a chapter so that prose is **governed, death-bound, and system-consistent**.

This protocol ensures every chapter operates as a functional unit in the larger machine: geometry → engines → failure → mortality → custody.

## Scope
Applies to **every chapter bundle**, including the Prologue and Epilogue.

No chapter is exempt.

## Inputs
- `book/spine.md` (chapter question, claim, exit contract)
- `book/emotional_arc.md` (grief limits and tonal guardrails)
- `concepts/README_concepts.md` (canonical ontology)
- `concepts/concept_vocabulary.md` (mandated phrases)
- `concepts/concept_digital_maya.md`
- `concepts/concept_maat.md`
- `protocols/protocol_asset_compliance.md`
- `protocols/protocol_narrative_asset.md`
- `chapters/NN_chapter_name/chapter_NN_ledger.md`
- `chapters/global_ledger.md`

## Outputs
- Updated `chapters/NN_chapter_name/chapter_NN_prose.md`
- Updated `chapters/NN_chapter_name/chapter_NN_ledger.md` (authoritative)
- Updated `chapters/NN_chapter_name/chapter_NN_scene.md`
- Updated `chapters/global_ledger.md`
- Figure callouts and captions (if used)

## Procedure

### Step 1 — Bundle Integrity
- Confirm naming conventions:
  - Prologue is Chapter `00`.
  - Chapter bundles use two-digit prefixes (`01_the_billable_code`).
  - Each bundle contains `chapter_NN_prose.md`, `chapter_NN_ledger.md`, and `chapter_NN_scene.md`.

### Step 2 — Spine Contract Lock
- Explicitly state the **Chapter Question**, **Claim**, and **Exit Handoff** from `book/spine.md`.
- If any of these are unclear, **stop**. Do not draft prose.

### Step 3 — Ledger First (Non-Negotiable)
- Update `chapter_NN_ledger.md` before writing prose.
- Every scene, episode, concept, figure, and death reference must be logged.
- Each death reference must be tagged with:
  - Failed engine(s): Discovery / Care / Information
  - Failure mode (exclusion, misaction, lock-in)

Prose may not introduce unledgered material.

### Step 4 — Global Ledger Sync (Non-Negotiable)
- Register every asset from the chapter ledger in `chapters/global_ledger.md`.
- Resolve duplicates via **DEPRECATED** redirects.
- Confirm all `chapter_NN_scene.md` asset IDs exist in the global ledger.

### Step 5 — Asset Compliance Check
- Run `protocols/protocol_asset_compliance.md` against the ledger.
- Resolve violations before drafting.

### Step 6 — Draft Prose from the Ledger
Draft `chapter_NN_prose.md` using the ledger as the outline.

Required structure:
- **Opening hook**: mirror or Core Thesis Asset within the first scene.
- **System explanation**: governance or structural explanation must appear within 600 words of any vignette.
- **Progression**: Translation → Extraction → Custody.

If a figure appears, insert a callout and caption tied to a ledgered asset.

### Step 7 — Scene Mapping
- Update `chapter_NN_scene.md` so every scene maps to one or more ledger assets.
- Remove or relocate orphan scenes.
- Scene order must match the order of headings in `chapter_NN_prose.md`.
- Ledger entries must follow the scene order.

### Step 8 — Death-Bound Enforcement

For every death, near-death, or lethal disparity referenced:
- Identify the **engine failure** explicitly in prose or in an adjacent sentence.
- If grief is invoked, the paragraph **must close** with a structural cause.
- Death may never appear as accident, mystery, or inevitability without mechanism.

### Step 9 — Tone and Emotion Control
- Match the emotional temperature defined in `book/emotional_arc.md`.
- Maintain observational, inevitable tone.
- No unresolved grief beats.

### Step 10 — Concept and Language Hygiene
- Use only canonical concepts defined in `concepts/`.
- Reuse mandated phrases from `concepts/concept_vocabulary.md`.
- Introduce new terms only via approved concepts.
- Mention **Digital Māyā** only when representation is governing action without custody.
- Mention **Ma’at** only when enforceable correction or governance is at stake.

### Step 11 — Exit Alignment
- Ensure the final section fulfills the **Exit Handoff** to the next chapter or part.
- The chapter must leave the reader with increased structural clarity, not just affect.

### Step 12 — Status Update
- Update `chapters/README_chapters.md` with chapter status and pass completion.

---

## Checks (Pass / Fail)

- [ ] Spine contract honored (question, claim, exit)
- [ ] Ledger complete and authoritative
- [ ] Global ledger updated and deduped
- [ ] Every death traceable to engine failure
- [ ] No ungoverned concepts or assets
- [ ] Emotional arc respected
- [ ] Scene-to-asset mapping complete
- [ ] Language reuse enforced

Failure on any check means the chapter is **not publication-ready**.

---

## AI Review Checklist (Second-Pass)

Use AI to:
- verify that every asset ID in `chapter_NN_prose.md` exists in `chapter_NN_ledger.md` and `chapters/global_ledger.md`
- flag any prose claims that lack engine failure linkage
- detect concept drift against `concepts/` definitions
- identify repeated explanations that should be collapsed into canonical phrases

AI does not decide meaning or claims; it enforces consistency.

---

## Notes
This protocol exists to prevent eloquence from outrunning accountability.

## Non-Negotiables

- Ledger precedes prose.
- Death is always an audit, never an anecdote.
- Governance language may not be softened for comfort.
- If the chapter cannot explain *why* harm occurred, it is incomplete.
