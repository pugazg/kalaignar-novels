# Split-PDF part-completion workflow — புதையல்

This file records the project-specific workflow for processing the access-derivative split PDFs of `TVA_BOK_0064097_புதையல்.pdf`.

## Governing distinction

The split PDFs are **access derivatives of one source edition**, not separate bibliographic works. Therefore a split may reach a **part-complete checkpoint**, but only the complete source edition may receive the final whole-work `PASSED`, whole-work English `verified`, and release-ready verdicts defined in `NOVEL_PROCESSING_GUIDE.md`.

## User-approved working rule

Do not stop after transcription of a split PDF. When a split is supplied, complete every workflow stage that can be completed safely for that split before asking for the next split.

For each split:

1. map every represented source scan;
2. create/reconcile every canonical `pages/` record;
3. perform native visual/textual fidelity review;
4. resolve or explicitly retain every `needs-review` item;
5. run a **part-level Tamil audit**;
6. update the incremental assembled Tamil reading layer from audited `pages/` only;
7. translate the audited material under the shared English translation plan;
8. source-check the English against canonical Tamil;
9. run a **part-level bilingual review**;
10. update part status, page map, README and HANDOVER before moving to the next split.

## Cross-split continuity rule

A split boundary is not a narrative boundary. A word, sentence, paragraph, chapter, scene or internal sequence crossing a split must remain continuous. A reversible provenance marker may be retained, but no false narrative break may be invented.

## Part-level states

- `tamil-pages-verified`
- `part-tamil-audit-passed`
- `assembled-part-checked`
- `english-part-reviewed`
- `part-complete`

`part-complete` means every stage safely possible for that derivative has passed. It does **not** mean the novel/source edition is complete.

## Whole-work gates retained

The following remain whole-source gates and cannot be closed per split:

- complete source extent / complete page map;
- final whole-work Tamil audit;
- final assembled-Tamil consistency pass;
- whole-work bilingual review;
- English whole-work `verified`;
- `RELEASE_REPORT.md` release-ready verdict.

## Completed split checkpoints

- Part 001 — scans **1–49** — **`part-complete`**
- Part 002 — scans **50–98** — **`part-complete`**
- Part 003 — scans **99–147** — **`part-complete`**
- Part 004 — scans **148–196** — **`part-complete`**

## Part 004 completion record

Source derivative: `TVA_BOK_0064097_புதையல்_part_004_pages_148-196.pdf`

- split pages: **49**
- printed range: **146–194**
- canonical Tamil: **49 / 49 verified**
- unresolved: **0**
- Tamil audit: [`notes/part-004-tamil-audit.md`](notes/part-004-tamil-audit.md) — **PASSED**
- assembled Tamil: **PASSED through scan 196**
- English review: [`translations/en/PART_004_REVIEW.md`](translations/en/PART_004_REVIEW.md) — **PASSED**
- final derivative map: [`indexes/part-004-page-map.md`](indexes/part-004-page-map.md) — **part-complete**

Cross-boundary checks include:

- 147→148 `அடங்கித்தான் போய் விட்டார்கள்.`
- 158→159 `டாக்துரைக்கு`
- 173→174 `வள்ளி வெட்டப்பட வேண்டும்`
- 187→188 `அதுகூட இல்லை எனக்கு.`
- 193→194 `ஆகாரமும்`
- 194→195 `வேண்டாமென்று`
- 195→196 `ஒரு பெருமாள் கோவில் வாசல்—`

Scan 196 closes chapter 21 and begins chapter **22**. Part 004 ends there only because the derivative ends; chapter 22 continues.

## Exact next source activity

Obtain / attach the next source split beginning at **scan 197 / printed page 195**. Establish chapter 22's continuation from native source pixels, then complete the entire per-split workflow before moving onward.
