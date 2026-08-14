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
6. Read `works/balipeedam-nokki/sections/README.md`.
7. Before English work, read `works/balipeedam-nokki/translations/en/TRANSLATION_PLAN.md` completely.
8. Continue existing work; do not create duplicate structures.
9. Treat the supplied scan / audited `pages/` records as controlling textual authority.
10. Do **not** upload/commit the source PDF to this repository.

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

## English translation plan — COMPLETE

Committed:

`works/balipeedam-nokki/translations/en/TRANSLATION_PLAN.md`

Working English title:

**Towards the Sacrificial Altar**

The plan follows the same source-first / bilingual-fidelity principles used elsewhere in the Kalaignar archive while adapting them to this novel's three-layer structure.

### Source authority for English

1. audited `pages/` records — final textual authority;
2. assembled `sections/` — continuity/readability;
3. metadata/audit — source and structural context;
4. external historical references only for clearly marked editorial notes, never to overwrite source wording.

### Translation batches

1. **Batch 1 — pilot:** scans 4–7 / opening frame.
2. **Batch 2:** scans 8–13 / internal title card, Nayak court, battle and Vijayaraghava's fall.
3. **Batch 3:** scans 14–20 / Alagiri–Vengannu sequence and Sengamaladasan discovery.
4. **Batch 4:** scans 21–26 / Bijapur–Venkoji intervention, restoration and ministership conflict.
5. **Batch 5:** scans 27–30 through the internal film's `வணக்கம்` end-card.
6. **Batch 6:** scan 30 beginning `படம் முடிந்துவிட்டது...` through scan 33 / return and conclusion.

The final English reading structure remains three section files mirroring the Tamil assembly. Batches are translation/review control units only.

### Translation policy locked by plan

- preserve political and social polemic without softening or intensifying;
- retain the central `பலிபீடம்` metaphor consistently as **sacrificial altar**;
- keep `ராயசம் வெங்கண்ணு` internal and use **Vengannu**, not a silently normalized Venganna;
- preserve cinematic vocabulary, title-card structure, screen movement and bracketed action directions;
- use stable English names/places while keeping the canonical Tamil untouched;
- treat source oddities cautiously and note exact Tamil where meaning remains unusually source-bound;
- preserve rhetorical repetition and source agency/responsibility;
- retain page provenance through HTML comments;
- use review statuses: `draft-translated`, `source-checked`, `reviewed`, `verified`;
- require final `TRANSLATION_REVIEW.md` before release.

### Planned English directory

```text
works/balipeedam-nokki/translations/en/
  TRANSLATION_PLAN.md
  README.md
  PROGRESS.md
  GLOSSARY.md
  sections/
    01-opening-frame.md
    02-rayasam-vengannu-sequence.md
    03-return-and-conclusion.md
  TRANSLATION_REVIEW.md
  RELEASE_REPORT.md
```

Only `TRANSLATION_PLAN.md` exists at the end of the current activity. Do not create final review/release files prematurely.

## Current gate

**Tamil source layer: PASSED**  
**Assembled Tamil reading layer: PASSED**  
**English translation plan: COMPLETE**  
**English prose translation: NOT STARTED**

## Next exact activity

Begin **Batch 1 — pilot English translation of scans 4–7 / `sections/01-opening-frame.md`**.

During that activity:

1. create `translations/en/README.md` and `PROGRESS.md`;
2. create the initial `translations/en/GLOSSARY.md`;
3. create `translations/en/sections/01-opening-frame.md` with `translation_status: draft-translated`;
4. translate every substantive Tamil unit — no summarising;
5. retain unobtrusive source-scan comments and already-audited page joins;
6. source-check the complete pilot against canonical `pages/0004`–`0007`;
7. review the pilot for the central `பலிபீடம்` metaphor, `ஆரியம்`, self-respect/rationalist vocabulary, rhetorical repetition, historical names and scan-7 cinematic transition;
8. update the glossary with only decisions actually established by the pilot;
9. advance the pilot to `source-checked` / `reviewed` only when justified;
10. **do not begin Batch 2 until the pilot style decisions are locked and the repository status/handover is updated.**

## Release gate reminder

No English layer is final until all batches have completed bilingual/source review and a final `TRANSLATION_REVIEW.md` confirms:

- no omissions or additions;
- no altered agency/responsibility;
- no softened/intensified political rhetoric;
- consistent names and recurring terminology;
- preserved cinematic form;
- intact scan-30 structural transition;
- one-work identity preserved throughout.

The audited Tamil remains authoritative after English release.
