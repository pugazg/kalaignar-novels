# Next Chat Prompt — வெள்ளிக்கிழமை

Continue directly in `pugazg/kalaignar-novels`, branch `main`, active work `works/vellikkizhamai/`. Live `main` is authoritative.

## Source

`TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf` — SHA-256 `ac241cbfbe3d47d76f22140f43c662176ba29a91521b826a1a8f5c75cf3081d3`, **179 scans**, image-only, second edition 1968. Do not commit it.

## Current durable state

- canonical records: **173 / 179**;
- Chapter 20 opens: **scan 154 / printed 153**, centered `20`;
- Chapter 21 opens: **scan 160 / printed 159**, centered `21`;
- Chapter 22 opens: **scan 166 / printed 165**, centered `22`;
- Chapter 23 opens: **scan 172 / printed 171**, centered `23`;
- Chapter 23 transcribed through **scan 173 / printed 172**;
- historical-glyph coverage: **PASS scans 1–173**;
- next iteration: **scans 174–178**;
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

- scan 169 / 170: `ஒலி வந்த திக்கையே நோக்கியவாறு` → `அவள் எழுந்துநின்றாள்,`;
- scan 170 / 171: `“எஜமான்!....இடும்பன்...”` → `என்றான்.`;
- scan 171 / 172: `வம்புச் சண்டையெல்லாம்` + `நடந்தது.` = `வம்புச் சண்டையெல்லாம் நடந்தது.`;
- scan 172: Chapter 22 / 23 boundary, centered `23`;
- scan 172 ends complete; scan 173 begins a new source sentence;
- scan 173 ends physical `அவள் நெஞ்சிலே`; establish scan 174 only from direct source.

## Source-specific recent forms

Preserve confirmed source forms such as `பொம்பளை`, `வளவுகளிலே`, `இடும்பனு`, `வேணும்`, `பார்க்கணுமா`, `இந்தஹாலில்`, `நாசிக்குத்தானே`, `சரக் சரக்`, `திகை சூழ்ந்தது`, `ஏமாற்றியிருக்கிறான்போலிருக்கிறது`, `தோற்றந்தான்`, `நீங்கள்தானு`, `கனைத்துக்கொண்டார்`, direct scan-171 `நயினு முகம்மது`, `முடிச்சுட்டேன்`, `பார்க்கலியே`, `இல்லீங்க`, `முழிச்சிகிட்டு`, `பண்ணினானுங்க`, `வம்புச் சண்டையெல்லாம்`, `விழுந்தா`, `போட்டுட்டு`, `இன்னேரம்`, `அவ தீர்ந்திருப்பா`, `கோட்டைக்குள்`, `குழி தோண்டினான்`, `மொந்தை`, `போயி`, `அங்கு தான்`, `ஒளிந்திருந்தாவது`, `மனப் போராட்டத்திற்கு`, `நாதியற்ற`, `நாலைந்து`, `சுமந்துவந்து கொண்டிருந்ததைச்`, and `சுடலைக்கு`.

## Exact next activity

Process **scans 174–178** in one bounded 5-page iteration. Do not start assembled Tamil or English.
