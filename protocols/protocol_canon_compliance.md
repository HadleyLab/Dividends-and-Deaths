# Canon Compliance Protocol

## Purpose
Enforce the non-negotiable rules that govern naming, interiority, identity, and claims.

## Scope
Applies to the Prologue and all chapters.

## Inputs
- `book/spine.md`
- `book/emotional_arc.md`
- `protocols/protocol_chapter_production.md`
- `protocols/protocol_asset_registration.md`

## Outputs
- Chapters and ledgers that comply with the canon

## Procedure

### Rule 0 — Ordering (Required)
- `chapter_NN_prose.md` headings define scene order.
- `chapter_NN_scene.md` follows chapter heading order.
- `chapter_NN_ledger.md` follows scene order.

### Rule 1 — Naming and Identity
- Only **one living, non–public-figure person may be named** in the entire book:
  - **Pearl Surajee** (the author’s mother)
- All other living people must:
  - remain unnamed, or
  - be referred to by role, relationship, or function
- Deceased people may be named only if:
  - they are family members, or
  - they are public historical or scientific figures
- Public figures are treated as **public-role entities**, not private individuals.

### Rule 2 — Interior-State Prohibition
Do **not** describe or infer thoughts, beliefs, intentions, motives, or private emotions of anyone other than the author.

Exceptions (limited):
- Memory-framed interiority for *deceased* family members or *deceased* colleagues, grounded in:
  - close physical scenes
  - observable behavior
  - spoken words
- Clinical-circumstance framing for *living* family members when a documented diagnosis alters cognition, grounded in:
  - observable behavior
  - care context
  - the author’s direct witness
- Authorial attestation for *biological relatives (shared DNA)* based on direct lived experience and relational proximity.
- Authorial attestation for *spouse/partner* grounded in direct conversation, shared decisions, or observed practice.

Always prefer actions, roles, context, outcomes, and structures.

### Rule 3 — Cultural, Religious, and Identity Representation
- Faith appears as environment, ritual, social rhythm, or inherited structure.
- Faith does **not** appear as doctrine, argument, or apologetics.
- Canonical coexisting faiths:
  - Hinduism
  - Seventh-day Adventism
  - Catholicism
  - Islam
- Trinidadian culture is represented as coexistence without apology, layering rather than resolution, and practice rather than explanation.
- Nationality or ethnicity may be named only when it provides cultural translation, historical/institutional context, or systemic legibility.
- Do not use parenthetical identity tags in prose; integrate identity as a clause.
- Any nationality/ethnicity named must be logged in the chapter ledger as part of the character asset.

### Rule 4 — Language and Jargon
- Technical jargon must be introduced gently, grounded in scene or imagery, and refreshed after long gaps.
- Accuracy is **mandatory**. Density is **optional**.

Rule of thumb: if a term cannot be explained to a lay reader without embarrassment, it does not belong.

### Rule 5 — Narrative Asset Rules
Every narrative asset must be logged in its chapter ledger using the canonical template.

Each asset must include:
- **Canonical Name**
- **Asset Type**
- **Cultural / Historical Context**
- **Narrative Function**
- **Reuse Hook**
- **Aliases** (optional variants, possessives, plurals, abbreviations)
- **Engine Link** — which single canonical engine failure (Discovery, Care, Information) the asset illuminates, if applicable

Character assets must also include:
- **Cultural/National Identity**
- **Status** (Living / Deceased / Public Figure / Abstract)

Canonical asset types:
- Character
- Place
- Object
- Figure
- Ritual
- Economic
- Phrase
- Concept
- Symbol
- Organization
- Policy
- Evidence
- Citation
- Historical case
- Metaphor
- Foreshadowing

Assets not logged are non-canonical.

### Rule 6 — Economic Claims
- Quantified claims must be conservative, order-of-magnitude, and anchored in widely cited public figures or structural logic.
- Avoid precise numbers unless sourced.
- If a claim is not cited, keep it to rough orders of magnitude or qualified ranges.
- The core economic invariant of the book is fixed:

> **Every layer of the system is reimbursed
> except the patient who generates the value.**

Any economic claim that implies harm or exclusion must be traceable to a specific engine failure.

### Rule 7 — Spine and Engine Alignment
Each chapter ledger must explicitly map:
- Chapter Question
- Chapter Claim
- Exit Handoff
- Interrogated Engine(s)

Assets that do not serve one of these functions—or that cannot be mapped to an engine when harm is implied—must be removed or relocated.

### Rule 8 — Authorial Posture
The authorial voice must be observational, grounded, inevitable, and based on lived experience.

Avoid moralizing, villain construction, polemics, and treating death as accidental or mysterious without mechanism.

The book critiques systems, not individuals.

### Rule 9 — Forward Compatibility
- Assets should be introduced early and reused later with new context.
- Avoid one-off assets when a reuse hook exists.
- Assume future chapters will deepen, not repeat.

---

## Checks (Pass / Fail)
- [ ] Ordering rule enforced
- [ ] Living-person naming rule satisfied
- [ ] Interior-state prohibition observed outside allowed exceptions
- [ ] Cultural identity and faith rules observed
- [ ] Jargon translated for lay readers
- [ ] Economic claims framed conservatively and sourced
- [ ] All assets logged and reusable
- [ ] Chapter aligns with spine and canon
- [ ] Chapter assets registered in `chapters/GLOBAL_LEDGER.md`
- [ ] Every referenced death or disparity traceable to a canonical engine failure

## Notes
This protocol defines policy, not style.

## Non-Negotiables
- Living-person naming rule is enforced without exception.
- Interior-state prohibitions are enforced without exception.
- All assets referenced in prose must exist in `chapters/GLOBAL_LEDGER.md`.

## Update Triggers
- When naming, identity, or interiority rules change.
- When chapter ordering or ledger rules change.
