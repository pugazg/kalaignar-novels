# கலைஞர் புதினங்கள் / கதைநூல்கள் — மின்னாக்கக் களஞ்சியம்

கலைஞர் மு. கருணாநிதியின் புதினங்கள், வரலாற்றுக் கதைகள் மற்றும் தொடர்புடைய கதைநூல்களை source provenance காக்கும் வகையில் Markdown வடிவில் பாதுகாக்கும் களஞ்சியம்.

## மூலக் கொள்கை

> **மூல ஸ்கேன் page/structure authority. புதையல் scan 280 onward lexical words user-supplied Gemini baseline-ல் இருந்து source-correct செய்யப்படாது; complete baseline omission இருந்தால் explicit user disposition தேவை.**

Source PDF / split PDF / uploaded baseline files repository-யில் commit செய்யப்படாது.

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
- canonical page records: **111 / 179**;
- Chapter 12/13 boundary: **scan 107 / printed 106**, centered `13`;
- Chapter 13 transcribed through **scan 111 / printed 110**;
- **historical-glyph work-level gate REOPENED** after a systematic old-type decoding error was found;
- corrective historical-glyph re-audit: **PASS scans 102–111**;
- retrospective historical-glyph re-audit: **PASS scans 1–45; pending scans 46–101**;
- full Tamil source audit: **not started**;
- assembled Tamil: **not started**;
- English translation: **blocked until Tamil gate passes**.

### Retrospective glyph audit — durable summary

All retrospective scans explicitly test the mandatory old-type families `ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ` from enlarged/native source pixels. Grammar is only a locator; source wording is not normalized and no global replacement is permitted.

- scans **1–35**: PASS; scan 4 additionally received ordinary source correction `பெருகிடுகிறது` → `பெருகிவிடுகிறது`; confirmed counterexamples/source forms include `வேலையில்ல`, `வந்துவிட்டானு`, `வரணும்`, `வயதினள்`, `காணோமே`, `பெண்ணொருத்தி`, `அவ்விதமானாள்`, `நட்டுவனார்`, and recurring `நயினா`;
- scans **36–40**: PASS after scan 38 `கண்ணின் மிகுதியால்` → `களைப்பின் மிகுதியால்`, and scan 40 `எண்ணையாவது` → `என்னையாவது`, `அவர்களோ` → `அவர்களை`, `கைவற்றுப்போனேன்` → `கைவற்றுப்போனான்`;
- scans **41–45**: PASS with no historical-family substitution; scan 42 separately corrected ordinary source text `பொறுத்துச்` → **`பொருத்தம்`** and `சுதன` → **`சனதன`**. Scan 45 remains the mixed Chapter 4 / Chapter 5 boundary with centered `5`.

Corrective scans **102–111** remain controlling for the known failure mode, including `நன்றாகக்`, `தவறாக`, `என்றாள்`, missing-`ஆ` corrections, `சொன்னா`, and `பெண்ணா?`.

### Durable source decisions

- recurring character name **`நயினா`**, not `நயினு`;
- scan 23 `வயதினள்` is genuine;
- scan 27 `காணோமே` confirms `ணோ`;
- scan 30 `பெண்ணொருத்தி` confirms `ணொ`;
- scan 38 source phrase is `களைப்பின் மிகுதியால்`;
- scan 40 source forms are `என்னையாவது`, `அவர்களை`, `கைவற்றுப்போனான்`;
- scan 42 source wording includes `பொருத்தம் சரியில்லை` and `சனதன உள்ளம்`;
- scan 45 has centered Chapter 5 heading `5`;
- scan 66 visibly prints only page number `5`; no `65` is inferred;
- scan 98 bottom standalone `7` is a printer/signature mark;
- scan 111 ends physical `சிறிதா`; scan 112 begins source-visible `வது`.

## Completed works

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [பெரிய இடத்துப் பெண்](works/periya-idathup-pen/README.md) | மு. கருணாநிதி | எட்டாம் பதிப்பு, ஜூலை 1953 | **49/49 canonical pages complete; full Tamil source audit COMPLETE; assembled Tamil PASSED; English VERIFIED; release-ready with canonical-Tamil verification qualification** |
| [புதையல்](works/pudhaiyal/README.md) | கலைஞர் மு. கருணாநிதி, எம். எல். ஏ. | மூன்றாம் பதிப்பு, செப்டம்பர் 1961 | **448 canonical / 446 verified-complete / 2 physical-loss `needs-review`; English VERIFIED; repository package RELEASE-READY WITH QUALIFICATION** |
| [பலிபீடம் நோக்கி](works/balipeedam-nokki/README.md) | மு. கருணாநிதி | முதல் பதிப்பு, ஏப்ரல் 1947 | **Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; archival package RELEASE-READY** |

## Historical Tamil glyph handling

Use [`HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`](HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md). Identify the historical character identity from source pixels first, then encode that identity in modern Unicode. Minimum set: `ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`. Never global-replace.

## Next activity

Continue the retrospective historical-glyph re-audit in the next 5-scan batch: **scans 46–50**. Forward transcription at scan 112 remains paused until scans 1–101 are cleared.

## Release-status meaning

Repository release-readiness is an editorial/archival workflow status. It is not a determination of copyright, licensing, distribution or public-domain status.
