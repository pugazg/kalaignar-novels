# Tamil / split-part audit — புதையல்

Status: **IN PROGRESS — Parts 001–005 part-complete; retrospective old-glyph integrity repair completed; Part 006 canonical/native-fidelity work underway; whole-work gate not eligible**

Source: `TVA_BOK_0064097_புதையல்.pdf`

## Permanent visual-integrity rule

The native scan is the textual authority. Before overriding a user baseline because a final character or vowel mark appears absent, inspect the **whole glyph cluster at high resolution**, explicitly consider old/historical Tamil typeforms, and use more than one useful scale/contrast when a mark is faint. Compare another clear occurrence from the same edition where helpful.

This source demonstrated that faint final `லை` can resemble bare `ல்` at ordinary zoom. A correction therefore requires positive native-pixel evidence. If the pixels remain ambiguous, retain the baseline and `needs-review`. Never apply a global `வில்ல` ↔ `வில்லை` or `இல்ல` ↔ `இல்லை` replacement.

Retrospective record: [`notes/old-glyph-retrospective-audit-120-245.md`](notes/old-glyph-retrospective-audit-120-245.md).

## Completed part checkpoints

| Part | Source scans | Tamil audit | Assembled Tamil | English review | State |
|---|---:|---|---|---|---|
| 001 | 1–49 | PASSED | PASSED | PASSED | part-complete |
| 002 | 50–98 | PASSED | PASSED | PASSED | part-complete |
| 003 | 99–147 | **PASSED after scan-120 old-glyph correction** | **re-synchronized / PASSED** | PASSED | part-complete |
| 004 | 148–196 | PASSED | PASSED | PASSED | part-complete |
| 005 | 197–245 | **SOURCE-DAMAGE-CLOSED after readable-page old-glyph reinspection** | **re-synchronized / PASSED WITH QUALIFICATION** | **PASSED WITH QUALIFICATION** | **part-complete** |

## Retrospective old-glyph integrity repair — 2026-08-30

High-resolution native reinspection established earlier assistant `லை`-loss errors on **23 readable physical scans**:

- Part 003: scan **120 / printed 118**;
- Part 005: scans **198, 199, 201, 207, 214, 220, 221, 225, 228, 229, 230, 231, 233, 234, 235, 238, 239, 241, 242, 243, 244, 245**.

The canonical page records were corrected and assembled Tamil chapters **13 and 22–27** were re-synchronized. This was not a normalization pass. The seven physically damaged Part-005 records **215–219 and 223–224** remain `needs-review`.

## Part 006 — active canonical/fidelity stage

Derivative: `TVA_BOK_0064097_புதையல்_part_006_pages_246-294.pdf`

- physical pages mapped: **49 / 49 — scans 246–294 / printed 242–290**
- canonical records created: **14 / 49 — scans 246–259**
- verified: **14**
- needs-review: **0**
- partial: **0**
- not-started: **35 — scans 260–294**
- derivative map: [`indexes/part-006-page-map.md`](indexes/part-006-page-map.md)
- native-fidelity records: [`notes/visual-fidelity-scans-246-249.md`](notes/visual-fidelity-scans-246-249.md), [`notes/visual-fidelity-scan-250.md`](notes/visual-fidelity-scan-250.md), [`notes/visual-fidelity-scan-251.md`](notes/visual-fidelity-scan-251.md), [`notes/visual-fidelity-scans-252-255.md`](notes/visual-fidelity-scans-252-255.md), [`notes/visual-fidelity-scans-256-259.md`](notes/visual-fidelity-scans-256-259.md)
- Part-006 Tamil audit: **NOT ELIGIBLE**
- assembled Tamil / English / bilingual review: **NOT ELIGIBLE**
- state: **`in-progress`**

### Mandatory split-boundary check

Native evidence establishes:

- scan 245 ends `இருக்கவே`;
- scan 246 begins `இருக்கிறாள் பரிமளா, ...`;
- source join: `இருக்கவே இருக்கிறாள் பரிமளா, ...`.

This derivative boundary creates no narrative break.

### Current verified joins / transitions

- 245→246: `இருக்கவே` + `இருக்கிறாள் ...`;
- 247→248: `இன்` + `னும்` = `இன்னும்`;
- 248→249: `அவ` + `தாரம்` = `அவதாரம்`;
- scan 251 ends a scene with the source-printed four-star separator;
- 257→258: `வெள்ளியம்` + `பலம்` = `வெள்ளியம்பலம்`.

### Part-006 verified reconciliation through scan 259

Scans 246–255 had already been verified. Native derivative mapping established that the remaining text under the user's Iteration-24 extraction continues through **scans 256–259 / printed 252–255**. Those four pages are now source-verified.

Material findings include:

- scan 256: source `காட்டுகிறியா?`;
- scan 257: source-specific `நன்றுகப் பார்த்தான்`; page ends `வெள்ளியம்`;
- scan 258: opening `பலம்` completes the cross-page word; source `அனாவசியமாக`; separated `காதலிக்க வில்லையே`;
- scan 259: source `மண்ணுங் கட்டியாவது!`, separated `விளங்க வில்லையே!`, and confirmed `ஒன்றாய்ப் பிசைந்து`.

No unresolved old-type glyph remains in scans 256–259. The supplied Iteration-25 baseline begins at **scan 260 / printed 256**.

### Structure mapped in Part 006

- chapter 27 closes / chapter 28 begins on scan 247;
- four-star internal transition on scan 251;
- chapter 29 begins scan 254;
- chapter 30 begins scan 262;
- chapter 31 begins scan 271;
- chapter 32 begins scan 278;
- chapter 33 begins scan 288 and continues through the derivative endpoint.

Only scans 246–259 are textually verified at this checkpoint; structural inspection does not upgrade scans 260–294.

## Part 005 — completed split checkpoint

- records created: **49 / 49 — scans 197–245**
- verified: **42**
- needs-review: **7 — scans 215–219, 223–224**
- Part-005 Tamil audit: [`notes/part-005-tamil-audit.md`](notes/part-005-tamil-audit.md) — **closed with explicit source-damage exceptions and old-glyph reinspection on readable pages**
- assembled Tamil: **re-synchronized with corrected canonical Tamil**
- controlled English: **source-checked**
- bilingual review: **completed with the same source-damage qualification**
- state: **`part-complete`**

## Aggregate canonical state

- records created: **259**
- verified: **252**
- needs-review: **7**
- partial: **0**
- clean contiguous fully verified coverage: through scan **214 / printed page 212**
- later individually verified coverage: through scan **259**, except the seven explicitly damaged scans
- Parts 001–005: **part-complete at split level**
- Part 006: **in progress — 14 / 49 verified**
- continuous split-level assembled Tamil / English review: through scan **245** only
- full-source physical coverage from received derivatives: mapped through scan **294**, but canonical text only through scan 259

## Whole-work gate

**NOT ELIGIBLE.** Complete source extent, later scans, true ending/back matter, final Tamil audit and whole-work bilingual review remain open.

## Exact next activity

Reconcile **scan 260 / printed page 256** from the supplied Iteration-25 baseline against native source pixels, applying the permanent old-Tamil-typeform pre-correction gate to every disputed glyph. Do not run Part-006 Tamil audit or downstream gates yet.