# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Current work: `works/pudhaiyal/`

## Authority rule

Native scans control page identity, punctuation, quotation marks, paragraph/section structure, physical boundaries, separators and chapter/scene transitions.

From scan **280 onward**, user-supplied Gemini transcription controls lexical words/forms. Part 007 uses `p7.md`; Part 008 uses `p8.md`. Complete source-visible lexical spans absent from the supplied baseline require explicit disposition rather than silent insertion. Source/split PDFs and uploaded baseline files are never committed.

## Source identity — புதையல்

- author: கலைஞர் மு. கருணாநிதி, எம். எல். ஏ.
- publisher: அன்புப் பதிப்பகம், பொறையார் :: தஞ்சை மாவட்டம்
- edition: மூன்றாம் பதிப்பு — செப்டம்பர் 1961
- TDL bibliographic extent: **443 p.**
- exact full scan count / full-source SHA-256: pending

## Durable split state

- Parts 001–006: part-complete
- Part 007 scans 295–343: **part-complete**
- Part 008 scans 344–392: **part-complete**

Part-005 source-damage qualification remains on scans **215–219 and 223–224**.

## Part 008 checkpoint

Derivative: `TVA_BOK_0064097_புதையல்_part_008_pages_344-392.pdf`

- 49 pages / scans **344–392** / printed **340–388**
- canonical **49 / 49**
- verified **49 / 49**
- Part-008 needs-review **0**
- Tamil audit **PASSED**
- assembled Tamil audit **PASSED**
- controlled English translation **COMPLETE**
- controlled English source check **PASSED** — `works/pudhaiyal/translations/en/PART_008_ENGLISH_CHECK.md`
- bilingual review **PASSED** — `works/pudhaiyal/translations/en/PART_008_REVIEW.md`
- split state **`part-complete`**

### User-authorized scan-384 restoration

Native scan **384 / printed 380** contains complete phrase **`தகட்டில் இருக்கிறபடி`**, absent from `p8.md`. The user explicitly authorized its restoration on 2026-09-02. English Chapter 44 represents it exactly once as **“as the plate says.”** This is a narrow restoration only.

### Part-008 English result

- `works/pudhaiyal/translations/en/sections/checkpoints/part-008-chapter-39-continuation.md` — scans **344–347**, source-checked and bilingual-reviewed; reviewed Part-007 `luc` + Part-008 `k` forms **luck** and Chapter 39 closes on scan 347;
- Chapters **40–44** — source-checked and bilingual-reviewed;
- Chapter **45** — source-checked and bilingual-reviewed through scan 392 and deliberately open at English **“our”**, corresponding to Tamil `நமது`.

The Part-008 English source check made four English-only corrections and no Tamil changes: explicit `சாயபுக்கு` → **“to Saibu”** in Chapter 39; Chapter 42 kiss reciprocity → **“in return he received just as many kisses from her”**; Chapter 44 `உசிருக்கு உசிரு` → **“each other's very life”**; and the disguise reveal wording → **“the clothes of her disguise.”**

The bilingual review made two further English-only fidelity refinements: Chapter 41 `ஜாடையாகத் திரும்பிப் பார்த்துவிட்டு` → **“cast a discreet glance back”** and Chapter 45 `பெரிய ஜெயிலில் பெரிய ஆட்கள்` → **“The big jail had all sorts of big shots.”** No Tamil changed.

Structural fidelity remains intact: native four-star transitions are retained, the scan-381 structure-only relocation is inherited from assembled Tamil, scan 390 preserves `அதெல்லாம் எதற்கு வீண் கதை!` ordering, and the scan-392 derivative boundary is not promoted into a chapter or novel ending.

## Aggregate durable state

- canonical records: **392**
- verified/completed: **385**
- needs-review: **7 — only Part 005 scans 215–219 and 223–224**
- partial: **0**
- assembled Tamil: continuous through **scan 392 / printed 388**
- source-checked English: continuous through **scan 392 / printed 388**
- bilingual-reviewed English: continuous through **scan 392 / printed 388**
- received source coverage: through scan **392 / printed 388**
- Parts 001–008: **part-complete**
- whole-work gates: not eligible

## Exact next activity

Obtain or resolve the **next source derivative beyond scan 392**. Before creating any new canonical record, verify the actual first new source page against the open scan-392 `நமது` boundary and establish the real source-scan / printed-page mapping from that material. Do not infer the continuation word, Chapter-45 ending, next part range, source ending or back matter without the source.
