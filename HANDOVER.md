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
- canonical records **168 / 179**;
- Chapter 18 opens: **scan 142 / printed 141**, centered `18`;
- Chapter 19 opens: **scan 149 / printed 148**, centered `19`;
- Chapter 20 opens: **scan 154 / printed 153**, centered `20`;
- Chapter 21 opens: **scan 160 / printed 159**, centered `21`;
- Chapter 22 opens: **scan 166 / printed 165**, centered `22`;
- Chapter 22 transcribed through **scan 168 / printed 167**;
- historical-glyph coverage: **PASS scans 1–168**;
- next forward iteration: **scans 169–173**;
- batch size: **5 scans**;
- full Tamil source audit / assembled Tamil / English: **not started / not started / blocked**.

## Critical historical-glyph rule

Mandatory set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Identify character identity from source pixels first. Grammar is only a locator, never proof. Preserve source spelling, grammar, punctuation, spacing and colloquial forms. Never global-replace. The expanded corrective re-audit remains controlling; recurring **`நயினா`** and other independently source-confirmed forms remain unchanged.

## Production workflow

For each 5-scan batch:

1. fetch live `main` once;
2. transcribe all five full pages first;
3. run one batch-level mandatory 13-family glyph sweep;
4. allow at most one targeted enlargement for a genuinely unclear token;
5. if still unresolved, record a source hold and continue;
6. create five page records and synchronize audit/page-map/README/HANDOVER/prompt together;
7. make one atomic commit;
8. do not reopen prior PASS scans without new source evidence.

## Latest durable results — scans 164–168

- scan 164 / printed 163: PASS; preserve `எந்தசம்பந்தமுமில்லை`, `கன ரக`, `‘பூட்ஸ்’கள்`, `‘திபு திபு’`, `அடையாளங்`; ends `கத்தி`;
- scan 165 / printed 164: PASS; begins `னான்.` completing `கத்தினான்.`; preserve `கிழத் தாயார்`, `தியாகம்செய்யத்`, `கொலைத்துவிட்டான்`, `திகைப்பிலாழ்ந்த`; printed `* * *` divider; ends `அதற்குள்`;
- scan 166 / printed 165: PASS; begins direct continuation; centered `22` opens Chapter 22; preserve `அதிகப்படுத்திற்று`, `அபின்`, `விபச்சாரிப் பட்டத்தோடு`, `மனக்கோட்டை யெல்லாம்`, `மண் கோட்டைக்குள்ளே`; ends physical em-dash;
- scan 167 / printed 166: PASS; source-specific `அகப்பட்டாக`; targeted source review confirms `பாலகங்காதரத் தேவரின்`; preserve `ஐந்துமைல்`, `வழக்குபற்றி`, `அழகப்பனைப்பற்றியும்`, `இடங்கொடுக்கமாட்டார்களா`, `வெகுவிரைவில்`; ends `போய்ச் சேர்ந்து`;
- scan 168 / printed 167: PASS; begins `விடவேண்டுமென்ற`; preserve `சவச்சடங்குகளைச்`, source `சேதியாக`, `மானம் போனதேயென்று`, `குடும்பந்தான்`, `ஐந்துமைல்`, `மூன்றுமைல்`, `நிதானமாயில்லை`; ends complete sentence.

No unresolved source holds remain through scan 168.

## New durable boundaries

- scan 164 / 165 `கத்தி` + `னான்.` = `கத்தினான்.`;
- scan 165 printed `* * *` divider; ends `அதற்குள்`;
- scan 165 / 166 `அதற்குள்` → `யாரோ அந்த வேலையைச் செய்து முடித்துவிட்டார்கள்!`;
- scan 166 opens Chapter 22, centered `22`;
- scan 166 / 167 physical em-dash → direct source `அம்மாவின் பக்கத்திலே...`; no grammatical reconstruction;
- scan 167 / 168 `போய்ச் சேர்ந்து` → `விடவேண்டுமென்ற...`;
- scan 168 ends complete `அவனைக் கடந்து நடந்துகொண்டிருந்தாள்.`.

All earlier structural/source decisions remain authoritative in `works/vellikkizhamai/audit.md` and `works/vellikkizhamai/indexes/page-map.md`.

## Exact next activity

1. re-fetch live `main`;
2. resolve controlling source;
3. process **scans 169–173** in one bounded 5-page iteration;
4. establish scan 169 only from direct source pixels after scan 168's complete ending;
5. run one batch glyph sweep and bounded ambiguity handling;
6. synchronize page records and status documents and commit atomically.

Do not start assembled Tamil or English.

## Completed works — preserve

- **பெரிய இடத்துப் பெண்**: source audit complete; assembled Tamil PASSED; English VERIFIED; release-ready with qualification.
- **புதையல்**: 448 canonical / 446 complete / 2 physical-loss `needs-review`; English VERIFIED; release-ready with qualification.
- **பலிபீடம் நோக்கி**: Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; release-ready.
