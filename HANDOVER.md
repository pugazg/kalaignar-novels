# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- When resuming, verify current `main` before making changes.

## Permanent startup rule

Before any new work:

1. Read `NOVEL_PROCESSING_GUIDE.md` completely.
2. Read root `README.md`.
3. Read `works/balipeedam-nokki/README.md`.
4. Read `works/balipeedam-nokki/metadata/source.md`.
5. Read `works/balipeedam-nokki/indexes/page-map.md` and `audit.md`.
6. Read `works/balipeedam-nokki/sections/README.md` before translation work.
7. Continue existing work; do not create duplicate structures.
8. Treat the supplied scan / audited `pages/` records as controlling textual authority.
9. Do **not** upload/commit the source PDF to this repository.

## Current source

Work: **பலிபீடம் நோக்கி**  
Author: **மு. கருணாநிதி**

Source filename, external to repository:

`TVA_BOK_0065570_பலிபீடம்_நோக்கி.pdf`

- SHA-256: `c4700c9043da8eadbf25144e7127a66a9270326512c095d99e1113a4feb464fe`
- File size: 69,724,254 bytes
- Scan pages: 34
- Edition visible in scan: முதல் பதிப்பு, ஏப்ரல் 1947
- Publisher visible in scan: எரிமலைப் பதிப்பகம், துறையூர்
- PDF committed to repository: **No**

## Critical structural rule

**`பலிபீடம் நோக்கி` is one continuous work.**

Do not treat `ராயசம் வெங்கண்ணு — தஞ்சை சரித்திரக் கதை` as a separate work. It is an internal cinematic-historical sequence within the same work.

Source-supported flow:

1. scans 4–7 — opening ideological / polemical frame;
2. scan 7 — narrator introduces a film-like lesson;
3. scans 8–29 and the opening portion of scan 30 — internal `ராயசம் வெங்கண்ணு` film sequence;
4. scan 30 — the internal film reaches its `வணக்கம்` end-card, then narrator says `படம் முடிந்துவிட்டது...` and returns to the main frame;
5. scans 31–33 — concluding direct address;
6. scan 34 — blank/back matter.

Every body page uses:

```text
work: balipeedam-nokki
```

`ராயசம் வெங்கண்ணு` may appear only as an internal `section` / title-card identity.

## Canonical Tamil source-preservation state — COMPLETE

The entire 34-page scan has been transcribed, character-reviewed and consistency-audited.

- page records: **34 / 34**
- verified: **34 / 34**
- needs-review: **0**
- unresolved readings: **0**
- page/metadata consistency audit: **PASSED**
- Tamil source layer: **PASSED**
- source PDF in repository: **No**

Canonical layer:

`works/balipeedam-nokki/pages/`

Final audit:

`works/balipeedam-nokki/audit.md`

### Important resolved source readings

Do not normalize these later:

- scan 3 — `பேனுப் பிடிக்கும்`
- scan 10 — `மித்தானமத்தனுக்குக்`
- scan 13 — `முச்சுற்றுப்படுத்திருக்கும்`
- scan 21 — `மளமள வென்று`; `என்றுன் பேதை!`
- scan 23 — `களேபாரப்படுகிறது`
- scan 26 — `தர்ப்பாகூரர்`; `விபரீதத்தை ஏற்கத்`
- scan 27 — `ஒரு காரணம்!`

## Assembled Tamil reading layer — COMPLETE

Created and cross-checked:

- `works/balipeedam-nokki/sections/README.md`
- `works/balipeedam-nokki/sections/01-opening-frame.md`
- `works/balipeedam-nokki/sections/02-rayasam-vengannu-sequence.md`
- `works/balipeedam-nokki/sections/03-return-and-conclusion.md`

Assembly status: **PASSED**.

### Assembly boundaries

- `01-opening-frame.md` — scans 4–7.
- `02-rayasam-vengannu-sequence.md` — scans 8–29 plus scan 30 through the film's `வணக்கம்` end-card.
- `03-return-and-conclusion.md` — scan 30 beginning `படம் முடிந்துவிட்டது...` through scan 33.

Scan 30 is deliberately split inside the page because the source itself places both the internal film ending and the explicit return to the main argument on that scan. No source text is duplicated or omitted.

### Verified readable joins in assembled layer

The canonical page files remain unchanged. The reading layer joins only already-audited continuities, including:

- `அணுக்` + `களிலிருந்து` → `அணுக்களிலிருந்து`
- `பாது` + `காத்துக்கொள்` → `பாதுகாத்துக்கொள்`
- `அப்படித்` + `தத்தளிக்கிறான்...`
- `கைகூப்புவதை` + `யும்` → `கைகூப்புவதையும்`

HTML comments preserve source-page provenance around these joins.

## Current gate

**Tamil source layer: PASSED**  
**Assembled Tamil reading layer: PASSED**  
**Translation-ready: YES**  
**English translation: not started**

## Next exact activity

Create an **English translation plan** before translating any prose.

Recommended file:

`works/balipeedam-nokki/translations/en/TRANSLATION_PLAN.md`

The plan must define at minimum:

1. translation batch boundaries mapped to the three assembled Tamil sections and source scan ranges;
2. one-work structural rule, explicitly keeping `ராயசம் வெங்கண்ணு` internal;
3. source-authority hierarchy: audited `pages/` first, `sections/` for continuity;
4. treatment of historical names, titles and place names;
5. transliteration / anglicization policy and a consistency table;
6. treatment of caste, religion, Dravidian-movement rhetoric and polemical language without softening or intensifying;
7. handling of cinematic vocabulary (`ரிலீஸ்`, `டைரக்ஷன்`, `குளோசப்`, stage/action directions, etc.);
8. handling of source oddities and historical spellings without silently correcting the Tamil source;
9. dialogue, quotation and punctuation conventions in English;
10. source-page traceability for every translation batch;
11. review statuses and gates (`draft`, `reviewed`, `verified` or equivalent);
12. requirement for a final editorial consistency review before release.

Do **not** begin the English prose translation until the translation plan is committed and reviewed against the Tamil audit/assembly rules.
