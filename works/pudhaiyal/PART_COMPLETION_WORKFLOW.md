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

A split may use these checkpoint states:

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

These gates are aggregated only after all split ranges and the true source ending/back matter are known.

## Current backfill request

The first two supplied derivatives are being backfilled under this workflow:

- Part 001 — scans 1–49;
- Part 002 — scans 50–98.

Both already have fully verified canonical page records after the backward-integrity recovery. Their remaining derived-layer and bilingual stages are to be completed before normal forward work continues.
