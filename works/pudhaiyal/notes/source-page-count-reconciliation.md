# Source page-count reconciliation — புதையல்

Date opened: 2026-08-25  
Last updated: 2026-08-30

## Why this note exists

The first onboarding pass incorrectly treated scans **1–150** as the complete PDF. That conclusion is permanently withdrawn.

Tamil Digital Library describes source identity `TVA_BOK_0064097` as **443 p.** and exposes the item as **PDF — 2 Files**. The repository therefore distinguishes:

- bibliographic printed extent: **443 p.**;
- canonical source-scan records currently created: **1–245**;
- exact original PDF scan/page-object count: **still pending**.

## Authority distinction

The source scan controls exact text, edition wording, punctuation and page structure. Catalogue information is used only for bibliographic / completeness reconciliation.

## Split-source workaround

Received access derivatives:

1. Part 001 — scans **1–49** — **part-complete**
2. Part 002 — scans **50–98** — **part-complete**
3. Part 003 — scans **99–147** — **part-complete**
4. Part 004 — scans **148–196** — **part-complete**
5. Part 005 — scans **197–245** — **part-complete with explicit source-damage qualification**
   - canonical records: **49 / 49**
   - native verified: **42**
   - needs-review: **7 — scans 215–219, 223–224**
   - assembled Tamil / English / bilingual review: **completed with the same qualification**

No split is committed to GitHub.

## Part-005 source anomalies

The derivative physically repeats printed pages **214–215**:

- scan 216 → printed 214
- scan 217 → printed 215
- scan 218 → printed 214 again
- scan 219 → printed 215 again

The duplicate witnesses are retained as distinct provenance records. They carry the same broad repair/tape obstruction and do not expose enough additional source pixels to resolve hidden letters.

Scans **223–224 / printed pages 219–220** are physically torn with substantial missing regions. Their baseline text is retained for comparison, but the hidden areas remain unverified.

These seven records remain `needs-review` after Part-005 completion. The split-level assembled/English workflow does not convert them to native verification.

## Backward integrity audit

Earlier assistant visual passes introduced multiple false source readings. The central correction record is [`backward-integrity-audit-001-118.md`](backward-integrity-audit-001-118.md). The backward integrity audit is **COMPLETE through scan 118**.

## Part-005 forward fidelity

- scans 197–216 — [`visual-fidelity-scans-197-216.md`](visual-fidelity-scans-197-216.md)
- scans 217–228 — [`visual-fidelity-scans-217-228.md`](visual-fidelity-scans-217-228.md)
- scans 229–238 — [`visual-fidelity-scans-229-238.md`](visual-fidelity-scans-229-238.md) — **10 / 10 verified**
- scans 239–245 — [`visual-fidelity-scans-239-245.md`](visual-fidelity-scans-239-245.md) — **7 / 7 verified**

Current chapter structure through the known source:

- chapter 22 closes scan 205;
- chapter 23 begins 206 / closes 214;
- chapter 24 begins 215 / closes 225;
- chapter 25 begins 226 / closes 235;
- chapter 26 begins on scan 235 / closes 240;
- chapter 27 begins scan 241 and continues beyond scan 245;
- scan 245 ends mid-sentence at `இருக்கவே`.

## Current textual state

- canonical page records created: **245**
- verified: **238**
- needs-review: **7**
- partial: **0**
- clean contiguous fully verified range: **1–214**
- individually source-verified later pages: through scan **245**, except the seven damaged records
- Parts 001–005: **part-complete at split level**
- continuous split-level assembled Tamil / English review: **through scan 245**, with the seven source-damage qualifications retained
- full-source manifest: **INCOMPLETE beyond scan 245**

## Full-source extent track

Still required:

1. obtain later source splits beyond scan 245, beginning with scan **246 / printed page 242**;
2. continue chapter 27 directly from the open scan-245 endpoint `இருக்கவே`;
3. process every later source scan under the same canonical/fidelity/split workflow;
4. identify true final text / back matter / closing leaves;
5. determine exact original PDF scan/page-object count;
6. calculate the exact original full-source SHA-256 when byte-level access is available;
7. only after complete-source coverage, run final whole-work Tamil and bilingual audits and release-readiness checks.

Do not infer any of those values from the TDL printed-page count.

## Exact next activity

Obtain / attach the next source derivative beginning at **scan 246 / printed page 242** and continue chapter 27 from native source evidence after `இருக்கவே`.
