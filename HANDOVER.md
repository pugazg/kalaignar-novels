# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Current work: `works/pudhaiyal/`

## Authority rule

Native scans control page identity, punctuation, quotation marks, paragraph/section structure, physical boundaries, separators and chapter/scene transitions.

From scan **280 onward**, user-supplied Gemini transcription controls lexical words/forms. Part 007 uses `p7.md`; Part 008 uses `p8.md`. Complete source-visible lexical spans absent from the supplied baseline must be quarantined rather than silently inserted. Source/split PDFs and uploaded baseline files are never committed.

## Source identity — புதையல்

- author: கலைஞர் மு. கருணாநிதி, எம். எல். ஏ.
- publisher: அன்புப் பதிப்பகம், பொறையார் :: தஞ்சை மாவட்டம்
- edition: மூன்றாம் பதிப்பு — செப்டம்பர் 1961
- TDL bibliographic extent: **443 p.**
- exact full scan count / full-source SHA-256: pending

## Durable split state

- Parts 001–006: part-complete
- Part 007 scans 295–343: **part-complete**
- Part 008 scans 344–392: **49/49 canonical; scan 384 needs-review; Tamil audit reopened**

Part-005 source-damage qualification remains on scans **215–219 and 223–224**.

## Part 008 checkpoint

Derivative: `TVA_BOK_0064097_புதையல்_part_008_pages_344-392.pdf`

- 49 pages / scans **344–392** / printed **340–388**
- size **54,567,816 bytes**
- SHA-256 `717d3ab75eb970313062e1e61517d442cffa188f2fd8cadb8f75263b5e9a8852`
- `p8.md` SHA-256 `aad52bdfeae873459d561a52826f4787fd04f72ac1c27886212a1942d8e89ca2`
- canonical **49 / 49**
- verified **48 / 49**
- Part-008 needs-review **1 — scan 384 / printed 380**
- Tamil audit **REOPENED / BLOCKED**
- page map `works/pudhaiyal/indexes/part-008-page-map.md`
- Tamil audit `works/pudhaiyal/notes/part-008-tamil-audit.md`

### Missed lexical omission discovered during assembly

Native scan **384 / printed 380** contains complete phrase **`தகட்டில் இருக்கிறபடி`** between `எங்கும் ஓடிவிடாமல்!` and `அவளுக்கு ஒரு மாப்பிள்ளை...`. The controlling `p8.md` baseline omits it. The earlier canonical page had incorrectly source-filled the phrase; that insertion has been removed and scan 384 is now `needs-review` pending explicit user disposition.

The earlier Part-008 Tamil-audit PASS is withdrawn.

### Assembled Tamil progress

- Chapter 39 has been extended through scan 347, joining Part 007 `அதிர்ஷ்` + Part 008 `டம்` as **`அதிர்ஷ்டம்`**;
- assembled Chapters **40, 41, 42 and 43** are created;
- Chapter 43 preserves the native four-star transitions and closes on scan 376;
- Chapter 44 is gated because it contains scan 384;
- Chapter 45 and the assembled-Tamil consistency check remain pending behind the same gate.

Other structural findings remain valid: scan 381 has a structure-only paragraph relocation; scan 390 uses structure-only order `அதெல்லாம் எதற்கு வீண் கதை!`; scan 392 ends Chapter 45 open at `நமது`.

## Aggregate durable state

- canonical records: **392**
- verified/completed: **384**
- needs-review: **8 — Part 005 scans 215–219, 223–224 plus Part 008 scan 384**
- partial: **0**
- assembled Tamil: continuous through **Chapter 43 close on scan 376**
- source-checked/bilingual-reviewed English: through scan **343**
- received source coverage: through scan **392 / printed 388**
- whole-work gates: not eligible

## Exact next activity

Obtain explicit user disposition for scan 384 source phrase **`தகட்டில் இருக்கிறபடி`**. If authorized, restore it, mark scan 384 verified, rerun the Part-008 Tamil audit, finish assembled Chapters 44–45, run the Part-008 assembled-Tamil consistency check, and only then begin controlled English.
