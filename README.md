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

## Active / qualified-complete work

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [பெரிய இடத்துப் பெண்](works/periya-idathup-pen/README.md) | மு. கருணாநிதி | எட்டாம் பதிப்பு, ஜூலை 1953 | **49/49 canonical pages complete; full Tamil source audit COMPLETE; verification freeze ACTIVE — 0 verified / 49 `needs-review`; assembled Tamil PASSED; English 7/7 sections + 8/8 batches REVIEWED; final bilingual review PASSED; whole-work English VERIFIED; RELEASE-READY WITH CANONICAL-TAMIL VERIFICATION QUALIFICATION** |

## Completed works

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [புதையல்](works/pudhaiyal/README.md) | கலைஞர் மு. கருணாநிதி, எம். எல். ஏ. | மூன்றாம் பதிப்பு, செப்டம்பர் 1961 | **448 canonical / 446 verified-complete / 2 physical-loss `needs-review`; Parts 001–010 part-complete; English VERIFIED; repository package RELEASE-READY WITH QUALIFICATION** |
| [பலிபீடம் நோக்கி](works/balipeedam-nokki/README.md) | மு. கருணாநிதி | முதல் பதிப்பு, ஏப்ரல் 1947 | **Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; archival package RELEASE-READY** |

## Historical Tamil glyph handling

For older Tamil sources, use [`HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`](HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md) before deciding difficult glyphs. Its governing rule is: **identify the historical character identity from source pixels first, then encode that identity in modern Unicode without modernizing the source wording.** The documented minimum Periyar-reform-sensitive set is `ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`.

The completed whole-work audit of `பெரிய இடத்துப் பெண்` found four dedicated-pass historical-glyph corrections on scans 33, 43, 46 and 47. The passed assembled Tamil reader preserves those final readings and all source-printed internal headings. Its `PASSED` status, English `VERIFIED` status and qualified release verdict do not override the canonical verification freeze.

## பெரிய இடத்துப் பெண் — final archival / English state

Working English title: **The Woman of the Great House**.

All seven source-structured English section files are **REVIEWED / PASS** at section level:

- [`works/periya-idathup-pen/translations/en/sections/01-opening.md`](works/periya-idathup-pen/translations/en/sections/01-opening.md) — opening, scans 8–15 before `உத்தண்டி`;
- [`works/periya-idathup-pen/translations/en/sections/02-uthandi.md`](works/periya-idathup-pen/translations/en/sections/02-uthandi.md) — `உத்தண்டி`, scan 15 through scan 19 before `கண்ணம்மா`;
- [`works/periya-idathup-pen/translations/en/sections/03-kannamma-first.md`](works/periya-idathup-pen/translations/en/sections/03-kannamma-first.md) — first `கண்ணம்மா`, scan 19 through scan 31; planned Batches 3A + 3B both reviewed;
- [`works/periya-idathup-pen/translations/en/sections/04-kumudha.md`](works/periya-idathup-pen/translations/en/sections/04-kumudha.md) — `குமுதா`, scans 32–37;
- [`works/periya-idathup-pen/translations/en/sections/05-veeran.md`](works/periya-idathup-pen/translations/en/sections/05-veeran.md) — `வீரன்`, scans 38–44;
- [`works/periya-idathup-pen/translations/en/sections/06-ulaganathar.md`](works/periya-idathup-pen/translations/en/sections/06-ulaganathar.md) — `உலகநாதர்`, scan 45;
- [`works/periya-idathup-pen/translations/en/sections/07-kannamma-conclusion.md`](works/periya-idathup-pen/translations/en/sections/07-kannamma-conclusion.md) — final `கண்ணம்மா`, scans 46–49 + separate printer colophon.

The final cross-section bilingual alignment in [`works/periya-idathup-pen/translations/en/TRANSLATION_REVIEW.md`](works/periya-idathup-pen/translations/en/TRANSLATION_REVIEW.md) **PASSED**, establishing the **whole-work English translation as VERIFIED**.

The release-readiness pass in [`works/periya-idathup-pen/translations/en/RELEASE_REPORT.md`](works/periya-idathup-pen/translations/en/RELEASE_REPORT.md) also passed, with the mandatory qualification that canonical Tamil remains **0 verified / 49 `needs-review`** under the active user-mandated freeze.

Therefore the accurate repository status is:

**RELEASE-READY WITH CANONICAL-TAMIL VERIFICATION QUALIFICATION.**

This means the English layer is release-ready within the archival repository and the full package has completed its release checks, but the canonical Tamil page-status gate is intentionally unresolved by user instruction. It must not be represented as unqualified release-ready unless that instruction changes.

The final review also corrected one English-only romanisation drift: source `ரதி` is **Rati**, not the earlier `Rathi`. No Tamil source text changed.

Control records:

- [`works/periya-idathup-pen/translations/en/TRANSLATION_PLAN.md`](works/periya-idathup-pen/translations/en/TRANSLATION_PLAN.md)
- [`works/periya-idathup-pen/translations/en/PROGRESS.md`](works/periya-idathup-pen/translations/en/PROGRESS.md)
- [`works/periya-idathup-pen/translations/en/GLOSSARY.md`](works/periya-idathup-pen/translations/en/GLOSSARY.md)
- [`works/periya-idathup-pen/translations/en/BATCH_01_REVIEW.md`](works/periya-idathup-pen/translations/en/BATCH_01_REVIEW.md)
- [`works/periya-idathup-pen/translations/en/BATCH_02_REVIEW.md`](works/periya-idathup-pen/translations/en/BATCH_02_REVIEW.md)
- [`works/periya-idathup-pen/translations/en/BATCH_03_REVIEW.md`](works/periya-idathup-pen/translations/en/BATCH_03_REVIEW.md)
- [`works/periya-idathup-pen/translations/en/BATCH_04_REVIEW.md`](works/periya-idathup-pen/translations/en/BATCH_04_REVIEW.md)
- [`works/periya-idathup-pen/translations/en/BATCH_05_REVIEW.md`](works/periya-idathup-pen/translations/en/BATCH_05_REVIEW.md)
- [`works/periya-idathup-pen/translations/en/BATCH_06_REVIEW.md`](works/periya-idathup-pen/translations/en/BATCH_06_REVIEW.md)
- [`works/periya-idathup-pen/translations/en/BATCH_07_REVIEW.md`](works/periya-idathup-pen/translations/en/BATCH_07_REVIEW.md)
- [`works/periya-idathup-pen/translations/en/TRANSLATION_REVIEW.md`](works/periya-idathup-pen/translations/en/TRANSLATION_REVIEW.md)
- [`works/periya-idathup-pen/translations/en/RELEASE_REPORT.md`](works/periya-idathup-pen/translations/en/RELEASE_REPORT.md)

No further mandatory processing remains for this title under the present freeze instruction. Future work must preserve this qualified state unless the user explicitly changes the canonical verification disposition.

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