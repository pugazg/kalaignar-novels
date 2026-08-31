# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Current work: `works/pudhaiyal/`

## Permanent source rule

The scan is the textual authority. User-supplied transcription is the comparison baseline. Do not modernize or infer unclear Tamil. Assistant-introduced changes must be established from native pixels. If damage/repair hides letters, retain the baseline and `needs-review` rather than claiming verification.

### Mandatory old-Tamil-glyph pre-correction check

The safeguard applies to **all Tamil vowel signs / combining marks**. Demonstrated hazards include faint final `லை`, faint `ா`, and `ே` / `ோ` distinctions. A proposed baseline change involving an old/faint vowel sign, near-identical same-word glyph, or apparent spacing produced by a printed line wrap requires a second independent high-resolution pass before acceptance. A printed line break alone never establishes word-internal spacing.

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
- canonical records: **30 / 49 — scans 246–275**
- verified: **30**
- needs-review: **0**
- not-started: **19 — scans 276–294**
- latest fidelity record: `works/pudhaiyal/notes/visual-fidelity-scan-275.md`
- Tamil audit / assembled Tamil / English / bilingual review: **not yet eligible**
- Part-006 state: **`in-progress`**

### Current verified source sequence

Scan **275 / printed 271** is source-verified:

- opening dialogue is `இல்லை; துரை தான்!` and preserves the source pauses `கிழவருந்தான்...... என்னை ...... என்னை ......`;
- native source order is **`அம்பலம் விடுவாரா? மிச்சமிருக்கிற உயிரையும் தேடித் தோண்டி...`**; the baseline's reordering is not source-supported and was not propagated;
- physical wraps `நிறுத்` / `திப்` and `விடா` / `திங்க` are joined as `நிறுத்திப்` and `விடாதிங்க`;
- source prints `மூடிக் கொண்டான்` separated and `தொட்டுப் பார்த்தார் — உதட்டைப் பிதுக்கினார்.`;
- second old-type pass confirms complete `முடியவில்லை`, `புரியவில்லை`, `வாயையும்`, `கண்களையும்`, `தன்னுடைய`, and `கிழவரையும்`;
- scan 275 ends mid-sentence at **`துரை`**; scan 276 must continue it.

### Part-006 structure mapped from physical pages

- chapter 27 closes / chapter 28 begins scan **247**;
- four-star internal transition scan **251**;
- chapter 29 begins scan **254** and closes scan **262**;
- chapter 30 begins scan **262** and closes scan **271**;
- chapter 31 begins scan **271**;
- chapter 32 begins scan **278**;
- chapter 33 begins scan **288** and continues through scan **294**.

## Aggregate durable state

- canonical records: **275**
- verified: **268**
- needs-review: **7 — scans 215–219, 223–224**
- partial: **0**
- clean contiguous fully verified range: through scan **214 / printed page 212**
- later individual source-verified pages: through scan **275**, except the seven damaged Part-005 records
- Parts 001–005: **part-complete at split level**
- Part 006: **in progress — 30 / 49 verified**
- assembled Tamil / English split-level review: through scan **245** only
- source scans represented by currently received derivatives: through **294**
- whole-work Tamil / English / release gates: not yet eligible

## Exact next activity

Continue Part 006 at **scan 276 / printed page 272**, chapter 31. First continue scan 275's open `துரை...` sentence. Apply the strengthened two-pass old-Tamil-typeform rule to all vowel signs and printed-line-wrap questions before accepting any disputed glyph or spacing.