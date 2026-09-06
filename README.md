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
- canonical page records: **32 / 179 — 27 verified + scans 28–32 partial source-review holds**;
- scans 1–3 front matter: **verified**;
- scans 4–12 / Chapter 1: **verified / complete**;
- scans 13–22 / Chapter 2: **verified / complete**;
- scans 23–27 / Chapter 3 opening: **verified**;
- scans 28–32: **printed-page/structure review complete; full Tamil and historical-glyph verification pending**;
- historical-glyph/source-sensitive checks: **PASS through scan 27; pending for scans 28–32**;
- printed-page mapping confirmed through scan 33: scans 28–32 = **27–31**; scan 33 = **32**;
- structural correction: scan 33 begins with **Chapter 3 carryover**, followed on the same scan by the source-printed **Chapter 4** heading;
- next activity: obtain/review sufficient-resolution source for scans **28–32**, complete their source-faithful Tamil + historical-glyph verification, then process scan **33** without moving its Chapter 3 carryover backward.

The source is image-only and uses older Tamil print conventions. Every body page must use the historical-glyph pre-correction workflow in `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`. Later underlining/ticks/handwriting remain separate from printed text. The source PDF remains outside the repository.

## Completed works

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [பெரிய இடத்துப் பெண்](works/periya-idathup-pen/README.md) | மு. கருணாநிதி | எட்டாம் பதிப்பு, ஜூலை 1953 | **49/49 canonical pages complete; full Tamil source audit COMPLETE; assembled Tamil PASSED; English VERIFIED; release-readiness PASS; package RELEASE-READY WITH CANONICAL-TAMIL VERIFICATION QUALIFICATION — freeze ACTIVE, 0 verified / 49 `needs-review`** |
| [புதையல்](works/pudhaiyal/README.md) | கலைஞர் மு. கருணாநிதி, எம். எல். ஏ. | மூன்றாம் பதிப்பு, செப்டம்பர் 1961 | **448 canonical / 446 verified-complete / 2 physical-loss `needs-review`; Parts 001–010 part-complete; English VERIFIED; repository package RELEASE-READY WITH QUALIFICATION** |
| [பலிபீடம் நோக்கி](works/balipeedam-nokki/README.md) | மு. கருணாநிதி | முதல் பதிப்பு, ஏப்ரல் 1947 | **Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; archival package RELEASE-READY** |

## Historical Tamil glyph handling

For older Tamil sources, use [`HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`](HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md). Governing rule: **identify historical character identity from source pixels first, then encode that identity in modern Unicode without modernizing source wording.** Minimum set: `ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`.

For `வெள்ளிக்கிழமை`, scans 4–27 have passed direct transcription and historical-glyph checking. Scans 28–32 are intentionally `partial`: their printed pages and structure are confirmed, but no full Tamil transcription is asserted until sufficient-resolution character-level review is possible.

## Release-status meaning

Repository release-readiness is an editorial/archival workflow status. It is not a determination of copyright, licensing, distribution or republication rights.
