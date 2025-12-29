# Dividends & Deaths - Publication Workspace

This repository is now organized like a production system so every chapter can be drafted, audited, and published without rediscovering the rules each time.

## Directory Map
- `docs/` - canonical governance artifacts (spine, compliance spec, concept vocabulary, Digital Maya guidance) plus operational playbooks.
- `assets/ledgers/` - chapter-by-chapter Narrative Asset Ledgers beginning with the Prologue. Every new chapter must add its ledger here.
- `chapters/` - prose drafts. Top-level files are current manuscripts; `first_drafts/` holds archival starters.

## Chapter Build Order
1. Read `docs/governance/chapter_blueprint.md` for the step-by-step recipe.
2. Log or update assets in `assets/ledgers/`.
3. Cross-check the ledger against `docs/governance/narrative_asset_compliance.md`, the book spine, the emotional arc map, and the concept vocabulary.
4. Draft or revise the chapter inside `chapters/`, using the ledger as the authority for scenes, terms, and hooks.

## Publication Readiness
- Governance docs live under `docs/governance/` so legal, editorial, and collaborators can review invariants without touching prose.
- Conceptual definitions and framing devices live under `docs/concepts/` and `docs/overview/` for quick linking in proposals or decks.
- Operational plans (structure passes, delivery schedule) live under `docs/operations/`.

The combination of governance + ledgers + prose is the whole book. Treat each folder as a unit test: governance enforces rules, ledgers validate assets, chapters deliver narrative.
