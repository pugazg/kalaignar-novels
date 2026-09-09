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
- canonical records **173 / 179**;
- Chapter 18 opens: **scan 142 / printed 141**, centered `18`;
- Chapter 19 opens: **scan 149 / printed 148**, centered `19`;
- Chapter 20 opens: **scan 154 / printed 153**, centered `20`;
- Chapter 21 opens: **scan 160 / printed 159**, centered `21`;
- Chapter 22 opens: **scan 166 / printed 165**, centered `22`;
- Chapter 23 opens: **scan 172 / printed 171**, centered `23`;
- Chapter 23 transcribed through **scan 173 / printed 172**;
- historical-glyph coverage: **PASS scans 1–173**;
- next forward iteration: **scans 174–178**;
- batch size: **5 scans**;
- full Tamil source audit / assembled Tamil / English: **not started / not started / blocked**.

## Critical historical-glyph rule

Mandatory set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Identify character identity from source pixels first. Grammar is only a locator, never proof. Preserve source spelling, grammar, punctuation, spacing and colloquial forms. Never global-replace. The expanded corrective re-audit remains controlling; recurring **`நயினா`** remains unchanged except where direct source evidence on a later scan visibly prints another form.

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

## Latest durable results — scans 169–173

- scan 169 / printed 168: PASS; targeted enlargement resolves `நாசிக்குத்தானே`; preserve `பொம்பளை`, `வளவுகளிலே`, `இடும்பனு`, `வேணும்`, `பார்க்கணுமா`, `இந்தஹாலில்`, `சரக் சரக்`; ends `ஒலி வந்த திக்கையே நோக்கியவாறு`;
- scan 170 / printed 169: PASS; begins `அவள் எழுந்துநின்றாள்,`; targeted source review confirms old-type `னை` in `கனைத்துக்கொண்டார்`; preserve `திகை சூழ்ந்தது`, `ஏமாற்றியிருக்கிறான்போலிருக்கிறது`, `தோற்றந்தான்`, `நீங்கள்தானு`; ends `“எஜமான்!....இடும்பன்...”`;
- scan 171 / printed 170: PASS; begins `என்றான்.`; preserve direct source `நயினு முகம்மது`, `முடிச்சுட்டேன்`, `பார்க்கலியே`, `இல்லீங்க`, `முழிச்சிகிட்டு`, `பண்ணினானுங்க`; ends `வம்புச் சண்டையெல்லாம்`;
- scan 172 / printed 171: PASS; begins `நடந்தது.`; centered `23` opens Chapter 23; preserve `விழுந்தா`, `போட்டுட்டு`, `இன்னேரம்`, `அவ தீர்ந்திருப்பா`, `கோட்டைக்குள்`, `குழி தோண்டினான்`, `மொந்தை`, `போயி`; ends complete;
- scan 173 / printed 172: PASS; preserve `அங்கு தான்`, `ஒளிந்திருந்தாவது`, `மனப் போராட்டத்திற்கு`, `நாதியற்ற`, `நாலைந்து`, `சுமந்துவந்து கொண்டிருந்ததைச்`, `சுடலைக்கு`; source has no punctuation between first `சிந்தாமணி` and `ஒரு நாலைந்து பேர்`; ends physical `அவள் நெஞ்சிலே`.

No unresolved source holds remain through scan 173.

## New durable boundaries

- scan 169 / 170 `ஒலி வந்த திக்கையே நோக்கியவாறு` → `அவள் எழுந்துநின்றாள்,`;
- scan 170 / 171 `“எஜமான்!....இடும்பன்...”` → `என்றான்.`;
- scan 171 / 172 `வம்புச் சண்டையெல்லாம்` + `நடந்தது.` = `வம்புச் சண்டையெல்லாம் நடந்தது.`;
- scan 172 opens Chapter 23, centered `23`;
- scan 172 ends complete; scan 173 starts a new sentence;
- scan 173 ends physical `அவள் நெஞ்சிலே`.

All earlier structural/source decisions remain authoritative in `works/vellikkizhamai/audit.md` and `works/vellikkizhamai/indexes/page-map.md`.

## Exact next activity

1. re-fetch live `main`;
2. resolve controlling source;
3. process **scans 174–178** in one bounded 5-page iteration;
4. establish scan 174 only from direct source pixels after scan 173's physical `அவள் நெஞ்சிலே` ending;
5. run one batch glyph sweep and bounded ambiguity handling;
6. synchronize page records and status documents and commit atomically.

Do not start assembled Tamil or English.

## Completed works — preserve

- **பெரிய இடத்துப் பெண்**: source audit complete; assembled Tamil PASSED; English VERIFIED; release-ready with qualification.
- **புதையல்**: 448 canonical / 446 complete / 2 physical-loss `needs-review`; English VERIFIED; release-ready with qualification.
- **பலிபீடம் நோக்கி**: Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; release-ready.
