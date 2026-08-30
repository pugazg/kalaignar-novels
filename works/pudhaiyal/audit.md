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

The canonical page records were corrected and assembled Tamil chapters **13 and 22–27** were re-synchronized. Representative restored forms include `இல்லை`, `தவறொன்றுமில்லை`, `இறக்கவில்லை`, `புரியவில்லை`, `முடியவில்லை`, `வரவில்லை`, `தேவையில்லை`, `எதுவுமில்லை`, `பிரியமும் இல்லை`, and `வேண்டியதில்லை` where the native pixels establish the old/faint final `லை`.

This was **not** a normalization pass. Source-specific readings such as scan 229 `தீண்ட வில்லையே` and scan 244's first `தெரியவில்லையே` remain unchanged because their native pixels support those forms.

The seven physically damaged Part-005 records **215–219 and 223–224** remain `needs-review`. Neither grammar nor the newly recognized glyph pattern may be used to reconstruct obscured or missing pixels.

## Part 006 — active canonical/fidelity stage

Derivative: `TVA_BOK_0064097_புதையல்_part_006_pages_246-294.pdf`

- physical pages mapped: **49 / 49 — scans 246–294 / printed 242–290**
- canonical records created: **10 / 49 — scans 246–255**
- verified: **10**
- needs-review: **0**
- partial: **0**
- not-started: **39 — scans 256–294**
- derivative map: [`indexes/part-006-page-map.md`](indexes/part-006-page-map.md)
- native-fidelity records: [`notes/visual-fidelity-scans-246-249.md`](notes/visual-fidelity-scans-246-249.md), [`notes/visual-fidelity-scan-250.md`](notes/visual-fidelity-scan-250.md), [`notes/visual-fidelity-scan-251.md`](notes/visual-fidelity-scan-251.md), [`notes/visual-fidelity-scans-252-255.md`](notes/visual-fidelity-scans-252-255.md)
- Part-006 opening old-glyph correction record: [`notes/old-glyph-correction-scans-246-248.md`](notes/old-glyph-correction-scans-246-248.md)
- retrospective earlier-page audit: [`notes/old-glyph-retrospective-audit-120-245.md`](notes/old-glyph-retrospective-audit-120-245.md)
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
- 249→250: continuous Dukkaram–Raman scene;
- 250→251: continuous Dukkaram–Raman dialogue;
- scan 251 ends that scene with the source-printed four-star separator `* * * *`;
- scan 252 begins the following night scene inside chapter 28;
- 253→254 continues the night/chase scene; chapter 29 begins later on scan 254;
- 255→256 has no mid-word join.

### Part-006 verified reconciliation through scan 255

Scans 246–249 were reconciled against Iteration 23. Scans 250–251 were transcribed directly from native pages. Scans **252–255 / printed 248–251** were reconciled against user Iteration 24 and verified against enlarged native pixels.

Source-established corrections/retentions in scans 252–255 include:

- scan 252: baseline line-wrap `ஒரு இடத் தில்` → source word `ஒரு இடத்தில்`;
- scan 253: baseline line-wrap `சல சலப்பும்` → `சலசலப்பும்`;
- scan 253: baseline line-wrap `நினைவு படுத்தின` → `நினைவுபடுத்தின`;
- scan 253: source `பூதம் நான்தான்!`, not baseline-separated `நான் தான்`;
- scan 254: source `உத்திரவை`, `பஸ்பமாக்கிவிடப்`, and source-printed chapter **29**;
- scan 255: source spelling `பரிக்ஷையா` and colloquial `மாட்டிக்கிட்டேனே`, `விட்டுடு`, `வேணும்னா`, `வச்சுக்க`, `கொடுத்தா`.

Source dash punctuation replaces baseline ASCII hyphens only where native pixels clearly establish the printed dash. No mechanical spelling normalization was applied. The permanent old-type glyph check found **0 unresolved glyphs** in scans 252–255.

### Structure mapped in Part 006

- chapter 27 continues from scan 245 and closes on scan 247;
- chapter 28 begins scan 247;
- four-star internal transition at the foot of scan 251;
- chapter 29 begins scan 254;
- chapter 30 begins scan 262;
- chapter 31 begins scan 271;
- chapter 32 begins scan 278;
- chapter 33 begins scan 288 and continues through the derivative endpoint.

Only scans 246–255 are textually verified at this checkpoint; structural inspection does not upgrade scans 256–294.

## Part 005 — completed split checkpoint

- records created: **49 / 49 — scans 197–245**
- verified: **42**
- needs-review: **7 — scans 215–219, 223–224**
- Part-005 Tamil audit: [`notes/part-005-tamil-audit.md`](notes/part-005-tamil-audit.md) — **closed with explicit source-damage exceptions and old-glyph reinspection on readable pages**
- assembled Tamil: **re-synchronized with corrected canonical Tamil**
- controlled English: **source-checked; restored final `லை` forms do not require semantic prose changes**
- bilingual review: **completed with the same source-damage qualification**
- state: **`part-complete`**

## Aggregate canonical state

- records created: **255**
- verified: **248**
- needs-review: **7**
- partial: **0**
- clean contiguous fully verified coverage: through scan **214 / printed page 212**
- later individually verified coverage: through scan **255**, except the seven explicitly damaged scans
- Parts 001–005: **part-complete at split level**
- Part 006: **in progress — 10 / 49 verified**
- continuous split-level assembled Tamil / English review: through scan **245** only
- full-source physical coverage from received derivatives: mapped through scan **294**, but canonical text only through scan 255

## Whole-work gate

**NOT ELIGIBLE.** Complete source extent, later scans, true ending/back matter, final Tamil audit and whole-work bilingual review remain open.

## Exact next activity

Reconcile **scan 256 / printed page 252** from user Iteration 25 against native source pixels, applying the permanent old-Tamil-typeform pre-correction gate to every disputed glyph. Do not run Part-006 Tamil audit or downstream gates yet.