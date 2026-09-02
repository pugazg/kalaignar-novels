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
- Part 008 scans 344–392: **Tamil audit PASSED + assembled Tamil PASSED / controlled English next**

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
- assembled Tamil audit **PASSED**
- page map `works/pudhaiyal/indexes/part-008-page-map.md`
- Tamil audit `works/pudhaiyal/notes/part-008-tamil-audit.md`
- assembled Tamil audit `works/pudhaiyal/notes/part-008-assembled-tamil-audit.md`

### User-authorized scan-384 restoration

Native scan **384 / printed 380** contains complete phrase **`தகட்டில் இருக்கிறபடி`** between `எங்கும் ஓடிவிடாமல்!` and `அவளுக்கு ஒரு மாப்பிள்ளை...`. The controlling `p8.md` baseline omits it.

On 2026-09-02 the user explicitly authorized insertion of **`தகட்டில் இருக்கிறபடி`**. It is restored narrowly in canonical scan 384, which is `verified`. This does not broaden source-correction authority beyond that documented omission.

### Assembled Tamil result

- Chapter 39 extends through scan 347 and joins Part 007 `அதிர்ஷ்` + Part 008 `டம்` as **`அதிர்ஷ்டம்`**;
- assembled Chapters **40–45** are complete through the received source endpoint;
- Chapters 43 and 44 preserve the audited native four-star transitions;
- Chapter 44 includes `தகட்டில் இருக்கிறபடி` exactly once;
- scan 381 retains the structure-only paragraph relocation;
- scan 390 retains structure-only order `அதெல்லாம் எதற்கு வீண் கதை!`;
- Chapter 45 remains open at scan 392 **`நமது`**;
- Part-008 assembled-Tamil consistency check **PASSED**.

## Aggregate durable state

- canonical records: **392**
- verified/completed: **385**
- needs-review: **7 — only Part 005 scans 215–219 and 223–224**
- partial: **0**
- assembled Tamil: continuous through **scan 392 / printed 388**
- source-checked/bilingual-reviewed English: through scan **343**
- received source coverage: through scan **392 / printed 388**
- whole-work gates: not eligible

## Exact next activity

Begin **controlled English translation for Part 008 scans 344–392** from assembled Tamil Chapters **39–45**. Preserve every established structural transition and leave the Chapter-45 English text open at the source endpoint corresponding to `நமது`. Do not infer any continuation beyond scan 392.
