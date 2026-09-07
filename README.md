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
- retrospective historical-glyph re-audit: **PASS scans 1–5; pending scans 6–101**;
- full Tamil source audit: **not started**;
- assembled Tamil: **not started**;
- English translation: **blocked until Tamil gate passes**.

### Retrospective glyph audit — scans 1–5

The first retrospective 5-scan batch is complete. All 13 mandatory historical families were explicitly tested against the source. No historical-character identity correction was required in scans 1–5. Representative confirmations include cover `கருணாநிதி` (`ணா`), `திராவிடப்பண்ணை` (`ணை`), publication-page `விலை` (`லை`), scan 4 `அன்னைப்` / `மாவீரனைப்` (`னை`) and `போனான்` (`னா`), and scan 5 `சாணமிட்டு` (`ணா`) / `நன்றாக` (`றா`).

A separate ordinary source-fidelity check on scan 4 corrected **`பெருகிடுகிறது` → `பெருகிவிடுகிறது`**. No global replacement was used.

### Historical-glyph corrective finding

The old metal-type forms were at several points read as modern look-alikes instead of being decoded to their Unicode character identities. The corrective pass repaired confirmed cases in scans 102–111, including `நன்றுகக்` → `நன்றாகக்`, `தவறுக` → `தவறாக`, `என்றுள்` → `என்றாள்`, multiple missing-`ஆ` forms, `சொன்னு` → `சொன்னா`, and `பெண்ணு?` → `பெண்ணா?`.

No global replacement was used. Nearby forms such as scan 109 `கூறினன்` / `சொன்னன்` and scan 110 `புளுகினன்` were rechecked separately and retained.

### Durable name correction — `நயினா`

The recurring character name is **`நயினா`**, not `நயினு`. Scan 34 provides the same-edition witness `நயினா என்பது நயினாமுகம்மது என்ற பெயரின் சுருக்கம்`.

### Source-number anomaly — scan 66

Scan **66** visibly prints only **`5`**; no `65` is inferred.

## Completed works

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [பெரிய இடத்துப் பெண்](works/periya-idathup-pen/README.md) | மு. கருணாநிதி | எட்டாம் பதிப்பு, ஜூலை 1953 | **49/49 canonical pages complete; full Tamil source audit COMPLETE; assembled Tamil PASSED; English VERIFIED; release-ready with canonical-Tamil verification qualification** |
| [புதையல்](works/pudhaiyal/README.md) | கலைஞர் மு. கருணாநிதி, எம். எல். ஏ. | மூன்றாம் பதிப்பு, செப்டம்பர் 1961 | **448 canonical / 446 verified-complete / 2 physical-loss `needs-review`; English VERIFIED; repository package RELEASE-READY WITH QUALIFICATION** |
| [பலிபீடம் நோக்கி](works/balipeedam-nokki/README.md) | மு. கருணாநிதி | முதல் பதிப்பு, ஏப்ரல் 1947 | **Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; archival package RELEASE-READY** |

## Historical Tamil glyph handling

Use [`HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`](HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md). Identify the historical character identity from source pixels first, then encode that identity in modern Unicode. Minimum set: `ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`. Never global-replace.

## Next activity

Continue the retrospective historical-glyph re-audit in the next 5-scan batch: **scans 6–10**. Forward transcription at scan 112 remains paused until scans 1–101 are cleared.

## Release-status meaning

Repository release-readiness is an editorial/archival workflow status. It is not a determination of copyright, licensing, distribution or republication rights.
