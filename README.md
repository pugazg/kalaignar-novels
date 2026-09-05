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
| [பெரிய இடத்துப் பெண்](works/periya-idathup-pen/README.md) | மு. கருணாநிதி | எட்டாம் பதிப்பு, ஜூலை 1953 | **49/49 canonical pages complete; full Tamil source audit COMPLETE; verification freeze ACTIVE — 0 verified / 49 `needs-review`; assembled Tamil PASSED; English plan COMPLETE; Batches 1 and 2 REVIEWED; English 2/7 sections reviewed, 0/7 verified; next: Kannamma Batch 3A** |

## Completed works

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [புதையல்](works/pudhaiyal/README.md) | கலைஞர் மு. கருணாநிதி, எம். எல். ஏ. | மூன்றாம் பதிப்பு, செப்டம்பர் 1961 | **448 canonical / 446 verified-complete / 2 physical-loss `needs-review`; Parts 001–010 part-complete; English VERIFIED; repository package RELEASE-READY WITH QUALIFICATION** |
| [பலிபீடம் நோக்கி](works/balipeedam-nokki/README.md) | மு. கருணாநிதி | முதல் பதிப்பு, ஏப்ரல் 1947 | **Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; archival package RELEASE-READY** |

## Historical Tamil glyph handling

For older Tamil sources, use [`HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`](HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md) before deciding difficult glyphs. Its governing rule is: **identify the historical character identity from source pixels first, then encode that identity in modern Unicode without modernizing the source wording.** The documented minimum Periyar-reform-sensitive set is `ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`.

The completed whole-work audit of `பெரிய இடத்துப் பெண்` found four dedicated-pass historical-glyph corrections on scans 33, 43, 46 and 47. The passed assembled Tamil reader preserves those final readings and all source-printed internal headings. Its `PASSED` status does not override the canonical verification freeze.

## பெரிய இடத்துப் பெண் — English translation

Working English title: **The Woman of the Great House**.

Completed reviewed English sections:

- [`works/periya-idathup-pen/translations/en/sections/01-opening.md`](works/periya-idathup-pen/translations/en/sections/01-opening.md) — opening pilot, scans 8–15 before `உத்தண்டி`;
- [`works/periya-idathup-pen/translations/en/sections/02-uthandi.md`](works/periya-idathup-pen/translations/en/sections/02-uthandi.md) — `உத்தண்டி`, scan 15 heading through scan 19 before `கண்ணம்மா`.

Batch 2 preserves Uthandi's hereditary-servitude, class/debt, wage, marriage/dowry and self-blaming vocabulary. Its page-boundary continuities were source-checked, difficult source forms were recorded in the translation glossary, and no Tamil canonical correction was triggered.

Control records:

- [`works/periya-idathup-pen/translations/en/TRANSLATION_PLAN.md`](works/periya-idathup-pen/translations/en/TRANSLATION_PLAN.md)
- [`works/periya-idathup-pen/translations/en/PROGRESS.md`](works/periya-idathup-pen/translations/en/PROGRESS.md)
- [`works/periya-idathup-pen/translations/en/GLOSSARY.md`](works/periya-idathup-pen/translations/en/GLOSSARY.md)
- [`works/periya-idathup-pen/translations/en/BATCH_01_REVIEW.md`](works/periya-idathup-pen/translations/en/BATCH_01_REVIEW.md)
- [`works/periya-idathup-pen/translations/en/BATCH_02_REVIEW.md`](works/periya-idathup-pen/translations/en/BATCH_02_REVIEW.md)

Next English activity is **Batch 3A — the first `கண்ணம்மா` account, scan 19 heading through scan 24**.

## புதையல் — final release state

Received derivatives cover scans **1–448**. The narrative ends on **scan 447 / printed 443**; scan **448** is the unnumbered printer colophon **`அன்பு அச்சகம், பொறையார்.`**

Final source count after the user's **2026-09-03 Part-005 re-review**:

- canonical: **448**;
- verified / completed: **446**;
- `needs-review`: **2 — only scans 223–224**, where substantial portions of the paper are physically absent;
- assembled Tamil and English remain complete through scan 448;
- whole-work English remains **VERIFIED**;
- release status remains **RELEASE-READY WITH TWO PHYSICAL-LOSS QUALIFICATIONS**.
