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
- Part 008 scans 344–392: **Tamil audit PASSED + assembled Tamil PASSED + controlled English draft COMPLETE / source check next**

Part-005 source-damage qualification remains on scans **215–219 and 223–224**.

## Part 008 checkpoint

Derivative: `TVA_BOK_0064097_புதையல்_part_008_pages_344-392.pdf`

- 49 pages / scans **344–392** / printed **340–388**
- canonical **49 / 49**
- verified **49 / 49**
- Part-008 needs-review **0**
- Tamil audit **PASSED**
- assembled Tamil audit **PASSED**
- controlled English draft **COMPLETE**
- controlled English source check **PENDING**
- bilingual review **BLOCKED until source check passes**

### User-authorized scan-384 restoration

Native scan **384 / printed 380** contains complete phrase **`தகட்டில் இருக்கிறபடி`**, absent from `p8.md`. The user explicitly authorized its restoration on 2026-09-02. English Chapter 44 represents it exactly once as **“as the plate says.”** This is a narrow restoration only.

### Part-008 English inventory

- `works/pudhaiyal/translations/en/sections/checkpoints/part-008-chapter-39-continuation.md` — scans **344–347**, completing Part-007 English `luc` + Part-008 `k` as **luck** and closing Chapter 39;
- `sections/40-chapter-40.md` — draft translated;
- `sections/41-chapter-41.md` — draft translated;
- `sections/42-chapter-42.md` — draft translated;
- `sections/43-chapter-43.md` — draft translated;
- `sections/44-chapter-44.md` — draft translated, including authorized scan-384 restoration;
- `sections/45-chapter-45.md` — draft translated through scan 392 and deliberately open at English **“our”**, corresponding to Tamil `நமது`.

The Part-007 Chapter-39 file remains untouched as the reviewed Part-007 witness ending at `luc`; the Part-008 checkpoint follows the established cross-split translation convention and begins with the completing `k`.

## Aggregate durable state

- canonical records: **392**
- verified/completed: **385**
- needs-review: **7 — only Part 005 scans 215–219 and 223–224**
- partial: **0**
- assembled Tamil: continuous through **scan 392 / printed 388**
- controlled English draft: continuous through **scan 392 / printed 388**
- source-checked/bilingual-reviewed English: through scan **343**
- received source coverage: through scan **392 / printed 388**
- whole-work gates: not eligible

## Exact next activity

Run the **Part-008 controlled English source check across scans 344–392**. Compare the English checkpoint and Chapters 40–45 against the audited canonical/assembled Tamil for complete semantic coverage, dialogue order, names/terms, humour, violence, romance, native internal transitions, the authorized scan-384 restoration and the open scan-392 endpoint. Correct English-only fidelity issues as needed. Only after that source check passes may the Part-008 bilingual review begin.
