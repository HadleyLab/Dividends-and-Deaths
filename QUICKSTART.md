# Quickstart — Writing *Dividends & Deaths* Without Getting Lost

This is the fast path. If you do not want to read the full authoring plan, start here.
It follows the same rules but compresses the sequence into a narrative you can act on immediately.

For the full system, read `AUTHORING_GUIDE.md`.

---

## The One Sentence You Must Obey

> **Structure precedes prose. Prose precedes polish.**

Everything you do in this repository either strengthens that chain or breaks it.

---

## The Story of How Work Moves Through the System

You begin with a real episode or a clear claim.
It does not go straight into prose.
It becomes an asset first.

Assets live in ledgers. Ledgers determine what is allowed to appear in prose.
If it is not in the ledger, it is not in the chapter.

Chapters are bundles, not documents. Each chapter contains:
- the prose (what the reader sees)
- the ledger (what governs it)
- the scene map (how the structure holds)

This is how the system keeps meaning stable while the manuscript grows.

---

## The Minimum Path (Do This, In Order)

1. **Choose the chapter.**  
   Open `book/spine.md` and write down the Chapter Question, Claim, and Exit Handoff.

2. **Ledger the episode.**  
   Add the assets to `chapters/NN_chapter_name/chapter_NN_ledger.md`.  
   Register every asset in `chapters/GLOBAL_LEDGER.md`.

3. **Align the scenes.**  
   Update `chapters/NN_chapter_name/chapter_NN_scene.md` so headings match prose order.

4. **Run compliance.**  
   Use `protocols/protocol_canon_compliance.md` before drafting prose.

5. **Draft from the ledger.**  
   Write only what the ledger contains. No new assets.

That is the workflow. It is not optional.

---

## The Map (Where Work Lives)

- `book/` — governance and authority  
- `concepts/` — canonical ontology  
- `protocols/` — execution rules and checks  
- `chapters/` — governed chapter bundles  
- `drafts/` — exploratory, non-canonical work

---

## AI Use, Explained Like a Rule

There are two planes:
- The ChatGPT app makes decisions.
- Codex edits files.

**Rule:** ChatGPT thinks. Codex edits.

AI never supplies authority. It enforces structure.

---

## Scenarios You Will Actually Run (From Draft to NYT-Ready)

Think of the project as a sequence of controlled passes. These are the scenarios you’ll cycle through:

### 1) Episode Intake (Raw Truth → Governed Asset)
You have a moment, case, or witnessed event. It is not prose yet.
You want it governed, reusable, and engine-linked.

Outcome:
- An asset entry in the chapter ledger
- A row in the global ledger

### 2) Concept Admission (Meaning → Canon)
You want to name a system idea in prose.
If it does conceptual work, it must be admitted first.

Outcome:
- A concept file in `concepts/`
- Added to `concepts/README_CONCEPTS.md`
- Added to `concepts/concept_vocabulary.md`

### 3) Ledger-First Chapter Build (Assets → Draft)
You want to write a chapter without violating governance.
You draft only what the ledger contains.

Outcome:
- Prose file drafted from the ledger
- Scene map aligned to the prose

### 4) Compliance Pass (Fix Before Polish)
You want to ensure the chapter obeys canon and protocol.
No rewriting yet—just find violations.

Outcome:
- A list of violations with file/line references

### 5) Scene Sync (Structure → Order)
You changed headings or moved sections.
Scene map and ledger order must follow the prose.

Outcome:
- Scene headings match prose
- Ledger order matches scenes

### 6) Global Ledger Maintenance (No Drift)
You added or renamed assets.
The global ledger must match the chapter ledgers.

Outcome:
- All asset IDs registered once
- No duplicates without DEPRECATED redirects

### 7) Compression and Cadence (Polish Only)
You want to tighten language without changing facts.
No new assets, no new claims.

Outcome:
- Prose tightened, cadence improved

### 8) Pre-Publication Readiness (Manuscript Integrity)
You want a coherent, governed Part or full manuscript.
Everything must be ledgered, cited, and compliant.

Outcome:
- Chapters pass protocol checks
- Emotional arc and spine are satisfied

---

## Copy-Paste Commands (Use These Verbatim)

Before you paste a command, include the **episode** or **scope** it refers to.
“This episode” means the raw paragraph you provide (a moment, case, or witnessed event).
The system converts that raw input into a ledgered asset and global registration.

### Ledger an Episode (Raw → Asset)
Paste your episode above this line:
“Add this episode to `chapters/02_dividends/chapter_02_ledger.md` and register it in `chapters/GLOBAL_LEDGER.md`. Use the canonical asset template. Do not write prose.”

### Admit a Concept (Meaning → Canon)
Paste the concept definition above this line:
“Create a concept file in `concepts/` using the canonical structure. Add it to `concepts/README_CONCEPTS.md` and `concepts/concept_vocabulary.md`. Do not write prose.”

### Run Compliance (Pass/Fail Only)
Scope is the files you name:
“Run `protocols/protocol_canon_compliance.md` on `chapters/03_deaths/chapter_03_prose.md` and `chapters/03_deaths/chapter_03_ledger.md`. List violations only. No rewrites.”

### Sync Scenes (Order Only)
Scope is the chapter you name:
“Ensure `chapters/01_the_billable_code/chapter_01_scene.md` headings match `chapter_01_prose.md`. Fix order only.”

### Controlled Rewrite (Polish Only)
Scope is the file you name:
“Tighten `chapters/00_prologue/chapter_00_prose.md` for compression. Do not add new facts. Preserve cadence. No new assets.”

---

## Final Reminder

If you only remember one thing: prose is not canonical unless it is ledgered, registered, and compliant.
