# Next Chat Prompt — வெள்ளிக்கிழமை / full Tamil source audit

Continue directly in `pugazg/kalaignar-novels`, branch `main`, active work `works/vellikkizhamai/`. **LIVE MAIN IS AUTHORITATIVE.**

## Source

`TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf` — SHA-256 `ac241cbfbe3d47d76f22140f43c662176ba29a91521b826a1a8f5c75cf3081d3`, **179 scans**, image-only, second edition 1968. Do not commit it.

## Durable state

- canonical page records: **179 / 179 — COMPLETE**;
- final narrative: **scan 179 / printed 178**;
- forward mandatory historical-glyph coverage: **PASS scans 1–179**;
- unresolved source holds: **0**;
- second historical-glyph re-audit: **COMPLETE — scans 119–179 PASS / 61 of 61**;
- second-pass corrections: **5 total / 0 unresolved**;
- full Tamil source audit: **READY / NEXT — not started**;
- assembled Tamil / English: **not started / blocked pending Tamil source audit and assembly gate**.

## Completed controlling phase — second historical-Tamil-glyph re-audit

The user explicitly requested one more independent glyph audit from **scan 119 through the end**, exactly **5 scans per iteration**.

Sequence:

`119–123 ✓ → 124–128 ✓ → 129–133 ✓ → 134–138 ✓ → 139–143 ✓ → 144–148 ✓ → 149–153 ✓ → 154–158 ✓ → 159–163 ✓ → 164–168 ✓ → 169–173 ✓ → 174–178 ✓ → 179 ✓`

Mandatory families on every scan:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Rules:
1. source pixels first; grammar only a locator;
2. compare each canonical page record against the source scan;
3. no global replacements or silent normalization;
4. one targeted enlargement per genuinely unclear token if needed;
5. if still unresolved, record a source hold instead of guessing;
6. record every correction, or explicitly record zero-correction PASS;
7. update affected page records plus `audit.md`, page map / README / HANDOVER / this prompt when phase state changes;
8. one atomic commit per 5-scan iteration;
9. do not start assembled Tamil or English until the entire second re-audit 119–179 is complete.

## Completed second-pass batches

