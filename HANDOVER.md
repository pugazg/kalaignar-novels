# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`; branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Historical-glyph guide: `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`
- Current target: **வெள்ளிக்கிழமை** — `works/vellikkizhamai/`

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first and preserve newer durable work.

## Controlling source

`TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf` — SHA-256 `ac241cbfbe3d47d76f22140f43c662176ba29a91521b826a1a8f5c75cf3081d3`, **251,126,214 bytes**, **179 scans**, image-only, second edition 1968. Do not commit PDF.

## Current durable state after corrective glyph work

- manifest **179 / 179**;
- canonical records **111 / 179**;
- Chapter 12/13 boundary: **scan 107 / printed 106**, centered `13`;
- Chapter 13 transcribed through **scan 111 / printed 110**;
- historical-glyph work-level gate: **REOPENED**;
- corrective historical-glyph re-audit: **PASS scans 102–111**;
- retrospective historical-glyph audit: **PENDING scans 1–101**;
- full Tamil source audit / assembled Tamil / English: **not started / not started / blocked**.

## Critical process correction

The previous historical-glyph pass was not applied correctly in several places. Old metal-type shapes were sometimes retained as their modern visual look-alikes instead of being decoded to their actual character identities, contrary to `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`.

Confirmed corrections now made in scans 102–111 include:

- scan 102 `ஆட்டினள்` → `ஆட்டினாள்`;
- scan 103 `நன்றுகக்` → `நன்றாகக்`; `கத்தினள்` → `கத்தினாள்`;
- scan 104 `கூறினள்` → `கூறினாள்`;
- scan 106 `திருப்பினள்` → `திருப்பினாள்`; `என்றுள்` → `என்றாள்`; `நன்றுகக்` → `நன்றாகக்`; `தவறுக` → `தவறாக`;
- scan 107 `கூறினள்` → `கூறினாள்`; `கொட்டினன்` → `கொட்டினான்`; `என்றுள்` → `என்றாள்`; `ஓடினன்` → `ஓடினான்`; `ஓடினர்கள்` → `ஓடினார்கள்`;
- scan 108 `திமிறினன்` → `திமிறினான்`; `நடுங்கினள்` → `நடுங்கினாள்`;
- scan 109 `சொன்னு` → `சொன்னா`; `பொய்தானு?` → `பொய்தானா?`;
- scan 110 `பெண்ணு?` → `பெண்ணா?`.

No global replacement was used. Nearby apparent forms must be decided independently. Scan 109 `கூறினன்` / `சொன்னன்` and scan 110 `புளுகினன்` were rechecked and retained.

## Preserve these structural/source decisions

- recurring name **`நயினா`**, not `நயினு`;
- scan 66 visible page number is **`5`**, never infer `65`;
- scan 98 bottom standalone `7` is a printer/signature mark, not a chapter heading;
- scan 99 is mixed Chapter 11 / Chapter 12 with centered `12`;
- scan 107 is mixed Chapter 12 / Chapter 13 with centered `13`;
- scan 111 ends physical `சிறிதா`; scan 112 begins source-visible `வது`, forming `சிறிதாவது` across the page boundary.

## Exact next activity

Forward transcription is paused until the earlier historical-glyph coverage is trustworthy.

1. re-fetch live `main`;
2. resolve the controlling PDF;
3. perform retrospective historical-glyph audit of **scans 1–5** as one 5-scan iteration;
4. explicitly test all 13 families on source pixels;
5. correct only positively supported character identities; never infer from grammar alone and never global-replace;
6. synchronize audit/status docs and commit;
7. continue retrospectively in 5-scan order until scans 1–101 are cleared;
8. only then resume forward transcription at scan 112.

Do not start assembled Tamil or English.

## Completed works — preserve

- **பெரிய இடத்துப் பெண்**: source audit complete; assembled Tamil PASSED; English VERIFIED; release-ready with qualification.
- **புதையல்**: 448 canonical / 446 complete / 2 physical-loss `needs-review`; English VERIFIED; release-ready with qualification.
- **பலிபீடம் நோக்கி**: Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; release-ready.
