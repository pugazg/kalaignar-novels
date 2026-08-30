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

A demonstrated risk in this edition is final `லை`, which can resemble bare `ல்` at ordinary zoom. This caused earlier false assistant corrections such as `தெரியவில்லை` → `தெரியவில்ல`. The retrospective repair is recorded in:

`works/pudhaiyal/notes/old-glyph-retrospective-audit-120-245.md`

This is **not** a global normalization rule. Source-specific forms remain unchanged when their native pixels support them. If pixels are ambiguous, retain the baseline and `needs-review`.

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

The old `150 pages total` conclusion is permanently withdrawn.

## Split workflow

For each supplied derivative: map → canonical pages → native fidelity → resolve/retain uncertainty → part Tamil audit → assembled Tamil → English → bilingual review → status synchronization → `part-complete`.

Split boundaries are provenance only.

## Completed derivatives

- Part 001 — scans 1–49 — **part-complete**
- Part 002 — scans 50–98 — **part-complete**
- Part 003 — scans 99–147 — **part-complete; scan 120 old-glyph correction re-synchronized**
- Part 004 — scans 148–196 — **part-complete**
- Part 005 — scans 197–245 — **part-complete with explicit source-damage qualification; readable-page old-glyph corrections re-synchronized**

Assembled Tamil and controlled English remain split-level reviewed continuously through scan **245**, with Part-005 source-damage qualifications preserved.

## Active derivative — Part 006

Source: `TVA_BOK_0064097_புதையல்_part_006_pages_246-294.pdf`

- physical pages: **49**
- source scans: **246–294**
- visible printed pages: **242–290**
- derivative size: **57,056,182 bytes**
- derivative SHA-256: `34a5ea5eb91a71ca8674760257779eb4ed6bdc6640517f8830b9ee70aa34aec7`
- derivative map: `works/pudhaiyal/indexes/part-006-page-map.md`
- canonical records: **15 / 49 — scans 246–260**
- verified: **15**
- needs-review: **0**
- not-started: **34 — scans 261–294**
- latest fidelity record: `works/pudhaiyal/notes/visual-fidelity-scan-260.md`
- Tamil audit / assembled Tamil / English / bilingual review: **not yet eligible**
- Part-006 state: **`in-progress`**

### Mandatory 245→246 continuity finding

Part 005 scan **245 / printed 241** ends `இருக்கவே`; Part 006 scan **246 / printed 242** begins `இருக்கிறாள் பரிமளா, ...`. Native evidence establishes the continuous source sentence `இருக்கவே இருக்கிறாள் பரிமளா, ...`.

### Corrected scans 256–259

The first visual pass introduced unsupported differences. The second high-resolution review confirms the user's baseline forms:

- scan 256: `காட்டுகிறாயா?`, plus `இடத்தை`, `என்னா`, `தங்கம்னா`, `பொன்னா`, `ஒளிஞ்சுகிட்டு`;
- scan 257: `நன்றாகப் பார்த்தான்`; page ends mid-word `வெள்ளியம்`;
- scan 258: begins `பலம்`, yielding `வெள்ளியம்பலம்`; source `அநாவசியமாக`; separated `காதலிக்க வில்லையே`;
- scan 259: `மண்ணாங் கட்டியாவது!`; separated `விளங்க வில்லையே!`; `ஒன்றாய்ப் பிசைந்து` remains confirmed.

The earlier assistant readings `காட்டுகிறியா?`, `நன்றுகப் பார்த்தான்`, `அனாவசியமாக`, and `மண்ணுங் கட்டியாவது!` are withdrawn.

### Scan 260 / printed 256 — verified

The supplied **Iteration 25** baseline begins at scan 260. A strengthened two-pass native review verifies the page with only positively established differences:

- baseline typo `சொலலு` → source `சொல்லு`, giving `சொல்லு! சொல்லு!`;
- source prints `சாமியாருக்குத்தான்` continuously;
- source reads `பொய் சொல்லுகிறாயா?`;
- physical page ends at `வெள்ளியம்பலம்`, and scan 261 must continue that sentence.

No unresolved glyph remains on scan 260.

### Part-006 structure mapped from physical pages

- chapter 27 closes / chapter 28 begins on scan **247 / printed 243**;
- four-star internal transition at scan **251 / printed 247**;
- chapter 29 begins scan **254 / printed 250**;
- chapter 30 begins scan **262 / printed 258**;
- chapter 31 begins scan **271 / printed 267**;
- chapter 32 begins scan **278 / printed 274**;
- chapter 33 begins scan **288 / printed 284** and continues through scan **294 / printed 290**.

## Part 005 durable completion record

- canonical records: **49 / 49**
- verified: **42**
- needs-review: **7 — scans 215–219, 223–224**
- state: **`part-complete` with source-damage qualification**

Those seven damaged records remain `needs-review`; do not silently resolve them without stronger source evidence.

## Aggregate durable state

- canonical records: **260**
- verified: **253**
- needs-review: **7**
- partial: **0**
- clean contiguous fully verified range: through scan **214 / printed page 212**
- later individual source-verified pages: through scan **260**, except the seven damaged Part-005 records
- Parts 001–005: **part-complete at split level**
- Part 006: **in progress — 15 / 49 verified**
- assembled Tamil / English split-level review: through scan **245** only
- source scans represented by currently received derivatives: through **294**
- whole-work Tamil / English / release gates: not yet eligible

## Exact next activity

Continue Part 006 at **scan 261 / printed page 257**, chapter 29, using the supplied Iteration-25 first-pass baseline. First close scan 260's physical endpoint `வெள்ளியம்பலம்` from native scan-261 evidence. Apply the strengthened two-pass old-Tamil-typeform rule before accepting any disputed glyph or word spacing.