# Next Chat Prompt — வெள்ளிக்கிழமை

Continue directly in `pugazg/kalaignar-novels`, branch `main`, active work `works/vellikkizhamai/`. Live `main` is authoritative.

## Source

`TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf` — SHA-256 `ac241cbfbe3d47d76f22140f43c662176ba29a91521b826a1a8f5c75cf3081d3`, **179 scans**, image-only, second edition 1968. Do not commit it.

## Current durable state

- canonical records: **148 / 179**;
- Chapter 16 / 17 boundary: **scan 134 / printed 133**, centered `17`;
- Chapter 18 opens: **scan 142 / printed 141**, centered `18`;
- Chapter 18 transcribed through **scan 148 / printed 147**;
- historical-glyph coverage: **PASS scans 1–148**;
- next iteration: **scans 149–153**;
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

- scan 142: Chapter 18 opening, centered `18`;
- scan 142 / 143: `வாசகங்கள்` → `இருந்தன.`;
- scan 144 / 145: `வரவழைத்துக்` + `கொண்டான்` = `வரவழைத்துக் கொண்டான்`;
- scan 145 / 146: `ஏது` → `அவ்வளவு அக்கறை!`;
- scan 146 bottom `10` printer/signature mark;
- scan 146 / 147: `கூறியதுதான்` + `தாமதம்;` = `கூறியதுதான் தாமதம்;`;
- scan 147 / 148: `சந்திப்` + `பதற்காக!` = `சந்திப்பதற்காக!`;
- scan 148 ends a complete sentence; establish scan 149 only from direct source.

## Source-specific recent forms

Preserve confirmed source forms such as `தவறுக் கருதிவிட்டானே`, `ஆள்மயக்கும்`, `தவறுக் கருத்துக்கூடும்`, `காற்று வாக்கில்`, `புளகாங்கித மூட்டுவனவாக`, `இளந் தாடியுடனும்`, `பட்டுச் சொக்காய்`, `பெங்களூர் பெரியசாமின்னு`, `மிரளமிரள`, `என்றைக்கிருந்தாலும்`, `கூட்டிட்டாள்`, `சிற்றவள்`, `செந்தேள்கள்`, `விறிட்டுக்`, and `நிம்மதியாக`.

## Exact next activity

Process **scans 149–153** in one bounded 5-page iteration. Do not start assembled Tamil or English.
