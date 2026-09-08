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
- canonical records **128 / 179**;
- Chapter 12 / 13 boundary: **scan 107 / printed 106**, centered `13`;
- Chapter 13 / 14 boundary: **scan 115 / printed 114**, centered `14`;
- Chapter 14 / 15 boundary: **scan 120 / printed 119**, centered `15`;
- Chapter 16 transcribed through **scan 128 / printed 127**;
- historical-glyph coverage: **PASS scans 1–128**;
- next forward iteration: **scans 129–133**;
- batch size: **5 scans per iteration**;
- full Tamil source audit / assembled Tamil / English: **not started / not started / blocked**.

## Critical historical-glyph rule

Mandatory set on every scan:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Identify character identity from enlarged/native source pixels first. Grammar is only a locator, never proof. Preserve source spelling, grammar, punctuation, spacing and colloquial forms. Never global-replace.

### Expanded corrective re-audit — controlling lesson

Earlier audit status falsely classified multiple old-type `னா` / `றா` shapes as genuine short-looking `னன்` / `னள்` / `னு` forms. Those claims are superseded by source-pixel comparison and the corrected canonical records.

Do **not** convert by grammar. Independently confirmed source-specific forms remain, including `வேலையில்ல`, `வரணும்`, `நானு`, recurring **`நயினா`**, scan 114 **`அப்படித்தான் ஆவள்`**, and the source-specific spellings and physical discontinuities preserved on scans 119–128.

An apparent `னன்` / `னள்` / `னு` must be compared with same-edition historical type at enlarged/native resolution before it can be called genuine.

## Historical-glyph coverage

- scans **1–101**: retrospective audit performed;
- scans **102–111**: corrective audit performed;
- scans **112–118**: forward audit performed;
- expanded corrective re-audit repaired old-type `னா` / `றா` misses across the existing corpus;
- scans **119–128**: mandatory forward source-pixel audit performed;
- canonical scans **1–128 are PASS**.

## Recent forward results

- scan 119: continues source-visible `வருகிறேன்.........`; `ஓடினாள்` confirmed; preserve `பதைக்`, `வஞ்சங்`, `நச்சரவு`, `ஜாடையாக`; ends `கவனித்து`;
- scan 120: begins `விட்டான்.`; mixed Chapter 14 / 15 with centered `15`; `நின்றாள்` and one `எண்ணினான்` confirmed; previous “both `எண்ணினான்`” target note superseded; separate `ஏங்கினான்` retained;
- scan 121: `குமுறினாள்`, `அலறினாள்`, both `ஓடினான்`; preserve `கரந்தொட்டுப்`, `ஆத்திரமனைத்தையும்`, `புறப்படத்தயாராக`; ends `வண்டியில்`;
- scan 122: `வருகிறானா`, `போகிறாள்`, `கிளம்பியிருக்கிறாள்`; preserve `தீமரென`, `தொத்திக்கொண்டான்`, `பலகணி`; ends `சிந்தாமணி, அவளுக்குப் பக்கத்திலே`;
- scan 123: literal physical opening `கார்ந்து கொண்டாள்.` retained; `நோக்கினாள்`, `நன்றாகக்`, `தோன்றினாள்`; disputed lexical clusters resolved as `மாது சிரோன்மணி`, `தண்டனைகளையெல்லாம்விட`, `கதவண்டை`; ends `கவனித்தாள்.`;
- scan 124: `வயதானவளை`, `ஏற்றிக்கொண்டிருந்தான்`; ends `புகை`;
- scan 125: begins `வண்டி` → cross-page `புகைவண்டி`; preserve `சூடேறிவிட்டது`, `வனைத்`, `அழகப்பனைத்`;
- scan 126: `நாலைந்து`, `திடுதிடுவென`, `ஏறினார்கள்`, `கதவண்டை`;
- scan 127: Chapter 16 opening centered `16`; preserve `புறக்கூடு`, `புடைசூழ`; ends `வாழ்`;
- scan 128: begins `விலே` → cross-page `வாழ்விலே`; preserve `அவனைச் சூழ்ந்தது`; ends `ஏறும்போது`.

## Preserve structural/source decisions

- scan 33 Chapter 3 / 4, centered `4`;
- scan 45 Chapter 4 / 5, centered `5`;
- scan 52 Chapter 6 opening, centered `6`;
- scan 59 Chapter 6 / 7, centered `7`;
- scan 66 visible printed number only `5`;
- scan 68 Chapter 7 / 8, centered `8`;
- scan 75 Chapter 8 / 9, centered `9`;
- scan 82 bottom `6` printer/signature mark;
- scan 85 Chapter 9 / 10, centered `10`;
- scan 89 / 90 `மறுத்துவிட்` + `டால்`;
- scan 92 Chapter 10 / 11, centered `11`;
- scan 98 bottom `7` printer/signature mark;
- scan 99 Chapter 11 / 12, centered `12`;
- scan 107 Chapter 12 / 13, centered `13`;
- scan 111 / 112 `சிறிதா` + `வது`;
- scan 114 bottom `8` printer/signature mark;
- scan 115 Chapter 13 / 14, centered `14`;
- scan 117 / 118 literal `உட்` → `எவ்வளவோ...` source discontinuity;
- scan 118 / 119 open dialogue continuation;
- scan 119 / 120 `கவனித்து` → `விட்டான்.`;
- scan 120 Chapter 14 / 15, centered `15`;
- scan 121 / 122 `வண்டியில்` → `ஒரே கூட்டம்.`;
- scan 122 / 123 literal `...அவளுக்குப் பக்கத்திலே` → `கார்ந்து கொண்டாள்.`; no grammatical reconstruction;
- scan 124 / 125 `புகை` + `வண்டி` = `புகைவண்டி`;
- scan 127 Chapter 16 opening, centered `16`;
- scan 127 / 128 `வாழ்` + `விலே` = `வாழ்விலே`;
- scan 128 ends `ஏறும்போது`.

## Exact next activity

1. re-fetch live `main`;
2. resolve controlling source;
3. process **scans 129–133** in one 5-page iteration;
4. preserve scan 128 / 129 continuity directly from source pixels;
5. transcribe all five pages first, then run one mandatory 13-family batch sweep;
6. allow at most one targeted enlargement per genuinely unclear token; if still unresolved, record a source hold and continue;
7. preserve source wording and physical boundaries; never infer from grammar or global-replace;
8. synchronize page records, audit, page-map, README/status/handover documents and commit.

Do not start assembled Tamil or English.

## Completed works — preserve

- **பெரிய இடத்துப் பெண்**: source audit complete; assembled Tamil PASSED; English VERIFIED; release-ready with qualification.
- **புதையல்**: 448 canonical / 446 complete / 2 physical-loss `needs-review`; English VERIFIED; release-ready with qualification.
- **பலிபீடம் நோக்கி**: Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; release-ready.
