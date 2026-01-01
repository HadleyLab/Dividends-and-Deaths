
# Copilot Instructions for Dividends & Deaths

## System Overview
This repository is a governed publication workspace for writing a nonfiction book as a system, not a stream of drafts. All work is governed by invariants, ledgers, and protocols. AI assists with consistency, compression, and enforcement, but does not supply meaning or authority.

## Directory Structure & Authority
- `book/` — Governance: invariants, spine, emotional arc, publication plan. **Overrides all other directories.**
- `concepts/` — Canonical ontology: definitions, closed sets, and mandated phrases. **Overrides narrative when in conflict.**
- `protocols/` — Execution: how work is done, including asset registration, chapter build, and compliance. **Overrides convenience.**
- `chapters/` — Governed prose bundles: each chapter is a directory containing prose, ledger, scene map, and optional references. **Prose is not canonical unless compliant.**
- `drafts/` — Ungoverned exploration. Nothing here is canonical.

## Authoring Workflow (Follow in Order)
1. **Start with Governance:**
   - Read `AUTHORING_PLAN.md` for lifecycle, roles, and invariants.
   - Use `book/README_book.md` for governance rules and authority map.
   - Reference `concepts/README_concepts.md` for canonical terms and definitions.
   - Use `protocols/README_protocols.md` for execution steps and compliance checks.
   - Use `chapters/README_chapters.md` for chapter bundle rules and status tags.
2. **Ledger First:**
   - All episodes, cases, and assets must be ledgered in `chapter_NN_ledger.md` before appearing in prose.
   - Register assets globally in `chapters/global_ledger.md`.
3. **Scene Mapping:**
   - Every scene in `chapter_NN_scene.md` must map to asset IDs in the global ledger.
   - Scene order must match prose headings.
4. **Draft Prose:**
   - Write `chapter_NN_prose.md` using only ledgered assets and canonical concepts.
   - No unledgered material may appear in prose.
5. **Compliance & Audit:**
   - Run protocol checks before elevating draft status.
   - Tag each chapter with one status: `Status: OUTLINE`, `Status: DRAFT`, `Status: STRUCTURE PASS`, or `Status: POLISH`.
   - Use the checklist in `chapters/README_chapters.md` before advancing status.

## Conventions & Non-Negotiables
- **Ledger precedes prose.**
- **Governance overrides style.**
- **Concepts override narrative.**
- **Death is always a systems outcome, never a mystery.**
- **Grief is permitted only after structure is explicit.**
- **No mixing of governance, ledgers, and prose in the same file.**

## Chapter Bundle Structure
Each chapter directory must contain:
```
NN_chapter_name/
├── chapter_NN_prose.md   # reader-facing prose
├── chapter_NN_ledger.md  # authoritative asset + failure map
├── chapter_NN_scene.md   # scene-to-asset alignment
└── references.bib        # optional
```
Only the directory carries the chapter stem; filenames use the chapter number only.

## Asset & Concept Rules
- Every asset must have a canonical ID and be registered in the global ledger.
- Concepts must be defined in `concepts/` and may not be redefined in prose.
- If prose references material not present in the ledger or canon, it is wrong.

## AI Role & Handoff
- AI enforces structure, consistency, and compression.
- AI does not invent lived experience, supply authority, or decide claims.
- When requesting AI review, specify:
  - Files in scope
  - Goal (validation, transformation, audit)
  - Constraints (non-negotiables)
  - Required outputs (checklist or diff-ready edits)

## Update Triggers
Update these instructions when:
- governance, canon, or protocol rules change
- chapter bundle or asset rules change
- status tags or workflow steps change

## Quick Reference
- `AUTHORING_PLAN.md` — Authoring lifecycle and rules
- `book/README_book.md` — Governance invariants and authority map
- `concepts/README_concepts.md` — Canonical ontology and closed sets
- `protocols/README_protocols.md` — Execution rules and compliance
- `chapters/README_chapters.md` — Chapter bundle and status workflow

For details, always start with the root `README.md` and follow the production order. When in doubt, governance wins.
