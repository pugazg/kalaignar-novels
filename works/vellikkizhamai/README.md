# வெள்ளிக்கிழமை

**ஆசிரியர் (source cover):** மு. கருணாநிதி  
**வெளியீடு:** திராவிடப்பண்ணை, 34, சிந்தாமணி, திருச்சி-2  
**பதிப்பு:** இரண்டாம் பதிப்பு — 1968  
**Source PDF:** `TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf`  
**Source PDF committed:** No

## Current archival status

- actual PDF scan count: **179**; size **251,126,214 bytes**;
- SHA-256: `ac241cbfbe3d47d76f22140f43c662176ba29a91521b826a1a8f5c75cf3081d3`;
- page manifest: **179 / 179**;
- canonical page records: **111 / 179**;
- scan 92 / printed 91: mixed Chapter 10 / Chapter 11 with centered `11`;
- scan 99 / printed 98: mixed Chapter 11 / Chapter 12 with centered `12`;
- scan 107 / printed 106: mixed Chapter 12 / Chapter 13 with centered `13`;
- Chapter 13 transcribed through scan 111 / printed 110;
- **historical-glyph work-level gate: REOPENED**;
- corrective historical-glyph re-audit: **PASS scans 102–111**;
- retrospective historical-glyph re-audit: **PASS scans 1–5; pending scans 6–101**;
- full Tamil source audit / assembled Tamil / English: **not started / not started / blocked**.

## Retrospective batch — scans 1–5

**Result: HISTORICAL-GLYPH PASS / 5 OF 5 COMPLETE.**

- scan 1: `கருணாநிதி` (`ணா`) and `திராவிடப்பண்ணை` (`ணை`) confirmed;
- scan 2: later donor label checked; no historical-family correction required;
- scan 3: `விலை` historical `லை` identity confirmed;
- scan 4: `அன்னைப்`, `மாவீரனைப்` (`னை`), `போனான்` (`னா`), and `மாலையிலே` checked; no historical-glyph correction required;
- scan 5: `சாணமிட்டு` (`ணா`) and `நன்றாக` (`றா`) confirmed.

Separate ordinary source comparison on scan 4 corrected **`பெருகிடுகிறது` → `பெருகிவிடுகிறது`**. This is a source-fidelity correction, not a historical-glyph substitution. No global replacement was used.

## Why the historical-glyph gate was reopened

The previous pass incorrectly treated several historical Tamil typeforms as their modern visual look-alikes. The guide requires the opposite: identify the historical character first, then encode that identity in Unicode. Confirmed corrections already applied in scans 102–111 include `நன்றுகக்` → `நன்றாகக்`, `தவறுக` → `தவறாக`, `என்றுள்` → `என்றாள்`, multiple missing-`ஆ` forms, `சொன்னு` → `சொன்னா`, and `பெண்ணு?` → `பெண்ணா?`.

No blanket morphological correction was made: scan 109 `கூறினன்` / `சொன்னன்` and scan 110 `புளுகினன்` were rechecked and retained.

## Historical Tamil glyph policy

Use root `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`. Every older-print page must explicitly consider `ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`; only source-pixel evidence clears a form. Do not normalize vocabulary or grammar and never global-replace.

## Key records

- [`metadata/source.md`](metadata/source.md)
- [`indexes/page-map.md`](indexes/page-map.md)
- [`audit.md`](audit.md)
- canonical pages through [`pages/0111-vellikkizhamai-108.md`](pages/0111-vellikkizhamai-108.md)

## Exact next activity

Keep forward scans 112–116 paused. Perform the next retrospective 5-scan historical-glyph audit on **scans 6–10**, synchronize status documents, and continue chronologically until scans 1–101 are cleared.
