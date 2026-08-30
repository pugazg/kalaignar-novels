# Source page-count reconciliation — புதையல்

Date opened: 2026-08-25  
Last updated: 2026-08-30

## Why this note exists

The first onboarding pass incorrectly treated scans **1–150** as the complete PDF. That conclusion is permanently withdrawn.

Tamil Digital Library describes source identity `TVA_BOK_0064097` as **443 p.** The repository therefore distinguishes:

- bibliographic printed extent: **443 p.**;
- canonical physical-scan records currently created: **1–228**;
- exact original PDF scan/page-object count: **still pending**.

## Split-source access received

1. Part 001 — scans **1–49** — **part-complete**
2. Part 002 — scans **50–98** — **part-complete**
3. Part 003 — scans **99–147** — **part-complete**
4. Part 004 — scans **148–196** — **part-complete**
5. Part 005 — scans **197–245** — **in progress**
   - records created through scan **228**
   - **25 verified / 7 needs-review** within Part 005 so far
   - scans **229–245** not yet processed

No split PDF is committed to GitHub.

## Part-005 physical-page anomaly

The source derivative includes repeated damaged physical scans rather than a simple one-scan-per-printed-page sequence:

- scan 215 → printed 213
- scan 216 → printed 214
- scan 217 → printed 215
- scan 218 → printed 214 again
- scan 219 → printed 215 again
- scan 220 resumes printed 216

Printed pages 214–215 are therefore represented by duplicate physical witnesses. Their repair/tape obstruction is materially the same and does not reveal enough additional source letters to close the affected readings.

Printed pages 219–220, represented by scans 223–224, have large physical losses and also remain `needs-review`.

This means **physical scan count, printed-page count and narrative-page count must not be conflated** when reconciling the full source.

## Current textual state

- canonical page records created: **228**
- verified: **221**
- needs-review: **7**
- partial: **0**
- clean continuous verified coverage: through scan **214 / printed page 212**
- Parts 001–004: **part-complete**
- Part 005: **in progress**
- full-source manifest: **INCOMPLETE beyond scan 228**

## Current Part-005 structure

- chapter 22 closes at scan 205;
- chapter 23 begins at 206 and closes at 214;
- chapter 24 begins at 215 and closes at 225;
- chapter 25 begins at 226 and continues beyond scan 228.

## Full-source extent track

Still required:

1. process Part-005 scans **229–245**;
2. retain or resolve damaged-page `needs-review` readings only from stronger source evidence;
3. complete the Part-005 Tamil audit, assembled Tamil, English and bilingual review when eligible;
4. reconcile later source splits beyond scan 245;
5. identify true final text / back matter / closing leaves;
6. determine exact original PDF scan/page-object count;
7. calculate the exact original full-source SHA-256 when byte-level access is available.

Do not infer any of those values from the TDL printed-page count.

## Exact next activity

Continue at **scan 229 / printed page 225 / Part-005 split page 33**. Scan 228 ends at `‘கள்வர் புகும்`; the next native page visibly continues `வழியிலே’`.
