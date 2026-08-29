# Split-PDF part-completion workflow — புதையல்

This file records the project-specific workflow for processing the access-derivative split PDFs of `TVA_BOK_0064097_புதையல்.pdf`.

## Governing distinction

The split PDFs are **access derivatives of one source edition**, not separate bibliographic works. Therefore a split may reach a **part-complete checkpoint**, but only the complete source edition may receive the final whole-work `PASSED`, whole-work English `verified`, and release-ready verdicts defined in `NOVEL_PROCESSING_GUIDE.md`.

## User-approved working rule

Going forward, do not stop after transcription of a split PDF. When a split is supplied, complete every workflow stage that can be completed safely for that split before asking for the next split.

For each split:

1. map every represented source scan;
2. create/reconcile every canonical `pages/` record;
3. perform native visual/textual fidelity review;
4. resolve or explicitly retain every `needs-review` item;
5. run a **part-level Tamil audit** for that split;
6. update the incremental assembled Tamil reading layer from audited `pages/` only;
7. once the shared English translation plan exists, translate the audited material from that split in controlled batches;
8. source-check the English against canonical Tamil;
9. run a **part-level bilingual review**;
10. update part status, page map, README and HANDOVER before moving to the next split.

## Cross-split continuity rule

A split boundary is not a narrative boundary.

- If a word, sentence, paragraph, chapter, scene or internal sequence crosses a split boundary, preserve the source continuity.
- Do not invent a chapter/section break because a derivative PDF ends.
- The assembled layer may carry a reversible split-boundary marker for provenance, but the reader-facing narrative remains continuous.
- When the next split arrives, recheck the boundary join before declaring the newer split part-complete.

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
- final assembled-Tamil consistency pass across the entire novel;
- whole-work bilingual review;
- English whole-work `verified`;
- `RELEASE_REPORT.md` release-ready verdict.

## Completed split checkpoints

- Part 001 — scans **1–49** — **`part-complete`**
- Part 002 — scans **50–98** — **`part-complete`**
- Part 003 — scans **99–147** — **`part-complete`**

Part 003 ended mid-sentence at scan 147 / printed page 145 with `அடங்கித்தான் போய்`. Part 004 native scan 148 closes that boundary as `விட்டார்கள்.` → continuous `அடங்கித்தான் போய் விட்டார்கள்.`

## Part 004 — scans 148–196

Source derivative: `TVA_BOK_0064097_புதையல்_part_004_pages_148-196.pdf`

- split pages: **49**
- visibly printed range: **146–194**
- derivative-local map: [`indexes/part-004-page-map.md`](indexes/part-004-page-map.md)
- structural preflight: [`notes/part-004-structural-preflight-148-196.md`](notes/part-004-structural-preflight-148-196.md)
- fidelity reports: [`notes/visual-fidelity-scans-148-158.md`](notes/visual-fidelity-scans-148-158.md), [`notes/visual-fidelity-scans-159-167.md`](notes/visual-fidelity-scans-159-167.md), [`notes/visual-fidelity-scans-168-177.md`](notes/visual-fidelity-scans-168-177.md)
- canonical Tamil verified: **scans 148–177 — 30 / 49**
- unresolved readings in verified range: **0**
- remaining canonical range: **178–196 — 19 scans**
- current state: **in progress**

Closed internal boundaries include:

- scan 158 `டாக்` → scan 159 `துரைக்கு` = **`டாக்துரைக்கு`**;
- scan 171 closes chapter 18 and scan 172 begins chapter **19**;
- scan 173 `வள்ளி வெட்டப்` → scan 174 `பட வேண்டும்` = **`வள்ளி வெட்டப்பட வேண்டும்`**;
- scan 175 `பூமியைத்` → scan 176 `தயார் செய்து வைத்திருக்கிறார்கள்`;
- scan 176 `“சிறிது` → scan 177 `நேரத்தில் உயிர் போய்விடும்”`.

The exact next source activity is **scan 178 / printed page 176 / split page 31**. Scan 177 ends physically at `அந்தகார இருட்டிலே,`; its continuation must be established from scan 178 native source pixels.

After all scans 148–196 are verified, complete Part 004's Tamil audit, assembled Tamil, English translation, bilingual review and status synchronization before moving to another split.
