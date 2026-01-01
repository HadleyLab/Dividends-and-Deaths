# Global Narrative Asset Ledger

This file is the **single authoritative index** of all narrative assets in *Dividends & Deaths*.

It exists to prevent duplication, enforce reuse, and allow the book to scale without narrative drift. All chapter-level ledgers (`chapters/NN_chapter_name/ledger.md`) must reference assets defined here.

If a conflict exists between a chapter ledger and this file, **this file wins**.

---

## Purpose

The Global Narrative Asset Ledger:
- assigns **canonical IDs** to narrative assets
- records each asset’s **home chapter**
- tracks **engine linkages** and status
- enforces deprecation and redirection rules

Engine Link stores **one** canonical engine per asset: **Discovery**, **Care**, or **Information**.

No narrative asset may appear in prose unless it is registered here.

---

## Asset Types (Closed Set)

Every asset must be classified as exactly one of the following:

- **Character** — a person appearing narratively (including the author)
- **Place** — a location or institution
- **Object** — a physical or digital artifact
- **Figure** — a diagram, chart, or visual explanatory object
- **Ritual** — a repeated practice or rite used as a narrative unit
- **Economic** — a defined economic mechanism or unit
- **Phrase** — a named line or structural refrain
- **Concept** — a canonical concept used narratively
- **Symbol** — a named symbol or emblematic object
- **Organization** — an institution or formal entity
- **Policy** — a law, program, or formal policy instrument
- **Evidence** — a study, dataset, statistic, or paper
- **Citation** — a formal reference unit when cited as an object
- **Historical case** — a bounded historical event or case
- **Metaphor** — a named metaphor used as a structural unit
- **Foreshadowing** — a named foreshadowing device

---

## ID Conventions

Canonical IDs follow this format:

```
NN-CODE-XX
```

Where:
- `NN` = two-digit home chapter number
- `CODE` = asset code (see below)
- `XX` = sequential integer within chapter

Variants may append a suffix:

```
NN-TYPE-XXa / NN-TYPE-XXb
```

Variants are permitted **only** when the same root episode must appear with materially different boundaries or engine mappings.

### Asset Codes

**Preferred codes (use for new assets):**
CHAR, PLACE, OBJ, FIG, RIT, ECON, PHRASE, CONCEPT, SYMBOL, ORG, POLICY, EVID, HIST, METAPHOR, FORESHADOW

**Legacy codes (already in use; keep only if the asset already exists):**
THESIS, CASE, DATA, TOOL, CULT, LEDGER, EXIT, OBJECT

---

## Duplication and Deprecation Rules (Non-Negotiable)

- **One asset, one canonical ID.** Reuse is mandatory.
- If a duplicate is created, it must be marked **DEPRECATED** and redirected to the canonical ID.
- Deprecated assets may not be referenced in new prose.
- Chapter ledgers must update references when deprecations occur.

Silent duplication is a protocol violation.

---

## Global Asset Index

