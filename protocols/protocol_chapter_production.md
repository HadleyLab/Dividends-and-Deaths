# Chapter Production Protocol — Governed Execution

## Purpose
Draft or revise a chapter so prose is governed, death-bound, and system-consistent.

## Scope
Applies to **every chapter bundle**, including the Prologue and Epilogue.

## Inputs
- `book/spine.md`
- `book/emotional_arc.md`
- `concepts/README_CONCEPTS.md`
- `concepts/concept_vocabulary.md`
- `concepts/concept_digital_maya.md`
- `concepts/concept_maat_egyptian.md`
- `concepts/concept_digital_maat.md`
- `protocols/protocol_canon_compliance.md`
- `protocols/protocol_asset_registration.md`
- `chapters/NN_chapter_name/chapter_NN_ledger.md`
- `chapters/GLOBAL_LEDGER.md`

## Outputs
- Updated `chapters/NN_chapter_name/chapter_NN_prose.md`
- Updated `chapters/NN_chapter_name/chapter_NN_ledger.md`
- Updated `chapters/NN_chapter_name/chapter_NN_scene.md`
- Updated `chapters/GLOBAL_LEDGER.md`
- Figure callouts and captions (if used)

## Procedure

### Step 1 — Bundle Integrity
- Confirm naming conventions.
- Confirm the bundle contains `chapter_NN_prose.md`, `chapter_NN_ledger.md`, and `chapter_NN_scene.md`.

### Step 2 — Spine Contract Lock
- Explicitly state the Chapter Question, Chapter Claim, and Exit Handoff from `book/spine.md`.
- If any are unclear, stop. Do not draft prose.

### Step 3 — Ledger First (Non-Negotiable)
- Update `chapter_NN_ledger.md` before writing prose.
- Every scene, episode, concept, figure, and death reference must be logged.
- Each death reference must be tagged with:
  - failed engine(s): Discovery / Care / Information
  - failure mode: exclusion, misaction, or lock-in

Prose may not introduce unledgered material.

### Step 4 — Global Ledger Sync (Non-Negotiable)
- Register every asset from the chapter ledger in `chapters/GLOBAL_LEDGER.md`.
- Resolve duplicates via **DEPRECATED** redirects.
- Confirm all `chapter_NN_scene.md` asset IDs exist in the global ledger.

### Step 5 — Asset Compliance Check
- Run `protocols/protocol_canon_compliance.md` against the ledger.
- Resolve violations before drafting.

### Step 6 — Draft Prose from the Ledger
Draft `chapter_NN_prose.md` using the ledger as the outline.

Required structure:
- opening hook: mirror or Core Thesis Asset within the first scene
- system explanation: governance or structural explanation within 600 words of any vignette
- progression: Translation → Extraction → Custody

If a figure appears, insert a callout and caption tied to a ledgered asset.

### Step 7 — Scene Mapping
- Update `chapter_NN_scene.md` so every scene maps to one or more ledger assets.
- Remove or relocate orphan scenes.
- Scene order must match headings in `chapter_NN_prose.md`.
- Ledger entries must follow scene order.

### Step 8 — Death-Bound Enforcement
For every death, near-death, or lethal disparity:
- identify the engine failure explicitly in prose or an adjacent sentence
- if grief is invoked, close the paragraph with a structural cause
- never frame death as accident, mystery, or inevitability without mechanism

### Step 9 — Tone and Emotion Control
- Match the emotional temperature in `book/emotional_arc.md`.
- Maintain observational, inevitable tone.
- No unresolved grief beats.

### Step 10 — Concept and Language Hygiene
- Use only canonical concepts defined in `concepts/`.
- Reuse mandated phrases from `concepts/concept_vocabulary.md`.
- Introduce new terms only via approved concepts.
- Mention **Digital Māyā** only when representation governs action without custody.
- Mention **Ma’at** only when enforceable correction or governance is at stake.

### Step 11 — Exit Alignment
- Ensure the final section fulfills the Exit Handoff.
- Leave the reader with increased structural clarity, not just affect.

### Step 12 — Index Freshness Gate
- Ensure `chapter_NN_scene.md` matches `chapter_NN_prose.md` headings.
- Ensure `chapter_NN_ledger.md` follows scene order.
- Ensure all assets are registered in `chapters/GLOBAL_LEDGER.md`.
- If prose order changed, reindex and update all references before advancing status.

### Step 13 — Status Update
- Update the status line in `chapter_NN_prose.md` to reflect governance maturity.

---

## Checks (Pass / Fail)
- [ ] Spine contract honored
- [ ] Ledger complete and authoritative
- [ ] Global ledger updated and deduped
- [ ] Every death traceable to engine failure
- [ ] No ungoverned concepts or assets
- [ ] Emotional arc respected
- [ ] Scene-to-asset mapping complete
- [ ] Language reuse enforced
- [ ] Indices fresh (scene order, ledger order, global ledger sync)

Failure on any check means the chapter is **not publication-ready**.

## Notes
This protocol exists to prevent eloquence from outrunning accountability.

## Non-Negotiables
- Ledger precedes prose.
- Death is always an audit, never an anecdote.
- Governance language may not be softened for comfort.
- If the chapter cannot explain why harm occurred, it is incomplete.

## Update Triggers
- Any change to chapter bundle structure
- Any change to required ledger fields
- Any change to the emotional arc or spine contracts
