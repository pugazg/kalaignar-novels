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

By explicit user instruction, Part-006 scan **280 onward** uses a hybrid authority model.

### WORDS

Gemini's supplied transcription controls lexical wording.

- retain Gemini's words, spelling, suffixes, vowel signs, sandhi, lexical forms and supplied lexical spacing;
- do not replace a Gemini word merely because the scan appears to contain a different lexical form;
- if Gemini omitted a word/span altogether, flag the omission instead of silently supplying lexical text from the scan.

### STRUCTURE / PRESENTATION

The native scan controls headings/chapter numbers, paragraph boundaries, punctuation, quotation marks, long dashes, speaker-label spacing/layout, physical line/page breaks, separators and chapter/scene transitions.

When a lexical word is split physically across a source line or source page, keep Gemini lexical wording while preserving/recording the native physical split.

## Latest completed split — Part 006

Source derivative: `TVA_BOK_0064097_புதையல்_part_006_pages_246-294.pdf`

- physical pages / mapped source scans: **49 / 49 — scans 246–294**
- visible printed pages: **242–290**
- derivative map: [`indexes/part-006-page-map.md`](indexes/part-006-page-map.md)
- canonical records: **49 / 49**
- verified / structurally completed: **49 / 49**
- needs-review: **0**
- Tamil audit: **PASSED** — [`notes/part-006-tamil-audit.md`](notes/part-006-tamil-audit.md)
- assembled Tamil: **PASSED** — [`notes/part-006-assembled-tamil-check.md`](notes/part-006-assembled-tamil-check.md)
- controlled English source check: **PASSED** — [`translations/en/PART_006_ENGLISH_CHECK.md`](translations/en/PART_006_ENGLISH_CHECK.md)
- bilingual review: **PASSED** — [`translations/en/PART_006_REVIEW.md`](translations/en/PART_006_REVIEW.md)
- state: **`part-complete`**

### Part-006 completed checkpoint

The completed layers:

- extend chapter 27 through its close on scan 247;
- carry chapters 28–33 through scan 294;
- preserve the source-printed four-star transition at scan 251;
- preserve chapter transitions at scans 254, 262, 271, 278 and 288;
- carry audited physical-page joins continuously without creating false split boundaries;
- remain subordinate to controlling Tamil, including scan-280-onward Gemini lexical authority;
- retain source-specific satire, threats, violence, romantic delusion, coercion and caste-marked wording in reviewed English;
- leave chapter 33 open at scan 294 / printed 290 at Tamil `‘லாக்` / English `‘Lock` with no invented closing punctuation.

The bilingual review made English-only fidelity/consistency corrections and glossary updates; canonical Tamil was not altered.

## Completed split checkpoints

- Part 001 — scans **1–49** — **`part-complete`**
- Part 002 — scans **50–98** — **`part-complete`**
- Part 003 — scans **99–147** — **`part-complete`**
- Part 004 — scans **148–196** — **`part-complete`**
- Part 005 — scans **197–245** — **`part-complete` with explicit source-damage qualification**
- Part 006 — scans **246–294** — **`part-complete`**

## Exact next activity

Obtain / resolve the **next source derivative beyond scan 294** before opening another split workflow.

1. inspect the actual first page of the next derivative;
2. verify that it continues the open scan-294 `‘லாக்` dialogue;
3. establish real source-scan / printed-page mapping from the source itself;
4. record derivative provenance/integrity metadata when available;
5. only then begin canonical transcription/reconciliation for the next split.

Do not assume the next derivative's range, continuation word, chapter boundary, ending or full source extent without source evidence.