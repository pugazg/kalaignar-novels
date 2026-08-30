# Source page-count reconciliation — புதையல்

Date opened: 2026-08-25  
Last updated: 2026-08-30

## Why this note exists

The first onboarding pass incorrectly treated scans **1–150** as the complete PDF. That conclusion is permanently withdrawn.

Tamil Digital Library describes source identity `TVA_BOK_0064097` as **443 p.** and exposes the item as **PDF — 2 Files**. The repository therefore distinguishes:

- bibliographic printed extent: **443 p.**;
- source scans currently represented by received derivatives: **1–294**;
- canonical source-scan records currently created: **1–251**;
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
6. Part 006 — scans **246–294 / printed 242–290** — **in progress**
   - physical pages mapped: **49 / 49**
   - canonical records created: **6 / 49 — scans 246–251**
   - native verified: **6**
   - needs-review: **0**
   - not-started: **43 — scans 252–294**
   - derivative SHA-256: `34a5ea5eb91a71ca8674760257779eb4ed6bdc6640517f8830b9ee70aa34aec7`

No split is committed to GitHub.

## Part-006 opening reconciliation

The mandatory cross-split test is source-established:

- scan 245 / printed 241 ends `இருக்கவே`;
- scan 246 / printed 242 begins `இருக்கிறாள் பரிமளா, ...`;
- source continuity is therefore `இருக்கவே இருக்கிறாள் பரிமளா, ...`.

No derivative-created word, sentence, paragraph, scene or chapter boundary is inserted.

Scans 246–249 / printed 242–245 are **4 / 4 verified** from the Iteration-23 baseline reconciliation. Scans **250–251 / printed 246–247** were then directly transcribed from native pages at high resolution without a user baseline and are also **verified**. Scan 251 ends the current scene with a source-printed four-star internal separator. See [`visual-fidelity-scans-246-249.md`](visual-fidelity-scans-246-249.md), [`visual-fidelity-scan-250.md`](visual-fidelity-scan-250.md), and [`visual-fidelity-scan-251.md`](visual-fidelity-scan-251.md).

The permanent old-Tamil-typeform pre-correction check is mandatory: inspect the complete glyph cluster at high resolution before deciding that a final vowel sign or old glyph is absent. The retrospective `லை` correction record is [`old-glyph-retrospective-audit-120-245.md`](old-glyph-retrospective-audit-120-245.md).

## Part-006 physical structure map

Full physical-page inspection of the 49-page derivative establishes printed page labels **242–290** and these chapter transitions:

- chapter 28 begins scan 247 / printed 243;
- a four-star internal transition occurs at the foot of scan 251 / printed 247;
- chapter 29 begins scan 254 / printed 250;
- chapter 30 begins scan 262 / printed 258;
- chapter 31 begins scan 271 / printed 267;
- chapter 32 begins scan 278 / printed 274;
- chapter 33 begins scan 288 / printed 284 and continues through scan 294 / printed 290.

This is structure mapping only for scans 252–294; their text remains `not-started` until native reconciliation.

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

A separate 2026-08-30 old-glyph retrospective audit corrected scan 120 and 22 readable Part-005 scans after the faint final `லை` typeform was recognized. Those corrections are synchronized into canonical/assembled/audit documentation.

## Current textual state

- canonical page records created: **251**
- verified: **244**
- needs-review: **7**
- partial: **0**
- clean contiguous fully verified range: **1–214**
- individually source-verified later pages: through scan **251**, except the seven damaged Part-005 records
- Parts 001–005: **part-complete at split level**
- Part 006: **in progress — 6 / 49 verified**
- continuous split-level assembled Tamil / English review: **through scan 245 only**, with the seven source-damage qualifications retained
- source scans physically mapped from received derivatives: **through scan 294**
- full-source manifest: **still incomplete beyond scan 294**

## Full-source extent track

Still required:

1. reconcile Part-006 scans **252–294** under the same canonical/fidelity workflow;
2. complete the Part-006 Tamil audit, assembled Tamil, controlled English and bilingual review before calling Part 006 `part-complete`;
3. obtain later source splits beyond scan 294;
4. process every later source scan under the same workflow;
5. identify true final text / back matter / closing leaves;
6. determine exact original PDF scan/page-object count;
7. calculate the exact original full-source SHA-256 when byte-level access is available;
8. only after complete-source coverage, run final whole-work Tamil and bilingual audits and release-readiness checks.

Do not infer any of those values from the TDL printed-page count.

## Exact next activity

Directly transcribe and visually verify **scan 252 / printed page 248** against native Part-006 source pixels, beginning after the source-printed four-star internal transition and applying the permanent old-Tamil-typeform pre-correction check.