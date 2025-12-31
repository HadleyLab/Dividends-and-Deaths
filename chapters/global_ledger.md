# Global Narrative Asset Ledger

This file is the **single authoritative index** of all narrative assets in *Dividends & Deaths*.

It exists to prevent duplication, enforce reuse, and allow the book to scale without narrative drift. All chapter-level ledgers (`chapters/NN/ledger.md`) must reference assets defined here.

If a conflict exists between a chapter ledger and this file, **this file wins**.

---

## Purpose

The Global Narrative Asset Ledger:
- assigns **canonical IDs** to narrative assets
- records each asset’s **home chapter**
- tracks **engine linkages** and status
- enforces deprecation and redirection rules

No narrative asset may appear in prose unless it is registered here.

---

## Asset Types (Closed Set)

Every asset must be classified as exactly one of the following:

- **Episode** — a bounded event or case (clinical, institutional, personal)
- **Character** — a person appearing narratively (including the author)
- **Place** — a location or institution
- **Object** — a physical or digital artifact
- **Concept Instance** — a narrative instantiation of a canonical concept
- **Evidence** — a study, dataset, statistic, or paper
- **Figure** — a diagram, chart, or visual explanatory object

---

## ID Conventions

Canonical IDs follow this format:

```
NN-TYPE-XX
```

Where:
- `NN` = two-digit home chapter number
- `TYPE` = EPIS, CHAR, PLACE, OBJ, CONCEPT, EVID, FIG
- `XX` = sequential integer within chapter

Variants may append a suffix:

```
NN-TYPE-XXa / NN-TYPE-XXb
```

Variants are permitted **only** when the same root episode must appear with materially different boundaries or engine mappings.

---

## Duplication and Deprecation Rules (Non-Negotiable)

- **One asset, one canonical ID.** Reuse is mandatory.
- If a duplicate is created, it must be marked **DEPRECATED** and redirected to the canonical ID.
- Deprecated assets may not be referenced in new prose.
- Chapter ledgers must update references when deprecations occur.

Silent duplication is a protocol violation.

---

## Global Asset Index

| Asset ID | Canonical Name | Type | Home Chapter | Engine Link | Status | Redirect / Notes |
|---|---|---|---|---|---|---|
| _(populate as assets are introduced)_ | | | | | | |

---

## Workflow Integration

- **Ledgering an episode** registers or updates an entry here.
- **Chapter build** may only reference assets listed here.
- **Structural audits (Pass 1)** must verify:
  - no duplicate assets
  - no deprecated IDs in use
  - correct engine mappings

---

## Invariants

- This file is append-only except for deprecations.
- IDs are never reused.
- Home chapters do not change once assigned.
- If this file blocks progress, fix the input — do not bypass the ledger.

---

End of global narrative asset ledger.
