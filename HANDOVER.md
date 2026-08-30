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

This is **not** a global normalization rule. Source-specific forms such as scan 229 `தீண்ட வில்லையே` and scan 244's first `தெரியவில்லையே` remain unchanged when their native pixels support them. If pixels are ambiguous, retain the baseline and `needs-review`.

The same safeguard is now repeated in `NEXT_NOVEL_CHAT_PROMPT.md` so future fresh-chat onboarding cannot skip it.

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
- Part 003 — scans 99–147 — **part-complete; scan 120 old-glyph correction re-synchronized**
- Part 004 — scans 148–196 — **part-complete**
- Part 005 — scans 197–245 — **part-complete with explicit source-damage qualification; readable-page old-glyph corrections re-synchronized**

Assembled Tamil and controlled English remain split-level reviewed continuously through scan **245**, with Part-005 source-damage qualifications preserved.

## Retrospective old-glyph repair — completed 2026-08-30

Native high-resolution reinspection established earlier assistant `லை`-loss errors on **23 readable scans**:

- Part 003: scan **120**;
- Part 005: scans **198, 199, 201, 207, 214, 220, 221, 225, 228, 229, 230, 231, 233, 234, 235, 238, 239, 241, 242, 243, 244, 245**.

Canonical page records were corrected and assembled Tamil chapters **13 and 22–27** were re-synchronized. Fidelity and Tamil-audit records were also corrected. The English meaning is unchanged by restoring the missed final `லை`, but bilingual-review documentation now uses the corrected Tamil authority.

The seven physically damaged Part-005 records **215–219 and 223–224** remain `needs-review`; the glyph discovery does not license reconstruction of hidden pixels.

## Active derivative — Part 006

Source: `TVA_BOK_0064097_புதையல்_part_006_pages_246-294.pdf`

- physical pages: **49**
- source scans: **246–294**
- visible printed pages: **242–290**
- derivative size: **57,056,182 bytes**
- derivative SHA-256: `34a5ea5eb91a71ca8674760257779eb4ed6bdc6640517f8830b9ee70aa34aec7`
- derivative map: `works/pudhaiyal/indexes/part-006-page-map.md`
- canonical records: **5 / 49 — scans 246–250**
- verified: **5**
- needs-review: **0**
- not-started: **44 — scans 251–294**
- fidelity records: `works/pudhaiyal/notes/visual-fidelity-scans-246-249.md`, `works/pudhaiyal/notes/visual-fidelity-scan-250.md`
- old-glyph correction record: `works/pudhaiyal/notes/old-glyph-correction-scans-246-248.md`
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

### Verified Part-006 text through scan 250

Scans 246–249 were reconciled against the supplied Iteration-23 baseline.

Important source findings/retentions:

- scan 246: baseline `தெரியவில்லை` is **confirmed** after high-resolution reinspection;
- scan 246: baseline `தாளவில்லை` is **confirmed** after high-resolution reinspection;
- scan 246: source `அந்த இருட்டிலே —`, not baseline `அந்த இருட்டில-`;
- scan 247: baseline `ராஜா மடம் என்ற ஊருக்கும்` is confirmed;
- 247→248: `இன்` + `னும்` = `இன்னும்`;
- scan 248: baseline `புரியவில்லை` is **confirmed**;
- scan 248: baseline `திரும்பி வரவில்லை` is **confirmed**;
- 248→249: `அவ` + `தாரம்` = `அவதாரம்`;
- scan 249 confirms baseline `ஒருவரையொருவர்`, `செய்யவில்லையே`, `முடியவில்லையே`; their printed line wraps are not word boundaries;
- scan 249 preserves source `புண்யங்கூட` and `யானையுமாக வெல்லாம்`.

Scan **250 / printed 246** was transcribed directly from the native derivative at high resolution with **no user baseline**. It continues the Dukkaram–Raman dialogue and is `verified`. Source-specific forms retained include:

- `கறு கண்ணை`;
- `கிடக்கிறாரு`;
- `வைத்தியனிடமில்லே`;
- `உன் கிட்டம்தான்`;
- `அப்படின்னு`;
- `கொடுன்னு`;
- `பெண்ணு`;
- `சந்திக்கணும்னு`;
- `துடிக்குது`.

The permanent old-Tamil-typeform pre-correction check was applied. No unresolved glyph remains on scan 250.

### Part-006 structure mapped from physical pages

- chapter 27 closes / chapter 28 begins on scan **247 / printed 243**;
- chapter 29 begins scan **254 / printed 250**;
- chapter 30 begins scan **262 / printed 258**;
- chapter 31 begins scan **271 / printed 267**;
- chapter 32 begins scan **278 / printed 274**;
- chapter 33 begins scan **288 / printed 284** and continues through scan **294 / printed 290**.

These later pages are mapped structurally only; scans 251–294 remain `not-started` until direct textual reconciliation.

## Part 005 durable completion record

- split pages / canonical records: **49 / 49 — scans 197–245**
- verified: **42**
- needs-review: **7 — scans 215–219, 223–224**
- Tamil audit: **closed with explicit source-damage exceptions and retrospective old-glyph reinspection on readable pages**
- assembled Tamil: **completed / re-synchronized / part-reviewed**
- controlled English: **completed / source-checked; no semantic rewrite required by glyph restoration**
- bilingual review: `works/pudhaiyal/translations/en/PART_005_REVIEW.md` — **PASSED WITH SOURCE-DAMAGE QUALIFICATION**
- state: **`part-complete`**

The seven damaged records remain `needs-review`; do not reopen or silently resolve them without genuinely stronger source evidence.

## Aggregate durable state

- canonical records: **250**
- verified: **243**
- needs-review: **7**
- partial: **0**
- clean contiguous fully verified range: through scan **214 / printed page 212**
- later individual source-verified pages: through scan **250**, except the seven damaged records
- Parts 001–005: **part-complete at split level**
- Part 006: **in progress — 5 / 49 verified**
- assembled Tamil / English split-level review: through scan **245** only
- source scans represented by currently received derivatives: through **294**
- whole-work Tamil / English / release gates: not yet eligible

## Exact next activity

Continue Part 006 at **scan 251 / printed page 247**, chapter 28. Transcribe directly from native source pixels, preserve physical page boundaries, and apply the permanent old-Tamil-typeform pre-correction check before accepting any disputed glyph. Keep the Part-006 downstream gates closed until scans 246–294 are all canonically dispositioned.