# கலைஞர் புதினங்கள் / கதைநூல்கள் — மின்னாக்கக் களஞ்சியம்

கலைஞர் மு. கருணாநிதியின் புதினங்கள், வரலாற்றுக் கதைகள் மற்றும் தொடர்புடைய கதைநூல்களை source provenance காக்கும் வகையில் Markdown வடிவில் பாதுகாக்கும் களஞ்சியம்.

## மூலக் கொள்கை

> **மூல ஸ்கேன் page/structure authority.** Source PDF / split PDF / uploaded baseline files repository-யில் commit செய்யப்படாது.

## Project continuation documents

- [`NOVEL_PROCESSING_GUIDE.md`](NOVEL_PROCESSING_GUIDE.md)
- [`HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`](HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md)
- [`HANDOVER.md`](HANDOVER.md)
- [`NEXT_NOVEL_CHAT_PROMPT.md`](NEXT_NOVEL_CHAT_PROMPT.md)

## Active work

### [வெள்ளிக்கிழமை](works/vellikkizhamai/README.md)

- source edition: **இரண்டாம் பதிப்பு, 1968**;
- source cover author form: **மு. கருணாநிதி**;
- publisher: **திராவிடப்பண்ணை**;
- source PDF: `TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf`;
- actual PDF scans: **179**;
- page manifest: **179 / 179 represented**;
- canonical page records: **133 / 179**;
- Chapter 12 / 13 boundary: **scan 107 / printed 106**, centered `13`;
- Chapter 13 / 14 boundary: **scan 115 / printed 114**, centered `14`;
- Chapter 14 / 15 boundary: **scan 120 / printed 119**, centered `15`;
- Chapter 16 transcribed through **scan 133 / printed 132**;
- historical-glyph coverage on existing canonical scans: **PASS scans 1–133**;
- forward transcription: **next 5-page iteration scans 134–138**;
- full Tamil source audit: **not started**;
- assembled Tamil: **not started**;
- English translation: **blocked until Tamil gate passes**.

### Historical Tamil glyph handling

Use [`HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`](HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md). Mandatory family set on every scan:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Identify character identity from source pixels first. Grammar is only a locator. Preserve source spelling, grammar, punctuation, spacing and colloquial forms. Never global-replace.

The expanded corrective re-audit overturned earlier false “genuine counterexample” readings caused by old-type `னா` / `றா` shapes. This is not a grammar-normalization rule. Independently source-confirmed forms such as `வேலையில்ல`, `வரணும்`, `நானு`, recurring **`நயினா`**, scan 114 `அப்படித்தான் ஆவள்`, and source-specific forms on scans 119–133 remain unchanged.

### Recent forward results

- scan 119 / printed 118: PASS; continues `வருகிறேன்.........`; source-confirmed `ஓடினாள்`; ends `கவனித்து`;
- scan 120 / printed 119: PASS; begins `விட்டான்.`; mixed Chapter 14 / 15, centered `15`; source-confirmed `நின்றாள்` and one `எண்ணினான்`; separate `ஏங்கினான்` retained;
- scan 121 / printed 120: PASS; `குமுறினாள்`, `அலறினாள்`, both `ஓடினான்`; ends `வண்டியில்`;
- scan 122 / printed 121: PASS; `வருகிறானா`, `போகிறாள்`, `கிளம்பியிருக்கிறாள்`; ends `சிந்தாமணி, அவளுக்குப் பக்கத்திலே`;
- scan 123 / printed 122: PASS; literal opening `கார்ந்து கொண்டாள்.` retained; `நோக்கினாள்`, `நன்றாகக்`, `தோன்றினாள்`; source-resolved `மாது சிரோன்மணி`, `தண்டனைகளையெல்லாம்விட`, `கதவண்டை`.

- scan 124 / printed 123: PASS; `வயதானவளை`, `ஏற்றிக்கொண்டிருந்தான்`; ends literal `புகை`;
- scan 125 / printed 124: PASS; begins `வண்டி`, completing cross-page `புகைவண்டி`; `வனைத்`, `அழகப்பனைத்`;
- scan 126 / printed 125: PASS; `நாலைந்து`, `ஏறினார்கள்`, `கதவண்டை`;
- scan 127 / printed 126: PASS; Chapter 16 opening, centered `16`; `புறக்கூடு`, `புடைசூழ`; ends literal `வாழ்`;
- scan 128 / printed 127: PASS; begins `விலே`, completing cross-page `வாழ்விலே`; `அவனைச் சூழ்ந்தது`; ends `ஏறும்போது`.
- scan 129 / printed 128: PASS; begins `அவளை`, directly continuing scan 128 `ஏறும்போது`; preserve `விழலுக்கிறைத்த`, `மனிதப்புழு`, `சிந்துவாற்றுச்`; ends literal `அழகப்ப`;
- scan 130 / printed 129: PASS; begins `னுடைய`, completing cross-page `அழகப்பனுடைய`; same-edition historical `நயினா`; preserve source `மங்காகர`; bottom `9` printer/signature mark;
- scan 131 / printed 130: PASS; same-edition `நயினாமுகம்மது`, `நயினாவின்`; ends literal `பின்னிக்`;
- scan 132 / printed 131: PASS; begins `கொண்டன;`, completing cross-page `பின்னிக்கொண்டன`; same-edition `நயினாவிடமிருந்து`; both source `என்றால்` retained;
- scan 133 / printed 132: PASS; same-edition `நயினா முகம்மது`, `நயினாவுக்கு`; historical `நகை நட்டுக்களை`; ends a complete sentence.

## Completed works

| நூல் | நிலை |
|---|---|
| பெரிய இடத்துப் பெண் | **49/49 canonical complete; Tamil source audit complete; assembled Tamil PASSED; English VERIFIED; release-ready with qualification** |
| புதையல் | **448 canonical / 446 complete / 2 physical-loss `needs-review`; English VERIFIED; release-ready with qualification** |
| பலிபீடம் நோக்கி | **Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; release-ready** |

## Next activity

Process **scans 134–138** as one 5-page forward iteration using the bounded production workflow: full-page transcription first, one 5-page glyph sweep, and at most one targeted enlargement per genuinely unclear token before recording a source hold. Preserve the new durable boundaries `அழகப்ப` + `னுடைய` = `அழகப்பனுடைய` and `பின்னிக்` + `கொண்டன` = `பின்னிக்கொண்டன`. Do not start assembled Tamil or English.
