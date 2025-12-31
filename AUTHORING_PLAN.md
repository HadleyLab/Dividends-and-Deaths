# Authoring Plan — Writing *Dividends & Deaths* as a System

This document is the **authoritative authoring guide** for *Dividends & Deaths*.

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
- reader-facing prose (`chapter.md`)
- an authoritative ledger (`ledger.md`)
- a scene map (`scene.md`)

Chapters **consume assets**. They do not invent them.

---

### 4. Editorial Passes (Audits)
Passes do not add content.
They test whether the system holds under scrutiny.

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
chapters/NN_chapter_name/ledger.md
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

## Phase 3 — Scene Mapping

Scenes declare how assets appear as narrative units.

Outputs live in:

```
chapters/NN_chapter_name/scene.md
```

Scene mapping is optional during ledgering and mandatory during chapter build.

---

## Phase 4 — Build Chapter XX (Composition)

### Purpose
Assemble governed assets into a **chapter-length argument**.

### Inputs
- chapter question, claim, and exit (from spine)
- ledgered assets
- canonical concepts
- emotional arc constraints

### Where Prose Is Written

```
chapters/NN_chapter_name/chapter.md
```

### Rules
- prose is drafted **from the ledger**
- no unledgered material may appear
- every death must be traceable to engine failure
- emotion must close with mechanism

This is the **only phase where reader-facing prose is written**.

---

## Phase 5 — Pass 1 Structural Edit (Audit)

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

## Phase 6 — Later Passes (Compression and Polish)

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