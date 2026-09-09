# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`; branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Historical-glyph guide: `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`
- Current target: **வெள்ளிக்கிழமை** — `works/vellikkizhamai/`

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first and preserve newer durable work.

## Controlling source

`TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf` — SHA-256 `ac241cbfbe3d47d76f22140f43c662176ba29a91521b826a1a8f5c75cf3081d3`, **251,126,214 bytes**, **179 scans**, image-only, second edition 1968. Do not commit PDF.

## Current durable state

- manifest **179 / 179**;
- canonical records **179 / 179 — COMPLETE**;
- Chapter 23 opens **scan 172 / printed 171**, centered `23`;
- final narrative **scan 179 / printed 178**, ending `திரும்பினர்கள்.`;
- forward mandatory historical-glyph coverage **PASS scans 1–179**;
- unresolved source holds **0**;
- user-directed second historical-glyph re-audit **PENDING scans 119–179**;
- second re-audit next batch **119–123**, exactly 5 scans per iteration;
- full Tamil source audit / assembled Tamil / English: **blocked pending second re-audit / not started / blocked**.

## Critical historical-glyph rule

Mandatory set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Identify character identity from source pixels first. Grammar is only a locator, never proof. Preserve source spelling, grammar, punctuation, spacing and colloquial forms. Never global-replace.

## Final page-level results — scans 174–179

- scan 174 / printed 173: PASS; `விவரிக்கவொண்ண`, `வாசற்படிகூட`, `சனாதனி`, `பக்தசிரோன்மணியை`, `பாழ்வன மாக்கிவிட்டார்`, `நயினு முகம்மதும்`; ends `உண்மையான பாலகங்காதரத் தேவரை`;
- scan 175 / printed 174: PASS; `விமரிசையாக`, `‘திபு திபு’`, `இரத்தக் கறை`, `வந்து இறங்கினர்`; ends `போலீசார் அவரைச் சூழ்ந்து`;
- scan 176 / printed 175: PASS; begins `கொண்டார்கள்.`; `நயினு முகம்மதும்`, `நயினு முகம்மது`, `விளக்கினன்`, `வருந்தி வருந்தி`; ends complete `யூகம் தெரிவித்தான்.`;
- scan 177 / printed 176: PASS; `அள்ளி வீசினன்`, `நயினுவிடம்`, `அபின் கடத்தல் வழக்கில்`, `ருஜுவாகிவிட்டதென்றும்`, `தானொரு`;
- scan 178 / printed 177: PASS; `தழுதழுத்தது`, `தடாலெனத்`, `இழுமூச்சைத்தாள்`, `நயினுவும்`, `புள்ளி மயில்`; ends complete `வெள்ளிக்கிழமையிலே!`;
- scan 179 / printed 178: PASS; final `திரும்பினர்கள்.`; lower illustration and later handwriting are non-body.

No unresolved source holds remain through scan 179.

## User-directed second glyph re-audit

Required exact sequence:

`119–123 → 124–128 → 129–133 → 134–138 → 139–143 → 144–148 → 149–153 → 154–158 → 159–163 → 164–168 → 169–173 → 174–178 → 179`

For each iteration: source pixels first; all 13 families; only individually supported corrections; no global replace; document corrections or zero-correction PASS; do not start assembled Tamil until the entire 119–179 re-audit is complete.

## Exact next activity

Re-audit historical Tamil glyphs in **scans 119–123** and commit that five-page audit result atomically.

## Completed works — preserve

- **பெரிய இடத்துப் பெண்**: source audit complete; assembled Tamil PASSED; English VERIFIED; release-ready with qualification.
- **புதையல்**: 448 canonical / 446 complete / 2 physical-loss `needs-review`; English VERIFIED; release-ready with qualification.
- **பலிபீடம் நோக்கி**: Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; release-ready.
