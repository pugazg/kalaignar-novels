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

Assembled Tamil and English are part-reviewed continuously through scan 196.

## Active derivative — Part 005

Source: `TVA_BOK_0064097_புதையல்_part_005_pages_197-245.pdf`

- split pages / canonical records: **49 / 49 — scans 197–245**
- verified: **42**
- needs-review: **7 — scans 215–219, 223–224**
- not-started inside derivative: **0**
- Part-005 Tamil audit: **closed with explicit source-damage exceptions**
- Part-005 assembled Tamil / English: **not yet completed**

Records:

- `works/pudhaiyal/indexes/part-005-page-map.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-197-216.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-217-228.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-229-238.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-239-245.md`
- `works/pudhaiyal/notes/part-005-tamil-audit.md`

### Structure established

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

Do not close any of these seven uncertainties by context or grammar.

### Iteration 22 source results

Scans **239–245 / printed pages 235–241**: **7 / 7 verified**.

Important source-confirmed corrections include:

- `தன் ஆசை அத்தான்`, not baseline `தன் ஆசை அத்தானை`;
- scan 239→240 `என்ன செய்` + `தானே?`;
- `தன் இதழ்கள்`, not `தன் இதழ்களை`;
- `போலீசாரே உதவிக்கு வந்து`, not `வந்தது`;
- `புரியவில்ல`, `புரிய வில்ல`, `காணப்படவில்ல`;
- `ஒரு புதுவழி`;
- `கேட்டார்கள்`, not baseline `கெட்டார்கள்`;
- `சந்திக்கும்போதெல்லாம்`, `நிமிஷங்கூட ஆகவில்ல`;
- `யோசனைகளைச்`, not baseline `யோகனைகளை`;
- `விடவில்ல`, `தேவையில்ல`;
- `இப்போது நான்`, not baseline `இப்போதே நான்`.

Important physical joins:

- scan 228 `‘கள்வர் புகும்` + scan 229 `வழியிலே’`;
- scan 230 `அவன் கண்` + scan 231 `கள்` = `அவன் கண்கள்`;
- scan 235 `அமைந்` + scan 236 `திருந்தன.` = `அமைந்திருந்தன.`;
- scan 237 `அந்தப் பிடியி` + scan 238 `லிருந்து` = `அந்தப் பிடியிலிருந்து`;
- scan 239 `என்ன செய்` + scan 240 `தானே?`;
- scan 243 `அங்கே` + scan 244 `அடர்ந்திருக்கும்`.

## Aggregate durable state

- canonical records: **245**
- verified: **238**
- needs-review: **7**
- partial: **0**
- clean contiguous fully verified range: through scan **214 / printed page 212**
- later individual source-verified pages: through scan **245**, except the seven damaged records
- Parts 001–004: part-complete
- Part 005: canonical/native fidelity complete; Tamil audit source-damage-closed; assembled/English pending
- whole-work Tamil / English / release gates: not yet eligible

## Exact next activity

Build the **Part-005 assembled Tamil** from scans **197–245**, preserving the seven source-damage qualifications and the open scan-245 boundary at `இருக்கவே`.

After that, complete the controlled English translation, English source-check and Part-005 bilingual review before marking this derivative `part-complete`. Do not start a later split before Part 005's split workflow is complete.
