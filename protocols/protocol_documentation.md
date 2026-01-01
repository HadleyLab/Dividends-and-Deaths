# Documentation Protocol — Naming and Order

## Purpose
Enforce canonical naming, file structure, and ordering so documentation stays consistent and scalable.

This protocol prevents drift when files are renamed, reindexed, or reorganized.

## Scope
Applies to all documentation, protocols, concepts, and chapter bundles.

## Inputs
- `README.md`
- `book/README_book.md`
- `chapters/README_chapters.md`
- `AUTHORING_PLAN.md`
- `protocols/README_protocols.md`
- `concepts/README_concepts.md`
- `drafts/README_drafts.md`

## Outputs
- Canonically named files and folders
- Updated references across the repository
- Rebuilt ledgers and global index when reindexing is required

## Procedure

### Step 1 — Naming Conventions (Non-Negotiable)

**Chapter bundles**
- Directory: `NN_chapter_name/`
- Files:
  - `chapter_NN_prose.md`
  - `chapter_NN_ledger.md`
  - `chapter_NN_scene.md`
  - `references.bib` (optional; chapter-scoped citations)
  - `figure_NN_XX_short_slug.png` (optional; chapter-scoped figures)

Only the directory carries the chapter stem; filenames use the chapter number only.

**Protocols**
- File name: `protocol_<name>.md`

**Concepts**
- File name: `concept_<name>.md`

**Directories**
- Repository root must contain `README.md` (GitHub entry point).
- Every top-level directory must contain `README_<dir>.md` (uppercase README_):
  - `book/README_book.md`
  - `chapters/README_chapters.md`
  - `concepts/README_concepts.md`
  - `protocols/README_protocols.md`
  - `drafts/README_drafts.md`
- Additional files are allowed only when declared by a protocol (e.g., ledgers, prose, scenes, references).

**Global ledgers**
- `chapters/global_ledger.md` is the canonical global asset index.

**Global references**
- `references.bib` at repository root is allowed for cross‑chapter references.

### Step 2 — README Scheme (Required)

**Root `README.md`**
- Must list top-level directories in this order: `book/`, `concepts/`, `protocols/`, `chapters/`, `drafts/`.
- Must include the chapter bundle file naming example (`chapter_NN_prose.md`, `chapter_NN_ledger.md`, `chapter_NN_scene.md`).
- Must include the “Start Here” reading order and the minimal chapter recipe.
- Must link to each stemmed directory readme (`book/README_book.md`, `concepts/README_concepts.md`, `protocols/README_protocols.md`, `chapters/README_chapters.md`, `drafts/README_drafts.md`).

**`chapters/README_chapters.md`**
- Must define bundle structure and ordering rule (prose → scene → ledger).
- Must include bootstrap and reindex procedures.

**`book/README_book.md`**
- Must define governance invariants and authority ordering.

**`drafts/README_drafts.md`**
- Must state that drafts are non-canonical and ungoverned.

**`protocols/README_protocols.md`**
- Must list all protocol files and remain authoritative for protocol names.

**`concepts/README_concepts.md`**
- Must list all concept files and remain authoritative for concept names.

### Step 3 — Reference Integrity
- When any file is renamed, update all references in:
  - `README.md`
  - `AUTHORING_PLAN.md`
  - `book/README_book.md`
  - `chapters/README_chapters.md`
  - `protocols/README_protocols.md`
  - `concepts/README_concepts.md`
  - `drafts/README_drafts.md`
  - protocol bodies

### Step 4 — Ordering Rules
- `chapter_NN_prose.md` headings define scene order.
- `chapter_NN_scene.md` must follow chapter heading order.
- `chapter_NN_ledger.md` must follow scene order.
- `chapters/global_ledger.md` must follow per-chapter ledger order.

### Step 5 — Reindex Triggers
Reindex chapter assets when:
- prose order changes, or
- an asset’s **Type** changes.

Reindex steps:
1. Reorder `chapter_NN_scene.md` to match prose.
2. Reassign IDs in `chapter_NN_ledger.md` by **type**, in scene order.
3. Update all references in prose, scene, and global ledger.
4. Rebuild `chapters/global_ledger.md` from chapter ledgers.

### Step 6 — Index Maintenance
- Update `protocols/README_protocols.md` when protocols are added, removed, or renamed.
- Update `concepts/README_concepts.md` when concept files change.

### Step 7 — Documentation Style (LLM + Human)
- Use explicit file paths in backticks (no implicit references).
- Use one action per list item; avoid compound instructions.
- Prefer checklists for pass/fail steps.
- Keep section order consistent: Purpose, Scope, Inputs, Outputs, Procedure, Checks, Notes, Non-Negotiables, Update Triggers.
- Avoid ambiguous pronouns (“this”, “that”) when a file or rule can be named.

## Checks (Pass / Fail)
- [ ] Chapter bundles follow the canonical filenames
- [ ] Protocol filenames follow `protocol_<name>.md`
- [ ] Concept filenames follow `concept_<name>.md`
- [ ] No references to legacy filenames remain
- [ ] Scene order matches prose order
- [ ] Ledger order matches scene order
- [ ] Global ledger order matches per-chapter ledger order
- [ ] Protocol and concept indices are updated

## Notes
- Naming is part of governance. If naming drifts, structure fails.
- When in doubt, update the protocol first, then the files.

## Non-Negotiables
- Canonical filenames must be enforced before any prose or ledger updates.
- README indices are authoritative; update them on every rename.
- Do not introduce aliases or legacy filenames in new docs.

## Update Triggers
- Any rename or reindex of chapters, protocols, or concepts.
- Any change to chapter bundle structure or README scheme.
