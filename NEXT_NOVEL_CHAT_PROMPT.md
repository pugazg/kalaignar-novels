# Next Chat Prompt — வெள்ளிக்கிழமை

Continue directly in `pugazg/kalaignar-novels`, branch `main`, active work `works/vellikkizhamai/`. Live `main` is authoritative.

## Source

`TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf` — SHA-256 `ac241cbfbe3d47d76f22140f43c662176ba29a91521b826a1a8f5c75cf3081d3`, **179 scans**, image-only, second edition 1968. Do not commit it.

## Current durable state

- canonical records: **158 / 179**;
- Chapter 19 opens: **scan 149 / printed 148**, centered `19`;
- Chapter 20 opens: **scan 154 / printed 153**, centered `20`;
- Chapter 20 transcribed through **scan 158 / printed 157**;
- historical-glyph coverage: **PASS scans 1–158**;
- next iteration: **scans 159–163**;
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

- scan 154: Chapter 19 / 20 boundary, centered `20`;
- scan 155 / 156: `சோலை` + `யில்` = `சோலையில்`;
- scan 156 / 157: literal `தலையிலும் காயம்` → `நயினா எதிர்த்தே அடிக்கவில்லை.`; do not grammatically reconstruct the boundary;
- scan 157 / 158: `பயங்கரமாக—` → `ஆனந்தியிருக்கும் அறையை நோக்கி நடக்கத் தொடங்கினாள்.`;
- scan 158 ends physical `வராத`; establish scan 159 only from direct source.

## Source-specific recent forms

Preserve confirmed source forms such as `சோகடிப்புமானான்`, `ஈனசுரத்தில்`, `மலை மலையாக`, `அலை அலையாக`, `சஞ்சீவி`, `சிபாரிசு`, `அபாக்கியவதி`, `நிலைமைகண்டு`, `நடந்துகொண்டதாகக்கருதி`, `அவ்வளவுங்`, `பண்டமாற்று`, `கன்றிப்போய்விட்டது`, `நயினாமீது`, `அலட்சியச்`, `குற்றவாளிக்கூண்டு`, `ஆக்ரோஷத்தோடு`, `குமுறின`, `மாறாக`, `ஸ்தம்பித்து`, `ஆருயிர்த் தோழனிடத்திலே`, and `சமயங்கூட`.

## Exact next activity

Process **scans 159–163** in one bounded 5-page iteration. Do not start assembled Tamil or English.
