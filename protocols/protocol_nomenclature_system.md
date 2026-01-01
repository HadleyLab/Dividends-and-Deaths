# Nomenclature System Protocol

## Purpose
Enforce canonical names so files, bundles, and references stay stable.

## Scope
Applies to all canonical documentation, protocols, concepts, and chapter bundles.

## Inputs
- `README.md`
- `protocols/README_PROTOCOLS.md`
- `concepts/README_CONCEPTS.md`
- `chapters/README_CHAPTERS.md`

## Outputs
- Canonically named files and folders
- Updated references where names changed

## Procedure

### Step 1 — Case Rule (README/Indices Only)
Uppercase applies only to README and index files that qualify or enumerate other files.
All other files use lowercase names.

System files (UPPERCASE role token):
- `README.md`
- `AUTHORING_GUIDE.md`
- `chapters/GLOBAL_LEDGER.md`
- `chapters/GLOBAL_REFERENCES.bib`
- `protocols/README_PROTOCOLS.md`
- `README_<DIR>.md` (entire README filename is uppercase)

Content files (lowercase):
- `book/emotional_arc.md`
- `book/spine.md`
- `chapter_NN_prose.md`
- `chapter_NN_scene.md`
- `chapter_NN_ledger.md`

### Step 2 — Chapter Bundle Names (Non-Negotiable)
- Directory: `NN_chapter_name/`
- Files:
  - `chapter_NN_prose.md`
  - `chapter_NN_ledger.md`
  - `chapter_NN_scene.md`
  - `references.bib` (optional; chapter-scoped citations)
  - `figure_NN_XX_short_slug.png` (optional; chapter-scoped figures)

Only the directory carries the chapter stem; filenames use the chapter number only.

### Step 3 — Protocol Names
- File name: `protocol_<name>.md`
- Canonical list must match `protocols/README_PROTOCOLS.md`.

### Step 4 — Concept Names
- File name: `concept_<name>.md`
- Canonical list must match `concepts/README_CONCEPTS.md`.

### Step 5 — Directory Readmes
- Repository root must contain `README.md`.
- Every top-level directory must contain an uppercase README:
  - `book/README_BOOK.md`
  - `concepts/README_CONCEPTS.md`
  - `protocols/README_PROTOCOLS.md`
  - `chapters/README_CHAPTERS.md`
  - `drafts/README_DRAFTS.md`

### Step 6 — Global Files
- Global asset index: `chapters/GLOBAL_LEDGER.md`.
- Global references (optional): `chapters/GLOBAL_REFERENCES.bib`.

---

## Checks (Pass / Fail)
- [ ] Case rule enforced for system vs content files
- [ ] Chapter bundles follow canonical filenames
- [ ] Protocol filenames follow `protocol_<name>.md`
- [ ] Protocol list matches `protocols/README_PROTOCOLS.md`
- [ ] Concept filenames follow `concept_<name>.md`
- [ ] Concept list matches `concepts/README_CONCEPTS.md`
- [ ] Top-level directories include `README_<DIR>.md`
- [ ] Global ledger and global references use canonical names

## Notes
Naming is part of governance. If naming drifts, structure fails.

## Non-Negotiables
- Canonical filenames must be enforced before any prose or ledger updates.
- Do not introduce aliases or legacy filenames in new docs.

## Update Triggers
- Any rename of chapters, protocols, concepts, or directories
- Any new canonical file type
