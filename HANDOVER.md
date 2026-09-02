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
- canonical records: **23 / 49 — scans 295–317**
- verified / structurally completed: **20 / 49**
- needs-review: **3 — scans 304–305, 315**
- not-started: **26 — scans 318–343**
- Part-007 state: **`canonical-in-progress`**
- Tamil audit / assembled Tamil / English / bilingual review: **not yet eligible**

### Critical Part-006 → Part-007 continuation

Scan **294 / printed 290** ends inside the Sub-Inspector's dialogue at `‘லாக்`. Part-007 scan **295 / printed 291** begins `அப்’பில் தானிருக்கிறார்கள்...`.

Therefore the verified cross-part reading is **`‘லாக் அப்’பில் தானிருக்கிறார்கள்...`**. No sentence, paragraph, scene or chapter boundary is created by the Part-006→007 split.

### Verified Part-007 structure through scan 317

- scan 295 / printed 291 — chapter 33 continues; page ends with source-printed `* * * *` internal transition;
- scan 297 / printed 293 — chapter 33 closes; source horizontal rule + heading `34`; chapter 34 begins on the same physical page;
- scan 302→303 — physical `பெற்` + `றான்` establishes baseline word `பெற்றான்`;
- scans 304–305 — complete baseline omissions `நீ` and `என்ன` remain `needs-review`; no source insertion;
- scan 306 / printed 302 — chapter 34 closes with a source horizontal rule;
- scan 307 / printed 303 — source heading `35` begins chapter 35;
- scan 310 / printed 306 — source-printed four-star internal transition;
- scan 313→314 — `தன் படுக்கையைத்` continues as `திண்ணையிலே விரித்துக் கொண்டான்...`;
- scan 315 / printed 311 — native source visibly contains the complete quoted span `சரி...... வா! வா!......`, omitted by `p7.md`; it was not inserted and the page remains `needs-review`;
- scan 315→316 — physical `அவர்` + `கள்` establishes `அவர்கள்` for later assembly;
- scan 316→317 — `“அகப்பட்டுக் கொண்டோம்!”` continues as `என்ற ஏக்கத்தோடு...`;
- scan 317 / printed 313 — chapter 35 closes; source horizontal rule + heading **36**; chapter 36 begins and the page ends at `பரிமளா பங்களாவிலே`.

Latest fidelity record: `works/pudhaiyal/notes/visual-fidelity-scans-313-317.md`.

Part-007 endpoint spot-check: scan **343 / printed 339** ends mid-utterance at `அதிர்ஷ்`. `p7.md` ends its source transcription at the same fragment. **Do not treat Part 007 as the chapter or novel ending.** Source beyond scan 343 will still be required.

## Aggregate durable state

- canonical records: **317**
- verified / completed: **307**
- needs-review: **10 — Part 005 scans 215–219, 223–224; Part 007 scans 304–305, 315**
- partial: **0**
- clean contiguous fully verified range: through scan **214 / printed page 212**
- later completed pages: through scan **317**, except the ten `needs-review` records above
- Parts 001–006: **part-complete at split level**
- Part 007: **canonical workflow active through scan 317**
- assembled Tamil: part-reviewed continuously through scan **294**
- source-checked / bilingual-reviewed English: continuously through scan **294**
- source scans represented by currently received derivatives: through **343 / printed 339**
- whole-work Tamil / English / release gates: not yet eligible

## Exact next activity

Process **scan 318 / printed page 314**, chapter 36.

1. use uploaded `p7.md` as lexical/textual authority;
2. use native Part-007 page 24 only for punctuation, quotes, paragraphing, line/page boundary and structural findings;
3. verify the open scan-317 continuation `பரிமளா பங்களாவிலே` → `இருந்ததால் புலனாகிவிட்டது...`;
4. continue sequentially through scans 318–343;
5. flag any additional complete baseline lexical omission rather than silently filling it from the scan;
6. do not open/pass the Part-007 Tamil-audit gate until all scans 295–343 are represented and scans 304–305, 315 receive explicit user/baseline disposition.

Do not begin assembled Tamil or English for Part 007 until its complete canonical/structural reconciliation and Tamil audit pass.