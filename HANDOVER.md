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

Complete source-visible lexical spans absent from the supplied baseline require explicit user disposition rather than silent insertion. Source/split PDFs and uploaded baseline files are never committed.

## Source identity — புதையல்

- author: கலைஞர் மு. கருணாநிதி, எம். எல். ஏ.
- publisher: அன்புப் பதிப்பகம், பொறையார் :: தஞ்சை மாவட்டம்
- edition: மூன்றாம் பதிப்பு — செப்டம்பர் 1961
- TDL bibliographic extent: **443 p.**
- exact original full-file page-object count / SHA-256: pending byte-level full-source reconciliation

## Durable split state

- Parts 001–008: **part-complete**
- Part 009 scans **393–441 / printed 389–437**: **source intake complete / canonical next**
- Part 010 scans **442–448**: **source intake complete / canonical after Part 009**

Part-005 source-damage qualification remains on scans **215–219 and 223–224**.

## New received-source checkpoint

### Part 009

Derivative: `TVA_BOK_0064097_புதையல்_part_009_pages_393-441.pdf`

- physical pages **49**
- scans **393–441**
- printed **389–437**
- size **57,643,045 bytes**
- SHA-256 `8e104e151ced62916de64d320afe41a4ede549af6712fba8c654ae6c1385cbce`
- lexical baseline `p9.md`, **164,794 bytes / 242 logical lines**
- baseline SHA-256 `b0b227ba8bce1650f65a10b114f53f4601a4c7d72f5649993de20bf991071664`
- source intake `works/pudhaiyal/notes/part-009-source-intake.md`
- page map `works/pudhaiyal/indexes/part-009-page-map.md`
- canonical **0 / 49** at intake checkpoint.

Part-008 scan 392 `நமது` + Part-009 scan 393 `வாழ்க்கையை` establishes continuous **`நமது வாழ்க்கையை`**.

Native chapter landmarks mapped at scans **396 (Ch46), 408 (Ch47), 414 (Ch48), 423 (Ch49), 429 (Ch50), 438 (Ch51)**. Scan 441 remains inside Chapter 51 and ends physically at `அம்ப`.

### Part 010

Derivative: `TVA_BOK_0064097_புதையல்_part_010_pages_442-448.pdf`

- physical pages **7**
- scans **442–448**
- printed **438–443** on scans 442–447
- scan 448 unnumbered printer colophon
- size **7,206,369 bytes**
- SHA-256 `27660cd6a8abe288ea1924f4ca02c23747713afc5883b010fb2f58a61b6ebbd0`
- lexical baseline `p10.md`, **17,559 bytes / 165 logical lines**
- baseline SHA-256 `938407860a3a80e14da3a5d6a273675b8cdcc3e70e8a0e538f40dcceb871dc3a`
- source intake `works/pudhaiyal/notes/part-010-source-intake.md`
- page map `works/pudhaiyal/indexes/part-010-page-map.md`
- canonical **0 / 7** at intake checkpoint.

Part-009 scan 441 `அம்ப` + Part-010 scan 442 `லமே` establishes continuous **`அம்பலமே`**.

The received source now establishes:

- **scan 447 / printed 443** — narrative ending of Chapter 51 / novel text;
- **scan 448** — separate printer colophon: `அன்பு அச்சகம், பொறையார்.`

Do not merge the colophon into Chapter 51. Do not call the project release-ready merely because the source ending is now received; Parts 009–010 and final whole-work gates remain unfinished.

## Aggregate durable state

- canonical records: **392**
- verified/completed: **385**
- needs-review: **7 — only Part 005 scans 215–219 and 223–224**
- partial: **0**
- assembled Tamil: continuous through **scan 392 / printed 388**
- source-checked English: continuous through **scan 392 / printed 388**
- bilingual-reviewed English: continuous through **scan 392 / printed 388**
- received source coverage: through **scan 448**, including the narrative ending and colophon
- Parts 001–008: **part-complete**
- Parts 009–010: **received/mapped; canonical pending**
- whole-work gates: not eligible

## Exact next activity

Begin **Part 009 canonical reconciliation at scan 393 / printed 389**. Use `p9.md` for lexical words/forms/spacing and native pages for structure. Preserve the proven `நமது வாழ்க்கையை` cross-split continuation. Reconcile Part 009 through scan 441 before processing Part 010, then preserve `அம்ப` + `லமே` → `அம்பலமே` and keep scan 448 as separate back matter.