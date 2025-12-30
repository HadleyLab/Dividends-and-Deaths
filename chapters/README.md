# Chapters

## Purpose
Keep prose and ledgers bundled so every chapter is auditable and scalable.

## Scope
Applies to all chapter bundles in `chapters/`.

## Structure
- `NN_chapter_name/` — production chapter bundles with `chapter.md`, `ledger.md`, and `scene.md`
- Drafts live in `drafts/`

## Status Tags
Add one of the following lines to the top of each `chapter.md`:
- `Status: OUTLINE`
- `Status: DRAFT`
- `Status: STRUCTURE PASS`
- `Status: POLISH`

## Workflow
1. Review `protocols/chapter_build.md`.
2. Create or update the matching `ledger.md` inside the chapter bundle.
3. Create or update `scene.md` to map scenes to assets.
4. Verify compliance + emotional arc + vocabulary invariants.
5. Draft or revise `chapter.md`.
6. Note any dependencies (tables, figures, data pulls) at the end of `chapter.md` for production tracking.

## Notes
This mirrors modern publishing pipelines: ledgers prove reuse, protocols enforce structure, and each bundle stays auditable without extra cross-referencing.
