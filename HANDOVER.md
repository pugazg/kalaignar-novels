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
- Part 009 scans **393–441 / printed 389–437**: **Tamil audit PASSED — 49 / 49 verified**
- Part 010 scans **442–448**: **canonical complete — 7 / 7 represented; 6 verified, scan 445 needs-review**

Part-005 source-damage qualification remains on scans **215–219 and 223–224**.

## Parts 009–010 checkpoint

Part 009:

- page map: `works/pudhaiyal/indexes/part-009-page-map.md`
- audit: `works/pudhaiyal/notes/part-009-tamil-audit.md`
- result: **49 / 49 verified, 0 needs-review, Tamil audit PASSED**
- no complete `p9.md` lexical omission found
- baseline-only structure marks rejected: `⚬` scan 416; `*` scan 435

Part 010:

- page map: `works/pudhaiyal/indexes/part-010-page-map.md`
- audit: `works/pudhaiyal/notes/part-010-tamil-audit.md`
- result: **7 / 7 canonical; 6 verified; 1 needs-review — scan 445 / printed 441**

Verified source boundaries:

- Part 008→009: `நமது` + `வாழ்க்கையை` → **`நமது வாழ்க்கையை`**;
- Part 009→010: `அம்ப` + `லமே` → **`அம்பலமே`**;
- scan **447 / printed 443**: actual narrative ending;
- scan **448**: separate printer colophon `அன்பு அச்சகம், பொறையார்.`

### Blocking Part-010 omission

Native scan **445 / printed 441** visibly contains:

`தங்கத்திற்குப் பக்கத்திலே புதைத்து விடு!”`

The controlling `p10.md` baseline omits complete word **`விடு`**, giving only `...புதைத்து` before the closing quote.

Canonical scan 445 therefore remains `needs-review` and does not silently insert `விடு`.

## Aggregate durable state

- canonical records: **448**
- verified/completed: **440**
- needs-review: **8** — Part 005 scans **215–219, 223–224** plus Part 010 scan **445**
- partial: **0**
- assembled Tamil: continuous through **scan 392 / printed 388**
- source-checked English: continuous through **scan 392 / printed 388**
- bilingual-reviewed English: continuous through **scan 392 / printed 388**
- received source coverage: through **scan 448**, including narrative ending and printer colophon
- Parts 001–008: **part-complete**
- Part 009: **Tamil audit PASSED; downstream assembly pending**
- Part 010: **Tamil audit BLOCKED on one lexical omission**
- whole-work gates: not eligible

## Exact next activity

Obtain explicit user disposition for native scan-445 word **`விடு`**. If authorized, insert it narrowly, return scan 445 to `verified`, rerun Part-010 Tamil audit, then build assembled Tamil continuously for Parts 009–010 from scan **393 through the narrative ending at scan 447**, preserving scan 448 separately as printer-colophon back matter.