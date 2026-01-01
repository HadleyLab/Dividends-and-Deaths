# Dividends & Deaths — How to Write a Book as a System

This repository is a **publication workspace**, not a draft folder.

It is a reference implementation for writing a high‑stakes nonfiction book using **symbiotic human computation**: a governed partnership between human judgment and AI‑assisted reasoning.

The goal is not speed.
The goal is **coherence, accountability, and scale**.

---

## What This Is

This repository defines a system for writing a book where:
- lived experience does not collapse into memoir
- theory does not drift into abstraction
- emotion never outruns mechanism
- death is treated as a systems outcome, not a mystery

The system is designed so **meaning cannot drift**, even as drafts evolve.

---

## Core Method — Symbiotic Human Computation

The book is written through two complementary human inputs:

### 1. Lived Episodes & Cases
The author supplies:
- witnessed episodes (e.g., UCSF, Elena, Hyojung)
- clinical or historical cases (e.g., Atul, father)
- lived experience rendered directly in prose

These provide **witness, consequence, and moral authority**.

### 2. Formal Concept Construction
The author also constructs:
- system‑level concepts (e.g., Geometry of Medicine)
- structural models (engines, gears)
- governance constructs (Digital Māyā, Ma’at)

These provide **structure, constraint, and causal clarity**.

These inputs are intentionally orthogonal.
They are reconciled through **governance and ledgers**, not intuition.

AI is used to:
- check consistency
- surface contradictions
- compress language
- enforce reuse and contracts

AI does **not** supply authority or lived experience.

---

## Canonical Writing Flow

Episodes / Cases ↔ Concepts  
→ Narrative Assets (ledgered)  
→ Chapter Bundles (chapter + ledger + scene)  
→ Book‑Level Enforcement (spine, emotional arc, red lines)

Core invariants:
- **Ledger precedes prose**
- **Concepts precede reuse**
- **Governance overrides style**

This allows the manuscript to function as a **well‑oiled system** rather than a fragile document.

---

## Directory Guide

### `book/` — Governance
Defines what must remain true across all drafts.
- overview, spine, emotional arc, publication plan
Read: `book/README_book.md`

### `concepts/` — Canon
Defines what is allowed to exist and what terms mean.
- engines, geometry, Digital Māyā, Ma’at, custody, dividends
Read: `concepts/README_concepts.md`

### `protocols/` — Execution
Defines how work is done.
- concept intake
- narrative asset registration
- chapter build
- asset compliance
Read: `protocols/README_protocols.md`

### `chapters/` — Governed Prose
Each chapter is a governed bundle:
```
NN_chapter_name/
├── chapter_NN_prose.md
├── chapter_NN_ledger.md
└── chapter_NN_scene.md
```
Only the directory carries the chapter stem; filenames use the chapter number only.
Global asset index: `chapters/global_ledger.md`
Global references (optional): `references.bib`
Read: `chapters/README_chapters.md`

### `drafts/` — Exploration
Ungoverned working space. Nothing here is canonical.
Read: `drafts/README_drafts.md`

---

## Start Here (Production Order)

1. `AUTHORING_PLAN.md` — end‑to‑end authoring lifecycle
2. `book/README_book.md` — governance invariants and authority map
3. `concepts/README_concepts.md` — canonical ontology and closed sets
4. `protocols/README_protocols.md` — execution rules and checks
5. `chapters/README_chapters.md` — governed output rules

---

## Authoring Plan (Required Reading)

All writing, ledgering, editing, and review assumes familiarity with:

- **`AUTHORING_PLAN.md`** — the authoritative manual describing:
  - where prose comes from
  - what ledgering produces
  - how chapter build differs from structural audit
  - how AI is used without replacing authorship

If there is uncertainty about *what to do next*, start there.

---

## How to Write a Chapter (Minimal Recipe)

This recipe assumes you are following `AUTHORING_PLAN.md`.

1. Read `book/spine.md` → identify the chapter question, claim, and exit handoff.
2. Update the chapter `chapter_NN_ledger.md` with all assets, concepts, and death references.
3. Register episodes, people, and cases via `protocols/protocol_narrative_asset_registration.md`.
4. Check constraints using `protocols/protocol_canon_compliance.md`.
5. Draft `chapter_NN_prose.md` **from the ledger**, not from memory.
6. Update `chapter_NN_scene.md` so every scene maps to asset IDs.

If prose introduces material not present in the ledger, it is wrong.

---

## How AI Fits In

AI is used to:
- enforce consistency across files
- surface contradictions
- compress language and reduce redundancy
- act as a second‑pass structural reader

AI is **not** used to:
- invent lived experience
- supply moral authority
- decide what the book claims

This keeps representation (Digital Māyā) in balance with accountability (Ma’at).

---

## Author–System Contract

- The author supplies meaning, witness, and responsibility.
- The system supplies structure, memory, and enforcement.
- Neither replaces the other.

Episodes without governance become memoir.
Concepts without episodes become abstraction.

This repository exists to prevent both failures.

---

## Non‑Negotiables

- Governance documents override prose.
- Canonical concepts override narrative when conflicts arise.
- Death must always be traceable to system failure.
- Grief is permitted only after structure is explicit.

If the system blocks progress, fix the input — do not bypass the system.
