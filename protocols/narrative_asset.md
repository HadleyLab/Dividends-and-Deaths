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
- `scene.md` updated to include the new asset

## Procedure
1. Open the chapter ledger in `chapters/NN_chapter_name/ledger.md`.
2. Confirm the asset belongs in this chapter (serves the Chapter Question, Claim, or Exit Handoff).
3. Assign the next ID using the chapter prefix (e.g., `00-CHAR-07`, `01-PLACE-03`).
4. Fill the template below with canonical details and reuse hooks.
5. If the asset is a Character, include **Status** and **Cultural/National Identity**.
6. Maintain human-readable ledger formatting:
   - Chapter Contract is a bullet list with bold labels.
   - Assets use a `### NN. ID — Name` heading and bolded field labels.
7. Maintain human-readable scene formatting in `scene.md`:
   - Document title: `# Scene Map — NN Chapter Name`.
   - Use `###` headings per scene with a single **Assets:** line.
8. Add or update the `scene.md` entry that uses this asset.
9. Re-run the compliance checks for naming and interior-state rules.

## Checks
- Asset is logged before it appears in prose.
- Character entries include Status and Cultural/National Identity.
- `scene.md` points to the correct asset ID.

## Notes
Append new assets rather than reordering existing IDs.

## Citation Handling
Citations are optional. Use them when a chapter includes a references section or when you want traceable sourcing beyond the Evidence asset.
- Evidence assets may include an optional **Citations** field listing source labels (Author, Year) or a short list of URLs/DOIs.
- Separate Citation assets are only required when a chapter maintains a formal references section.
- When using a `.bib`, use only inline citation keys (e.g., `[@key]`) in the prose and omit any “Selected References” block from the chapter text.
- Do not duplicate citations by mixing inline keys with textual citations like “Author, Year.”
- When a list or block draws from one source, include a single inline key after the list instead of repeating it on each bullet.

## References Handling
Journal names and author initials in reference sections are treated as part of the Evidence asset. Do not log them as separate assets unless they are discussed in the prose as entities.

## Quick Checklist
- ID assigned
- Template filled
- `scene.md` updated
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
