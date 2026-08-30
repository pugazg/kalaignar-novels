# Source page-count reconciliation — புதையல்

Date opened: 2026-08-25  
Last updated: 2026-08-30

## Why this note exists

The first onboarding pass incorrectly treated scans **1–150** as the complete PDF. That conclusion is permanently withdrawn.

Tamil Digital Library describes source identity `TVA_BOK_0064097` as **443 p.** and exposes the item as **PDF — 2 Files**. The repository therefore distinguishes:

- bibliographic printed extent: **443 p.**;
- source scans currently represented by received derivatives: **1–294**;
- canonical source-scan records currently created: **1–261**;
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
   - canonical records created: **16 / 49 — scans 246–261**
   - native verified: **16**
   - needs-review: **0**
   - not-started: **33 — scans 262–294**
   - derivative SHA-256: `34a5ea5eb91a71ca8674760257779eb4ed6bdc6640517f8830b9ee70aa34aec7`

No split is committed to GitHub.

## Part-006 opening reconciliation

The mandatory cross-split test is source-established:

- scan 245 / printed 241 ends `இருக்கவே`;
- scan 246 / printed 242 begins `இருக்கிறாள் பரிமளா, ...`;
- source continuity is therefore `இருக்கவே இருக்கிறாள் பரிமளா, ...`.

No derivative-created word, sentence, paragraph, scene or chapter boundary is inserted.

Scans 246–255 were previously verified. Native derivative mapping established that user Iteration 24 continues through **scans 256–259 / printed 252–255**. A corrected second high-resolution inspection confirms the user's baseline forms `காட்டுகிறாயா?`, `நன்றாகப் பார்த்தான்`, `அநாவசியமாக`, and `மண்ணாங் கட்டியாவது!`; the earlier assistant alternatives are withdrawn. The cross-page `வெள்ளியம்` + `பலம்` = `வெள்ளியம்பலம்` and `ஒன்றாய்ப் பிசைந்து` remain source-confirmed. See [`visual-fidelity-scans-256-259.md`](visual-fidelity-scans-256-259.md).

The safeguard is now stronger: an old/faint vowel-sign, same-word glyph, or line-wrap spacing disagreement requires a second independent high-resolution pass before overriding the baseline; a printed line break alone never establishes word spacing.

## Scan 260 / printed 256

Iteration 25 begins canonically at scan 260 and is source-verified. The strengthened two-pass comparison positively establishes only these baseline differences:

- typo `சொலலு` → source `சொல்லு`, giving `சொல்லு! சொல்லு!`;
- continuous source `சாமியாருக்குத்தான்`;
- source `பொய் சொல்லுகிறாயா?`;
- source punctuation `ஏன்!` retained.

The physical page ends at `வெள்ளியம்பலம்`.

## Scan 261 / printed 257

Direct high-resolution native inspection closes the prior sentence as `வெள்ளியம்பலம் கேட்டு விட்டு, ...`. Source-specific `தவழுகத்`, `ஆள்பாடு ஆயிடும்`, `எங்கேயிருக்கு`, and `பேஷாக` are preserved as printed. The physical page ends at `விடிந்த`; scan 262 must continue the sentence before the source-printed chapter 30 transition later on the page. No unresolved old-type glyph remains after the strengthened second pass.

## Part-006 physical structure map

Full physical-page inspection of the 49-page derivative establishes printed page labels **242–290** and these chapter transitions:

- chapter 28 begins scan 247 / printed 243;
- a four-star internal transition occurs at scan 251 / printed 247;
- chapter 29 begins scan 254 / printed 250;
- chapter 30 begins scan 262 / printed 258;
- chapter 31 begins scan 271 / printed 267;
- chapter 32 begins scan 278 / printed 274;
- chapter 33 begins scan 288 / printed 284 and continues through scan 294 / printed 290.

This is structure mapping only for scans 262–294; their text remains `not-started` until native reconciliation.

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

- canonical page records created: **261**
- verified: **254**
- needs-review: **7**
- partial: **0**
- clean contiguous fully verified range: **1–214**
- individually source-verified later pages: through scan **261**, except the seven damaged Part-005 records
- Parts 001–005: **part-complete at split level**
- Part 006: **in progress — 16 / 49 verified**
- continuous split-level assembled Tamil / English review: **through scan 245 only**, with the seven source-damage qualifications retained
- source scans physically mapped from received derivatives: **through scan 294**
- full-source manifest: **still incomplete beyond scan 294**

## Full-source extent track

Still required:

1. reconcile Part-006 scans **262–294** under the same canonical/fidelity workflow;
2. complete the Part-006 Tamil audit, assembled Tamil, controlled English and bilingual review before calling Part 006 `part-complete`;
3. obtain later source splits beyond scan 294;
4. process every later source scan under the same workflow;
5. identify true final text / back matter / closing leaves;
6. determine exact original PDF scan/page-object count;
7. calculate the exact original full-source SHA-256 when byte-level access is available;
8. only after complete-source coverage, run final whole-work Tamil and bilingual audits and release-readiness checks.

Do not infer any of those values from the TDL printed-page count.

## Exact next activity

Reconcile **scan 262 / printed page 258** directly against native Part-006 source pixels, first closing scan 261's endpoint `விடிந்த`, then capture the source-printed chapter 30 transition later on the page. Apply the strengthened two-pass old-Tamil-typeform rule.