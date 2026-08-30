# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Current work: `works/pudhaiyal/`

## Permanent source rule

The scan is the textual authority. User-supplied transcription is the comparison baseline. Do not modernize or infer unclear Tamil. Assistant-introduced changes must be established from native pixels. If damage/repair hides letters, retain the baseline and `needs-review` rather than claiming verification.

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

A physically damaged source may receive an explicit source-damage disposition at the part Tamil gate. Such scans remain `needs-review`; the exception permits continued split workflow but does not turn missing pixels into verified text.

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
- canonical records: **4 / 49 — scans 246–249**
- verified: **4**
- needs-review: **0**
- not-started: **45 — scans 250–294**
- fidelity record: `works/pudhaiyal/notes/visual-fidelity-scans-246-249.md`
- Tamil audit / assembled Tamil / English / bilingual review: **not yet eligible**
- Part-006 state: **`in-progress`**

### Mandatory 245→246 continuity finding

Part 005 scan **245 / printed 241** ends:

`இருக்கவே`

Part 006 scan **246 / printed 242** begins:

`இருக்கிறாள் பரிமளா, அவள் சொல்லட்டும், இது யாருடைய கை என்று!”`

Native evidence establishes one continuous sentence:

`இருக்கவே இருக்கிறாள் பரிமளா, ...`

Do not normalize the repetition or insert a split boundary.

### Iteration-23 completion — scans 246–249

All four supplied baseline pages are directly source-verified.

Important source corrections/retentions:

- scan 246: `தெரியவில்ல`, not baseline `தெரியவில்லை`;
- scan 246: `தாளவில்ல`, not baseline `தாளவில்லை`;
- scan 246: `அந்த இருட்டிலே —`, not `அந்த இருட்டில-`;
- scan 247: baseline `ராஜா மடம் என்ற ஊருக்கும்` is confirmed;
- 247→248: `இன்` + `னும்` = `இன்னும்`;
- scan 248: `புரியவில்ல`, not baseline `புரியவில்லை`;
- scan 248: `திரும்பி வரவில்ல`, not baseline `திரும்பி வரவில்லை`;
- 248→249: `அவ` + `தாரம்` = `அவதாரம்`;
- scan 249 preserves `ஒருவரை யொருவர்`, `செய்ய வில்லையே`, `முடிய வில்லையே`, `புண்யங்கூட`, `யானையுமாக வெல்லாம்`.

### Part-006 structure mapped from physical pages

- chapter 27 closes / chapter 28 begins on scan **247 / printed 243**;
- chapter 29 begins scan **254 / printed 250**;
- chapter 30 begins scan **262 / printed 258**;
- chapter 31 begins scan **271 / printed 267**;
- chapter 32 begins scan **278 / printed 274**;
- chapter 33 begins scan **288 / printed 284** and continues through scan **294 / printed 290**.

These later pages are mapped structurally only; scans 250–294 remain `not-started` until direct textual reconciliation.

## Part 005 durable completion record

- split pages / canonical records: **49 / 49 — scans 197–245**
- verified: **42**
- needs-review: **7 — scans 215–219, 223–224**
- Tamil audit: **closed with explicit source-damage exceptions**
- assembled Tamil: **completed / part-reviewed**
- controlled English: **completed / source-checked**
- bilingual review: `works/pudhaiyal/translations/en/PART_005_REVIEW.md` — **PASSED WITH SOURCE-DAMAGE QUALIFICATION**
- state: **`part-complete`**

The seven damaged records remain `needs-review`; do not reopen or silently resolve them without genuinely stronger source evidence.

## Aggregate durable state

- canonical records: **249**
- verified: **242**
- needs-review: **7**
- partial: **0**
- clean contiguous fully verified range: through scan **214 / printed page 212**
- later individual source-verified pages: through scan **249**, except the seven damaged records
- Parts 001–005: **part-complete at split level**
- Part 006: **in progress — 4 / 49 verified**
- assembled Tamil / English split-level review: through scan **245** only
- source scans represented by currently received derivatives: through **294**
- whole-work Tamil / English / release gates: not yet eligible

## Exact next activity

Continue Part 006 at **scan 250 / printed page 246** using the next user-supplied transcription baseline. Reconcile every reading directly from native source pixels, preserve physical page boundaries, report material discrepancies, and keep the Part-006 downstream gates closed until scans 246–294 are all canonically dispositioned.