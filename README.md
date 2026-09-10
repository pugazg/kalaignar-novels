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
- source PDF: `TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf`;
- actual PDF scans: **179**;
- page manifest: **179 / 179 represented**;
- canonical page records: **179 / 179 — COMPLETE / VERIFIED**;
- final narrative: **scan 179 / printed 178**, ending `திரும்பினர்கள்.`;
- unresolved source holds: **0**;
- forward historical-glyph coverage: **PASS scans 1–179**;
- second historical-glyph re-audit: **COMPLETE — scans 119–179 / 61 of 61 PASS; 5 corrections / 0 unresolved**;
- full Tamil source audit: **PASSED**;
- Tamil source layer: **PASSED**;
- assembled Tamil content: **COMPLETE — Chapters 1–23 / 23 VERIFIED**;
- final assembled Tamil consistency gate: **PENDING / NOT YET RUN**;
- English translation: **blocked until the final assembled Tamil consistency gate passes**.

### Historical Tamil glyph handling

Mandatory family set on source-dependent historical-glyph work:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Source pixels decide identity. Grammar is only a locator. Preserve source spelling, grammar, punctuation, spacing, colloquial forms and physical boundaries. Never global-replace.

### Current assembly state

The canonical `works/vellikkizhamai/pages/` layer is closed and controlling. The derived `sections/` reading layer now contains **23 / 23 VERIFIED chapters**, all derived only from canonical records. Mixed physical scans were split at centered source chapter headings; verified page continuities are reversible with provenance comments; literal source discontinuities and oddities remain unrepaired; printer/signature marks and non-body visual/later-handwritten material are excluded. No canonical page record changed during assembly.

The final remaining Chapters **21–23** were assembled together under explicit user authorization, covering scan 160 after centered `21` through final narrative scan 179, with centered boundaries `22` on scan 166 and `23` on scan 172. Remaining-batch verification: **PASS — 3 / 3 chapters, 0 unresolved / 0 canonical changes**.

## Completed works

| நூல் | நிலை |
|---|---|
| பெரிய இடத்துப் பெண் | **49/49 canonical complete; Tamil source audit complete; assembled Tamil PASSED; English VERIFIED; release-ready with qualification** |
| புதையல் | **448 canonical / 446 complete / 2 physical-loss `needs-review`; English VERIFIED; release-ready with qualification** |
| பலிபீடம் நோக்கி | **Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; release-ready** |

## Next activity

Run the **final assembled Tamil consistency gate** for `வெள்ளிக்கிழமை` across all 23 section files. Confirm complete source/chapter coverage, correct centered-heading splits, only source-verified reversible joins, preservation of canonical oddities/discontinuities, exclusion of non-body material, and zero unauthorized canonical `pages/` changes. Do not start English until that gate passes.
