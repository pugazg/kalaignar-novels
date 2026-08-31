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

By explicit user instruction, the remaining Part-006 transcription uses a **hybrid authority model**:

### WORDS

For scan **280 onward**, Gemini's supplied transcription controls lexical wording.

- retain Gemini's words exactly;
- do not change spelling, suffixes, vowel signs, sandhi, lexical spacing, or unusual word forms from native visual reading;
- do not replace a Gemini word merely because the scan appears to contain a different word;
- do not use the old-Tamil-glyph check to alter Gemini's supplied lexical text;
- if Gemini omitted a word/span altogether or a baseline span is incomplete, flag the omission instead of silently supplying lexical text from the scan.

### STRUCTURE / PRESENTATION

The native scan controls:

- headings and chapter numbers;
- paragraph boundaries;
- punctuation;
- quotation marks;
- long dashes;
- speaker-label spacing/layout;
- physical line breaks;
- physical page breaks and cross-page provenance;
- horizontal rules / star separators;
- scene/chapter transitions;
- other non-lexical structural findings.

When a lexical word is split physically across a source line or source page, keep Gemini's word but record the native physical split in the source/boundary note.

This rule is **prospective from scan 280**. Scans 246–279 are not to be reopened solely to apply this new policy unless the user explicitly requests a retrospective pass.

## Old-Tamil-typeform safeguard

The edition demonstrates faint final `லை`, faint `ா`, and `ே` / `ோ` distinctions. For scan 280 onward this safeguard is used to understand **structure and physical layout only**, not to override Gemini's supplied words.

## Completed split checkpoints

- Part 001 — scans **1–49** — **`part-complete`**
- Part 002 — scans **50–98** — **`part-complete`**
- Part 003 — scans **99–147** — **`part-complete`**
- Part 004 — scans **148–196** — **`part-complete`**
- Part 005 — scans **197–245** — **`part-complete` with explicit source-damage qualification**

## Active split — Part 006

Source derivative: `TVA_BOK_0064097_புதையல்_part_006_pages_246-294.pdf`

- physical pages / mapped source scans: **49 / 49 — scans 246–294**
- visible printed pages: **242–290**
- derivative map: [`indexes/part-006-page-map.md`](indexes/part-006-page-map.md)
- canonical records: **34 / 49 — scans 246–279**
- verified: **34**
- needs-review: **0**
- not-started: **15 — scans 280–294**
- latest native-fidelity record: [`notes/visual-fidelity-scan-279.md`](notes/visual-fidelity-scan-279.md)
- Tamil audit: **not eligible**
- assembled Tamil: **not eligible**
- controlled English: **not eligible**
- bilingual review: **not eligible**
- state: **`in-progress`**

### Current Part-006 checkpoint

- scan 279 is complete;
- scan 279 ends physically at `அதிபதி`;
- scan 280 begins physically with `யாக வேண்டும்`;
- from scan 280 onward, record this and later physical boundaries structurally while preserving Gemini's lexical wording exactly.

Part-006 mapped chapter transitions: chapter 28 begins scan 247; a four-star internal transition occurs on scan 251; chapter 29 begins 254 and closes 262; chapter 30 begins 262 and closes 271; chapter 31 begins 271 and closes 278; chapter 32 begins 278; chapter 33 begins 288.

Do not run the Part-006 Tamil audit or any downstream stage until all scans 246–294 have canonical records and structural/native-fidelity dispositions.

## Part 005 — durable completion record

- split pages / canonical records: **49 / 49 — scans 197–245**
- `verified`: **42**
- `needs-review`: **7 — scans 215–219, 223–224**
- state: **`part-complete` with source-damage qualification**

## Exact next activity

Process **scan 280 / printed page 276**. Keep **Gemini's words exactly**. Use the source scan for headings, punctuation, long dashes, quote style, paragraph structure, speaker-label spacing, physical line/page breaks and other structural findings only.