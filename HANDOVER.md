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
- controlled English source check: **PASSED** — `works/pudhaiyal/translations/en/PART_006_ENGLISH_CHECK.md`
- bilingual review: **ELIGIBLE — NEXT ACTIVITY**
- Part-006 state: **English `source-checked`; not yet `part-complete`**

### Part-006 English checkpoint

The source-checked English layer now contains:

- `translations/en/sections/27-chapter-27.md` — extended through chapter-27 close on scan 247;
- `translations/en/sections/28-chapter-28.md` — chapter 28, including the source-printed four-star internal transition at scan 251;
- `translations/en/sections/29-chapter-29.md` — chapter 29 through scan 262;
- `translations/en/sections/30-chapter-30.md` — chapter 30 through scan 271;
- `translations/en/sections/31-chapter-31.md` — chapter 31 through scan 278;
- `translations/en/sections/32-chapter-32.md` — chapter 32 through scan 288;
- `translations/en/sections/33-chapter-33.md` — chapter 33 from scan 288 through the open Part-006 endpoint on scan 294.

The English source check confirms:

- Part 005→006 continuity is preserved;
- all audited page joins are translated continuously rather than as artificial split boundaries;
- the scan-251 internal transition and real chapter boundaries are retained;
- scan-280-onward Gemini lexical authority in Tamil is respected; English does not source-correct those words from native pixels;
- one initially invented dash after the final open `‘Lock` was removed during checking;
- one English-only grammar slip in the Sub-Inspector line was corrected;
- no Tamil lexical text was changed by those English-layer corrections.

### Critical continuation boundary

Scan **294 / printed 290** ends inside the Sub-Inspector's dialogue at open `‘லாக்`. Source-checked English correspondingly ends at open `‘Lock` with **no closing quotation mark or punctuation**.

**Do not treat Part 006 as the end of the novel.** A later source split beyond scan 294 is required to continue chapter 33.

## Aggregate durable state

- canonical records: **294**
- verified / completed: **287**
- needs-review: **7 — Part 005 scans 215–219, 223–224**
- partial: **0**
- clean contiguous fully verified range: through scan **214 / printed page 212**
- later completed pages: through scan **294**, except the seven damaged Part-005 records
- Parts 001–005: **part-complete at split level**
- Part 006: **Tamil audit + assembled Tamil + English source check PASSED; bilingual review pending**
- assembled Tamil: part-reviewed continuously through scan **294**
- source-checked English: continuously through scan **294**
- bilingual-reviewed / part-complete English: continuously through scan **245**
- source scans represented by currently received derivatives: through **294**
- whole-work Tamil / English / release gates: not yet eligible

## Exact next activity

Run the **Part-006 bilingual review for scans 246–294**.

Review scope:

1. compare audited Tamil and source-checked English sentence by sentence / dialogue by dialogue;
2. confirm no substantive sentence, repetition, joke, threat, violence, romantic delusion, coercive act or satirical turn is omitted, softened or intensified;
3. verify names, place names and culture-specific terms against `translations/en/GLOSSARY.md` and established prior usage;
4. verify all audited page joins and the scan-251 internal transition;
5. verify chapter boundaries at scans 247/254/262/271/278/288;
6. verify the scan-280-onward Gemini lexical-authority discipline is respected;
7. leave the scan-294 Tamil `‘லாக்` / English `‘Lock` endpoint open with no invented close;
8. if the review passes, create `works/pudhaiyal/translations/en/PART_006_REVIEW.md`, mark Part 006 `part-complete`, and synchronize repository status.

Do not claim whole-work English verification or release readiness after Part 006; later source beyond scan 294 remains required.