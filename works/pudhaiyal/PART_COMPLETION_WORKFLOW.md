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

## Active split — Part 006

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
- bilingual review: **ELIGIBLE — NEXT ACTIVITY**
- state: **English `source-checked`; not yet `part-complete`**

### Part-006 English checkpoint

The source-checked English layer:

- extends chapter 27 through its close on scan 247;
- translates chapters 28–33 through scan 294;
- preserves the source-printed four-star transition at scan 251;
- preserves chapter transitions at scans 254, 262, 271, 278 and 288;
- carries audited physical-page joins continuously without creating false split boundaries;
- remains subordinate to the controlling Tamil, including the scan-280-onward Gemini lexical authority;
- leaves chapter 33 open at scan 294 / printed 290 at Tamil `‘லாக்` / English `‘Lock` with no invented closing punctuation.

The English source check corrected one initially invented endpoint dash and one English-only grammar slip; no Tamil text was changed.

## Completed split checkpoints

- Part 001 — scans **1–49** — **`part-complete`**
- Part 002 — scans **50–98** — **`part-complete`**
- Part 003 — scans **99–147** — **`part-complete`**
- Part 004 — scans **148–196** — **`part-complete`**
- Part 005 — scans **197–245** — **`part-complete` with explicit source-damage qualification**

## Exact next activity

Run the **Part-006 bilingual review for scans 246–294**:

1. compare audited Tamil and source-checked English sentence by sentence and dialogue by dialogue;
2. verify complete narrative coverage and meaning alignment;
3. verify names, place names and culture-specific terms against established usage/glossary;
4. verify humour, satire, threats, violence, romantic delusion and coercive behaviour are neither omitted nor deliberately softened/intensified;
5. verify all audited page joins, the scan-251 internal transition and real chapter boundaries;
6. verify scan-280-onward Gemini lexical-authority discipline remains intact;
7. verify the open scan-294 Tamil `‘லாக்` / English `‘Lock` endpoint remains unclosed;
8. if the review passes, create `translations/en/PART_006_REVIEW.md`, mark Part 006 `part-complete`, and synchronize status.

Do not claim whole-work English verification or release-readiness after Part 006; later source beyond scan 294 remains required.