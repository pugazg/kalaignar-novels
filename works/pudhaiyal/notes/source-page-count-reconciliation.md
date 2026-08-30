# Source page-count reconciliation — புதையல்

Date opened: 2026-08-25  
Last updated: 2026-08-30

## Why this note exists

The first onboarding pass incorrectly treated scans **1–150** as the complete PDF. That conclusion is permanently withdrawn.

Tamil Digital Library describes source identity `TVA_BOK_0064097` as **443 p.** and exposes the item as **PDF — 2 Files**. The repository therefore distinguishes:

- bibliographic printed extent: **443 p.**;
- canonical source-scan records currently created: **1–238**;
- exact original PDF scan/page-object count: **still pending**.

## Authority distinction

The source scan controls exact text, edition wording, punctuation and page structure. Catalogue information is used only for bibliographic / completeness reconciliation.

## Split-source workaround

Received access derivatives:

1. Part 001 — scans **1–49** — **part-complete**
2. Part 002 — scans **50–98** — **part-complete**
3. Part 003 — scans **99–147** — **part-complete**
4. Part 004 — scans **148–196** — **part-complete**
5. Part 005 — scans **197–245** — **in progress**
   - records created through scan **238**
   - verified physical records: **35 / 42 processed Part-005 scans**
   - needs-review: **7 — scans 215–219, 223–224**
   - not-started inside derivative: **239–245 — 7**

No split is committed to GitHub.

## Part-005 source anomalies

The derivative physically repeats printed pages **214–215**:

- scan 216 → printed 214
- scan 217 → printed 215
- scan 218 → printed 214 again
- scan 219 → printed 215 again

The duplicate witnesses are retained as distinct provenance records. They carry the same broad repair/tape obstruction and do not expose enough additional source pixels to resolve hidden letters.

Scans **223–224 / printed pages 219–220** are physically torn with substantial missing regions. Their baseline text is retained for comparison, but the hidden areas remain unverified.

## Backward integrity audit

Earlier assistant visual passes introduced multiple false source readings. The central correction record is [`backward-integrity-audit-001-118.md`](backward-integrity-audit-001-118.md). The backward integrity audit is **COMPLETE through scan 118**.

## Part-005 forward fidelity

- scans 197–216 — [`visual-fidelity-scans-197-216.md`](visual-fidelity-scans-197-216.md)
- scans 217–228 — [`visual-fidelity-scans-217-228.md`](visual-fidelity-scans-217-228.md)
- scans 229–238 — [`visual-fidelity-scans-229-238.md`](visual-fidelity-scans-229-238.md) — **10 / 10 verified**

Current chapter structure in Part 005:

- chapter 22 closes scan 205;
- chapter 23 begins 206 / closes 214;
- chapter 24 begins 215 / closes 225;
- chapter 25 begins 226 / closes 235;
- chapter 26 begins on scan 235 and continues beyond scan 238.

## Current textual state

- canonical page records created: **238**
- verified: **231**
- needs-review: **7**
- partial: **0**
- clean contiguous verified range: **1–214**
- individually source-verified later pages: through scan **238**, except the seven damaged records
- Parts 001–004: **part-complete**
- Part 005: **in progress**
- full-source manifest: **INCOMPLETE**

## Full-source extent track

Still required:

1. process scans **239–245** to close Part 005's physical inventory;
2. explicitly resolve or carry the seven damaged `needs-review` physical records under project policy;
3. run the Part-005 Tamil audit only when eligible;
4. then complete assembled Tamil, English and bilingual review for Part 005;
5. obtain later source splits beyond scan 245;
6. identify true final text / back matter / closing leaves;
7. determine exact original PDF scan/page-object count;
8. calculate the exact original full-source SHA-256 when byte-level access is available.

Do not infer any of those values from the TDL printed-page count.

## Exact next activity

Continue canonical transcription at **scan 239 / printed page 235 / Part-005 split page 43**.
