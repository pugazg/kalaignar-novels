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
- canonical records **138 / 179**;
- Chapter 14 / 15 boundary: **scan 120 / printed 119**, centered `15`;
- Chapter 16 opens: **scan 127 / printed 126**, centered `16`;
- Chapter 16 / 17 boundary: **scan 134 / printed 133**, centered `17`;
- Chapter 17 transcribed through **scan 138 / printed 137**;
- historical-glyph coverage: **PASS scans 1–138**;
- next forward iteration: **scans 139–143**;
- batch size: **5 scans**;
- full Tamil source audit / assembled Tamil / English: **not started / not started / blocked**.

## Critical historical-glyph rule

Mandatory set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Identify character identity from source pixels first. Grammar is only a locator, never proof. Preserve source spelling, grammar, punctuation, spacing and colloquial forms. Never global-replace.

The expanded corrective re-audit remains controlling. Apparent short-looking old type must be checked against same-edition forms before classification. Independently source-confirmed forms such as `வேலையில்ல`, `வரணும்`, `நானு`, recurring **`நயினா`**, scan 114 `அப்படித்தான் ஆவள்`, and later source-specific clusters remain unchanged.

## Production workflow

For each 5-scan batch:

1. fetch live `main` once;
2. transcribe all five full pages first;
3. run one batch-level mandatory 13-family glyph sweep;
4. allow at most one targeted enlargement for a genuinely unclear token;
5. if still unresolved, record a source hold and continue;
6. create five page records and synchronize audit/page-map/README/HANDOVER/prompt together;
7. make one atomic commit;
8. do not reopen prior PASS scans without new source evidence.

## Recent durable results

- scan 129 / 130: physical `அழகப்ப` + `னுடைய` = `அழகப்பனுடைய`;
- scan 130 bottom `9` printer/signature mark;
- scan 131 / 132: physical `பின்னிக்` + `கொண்டன` = `பின்னிக்கொண்டன`;
- scan 134: mixed Chapter 16 / 17 boundary, centered `17`; preserve `முழுசம்`, `எழுதியிட்டான்`; ends `நயினாவின்`;
- scan 135: begins `கேள்வி`; preserve `பார்த்து.`, `செளக்கியந்தானே!`, `இப்படி யென்றால்`; ends `வருத்தத்`;
- scan 136: begins `தோடு`, completing `வருத்தத்தோடு`; preserve `சொல்லுகிறாளாக்கும்`, `பதிலக் கேள்வி`;
- scan 137: preserve `சிக்கலங்கிப்போயிருக்கிறோம்`; ends open quote `“இதோ,`;
- scan 138: begins `கொண்டுவருகிறேன்”`; preserve `வந்துவிட்டுமா?`; ends literal `‘மளமள’`.

## Structural/source decisions to preserve

- scan 66 visible printed number only `5`;
- scan 82 bottom `6` printer/signature mark;
- scan 89 / 90 `மறுத்துவிட்` + `டால்`;
- scan 98 bottom `7` printer/signature mark;
- scan 111 / 112 `சிறிதா` + `வது` = `சிறிதாவது`;
- scan 114 bottom `8` printer/signature mark;
- scan 117 / 118 literal `உட்` → `எவ்வளவோ...` source discontinuity;
- scan 119 / 120 `கவனித்து` → `விட்டான்.`;
- scan 122 / 123 literal `...அவளுக்குப் பக்கத்திலே` → `கார்ந்து கொண்டாள்.`; no grammatical reconstruction;
- scan 124 / 125 `புகை` + `வண்டி` = `புகைவண்டி`;
- scan 127 / 128 `வாழ்` + `விலே` = `வாழ்விலே`;
- scan 129 / 130 `அழகப்ப` + `னுடைய` = `அழகப்பனுடைய`;
- scan 131 / 132 `பின்னிக்` + `கொண்டன` = `பின்னிக்கொண்டன`;
- scan 134 / 135 `நயினாவின்` → `கேள்வி`;
- scan 135 / 136 `வருத்தத்` + `தோடு` = `வருத்தத்தோடு`;
- scan 137 / 138 `“இதோ,` → `கொண்டுவருகிறேன்”`;
- scan 138 ends `‘மளமள’`; continue only from direct scan-139 evidence.

## Exact next activity

1. re-fetch live `main`;
2. resolve controlling source;
3. process **scans 139–143** in one bounded 5-page iteration;
4. establish scan 139 only from direct source pixels after scan 138's literal `‘மளமள’`;
5. run one batch glyph sweep and bounded ambiguity handling;
6. synchronize page records and status documents and commit atomically.

Do not start assembled Tamil or English.

## Completed works — preserve

- **பெரிய இடத்துப் பெண்**: source audit complete; assembled Tamil PASSED; English VERIFIED; release-ready with qualification.
- **புதையல்**: 448 canonical / 446 complete / 2 physical-loss `needs-review`; English VERIFIED; release-ready with qualification.
- **பலிபீடம் நோக்கி**: Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; release-ready.
