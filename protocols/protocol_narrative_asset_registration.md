# Narrative Asset Registration Protocol — Canonical Reconciliation

## Purpose
Admit, register, and govern **narrative assets** so that lived episodes, cases, people, places, objects, and figures become reusable **system components** rather than isolated anecdotes.

This protocol ensures that narrative material serves the book’s structural claims, remains interoperable with formal concepts, and never outruns accountability.

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
- `book/spine.md` (chapter question, claim, exit)
- `book/emotional_arc.md` (grief limits)
- `concepts/README_concepts.md` (canonical ontology)
- `protocols/protocol_canon_compliance.md`
- `chapters/NN_chapter_name/chapter_NN_ledger.md`
- `chapters/global_ledger.md`
- Draft prose or scene introducing the asset

## Outputs
- Updated `chapters/NN_chapter_name/chapter_NN_ledger.md` with canonical asset entry
- Updated `chapters/global_ledger.md` with canonical index row
- Updated `chapters/NN_chapter_name/chapter_NN_scene.md` with asset references
- Updated reuse hooks for future chapters

---

## Asset Classification (Required)

Every narrative asset must be classified as **one** of the following:

- **Character** — a person appearing in narrative (including the author)
- **Place** — a location or institution
- **Object** — a physical or digital artifact
- **Figure** — diagram, chart, or visual explanatory object
- **Ritual** — a repeated practice or rite used as a narrative unit
- **Economic** — a defined economic mechanism or unit
- **Phrase** — a named line or structural refrain
- **Concept** — a canonical concept used narratively
- **Symbol** — a named symbol or emblematic object
- **Organization** — an institution or formal entity
- **Policy** — a law, program, or formal policy instrument
- **Evidence** — data, paper, statistic, or study
- **Citation** — a formal reference unit when cited as an object
- **Historical case** — a bounded historical event or case
- **Metaphor** — a named metaphor used as a structural unit
- **Foreshadowing** — a named foreshadowing device

If an asset does not fit cleanly, it is not ready for prose.

---

## Procedure

### Step 1 — Chapter Contract Check
Confirm the asset directly serves **at least one** of:
- the Chapter Question
- the Chapter Claim
- the Exit Handoff

If it does not, do not admit the asset.

### Step 2 — Assign Canonical ID
- Use the chapter prefix and asset code: `NN-CODE-XX`.
- Codes are fixed. Do not invent new codes.
- IDs are append-only. Never reuse or reorder.
- IDs are assigned in the order assets are introduced in `chapter_NN_prose.md` (scene order).
- If an asset’s **Type** changes, reindex IDs for the chapter and update all references.

**Preferred codes (use for new assets):**
CHAR, PLACE, OBJ, FIG, RIT, ECON, PHRASE, CONCEPT, SYMBOL, ORG, POLICY, EVID, HIST, METAPHOR, FORESHADOW

**Legacy codes (already in use; keep only if the asset already exists):**
THESIS, CASE, DATA, TOOL, CULT, LEDGER, EXIT, OBJECT

### Step 3 — Ledger Registration (Non-Negotiable)
Register the asset in `chapters/NN_chapter_name/chapter_NN_ledger.md` using the canonical template.

Required fields:
- **Canonical Name** (use the entry heading)
- **Asset Type**
- **Status** (for Characters)
- **Cultural / National Identity** (for Characters, when relevant)
- **Cultural / Historical Context**
- **Introduced In**
- **Narrative Function** (what structural work this asset does)
- **Engine Link** — which single engine failure this asset illuminates
- **Reuse Hook** — where and why it may reappear

Interior emotional states are not logged unless analytically required.

### Step 4 — Global Ledger Registration (Non-Negotiable)
Add or update the asset row in `chapters/global_ledger.md`.

Required columns:
- Asset ID
- Canonical Name
- Type
- Home Chapter
- Engine Link
- Status
- Redirect / Notes

If a duplicate exists, mark the duplicate **DEPRECATED** and redirect to the canonical ID.

### Step 5 — Death-Bound Declaration
If the asset involves harm, disparity, or death:
- Explicitly declare which **engine failure** is implicated.
- State whether the failure is **exclusion**, **misaction**, or **lock-in**.

Assets that touch death without mechanism are non-compliant.

### Step 6 — Scene Map Update
- Update `chapters/NN_chapter_name/chapter_NN_scene.md` so each scene lists the asset IDs it uses.
- Scenes may not reference unregistered assets.
- Scene order must match the order of headings in `chapters/NN_chapter_name/chapter_NN_prose.md`.

### Step 7 — Ledger Ordering
- Ledger entries must follow the scene order derived from `chapter_NN_prose.md`.
- If prose order changes, reorder `chapter_NN_ledger.md` and `chapter_NN_scene.md` to match.

### Step 8 — Compliance Check
Run `protocols/protocol_canon_compliance.md` and resolve all violations before prose is finalized.

---

## Checks (Pass / Fail)

- [ ] Asset serves chapter contract
- [ ] Canonical ID assigned
- [ ] Chapter ledger entry complete
- [ ] Global ledger row recorded or updated
- [ ] Engine failure declared (if applicable)
- [ ] Scene map updated
- [ ] Compliance rechecked

Failure on any check means the asset is **not canonical**.

---

## Figure Handling

When a chapter introduces a figure:
- Log it as a **Figure** asset in the ledger.
- Include a figure callout in the prose (e.g., “(See Figure 2.1.)”).
- Add a standalone title line and a caption line in `chapter_NN_prose.md` using `Figure X | Caption...`.
- List the file name in **Aliases** if a source image or diagram exists.
- Standardize file naming: `figure_NN_XX_short_slug.png` (e.g., `figure_02_01_dividend_stack.png`) and place the file in the chapter folder.

---

## References Handling

Journal names and author initials in reference sections are treated as part of the Evidence asset. Do not log them as separate assets unless they are discussed in the prose as entities.

---

## Templates

### Chapter Ledger Entry (Canonical Fields)

- **Asset Type:** (see canonical asset types)
- **Status:** (Living / Deceased / Public Figure / Abstract) (if Character)
- **Cultural/National Identity:** (if Character)
- **Aliases:** (optional variants, possessives, plurals, abbreviations)
- **Introduced In:** (scene or section)
- **Narrative Function:** (what work this asset does in this chapter)
- **Engine Link:** (single engine: Discovery / Care / Information + failure mode)
- **Reuse Hook:** (where and how it will reappear later)

### Global Ledger Row

| Asset ID | Canonical Name | Type | Home Chapter | Engine Link | Status | Redirect / Notes |
|---|---|---|---|---|---|---|

---

## Notes
- Assets are **structural**, not decorative.
- Episodes exist to demonstrate system behavior, not to elicit sympathy.
- Characters are treated as agents or witnesses, not interior monologues.

---

## Non-Negotiables

- Assets override prose when conflicts arise.
- No asset may introduce ungoverned concepts.
- Death may appear only when its structural cause is legible.
- If an asset cannot be reused or traced, it does not belong.
