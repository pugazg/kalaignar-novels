# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Current work: `works/pudhaiyal/`

## Current authority rule

The scan remains the authority for page identity, headings, punctuation, paragraph/section structure, long dashes, speaker-label spacing, physical line/page breaks, chapter/scene transitions and other structural findings.

### Pudhaiyal lexical-preservation override — effective from scan 280 onward

By explicit user instruction, **Gemini's supplied transcription is the controlling baseline for WORDS from scan 280 onward**.

For scans **280 onward**:

- keep Gemini's words, spelling, suffixes, lexical forms, wording and supplied lexical spacing exactly;
- do **not** replace Gemini lexical text because the scan appears different;
- use native scan inspection only for **headings, punctuation, quote marks, long dashes, speaker-label spacing, paragraph breaks, physical line/page breaks, chapter/scene boundaries, separators/rules and other structural findings**;
- preserve/record physical word splits without using them to source-correct Gemini wording;
- if Gemini omits a word/span, flag the gap rather than silently supplying lexical text from the scan.

Source/split PDFs must never be committed.

## Source identity — புதையல்

- original filename: `TVA_BOK_0064097_புதையல்.pdf`
- author: கலைஞர் மு. கருணாநிதி, எம். எல். ஏ.
- publisher: அன்புப் பதிப்பகம், பொறையார் :: தஞ்சை மாவட்டம்
- edition: மூன்றாம் பதிப்பு — செப்டம்பர் 1961
- Tamil Digital Library bibliographic extent: 443 p.
- exact full-PDF scan count / full-source SHA-256: pending complete source access
- source/split PDFs committed: No

## Completed derivatives

- Part 001 — scans 1–49 — **part-complete**
- Part 002 — scans 50–98 — **part-complete**
- Part 003 — scans 99–147 — **part-complete**
- Part 004 — scans 148–196 — **part-complete**
- Part 005 — scans 197–245 — **part-complete with explicit source-damage qualification**

Assembled Tamil and controlled English remain split-level reviewed continuously through scan **245**, with Part-005 source-damage qualifications preserved.

## Active derivative — Part 006

Source: `TVA_BOK_0064097_புதையல்_part_006_pages_246-294.pdf`

- physical pages: **49**
- source scans: **246–294**
- visible printed pages: **242–290**
- derivative size: **57,056,182 bytes**
- derivative SHA-256: `34a5ea5eb91a71ca8674760257779eb4ed6bdc6640517f8830b9ee70aa34aec7`
- derivative map: `works/pudhaiyal/indexes/part-006-page-map.md`
- canonical records: **49 / 49**
- verified / structurally completed: **49 / 49**
- needs-review: **0**
- not-started: **0**
- latest fidelity record: `works/pudhaiyal/notes/visual-fidelity-scan-294.md`
- Tamil audit: **PASSED** — `works/pudhaiyal/notes/part-006-tamil-audit.md`
- assembled Tamil: **eligible — pending**
- English / bilingual review: **blocked until assembled Tamil split-level consistency check passes**
- Part-006 state: **`part-tamil-audit-passed`**

### Part-006 Tamil-audit result

The Part-006 audit passed all required source-layer checks:

- 49/49 page inventory and canonical coverage;
- page-map ↔ canonical agreement;
- Part 005→006 opening continuity;
- page-boundary joins and chapter transitions;
- scan-280-onward Gemini lexical preservation;
- native structural fidelity;
- no unresolved Gemini lexical omission;
- scan 294 treated as an open access-derivative endpoint.

Important continuity checkpoints include:

- 245→246: `இருக்கவே` / `இருக்கிறாள் பரிமளா, ...`;
- 282→283: `நின்றான்` / `சிறிது நேரம்.`;
- 284→285: open dialogue `முடியுமா` / `என்று யோசனை செய்கிறேன்`;
- 285→286: `பரி` / `மளாவையும்`;
- 287→288: `எப்படியா` / `வது`;
- 289→290: `பட்டுக்` / `கோட்டை`;
- 291→292: `காப்` / `பாத்துங்க!`;
- 292→293: `ஓடி` / `விட்டான்.`;
- 293→294: `படுகுழியொன்` / `றில்`.

Scan **288 / printed 284** carries the source horizontal rule and heading **33**, closing chapter 32 and beginning chapter 33.

Scan **294 / printed 290** ends physically at open `‘லாக்` inside the Sub-Inspector's dialogue. There is no closing punctuation, chapter close or work-ending marker. This is the Part-006 derivative boundary only; whole-work continuation requires a later source split beyond scan 294.

## Aggregate durable state

- canonical records: **294**
- verified / completed: **287**
- needs-review: **7 — Part 005 scans 215–219, 223–224**
- partial: **0**
- clean contiguous fully verified range: through scan **214 / printed page 212**
- later completed pages: through scan **294**, except the seven damaged Part-005 records
- Parts 001–005: **part-complete at split level**
- Part 006: **Tamil audit PASSED; assembled Tamil pending**
- assembled Tamil / English split-level review: through scan **245** only
- source scans represented by currently received derivatives: through **294**
- whole-work Tamil / English / release gates: not yet eligible

## Exact next activity

Build the **Part-006 assembled Tamil reading layer from audited canonical pages only**:

1. extend `works/pudhaiyal/sections/27-chapter-27.md` from scan 245 through the chapter-27 close on scan 247;
2. create / populate assembled chapter files **28 through 33** from scans 247–294;
3. preserve the scan-251 four-star internal transition, real chapter boundaries, reversible source-page comments and verified cross-page joins;
4. leave chapter 33 explicitly open at scan 294 / `‘லாக்`; do not invent a close or novel ending;
5. update `works/pudhaiyal/sections/README.md` after a split-level assembled consistency check.

Do not begin Part-006 English translation until the assembled Tamil layer passes that check.