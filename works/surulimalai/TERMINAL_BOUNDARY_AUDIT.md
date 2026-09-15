# Terminal / Full-198-Page Reconciliation — சுருளிமலை

Status: **COMPLETE / PASS**.

## Complete-source identity

- physical pages: **198**
- bytes: **268,529,598**
- SHA-256: **`3d940115bed12e818b8f3cbfbdfca56def0285aef803334f8711acf27f7408ea`**
- PDF metadata check: `Pages: 198`
- source format: image-only scan

The historical 150-page ChatGPT Files parser view is **non-authoritative** and remains documented only as an ingestion limitation.

## Same-copy / split continuity check

The complete source was render-compared against the supplied part007 derivative at 30 dpi:

- complete scan181 ↔ part007 page1 — **pixel-identical**;
- complete scan190 ↔ part007 page10 — **pixel-identical**;
- complete scan198 ↔ part007 page18 — **pixel-identical**.

This confirms that the terminal split used for scans181–198 belongs to the same physical source representation.

## Canonical record reconciliation

Before terminal cleanup, `works/surulimalai/pages/` contained one obsolete invalidated parser-derived record, `0150-back-cover.md`, alongside the true scan150 record. It is not canonical.

Terminal cleanup:

- obsolete `pages/0150-back-cover.md` moved to `works/surulimalai/superseded/0150-back-cover.invalidated.md`;
- canonical `pages/` set now contains **198 records**, one for each physical scan **1–198**;
- no missing scan numbers;
- no duplicate scan numbers;
- all canonical scan records are **verified**.

## Page-map reconciliation

The manifest had two control defects:

1. scans **48–49** were absent from the table;
2. rows **50–54** were stranded above the table header.

Both are repaired.

Final manifest invariant:

- **198 unique rows**;
- ordered **1→198**;
- no gaps;
- no duplicates;
- printed-page mapping retained only where source-visible.

Stale `T3 pending` wording in final verified rows was normalized to current **T1/T2/T3 PASS** state.

## Structural reconciliation

- scans1–4 — front matter: **verified**;
- scan5 — unnumbered `அறிமுகம்`;
- scan197 / printed195 — source-visible work ending **`[முற்றிற்று.]`**;
- scan198 — **back-cover / publisher-device**, no story body;
- terminal boundary: **resolved**.

Source-visible chapter sequence is preserved exactly as archived. Notably, the source-visible sequence jumps from chapter **5** to chapter **8**; no chapter **6** or **7** marker is invented.

## Final result

- complete physical-source coverage: **198/198**
- canonical page records: **198/198**
- T1/T2/T3 verified body/source records through scan198: **PASS**
- unresolved terminal/control inconsistencies: **0**
- terminal/full-198-page reconciliation: **PASS**
- Tamil source-archival phase: **CLOSED**

The earlier terminal audit conclusions based on the 150-page parser view remain retracted and are superseded by this complete-source reconciliation.
