# Next Chat Prompt — வெள்ளிக்கிழமை / second historical-glyph re-audit

Continue directly in `pugazg/kalaignar-novels`, branch `main`, active work `works/vellikkizhamai/`. **LIVE MAIN IS AUTHORITATIVE.**

## Source

`TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf` — SHA-256 `ac241cbfbe3d47d76f22140f43c662176ba29a91521b826a1a8f5c75cf3081d3`, **179 scans**, image-only, second edition 1968. Do not commit it.

## Durable state

- canonical page records: **179 / 179 — COMPLETE**;
- final narrative: **scan 179 / printed 178**;
- forward mandatory historical-glyph coverage: **PASS scans 1–179**;
- unresolved source holds: **0**;
- second historical-glyph re-audit: **IN PROGRESS — scans 119–163 PASS / 45 of 61 complete**;
- second-pass corrections through scan 163: **2**;
- assembled Tamil / English: **not started / blocked**.

## Controlling phase — second historical-Tamil-glyph re-audit

The user explicitly requested one more independent glyph audit from **scan 119 through the end**, exactly **5 scans per iteration**.

Sequence:

`119–123 ✓ → 124–128 ✓ → 129–133 ✓ → 134–138 ✓ → 139–143 ✓ → 144–148 ✓ → 149–153 ✓ → 154–158 ✓ → 159–163 ✓ → 164–168 → 169–173 → 174–178 → 179`

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

## Exact next activity

Batch **164–168** has been started: canonical records for all five scans are loaded. Continue source-level verification for these five scans only. Preserve:

- scan 164 / 165: `கத்தி` + `னான்.` = `கத்தினான்.`;
- scan 165 / 166: `அதற்குள்` → `யாரோ அந்த வேலையைச் செய்து முடித்துவிட்டார்கள்!`;
- scan 166 centered `22` opens Chapter 22 after Chapter 21 text on the same scan;
- scan 166 / 167: preserve the physical em-dash and direct source continuation;
- scan 167 / 168: `போய்ச் சேர்ந்து` + `விடவேண்டுமென்ற`.

Before closing 164–168, directly confirm these source readings because they are suspicious but must not be grammar-corrected without evidence:

- scan 164: `நயினாவில்`;
- scan 164: `என் சார்?`;
- scan 165: `அவனது சவம்`.

Do not reopen scans 119–163 without new direct source evidence. Do not start assembled Tamil or English.
