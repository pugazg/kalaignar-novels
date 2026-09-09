# Next Chat Prompt — வெள்ளிக்கிழமை

Continue directly in `pugazg/kalaignar-novels`, branch `main`, active work `works/vellikkizhamai/`. Live `main` is authoritative.

## Source

`TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf` — SHA-256 `ac241cbfbe3d47d76f22140f43c662176ba29a91521b826a1a8f5c75cf3081d3`, **179 scans**, image-only, second edition 1968. Do not commit it.

## Current durable state

- canonical records: **168 / 179**;
- Chapter 20 opens: **scan 154 / printed 153**, centered `20`;
- Chapter 21 opens: **scan 160 / printed 159**, centered `21`;
- Chapter 22 opens: **scan 166 / printed 165**, centered `22`;
- Chapter 22 transcribed through **scan 168 / printed 167**;
- historical-glyph coverage: **PASS scans 1–168**;
- next iteration: **scans 169–173**;
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

- scan 164 / 165: `கத்தி` + `னான்.` = `கத்தினான்.`;
- scan 165 contains printed `* * *` divider and ends physical `அதற்குள்`;
- scan 165 / 166: `அதற்குள்` → `யாரோ அந்த வேலையைச் செய்து முடித்துவிட்டார்கள்!`;
- scan 166: Chapter 21 / 22 boundary, centered `22`;
- scan 166 / 167: physical em-dash → direct source `அம்மாவின் பக்கத்திலே...`; no grammatical reconstruction;
- scan 167 / 168: `போய்ச் சேர்ந்து` → `விடவேண்டுமென்ற...`;
- scan 168 ends complete `அவனைக் கடந்து நடந்துகொண்டிருந்தாள்.`; establish scan 169 only from direct source.

## Source-specific recent forms

Preserve confirmed source forms such as `எந்தசம்பந்தமுமில்லை`, `கன ரக`, `‘பூட்ஸ்’கள்`, `‘திபு திபு’`, `அடையாளங்`, `கிழத் தாயார்`, `தியாகம்செய்யத்`, `கொலைத்துவிட்டான்`, `திகைப்பிலாழ்ந்த`, `அதிகப்படுத்திற்று`, `அபின்`, `விபச்சாரிப் பட்டத்தோடு`, `மனக்கோட்டை யெல்லாம்`, `மண் கோட்டைக்குள்ளே`, `அகப்பட்டாக`, `பாலகங்காதரத் தேவரின்`, `ஐந்துமைல்`, `வழக்குபற்றி`, `அழகப்பனைப்பற்றியும்`, `இடங்கொடுக்கமாட்டார்களா`, `வெகுவிரைவில்`, `சவச்சடங்குகளைச்`, `சேதியாக`, `மானம் போனதேயென்று`, `குடும்பந்தான்`, `மூன்றுமைல்`, and `நிதானமாயில்லை`.

## Exact next activity

Process **scans 169–173** in one bounded 5-page iteration. Do not start assembled Tamil or English.
