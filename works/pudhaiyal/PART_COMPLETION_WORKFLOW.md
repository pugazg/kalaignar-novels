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

## Final split checkpoints

- Parts **001–010 — `part-complete`**
- Part 005 retains the explicit source-damage qualification on scans **215–219 and 223–224**.
- Part 009 — scans **393–441** — Tamil audit + assembled Tamil + controlled English source check + bilingual review **PASSED**.
- Part 010 — scans **442–448** — Tamil audit + assembled Tamil + controlled English source check + bilingual review **PASSED**.

## Part 009 gate state

- mapping: **PASS — 49 / 49**
- canonical: **PASS — 49 / 49**
- visual/structural fidelity: **PASS**
- needs-review: **0**
- Tamil audit: **PASS** — [`notes/part-009-tamil-audit.md`](notes/part-009-tamil-audit.md)
- assembled Tamil: **PASS** — [`notes/part-009-assembled-tamil-check.md`](notes/part-009-assembled-tamil-check.md)
- controlled English source check: **PASS** — [`translations/en/PART_009_ENGLISH_CHECK.md`](translations/en/PART_009_ENGLISH_CHECK.md)
- bilingual review: **PASS** — [`translations/en/PART_009_REVIEW.md`](translations/en/PART_009_REVIEW.md)
- split state: **`part-complete`**

Part 009 continues Chapter 45 across scan392→393 and carries Chapters 45–51 through scan 441. The endpoint `அம்ப` is a physical split only and joins Part010 `லமே` as **`அம்பலமே`**.

## Part 010 gate state

- mapping: **PASS — 7 / 7**
- canonical: **PASS — 7 / 7**
- verified: **PASS — 7 / 7**
- needs-review: **0**
- Tamil audit: **PASS** — [`notes/part-010-tamil-audit.md`](notes/part-010-tamil-audit.md)
- assembled Tamil: **PASS** — [`notes/part-010-assembled-tamil-check.md`](notes/part-010-assembled-tamil-check.md)
- controlled English source check: **PASS** — [`translations/en/PART_010_ENGLISH_CHECK.md`](translations/en/PART_010_ENGLISH_CHECK.md)
- bilingual review: **PASS** — [`translations/en/PART_010_REVIEW.md`](translations/en/PART_010_REVIEW.md)
- split state: **`part-complete`**

Authorized Part-010 source/baseline difference:

- native: `தங்கத்திற்குப் பக்கத்திலே புதைத்து விடு!”`
- `p10.md`: `தங்கத்திற்குப் பக்கத்திலே புதைத்து` + closing quote
- omitted complete word: **`விடு`**
- user authorization: **granted 2026-09-03**
- canonical restoration: **complete on scan 445**
- reviewed English: **“bury it beside Thangam!”**

The reviewed Part-010 English also preserves Mayandi's `இந்தப் பாவி` as **“this sinner”**, scan-446 **“Ayyappan murder case”**, source-form **`Agar!`**, and the final source wording that Durai goes to report that **“Velliyambalam had returned.”**

## Whole-work closure

- complete-source map: **PASS — scans 1–448** — [`indexes/FULL_SOURCE_PAGE_MAP.md`](indexes/FULL_SOURCE_PAGE_MAP.md)
- whole-work Tamil archival audit: **PASS WITH PART-005 SOURCE-DAMAGE QUALIFICATION** — [`audit.md`](audit.md)
- assembled Tamil reading layer: **PASS through scan 447 + separate scan-448 colophon**
- all ten split English reviews: **PASS**
- final whole-work bilingual review: **PASS / ENGLISH VERIFIED** — [`translations/en/TRANSLATION_REVIEW.md`](translations/en/TRANSLATION_REVIEW.md)
- release-readiness: **RELEASE-READY WITH SOURCE-DAMAGE QUALIFICATION** — [`translations/en/RELEASE_REPORT.md`](translations/en/RELEASE_REPORT.md)

## Workflow status

There is no remaining split-level or whole-work gate for `புதையல்` in the current archival workflow.

Future changes to this completed work should be source-supported corrections or documentation maintenance only. A new novel/story should begin as a separate `works/<slug>/` workflow after reading the live repository handover and `NEXT_NOVEL_CHAT_PROMPT.md`.
