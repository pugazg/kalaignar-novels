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

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [பெரிய இடத்துப் பெண்](works/periya-idathup-pen/README.md) | மு. கருணாநிதி | எட்டாம் பதிப்பு, ஜூலை 1953 | **49/49 canonical pages complete; dedicated full Tamil source audit COMPLETE — 49/49 directly reviewed; verification freeze ACTIVE; 0 verified / 49 `needs-review`; assembled Tamil reading layer PASSED across 7 source-structured files; English translation plan is next** |

## Completed works

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [புதையல்](works/pudhaiyal/README.md) | கலைஞர் மு. கருணாநிதி, எம். எல். ஏ. | மூன்றாம் பதிப்பு, செப்டம்பர் 1961 | **448 canonical / 446 verified-complete / 2 physical-loss `needs-review`; Parts 001–010 part-complete; English VERIFIED; repository package RELEASE-READY WITH QUALIFICATION** |
| [பலிபீடம் நோக்கி](works/balipeedam-nokki/README.md) | மு. கருணாநிதி | முதல் பதிப்பு, ஏப்ரல் 1947 | **Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; archival package RELEASE-READY** |

## Historical Tamil glyph handling

For older Tamil sources, use [`HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`](HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md) before deciding difficult glyphs. Its governing rule is: **identify the historical character identity from source pixels first, then encode that identity in modern Unicode without modernizing the source wording.** The documented minimum Periyar-reform-sensitive set is `ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`.

The completed whole-work audit of `பெரிய இடத்துப் பெண்` demonstrates why the second pass is required. Four first-pass look-alike readings were corrected from direct pixels during the dedicated audit:

- scan 33 `கண்ணடி` → `கண்ணாடி` (`ணா`);
- scan 43 `இளிச்சவாயனுக` → `இளிச்சவாயனாக` (`னா`);
- scan 46 `நானு ஆள்?` → `நானா ஆள்?` (`னா`);
- scan 47 `விட வேணு?` → `விட வேணா?` (`ணா`).

The passed assembled Tamil reader preserves those final canonical readings, all source-printed internal headings and audit-established page-boundary joins. Its `PASSED` status does not override the canonical verification freeze.

## புதையல் — final release state

Received derivatives cover scans **1–448**. The narrative ends on **scan 447 / printed 443**; scan **448** is the unnumbered printer colophon **`அன்பு அச்சகம், பொறையார்.`**

Final source count after the user's **2026-09-03 Part-005 re-review**:

- canonical: **448**;
- verified / completed: **446**;
- `needs-review`: **2 — only scans 223–224**, where substantial portions of the paper are physically absent;
- scans **215–219** are now closed by direct user review;
- assembled Tamil and English remain complete through scan 448;
- whole-work English remains **VERIFIED**;
- release status remains **RELEASE-READY WITH TWO PHYSICAL-LOSS QUALIFICATIONS**.

The user supplied exact corrections on scans 215–216, including `பரிமளாவும்`, `கொழுந்தாம்`, `புண்ணுக்கு மருந்து கேள்; தருகிறேன்.`, and `அவன் வீரனாக`; these are synchronized through canonical Tamil, assembled Tamil and English.

Final records:

- complete-source manifest: [`works/pudhaiyal/indexes/FULL_SOURCE_PAGE_MAP.md`](works/pudhaiyal/indexes/FULL_SOURCE_PAGE_MAP.md)
- whole-work Tamil audit: [`works/pudhaiyal/audit.md`](works/pudhaiyal/audit.md)
- Part-005 audit: [`works/pudhaiyal/notes/part-005-tamil-audit.md`](works/pudhaiyal/notes/part-005-tamil-audit.md)
- verified English reader index: [`works/pudhaiyal/translations/en/README.md`](works/pudhaiyal/translations/en/README.md)
- final bilingual review: [`works/pudhaiyal/translations/en/TRANSLATION_REVIEW.md`](works/pudhaiyal/translations/en/TRANSLATION_REVIEW.md)
- release report: [`works/pudhaiyal/translations/en/RELEASE_REPORT.md`](works/pudhaiyal/translations/en/RELEASE_REPORT.md)
