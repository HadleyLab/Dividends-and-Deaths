# Authoring Guide — Writing *Dividends & Deaths* as a System

This document is the **authoritative authoring guide** for *Dividends & Deaths*.
For a fast entry point, see `QUICKSTART.md`.

It defines:
- where prose comes from,
- how lived experience becomes governed material,
- how chapters are built and audited,
- and how AI tools are used without replacing authorship.

This is a **how-to manual**, not a philosophy statement.

---

## Core Principle

> **Structure precedes prose.  
> Prose precedes polish.  
> Death precedes explanation.**

The book is written as a **system**, not a stream of drafts.

---

## Canonical Writing Objects

The authoring process operates on four distinct objects. They are not interchangeable.

### 1. Episodes (Raw Human Input)
- lived experience
- witnessed events
- clinical or historical cases
- memories, notes, rough prose

Episodes are **human-supplied** and ungoverned.

---

### 2. Narrative Assets (Governed Units)
- episodes, people, places, objects, figures
- each registered once
- each assigned a structural function and engine link

Narrative assets are created by **ledgering**.

---

### 3. Chapter Bundles (Argument Containers)
Each chapter is a bundle of:
- reader-facing prose (`chapter_NN_prose.md`)
- an authoritative ledger (`chapter_NN_ledger.md`)
- a scene map (`chapter_NN_scene.md`)

Chapters **consume assets**. They do not invent them.

Ordering rule:
- `chapter_NN_prose.md` headings define scene order.
- `chapter_NN_scene.md` must follow chapter heading order.
- `chapter_NN_ledger.md` must follow scene order.

---

### 4. Editorial Passes (Audits)
Passes do not add content.
They test whether the system holds under scrutiny.

---

## Concept Placement (Canonical)

Concepts are not placed by inference. They are placed by explicit governance.

### Purpose
Bind required concepts from the book map to chapter assets before prose is drafted.

### Source of Truth
`book/overview.md` defines the required concept placement per part and chapter.

### Required Outputs
- Concept assets in `chapters/NN_chapter_name/chapter_NN_ledger.md`
- Concept asset IDs referenced in `chapters/NN_chapter_name/chapter_NN_scene.md`
- Concept assets registered in `chapters/GLOBAL_LEDGER.md`

If a chapter is missing a required concept, the ledger is incomplete and prose is non-canonical.

---

## Tooling Model (Critical)

This project uses **two AI interfaces**, each with a distinct role.

### ChatGPT App — Control Plane (Thinking)
Use the ChatGPT app to:
- reason about next steps
- clarify protocols and invariants
- design or revise governance
- debug confusion ("where does this output go?")
- diagnose failures found during audits

The ChatGPT app is used for **decisions**, not file edits.

---

### ChatGPT Codex in VS Code — Execution Plane (Doing)
Use Codex in VS Code to:
- edit repository files
- ledger episodes
- build chapters
- update ledgers and scenes
- apply audit fixes

Codex is used when the instruction is: *"change this file."*

**Rule:** ChatGPT thinks. Codex edits.

---

## Phase 1 — Episode Intake (Human Work)

The author recalls or drafts:
- a moment (e.g., UCSF)
- a trajectory (e.g., father)
- a case (e.g., Elena, Atul)

This material may exist as notes, rough prose, or spoken recall.

At this stage:
- nothing is canonical
- nothing enters a chapter

---

## Phase 2 — Ledger an Episode (Asset Creation)

### Purpose
Convert lived experience into a **governed, reusable system asset**.

### Where Outputs Go
Ledgering always occurs inside a **chapter bundle**:

```
chapters/NN_chapter_name/chapter_NN_ledger.md
```

Every episode has:
- exactly **one home chapter**
- exactly **one ledger entry**
- a stable asset ID

### What Ledgering Produces
- an asset record
- an engine failure mapping
- a narrative function
- reuse hooks for future chapters

### What Ledgering Does *Not* Produce
- prose
- scenes
- emotional pacing

Ledgering extracts **structure**, not language.

---

## Phase 3 — Place Required Concepts (Canonical Mapping)

### Purpose
Make the chapter obey the part-level concept map before prose exists.

### Inputs
- `book/overview.md`
- `concepts/README_CONCEPTS.md`
- `chapters/NN_chapter_name/chapter_NN_ledger.md`
- `chapters/NN_chapter_name/chapter_NN_scene.md`
- `chapters/GLOBAL_LEDGER.md`

### Procedure
1. Locate the chapter's required concepts in `book/overview.md`.
2. Add each required concept as an asset in `chapter_NN_ledger.md`.
3. Register those assets in `chapters/GLOBAL_LEDGER.md`.
4. Reference the concept asset IDs in `chapter_NN_scene.md`.

If a concept cannot be placed, revise the chapter inputs before drafting prose.

