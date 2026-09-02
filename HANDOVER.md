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
- Part 006 — scans 246–294 — **part-complete**

Part-005 source-damage qualification remains attached to scans **215–219 and 223–224**. Their canonical status is not upgraded by downstream assembly/translation.

## Latest completed derivative — Part 006

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
- assembled Tamil: **PASSED** — `works/pudhaiyal/notes/part-006-assembled-tamil-check.md`
- controlled English source check: **PASSED** — `works/pudhaiyal/translations/en/PART_006_ENGLISH_CHECK.md`
- bilingual review: **PASSED** — `works/pudhaiyal/translations/en/PART_006_REVIEW.md`
- Part-006 state: **`part-complete`**

### Part-006 reviewed checkpoint

The Tamil/English layers now cover:

- chapter 27 continuation through its close on scan 247;
- chapter 28, including the source-printed four-star transition on scan 251;
- chapters 29–32 through their source-established closes;
- chapter 33 from scan 288 through the open Part-006 endpoint on scan 294.

The bilingual review confirmed complete represented sentence/dialogue coverage, audited page joins, chapter/internal-transition fidelity, scan-280-onward Gemini lexical-authority discipline, names/terms consistency and the represented satire/violence/romance/coercion/caste-marked wording.

English-only review corrections included conservative **Chakkili** handling, removal of two over-interpretive readings, non-repair of the scan-277 source anomaly, and stable **Raja Madam** / glossary handling. No Tamil lexical text was changed.

### Critical continuation boundary

Scan **294 / printed 290** ends inside the Sub-Inspector's dialogue at open Tamil `‘லாக்`. Reviewed English correspondingly ends at open `‘Lock` with **no closing quotation mark or punctuation**.

There is no chapter close, work-ending ornament or back-matter transition.

**Do not treat Part 006 as the end of the novel.** The next source material beyond scan 294 is required to continue chapter 33.

## Aggregate durable state

- canonical records: **294**
- verified / completed: **287**
- needs-review: **7 — Part 005 scans 215–219, 223–224**
- partial: **0**
- clean contiguous fully verified range: through scan **214 / printed page 212**
- later completed pages: through scan **294**, except the seven damaged Part-005 records
- Parts 001–006: **part-complete at split level**
- assembled Tamil: part-reviewed continuously through scan **294**
- source-checked / bilingual-reviewed English: continuously through scan **294**
- source scans represented by currently received derivatives: through **294**
- whole-work Tamil / English / release gates: not yet eligible

## Exact next activity

Obtain / resolve the **next source derivative beyond scan 294**.

Before any new canonical write:

1. inspect the actual first page of the new derivative;
2. confirm that it continues the open scan-294 `‘லாக்` dialogue rather than assuming the continuation;
3. establish the real source-scan and printed-page mapping from the source itself;
4. record derivative identity/size/hash when available;
5. only then begin the next split's canonical Tamil workflow under the same authority policy unless the user changes it.

Do not infer the next part range, continuation word, chapter boundary, true ending, back matter or full source extent without the actual source material.