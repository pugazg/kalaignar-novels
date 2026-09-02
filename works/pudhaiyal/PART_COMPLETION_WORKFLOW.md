# Split-PDF part-completion workflow — புதையல்

The split PDFs are **access derivatives of one source edition**, not separate bibliographic works. A split may reach `part-complete`, but whole-work Tamil/English/release gates remain blocked until the complete edition is processed.

## Per-split sequence

1. map represented source scans;
2. create/reconcile canonical `pages/` records;
3. perform native visual/structural fidelity review;
4. resolve or explicitly retain every `needs-review` item;
5. run a part-level Tamil audit;
6. update assembled Tamil from audited canonical pages only;
7. translate the audited material;
8. source-check English against canonical Tamil;
9. run part-level bilingual review;
10. synchronize status before moving to the next split.

A derivative boundary is provenance only. Do not invent word, sentence, paragraph, scene or chapter boundaries from it.

## Pudhaiyal lexical baseline rule — effective from scan 280 onward

By explicit user instruction, scan **280 onward** uses a hybrid authority model.

### WORDS

The user-supplied Gemini transcription controls lexical wording.

- retain supplied words, spelling, suffixes, vowel signs, sandhi, lexical forms and supplied lexical spacing;
- do not replace a supplied word merely because the scan appears to contain a different lexical form;
- if the supplied baseline omitted a word/span altogether, flag the omission instead of silently supplying lexical text from the scan.

For active Part 007, uploaded `p7.md` is the complete lexical baseline.

### STRUCTURE / PRESENTATION

The native scan controls headings/chapter numbers, paragraph boundaries, punctuation, quotation marks, long dashes, speaker-label spacing/layout, physical line/page breaks, separators and chapter/scene transitions.

When a lexical word is split physically across a source line or source page, keep the supplied lexical wording while preserving/recording the native physical split.

## Completed split checkpoints

- Part 001 — scans **1–49** — **`part-complete`**
- Part 002 — scans **50–98** — **`part-complete`**
- Part 003 — scans **99–147** — **`part-complete`**
- Part 004 — scans **148–196** — **`part-complete`**
- Part 005 — scans **197–245** — **`part-complete` with explicit source-damage qualification**
- Part 006 — scans **246–294** — **`part-complete`**

## Active split — Part 007

Source derivative: `TVA_BOK_0064097_புதையல்_part_007_pages_295-343.pdf`

- physical pages / mapped source scans: **49 / 49 — scans 295–343**
- visible printed pages: **291–339**
- derivative file size: **57,055,891 bytes**
- derivative SHA-256: `9ead2089eb238273f7b0fd0dbe2f929095730fbf3fc218719e66fe0d472bb15c`
- lexical baseline: uploaded `p7.md`, SHA-256 `a804b914b88050ca8d31142cb00d7491c94e89ff1fb7e564fdd348bdf14b1c59`
- source intake: [`notes/part-007-source-intake.md`](notes/part-007-source-intake.md)
- derivative map: [`indexes/part-007-page-map.md`](indexes/part-007-page-map.md)
- canonical records: **13 / 49 — scans 295–307**
- verified / structurally completed: **11 / 49**
- needs-review: **2 — scans 304–305**
- not-started: **36 — scans 308–343**
- state: **`canonical-in-progress`**
- Tamil audit / assembled Tamil / English / bilingual review: **not yet eligible**

### Verified continuity through scan 307

Part 006 ends at scan 294 with open `‘லாக்`. Part-007 scan 295 begins `அப்’பில்`, establishing **`‘லாக் அப்’பில்`** across the derivative boundary.

Verified structural progression:

- scan 295 — chapter 33 + four-star internal transition at foot;
- scan 296 — chapter 33 continues;
- scan 297 — chapter 33 closes / chapter 34 begins under a horizontal rule + heading `34`;
- scan 297→298 — `அவனை அனுதாபத்தோடு` → `தொட்டுத் தூக்கிடும் போதும்...`;
- scan 302→303 — physical `பெற்` + `றான்` establishes `பெற்றான்`;
- scan 304 — source-visible lexical `நீ` is omitted by `p7.md`; canonical record remains `needs-review` without source insertion;
- scan 305 — source-visible lexical `என்ன` is omitted by `p7.md`; canonical record remains `needs-review` without source insertion;
- scan 306 — chapter 34 closes with a source horizontal rule;
- scan 307 — chapter 35 begins under source heading `35` and ends open at `அவனை ஆட்டி வைத்த ‘மிருகம்’`.

The endpoint spot-check at scan 343 / printed 339 ends at `அதிர்ஷ்`, so Part 007 also remains open and cannot be treated as the work ending.

## Gate consequence

Sequential canonical work may continue despite scans 304–305 being `needs-review`, but the Part-007 Tamil audit cannot pass until those two complete baseline lexical omissions receive explicit user/baseline disposition.

## Exact next activity

Process **scan 308 / printed 304** in chapter 35 from the controlling `p7.md` lexical baseline and native Part-007 page 14. Verify `‘மிருகம்’` → `பதுங்கி விட்டது...`, then continue sequential canonical/structural reconciliation through scan 343.