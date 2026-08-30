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

For each supplied derivative: canonical pages → native fidelity → resolve/retain uncertainty → part Tamil audit → assembled Tamil → English → bilingual review → status synchronization → `part-complete`.

Split boundaries are provenance only.

A physically damaged source may receive an explicit source-damage disposition at the part Tamil gate. Such scans remain `needs-review`; the exception permits continued split workflow but does not turn missing pixels into verified text.

## Completed derivatives

- Part 001 — scans 1–49 — **part-complete**
- Part 002 — scans 50–98 — **part-complete**
- Part 003 — scans 99–147 — **part-complete**
- Part 004 — scans 148–196 — **part-complete**
- Part 005 — scans 197–245 — **part-complete with explicit source-damage qualification**

Assembled Tamil and controlled English are split-level reviewed continuously through scan **245**, with Part-005 source-damage qualifications preserved.

## Part 005 durable completion record

Source: `TVA_BOK_0064097_புதையல்_part_005_pages_197-245.pdf`

- split pages / canonical records: **49 / 49 — scans 197–245**
- verified: **42**
- needs-review: **7 — scans 215–219, 223–224**
- not-started inside derivative: **0**
- Part-005 Tamil audit: **closed with explicit source-damage exceptions**
- assembled Tamil: **completed / part-reviewed**
- controlled English: **completed / source-checked**
- bilingual review: `works/pudhaiyal/translations/en/PART_005_REVIEW.md` — **PASSED WITH SOURCE-DAMAGE QUALIFICATION**
- Part-005 state: **`part-complete`**

Records:

- `works/pudhaiyal/indexes/part-005-page-map.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-197-216.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-217-228.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-229-238.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-239-245.md`
- `works/pudhaiyal/notes/part-005-tamil-audit.md`
- `works/pudhaiyal/translations/en/PART_005_REVIEW.md`

### Structure through the known source

- chapter 22 closes on scan 205;
- chapter 23 begins 206 / closes 214;
- chapter 24 begins 215 / closes 225;
- chapter 25 begins 226 / closes 235;
- chapter 26 begins 235 / closes 240;
- chapter **27** begins scan 241 and continues beyond Part 005;
- scan **245 / printed 241** ends mid-sentence at `இருக்கவே`.

### Damaged-page constraint

Scans **215–219** are crossed by repair/tape obstruction. The derivative repeats printed pages 214–215, but the duplicate witnesses do not reveal enough additional letters to close the obscured readings.

Scans **223–224 / printed pages 219–220** have substantial physical tear/loss. User baseline text is retained where necessary, but these pages remain `needs-review`.

Do not close any of these seven uncertainties by context or grammar. Part completion does not upgrade them to `verified`.

### Important continuity joins in Part 005

- 196→197: chapter 22 continues across the split boundary;
- 204→205: `குதூகலமு` + `மாக` = `குதூகலமுமாக`;
- 206→207: `என்று தனக்குத் தானே` + `வருத்தப்பட்டுக்கொண்டான் துரை.`;
- 208→209: `வெளி` + `யிலே` = `வெளியிலே`;
- 212→213: `அவனிடம்` + `பெற்ற பாடம்`;
- 227→228: `சிறு` + `கல்லும்` = `சிறு கல்லும்`;
- 228→229: `‘கள்வர் புகும்` + `வழியிலே’`;
- 230→231: `அவன் கண்` + `கள்` = `அவன் கண்கள்`;
- 235→236: `அமைந்` + `திருந்தன.` = `அமைந்திருந்தன.`;
- 237→238: `அந்தப் பிடியி` + `லிருந்து` = `அந்தப் பிடியிலிருந்து`;
- 239→240: `என்ன செய்` + `தானே?`;
- 243→244: `அங்கே` + `அடர்ந்திருக்கும்`.

## Aggregate durable state

- canonical records: **245**
- verified: **238**
- needs-review: **7**
- partial: **0**
- clean contiguous fully verified range: through scan **214 / printed page 212**
- later individual source-verified pages: through scan **245**, except the seven damaged records
- Parts 001–005: **part-complete at split level**
- assembled Tamil / English split-level review: through scan **245**, carrying the seven source-damage qualifications
- whole-work Tamil / English / release gates: not yet eligible
- source coverage beyond scan 245: not yet available in repository

## Exact next activity

Obtain / attach the next Pudhaiyal source derivative beginning at **scan 246 / printed page 242**.

Resume chapter 27 directly from the open scan-245 endpoint `இருக்கவே` using the next user-supplied baseline plus native source verification. Do not infer the continuation from grammar, context or outside editions. Do not start whole-work verification until the complete source extent and true ending/back matter are known.
