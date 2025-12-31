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

4. **Check Compliance Early**  
   Run `protocols/asset_compliance.md` before drafting prose.

5. **Draft Prose from the Ledger**  
   Write `chapter.md` using the ledger as the outline, not memory or intuition.

6. **Map Scenes**  
   Update `scene.md` so each scene lists the asset IDs it uses.

7. **Enforce Death-Bound Logic**  
   Ensure every referenced death or disparity is explicitly traceable to:
   - a canonical engine failure (Discovery, Care, Information)
   - a failure mode (exclusion, misaction, lock-in)

8. **Update Chapter Status**  
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

## Why This Structure Exists

This mirrors modern safety-critical production systems:

- **Ledgers** provide auditability
- **Protocols** enforce consistency
- **Bundles** localize failure

The result is prose that can scale without losing meaning.

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
- status tags change
- chapter workflow steps change
