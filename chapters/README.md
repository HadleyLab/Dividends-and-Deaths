## Global Narrative Asset Index (Required)

This repository enforces a **single global index** of narrative assets to prevent duplicate IDs, duplicated episodes, and drift across chapters.

**Location:** the global narrative asset index lives in a dedicated file:

```
chapters/global_ledger.md
```

This separation is intentional and required for scale.

### Index Rules

- **One asset, one canonical ID.** Do not create a new asset if one already exists.
- If a duplicate is created by mistake, it must be marked **DEPRECATED** and redirected to the canonical ID.
- Variants (`a/b/c`) are permitted only when the same root episode must appear with materially different boundaries or engine mappings.
- Every asset must have exactly **one Home Chapter** (first canonical appearance).

### Enforcement and Bootstrap Workflow

This project assumes an initial **bootstrap phase** in which existing chapters may contain narrative material that predates the global ledger.

During bootstrap:
- Existing chapters are **converted into ledger entries** to prime `chapters/global_ledger.md`.
- This conversion is a one-time normalization step and does **not** require prose changes.
- Duplicate or overlapping assets discovered during conversion must be resolved via canonical IDs, deprecation, and redirects.

After bootstrap:
- `chapters/global_ledger.md` becomes mandatory and authoritative.
- No new narrative asset may appear unless it is first registered in the global ledger.
- Chapters may only reference assets that already exist in the global ledger.

Structural audits must verify that all assets in chapter ledgers are registered in `chapters/global_ledger.md`.
