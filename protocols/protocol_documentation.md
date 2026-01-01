# Documentation Protocol — Naming and Order

## Purpose
Enforce canonical naming, file structure, and ordering so documentation stays consistent and scalable.

This protocol prevents drift when files are renamed, reindexed, or reorganized.

## Scope
Applies to all documentation, protocols, concepts, and chapter bundles.

## Inputs
- `chapters/README.md`
- `AUTHORING_PLAN.md`
- `protocols/README.md`
- `concepts/README.md`

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

Only the directory carries the chapter stem; filenames use the chapter number only.

**Protocols**
- File name: `protocol_<name>.md`

**Concepts**
- File name: `concept_<name>.md`

### Step 2 — Reference Integrity
- When any file is renamed, update all references in:
  - `README.md`
  - `AUTHORING_PLAN.md`
  - `chapters/README.md`
  - `protocols/README.md`
  - `concepts/README.md`
  - protocol bodies

### Step 3 — Ordering Rules
- `chapter_NN_prose.md` headings define scene order.
- `chapter_NN_scene.md` must follow chapter heading order.
- `chapter_NN_ledger.md` must follow scene order.
- `chapters/global_ledger.md` must follow per-chapter ledger order.

### Step 4 — Reindex Triggers
Reindex chapter assets when:
- prose order changes, or
- an asset’s **Type** changes.

Reindex steps:
1. Reorder `chapter_NN_scene.md` to match prose.
2. Reassign IDs in `chapter_NN_ledger.md` by **type**, in scene order.
3. Update all references in prose, scene, and global ledger.
4. Rebuild `chapters/global_ledger.md` from chapter ledgers.

### Step 5 — Index Maintenance
- Update `protocols/README.md` when protocols are added, removed, or renamed.
- Update `concepts/README.md` when concept files change.

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
