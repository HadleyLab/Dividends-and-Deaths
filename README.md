# Dividends & Deaths - Publication Workspace

This repository is now organized like a production system so every chapter can be drafted, audited, and published without rediscovering the rules each time.

## Directory Map
- `book/` - book-level invariants (overview, spine, emotional arc, publication plan).
- `concepts/` - canonical definitions and framing devices.
- `protocols/` - lab-style workflows (chapter build, narrative asset protocol, asset compliance).
- `chapters/` - chapter bundles; each `NN_chapter_name/` contains `chapter.md` + `ledger.md`.
- `drafts/` - exploratory material and early drafts.

## Naming Standard
- Files use `snake_case` in `book/`, `concepts/`, and `protocols/`. Drafts are exempt.

## Chapter Build Order
1. Read `protocols/chapter_build.md` for the step-by-step recipe.
2. Log or update assets in `chapters/NN_chapter_name/ledger.md`.
3. Confirm the Chapter Contract includes **Chapter Question**, **Chapter Claim**, and **Exit Handoff**.
4. Use `protocols/narrative_asset.md` and fill required fields (Character assets must include **Status** and **Cultural/National Identity**).
5. Cross-check the ledger against `protocols/asset_compliance.md`, the spine, the emotional arc map, and the concept vocabulary.
6. Draft or revise `chapters/NN_chapter_name/chapter.md`, using the ledger as the authority for scenes, terms, and hooks.

## Publication Readiness
- Book invariants live under `book/` so legal, editorial, and collaborators can review without touching prose.
- Conceptual definitions and framing devices live under `concepts/` for quick linking in proposals or decks.
- Protocols live under `protocols/` so every chapter follows the same lab-style workflow.

The combination of governance + ledgers + prose is the whole book. Treat each folder as a unit test: governance enforces rules, ledgers validate assets, chapters deliver narrative.
