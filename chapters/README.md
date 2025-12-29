# Chapters Workspace

Use this folder strictly for prose. Governance, ledgers, and vocabulary live elsewhere so they can be audited independently.

## Subdirectories
- `.` – current working chapters (00-03). Treat these as production-ready candidates subject to compliance checks.
- `first_drafts/` – exploratory material. Before elevating anything from here, run it through the Chapter Blueprint workflow.

## Chapter Status Tags
Add one of the following lines to the top of each file to communicate progress:
- `Status: OUTLINE`
- `Status: DRAFT`
- `Status: STRUCTURE PASS`
- `Status: POLISH`

## Required Workflow
1. Review `docs/governance/chapter_blueprint.md`.
2. Create or update the matching ledger under `assets/ledgers/`.
3. Verify compliance + emotional arc + vocabulary invariants.
4. Draft or revise the chapter.
5. Note any dependencies (tables, figures, data pulls) at the end of the file for production tracking.

This mirrors modern publishing pipelines: ledgers prove reuse, blueprint enforces structure, and this directory carries only the prose that survives those gates.
