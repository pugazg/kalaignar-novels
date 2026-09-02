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

- keep Gemini's words exactly as supplied;
- do **not** replace a Gemini word, spelling, suffix, vowel sign, sandhi form or lexical spacing because the scan appears to show a different lexical form;
- use native scan inspection for **headings, punctuation, quote marks, long dashes, speaker-label spacing, paragraph breaks, physical line breaks, chapter/scene boundaries, separators/rules, page boundaries and other structural findings**;
- when a word is physically split across a printed line/page, retain Gemini's lexical word while preserving/recording the physical break/provenance;
- if Gemini omitted a word/span entirely or the supplied baseline is genuinely incomplete, record the gap rather than silently supplying lexical text from the scan;
- this rule is **prospective**. Do not reopen scans 246–279 solely to conform to it unless explicitly requested.

The old-Tamil-glyph safeguard remains useful for structural interpretation but must not alter Gemini lexical words from scan 280 onward.

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

Assembled Tamil and controlled English remain split-level reviewed continuously through scan **245**, with Part-005 source-damage qualifications preserved.

## Active derivative — Part 006

Source: `TVA_BOK_0064097_புதையல்_part_006_pages_246-294.pdf`

- physical pages: **49**
- source scans: **246–294**
- visible printed pages: **242–290**
- derivative size: **57,056,182 bytes**
- derivative SHA-256: `34a5ea5eb91a71ca8674760257779eb4ed6bdc6640517f8830b9ee70aa34aec7`
- derivative map: `works/pudhaiyal/indexes/part-006-page-map.md`
- canonical records: **38 / 49 — scans 246–283**
- verified / completed: **37**
- needs-review: **1 — scan 283**
- not-started: **11 — scans 284–294**
- latest fidelity record: `works/pudhaiyal/notes/visual-fidelity-scan-283.md`
- Tamil audit / assembled Tamil / English / bilingual review: **not yet eligible**
- Part-006 state: **`in-progress`**

### Hybrid-policy checkpoint — scans 280–283

- scans 280–283 use Gemini lexical wording unchanged;
- native source supplies punctuation, quotation structure, paragraphing, long dashes and physical line breaks;
- scan 282 ends without punctuation at `துக்காராம் அப்படியே அசைவற்று நின்றான்`;
- scan 283 begins `சிறிது நேரம்.`, confirming a cross-page sentence continuation;
- no source-printed chapter/scene transition occurs on scan 283;
- source long-dash structures include `போதும்—இனியும்` and `வெள்ளியம்பலம்—என்ற`;
- scan 283 physical line-break provenance includes `நிலைப்` / `படுத்திவிட்டது`, `கூறிக்` / `கொண்டே`, `துக்கா` / `ராம்`, `உனக்` / `கும்`, `உண்மை` / `யைக்`, `சொல்` / `வது`, and `பயன்படுத்து` / `வார்`;
- **open lexical omission:** source contains `பார்` immediately after `ஓடிப் போகிறேன்`; Gemini does not. Per policy, the source-only token was not inserted. Scan 283 is `needs-review` pending explicit user disposition;
- scan 283 ends `வெள்ளியம்பலம்—என்ற திகிலும் கூடவே பிறந்தது.`.

### Part-006 structure mapped from physical pages

- chapter 27 closes / chapter 28 begins scan **247**;
- four-star internal transition scan **251**;
- chapter 29 begins scan **254** and closes scan **262**;
- chapter 30 begins scan **262** and closes scan **271**;
- chapter 31 begins scan **271** and closes scan **278**;
- chapter 32 begins scan **278**;
- chapter 33 begins scan **288** and continues through scan **294**.

## Aggregate durable state

- canonical records: **283**
- verified / completed: **275**
- needs-review: **8 — Part 005 scans 215–219, 223–224; Part 006 scan 283**
- partial: **0**
- clean contiguous fully verified range: through scan **214 / printed page 212**
- later completed pages: through scan **282**, with scan 283 explicitly `needs-review`
- Parts 001–005: **part-complete at split level**
- Part 006: **in progress — 37 verified/completed + 1 needs-review / 49**
- assembled Tamil / English split-level review: through scan **245** only
- source scans represented by currently received derivatives: through **294**
- whole-work Tamil / English / release gates: not yet eligible

## Exact next activity

Continue Part 006 at **scan 284 / printed page 280**, chapter 32. **Keep Gemini's words exactly.** Use native scan evidence only for headings, punctuation, long dashes, quote style, speaker-label spacing, paragraph/physical line breaks, page-boundary provenance and other structural findings. Keep scan 283's `பார்` omission open until explicitly resolved by the user.