# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Current work: `works/pudhaiyal/`

## Authority rule

Native scans control page identity, punctuation, quotation marks, paragraph/section structure, physical boundaries, separators and chapter/scene transitions.

From scan **280 onward**, user-supplied Gemini transcription controls lexical words/forms. Part 007 uses `p7.md`; Part 008 uses `p8.md`. Source/split PDFs and uploaded baseline files are never committed.

## Source identity — புதையல்

- author: கலைஞர் மு. கருணாநிதி, எம். எல். ஏ.
- publisher: அன்புப் பதிப்பகம், பொறையார் :: தஞ்சை மாவட்டம்
- edition: மூன்றாம் பதிப்பு — செப்டம்பர் 1961
- TDL bibliographic extent: **443 p.**
- exact full scan count / full-source SHA-256: pending

## Durable split state

- Parts 001–006: part-complete
- Part 007 scans 295–343: **part-complete**
- Part 008 scans 344–392: **Tamil audit PASSED / assembled Tamil next**

Part-005 source-damage qualification remains on scans **215–219 and 223–224**.

## Part 008 checkpoint

Derivative: `TVA_BOK_0064097_புதையல்_part_008_pages_344-392.pdf`

- 49 pages / scans **344–392** / printed **340–388**
- size **54,567,816 bytes**
- SHA-256 `717d3ab75eb970313062e1e61517d442cffa188f2fd8cadb8f75263b5e9a8852`
- `p8.md` SHA-256 `aad52bdfeae873459d561a52826f4787fd04f72ac1c27886212a1942d8e89ca2`
- canonical **49 / 49**
- verified **49 / 49**
- Part-008 needs-review **0**
- Tamil audit **PASSED**
- page map `works/pudhaiyal/indexes/part-008-page-map.md`
- fidelity `works/pudhaiyal/notes/visual-fidelity-scans-344-392.md`
- Tamil audit `works/pudhaiyal/notes/part-008-tamil-audit.md`

### Proven structural progression

- Part 007→008: `அதிர்ஷ்` + `டம்` → **`அதிர்ஷ்டம்`**;
- Chapter 39 closes scan 347;
- Chapter 40 begins 348;
- Chapter 41 begins 355;
- Chapter 42 begins 362;
- Chapter 43 begins 369;
- Chapter 44 begins 376;
- Chapter 45 begins 387 and remains open through scan 392;
- native four-star transitions include scans 372, 373 and 381;
- scan 381 uses a structure-only paragraph relocation;
- scan 390 uses structure-only order `அதெல்லாம் எதற்கு வீண் கதை!`;
- scan 392 ends open at **`நமது`**.

No complete Part-008 `p8.md` lexical omission was found.

## Aggregate durable state

- canonical records: **392**
- verified/completed: **385**
- needs-review: **7 — only Part 005 scans 215–219 and 223–224**
- partial: **0**
- assembled Tamil: through scan **343**
- source-checked/bilingual-reviewed English: through scan **343**
- received source coverage: through scan **392 / printed 388**
- whole-work gates: not eligible

## Exact next activity

Build and consistency-check the **Part-008 assembled Tamil reading layer** from audited scans **344–392**. Continue Chapter 39 across the Part-007 boundary, assemble Chapters 40–45, preserve all audited internal transitions/joins, and leave Chapter 45 open at `நமது`. Only after assembled Tamil passes should controlled English begin.
