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
- canonical page records: **106 / 179 — all 106 verified**;
- Chapters 1–11: **verified through scan 99 pre-heading carryover**;
- Chapter 12: **scan 99 below centered `12` through scan 106 / printed 105 — verified continuation**;
- historical-glyph/source-sensitive checks: **PASS through scan 106**;
- full Tamil source audit: **not started**;
- assembled Tamil: **not started**;
- English translation: **blocked until Tamil gate passes**;
- next 5-scan iteration: **scans 107–111**.

### Durable name correction — `நயினா`

The recurring character name is **`நயினா`**, not `நயினு`. Reinspection of the controlling scan shows that the historical `னா` typeform had been misread as `னு`. Scan 34 directly gives the same-edition witness `நயினா என்பது நயினாமுகம்மது என்ற பெயரின் சுருக்கம்`. Canonical scans 34–106 use `நயினா`; future transcription must not regress to `நயினு`.

### Source-number anomaly — scan 66

Scan **66** visibly prints only **`5`** at the page-number positions; no tens digit is present even under enlarged/native inspection. Canonical `printed_page` therefore records the visible source value `5` rather than silently inferring `65`. Scans 67–106 visibly print `66–105`.

### Completed 5-scan batch — scans 102–106

Scans **102–106 / printed 101–105** are verified Chapter 12 continuation. Direct source review corrected source-sensitive readings before commit: scan 102 `கண்கொட்டாமல்`, `அடைத்துக்கொள்வானேன்?`, `ஆட்டினள்`; scan 103 `என்னால் உங்களுக்கு வீண் சிரமம்` and `அவள் டாக்டர்! அதனால் அதைக் கண்டுபிடித்துவிட்டாள்.`; scan 104 `விபத்தினில்`; scan 105 `விஷங்கலக்கலாம்`; scan 106 source `தவறுக சந்தேகப்பட்டுவிட்டேன்`. Physical continuities are preserved, including scan 103 `சொல்லு` → scan 104 `கிறேன்`, scan 105 `உன்` → scan 106 `சௌந்தர்யம்!`, and scan 106 `அவள் கண்களில்` → scan 107 continuation.

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
