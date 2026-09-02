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

Part-005 source-damage qualification remains attached to scans **215–219 and 223–224**. Their canonical status is not upgraded by downstream assembly/translation.

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
- Tamil audit: **PASSED** — `works/pudhaiyal/notes/part-006-tamil-audit.md`
- assembled Tamil: **PASSED split-level consistency check** — `works/pudhaiyal/notes/part-006-assembled-tamil-check.md`
- controlled English: **ELIGIBLE — NEXT ACTIVITY**
- bilingual review: **not yet eligible**
- Part-006 state: **`assembled-part-checked`**

### Part-006 assembled Tamil checkpoint

The checked assembled reading layer now contains:

- `sections/27-chapter-27.md` — extended from the Part-005 endpoint through the chapter-27 close on scan 247;
- `sections/28-chapter-28.md` — chapter 28, including the source-printed four-star internal transition at scan 251;
- `sections/29-chapter-29.md` — chapter 29 through scan 262;
- `sections/30-chapter-30.md` — chapter 30 through scan 271;
- `sections/31-chapter-31.md` — chapter 31 through scan 278;
- `sections/32-chapter-32.md` — chapter 32 through scan 288;
- `sections/33-chapter-33.md` — chapter 33 from scan 288 through the open Part-006 endpoint on scan 294.

The assembly check confirms:

- audited canonical pages are the only Tamil input;
- physical line wrapping is removed for readability without lexical rewriting;
- page/split joins occur only where canonical/audit evidence establishes continuity;
- scan-280-onward Gemini lexical authority remains intact;
- source-page provenance is retained through comments and the canonical page map;
- chapter 33 remains open at scan 294 / printed 290 at `‘லாக்`.

### Critical continuation boundary

Scan **294 / printed 290** ends inside the Sub-Inspector's dialogue at open `‘லாக்`. There is no closing quotation mark, sentence punctuation, chapter close, work-ending ornament or back-matter transition.

**Do not treat Part 006 as the end of the novel.** A later source split beyond scan 294 is required to continue chapter 33.

## Aggregate durable state

- canonical records: **294**
- verified / completed: **287**
- needs-review: **7 — Part 005 scans 215–219, 223–224**
- partial: **0**
- clean contiguous fully verified range: through scan **214 / printed page 212**
- later completed pages: through scan **294**, except the seven damaged Part-005 records
- Parts 001–005: **part-complete at split level**
- Part 006: **Tamil audit + assembled Tamil check PASSED; English pending**
- assembled Tamil: part-reviewed continuously through scan **294**
- controlled English / bilingual review: part-reviewed continuously through scan **245** only
- source scans represented by currently received derivatives: through **294**
- whole-work Tamil / English / release gates: not yet eligible

## Exact next activity

Begin the **Part-006 controlled English translation** from the checked assembled Tamil layer.

Translation scope:

1. extend the existing chapter-27 English translation through the chapter-27 close on scan 247;
2. translate assembled chapters **28 through 33** from the checked Tamil layer through scan 294;
3. preserve the scan-251 internal transition and all real chapter boundaries;
4. keep English subordinate to canonical Tamil meaning and source-specific narrative/dialogue structure;
5. do not translate scan 294 as an ending — leave the final Sub-Inspector dialogue open where Tamil ends at `‘லாக்`;
6. source-check the completed Part-006 English against canonical Tamil before opening the bilingual-review gate.

Do not start Part-006 bilingual review until the controlled English translation is complete and source-checked.