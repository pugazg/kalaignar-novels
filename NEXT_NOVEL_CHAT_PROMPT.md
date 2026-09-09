# Next Chat Prompt — வெள்ளிக்கிழமை

Continue directly in `pugazg/kalaignar-novels`, branch `main`, active work `works/vellikkizhamai/`. Live `main` is authoritative.

## Source

`TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf` — SHA-256 `ac241cbfbe3d47d76f22140f43c662176ba29a91521b826a1a8f5c75cf3081d3`, **179 scans**, image-only, second edition 1968. Do not commit it.

## Current durable state

- canonical records: **163 / 179**;
- Chapter 19 opens: **scan 149 / printed 148**, centered `19`;
- Chapter 20 opens: **scan 154 / printed 153**, centered `20`;
- Chapter 21 opens: **scan 160 / printed 159**, centered `21`;
- Chapter 21 transcribed through **scan 163 / printed 162**;
- historical-glyph coverage: **PASS scans 1–163**;
- next iteration: **scans 164–168**;
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

- scan 158 / 159: `வராத` + `கண்ணீர்,` = `வராத கண்ணீர்,`;
- scan 159 / 160: `அழகப்பனுக்கும்` → `ஒன்றும் புரியவில்லை.`;
- scan 160: Chapter 20 / 21 boundary, centered `21`;
- scan 160 / 161: `நமது தூய நட்பு` → `ஒரு பெண்ணால் பிரிக்கப்பட்டுவிட்டது...`;
- scan 161 ends complete `“சிந்தாமணி கைது செய்யப்பட்டிருப்பது எப்படி?” என்றான் அழகு.`;
- scan 162 bottom `11—A` is a printer/signature mark; narrative ends complete `ஆனந்தியின் அறையிலே கண்டார்கள்.`;
- scan 163 ends complete quoted accusation `கொலைகாரா!”`; establish scan 164 only from direct source.

## Source-specific recent forms

Preserve confirmed source forms such as `உள்ளங்`, `உதயமாயிற்று`, `ஜோடியாக`, `தம்பதிகளாக்குகிறேன்`, `குடிமுழுகிவிடவில்லை`, `இவ்வளவுதூரம்`, `இப்படி யொரு`, `தீயசக்தி`, `காதல்வீடு`, `மன்னித்துவிடடா`, `சூறாவளியை`, `பழி-பாவம்`, `பிராயச்சித்தம்`, `மனச்சாட்சியைக்`, `பத்தரைமாற்றுப் பசும்பொன்`, `அஸ்தமித்துப்போகும்`, `அவகாசமெடுத்துக்கொண்டு`, `அறைநோக்கிச்`, `புயலுக்குப்பின்`, `சண்டாளப்பட்டம்`, `மேனித்தின்மீது`, `காரண கர்த்தாவானேன்`, and `இருக்கவேண்டாமென்று`.

## Exact next activity

Process **scans 164–168** in one bounded 5-page iteration. Do not start assembled Tamil or English.
