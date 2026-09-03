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
- exact original full-file page-object count / SHA-256: pending byte-level full-source reconciliation

## Durable split state

- Parts 001–008: **part-complete**
- Part 009 scans **393–441 / printed 389–437**: **canonical in progress — 10 / 49 verified**
- Part 010 scans **442–448**: **source intake complete / canonical after Part 009**

Part-005 source-damage qualification remains on scans **215–219 and 223–224**.

## Parts 009–010 checkpoint

Part 009 source identity/checksums and map are recorded in:

- `works/pudhaiyal/notes/part-009-source-intake.md`
- `works/pudhaiyal/indexes/part-009-page-map.md`

Part 010 source identity/checksums and map are recorded in:

- `works/pudhaiyal/notes/part-010-source-intake.md`
- `works/pudhaiyal/indexes/part-010-page-map.md`

Verified source boundaries:

- Part 008→009: `நமது` + `வாழ்க்கையை` → **`நமது வாழ்க்கையை`**;
- Part 009→010: `அம்ப` + `லமே` → **`அம்பலமே`**;
- scan **447 / printed 443**: narrative ending;
- scan **448**: separate printer colophon `அன்பு அச்சகம், பொறையார்.`

### Part 009 canonical frontier

Scans **393–402 / printed 389–398** are canonical and `verified`.

- scan 396 closes Chapter 45 and opens Chapter 46;
- physical splits such as `விவரிக்க`→`வில்லை`, `ஷோக்சுந்`→`தரி`, `அவ`→`ளுக்குத்`, and open quotation continuations are preserved at page level;
- no complete `p9.md` lexical omission was found in scans 393–402;
- scan 402 ends at `விடுவித்து`; scan 403 begins `விடு`.

Part 010 canonical work must not begin until Part 009 reaches scan 441.

## Aggregate durable state

- canonical records: **402**
- verified/completed: **395**
- needs-review: **7 — only Part 005 scans 215–219 and 223–224**
- partial: **0**
- assembled Tamil: continuous through **scan 392 / printed 388**
- source-checked English: continuous through **scan 392 / printed 388**
- bilingual-reviewed English: continuous through **scan 392 / printed 388**
- received source coverage: through **scan 448**, including narrative ending and printer colophon
- Parts 001–008: **part-complete**
- whole-work gates: not eligible

## Exact next activity

Continue **Part 009 canonical reconciliation at scan 403 / printed 399**, beginning `விடு` as the continuation of scan 402 `விடுவித்து`. Keep `p9.md` lexical wording authoritative; use the native scan only for structure/punctuation/page boundaries. Continue toward scan 441 before entering Part 010.