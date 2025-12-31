# Narrative Asset Protocol

## Purpose
Add or update a narrative asset so it is canonical, compliant, and reusable.

## Scope
Applies to any new character, place, object, concept, ritual, or phrase introduced in a chapter.

## Inputs
- `protocols/asset_compliance.md`
- `chapters/NN_chapter_name/ledger.md`
- The draft or scene that introduces the asset

## Outputs
- Updated ledger entry with the next canonical ID
- `scene.md` updated to include the new asset

## Procedure
1. Open the chapter ledger in `chapters/NN_chapter_name/ledger.md`.
2. Confirm the asset belongs in this chapter (serves the Chapter Question, Claim, or Exit Handoff).
3. Assign the next ID using the chapter prefix (e.g., `00-CHAR-07`, `01-PLACE-03`).
4. Fill the template below with canonical details and reuse hooks.
5. If the asset is a Character, include **Status** and **Cultural/National Identity**.
6. Maintain human-readable ledger formatting:
   - Chapter Contract is a bullet list with bold labels.
   - Assets use a `### NN. ID — Name` heading and bolded field labels.
7. Maintain human-readable scene formatting in `scene.md`:
   - Document title: `# Scene Map — NN Chapter Name`.
   - Use `###` headings per scene with a single **Assets:** line.
8. Add or update the `scene.md` entry that uses this asset.
9. Re-run the compliance checks for naming and interior-state rules.

## Checks
- Asset is logged before it appears in prose.
- Character entries include Status and Cultural/National Identity.
- `scene.md` points to the correct asset ID.

## Notes
Append new assets rather than reordering existing IDs.

## Citation Handling
Citations are optional. Use them when a chapter includes a references section or when you want traceable sourcing beyond the Evidence asset.
- Evidence assets may include an optional **Citations** field listing source labels (Author, Year) or a short list of URLs/DOIs.
- Separate Citation assets are only required when a chapter maintains a formal references section.
- When using a `.bib`, use only inline citation keys (e.g., `[@key]`) in the prose and omit any “Selected References” block from the chapter text.
- Do not duplicate citations by mixing inline keys with textual citations like “Author, Year.”
- When a list or block draws from one source, include a single inline key after the list instead of repeating it on each bullet.

## Figure Handling
When a chapter introduces a figure:
- Log it as a **Figure** asset in the ledger.
- Include a figure callout in the prose (e.g., “(See Figure 2.1.)”).
- Add a standalone title line and a caption line in `chapter.md` using `Figure X | Caption...`.
- List the file name in **Aliases** if a source image or diagram exists.
- Standardize file naming: `figure_NN_XX_short_slug.png` (e.g., `figure_02_01_dividend_stack.png`) and place the file in the chapter folder.

## References Handling
Journal names and author initials in reference sections are treated as part of the Evidence asset. Do not log them as separate assets unless they are discussed in the prose as entities.

## Quick Checklist
- ID assigned
- Template filled
- `scene.md` updated
- Compliance rechecked

## Template
# Narrative Asset Ledger — Chapter XX

## Asset: [Canonical Name]

- **Asset Type:** (see protocols/asset_compliance.md)
- **Status:** (Living / Deceased / Public Figure / Abstract) (if Character)
- **Cultural/National Identity:** (ancestry, geography, faith environment; if Character include national identity)
- **Aliases:** (optional variants, possessives, plurals, abbreviations)
- **Introduced In:** (scene or section)
- **Narrative Function:** (what work this asset does *in this chapter*)
- **Reuse Hook:** (where and how it will reappear later)

## Notes
(Optional: constraints, reminders, compliance flags)

# Narrative Asset Protocol — Canonical Reconciliation

## Purpose
Admit, register, and govern **narrative assets** so that lived episodes, cases, people, places, and objects become reusable **system components** rather than isolated anecdotes.

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
- Draft prose or scene introducing the asset

## Outputs
- Updated `ledger.md` with canonical asset entry
- Updated `scene.md` with asset references
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
Register the asset in `ledger.md` using the canonical template.

Required fields:
- **Asset Type**
- **Status** (for Characters)
- **Cultural / National Identity** (for Characters, when relevant)
- **Introduced In**
- **Narrative Function** (what structural work this asset does)
- **Engine Link** — which engine failure(s) this asset illuminates
- **Reuse Hook** — where and why it may reappear

Interior emotional states are not logged unless analytically required.

### Step 4 — Death-Bound Declaration
If the asset involves harm, disparity, or death:
- Explicitly declare which **engine failure(s)** are implicated.
- State whether the failure is **exclusion**, **misaction**, or **lock-in**.

Assets that touch death without mechanism are non-compliant.

### Step 5 — Scene Map Update
- Update `scene.md` so each scene lists the asset IDs it uses.
- Scenes may not reference unregistered assets.

### Step 6 — Compliance Check
Run `protocols/asset_compliance.md` and resolve all violations before prose is finalized.

---

## Checks (Pass / Fail)

- [ ] Asset serves chapter contract
- [ ] Canonical ID assigned
- [ ] Ledger entry complete
- [ ] Engine failure declared (if applicable)
- [ ] Scene map updated
- [ ] Compliance rechecked

Failure on any check means the asset is **not canonical**.

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