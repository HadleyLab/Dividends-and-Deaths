# Asset Registration Protocol — Canonical Reconciliation

## Purpose
Admit and govern narrative assets so lived episodes, cases, people, places, objects, and figures become reusable system components.

## Scope
Applies to any new or modified:
- person (author, patient, clinician, researcher)
- episode or case
- place or institution
- object, technology, or artifact
- organization or policy
- ritual, symbol, or phrase used as a named asset
- concept instance referenced narratively
- figure or visual object

If an asset appears in prose, it must be registered here.

## Inputs
- `book/spine.md`
- `book/emotional_arc.md`
- `concepts/README_CONCEPTS.md`
- `protocols/protocol_canon_compliance.md`
- `chapters/NN_chapter_name/chapter_NN_ledger.md`
- `chapters/GLOBAL_LEDGER.md`
- draft prose or scene introducing the asset

## Outputs
- Updated `chapters/NN_chapter_name/chapter_NN_ledger.md`
- Updated `chapters/GLOBAL_LEDGER.md`
- Updated `chapters/NN_chapter_name/chapter_NN_scene.md`
- Updated reuse hooks for future chapters

## Procedure

### Step 1 — Asset Classification (Required)
Every asset must be classified as **one** of:
- Character
- Place
- Object
- Figure
- Ritual
- Economic
- Phrase
- Concept
- Symbol
- Organization
- Policy
- Evidence
- Citation
- Historical case
- Metaphor
- Foreshadowing

If an asset does not fit cleanly, it is not ready for prose.

### Step 2 — Chapter Contract Check
Confirm the asset serves **at least one** of:
- Chapter Question
- Chapter Claim
- Exit Handoff

If it does not, do not admit the asset.

### Step 3 — Assign Canonical ID
- Use the chapter prefix and asset code: `NN-CODE-XX`.
- Codes are fixed. Do not invent new codes.
- IDs are order-dependent and assigned in the order assets appear in `chapter_NN_prose.md` (scene order).
- Do not reuse retired IDs.
- Reindex only when prose order changes or an asset’s **Type** changes; update all references.

Preferred codes:
CHAR, PLACE, OBJ, FIG, RIT, ECON, PHRASE, CONCEPT, SYMBOL, ORG, POLICY, EVID, HIST, METAPHOR, FORESHADOW

Legacy codes (already in use; keep only if the asset already exists):
THESIS, CASE, DATA, TOOL, CULT, LEDGER, EXIT, OBJECT

### Step 4 — Ledger Registration (Non-Negotiable)
Register the asset in `chapters/NN_chapter_name/chapter_NN_ledger.md` using the canonical template.

Required fields:
- **Canonical Name**
- **Asset Type**
- **Status** (for Characters)
- **Cultural / National Identity** (for Characters, when relevant)
- **Cultural / Historical Context**
- **Introduced In**
- **Narrative Function**
- **Engine Link** — single engine failure this asset illuminates
- **Reuse Hook**

Interior emotional states are not logged unless analytically required.

### Step 5 — Global Ledger Registration (Non-Negotiable)
Add or update the asset row in `chapters/GLOBAL_LEDGER.md`.

Required columns:
- Asset ID
- Canonical Name
- Type
- Home Chapter
- Engine Link
- Status
- Redirect / Notes

If a duplicate exists, mark the duplicate **DEPRECATED** and redirect to the canonical ID.

### Step 6 — Death-Bound Declaration
If the asset involves harm, disparity, or death:
- declare the **engine failure**
- state whether the failure is **exclusion**, **misaction**, or **lock-in**

Assets that touch death without mechanism are non-compliant.

### Step 7 — Scene Map Update
- Update `chapters/NN_chapter_name/chapter_NN_scene.md` so each scene lists the asset IDs it uses.
- Scenes may not reference unregistered assets.
- Scene order must match the order of headings in `chapters/NN_chapter_name/chapter_NN_prose.md`.

### Step 8 — Ledger Ordering
- Ledger entries must follow the scene order derived from `chapter_NN_prose.md`.
- If prose order changes, reorder `chapter_NN_ledger.md` and `chapter_NN_scene.md` to match.

### Step 9 — Compliance Check
Run `protocols/protocol_canon_compliance.md` and resolve all violations before prose is finalized.

---

## Checks (Pass / Fail)
- [ ] Asset classified
- [ ] Chapter contract satisfied
- [ ] Canonical ID assigned
- [ ] Chapter ledger entry complete
- [ ] Global ledger row recorded or updated
- [ ] Engine failure declared (if applicable)
- [ ] Scene map updated
- [ ] Compliance rechecked

Failure on any check means the asset is **not canonical**.

## Notes
- Assets are **structural**, not decorative.
- Episodes demonstrate system behavior, not sympathy.
- Characters are treated as agents or witnesses, not interior monologues.

## Non-Negotiables
- Assets override prose when conflicts arise.
- No asset may introduce ungoverned concepts.
- Death may appear only when its structural cause is legible.
- If an asset cannot be reused or traced, it does not belong.

## Update Triggers
- Any change to asset types, ID rules, or ledger templates
- Any change to global ledger structure
