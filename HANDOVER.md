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

## Completed derivatives

- Part 001 — scans 1–49 — **part-complete**
- Part 002 — scans 50–98 — **part-complete**
- Part 003 — scans 99–147 — **part-complete**
- Part 004 — scans 148–196 — **part-complete**

Assembled Tamil and English are part-reviewed continuously through scan 196.

## Active derivative — Part 005

Source: `TVA_BOK_0064097_புதையல்_part_005_pages_197-245.pdf`

- split pages: **49**
- records created: **197–228 — 32**
- verified: **25**
- needs-review: **7 — scans 215–219, 223–224**
- remaining: **229–245 — 17 not-started**
- Part-005 Tamil audit: not yet eligible
- Part-005 assembled Tamil / English: not started

Records:

- `works/pudhaiyal/indexes/part-005-page-map.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-197-216.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-217-228.md`

### Structure established

- chapter 22 closes on scan 205;
- chapter 23 begins on scan 206 and closes on scan 214;
- chapter 24 begins on scan 215 and closes on scan 225;
- chapter 25 begins on scan 226 and remains open after scan 228.

### Damaged / duplicated source pages

Physical source sequence around printed pages 214–215:

- scan 216 → printed 214
- scan 217 → printed 215
- scan 218 → printed 214 duplicate
- scan 219 → printed 215 duplicate

The duplicated witnesses repeat essentially the same repair/tape obstruction and do not source-resolve the hidden characters. All four later damaged scans remain explicit provenance records.

Additionally:

- scan 215 / printed 213 — repair/tape obstruction — `needs-review`;
- scan 223 / printed 219 — large right-side physical loss — `needs-review`;
- scan 224 / printed 220 — large left-side physical loss — `needs-review`.

Do not repair those readings from grammar or context.

### Iteration-20 source-confirmed forms

- scan 220: `அதுதான் இல்ல!`, `எனக்குக் கவலையில்ல!`
- scan 221: `அப்பா இறக்கவில்ல`, `பூச்சிடுகிறார்`
- scan 225: `கையிலே இல்ல`, `கையில்ல`, `கேட்கவில்ல`, `முடியவில்ல`
- scan 227: `மருங்கப்பள்ளம் கிராமம் தான்`
- scan 228: `புரியவில்ல`; treasure clue retained as a separate multi-line source unit

## Aggregate durable state

- canonical records: **228**
- verified: **221**
- needs-review: **7**
- partial: **0**
- clean verified range remains continuous through scan **214 / printed 212**
- Parts 001–004: part-complete
- Part 005: in progress
- whole-work Tamil / English / release gates: not yet eligible

## Exact next activity

Resume canonical transcription from **scan 229 / printed page 225 / Part-005 split page 33**.

Scan 228 physically ends at `‘கள்வர் புகும்`; scan 229 visibly continues `வழியிலே’`. Establish that continuation from the native scan before proceeding through the next baseline batch.

Do not start Part-005 translation until all 49 physical scans have canonical records and the Part-005 Tamil audit is eligible.
