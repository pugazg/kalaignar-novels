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
| [பெரிய இடத்துப் பெண்](works/periya-idathup-pen/README.md) | மு. கருணாநிதி | எட்டாம் பதிப்பு, ஜூலை 1953 | **49/49 canonical pages complete; full Tamil source comparison COMPLETE; verification freeze ACTIVE — 0 verified / 49 `needs-review`; assembled Tamil PASSED across 7 source-structured sections; English translation plan COMPLETE; next: Batch-1 pilot translation of opening section** |

## Completed works

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [புதையல்](works/pudhaiyal/README.md) | கலைஞர் மு. கருணாநிதி, எம். எல். ஏ. | மூன்றாம் பதிப்பு, செப்டம்பர் 1961 | **448 canonical / 446 verified-complete / 2 physical-loss `needs-review`; Parts 001–010 part-complete; English VERIFIED; repository package RELEASE-READY WITH QUALIFICATION** |
| [பலிபீடம் நோக்கி](works/balipeedam-nokki/README.md) | மு. கருணாநிதி | முதல் பதிப்பு, ஏப்ரல் 1947 | **Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; archival package RELEASE-READY** |

## பெரிய இடத்துப் பெண் — current durable state

The dedicated audit corrected historical-glyph look-alike readings on scans 33, 43, 46 and 47, including `கண்ணாடி`, `இளிச்சவாயனாக`, `நானா ஆள்?`, and `விட வேணா?`. The passed assembled Tamil reader preserves all source-printed internal headings, audit-established page joins and the final printer colophon while leaving all canonical pages `needs-review` under the active freeze.

The English planning layer is now recorded at [`works/periya-idathup-pen/translations/en/TRANSLATION_PLAN.md`](works/periya-idathup-pen/translations/en/TRANSLATION_PLAN.md). Working English title: **The Woman of the Great House** (provisional; Tamil title remains authoritative). No English prose has been drafted yet.

## Historical Tamil glyph handling

For older Tamil sources, use [`HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`](HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md). Identify historical character identity from source pixels first, then encode that identity in modern Unicode without modernizing source wording. Minimum known reference set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

## புதையல் — final release state

Received derivatives cover scans **1–448**. The narrative ends on scan **447 / printed 443**; scan **448** is the unnumbered printer colophon `அன்பு அச்சகம், பொறையார்.`

Final durable state:

- canonical: **448**;
- verified / completed: **446**;
- `needs-review`: **2 — scans 223–224**, where substantial portions of the paper are physically absent;
- assembled Tamil and English complete;
- whole-work English **VERIFIED**;
- release status **RELEASE-READY WITH TWO PHYSICAL-LOSS QUALIFICATIONS**.

Final records include `works/pudhaiyal/indexes/FULL_SOURCE_PAGE_MAP.md`, `works/pudhaiyal/audit.md`, `works/pudhaiyal/translations/en/TRANSLATION_REVIEW.md` and `works/pudhaiyal/translations/en/RELEASE_REPORT.md`.