| Asset ID | Canonical Name | Type | Home Chapter | Engine Link | Status | Redirect / Notes |
|---|---|---|---|---|---|---|
| 00-PHRASE-01 | The Mother of Precision Medicine | Phrase | 00 | Care |  |  |
| 00-HIST-01 | Henrietta Lacks | Historical case | 00 | Information |  |  |
| 00-OBJ-01 | HeLa cell line | Object | 00 | Care |  |  |
| 00-PLACE-01 | Johns Hopkins segregated ward | Place | 00 | Care |  |  |
| 00-SYMBOL-01 | Hospital freezer | Symbol | 00 | Discovery |  |  |
| 00-CONCEPT-01 | Dividends and deaths frame | Phrase | 00 | Care |  |  |
| 00-CONCEPT-02 | Billable Code (named as currency) | Phrase | 00 | Information |  |  |
| 00-CONCEPT-03 | Prologue exit hook | Phrase | 00 | Care |  |  |
| 00-PHRASE-02 | Behind God’s Back | Phrase | 00 | Care |  |  |
| 00-CHAR-01 | Father - Leonard Kempthorne | Character | 00 | Care | Deceased |  |
| 00-CHAR-02 | Granny Veronica | Character | 00 | Information | Deceased |  |
| 00-CHAR-03 | Aunty Betty | Character | 00 | Care | Deceased |  |
| 00-CHAR-04 | Major Francis Hadley | Character | 00 | Care | Deceased |  |
| 00-PLACE-02 | Charlotteville, Tobago | Place | 00 | Care |  |  |
| 00-PLACE-03 | Englishman's Bay | Place | 00 | Care |  |  |
| 00-PLACE-04 | Trinidad and Tobago | Place | 00 | Care |  |  |
| 00-PLACE-05 | Caribbean Union College | Place | 00 | Information |  |  |
| 00-PHRASE-03 | The Rose from Gasparillo | Phrase | 00 | Care |  |  |
| 00-CHAR-05 | Pearl Surajee | Character | 00 | Information | Living |  |
| 00-ORG-01 | National Health Service (NHS) | Organization | 00 | Information |  |  |
| 00-ORG-02 | Seventh-day Adventist community hospital (Trinidad) | Organization | 00 | Information |  |  |
| 00-PLACE-06 | Gasparillo, Trinidad | Place | 00 | Care |  |  |
| 00-PLACE-07 | Andrews University | Place | 00 | Discovery |  |  |
| 00-PLACE-08 | Michigan | Place | 00 | Discovery |  |  |
| 00-PHRASE-04 | Malta, Mangoes, and Mauby | Phrase | 00 | Care |  |  |
| 00-CHAR-06 | Mama | Character | 00 | Care | Deceased |  |
| 00-CHAR-07 | Grandma Anita | Character | 00 | Care | Deceased |  |
| 00-CHAR-08 | Grandpa Frank | Character | 00 | Care | Deceased |  |
| 00-CHAR-09 | Brother (author’s) | Character | 00 | Care | Living |  |
| 00-CONCEPT-04 | Dougla | Concept | 00 | Care |  |  |
| 00-RIT-01 | Malta bottle ritual | Ritual | 00 | Care |  |  |
| 00-OBJ-02 | Mauby drink | Object | 00 | Care |  |  |
| 00-OBJ-03 | Oorni (Hindu headpiece) | Object | 00 | Information |  |  |
| 00-RIT-02 | Divali bamboo by the river | Ritual | 00 | Care |  |  |
| 00-RIT-03 | Boxing Day | Ritual | 00 | Care |  |  |
| 00-RIT-04 | Christmas | Ritual | 00 | Care |  |  |
| 00-RIT-05 | Sabbath | Ritual | 00 | Information |  |  |
| 00-RIT-06 | Pooja and bhajan prayers | Ritual | 00 | Information |  |  |
| 00-RIT-07 | Hindu cremation pyre by the village creek | Ritual | 00 | Care |  |  |
| 00-HIST-02 | Red House fire of 1903 | Historical case | 00 | Information |  |  |
| 00-PLACE-09 | St. James, Port of Spain | Place | 00 | Information |  |  |
| 00-PLACE-10 | River Estate | Place | 00 | Discovery |  |  |
| 00-PLACE-11 | Barataria | Place | 00 | Care |  |  |
| 00-PLACE-12 | Fatima College | Place | 00 | Information |  |  |
| 00-SYMBOL-02 | Fatima naming lineage | Symbol | 00 | Care |  |  |
| 00-SYMBOL-03 | Virgin Mary | Symbol | 00 | Information |  |  |
| 00-PHRASE-05 | A Long Line of Universal Men | Phrase | 00 | Care |  |  |
| 00-CONCEPT-05 | Universal men | Phrase | 00 | Care |  |  |
| 00-ORG-03 | Commonwealth of Nations | Organization | 00 | Information |  |  |
| 00-PHRASE-06 | Code and Calling | Phrase | 00 | Information |  |  |
| 00-OBJ-04 | Tandy TRS-80 | Object | 00 | Information |  |  |
| 00-OBJ-05 | IBM 286 clone | Object | 00 | Information |  |  |
| 00-FORESHADOW-01 | Code before medicine | Foreshadowing | 00 | Information |  |  |
| 00-CONCEPT-06 | BASIC | Object | 00 | Information |  |  |
| 00-PHRASE-07 | Migration and the Cost of Opportunity | Phrase | 00 | Care |  |  |
| 00-CONCEPT-07 | Migration as cost | Phrase | 00 | Care |  |  |
| 00-PLACE-13 | Orlando, Florida | Place | 00 | Care |  |  |
| 00-PLACE-14 | England | Place | 00 | Information |  |  |
| 00-PLACE-15 | United States | Place | 00 | Care |  |  |
| 00-HIST-03 | HIV epidemic | Historical case | 00 | Information |  |  |
| 00-PHRASE-08 | Franklin’s University and the Promise of Precision | Phrase | 00 | Discovery |  |  |
| 00-PLACE-16 | University of Pennsylvania | Place | 00 | Information |  |  |
| 00-CHAR-10 | Benjamin Franklin | Character | 00 | Discovery | Public Figure |  |
| 00-ORG-04 | Quakers (Religious Society of Friends) | Organization | 00 | Discovery |  |  |
| 00-CONCEPT-08 | Ivy League | Organization | 00 | Discovery |  |  |
| 00-HIST-04 | Human Genome Project | Historical case | 00 | Discovery |  |  |
| 00-CHAR-11 | Barack Obama | Character | 00 | Care | Public Figure |  |
| 00-POLICY-01 | Precision Medicine Initiative | Policy | 00 | Discovery |  |  |
| 00-ORG-05 | Children’s Hospital of Philadelphia (CHOP) | Organization | 00 | Information |  |  |
| 00-PLACE-17 | West Philadelphia | Place | 00 | Discovery |  |  |
| 00-PLACE-18 | CHOP Center for Applied Genomics (CAG) | Place | 00 | Information |  |  |
| 00-CHAR-12 | Hakon Hakonarson | Character | 00 | Discovery | Public Figure |  |
| 00-ORG-06 | NeuroFix Therapeutics | Organization | 00 | Care |  |  |
| 00-CONCEPT-09 | GWAS | Object | 00 | Discovery |  |  |
| 00-PHRASE-09 | The Transitional Year and the Decision Not to Cut | Phrase | 00 | Care |  |  |
| 00-ORG-07 | Hospital of the University of Pennsylvania | Organization | 00 | Discovery |  |  |
| 00-PHRASE-10 | Stanford, Ontologies, and the Skeleton of the System | Phrase | 00 | Information |  |  |
| 00-ORG-08 | Stanford University | Organization | 00 | Information |  |  |
| 00-CHAR-13 | Mark Musen | Character | 00 | Care | Public Figure |  |
| 00-CONCEPT-10 | SNOMED | Object | 00 | Information |  |  |
| 00-CONCEPT-11 | ICD | Object | 00 | Information |  |  |
| 00-CONCEPT-12 | CPT | Object | 00 | Information |  |  |
| 00-CONCEPT-13 | ADHD | Historical case | 00 | Care |  |  |
| 00-CHAR-14 | Atul Butte | Character | 00 | Information | Public Figure |  |
| 00-PHRASE-11 | UCSF, Eighty Million Lives, and the Profit of Failure | Phrase | 00 | Information |  |  |
| 00-PLACE-19 | California | Place | 00 | Information |  |  |
| 00-PLACE-20 | UCSF and Bakar Institute | Place | 00 | Information |  |  |
| 00-ORG-09 | Bakar Institute for Computational Health Sciences | Organization | 00 | Information |  |  |
| 00-CHAR-15 | Mark Zuckerberg | Character | 00 | Information | Public Figure |  |
| 00-ORG-10 | University of California health system | Organization | 00 | Information |  |  |
| 00-EVID-01 | Gene Expression Omnibus | Evidence | 00 | Information |  |  |
| 00-OBJ-06 | FDG-PET scans | Object | 00 | Information |  |  |
| 00-CONCEPT-14 | Alzheimer’s disease | Historical case | 00 | Information |  |  |
| 00-CONCEPT-15 | Profit from failure | Phrase | 00 | Information |  |  |
| 00-PHRASE-12 | Florida, DEI, and a Pacemaker Serial Number | Phrase | 00 | Care |  |  |
| 00-PLACE-21 | Florida and UCF | Place | 00 | Information |  |  |
| 00-ORG-11 | University of Central Florida | Organization | 00 | Discovery |  |  |
| 00-ORG-12 | HCA | Organization | 00 | Information |  |  |
| 00-ORG-13 | AdventHealth | Organization | 00 | Information |  |  |
| 00-HIST-05 | COVID-19 | Historical case | 00 | Discovery |  |  |
| 00-EVID-02 | NCT05384912 decentralized imaging trial | Evidence | 00 | Information |  |  |
| 00-ORG-14 | Facebook | Organization | 00 | Information |  |  |
| 00-POLICY-02 | SB 266 (Florida) | Policy | 00 | Information |  |  |
| 00-POLICY-03 | Casey DeSantis Breast Cancer Research grant | Policy | 00 | Discovery |  |  |
| 00-ORG-15 | MammoChat | Organization | 00 | Information |  |  |
| 00-CONCEPT-16 | Hypertension | Historical case | 00 | Care |  |  |
| 00-CONCEPT-17 | Diabetes | Historical case | 00 | Care |  |  |
| 00-CONCEPT-18 | End-stage kidney disease | Historical case | 00 | Information |  |  |
| 00-CONCEPT-19 | Dialysis | Historical case | 00 | Care |  |  |
| 00-OBJ-07 | Pacemaker serial number | Object | 00 | Information |  |  |
| 00-PLACE-22 | Nursing home | Place | 00 | Information |  |  |
| 00-PHRASE-13 | Alzheimer’s, Culture, and COVID | Phrase | 00 | Care |  |  |
| 00-PHRASE-14 | A Universal Future | Phrase | 00 | Care |  |  |
| 00-CHAR-16 | Wife (Spanish Moroccan) | Character | 00 | Discovery | Living |  |
| 00-CHAR-17 | Children (author’s) | Character | 00 | Care | Living |  |
| 00-CONCEPT-20 | Islam | Symbol | 00 | Information |  |  |
| 00-CONCEPT-21 | Spanish | Symbol | 00 | Care |  |  |
| 00-CONCEPT-22 | Arabic | Symbol | 00 | Care |  |  |
| 00-CONCEPT-23 | English | Symbol | 00 | Care |  |  |
| 00-PHRASE-15 | Dividends & Deaths | Phrase | 00 | Care |  |  |
| 00-OBJ-08 | Urn and ashes at Englishman's Bay | Object | 00 | Information |  |  |
| 00-CHAR-18 | Seventh-day Adventist pastor | Character | 00 | Care | Living |  |
| 00-CONCEPT-24 | Open Provenance Token System | Concept | 00 | Information |  |  |
| 00-CONCEPT-25 | Equitable governance layer | Concept | 00 | Care |  |  |
| 00-CHAR-19 | Casey DeSantis | Character | 00 | Discovery | Public Figure |  |
| 00-CONCEPT-26 | LOINC | Object | 00 | Information |  |  |
| 00-CONCEPT-27 | Seventh-day Adventism | Symbol | 00 | Information |  |  |
| 00-CONCEPT-28 | Hinduism | Symbol | 00 | Information |  |  |
| 00-CONCEPT-29 | Catholicism | Symbol | 00 | Information |  |  |
| 00-CONCEPT-30 | Christianity | Symbol | 00 | Information |  |  |
| 00-CONCEPT-31 | Hindi | Symbol | 00 | Care |  |  |
| 00-CONCEPT-32 | Latin | Symbol | 00 | Care |  |  |
| 00-CONCEPT-33 | SQL | Object | 00 | Information |  |  |
| 00-CONCEPT-34 | AI | Object | 00 | Information |  |  |
| 00-CONCEPT-35 | DNA | Object | 00 | Care |  |  |
| 00-CONCEPT-36 | HIV | Historical case | 00 | Care |  |  |
| 00-CONCEPT-37 | HPV | Historical case | 00 | Care |  |  |
| 00-CONCEPT-38 | Polio vaccine | Object | 00 | Care |  |  |
| 00-CONCEPT-39 | Personalized medicine | Object | 00 | Information |  |  |
| 00-CONCEPT-40 | Precision medicine | Object | 00 | Care |  |  |
| 00-CONCEPT-41 | Genomics and Computational Biology | Organization | 00 | Information |  |  |
| 00-CONCEPT-42 | Clinical Pathology and Laboratory Medicine | Organization | 00 | Information |  |  |
| 00-CONCEPT-43 | Systems Medicine | Organization | 00 | Information |  |  |
| 00-CONCEPT-44 | DEI | Policy | 00 | Information |  |  |
| 00-CONCEPT-45 | ICU | Place | 00 | Care |  |  |
| 00-CONCEPT-46 | Bollywood | Symbol | 00 | Care |  |  |
| 00-CONCEPT-47 | Colonialism | Symbol | 00 | Care |  |  |
| 00-CONCEPT-48 | God | Symbol | 00 | Information |  |  |
| 00-CONCEPT-49 | Latina | Symbol | 00 | Information |  |  |
| 00-CONCEPT-50 | Mammography | Object | 00 | Discovery |  |  |
| 00-CONCEPT-51 | European ancestry | Symbol | 00 | Information |  |  |
| 00-METAPHOR-01 | Unpaid labor ledger | Metaphor | 00 | Information |  |  |
| 00-OBJ-09 | Imaging uploads | Object | 00 | Discovery |  |  |
| 00-ORG-16 | National Institutes of Health (NIH) | Organization | 00 | Information |  |  |
| 00-ORG-17 | Harvard University | Organization | 00 | Discovery |  |  |
| 00-ORG-18 | Office of the First Lady of Florida | Organization | 00 | Discovery |  |  |
| 00-PHRASE-16 | Devanand | Phrase | 00 | Care |  |  |
| 00-PLACE-23 | Stanford pathology residency | Place | 00 | Information |  |  |
| 00-PLACE-24 | Spain | Place | 00 | Information |  |  |
| 00-PLACE-25 | Latin America | Place | 00 | Information |  |  |
| 00-RIT-08 | Faith coexistence | Ritual | 00 | Information |  |  |
| 01-PHRASE-01 | Where Story Becomes Fate | Phrase | 01 | Care |  |  |
| 01-PLACE-01 | St. James, Trinidad (Agra Street) | Place | 01 | Care |  |  |
| 01-PLACE-02 | Agra, India | Place | 01 | Care |  |  |
| 01-PLACE-03 | Taj Mahal | Place | 01 | Care |  |  |
| 01-PLACE-04 | Spain | Place | 01 | Information |  |  |
| 01-PLACE-05 | Caribbean | Place | 01 | Care |  |  |
| 01-PLACE-06 | Coolie Town | Place | 01 | Discovery |  |  |
| 01-RIT-01 | Carnival and Ash Wednesday | Ritual | 01 | Information |  |  |
| 01-PHRASE-02 | Big Apple of Trinidad | Phrase | 01 | Care |  |  |
| 01-CHAR-01 | Neighborhood friend (unnamed) | Character | 01 | Care | Living |  |
| 01-CHAR-02 | Aunty Janice | Character | 01 | Care | Deceased |  |
| 01-PHRASE-03 | Queen of the Band | Phrase | 01 | Care |  |  |
| 01-RIT-02 | Sabbath worship and Lord’s Prayer | Ritual | 01 | Information |  |  |
| 01-OBJ-01 | VCR and cassette-era media | Object | 01 | Care |  |  |
| 01-OBJ-02 | TRS-80 (and early home computing) | Object | 01 | Information |  |  |
| 01-OBJ-03 | Bottle rockets and rum factory caps | Object | 01 | Care |  |  |
| 01-OBJ-04 | IBM 286 clone | Object | 01 | Information |  |  |
| 01-OBJ-05 | Nintendo console | Object | 01 | Information |  |  |
| 01-OBJ-06 | Nintendo games (Mario, Zelda) | Object | 01 | Care |  |  |
| 01-OBJ-07 | James Bond films | Object | 01 | Care |  |  |
| 01-OBJ-08 | Bruce Lee films | Object | 01 | Care |  |  |
| 01-OBJ-09 | Microsoft Flight Simulator | Object | 01 | Care |  |  |
| 01-OBJ-10 | Hercules monochrome graphics | Object | 01 | Information |  |  |
| 01-PLACE-07 | Maracas Beach | Place | 01 | Care |  |  |
| 01-PLACE-08 | Canada | Place | 01 | Care |  |  |
| 01-PLACE-09 | United States | Place | 01 | Care |  |  |
| 01-CONCEPT-01 | Legibility vs personhood | Concept | 01 | Information |  |  |
| 01-PHRASE-04 | Why We Have Codes at All | Phrase | 01 | Information |  |  |
| 01-ECON-01 | Insurance engine | Economic | 01 | Information |  |  |
| 01-CONCEPT-02 | Billable Code as economic unit | Phrase | 01 | Information |  |  |
| 01-PHRASE-05 | The First Code | Phrase | 01 | Information |  |  |
| 01-CONCEPT-03 | Date of birth as primary key | Concept | 01 | Information |  |  |
| 01-CHAR-03 | Mama (maternal grandmother) | Character | 01 | Information | Deceased |  |
| 01-CHAR-04 | Father - Leonard Kempthorne | Character | 01 | Information | Deceased |  |
| 01-PHRASE-06 | Mama’s Code Was a Story | Phrase | 01 | Information |  |  |
| 01-HIST-01 | Red House fire of 1903 | Historical case | 01 | Information |  |  |
| 01-PHRASE-07 | My Mother’s Name Was a Code Too | Phrase | 01 | Information |  |  |
| 01-CHAR-05 | Mother - Pearl Surajee | Character | 01 | Information | Living |  |
| 01-SYMBOL-01 | Hadley surname | Symbol | 01 | Information |  |  |
| 01-PHRASE-08 | Penn and the Operating Room | Phrase | 01 | Care |  |  |
| 01-PLACE-10 | Penn operating room | Place | 01 | Information |  |  |
| 01-CONCEPT-04 | Surgery | Object | 01 | Care |  |  |
| 01-CONCEPT-05 | ICD | Object | 01 | Information |  |  |
| 01-CONCEPT-06 | CPT | Object | 01 | Information |  |  |
| 01-PHRASE-09 | Stanford, the Basement, and the Constitution of Medicine | Phrase | 01 | Information |  |  |
| 01-PLACE-11 | Stanford pathology basements | Place | 01 | Information |  |  |
| 01-CONCEPT-07 | Clinical Pathology and Laboratory Medicine | Organization | 01 | Information |  |  |
| 01-CONCEPT-08 | LOINC | Object | 01 | Information |  |  |
| 01-CONCEPT-09 | RxNorm | Object | 01 | Information |  |  |
| 01-CONCEPT-10 | SNOMED CT | Object | 01 | Information |  |  |
| 01-CONCEPT-11 | UMLS (Unified Medical Language System) | Object | 01 | Information |  |  |
| 01-CHAR-06 | Mark Musen | Character | 01 | Information | Public Figure |  |
| 01-PHRASE-10 | When Story Became Fate | Phrase | 01 | Care |  |  |
| 01-SYMBOL-02 | Pacemaker serial number missing at bedside | Symbol | 01 | Information |  |  |
| 01-PHRASE-11 | The Insurance Engine | Phrase | 01 | Care |  |  |
| 01-CONCEPT-12 | Coverage | Concept | 01 | Information |  |  |
| 01-CONCEPT-13 | Access | Concept | 01 | Information |  |  |
| 01-CONCEPT-14 | Precision Medicine Economy | Concept | 01 | Care |  |  |
| 01-PHRASE-12 | Europe, Curation, and the Long Memory of Power | Phrase | 01 | Care |  |  |
| 01-PLACE-12 | Europe | Place | 01 | Care |  |  |
| 01-PLACE-13 | Rome | Place | 01 | Care |  |  |
| 01-PLACE-14 | Vatican | Place | 01 | Care |  |  |
| 01-PLACE-15 | Sistine Chapel | Place | 01 | Care |  |  |
| 01-CHAR-07 | Michelangelo | Character | 01 | Care | Public Figure |  |
| 01-CHAR-08 | Leonardo da Vinci | Character | 01 | Care | Public Figure |  |
| 01-CHAR-09 | Raphael | Character | 01 | Care | Public Figure |  |
| 01-CONCEPT-15 | Western civilization | Symbol | 01 | Care |  |  |
| 01-CONCEPT-16 | Renaissance | Symbol | 01 | Information |  |  |
| 01-PLACE-16 | India | Place | 01 | Care |  |  |
| 01-PLACE-17 | Arab world | Place | 01 | Information |  |  |
| 01-PLACE-18 | Africa | Place | 01 | Care |  |  |
| 01-CHAR-10 | Wife (Spanish Moroccan) | Character | 01 | Information | Living |  |
| 01-PHRASE-13 | Zero, Algebra, and the Systems Europe Inherited | Phrase | 01 | Care |  |  |
| 01-CONCEPT-17 | Zero | Object | 01 | Care |  |  |
| 01-CONCEPT-18 | Binary | Object | 01 | Care |  |  |
| 01-CONCEPT-19 | Algebra | Object | 01 | Care |  |  |
| 01-CONCEPT-20 | Algorithm | Object | 01 | Information |  |  |
| 01-CHAR-11 | al-Khwarizmi | Character | 01 | Information | Public Figure |  |
| 01-PHRASE-14 | The Moors, and the Proof of a Larger Lineage | Phrase | 01 | Care |  |  |
| 01-CONCEPT-21 | Moorish lineage | Symbol | 01 | Information |  |  |
| 01-CONCEPT-22 | Islam | Symbol | 01 | Care |  |  |
| 01-PLACE-19 | Al-Andalus (Islamic Spain) | Place | 01 | Information |  |  |
| 01-PLACE-20 | Alhambra | Place | 01 | Information |  |  |
| 01-PLACE-21 | Morocco | Place | 01 | Care |  |  |
| 01-PHRASE-15 | Names as Prophecy | Phrase | 01 | Care |  |  |
| 01-CONCEPT-23 | Prophets of Islam | Symbol | 01 | Care |  |  |
| 01-CONCEPT-24 | Data science | Object | 01 | Information |  |  |
| 01-CONCEPT-25 | Prediction and pattern recognition | Object | 01 | Information |  |  |
| 01-PHRASE-16 | Code Is Not Software — It Is Power | Phrase | 01 | Information |  |  |
| 01-PHRASE-17 | Digital Māyā | Phrase | 01 | Information |  |  |
| 01-CONCEPT-26 | Digital Māyā | Concept | 01 | Information |  |  |
| 01-CONCEPT-27 | Māyā (Hindu concept) | Concept | 01 | Information |  |  |
| 01-PHRASE-18 | The Counterattack | Phrase | 01 | Care |  |  |
| 01-CHAR-12 | Aunty Betty | Character | 01 | Care | Deceased |  |
| 01-CONCEPT-28 | Seventh-day Adventism | Symbol | 01 | Information |  |  |
| 01-CONCEPT-29 | Hinduism | Symbol | 01 | Care |  |  |
| 02-PHRASE-01 | Where the Money Goes | Phrase | 02 | Care |  |  |
| 02-PHRASE-02 | Software is eating the world | Phrase | 02 | Information |  |  |
| 02-CHAR-01 | Marc Andreessen | Character | 02 | Information | Public Figure |  |
| 02-CONCEPT-01 | Precision-medicine economy | Object | 02 | Information |  |  |
| 02-CONCEPT-02 | Dividends follow volume and legibility | Phrase | 02 | Information |  |  |
| 02-PHRASE-03 | Dividend One: Training the Eye to See Value | Phrase | 02 | Information |  |  |
| 02-PLACE-01 | Penn MD/PhD Genomics and Computational Biology | Place | 02 | Information |  |  |
| 02-ORG-01 | Penn Medicine | Organization | 02 | Information |  |  |
| 02-ORG-02 | Perelman School of Medicine | Organization | 02 | Information |  |  |
| 02-PLACE-02 | Philadelphia | Place | 02 | Care |  |  |
| 02-HIST-01 | Human Genome Project | Historical case | 02 | Information |  |  |
| 02-RIT-01 | Systems engineering study groups | Ritual | 02 | Information |  |  |
| 02-CHAR-02 | Engineering cohort (Chinese students) | Character | 02 | Information | Abstract |  |
| 02-CHAR-03 | Engineering cohort peer (unnamed) | Character | 02 | Discovery | Living |  |
| 02-CONCEPT-03 | Evolutionary conservation | Object | 02 | Information |  |  |
| 02-PHRASE-04 | A Quick Inventory of the Jargon You’re About to See | Phrase | 02 | Care |  |  |
| 02-CONCEPT-04 | Genome | Object | 02 | Discovery |  |  |
| 02-CONCEPT-05 | Genomics | Object | 02 | Discovery |  |  |
| 02-CONCEPT-06 | Genotype | Object | 02 | Care |  |  |
| 02-CONCEPT-07 | Variant | Object | 02 | Care |  |  |
| 02-CONCEPT-08 | SNPs | Object | 02 | Information |  |  |
| 02-CONCEPT-09 | Cohort | Object | 02 | Discovery |  |  |
| 02-CONCEPT-10 | Statistical power | Object | 02 | Care |  |  |
| 02-CONCEPT-11 | Bias (data) | Object | 02 | Information |  |  |
| 02-CONCEPT-12 | DNA letter | Object | 02 | Care |  |  |
| 02-PHRASE-05 | Dividend Two: Volume | Phrase | 02 | Care |  |  |
| 02-EVID-01 | Presynaptic neural gene conservation study | Evidence | 02 | Information |  |  |
| 02-EVID-02 | Autism cohorts (AGRE, Autism Genome Project) | Evidence | 02 | Information |  |  |
| 02-ORG-03 | Autism Genetics Resource Exchange | Organization | 02 | Information |  |  |
| 02-ORG-04 | Autism Genome Project | Organization | 02 | Information |  |  |
| 02-EVID-03 | Pivot table ancestry check | Evidence | 02 | Information |  |  |
| 02-CHAR-04 | Junhyong Kim | Character | 02 | Information | Public Figure |  |
| 02-CHAR-05 | Motoo Kimura | Character | 02 | Information | Public Figure |  |
| 02-CHAR-06 | Maja Bucan | Character | 02 | Information | Public Figure |  |
| 02-CHAR-07 | Warren Ewens | Character | 02 | Care | Public Figure |  |
| 02-CHAR-08 | Charles Darwin | Character | 02 | Care | Public Figure |  |
| 02-RIT-02 | Australia vs West Indies Test cricket contrast | Ritual | 02 | Care |  |  |
| 02-CHAR-09 | Brian Lara | Character | 02 | Care | Public Figure |  |
| 02-CONCEPT-13 | Population genetics | Object | 02 | Discovery |  |  |
| 02-CONCEPT-14 | Neutral theory | Object | 02 | Care |  |  |
| 02-CONCEPT-15 | Excel | Object | 02 | Information |  |  |
| 02-CONCEPT-16 | Statistical noise | Object | 02 | Discovery |  |  |
| 02-CONCEPT-17 | Statistical signal | Object | 02 | Care |  |  |
| 02-OBJ-01 | Recruitment letters | Object | 02 | Information |  |  |
| 02-PHRASE-06 | Dividend Three: The Basement Tree | Phrase | 02 | Care |  |  |
| 02-EVID-04 | Ancestry caller and phylogenetic tree | Evidence | 02 | Information |  |  |
| 02-CONCEPT-18 | African ancestry | Symbol | 02 | Information |  |  |
| 02-CONCEPT-19 | European ancestry | Symbol | 02 | Information |  |  |
| 02-PHRASE-07 | Dividend Four: The Cathedral at CHOP | Phrase | 02 | Care |  |  |
| 02-ORG-05 | Children’s Hospital of Philadelphia (CHOP) | Organization | 02 | Information |  |  |
| 02-PLACE-03 | CHOP Center for Applied Genomics (CAG) | Place | 02 | Information |  |  |
| 02-PLACE-04 | West Philadelphia (CHOP across the street) | Place | 02 | Information |  |  |
| 02-CHAR-10 | Hakon Hakonarson | Character | 02 | Discovery | Public Figure |  |
| 02-ORG-06 | NeuroFix Therapeutics | Organization | 02 | Information |  |  |
| 02-CONCEPT-20 | Genotyping | Object | 02 | Information |  |  |
| 02-CONCEPT-21 | Neuropsychiatry | Organization | 02 | Care |  |  |
| 02-CONCEPT-22 | Black | Symbol | 02 | Information |  |  |
| 02-CONCEPT-23 | White | Symbol | 02 | Information |  |  |
| 02-FIG-01 | Figure 2.1 - From Data to Dividends pipeline | Figure | 02 | Information |  |  |
| 02-PHRASE-08 | Dividend Five: Stanford and the Rule That Governs Everything | Phrase | 02 | Information |  |  |
| 02-PLACE-05 | Stanford pathology and informatics | Place | 02 | Information |  |  |
| 02-CONCEPT-24 | LOINC | Object | 02 | Information |  |  |
| 02-CONCEPT-25 | SNOMED CT | Object | 02 | Information |  |  |
| 02-CONCEPT-26 | ICD | Object | 02 | Information |  |  |
| 02-CONCEPT-27 | CPT | Object | 02 | Information |  |  |
| 02-CHAR-11 | Co-resident (unnamed) | Character | 02 | Care | Living |  |
| 02-ORG-07 | California Institute of Technology | Organization | 02 | Information |  |  |
| 02-CHAR-12 | Ben Pinsky | Character | 02 | Care | Public Figure |  |
| 02-CONCEPT-28 | Dengue | Historical case | 02 | Care |  |  |
| 02-CONCEPT-29 | Neglected tropical diseases | Policy | 02 | Care |  |  |
| 02-ORG-08 | World Health Organization | Organization | 02 | Care |  |  |
| 02-PLACE-06 | Trinidad | Place | 02 | Care |  |  |
| 02-PLACE-07 | Silicon Valley | Place | 02 | Information |  |  |
| 02-CONCEPT-30 | Bitcoin | Object | 02 | Care |  |  |
| 02-CONCEPT-31 | Deep learning | Object | 02 | Information |  |  |
| 02-CONCEPT-32 | GPUs | Object | 02 | Information |  |  |
| 02-CHAR-13 | Atul Butte | Character | 02 | Information | Public Figure |  |
| 02-PHRASE-09 | Dividend Six: UCSF and the Liquidity of Open Data | Phrase | 02 | Information |  |  |
| 02-PLACE-08 | UCSF and public data platforms (GEO, STARGEO, CrADLe, BD2K) | Place | 02 | Information |  |  |
| 02-CONCEPT-33 | Liquidity as dividend | Phrase | 02 | Information |  |  |
| 02-CONCEPT-34 | Open data | Object | 02 | Information |  |  |
| 02-CONCEPT-35 | AI models | Object | 02 | Information |  |  |
| 02-PHRASE-10 | Dividend Seven: UCF, COVID, and the Price of Representation | Phrase | 02 | Information |  |  |
| 02-ORG-09 | University of Central Florida | Organization | 02 | Information |  |  |
| 02-PLACE-09 | UCF decentralized imaging trial (NCT05384912) | Place | 02 | Information |  |  |
| 02-HIST-02 | COVID-19 | Historical case | 02 | Discovery |  |  |
| 02-ECON-01 | Recruitment cost gap | Economic | 02 | Information |  |  |
| 02-PHRASE-11 | Dividend Eight: The Insurance Engine | Phrase | 02 | Care |  |  |
| 02-POLICY-01 | Medicare Advantage | Policy | 02 | Care |  |  |
| 02-EVID-05 | Medicare Advantage coding allegations (OIG/Reuters) | Evidence | 02 | Information |  |  |
| 02-ORG-10 | Office of Inspector General | Organization | 02 | Information |  |  |
| 02-ORG-11 | Reuters | Organization | 02 | Information |  |  |
| 02-ORG-12 | UnitedHealth | Organization | 02 | Care |  |  |
| 02-CONCEPT-36 | System billing for invisibility | Concept | 02 | Information |  |  |
| 02-PHRASE-12 | The Dividend Summary: How the Trillions Assemble | Phrase | 02 | Care |  |  |
| 02-PHRASE-13 | Exit Handoff: Why Chapter Three Must Be Deaths | Phrase | 02 | Care |  |  |
| 02-CONCEPT-37 | EHR integration | Object | 02 | Information |  |  |
| 02-PLACE-10 | United States | Place | 02 | Care |  |  |
| 03-PHRASE-01 | Deaths: Where the Burden Falls | Phrase | 03 | Care |  |  |
| 03-PHRASE-02 | The billable code is the fundamental economic unit of American healthcare. | Phrase | 03 | Information |  |  |
| 03-PHRASE-03 | Codes are not neutral. | Phrase | 03 | Information |  |  |
| 03-CONCEPT-01 | Deaths follow representation | Phrase | 03 | Information |  |  |
| 03-CONCEPT-02 | Mortality as ledger | Concept | 03 | Care |  |  |
| 03-CONCEPT-03 | Mortality gap | Concept | 03 | Care |  |  |
| 03-CONCEPT-04 | Extraction | Concept | 03 | Care |  |  |
| 03-EVID-01 | Breast cancer mortality gap (DeSantis et al. 2022) | Evidence | 03 | Care |  |  |
| 03-EVID-02 | Breast cancer disparity review (Daly & Olopade 2022) | Evidence | 03 | Care |  |  |
| 03-CONCEPT-05 | Breast cancer | Historical case | 03 | Care |  |  |
| 03-CONCEPT-06 | Precision medicine | Object | 03 | Care |  |  |
| 03-CONCEPT-07 | Billable Code | Concept | 03 | Information |  |  |
| 03-PHRASE-04 | The UCSF Revelation — Diseases Don’t Come One at a Time | Phrase | 03 | Care |  |  |
| 03-PLACE-01 | UCSF | Place | 03 | Discovery |  |  |
| 03-CHAR-01 | Esteban Gonzalez Burchard | Character | 03 | Information | Public Figure |  |
| 03-CONCEPT-08 | Comorbidity | Concept | 03 | Information |  |  |
| 03-CONCEPT-09 | Asthma | Historical case | 03 | Care |  |  |
| 03-CONCEPT-10 | Hypertension | Historical case | 03 | Information |  |  |
| 03-CONCEPT-11 | Diabetes | Historical case | 03 | Information |  |  |
| 03-CONCEPT-12 | Preterm birth | Historical case | 03 | Care |  |  |
| 03-CONCEPT-13 | Chronic kidney disease (CKD) | Historical case | 03 | Care |  |  |
| 03-CONCEPT-14 | Puerto Rican | Symbol | 03 | Care |  |  |
| 03-CONCEPT-15 | African ancestry | Symbol | 03 | Care |  |  |
| 03-CONCEPT-16 | APOL1 | Object | 03 | Information |  |  |
| 03-EVID-03 | Asthma disparities (Akinbami et al. 2012; Burchard et al. 2014) | Evidence | 03 | Care |  |  |
| 03-EVID-04 | Puerto Rican asthma prevalence (Nishimura & Burchard 2015) | Evidence | 03 | Care |  |  |
| 03-EVID-05 | African ancestry asthma severity (Kumar et al. 2015) | Evidence | 03 | Information |  |  |
| 03-EVID-06 | Genomics diversity failure (Popejoy & Fullerton 2016) | Evidence | 03 | Information |  |  |
| 03-PHRASE-05 | The Multiplicative Nature of Inequity | Phrase | 03 | Care |  |  |
| 03-CONCEPT-17 | Multiplicative risk | Concept | 03 | Information |  |  |
| 03-CONCEPT-18 | Polygenic scores | Object | 03 | Information |  |  |
| 03-CONCEPT-19 | Machine-learning prognostics | Object | 03 | Information |  |  |
| 03-CONCEPT-20 | EHR-based algorithms | Object | 03 | Information |  |  |
| 03-CONCEPT-21 | Social determinants of health | Concept | 03 | Care |  |  |
| 03-CONCEPT-22 | Redlining | Concept | 03 | Care |  |  |
| 03-CONCEPT-23 | HbA1c | Object | 03 | Information |  |  |
| 03-CONCEPT-24 | Electronic health records (EHR) | Object | 03 | Information |  |  |
| 03-EVID-07 | Hypertension bias (Hoffmann et al. 2018) | Evidence | 03 | Information |  |  |
| 03-EVID-08 | Diabetes disparities (Osei et al. 2021) | Evidence | 03 | Information |  |  |
| 03-EVID-09 | Preterm birth inequities (Taylor et al. 2020) | Evidence | 03 | Care |  |  |
| 03-EVID-10 | APOL1 variants and kidney disease (Genovese et al. 2010) | Evidence | 03 | Information |  |  |
| 03-PHRASE-06 | The Geography of Absence | Phrase | 03 | Care |  |  |
| 03-PLACE-02 | Florida | Place | 03 | Care |  |  |
| 03-PLACE-03 | Central Florida | Place | 03 | Care |  |  |
| 03-CONCEPT-25 | Data completeness | Concept | 03 | Information |  |  |
| 03-CONCEPT-26 | Genomic recurrence scoring | Object | 03 | Information |  |  |
| 03-PHRASE-07 | Institutional mirror | Phrase | 03 | Information |  |  |
| 03-EVID-11 | Mammography follow-up delays (Fedewa et al. 2020) | Evidence | 03 | Care |  |  |
| 03-PHRASE-08 | Clinical Trials — Where Future Deaths Are Decided | Phrase | 03 | Discovery |  |  |
| 03-CONCEPT-27 | Underrepresentation in trials | Concept | 03 | Information |  |  |
| 03-EVID-12 | Clinical trial underrepresentation (Loree et al. 2021) | Evidence | 03 | Information |  |  |
| 03-CONCEPT-28 | GWAS | Object | 03 | Information |  |  |
| 03-CONCEPT-29 | European ancestry | Symbol | 03 | Discovery |  |  |
| 03-CONCEPT-30 | Latino | Symbol | 03 | Information |  |  |
| 03-CONCEPT-31 | Hispanic | Symbol | 03 | Information |  |  |
| 03-CONCEPT-32 | Indigenous | Symbol | 03 | Information |  |  |
| 03-CONCEPT-33 | Asian | Symbol | 03 | Information |  |  |
| 03-PHRASE-09 | COVID-19 — The Exposing Event | Phrase | 03 | Care |  |  |
| 03-CONCEPT-34 | COVID-19 | Historical case | 03 | Care |  |  |
| 03-CONCEPT-35 | Metaverse of medical data | Object | 03 | Information |  |  |
| 03-EVID-13 | COVID-19 mortality inequities (Hill et al. 2021) | Evidence | 03 | Care |  |  |
| 03-EVID-14 | Decentralized imaging trial (NCT05384912) | Evidence | 03 | Discovery |  |  |
| 03-ORG-01 | University of Central Florida | Organization | 03 | Discovery |  |  |
| 03-ORG-02 | Facebook | Organization | 03 | Information |  |  |
| 03-ORG-03 | ClinicalTrials.gov | Organization | 03 | Information |  |  |
| 03-CONCEPT-36 | Recruitment cost differential | Concept | 03 | Care |  |  |
| 03-CONCEPT-37 | Black | Symbol | 03 | Information |  |  |
| 03-CONCEPT-38 | White | Symbol | 03 | Care |  |  |
| 03-CONCEPT-39 | Native | Symbol | 03 | Care |  |  |
| 03-PHRASE-10 | The Arithmetic of Death | Phrase | 03 | Care |  |  |
| 03-PHRASE-11 | Mortality is the only KPI that matters. | Phrase | 03 | Care |  |  |
| 03-CONCEPT-40 | Underrepresented ancestry | Symbol | 03 | Information |  |  |
| 03-CONCEPT-41 | AI models | Object | 03 | Information |  |  |
| 03-PLACE-04 | West Philadelphia | Place | 03 | Care |  |  |
| 03-PLACE-05 | San Francisco’s Mission District | Place | 03 | Care |  |  |
| 03-PLACE-06 | United States | Place | 03 | Care |  |  |
| 03-CHAR-02 | Daughters (author’s) | Character | 03 | Care | Living |  |
| 03-PHRASE-12 | Dividends rise. Deaths fall. | Phrase | 03 | Care |  |  |
---

## Conflict Resolution

When discrepancies appear:
1. This file defines canonical IDs and asset truth.
2. Chapter ledgers must conform to this file.
3. Prose must conform to chapter ledgers.

Fix inputs upstream; never patch prose to bypass the ledger.

---

## Workflow Integration

- **Ledgering an episode** registers or updates an entry here.
- **Chapter build** may only reference assets listed here.
- **Structural audits (Pass 1)** must verify:
  - no duplicate assets
  - no deprecated IDs in use
  - correct engine mappings

---

## Invariants

- This file is append-only except for deprecations.
- IDs are never reused.
- Home chapters do not change once assigned.
- If this file blocks progress, fix the input — do not bypass the ledger.

---

End of global narrative asset ledger.
