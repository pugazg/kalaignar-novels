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
- canonical page records: **91 / 179 — all 91 verified**;
- scans 1–3 front matter: **verified**;
- Chapters 1–3: **verified through scan 33 carryover**;
- Chapter 4: **scan 33 opening through scan 45 pre-heading carryover — verified**;
- Chapter 5: **scan 45 below heading `5` through scan 51 — verified**;
- Chapter 6: **scan 52 through scan 59 pre-heading carryover — verified**;
- Chapter 7: **scan 59 below heading `7` through scan 68 pre-heading carryover — verified**;
- Chapter 8: **scan 68 below heading `8` through scan 75 pre-heading carryover — verified**;
- Chapter 9: **scan 75 below heading `9` through scan 85 pre-heading carryover — verified**;
- Chapter 10: **scan 85 below heading `10` through scan 91 — verified continuation**;
- historical-glyph/source-sensitive checks: **PASS through scan 91**;
- full Tamil source audit: **not started**;
- assembled Tamil: **not started**;
- English translation: **blocked until Tamil gate passes**;
- next 5-scan iteration: **scans 92–96**.

### Durable name correction — `நயினா`

The recurring character name is **`நயினா`**, not `நயினு`. Reinspection of the controlling scan shows that the historical `னா` typeform had been misread as `னு`. Scan 34 directly gives the same-edition witness `நயினா என்பது நயினாமுகம்மது என்ற பெயரின் சுருக்கம்`. Canonical scans 34–91 use `நயினா`; future transcription must not regress to `நயினு`.

### Source-number anomaly — scan 66

Scan **66** visibly prints only **`5`** at the page-number positions; no tens digit is present even under enlarged/native inspection. Canonical `printed_page` therefore records the visible source value `5` rather than silently inferring `65`. Scans 67–91 then visibly print `66–90`.

### Completed 5-scan batch — scans 87–91

Scans **87–91 / printed 86–90** are verified Chapter 10 continuation. Physical continuities are preserved, including scan 89 `மறுத்துவிட்` → scan 90 `டால்`, and scan 91's final `என்று எட்டணா பணத்தையும்` continuing onto scan 92. Every page passed the mandatory historical-glyph gate.

## Completed works

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [பெரிய இடத்துப் பெண்](works/periya-idathup-pen/README.md) | மு. கருணாநிதி | எட்டாம் பதிப்பு, ஜூலை 1953 | **49/49 canonical pages complete; full Tamil source audit COMPLETE; assembled Tamil PASSED; English VERIFIED; release-readiness PASS; package RELEASE-READY WITH CANONICAL-TAMIL VERIFICATION QUALIFICATION — freeze ACTIVE, 0 verified / 49 `needs-review`** |
| [புதையல்](works/pudhaiyal/README.md) | கலைஞர் மு. கருணாநிதி, எம். எல். ஏ. | மூன்றாம் பதிப்பு, செப்டம்பர் 1961 | **448 canonical / 446 verified-complete / 2 physical-loss `needs-review`; Parts 001–010 part-complete; English VERIFIED; repository package RELEASE-READY WITH QUALIFICATION** |
| [பலிபீடம் நோக்கி](works/balipeedam-nokki/README.md) | மு. கருணாநிதி | முதல் பதிப்பு, ஏப்ரல் 1947 | **Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; archival package RELEASE-READY** |

## Historical Tamil glyph handling

Use [`HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`](HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md). Governing rule: identify historical character identity from source pixels first, then encode that identity in modern Unicode without modernizing source wording. Minimum set: `ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`.

## Release-status meaning

Repository release-readiness is an editorial/archival workflow status. It is not a determination of copyright, licensing, distribution or republication rights.
