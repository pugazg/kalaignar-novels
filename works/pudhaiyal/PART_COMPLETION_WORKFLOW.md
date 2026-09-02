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
- not-started: **0**
- latest native-fidelity record: [`notes/visual-fidelity-scan-294.md`](notes/visual-fidelity-scan-294.md)
- Tamil audit: **eligible — next activity**
- assembled Tamil: **not eligible until audit passes**
- controlled English: **not eligible until audit/assembled Tamil pass**
- bilingual review: **not eligible**
- state: **canonical/structural complete — audit pending**

### Part-006 boundary / structure checkpoints

- chapter 27 closes / chapter 28 begins scan 247;
- four-star internal transition scan 251;
- chapter 29 begins 254 and closes 262;
- chapter 30 begins 262 and closes 271;
- chapter 31 begins 271 and closes 278;
- chapter 32 begins 278 and closes 288;
- chapter 33 begins 288 and continues beyond the derivative endpoint;
- scan 294 / printed 290 ends at open `‘லாக்` inside dialogue, with no source ending marker.

Scans **280–294** are all verified under the Gemini-lexical/native-structure policy, and no Gemini lexical omission remains unresolved.

## Completed split checkpoints

- Part 001 — scans **1–49** — **`part-complete`**
- Part 002 — scans **50–98** — **`part-complete`**
- Part 003 — scans **99–147** — **`part-complete`**
- Part 004 — scans **148–196** — **`part-complete`**
- Part 005 — scans **197–245** — **`part-complete` with explicit source-damage qualification**

## Exact next activity

Run the **Part-006 Tamil audit** for scans **246–294**. Audit all 49 canonical records against the page map and fidelity records; verify page-boundary continuity, chapter transitions, scan-280-onward Gemini lexical preservation and scan-294's open derivative boundary. Only after a passing audit should assembled Tamil be updated.