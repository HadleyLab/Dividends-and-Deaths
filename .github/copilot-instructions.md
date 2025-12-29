# Copilot Instructions for Dividends & Deaths

## Project Structure & Workflow
- **Three Pillars:**
  - `docs/` — Governance, compliance, and conceptual definitions. Treat as the source of truth for rules, vocabulary, and structure.
  - `assets/ledgers/` — Narrative Asset Ledgers. Every chapter must have a matching ledger, named with a two-digit prefix (e.g., `02_dividends.md`).
  - `chapters/` — Prose drafts. Top-level files are current manuscripts; `first_drafts/` holds exploratory material.

## Authoring & Publication Pipeline
- **Start with Governance:**
  - Read `docs/governance/chapter_blueprint.md` for the required workflow and naming conventions.
  - Use `docs/governance/narrative_asset_compliance.md` and `docs/governance/book_spine.md` to check legal, ethical, and narrative alignment.
  - Reference `docs/concepts/concept_vocabulary.md` for mandated terms and phrases.
- **Asset-First Drafting:**
  - Before writing or revising a chapter, create/update its ledger in `assets/ledgers/`.
  - Each scene in a chapter must map to a logged asset; remove or relocate orphans.
- **Compliance & Status:**
  - Tag each chapter file with a status at the top: `Status: OUTLINE`, `Status: DRAFT`, `Status: STRUCTURE PASS`, or `Status: POLISH`.
  - Use the checklist in `chapters/README.md` before elevating drafts.

## Conventions & Patterns
- **Naming:**
  - Chapters and ledgers use two-digit prefixes (e.g., `01_the_billable_code.md`). Prologue is `00`.
- **Scene Structure:**
  - Open with the ledger's Core Thesis Asset or a mirror scene.
  - Insert governance facts within 600 words of any vignette.
  - Reuse at least one prior asset per chapter.
- **Language:**
  - Use mandated phrases from the concept vocabulary (e.g., "Dividends rise. Deaths fall.").
  - Introduce jargon using the three-step rule: gentle entry, imagery, refresher.
- **Tonal Guardrails:**
  - After grief vignettes, close with a structural cause sentence.
  - Maintain an observational, inevitable tone.

## Key Files & References
- `docs/governance/chapter_blueprint.md` — Workflow and structure rules
- `docs/governance/narrative_asset_compliance.md` — Compliance checklist
- `docs/governance/book_spine.md` — Chapter-level narrative contract
- `docs/concepts/concept_vocabulary.md` — Canonical terms
- `assets/ledgers/` — Asset tracking per chapter
- `chapters/README.md` — Status workflow and tagging

## Example: Adding a New Chapter
1. Draft or update the ledger: `assets/ledgers/NN_chapter_name.md`
2. Run compliance checks using governance docs
3. Draft the chapter: `chapters/NN_chapter_name.md`, tagging status at the top
4. Update `chapters/README.md` with progress

**Do not mix governance, ledgers, and prose in the same file.**

---
For more, see the top-level and chapter `README.md` files. When in doubt, follow the Chapter Blueprint.
