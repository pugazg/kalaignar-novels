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

## Current durable state

- manifest **179 / 179**;
- canonical records **118 / 179**;
- Chapter 12 / 13 boundary: **scan 107 / printed 106**, centered `13`;
- Chapter 13 / 14 boundary: **scan 115 / printed 114**, centered `14`;
- Chapter 14 transcribed through **scan 118 / printed 117**;
- historical-glyph coverage on existing canonical scans: **PASS scans 1–118**;
- retrospective historical-glyph re-audit: **PASS scans 1–101 / COMPLETE**;
- corrective historical-glyph re-audit: **PASS scans 102–111**;
- prospective forward historical-glyph check: **PASS scans 112–118**;
- next forward iteration: **scans 119–123**;
- batch size: **5 scans per iteration**;
- full Tamil source audit / assembled Tamil / English: **not started / not started / blocked**.

## Critical historical-glyph rule

Mandatory set on every scan:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Identify character identity from enlarged/native source pixels first. Grammar is only a locator, never proof. Preserve source spelling, grammar, punctuation, spacing and colloquial forms. Never global-replace.

Corrective scans 102–111 remain controlling for the known failure mode. Nearby forms must always be independently source-checked. Genuine counterexamples include `வயதினள்`, `பருவத்தினள்`, `மாறினள்`, `கத்தினள்`, `நீட்டினன்`, `அமர்த்தினன்`, `பொத்தினன்`, `தொடங்கினள்`, `கருதினன்`, and `கூறினன்`. Recurring name is **`நயினா`**.

## Historical-glyph closure

- scans **1–101**: retrospective re-audit COMPLETE / PASS;
- scans **102–111**: corrective PASS;
- scans **112–118**: forward PASS;
- therefore every canonical scan **1–118** has direct source-pixel historical-glyph coverage.

## Recent forward results

- scan 112: `சிறிதா` + `வது` = `சிறிதாவது`; genuine `கருதினன்`;
- scan 113: genuine `கூறினன்`; ends `ஆறுதல் கூறுவதற்கு ஒருவர் அருகே இருக்கும்போது`;
- scan 114: continues `பாசமும் பற்றும்...`; `அப்படித்தான் ஆவள்`, `கதறினள்`, `முனகினள்`, `அமராழ்`; bottom `8` printer/signature mark;
- scan 115: mixed Chapter 13 / 14; centered `14`; `சூடான`, `கண்டு பிடித்த`, `நமைச்சலுக்கு`;
- scan 116: `தவறாகக்`, `சித்திரப் புள்`, `பூர்வ ஜென்ம பூஜாபலன்`, genuine `தொடங்கினள்`; ends `நான் யாருக்கு என்ன துரோகம்`;
- scan 117: begins `செய்தேனம்மா!...`; genuine `கத்தினள்`; literal final `உட்` retained;
- scan 118: begins `எவ்வளவோ முயன்றும் நடக்கவில்லை.`; no fabricated completion for scan 117; final dialogue continues on scan 119 with `வருகிறேன்.........`.

## Preserve structural/source decisions

- scan 33 Chapter 3 / 4, centered `4`;
- scan 45 Chapter 4 / 5, centered `5`;
- scan 52 Chapter 6 opening, centered `6`;
- scan 59 Chapter 6 / 7, centered `7`;
- scan 66 visible printed number only `5`;
- scan 68 Chapter 7 / 8, centered `8`;
- scan 75 Chapter 8 / 9, centered `9`;
- scan 82 bottom `6` printer/signature mark;
- scan 85 Chapter 9 / 10, centered `10`;
- scan 89 / 90 `மறுத்துவிட்` + `டால்`;
- scan 92 Chapter 10 / 11, centered `11`;
- scan 98 bottom `7` printer/signature mark;
- scan 99 Chapter 11 / 12, centered `12`;
- scan 101 / 102 continuation;
- scan 107 Chapter 12 / 13, centered `13`;
- scan 111 / 112 `சிறிதா` + `வது`;
- scan 113 / 114 sentence continuation;
- scan 114 bottom `8` printer/signature mark;
- scan 115 Chapter 13 / 14, centered `14`;
- scan 116 / 117 sentence continuation;
- scan 117 / 118 literal `உட்` → `எவ்வளவோ...` source discontinuity;
- scan 118 / 119 open dialogue continuation.

## Exact next activity

1. re-fetch live `main`;
2. resolve controlling source;
3. process **scans 119–123** in one 5-page iteration;
4. preserve scan 118 / 119 continuation beginning `வருகிறேன்.........`;
5. apply mandatory 13-family source-pixel checks before encoding every page;
6. synchronize page records, audit, page-map, README/status/handover documents and commit.

Do not start assembled Tamil or English.

## Completed works — preserve

- **பெரிய இடத்துப் பெண்**: source audit complete; assembled Tamil PASSED; English VERIFIED; release-ready with qualification.
- **புதையல்**: 448 canonical / 446 complete / 2 physical-loss `needs-review`; English VERIFIED; release-ready with qualification.
- **பலிபீடம் நோக்கி**: Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; release-ready.
