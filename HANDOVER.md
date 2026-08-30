# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Current work: `works/pudhaiyal/`

## Permanent source rule

The scan is the textual authority. User-supplied transcription is the comparison baseline. Do not modernize or infer unclear Tamil. Assistant-introduced changes must be established from native pixels. If damage/repair hides letters, retain the baseline and `needs-review` rather than claiming verification.

### Mandatory old-Tamil-glyph pre-correction check

Before overriding a baseline because a final character or vowel mark appears absent, inspect the **complete glyph cluster at high resolution**, explicitly consider old/historical Tamil typeforms, and compare another clear instance from the same edition when useful. Faint marks must be checked at more than one useful scale/contrast before a correction is accepted.

A demonstrated risk in this edition is final `லை`, which can resemble bare `ல்` at ordinary zoom. This caused earlier false assistant corrections such as `தெரியவில்லை` → `தெரியவில்ல`. This is **not** a global normalization rule.

**Strengthened after the scans-256–259 correction:** a proposed baseline change involving an old/faint vowel sign, near-identical same-word glyph, or apparent spacing produced by a printed line wrap requires a **second independent high-resolution pass** before acceptance. Compare the same form elsewhere in the edition when possible. A printed line break alone never establishes word-internal spacing. If the user/source challenges one glyph in a batch, reopen every assistant-origin discrepancy in that batch before moving forward.

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
- canonical records: **19 / 49 — scans 246–264**
- verified: **19**
- needs-review: **0**
- not-started: **30 — scans 265–294**
- latest fidelity record: `works/pudhaiyal/notes/visual-fidelity-scan-264.md`
- Tamil audit / assembled Tamil / English / bilingual review: **not yet eligible**
- Part-006 state: **`in-progress`**

### Current verified Iteration-25 sequence

- scan 260 / printed 256: verified; ends `வெள்ளியம்பலம்`;
- scan 261 / printed 257: closes `வெள்ளியம்பலம் கேட்டு விட்டு, ...`; preserves `தவழுகத்`, `ஆள்பாடு ஆயிடும்`, `எங்கேயிருக்கு`, `பேஷாக`; ends `விடிந்த`;
- scan 262 / printed 258: begins `தும்`, yielding `விடிந்ததும்`; source `குறுக்கிட்டது`, `என்று கூறினான்`, `ஆம்;`, `நடந்து, நடந்து`; chapter 29 closes / chapter 30 begins; ends `துக்காராமுக்கோ,`;
- scan 263 / printed 259: begins `ஆனந்தம் தாங்கவில்லை.`; source `நடந்தவைகள்`, `புதையலைக் கண்டுபிடிப்பதற்காகவே`, full `மறந்து விடவில்லை`; ends `அவர்!`;
- scan 264 / printed 260: source **`என்ன — தெரியாது மாதிரி விழிக்கிறே?`**, not baseline `என்னா - ...`; source punctuation `தெரியவில்லை — விழித்தாள்!`, `சரி — சரி —`, `வந்தேனே......`; complete `புரியவில்லை` confirmed; ends `பேசக்கூட விடமாட்டேங்கிறீர்களே!”`.

### Part-006 structure mapped from physical pages

- chapter 27 closes / chapter 28 begins scan **247**;
- four-star internal transition scan **251**;
- chapter 29 begins scan **254** and closes scan **262**;
- chapter 30 begins scan **262**;
- chapter 31 begins scan **271**;
- chapter 32 begins scan **278**;
- chapter 33 begins scan **288** and continues through scan **294**.

## Aggregate durable state

- canonical records: **264**
- verified: **257**
- needs-review: **7 — scans 215–219, 223–224**
- partial: **0**
- clean contiguous fully verified range: through scan **214 / printed page 212**
- later individual source-verified pages: through scan **264**, except the seven damaged Part-005 records
- Parts 001–005: **part-complete at split level**
- Part 006: **in progress — 19 / 49 verified**
- assembled Tamil / English split-level review: through scan **245** only
- source scans represented by currently received derivatives: through **294**
- whole-work Tamil / English / release gates: not yet eligible

## Exact next activity

Continue Part 006 at **scan 265 / printed page 261**, chapter 30, from user Iteration 25. Apply the strengthened two-pass old-Tamil-typeform and printed-line-wrap rules before accepting any disputed glyph or spacing.