# Next Chat Prompt — வெள்ளிக்கிழமை

Continue directly in `pugazg/kalaignar-novels`, branch `main`, active work `works/vellikkizhamai/`. Live `main` is authoritative.

## Source

`TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf` — SHA-256 `ac241cbfbe3d47d76f22140f43c662176ba29a91521b826a1a8f5c75cf3081d3`, **179 scans**, image-only, second edition 1968. Do not commit it.

## Current durable state

- canonical records: **128 / 179**;
- Chapter 14 / 15 boundary: **scan 120 / printed 119**, centered `15`;
- Chapter 16 opens **scan 127 / printed 126**, centered `16`;
- Chapter 16 transcribed through **scan 128 / printed 127**;
- historical-glyph coverage: **PASS scans 1–128**;
- next iteration: **scans 129–133**;
- batch size: **5 scans**;
- assembled Tamil / English: **not started / blocked**.

## Mandatory glyph rule

Check `ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ` from source pixels. Grammar is only a locator. Never global-replace or normalize source wording.

## Production workflow — use this to avoid slow iterations

1. Fetch live `main` once.
2. Transcribe all five full pages straight through before stopping for ambiguities.
3. Run one batch-level 13-family historical-glyph sweep.
4. For a genuinely unclear token, allow **one targeted enlargement only**.
5. If still unresolved, record a source hold / `needs-review` item and continue; do not repeatedly crop the same word.
6. Create five page records, update audit/page-map/README/HANDOVER/prompt together, then make one atomic commit.
7. Do not reopen previously PASS scans unless new source evidence directly contradicts them.

## Recent source boundaries to preserve

- scan 124 / 125: physical `புகை` + `வண்டி` = `புகைவண்டி`;
- scan 127: Chapter 16 opening, centered `16`;
- scan 127 / 128: physical `வாழ்` + `விலே` = `வாழ்விலே`;
- scan 128 ends literal `ஏறும்போது`; establish scan 129 continuation only from direct source evidence.

## Exact next activity

Process **scans 129–133** in one bounded 5-page iteration using the production workflow above. Do not start assembled Tamil or English.