---

## Phase 4 — Scene Mapping

Scenes declare how assets appear as narrative units.

Outputs live in:

```
chapters/NN_chapter_name/chapter_NN_scene.md
```

Scene mapping is optional during ledgering and mandatory during chapter build.
Scene order must match `chapter_NN_prose.md` headings.

---

## Phase 5 — Build Chapter XX (Composition)

### Purpose
Assemble governed assets into a **chapter-length argument**.

### Inputs
- chapter question, claim, and exit (from spine)
- ledgered assets
- canonical concepts
- emotional arc constraints
 - required concepts from `book/overview.md`

### Where Prose Is Written

```
chapters/NN_chapter_name/chapter_NN_prose.md
```

### Rules
- prose is drafted **from the ledger**
- no unledgered material may appear
- every death must be traceable to engine failure
- emotion must close with mechanism

This is the **only phase where reader-facing prose is written**.

---

## Production Initialization and Reindex

When prose order changes, reindex IDs to match the new sequence.

Steps:
- Ensure `chapter_NN_scene.md` follows `chapter_NN_prose.md` heading order.
- Reassign IDs in `chapter_NN_ledger.md` by **type**, in scene order.
- Update all references in `chapter_NN_prose.md`, `chapter_NN_scene.md`, and `chapters/GLOBAL_LEDGER.md`.
- Rebuild the global ledger from the updated chapter ledgers.

IDs are append-only within a given index pass, but the index itself is **prose-derived**.

---

## Phase 6 — Pass 1 Structural Edit (Audit)

### Purpose
Test whether the chapter works **without relying on eloquence**.

### Pass 1 Checks
- spine alignment
- engine failure traceability
- correct asset usage
- absence of redundancy or drift

### What Pass 1 Never Does
- rewrite sentences
- polish language

Failures are fixed in:
- ledgers
- asset mappings
- chapter structure

Not in sentence-level prose.

---

## Phase 7 — Later Passes (Compression and Polish)

### Pass 2 — Concept Compression
- remove redundancy
- enforce canonical phrasing
- strengthen callbacks

### Pass 3 — Language and Cadence
- tighten sentences
- refine tone
- remove defensive or grant-style language

These passes occur **only after structural integrity is confirmed**.

---

## Phase Outputs and Definition of Done

Use this checklist to scale work across collaborators.

### Phase 1 — Episode Intake
- **Output:** raw episode notes (non-canonical)
- **Done when:** the episode can be summarized in one sentence without interpretation

### Phase 2 — Ledger an Episode
- **Outputs:**
  - `chapters/NN_chapter_name/chapter_NN_ledger.md` entry
  - `chapters/GLOBAL_LEDGER.md` row
- **Done when:** asset has a canonical ID, engine link, and reuse hook

### Phase 3 — Scene Mapping
- **Output:** `chapters/NN_chapter_name/chapter_NN_scene.md` entries
- **Done when:** every scene lists asset IDs that exist in the global ledger

### Phase 4 — Build Chapter
- **Output:** `chapters/NN_chapter_name/chapter_NN_prose.md` draft
- **Done when:** every asset referenced in prose is logged and engine-linked

### Phase 5 — Structural Edit (Pass 1)
- **Output:** audit notes and fixes applied to ledgers/scenes
- **Done when:** chapter passes all protocol checks without prose edits

### Phase 6 — Compression and Polish
- **Output:** tightened prose with canonical phrasing enforced
- **Done when:** redundancy removed and cadence tuned without changing claims

---

## Role of AI (Explicit)

AI is used to:
- enforce consistency
- surface contradictions
- assist with compression and clarity

AI is **not** used to:
- invent lived experience
- determine moral authority
- decide what the book claims

AI enforces structure.
Humans supply meaning.

---

## AI Handoff Format (Required)

When requesting AI review or assistance, provide:

- **Files in scope:** exact paths (chapter, ledger, scene, global ledger)
- **Goal:** what must be validated or transformed
- **Constraints:** non-negotiables and exclusions
- **Required outputs:** checklist or specific edits

Example:
\"Validate that `chapters/02_dividends/chapter_02_prose.md` only references assets listed in `chapters/02_dividends/chapter_02_ledger.md` and `chapters/GLOBAL_LEDGER.md`. Flag missing IDs and mismatches. Do not rewrite prose.\"
AI outputs must be actionable lists or diff-ready edits.

---

## Mental Model

> **Episodes are human truth.  
> Ledgering makes truth reusable.  
> Chapters assemble truth into argument.  
> Audits test whether the argument survives scrutiny.**

---

## Final Invariants

- If prose exists without a ledger entry, it is wrong.
- If death appears without mechanism, it is wrong.
- If a protocol blocks progress, fix the input — do not bypass the system.

---

End of authoring plan.