- **119–123:** PASS — 0 corrections / 0 unresolved.
- **124–128:** PASS — 0 corrections / 0 unresolved. Preserve `புகை` → `வண்டி`, centered `16` on scan 127, and `வாழ்` → `விலே`.
- **129–133:** PASS — 0 corrections / 0 unresolved. Preserve `அழகப்ப` → `னுடைய`, scan 130 bottom `9` as a printer/signature mark, and `பின்னிக்` → `கொண்டன`.
- **134–138:** PASS — 0 corrections / 0 unresolved. Preserve centered `17`, `நயினாவின்` → `கேள்வி`, `வருத்தத்` → `தோடு`, `“இதோ,` → `கொண்டுவருகிறேன்”`, and final `‘மளமள’`.
- **139–143:** PASS — 0 corrections / 0 unresolved. Preserve `‘மளமள’` → `வென்று`, `புயலால் தாக்குண்டவன்போல` → `ஆனேன் அன்று!`, `நயினா` → `எதுவும் பேசவில்லை.`, centered `18`, and `வாசகங்கள்` → `இருந்தன`.
- **144–148:** PASS — 0 corrections / 0 unresolved. Preserve `வரவழைத்துக்` + `கொண்டான்`, scan 146 bottom `10` printer/signature mark, `கூறியதுதான்` + `தாமதம்;`, and `சந்திப்` + `பதற்காக!`.
- **149–153:** PASS — 1 correction / 0 unresolved. All historical-glyph identities pass; scan 151 source punctuation corrected `அங்கே வந்து.` → `அங்கே வந்து,`. Preserve centered `19`, `புறப்` + `பட்டுவிட்டாயே!`, `தேவ` + `லோகத்தில்`, and `வழக்கமாக உறங்கும்` → `அறைக்கல்லவா போகிறாள்!`.
- **154–158:** PASS — 0 corrections / 0 unresolved. Preserve centered `20` on scan 154, `சோலை` + `யில்`, literal `தலையிலும் காயம்` → `நயினா எதிர்த்தே அடிக்கவில்லை.` without reconstruction, `பயங்கரமாக—` → `ஆனந்தியிருக்கும் அறையை நோக்கி நடக்கத் தொடங்கினாள்.`, and `வராத` + `கண்ணீர்,`.
- **159–163:** PASS — 1 correction / 0 unresolved. Closed on the user's explicit instruction using the existing direct-source forward audit plus the user's direct-source correction on scan 163. Corrected `ஆனந்தியின் மேனித்தின்மீது` → `ஆனந்தியின் பிணத்தின் மீது`. Preserve `வராத` + `கண்ணீர்,`, `அழகப்பனுக்கும்` → `ஒன்றும் புரியவில்லை.`, centered `21`, `நமது தூய நட்பு` → `ஒரு பெண்ணால் பிரிக்கப்பட்டுவிட்டது`, and scan 162 bottom `11—A`.
- **164–168:** PASS — 3 corrections / 0 unresolved. User direct-source corrections: scan 164 `நயினாவில்` → `நயினாவால்`; scan 164 `“என் சார்?”` → `“ஏன் சார்?”`; scan 165 `அவனது சவம்` → `அவளது சவம்`. Preserve `கத்தி` + `னான்.`, `அதற்குள்` → `யாரோ அந்த வேலையைச் செய்து முடித்துவிட்டார்கள்!`, centered `22`, the scan 166 / 167 physical em-dash, and `போய்ச் சேர்ந்து` + `விடவேண்டுமென்ற`.
- **169–173:** PASS — 0 corrections / 0 unresolved. Closed on the user's instruction using the existing direct-source forward audit. Preserve source-specific scan-171 `அங்கிருந்த வாறு`, `ஒலி வந்த திக்கையே நோக்கியவாறு` → `அவள் எழுந்துநின்றாள்,`, `“எஜமான்!....இடும்பன்...”` → `என்றான்.`, `வம்புச் சண்டையெல்லாம்` + `நடந்தது.`, centered `23`, and scan 173 physical end `அவள் நெஞ்சிலே`.
- **174–178:** PASS — 0 corrections / 0 unresolved. Closed using the already-completed direct-source forward audit. Preserve `அவள் நெஞ்சிலே` → `எழுந்த குமுறல்கள்!...`, `உண்மையான பாலகங்காதரத் தேவரை` → `சிக்கவைக்கவேண்டுமென்றும்,`, `போலீசார் அவரைச் சூழ்ந்து` → `கொண்டார்கள்.`, plus source forms `பாழ்வன மாக்கிவிட்டார்`, `நயினு முகம்மதும்`, `வந்து இறங்கினர்`, `விளக்கினன்`, `வருந்தி வருந்தி`, `அள்ளி வீசினன்`, and `இழுமூச்சைத்தாள்`.
- **179:** PASS — 0 corrections / 0 unresolved. Preserve final `திரும்பினர்கள்.`; lower printed illustration and faint later handwriting remain non-body material. **Second re-audit COMPLETE — 61/61 scans, 5 total corrections, 0 unresolved.**

## Exact next activity

Begin the **full Tamil source audit** before assembled Tamil. Follow `NOVEL_PROCESSING_GUIDE.md` and use `works/balipeedam-nokki/` only as a structural reference. Check the complete canonical `pages/` layer for:

1. scan coverage **179 / 179** and continuous records;
2. `verified` / unresolved status consistency;
3. single-work identity and chapter/section structure;
4. printed-page map and known source exceptions;
5. all durable cross-page joins without silent reconstruction;
6. the five second-pass source corrections and all source-specific forms;
7. printed text vs illustration / handwriting / printer-signature marks separation;
8. consistency among page records, `metadata/source.md`, `indexes/page-map.md`, README and `audit.md`.

When all checks pass, mark the **Tamil source layer PASSED**. Only after that may the assembled Tamil `sections/` layer begin. Do not start English translation yet.

Do not reopen the completed 119–179 second glyph re-audit without new direct-source evidence.
