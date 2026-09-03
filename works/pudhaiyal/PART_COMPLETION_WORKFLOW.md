# Split-PDF part-completion workflow — புதையல்

Split PDFs are access derivatives of one source edition. `part-complete` is a split-level state only; whole-work Tamil/English/release gates remain separate.

## Per-split sequence

1. map represented source scans;
2. reconcile canonical `pages/` records;
3. native visual/structural fidelity review;
4. resolve/retain every `needs-review` item;
5. part-level Tamil audit;
6. assembled Tamil from audited canonical pages;
7. controlled English translation;
8. English source check;
9. part-level bilingual review;
10. synchronize status.

## Lexical baseline rule — scan 280 onward

User-supplied Gemini transcription controls lexical wording/forms/spacing. Native scans control headings, paragraph boundaries, punctuation, quotations, physical boundaries, separators, chapter/scene/work-ending structure and back matter.

- Part 007 baseline: `p7.md`; three explicit user-authorized omissions restored.
- Part 008 baseline: `p8.md`; user-authorized scan-384 phrase **`தகட்டில் இருக்கிறபடி`** restored.
- Part 009 baseline: `p9.md`; **no complete lexical omission found**.
- Part 010 baseline: `p10.md`; native scan 445 complete word **`விடு`** was absent from baseline and was explicitly authorized/restored on 2026-09-03.

A user-authorized restoration is narrow to the documented omission and does not establish general source-correction authority.

## Split checkpoints

- Parts **001–010 — `part-complete`**
- Part 009 — scans **393–441** — **Tamil audit PASSED + assembled Tamil PASSED + controlled English source check PASSED + bilingual review PASSED / part-complete**
- Part 010 — scans **442–448** — **Tamil audit PASSED + assembled Tamil PASSED + controlled English source check PASSED + bilingual review PASSED / part-complete**

## Part 009 gate state

- mapping: **PASS — 49 / 49**
- canonical: **PASS — 49 / 49**
- visual/structural fidelity: **PASS**
- needs-review: **0**
- Tamil audit: **PASS** — [`notes/part-009-tamil-audit.md`](notes/part-009-tamil-audit.md)
- assembled Tamil: **PASS** — [`notes/part-009-assembled-tamil-check.md`](notes/part-009-assembled-tamil-check.md)
- controlled English draft: **PASS — complete through scan 441 physical endpoint**
- English source check: **PASS** — [`translations/en/PART_009_ENGLISH_CHECK.md`](translations/en/PART_009_ENGLISH_CHECK.md)
- bilingual review: **PASS** — [`translations/en/PART_009_REVIEW.md`](translations/en/PART_009_REVIEW.md)
- split state: **`part-complete`**

Part 009 continues Chapter 45 across scan392→393 and carries Chapters 45–51 through scan 441. The endpoint `அம்ப` is a physical split only and joins Part010 `லமே` as **`அம்பலமே`**.

The bilingual-reviewed English resolves the scan392 `நமது` + scan393 `வாழ்க்கையை` boundary once, continues through Chapters 45–50, and reaches Chapter 51's Part-009 witness at English **`Amb`** corresponding to Tamil **`அம்ப`**. The reviewed Part-010 continuation completes that boundary once as **`Ambalam`**.

The dedicated Part-009 source check made one English-only Chapter-46 fidelity correction: the ritual-oath sequence now reads **“I will lay down the cloth and cross it. I will swear it! I will even embrace the heat!”**, removing the draft's added interpretive phrase `in oath`. Tamil was not changed. The bilingual review required no further English change.

Source-specific oddities remain preserved without external correction, including the Chapter-46 disguise inconsistency and Laila/Qais tale, Chapter-47 `dharpaasooran`, Chapter-48 Aravan/Bhima and caste-marked wording, Chapter-49 violence/rallying rhetoric, Chapter-50 `சாவுக் கண்ணீர்` imagery and Chapter-51's public-service exhortation.

## Part 010 gate state

- mapping: **PASS — 7 / 7**
- canonical: **PASS — 7 / 7**
- verified: **PASS — 7 / 7**
- needs-review: **0**
- Tamil audit: **PASS** — [`notes/part-010-tamil-audit.md`](notes/part-010-tamil-audit.md)
- assembled Tamil: **PASS** — [`notes/part-010-assembled-tamil-check.md`](notes/part-010-assembled-tamil-check.md)
- controlled English draft: **PASS — Chapter 51 continuation scans 442–447 through actual ending + separate scan-448 printer colophon**
- English source check: **PASS** — [`translations/en/PART_010_ENGLISH_CHECK.md`](translations/en/PART_010_ENGLISH_CHECK.md)
- bilingual review: **PASS** — [`translations/en/PART_010_REVIEW.md`](translations/en/PART_010_REVIEW.md)
- split state: **`part-complete`**

Authorized source/baseline difference:

- native: `தங்கத்திற்குப் பக்கத்திலே புதைத்து விடு!”`
- `p10.md`: `தங்கத்திற்குப் பக்கத்திலே புதைத்து` + closing quote
- omitted complete word: **`விடு`**
- user authorization: **granted 2026-09-03**
- canonical restoration: **complete on scan 445**
- reviewed English coverage: **“bury it beside Thangam!”**

Part-010 reviewed English:

- completes reviewed Part-009 English `Amb` as **`Ambalam`**, matching Tamil `அம்ப` + `லமே`;
- continues Mayandi's letter through scan 445, including the authorized `விடு` command;
- preserves Mayandi's scan-445 self-reproach `இந்தப் பாவி` as **“this sinner”** after the bilingual review restored that rhetorical nuance;
- continues post-letter narrative through Velliyambalam's corpse and the recovered/abandoned treasure secret on scan 446;
- represents scan-446 `ஐயப்பன் கொலை வழக்கு` explicitly as **“Ayyappan murder case”**;
- preserves source-form scan-446 `ஆகர` conservatively as **`Agar!`** rather than silently normalizing it;
- reaches the actual novel narrative ending on scan **447 / printed443**, retaining the source's final wording that Durai goes to report that **“Velliyambalam had returned”**;
- keeps scan **448** separate as bilingual-reviewed printer-colophon back matter in `translations/en/sections/99-printer-colophon.md`.

## Exact next activity

Run the **final whole-work English / release review for `புதையல்`** across the complete assembled English package. Verify front matter, introduction, Chapters 1–51, all split-boundary joins, Part-005 source-damage qualifications, user-authorized restorations, controlled terminology, the narrative ending on scan 447, separate scan-448 printer colophon, and consistency of all per-part source-check/review records. Only after that whole-work gate passes should `புதையல்` be marked English verified / release-ready.