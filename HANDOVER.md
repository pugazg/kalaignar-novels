# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Current work: `works/pudhaiyal/`

## Current authority rule

The native scan controls page identity, headings, punctuation, quotation marks, paragraph/section structure, long dashes, physical line/page breaks, separators and chapter/scene transitions.

### Pudhaiyal lexical-preservation override — scan 280 onward

By explicit user instruction, supplied Gemini transcription controls **WORDS / lexical text** from scan 280 onward. Keep supplied words, spelling, suffixes, lexical forms, wording and supplied lexical spacing; do not source-correct a supplied form from native visual evidence.

Part-specific lexical baselines:

- Part 007 — uploaded `p7.md`, SHA-256 `a804b914b88050ca8d31142cb00d7491c94e89ff1fb7e564fdd348bdf14b1c59`;
- Part 008 — uploaded `p8.md`, SHA-256 `aad52bdfeae873459d561a52826f4787fd04f72ac1c27886212a1942d8e89ca2`.

For Part 007, three complete omissions were restored only after the user's explicit 2026-09-02 instruction **`insert all three omissions`**:

- scan 304 — `நீ`;
- scan 305 — `என்ன`;
- scan 315 — `சரி...... வா! வா!......`.

No broader lexical source-correction permission exists. For Part 008, any complete source-visible lexical word/span absent from `p8.md` must be flagged `needs-review`; do not silently insert it.

Source/split PDFs and uploaded baseline files must never be committed.

## Source identity — புதையல்

- original filename: `TVA_BOK_0064097_புதையல்.pdf`
- author: கலைஞர் மு. கருணாநிதி, எம். எல். ஏ.
- publisher: அன்புப் பதிப்பகம், பொறையார் :: தஞ்சை மாவட்டம்
- edition: மூன்றாம் பதிப்பு — செப்டம்பர் 1961
- Tamil Digital Library bibliographic extent: 443 p.
- exact full-PDF scan count / full-source SHA-256: pending complete source reconciliation

## Completed derivatives

- Part 001 — scans 1–49 — **part-complete**
- Part 002 — scans 50–98 — **part-complete**
- Part 003 — scans 99–147 — **part-complete**
- Part 004 — scans 148–196 — **part-complete**
- Part 005 — scans 197–245 — **part-complete with explicit source-damage qualification**
- Part 006 — scans 246–294 — **part-complete**
- Part 007 — scans 295–343 — **part-complete**

Part-005 source-damage qualification remains attached to scans **215–219 and 223–224**.

## Active derivative — Part 008

Source: `TVA_BOK_0064097_புதையல்_part_008_pages_344-392.pdf`

- physical pages: **49**
- source scans: **344–392**
- printed pages: **340–388**
- derivative size: **54,567,816 bytes**
- derivative SHA-256: `717d3ab75eb970313062e1e61517d442cffa188f2fd8cadb8f75263b5e9a8852`
- lexical baseline: uploaded `p8.md`, **159,525 bytes / 319 lines**
- `p8.md` SHA-256: `aad52bdfeae873459d561a52826f4787fd04f72ac1c27886212a1942d8e89ca2`
- source intake: `works/pudhaiyal/notes/part-008-source-intake.md`
- page map: `works/pudhaiyal/indexes/part-008-page-map.md`
- canonical records: **0 / 49**
- verified: **0 / 49**
- Part-008 needs-review: **0**
- not-started: **49**
- state: **`intake-complete / canonical-reconciliation-next`**

### Verified Part-007→008 boundary

Part 007 scan **343 / printed 339** ends inside the fortune-teller's open utterance at `அதிர்ஷ்`.

Part 008 scan **344 / printed 340** visibly begins `டம் அடிக்குது!`, and `p8.md` begins with the same lexical continuation.

Therefore the source-backed split join is:

**`அதிர்ஷ்` + `டம்` → `அதிர்ஷ்டம்`**, giving **`அதிர்ஷ்டம் அடிக்குது!`**.

This is a narrative continuation; no chapter boundary occurs at the split.

### Native structural landmarks already resolved at intake

- scan 347 / printed 343 — Chapter 39 closes;
- scan 348 / printed 344 — Chapter 40 begins;
- scan 355 / printed 351 — Chapter 40 closes / Chapter 41 begins;
- scan 362 / printed 358 — Chapter 41 closes / Chapter 42 begins;
- scan 369 / printed 365 — Chapter 42 closes / Chapter 43 begins;
- scan 376 / printed 372 — Chapter 43 closes / Chapter 44 begins;
- scan 387 / printed 383 — Chapter 44 closes / Chapter 45 begins;
- scan 392 / printed 388 — Chapter 45 remains open; derivative ends visibly at `நமது`.

Do not treat scan 392 as the novel ending.

## Aggregate durable state

- canonical records: **343**
- verified / completed: **336**
- needs-review: **7 — only Part 005 scans 215–219, 223–224**
- partial: **0**
- Parts 001–007: **part-complete** at split level
- Part 008: **received and mapped; canonical reconciliation pending**
- assembled Tamil: part-reviewed continuously through scan **343**
- source-checked and bilingual-reviewed English: continuously through scan **343**
- physically received source coverage: through scan **392 / printed 388**
- whole-work Tamil / English / release gates: not yet eligible

## Exact next activity

Run **Part-008 canonical reconciliation across scans 344–392 in bulk**. Use `p8.md` as lexical authority and the native Part-008 PDF as structural authority. Preserve the verified `அதிர்ஷ்` + `டம்` continuation, reconcile every physical page boundary/chapter transition/separator, and flag any complete baseline omission rather than silently inserting native-source words.

After canonical reconciliation completes, run the Part-008 Tamil audit before assembled Tamil or English work.