# Chapters — Governed Prose Bundles

## Purpose
Define how **prose is produced, audited, and scaled** in *Dividends & Deaths*.

Chapters are not standalone documents. Each chapter is a **governed bundle** designed to make narrative, evidence, and accountability inseparable.

This directory is where the system produces readable output.

## Scope
Applies to all chapters, including the Prologue (`00`) and Epilogue.

No prose is considered canonical unless it lives inside a compliant chapter bundle.

---

## Chapter Bundle Structure (Non-Negotiable)

Each chapter lives in its own directory:

```text
NN_chapter_name/
├── chapter.md   # reader-facing prose
├── ledger.md    # authoritative asset + failure map
└── scene.md     # scene-to-asset alignment
```

- **`chapter.md`** is narrative output.
- **`ledger.md`** is the source of truth.
- **`scene.md`** ensures narrative structure maps to system structure.

If these three files disagree, **the ledger wins**.

---

## Chapter Status Tags

Add exactly one status line at the top of `chapter.md`:

- `Status: OUTLINE` — spine-aligned structure only
- `Status: DRAFT` — prose exists but governance incomplete
- `Status: STRUCTURE PASS` — ledger, engines, and exits enforced
- `Status: POLISH` — language and cadence tightening only

Status reflects **governance maturity**, not writing effort.

---

## Global Narrative Asset Index (Required)

This repository enforces a **single global index** of narrative assets to prevent duplicate IDs, duplicated episodes, and drift across chapters.

**Location:**

```
chapters/global_ledger.md
```

### Index Rules

- **One asset, one canonical ID.** Do not create a new asset if one already exists.
- If a duplicate is created by mistake, it must be marked **DEPRECATED** and redirected to the canonical ID.
- Variants (`a/b/c`) are permitted only when the same root episode must appear with materially different boundaries or engine mappings.
- Every asset must have exactly **one Home Chapter** (first canonical appearance).

### Bootstrap Procedure (Required Once)

Use this to normalize existing chapters into the global ledger:

1. For each existing `chapters/NN_*` bundle, list all assets in `ledger.md`.
2. For each asset, create a row in `chapters/global_ledger.md` with:
   - Asset ID
   - Canonical Name
   - Type
   - Home Chapter
   - Engine Link
   - Status
   - Redirect / Notes (if needed)
3. If two assets describe the same episode or entity:
   - Choose a single canonical ID
   - Mark the duplicate **DEPRECATED** in the global ledger
   - Update chapter ledgers to reference the canonical ID
4. Verify every asset referenced in every `scene.md` exists in the global ledger.

After bootstrap:
- `chapters/global_ledger.md` is mandatory and authoritative.
- No new asset appears in prose unless it is registered globally first.

---

## Canonical Chapter Workflow (How to Use This Folder)

1. **Read the Spine**  
   Open `book/spine.md` and identify:
   - Chapter Question
   - Chapter Claim
   - Exit Handoff

2. **Build the Ledger First**  
   Create or update `ledger.md` with:
   - all narrative assets (episodes, people, places, figures)
   - all concepts referenced
   - every death, disparity, or harm
   - the implicated engine failure(s)

   If it is not in the ledger, it may not appear in prose.

3. **Register Narrative Assets**  
   Run `protocols/narrative_asset.md` for any episode, case, person, or place.

4. **Update the Global Ledger**  
   Register or update all assets in `chapters/global_ledger.md`.

5. **Check Compliance Early**  
   Run `protocols/asset_compliance.md` before drafting prose.

6. **Draft Prose from the Ledger**  
   Write `chapter.md` using the ledger as the outline, not memory or intuition.

7. **Map Scenes**  
   Update `scene.md` so each scene lists the asset IDs it uses.

8. **Enforce Death-Bound Logic**  
   Ensure every referenced death or disparity is explicitly traceable to:
   - a canonical engine failure (Discovery, Care, Information)
   - a failure mode (exclusion, misaction, lock-in)

9. **Update Chapter Status**  
   Advance the status tag only when the governance conditions are met.

---

## What Belongs in a Chapter (and What Does Not)

Chapters **may include**:
- lived episodes and cases (ledgered)
- system explanation and analysis
- figures tied to ledgered assets

Chapters **may not include**:
- unledgered anecdotes
- new concepts that bypass concept intake
- death framed as accident, mystery, or fate
- unresolved grief without structural cause

---

## Conflict Resolution (Authoritative Order)

When discrepancies appear:

1. `chapters/global_ledger.md` (global IDs and asset truth)
2. `chapters/NN_chapter_name/ledger.md` (chapter asset authority)
3. `chapters/NN_chapter_name/scene.md` (scene mapping)
4. `chapters/NN_chapter_name/chapter.md` (prose)

Fix inputs upstream; never patch prose to bypass the ledger.

---

## Related Documents

- Root context and directory map: `README.md`
- Governance invariants: `book/README.md`
- Canonical ontology: `concepts/README.md`
- Execution protocols: `protocols/README.md`

---

## Non-Negotiables

- Ledger precedes prose.
- Governance overrides style.
- Concepts override narrative when conflicts arise.
- Death is always treated as a systems outcome.

If a chapter feels "right" but violates these rules, the chapter is wrong.

---

## Update Triggers

Update this README when:
- the chapter bundle structure changes
- global ledger rules change
- status tags change
- chapter workflow steps change
