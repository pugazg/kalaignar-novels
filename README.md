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
- canonical page records: **123 / 179**;
- Chapter 12 / 13 boundary: **scan 107 / printed 106**, centered `13`;
- Chapter 13 / 14 boundary: **scan 115 / printed 114**, centered `14`;
- Chapter 14 / 15 boundary: **scan 120 / printed 119**, centered `15`;
- Chapter 15 transcribed through **scan 123 / printed 122**;
- historical-glyph coverage on existing canonical scans: **PASS scans 1–123**;
- forward transcription: **next 5-page iteration scans 124–128**;
- full Tamil source audit: **not started**;
- assembled Tamil: **not started**;
- English translation: **blocked until Tamil gate passes**.

### Historical Tamil glyph handling

Use [`HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`](HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md). Mandatory family set on every scan:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Identify character identity from source pixels first. Grammar is only a locator. Preserve source spelling, grammar, punctuation, spacing and colloquial forms. Never global-replace.

The expanded corrective re-audit overturned earlier false “genuine counterexample” readings caused by old-type `னா` / `றா` shapes. This is not a grammar-normalization rule. Independently source-confirmed forms such as `வேலையில்ல`, `வரணும்`, `நானு`, recurring **`நயினா`**, scan 114 `அப்படித்தான் ஆவள்`, and source-specific forms on scans 119–123 remain unchanged.

### Recent forward results

- scan 119 / printed 118: PASS; continues `வருகிறேன்.........`; source-confirmed `ஓடினாள்`; ends `கவனித்து`;
- scan 120 / printed 119: PASS; begins `விட்டான்.`; mixed Chapter 14 / 15, centered `15`; source-confirmed `நின்றாள்` and one `எண்ணினான்`; separate `ஏங்கினான்` retained;
- scan 121 / printed 120: PASS; `குமுறினாள்`, `அலறினாள்`, both `ஓடினான்`; ends `வண்டியில்`;
- scan 122 / printed 121: PASS; `வருகிறானா`, `போகிறாள்`, `கிளம்பியிருக்கிறாள்`; ends `சிந்தாமணி, அவளுக்குப் பக்கத்திலே`;
- scan 123 / printed 122: PASS; literal opening `கார்ந்து கொண்டாள்.` retained; `நோக்கினாள்`, `நன்றாகக்`, `தோன்றினாள்`; source-resolved `மாது சிரோன்மணி`, `தண்டனைகளையெல்லாம்விட`, `கதவண்டை`.

## Completed works

| நூல் | நிலை |
|---|---|
| பெரிய இடத்துப் பெண் | **49/49 canonical complete; Tamil source audit complete; assembled Tamil PASSED; English VERIFIED; release-ready with qualification** |
| புதையல் | **448 canonical / 446 complete / 2 physical-loss `needs-review`; English VERIFIED; release-ready with qualification** |
| பலிபீடம் நோக்கி | **Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; release-ready** |

## Next activity

Process **scans 124–128** as one 5-page forward iteration. Re-establish scan 123 / 124 continuity from the controlling source and apply direct source-pixel historical-glyph checks on every scan. Do not start assembled Tamil or English.
