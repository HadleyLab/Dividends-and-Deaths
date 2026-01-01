# Documentation System Protocol

## Purpose
Define the documentation system so every directory is qualified and authoritative references stay synchronized.

## Scope
Applies to all canonical directories and documentation files.

## Inputs
- `README.md`
- `AUTHORING_PLAN.md`
- `book/README_BOOK.md`
- `concepts/README_CONCEPTS.md`
- `protocols/README_PROTOCOLS.md`
- `chapters/README_CHAPTERS.md`
- `drafts/README_DRAFTS.md`

## Outputs
- A README in every canonical directory that qualifies its contents
- Synchronized documentation references across the repository

## Procedure

### Step 1 — README Required Per Canonical Directory
Every top-level canonical directory must include a README that qualifies its contents.
The root README is covered in Step 2.

Minimum required sections:
- Purpose
- Scope
- Related Documents
- Non-Negotiables
- Update Triggers

Required order:
Purpose → Scope → Related Documents → Non-Negotiables → Update Triggers

### Step 2 — Root README Entry Point
`README.md` must:
- define the repository purpose and invariants
- include Purpose, Scope, Related Documents, Non-Negotiables, Update Triggers
- use the required section order
- list top-level directories in canonical order
- link to each top-level README
- provide the start-here reading order

### Step 3 — Authoritative Indices
- `protocols/README_PROTOCOLS.md` is the authoritative list of protocol files.
- `concepts/README_CONCEPTS.md` is the authoritative list of concept files.
- `chapters/README_CHAPTERS.md` is the authoritative definition of chapter bundle structure.

### Step 4 — Reference Integrity
When any canonical file is added, removed, or renamed, update references in:
- `README.md`
- `AUTHORING_PLAN.md`
- `book/README_BOOK.md`
- `concepts/README_CONCEPTS.md`
- `protocols/README_PROTOCOLS.md`
- `chapters/README_CHAPTERS.md`
- `drafts/README_DRAFTS.md`
- affected protocol bodies

---

## Checks (Pass / Fail)
- [ ] Every canonical directory contains a qualifying README
- [ ] Required sections are present in each canonical README
- [ ] Root README lists top-level directories and links to each README
- [ ] Root README includes Purpose, Scope, Related Documents, Non-Negotiables, Update Triggers
- [ ] Root README follows the required section order
- [ ] Protocol and concept indices are authoritative and current
- [ ] Chapter bundle structure is documented once and referenced everywhere
- [ ] No references to removed or legacy files remain

## Notes
Keep documentation short, explicit, and path-based. Avoid implicit references.

## Non-Negotiables
- No canonical directory is allowed without a qualifying README.
- Indices are authoritative; update them on every change.

## Update Triggers
- Any change to directory structure or documentation scope
- Any addition or removal of canonical files
- Any change to authoritative indices
