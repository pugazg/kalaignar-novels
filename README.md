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
- canonical page records: **17 / 179**;
- scans 1–3 front matter: **verified**;
- scans 4–12 / Chapter 1: **directly transcribed and verified; Chapter 1 complete**;
- scans 13–17 / Chapter 2 opening: **directly transcribed and verified**;
- historical-glyph/source-sensitive checks: **PASS through scan 17**, including scan 8 `களைத்துத்`, scan 9 `குழப்பட்டு`, scan 12 `அந்தப் பருக்கூட்டமே`, and source-specific Chapter 2 readings preserved without normalization;
- next batch: **scans 18–22**, completing Chapter 2 before scan 23 / Chapter 3.

The source is image-only and uses older Tamil print conventions. Every body page must use the historical-glyph pre-correction workflow in `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`. Later underlining/ticks/handwriting must remain separate from printed text. The source PDF remains outside the repository.

## Completed works

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [பெரிய இடத்துப் பெண்](works/periya-idathup-pen/README.md) | மு. கருணாநிதி | எட்டாம் பதிப்பு, ஜூலை 1953 | **49/49 canonical pages complete; full Tamil source audit COMPLETE; assembled Tamil PASSED; English VERIFIED; release-readiness PASS; package RELEASE-READY WITH CANONICAL-TAMIL VERIFICATION QUALIFICATION — freeze ACTIVE, 0 verified / 49 `needs-review`** |
| [புதையல்](works/pudhaiyal/README.md) | கலைஞர் மு. கருணாநிதி, எம். எல். ஏ. | மூன்றாம் பதிப்பு, செப்டம்பர் 1961 | **448 canonical / 446 verified-complete / 2 physical-loss `needs-review`; Parts 001–010 part-complete; English VERIFIED; repository package RELEASE-READY WITH QUALIFICATION** |
| [பலிபீடம் நோக்கி](works/balipeedam-nokki/README.md) | மு. கருணாநிதி | முதல் பதிப்பு, ஏப்ரல் 1947 | **Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; archival package RELEASE-READY** |

## Historical Tamil glyph handling

For older Tamil sources, use [`HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`](HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md) before deciding difficult glyphs. Its governing rule is: **identify the historical character identity from source pixels first, then encode that identity in modern Unicode without modernizing the source wording.** The documented minimum Periyar-reform-sensitive set is `ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`.

`வெள்ளிக்கிழமை` (1968) is the current active work. Scans 4–17 have passed direct high-resolution transcription and historical-glyph checking. Chapter 1 is complete through scan 12; scans 13–17 begin Chapter 2. Scan 8's initially held cluster is source-supported as `களைத்துத் தூங்கிவிட்டால்`, with historical `ளை` identity. No contextual guess or global replacement was used.

The completed whole-work audit of `பெரிய இடத்துப் பெண்` remains a reference for historical-glyph handling; its canonical freeze remains unchanged.

## பெரிய இடத்துப் பெண் — completed archival / English state

Working English title: **The Woman of the Great House**. All seven source-structured English sections are reviewed; the whole-work bilingual review PASSED and English is VERIFIED. Its package is **RELEASE-READY WITH CANONICAL-TAMIL VERIFICATION QUALIFICATION** because canonical Tamil remains 0 verified / 49 `needs-review` under the user-mandated freeze. No further mandatory processing remains under that instruction.

## புதையல் — final release state

Received derivatives cover scans **1–448**. The narrative ends on scan 447 / printed 443; scan 448 is the unnumbered printer colophon `அன்பு அச்சகம், பொறையார்.` Final canonical count is 448, with 446 verified-complete and scans 223–224 retained `needs-review` because of physical loss. Whole-work English remains VERIFIED and the package RELEASE-READY WITH QUALIFICATION.

## Release-status meaning

Repository release-readiness is an editorial/archival workflow status. It is not a determination of copyright, licensing, distribution or republication rights.
