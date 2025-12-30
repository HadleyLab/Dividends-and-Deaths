# Narrative Asset Protocol

## Purpose
Add or update a narrative asset so it is canonical, compliant, and reusable.

## Scope
Applies to any new character, place, object, concept, ritual, or phrase introduced in a chapter.

## Inputs
- `protocols/asset_compliance.md`
- `chapters/NN_chapter_name/ledger.md`
- The draft or scene that introduces the asset

## Outputs
- Updated ledger entry with the next canonical ID
- Scene Map updated to include the new asset

## Procedure
1. Open the chapter ledger in `chapters/NN_chapter_name/ledger.md`.
2. Confirm the asset belongs in this chapter (serves the Chapter Question, Claim, or Exit Handoff).
3. Assign the next ID using the chapter prefix (e.g., `00-CHAR-07`, `01-PLACE-03`).
4. Fill the template below with canonical details and reuse hooks.
5. If the asset is a Character, include **Status** and **Cultural/National Identity**.
6. Add or update the Scene Map entry that uses this asset.
7. Re-run the compliance checks for naming and interior-state rules.

## Checks
- Asset is logged before it appears in prose.
- Character entries include Status and Cultural/National Identity.
- Scene Map points to the correct asset ID.

## Notes
Append new assets rather than reordering existing IDs.

## Quick Checklist
- ID assigned
- Template filled
- Scene Map updated
- Compliance rechecked

## Template
# Narrative Asset Ledger — Chapter XX

## Asset: [Canonical Name]

- **Asset Type:** (see protocols/asset_compliance.md)
- **Status:** (Living / Deceased / Public Figure / Abstract) (if Character)
- **Cultural/National Identity:** (ancestry, geography, faith environment; if Character include national identity)
- **Aliases:** (optional variants, possessives, plurals, abbreviations)
- **Introduced In:** (scene or section)
- **Narrative Function:** (what work this asset does *in this chapter*)
- **Reuse Hook:** (where and how it will reappear later)

## Notes
(Optional: constraints, reminders, compliance flags)
