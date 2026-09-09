# Next Chat Prompt — வெள்ளிக்கிழமை

Continue directly in `pugazg/kalaignar-novels`, branch `main`, active work `works/vellikkizhamai/`. Live `main` is authoritative.

## Source

`TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf` — SHA-256 `ac241cbfbe3d47d76f22140f43c662176ba29a91521b826a1a8f5c75cf3081d3`, **179 scans**, image-only, second edition 1968. Do not commit it.

## Current durable state

- canonical records: **153 / 179**;
- Chapter 18 opens: **scan 142 / printed 141**, centered `18`;
- Chapter 19 opens: **scan 149 / printed 148**, centered `19`;
- Chapter 19 transcribed through **scan 153 / printed 152**;
- historical-glyph coverage: **PASS scans 1–153**;
- next iteration: **scans 154–158**;
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

- scan 147 / 148: `சந்திப்` + `பதற்காக!` = `சந்திப்பதற்காக!`;
- scan 148 ends a complete sentence;
- scan 149: Chapter 19 opening, centered `19`;
- scan 149 / 150: `புறப்` + `பட்டுவிட்டாயே!` = `புறப்பட்டுவிட்டாயே!`;
- scan 150 / 151: `தேவ` + `லோகத்தில்` = `தேவலோகத்தில்`;
- scan 151 ends the complete question `பிடித்து விட்டால்...?`;
- scan 152 / 153: `வழக்கமாக உறங்கும்` → `அறைக்கல்லவா போகிறாள்!`;
- scan 153 ends a complete sentence; establish scan 154 only from direct source.

## Source-specific recent forms

Preserve confirmed source forms such as `துயர்களை யேற்று`, `இழிவுப்படு குழியிலே`, `ஆவேசங்கொண்டு`, `வெறிபிடித்தவள்போல`, `மருத்துவ மனையிருக்கும்`, `துவங்கியது`, `அவ்விடம்`, `நயினா வலியுறுத்தியதன்பேரில்`, `அழகுவின்`, `நயினாதான்`, `பீறிட்டுப்`, `ஸ்பரிச`, `நயினா முகமதுவும்`, and `ஈன சுரத்தில்`.

## Exact next activity

Process **scans 154–158** in one bounded 5-page iteration. Do not start assembled Tamil or English.
