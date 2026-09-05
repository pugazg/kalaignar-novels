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
- canonical page records: **3 / 179**;
- scans 1–3 front matter: **verified**;
- body transcription: **not started**;
- next batch: **scans 4–8 / Chapter 1 opening**.

The source is image-only and uses older Tamil print conventions. Every body page must use the historical-glyph pre-correction workflow in `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`. The source PDF remains outside the repository.

## Completed works

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [பெரிய இடத்துப் பெண்](works/periya-idathup-pen/README.md) | மு. கருணாநிதி | எட்டாம் பதிப்பு, ஜூலை 1953 | **49/49 canonical pages complete; full Tamil source audit COMPLETE; assembled Tamil PASSED; English VERIFIED; release-readiness PASS; package RELEASE-READY WITH CANONICAL-TAMIL VERIFICATION QUALIFICATION — freeze ACTIVE, 0 verified / 49 `needs-review`** |
| [புதையல்](works/pudhaiyal/README.md) | கலைஞர் மு. கருணாநிதி, எம். எல். ஏ. | மூன்றாம் பதிப்பு, செப்டம்பர் 1961 | **448 canonical / 446 verified-complete / 2 physical-loss `needs-review`; Parts 001–010 part-complete; English VERIFIED; repository package RELEASE-READY WITH QUALIFICATION** |
| [பலிபீடம் நோக்கி](works/balipeedam-nokki/README.md) | மு. கருணாநிதி | முதல் பதிப்பு, ஏப்ரல் 1947 | **Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; archival package RELEASE-READY** |

## Historical Tamil glyph handling

For older Tamil sources, use [`HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`](HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md) before deciding difficult glyphs. Its governing rule is: **identify the historical character identity from source pixels first, then encode that identity in modern Unicode without modernizing the source wording.** The documented minimum Periyar-reform-sensitive set is `ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`.

`வெள்ளிக்கிழமை` (1968) is the current active work and must apply this rule from the first narrative page onward. Several sampled scans also contain later underlining/ticks/handwriting; those marks must remain separate from printed text.

The completed whole-work audit of `பெரிய இடத்துப் பெண்` found four dedicated-pass historical-glyph corrections on scans 33, 43, 46 and 47 in addition to the earlier confirmed corrections. Its passed assembled Tamil reader, English `VERIFIED` status and qualified release verdict do not override its canonical verification freeze.

## பெரிய இடத்துப் பெண் — completed archival / English state

Working English title: **The Woman of the Great House**.

All seven source-structured English section files are **REVIEWED / PASS** at section level. The final cross-section bilingual alignment in [`works/periya-idathup-pen/translations/en/TRANSLATION_REVIEW.md`](works/periya-idathup-pen/translations/en/TRANSLATION_REVIEW.md) **PASSED**, establishing the **whole-work English translation as VERIFIED**.

The release-readiness pass in [`works/periya-idathup-pen/translations/en/RELEASE_REPORT.md`](works/periya-idathup-pen/translations/en/RELEASE_REPORT.md) also passed, with the mandatory qualification that canonical Tamil remains **0 verified / 49 `needs-review`** under the active user-mandated freeze.

Therefore the accurate repository status is:

**RELEASE-READY WITH CANONICAL-TAMIL VERIFICATION QUALIFICATION.**

Completion/status records include [`works/periya-idathup-pen/COMPLETION_SYNC_AUDIT.md`](works/periya-idathup-pen/COMPLETION_SYNC_AUDIT.md), the Tamil source/glyph/assembly audits, and the English translation/release records. No further mandatory processing remains for that title under the present freeze instruction.

## புதையல் — final release state

Received derivatives cover scans **1–448**. The narrative ends on **scan 447 / printed 443**; scan **448** is the unnumbered printer colophon **`அன்பு அச்சகம், பொறையார்.`**

Final source count after the user's **2026-09-03 Part-005 re-review**:

- canonical: **448**;
- verified / completed: **446**;
- `needs-review`: **2 — only scans 223–224**, where substantial portions of the paper are physically absent;
- assembled Tamil and English remain complete through scan 448;
- whole-work English remains **VERIFIED**;
- release status remains **RELEASE-READY WITH TWO PHYSICAL-LOSS QUALIFICATIONS**.

## Release-status meaning

Repository release-readiness is an editorial/archival workflow status. It is not a determination of copyright, licensing, distribution or republication rights.