# Dividends & Deaths — How to Write a Book as a System

This repository is a **publication workspace**, not a draft folder.

It demonstrates how to write a complex, high‑stakes nonfiction book using **symbiotic human computation**: an explicit partnership between human judgment and AI‑assisted reasoning, governed by enforceable rules.

The goal is not speed.
The goal is **coherence, accountability, and scale**.

---

## What This Is

This is a manualized system for writing a book where:
- personal episodes do not become memoir
- theory does not become abstraction
- emotion does not outrun mechanism
- death is treated as a systems outcome, not a mystery

The system is designed so **meaning cannot drift**, even as drafts evolve.

---

## Core Method — Symbiotic Human Computation

This book is written through two complementary human inputs:

### 1. Lived Episodes & Cases
The human author injects:
- witnessed episodes (e.g., UCSF, Elena, Hyojung)
- clinical or historical cases (e.g., Atul, father)
- lived experience written directly in prose

These supply **witness, consequence, and moral authority**.

### 2. Formal Concept Construction
The human author also constructs:
- system‑level concepts (e.g., Geometry of Medicine)
- structural models (engines, gears)
- governance frameworks (Digital Māyā, Ma’at)

These supply **structure, constraint, and causal clarity**.

These inputs are intentionally orthogonal.

They are reconciled through **governance**, not intuition.

AI is used to:
- test consistency
- surface contradictions
- compress language
- enforce reuse

AI does *not* supply authority.

---

## Canonical Writing Flow (How the System Runs)

Episodes / Cases ↔ Concepts  
→ Narrative Assets (ledgered)  
→ Chapter Bundles (chapter + ledger + scene)  
→ Book‑Level Governance (spine, emotional arc, red lines)

Key rules:
- **Ledger precedes prose**
- **Concepts precede reuse**
- **Governance overrides style**

This allows the manuscript to behave like a **well‑oiled system** rather than a fragile document.

---

## Directory Guide (Read This First)

### `book/` — Governance
Defines what must remain true across all drafts.
- overview, spine, emotional arc, publication plan
Read: `book/README.md`

### `concepts/` — Canon
Defines what is allowed to exist and what words mean.
- engines, geometry, Digital Māyā, Ma’at, custody, dividends
Read: `concepts/README.md`

### `protocols/` — Execution
Defines *how* work is done.
- chapter build
- narrative asset intake
- asset compliance
- concept intake
Read: `protocols/README.md`

### `chapters/` — Governed Prose
Each chapter lives in its own bundle:
```
NN_chapter_name/
├── chapter.md
├── ledger.md
└── scene.md
```
Read: `chapters/README.md`

### `drafts/`
Ungoverned exploration. Nothing here is canonical.
Read: `drafts/README.md`

---

## Start Here (Production Order)

1. `book/README.md` — governance invariants and authority map
2. `concepts/README.md` — canonical ontology and closed sets
3. `protocols/README.md` — execution rules and checks
4. `chapters/README.md` — governed output and bundle rules
5. `drafts/README.md` — non-canonical exploration only

---

## How to Write a Chapter (Minimal Recipe)

1. Read `book/spine.md` → identify the chapter question, claim, exit handoff.
2. Update the chapter `ledger.md` with every asset, concept, and death reference.
3. Run `protocols/narrative_asset.md` for any episode, person, or case.
4. Check `protocols/asset_compliance.md` for rule violations.
5. Draft `chapter.md` **from the ledger**, not from memory.
6. Update `scene.md` so scenes map cleanly to assets.

If prose introduces something not in the ledger, it is wrong.

---

## How AI Fits In (Explicitly)

AI is used as:
- a consistency checker
- a compression engine
- a governance enforcer
- a second‑pass structural reader

AI is *not* used to:
- invent lived experience
- supply moral authority
- replace human judgment

This keeps Digital Māyā (representation) in balance with Ma’at (accountability).

---

## Author–System Contract

- The human author supplies meaning, witness, and responsibility.
- The system supplies structure, memory, and constraint.
- Neither replaces the other.

Episodes without governance become memoir.
Concepts without episodes become abstraction.

This repository exists to prevent both failures.

---

## Non‑Negotiables

- Governance documents override prose.
- Concepts override narrative when conflicts arise.
- Death must always be traceable to system failure.
- Grief is permitted only when structure is explicit.

If the system blocks progress, fix the input — do not bypass the system.

---

## Documentation Standards (Production Ready)

- **Single source of truth**: every rule lives in exactly one README; other files link to it.
- **Authority order**: `book/` → `concepts/` → `protocols/` → `chapters/` → `drafts/`.
- **Update triggers**: if a rule or structure changes, update the owning README before prose.
- **Scoped language**: each README only describes its directory’s purpose and rules.
- **Link discipline**: every README links upstream (governance) and downstream (execution).
- **Change control**: record governance or canon changes in `CHANGELOG.md`.
