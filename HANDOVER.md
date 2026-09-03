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

- Parts 001–008: **part-complete**
- Part 009 / scans **393–441 / printed 389–437**: **Tamil audit PASSED + assembled Tamil PASSED; English draft through Chapter 50 / scan 438 portion**
- Part 010 / scans **442–448**: **Tamil audit PASSED + assembled Tamil PASSED; English pending**
- Part-005 source-damage qualification remains on scans **215–219 and 223–224**.

Part 009 records:

- `works/pudhaiyal/notes/part-009-tamil-audit.md`
- `works/pudhaiyal/notes/part-009-assembled-tamil-check.md`
- result: **49 / 49 verified, 0 Part-009 needs-review**
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

- Chapter 45 now continues through its close in Part 009.
- Chapters **46–50** are assembled from audited Part-009 pages.
- Chapter **51** is assembled continuously across Parts 009–010 through the actual ending on scan 447.
- scan 448 is separate in `works/pudhaiyal/sections/99-printer-colophon.md` and is not narrative.

## English frontier

- source-checked English: continuous through **scan 392 / printed 388**;
- bilingual-reviewed English: continuous through **scan 392 / printed 388**;
- Chapter 45 Part-009 continuation is **draft-translated through its close on scan 396 portion**, resolving the audited `நமது வாழ்க்கையை` join;
- Chapter 46 is **draft-translated continuously through its close on scan 408 portion**;
- Chapter 47 is **draft-translated continuously through its close on scan 414 portion**;
- Chapter 48 is **draft-translated continuously through its close on scan 422**; the source's Aravan/Bhima wording, caste-marked insult and `kalappali` language are preserved without external correction;
- Chapter 49 is **draft-translated continuously through its close on scan 429 portion**; village-violence wording, Durai's rallying speech and the rekla pursuit toward Manora are preserved without downstream review claims;
- Chapter 50 is **draft-translated continuously through its close on scan 438 portion**; Mayandi's `சாவுக் கண்ணீர்` image, his death, the loss of the treasure secret into the sea and Ambalam's disappearance into the sea are preserved without downstream review claims;
- Part-009 controlled English source check and bilingual review have **not** yet been claimed;
- only the Chapter-51 Part-009 portion from scan **438 portion through scan 441** remains before the Part-009 draft is complete.

## Aggregate durable state

- canonical records: **448**
- verified/completed: **441**
- needs-review: **7 — only Part 005 scans 215–219 and 223–224**
- partial: **0**
- assembled Tamil narrative: continuous through **scan 447 / printed 443 — actual ending**
- assembled back matter: through **scan 448**
- source-checked English: continuous through **scan 392 / printed 388**
- bilingual-reviewed English: continuous through **scan 392 / printed 388**
- draft-translated English: continuous through **scan 438 portion / Chapter 50 close**
- Parts 001–008: **part-complete**
- Part 009: **Tamil + assembled gates PASSED; controlled English draft in progress**
- Part 010: **Tamil + assembled gates PASSED; controlled English pending**
- whole-work release gates: not yet eligible

## Exact next activity

Continue **controlled English translation for Part 009 with the Chapter 51 Part-009 portion**, beginning at scan **438 portion** and translating continuously through the physical Part-009 endpoint on scan **441**. Preserve the audited open split boundary `அம்ப` exactly as a derivative endpoint; do not infer or pull in Part-010 `லமே` during the Part-009 draft. After that Part-009 draft is complete, run the dedicated Part-009 English source check before bilingual review.
