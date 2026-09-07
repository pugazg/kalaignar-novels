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
- **scan 107 / printed 106: mixed Chapter 12 / Chapter 13 with centered `13`**;
- Chapter 13 transcribed through scan 111 / printed 110;
- **historical-glyph work-level gate: REOPENED**;
- corrective re-audit **PASS for scans 102–111**;
- retrospective historical-glyph audit **pending for scans 1–101**;
- full Tamil source audit / assembled Tamil / English: **not started / not started / blocked**.

## Why the historical-glyph gate was reopened

The previous pass incorrectly treated several historical Tamil typeforms as their modern visual look-alikes. The guide requires the opposite: identify the historical character first, then encode that identity in Unicode. Confirmed corrections now applied include `நன்றுகக்` → `நன்றாகக்`, `தவறுக` → `தவறாக`, `என்றுள்` → `என்றாள்`, multiple missing-`ஆ` forms such as `ஆட்டினள்` → `ஆட்டினாள்`, and current-batch forms `ஓடினன்` → `ஓடினான்`, `திமிறினன்` → `திமிறினான்`, `சொன்னு` → `சொன்னா`, `பெண்ணு?` → `பெண்ணா?`.

No blanket morphological correction was made: scan 109 `கூறினன்` / `சொன்னன்` and scan 110 `புளுகினன்` were rechecked and retained.

## Corrective batch — scans 102–111

**Result: SOURCE-PIXEL CORRECTIVE PASS.**

- scan 102 / printed 101: `ஆட்டினாள்`;
- scan 103 / printed 102: `நன்றாகக்`, `கத்தினாள்`;
- scan 104 / printed 103: `கூறினாள்`;
- scan 105 / printed 104: rechecked, no confirmed historical-glyph correction required;
- scan 106 / printed 105: `திருப்பினாள்`, `என்றாள்` ×2, `நன்றாகக்`, `தவறாக`;
- scan 107 / printed 106: Chapter 12/13 boundary; `கூறினாள்`, `கொட்டினான்`, `என்றாள்`, `ஓடினான்`, `ஓடினார்கள்`;
- scan 108 / printed 107: `திமிறினான்`, `நடுங்கினாள்`;
- scan 109 / printed 108: `சொன்னா`, `பொய்தானா?`; `கூறினன்` / `சொன்னன்` retained after separate check;
- scan 110 / printed 109: `பெண்ணா?`; `புளுகினன்` retained after separate check;
- scan 111 / printed 110: rechecked; `பெண்ணை`, `தகப்பனாவது`, `அக்கரை`, `குடிலர்` retained; final physical `சிறிதா` continues with scan 112 `வது`.

## Historical Tamil glyph policy

Use root `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`. Every older-print page must explicitly consider `ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`; only source-pixel evidence clears a form. Do not normalize vocabulary or grammar and never global-replace.

## Key records

- [`metadata/source.md`](metadata/source.md)
- [`indexes/page-map.md`](indexes/page-map.md)
- [`audit.md`](audit.md)
- canonical pages through [`pages/0111-vellikkizhamai-108.md`](pages/0111-vellikkizhamai-108.md)

## Exact next activity

Pause forward scans 112–116. Perform a **retrospective historical-glyph re-audit of scans 1–5** as the next 5-scan iteration, then continue chronologically until prior coverage is cleared.
