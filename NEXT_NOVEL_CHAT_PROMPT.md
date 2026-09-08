# Next Chat Prompt — வெள்ளிக்கிழமை

Continue directly in `pugazg/kalaignar-novels`, branch `main`, active work `works/vellikkizhamai/`. Live `main` is authoritative.

## Source

`TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf` — SHA-256 `ac241cbfbe3d47d76f22140f43c662176ba29a91521b826a1a8f5c75cf3081d3`, **179 scans**, image-only, second edition 1968. Do not commit it.

## Current durable state

- canonical records: **138 / 179**;
- Chapter 16 opens: **scan 127 / printed 126**, centered `16`;
- Chapter 16 / 17 boundary: **scan 134 / printed 133**, centered `17`;
- Chapter 17 transcribed through **scan 138 / printed 137**;
- historical-glyph coverage: **PASS scans 1–138**;
- next iteration: **scans 139–143**;
- batch size: **5 scans**;
- assembled Tamil / English: **not started / blocked**.

## Mandatory glyph rule

Check `ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ` from source pixels. Grammar is only a locator. Never global-replace or normalize source wording.

## Production workflow

1. Fetch live `main` once.
2. Transcribe all five full pages straight through.
3. Run one batch-level 13-family historical-glyph sweep.
4. For a genuinely unclear token, allow **one targeted enlargement only**.
5. If still unresolved, record a source hold / `needs-review` and continue.
6. Create five page records, update audit/page-map/README/HANDOVER/prompt together, then make one atomic commit.
7. Do not reopen previously PASS scans unless new direct source evidence contradicts them.

## Recent source boundaries to preserve

- scan 129 / 130: `அழகப்ப` + `னுடைய` = `அழகப்பனுடைய`;
- scan 130 bottom `9` printer/signature mark;
- scan 131 / 132: `பின்னிக்` + `கொண்டன` = `பின்னிக்கொண்டன`;
- scan 134: Chapter 16 / 17 boundary, centered `17`;
- scan 134 / 135: `நயினாவின்` → `கேள்வி`;
- scan 135 / 136: `வருத்தத்` + `தோடு` = `வருத்தத்தோடு`;
- scan 137 / 138: open quotation `“இதோ,` → `கொண்டுவருகிறேன்”`;
- scan 138 ends literal `‘மளமள’`; establish scan 139 only from direct source.

## Source-specific recent forms

Preserve confirmed source forms such as `முழுசம்`, `எழுதியிட்டான்`, `பார்த்து.`, `செளக்கியந்தானே!`, `சொல்லுகிறாளாக்கும்`, `பதிலக் கேள்வி`, `சிக்கலங்கிப்போயிருக்கிறோம்`, and `வந்துவிட்டுமா?`.

## Exact next activity

Process **scans 139–143** in one bounded 5-page iteration. Do not start assembled Tamil or English.
