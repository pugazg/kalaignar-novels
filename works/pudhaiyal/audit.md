# Tamil / split-part audit — புதையல்

Status: **IN PROGRESS — Parts 001–005 part-complete; retrospective old-glyph integrity repair completed; Part 006 canonical/native-fidelity work underway; whole-work gate not eligible**

Source: `TVA_BOK_0064097_புதையல்.pdf`

## Permanent visual-integrity rule

The native scan is the textual authority. Before overriding a user baseline because a final character or vowel mark appears absent, inspect the **whole glyph cluster at high resolution**, explicitly consider old/historical Tamil typeforms, and use more than one useful scale/contrast when a mark is faint. Compare another clear occurrence from the same edition where helpful.

This source demonstrated that faint final `லை` can resemble bare `ல்` at ordinary zoom. A correction therefore requires positive native-pixel evidence. If the pixels remain ambiguous, retain the baseline and `needs-review`. Never apply a global `வில்ல` ↔ `வில்லை` or `இல்ல` ↔ `இல்லை` replacement.

**Strengthened after the scans-256–259 failure:** an apparent baseline difference limited to an old-type vowel sign, same-word letter shape, or line-wrap spacing requires a second independent visual pass before the baseline may be changed. Same-edition comparison should be used when possible. A printed line break alone is not evidence for a word-internal space. If the user challenges a glyph reading, reopen every assistant-origin discrepancy in that batch before proceeding.

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

High-resolution native reinspection established earlier assistant `லை`-loss errors on **23 readable physical scans**. Canonical page records and assembled Tamil were synchronized. The seven physically damaged Part-005 records **215–219 and 223–224** remain `needs-review`.

## Part 006 — active canonical/fidelity stage

Derivative: `TVA_BOK_0064097_புதையல்_part_006_pages_246-294.pdf`

- physical pages mapped: **49 / 49 — scans 246–294 / printed 242–290**
- canonical records created: **18 / 49 — scans 246–263**
- verified: **18**
- needs-review: **0**
- partial: **0**
- not-started: **31 — scans 264–294**
- derivative map: [`indexes/part-006-page-map.md`](indexes/part-006-page-map.md)
- latest native-fidelity record: [`notes/visual-fidelity-scan-263.md`](notes/visual-fidelity-scan-263.md)
- Part-006 Tamil audit: **NOT ELIGIBLE**
- assembled Tamil / English / bilingual review: **NOT ELIGIBLE**
- state: **`in-progress`**

### Current verified joins / transitions

- 245→246: `இருக்கவே` + `இருக்கிறாள் ...`;
- 247→248: `இன்` + `னும்` = `இன்னும்`;
- 248→249: `அவ` + `தாரம்` = `அவதாரம்`;
- 257→258: `வெள்ளியம்` + `பலம்` = `வெள்ளியம்பலம்`;
- 260→261: `வெள்ளியம்பலம்` + `கேட்டு விட்டு, ...`;
- 261→262: `விடிந்த` + `தும்` = `விடிந்ததும்`;
- 262→263: `துக்காராமுக்கோ,` + `ஆனந்தம் தாங்கவில்லை.`.

### Scan 263 / printed 259

Native high-resolution reconciliation against user Iteration 25 establishes:

- baseline `நடந்தவைகளை` → source **`நடந்தவைகள்`**;
- baseline `புதையல் ரகசியத்தைக் கண்டுபிடிப்பதற்காகவே` → source **`புதையலைக் கண்டுபிடிப்பதற்காகவே`**;
- full `மறந்து விடவில்லை` is confirmed on the second old-typeform pass;
- printed line wraps inside `காதலனின்`, `அம்பலத்திடம்`, `பயந்தாள்`, `நோக்க`, `விட்டது`, and `ரகசியம்` are typographic only;
- page endpoint is `அவர்!`.

No unresolved old-type glyph remains through scan 263.

### Structure mapped in Part 006

- chapter 27 closes / chapter 28 begins on scan 247;
- four-star internal transition on scan 251;
- chapter 29 begins scan 254 and closes scan 262;
- chapter 30 begins scan 262;
- chapter 31 begins scan 271;
- chapter 32 begins scan 278;
- chapter 33 begins scan 288 and continues through the derivative endpoint.

Only scans 246–263 are textually verified at this checkpoint; structural inspection does not upgrade scans 264–294.

## Part 005 — completed split checkpoint

- records created: **49 / 49 — scans 197–245**
- verified: **42**
- needs-review: **7 — scans 215–219, 223–224**
- state: **`part-complete` with source-damage qualification**

## Aggregate canonical state

- records created: **263**
- verified: **256**
- needs-review: **7**
- partial: **0**
- clean contiguous fully verified coverage: through scan **214 / printed page 212**
- later individually verified coverage: through scan **263**, except the seven explicitly damaged scans
- Parts 001–005: **part-complete at split level**
- Part 006: **in progress — 18 / 49 verified**
- continuous split-level assembled Tamil / English review: through scan **245** only
- full-source physical coverage from received derivatives: mapped through scan **294**, but canonical text only through scan 263

## Whole-work gate

**NOT ELIGIBLE.** Complete source extent, later scans, true ending/back matter, final Tamil audit and whole-work bilingual review remain open.

## Exact next activity

Reconcile **scan 264 / printed page 260** from user Iteration 25 against native source pixels, continuing chapter 30. Apply the strengthened second-pass old-Tamil-typeform and printed-line-wrap rules to every proposed baseline override. Do not run Part-006 Tamil audit or downstream gates yet.