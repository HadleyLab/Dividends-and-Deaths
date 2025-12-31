# Narrative Asset Protocol — Canonical Reconciliation

## Purpose
Admit, register, and govern **narrative assets** so that lived episodes, cases, people, places, objects, and figures become reusable **system components** rather than isolated anecdotes.

This protocol ensures that narrative material serves the book’s structural claims, remains interoperable with formal concepts, and never outruns accountability.

## Scope
Applies to any new or modified:
- person (author, patient, clinician, researcher)
- episode or case
- place or institution
- object, technology, or artifact
- concept instance referenced narratively
- figure or visual object

If an asset appears in prose, it must be registered here.

## Inputs
- `book/spine.md` (chapter question, claim, exit)
- `book/emotional_arc.md` (grief limits)
- `concepts/README.md` (canonical ontology)
- `protocols/asset_compliance.md`
- `chapters/NN_chapter_name/ledger.md`
- `chapters/global_ledger.md`
- Draft prose or scene introducing the asset

## Outputs
- Updated `chapters/NN_chapter_name/ledger.md` with canonical asset entry
- Updated `chapters/global_ledger.md` with canonical index row
- Updated `chapters/NN_chapter_name/scene.md` with asset references
- Updated reuse hooks for future chapters

---

## Asset Classification (Required)

Every narrative asset must be classified as **one** of the following:

- **Character** — a person appearing in narrative (including the author)
- **Episode** — a bounded event or case (clinical, institutional, personal)
- **Place** — a location or institution
- **Object** — a physical or digital artifact
- **Concept Instance** — a narrative instantiation of a canonical concept
- **Evidence** — data, paper, statistic, or study
- **Figure** — diagram, chart, or visual explanatory object

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
- Use the chapter prefix and asset type code (e.g., `00-CHAR-01`, `02-EPIS-03`).
- IDs are append-only. Never reuse or reorder.

### Step 3 — Ledger Registration (Non-Negotiable)
Register the asset in `chapters/NN_chapter_name/ledger.md` using the canonical template.

Required fields:
- **Asset Type**
- **Status** (for Characters)
- **Cultural / National Identity** (for Characters, when relevant)
- **Introduced In**
- **Narrative Function** (what structural work this asset does)
- **Engine Link** — which engine failure(s) this asset illuminates
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
- Explicitly declare which **engine failure(s)** are implicated.
- State whether the failure is **exclusion**, **misaction**, or **lock-in**.

Assets that touch death without mechanism are non-compliant.

### Step 6 — Scene Map Update
- Update `chapters/NN_chapter_name/scene.md` so each scene lists the asset IDs it uses.
- Scenes may not reference unregistered assets.

### Step 7 — Compliance Check
Run `protocols/asset_compliance.md` and resolve all violations before prose is finalized.

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
- Add a standalone title line and a caption line in `chapter.md` using `Figure X | Caption...`.
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
- **Engine Link:** (Discovery / Care / Information + failure mode)
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
