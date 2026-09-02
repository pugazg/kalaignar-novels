# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Current work: `works/pudhaiyal/`

## Current authority rule

The scan remains the authority for page identity, headings, punctuation, paragraph/section structure, long dashes, speaker-label spacing, physical line/page breaks, chapter/scene transitions and other structural findings.

### Pudhaiyal lexical-preservation override — effective from scan 280 onward

By explicit user instruction, the supplied Gemini transcription is the controlling baseline for **WORDS / lexical text** from scan 280 onward.

- keep supplied words, spelling, suffixes, lexical forms, wording and supplied lexical spacing exactly;
- do **not** replace supplied lexical text because the scan appears different;
- use native scan inspection only for **headings, punctuation, quote marks, long dashes, speaker-label spacing, paragraph breaks, physical line/page breaks, chapter/scene boundaries, separators/rules and other structural findings**;
- preserve/record physical word splits without using them to source-correct lexical wording;
- if the supplied baseline omits a word/span, flag the gap rather than silently supplying lexical text from the scan.

For active Part 007, uploaded `p7.md` is the complete controlling lexical baseline.

Source/split PDFs and uploaded baseline files must never be committed.

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
- Part 006 — scans 246–294 — **part-complete**

Part-005 source-damage qualification remains attached to scans **215–219 and 223–224**. Their canonical status is not upgraded by downstream assembly/translation.

## Active derivative — Part 007

Source: `TVA_BOK_0064097_புதையல்_part_007_pages_295-343.pdf`

- physical pages: **49**
- source scans: **295–343**
- visible printed pages: **291–339**
- derivative size: **57,055,891 bytes**
- derivative SHA-256: `9ead2089eb238273f7b0fd0dbe2f929095730fbf3fc218719e66fe0d472bb15c`
- lexical baseline: uploaded `p7.md`
- `p7.md` size: **160,271 bytes**
- `p7.md` SHA-256: `a804b914b88050ca8d31142cb00d7491c94e89ff1fb7e564fdd348bdf14b1c59`
- source intake: `works/pudhaiyal/notes/part-007-source-intake.md`
- page map: `works/pudhaiyal/indexes/part-007-page-map.md`
- canonical records: **3 / 49 — scans 295–297**
- verified / structurally completed: **3 / 49**
- needs-review: **0**
- not-started: **46 — scans 298–343**
- Part-007 state: **`canonical-in-progress`**
- Tamil audit / assembled Tamil / English / bilingual review: **not yet eligible**

### Critical Part-006 → Part-007 continuation

The old open boundary is now resolved from actual source evidence.

Scan **294 / printed 290** ends inside the Sub-Inspector's dialogue at:

`‘லாக்`

Part-007 scan **295 / printed 291** begins:

`அப்’பில் தானிருக்கிறார்கள். இன்னும் ‘சார்ஜ் ஷீட்’டே போடவில்லை!”`

Therefore the verified cross-part reading is:

**`‘லாக் அப்’பில் தானிருக்கிறார்கள்...`**

No sentence, paragraph, scene or chapter boundary is created by the Part-006→007 split.

### Verified Part-007 structure through scan 297

- scan 295 / printed 291 — chapter 33 continues; page ends with source-printed `* * * *` internal transition;
- scan 296 / printed 292 — chapter 33 continues after the internal transition;
- scan 297 / printed 293 — chapter 33 closes; source horizontal rule + heading `34`; chapter 34 begins on the same physical page;
- scan 297 ends mid-sentence at `அவனை அனுதாபத்தோடு`;
- exact next native page is scan 298 / printed 294, whose lexical continuation begins `தொட்டுத் தூக்கிடும் போதும்...` in the supplied `p7.md` but must still be structurally reconciled against the scan.

Part-007 endpoint spot-check: scan **343 / printed 339** ends mid-utterance at `அதிர்ஷ்`. `p7.md` ends its source transcription at the same fragment. **Do not treat Part 007 as the chapter or novel ending.** Source beyond scan 343 will still be required.

## Aggregate durable state

- canonical records: **297**
- verified / completed: **290**
- needs-review: **7 — Part 005 scans 215–219, 223–224**
- partial: **0**
- clean contiguous fully verified range: through scan **214 / printed page 212**
- later completed pages: through scan **297**, except the seven damaged Part-005 records
- Parts 001–006: **part-complete at split level**
- Part 007: **canonical workflow active through scan 297**
- assembled Tamil: part-reviewed continuously through scan **294**
- source-checked / bilingual-reviewed English: continuously through scan **294**
- source scans represented by currently received derivatives: through **343 / printed 339**
- whole-work Tamil / English / release gates: not yet eligible

## Exact next activity

Process **scan 298 / printed page 294**, chapter 34.

1. use uploaded `p7.md` as the lexical/textual authority;
2. use native Part-007 page 4 only for punctuation, quotes, paragraphing, line/page boundary and structural findings;
3. preserve the scan-297→298 open sentence continuation (`அவனை அனுதாபத்தோடு` → `தொட்டுத் தூக்கிடும் போதும்...`);
4. create/update the canonical page, fidelity record and Part-007 page map;
5. continue sequentially through scans 298–343 before running the Part-007 Tamil audit.

Do not begin assembled Tamil or English for Part 007 until its complete canonical/structural reconciliation and Tamil audit pass.