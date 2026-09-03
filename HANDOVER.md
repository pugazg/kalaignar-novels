# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Current work: `works/pudhaiyal/`

## Authority rule

Native scans control page identity, punctuation, quotation marks, paragraph/section structure, physical boundaries, separators, chapter transitions, narrative ending and back matter.

From scan **280 onward**, user-supplied Gemini transcription controls lexical words/forms/spacing:

- Part 007 — `p7.md`
- Part 008 — `p8.md`
- Part 009 — `p9.md`
- Part 010 — `p10.md`

Complete source-visible lexical spans absent from the baseline require explicit user disposition rather than silent insertion. Source/split PDFs and uploaded baseline files are never committed.

## Source identity — புதையல்

- author: கலைஞர் மு. கருணாநிதி, எம். எல். ஏ.
- publisher: அன்புப் பதிப்பகம், பொறையார் :: தஞ்சை மாவட்டம்
- edition: மூன்றாம் பதிப்பு — செப்டம்பர் 1961
- TDL bibliographic extent: **443 p.**
- exact original full-file byte/SHA reconciliation remains separate from the split-derivative workflow

## Durable split state

- Parts 001–009: **part-complete**
- Part 009 / scans **393–441 / printed 389–437**: **Tamil audit PASSED + assembled Tamil PASSED + controlled English source check PASSED + bilingual review PASSED / part-complete**
- Part 010 / scans **442–448**: **Tamil audit PASSED + assembled Tamil PASSED; English pending**
- Part-005 source-damage qualification remains on scans **215–219 and 223–224**.

Part 009 records:

- `works/pudhaiyal/notes/part-009-tamil-audit.md`
- `works/pudhaiyal/notes/part-009-assembled-tamil-check.md`
- `works/pudhaiyal/translations/en/PART_009_ENGLISH_CHECK.md`
- `works/pudhaiyal/translations/en/PART_009_REVIEW.md`
- result: **49 / 49 verified, 0 Part-009 needs-review**
- English source check: **PASSED with one English-only Chapter-46 ritual-oath fidelity correction**
- bilingual review: **PASSED with no additional English changes required**
- no complete `p9.md` lexical omission found
- baseline-only structure marks rejected: `⚬` scan 416; `*` scan 435

Part 010 records:

- `works/pudhaiyal/notes/part-010-tamil-audit.md`
- `works/pudhaiyal/notes/part-010-assembled-tamil-check.md`
- result: **7 / 7 verified, 0 Part-010 needs-review**
- scan 445 native `விடு`, omitted from `p10.md`, was explicitly authorized by the user on 2026-09-03 and restored narrowly

Verified source/reading boundaries:

- Part 008→009: `நமது` + `வாழ்க்கையை` → **`நமது வாழ்க்கையை`**;
- Part 009→010: `அம்ப` + `லமே` → **`அம்பலமே`**;
- scan **447 / printed 443**: actual narrative ending;
- scan **448**: separate printer colophon `அன்பு அச்சகம், பொறையார்.`

## Assembled Tamil frontier

- Chapter 45 continues through its close in Part 009.
- Chapters **46–50** are assembled from audited Part-009 pages.
- Chapter **51** is assembled continuously across Parts 009–010 through the actual ending on scan 447.
- scan 448 is separate in `works/pudhaiyal/sections/99-printer-colophon.md` and is not narrative.

## English frontier

- source-checked English: continuous through **scan 441 / printed 437 — Part-009 physical endpoint**;
- bilingual-reviewed English: continuous through **scan 441 / printed 437 — Part-009 physical endpoint**;
- Chapter 45 Part-009 continuation is **bilingual-reviewed through its close on scan 396 portion**, resolving the audited `நமது வாழ்க்கையை` join;
- Chapters 46–50 are **bilingual-reviewed continuously through the Chapter-50 close on scan 438 portion**;
- Chapter 46 source check made one English-only fidelity refinement to the ritual-oath sequence, removing the draft's added interpretive phrase `in oath` while leaving Tamil unchanged;
- Chapter 51 is **bilingual-reviewed from scan 438 portion through the Part-009 physical endpoint on scan 441**, deliberately ending at English `Amb` for Tamil `அம்ப` without importing Part-010 `லமே`;
- source-specific oddities including Chapter-46 disguise/Laila-Qais details, Chapter-47 `dharpaasooran`, Chapter-48 Aravan/Bhima and caste-marked wording, Chapter-50 `சாவுக் கண்ணீர்`, Chapter-51 public-service exhortation, and the open Chapter-51 boundary were preserved without external correction;
- Part-009 bilingual review made **no additional English changes** beyond the source-check correction;
- Part-010 controlled English continuation remains pending.

## Aggregate durable state

- canonical records: **448**
- verified/completed: **441**
- needs-review: **7 — only Part 005 scans 215–219 and 223–224**
- partial: **0**
- assembled Tamil narrative: continuous through **scan 447 / printed 443 — actual ending**
- assembled back matter: through **scan 448**
- source-checked English: continuous through **scan 441 / printed 437 — Part-009 physical endpoint**
- bilingual-reviewed English: continuous through **scan 441 / printed 437 — Part-009 physical endpoint**
- Parts 001–009: **part-complete**
- Part 010: **Tamil + assembled gates PASSED; controlled English pending**
- whole-work release gates: not yet eligible

## Exact next activity

Continue **Part 010 controlled English translation**, beginning at scan **442** by completing the open Chapter-51 boundary: English `Amb` from Part 009 must continue to **`Ambalam`**, corresponding to audited Tamil `அம்ப` + `லமே` → **`அம்பலமே`**. Translate Chapter 51 continuously through the actual narrative ending on scan **447 / printed 443**. Keep scan **448** as separate printer-colophon back matter and do not claim Part-010 source check or bilingual review until the Part-010 English draft is complete.