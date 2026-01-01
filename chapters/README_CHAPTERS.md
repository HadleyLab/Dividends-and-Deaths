# Chapters — Governed Prose Bundles

## Purpose
Define how prose is produced, audited, and scaled in *Dividends & Deaths*.

## Scope
Applies to all chapters, including the Prologue (`00`) and Epilogue.

No prose is canonical unless it lives inside a compliant chapter bundle.

## Related Documents
- Root context and directory map: `README.md`
- Governance invariants: `book/README_BOOK.md`
- Canonical ontology: `concepts/README_CONCEPTS.md`
- Execution protocols: `protocols/README_PROTOCOLS.md`

---

## Chapter Bundle Structure (Non-Negotiable)

Each chapter lives in its own directory:

```text
NN_chapter_name/
├── chapter_NN_prose.md   # reader-facing prose
├── chapter_NN_ledger.md  # authoritative asset + failure map
├── chapter_NN_scene.md   # scene-to-asset alignment
└── references.bib        # optional chapter-scoped references
```

Only the directory carries the chapter stem; filenames use the chapter number only.

- **`chapter_NN_prose.md`** is narrative output.
- **`chapter_NN_ledger.md`** is the source of truth.
- **`chapter_NN_scene.md`** maps narrative to system structure.
- **`references.bib`** is optional and chapter-scoped.

Global asset index: `chapters/GLOBAL_LEDGER.md`
Global references (optional): `chapters/GLOBAL_REFERENCES.bib`

If these files disagree, **the ledger wins**.

**Ordering rule:** `chapter_NN_prose.md` headings define scene order. `chapter_NN_scene.md` follows that order. `chapter_NN_ledger.md` follows scene order.

---

## Chapter Status Tags

Add exactly one status line at the top of `chapter_NN_prose.md`:

- `Status: OUTLINE` — spine-aligned structure only
- `Status: DRAFT` — prose exists but governance incomplete
- `Status: STRUCTURE PASS` — ledger, engines, and exits enforced
- `Status: POLISH` — language and cadence tightening only

Status reflects **governance maturity**, not writing effort.

---

## Global Narrative Asset Index (Required)

Single global index to prevent duplicate IDs and drift:

```
chapters/GLOBAL_LEDGER.md
```

Index rules:
- **One asset, one canonical ID.**
- Duplicates must be marked **DEPRECATED** and redirected.
- Variants (`a/b/c`) are allowed only when the same episode must appear with materially different boundaries or engine mappings.
- Every asset has exactly **one Home Chapter** (first canonical appearance).

### Bootstrap Procedure (Required Once)

1. List all assets in each `chapter_NN_ledger.md`.
2. Create rows in `chapters/GLOBAL_LEDGER.md` with:
   - Asset ID
   - Canonical Name
   - Type
   - Home Chapter
   - Engine Link
   - Status
   - Redirect / Notes (if needed)
3. Resolve duplicates by deprecating and redirecting.
4. Verify every asset referenced in every `chapter_NN_scene.md` exists in the global ledger.

After bootstrap:
- `chapters/GLOBAL_LEDGER.md` is mandatory and authoritative.
- No new asset appears in prose unless registered globally first.

### Production Reindex (When Prose Order Changes)

1. Ensure `chapter_NN_scene.md` matches `chapter_NN_prose.md` heading order.
2. Reassign asset IDs in `chapter_NN_ledger.md` by **type**, in prose order.
3. Update references in `chapter_NN_prose.md`, `chapter_NN_scene.md`, and `chapters/GLOBAL_LEDGER.md`.
4. Rebuild the global ledger from chapter ledgers in the new order.

IDs are defined by prose order, not convenience.
If an asset’s **Type** changes, reindex the chapter and update all references.

---

## Canonical Chapter Workflow

1. Read `book/spine.md` for the Chapter Question, Chapter Claim, and Exit Handoff.
2. Build `chapter_NN_ledger.md` with all narrative assets, concepts, deaths, and engine failures.
3. Register assets via `protocols/protocol_asset_registration.md`.
4. Update `chapters/GLOBAL_LEDGER.md`.
5. Check constraints with `protocols/protocol_canon_compliance.md`.
6. Draft `chapter_NN_prose.md` from the ledger.
7. Update `chapter_NN_scene.md` so each scene lists the asset IDs it uses.
8. Ensure every death or disparity is traceable to a canonical engine failure and failure mode.
9. Advance the status tag only when governance conditions are met.

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

1. `chapters/GLOBAL_LEDGER.md`
2. `chapters/NN_chapter_name/chapter_NN_ledger.md`
3. `chapters/NN_chapter_name/chapter_NN_scene.md`
4. `chapters/NN_chapter_name/chapter_NN_prose.md`

Fix inputs upstream; never patch prose to bypass the ledger.

---

## Non-Negotiables

- Ledger precedes prose.
- Governance overrides style.
- Concepts override narrative when conflicts arise.
- Death is always treated as a systems outcome.

If a chapter feels "right" but violates these rules, the chapter is wrong.

## Update Triggers

- the chapter bundle structure changes
- global ledger rules change
- status tags change
- chapter workflow steps change
