# Tamil / split-part audit — புதையல்

Status: **IN PROGRESS — Parts 001–005 part-complete; retrospective old-glyph integrity repair completed; Part 006 canonical/native-fidelity work underway; whole-work gate not eligible**

Source: `TVA_BOK_0064097_புதையல்.pdf`

## Permanent visual-integrity rule

The native scan is the textual authority. Before overriding a user baseline because a final character or vowel mark appears absent, inspect the **whole glyph cluster at high resolution**, explicitly consider old/historical Tamil typeforms, and use more than one useful scale/contrast when a mark is faint. Compare another clear occurrence from the same edition where helpful.

This source has now demonstrated at least two distinct old/faint-vowel hazards:

- final `லை` can resemble bare `ல்` at ordinary zoom;
- scan 264 source `என்னா` has a faint `ா` that was initially missed and falsely shortened to `என்ன`.

The safeguard therefore applies to **every vowel sign / combining mark**, not only final `ை`. A correction requires positive native-pixel evidence. If pixels remain ambiguous, retain the baseline and `needs-review`. Never apply a global spelling or vowel-sign replacement.

**Strengthened after the scans-256–259 and scan-264 failures:** an apparent baseline difference limited to an old-type vowel sign, same-word letter shape, or line-wrap spacing requires a second independent visual pass before the baseline may be changed. Same-edition comparison should be used when possible. A printed line break alone is not evidence for a word-internal space. If the user challenges a glyph reading, reopen every assistant-origin discrepancy in that batch before proceeding.

## Completed part checkpoints

| Part | Source scans | State |
|---|---:|---|
| 001 | 1–49 | part-complete |
| 002 | 50–98 | part-complete |
| 003 | 99–147 | part-complete |
| 004 | 148–196 | part-complete |
| 005 | 197–245 | part-complete with source-damage qualification |

The seven physically damaged Part-005 records **215–219 and 223–224** remain `needs-review`.

## Part 006 — active canonical/fidelity stage

Derivative: `TVA_BOK_0064097_புதையல்_part_006_pages_246-294.pdf`

- physical pages mapped: **49 / 49 — scans 246–294 / printed 242–290**
- canonical records created: **19 / 49 — scans 246–264**
- verified: **19**
- needs-review: **0**
- partial: **0**
- not-started: **30 — scans 265–294**
- derivative map: [`indexes/part-006-page-map.md`](indexes/part-006-page-map.md)
- latest native-fidelity record: [`notes/visual-fidelity-scan-264.md`](notes/visual-fidelity-scan-264.md)
- scan-264 correction record: [`notes/old-glyph-correction-scan-264.md`](notes/old-glyph-correction-scan-264.md)
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

Native high-resolution reconciliation establishes:

- baseline `நடந்தவைகளை` → source `நடந்தவைகள்`;
- baseline `புதையல் ரகசியத்தைக் கண்டுபிடிப்பதற்காகவே` → source `புதையலைக் கண்டுபிடிப்பதற்காகவே`;
- full `மறந்து விடவில்லை` confirmed on second old-typeform pass;
- page endpoint `அவர்!`.

### Scan 264 / printed 260 — corrected after user challenge

Fresh enlarged native inspection establishes:

- user baseline word **`என்னா`** is source-supported;
- earlier assistant `என்ன` is withdrawn; the faint/old `ா` after `ன்ன` had been missed;
- canonical punctuation is **`என்னா — தெரியாது மாதிரி விழிக்கிறே?`**;
- source punctuation also confirms **`தெரியவில்லை — விழித்தாள்!`**, **`சரி — சரி —`**, and **`வந்தேனே......`**;
- printed wraps inside `காரணமும்`, `அவருக்குப்`, `ஆவலோடு`, `புரியவில்லை`, `இல்லையா`, and `வெள்ளியம்பலம்` are typographic only;
- second old-typeform pass confirms complete `புரியவில்லை`, including final `லை`;
- page endpoint `பேசக்கூட விடமாட்டேங்கிறீர்களே!”`.

All assistant-origin discrepancies on scan 264 were reopened after the challenge. No unresolved old-type glyph remains on the page.

### Structure mapped in Part 006

- chapter 27 closes / chapter 28 begins scan 247;
- four-star internal transition scan 251;
- chapter 29 begins scan 254 and closes scan 262;
- chapter 30 begins scan 262;
- chapter 31 begins scan 271;
- chapter 32 begins scan 278;
- chapter 33 begins scan 288 and continues through the derivative endpoint.

Only scans 246–264 are textually verified at this checkpoint; structural inspection does not upgrade scans 265–294.

## Aggregate canonical state

- records created: **264**
- verified: **257**
- needs-review: **7**
- partial: **0**
- clean contiguous fully verified coverage: through scan **214 / printed page 212**
- later individually verified coverage: through scan **264**, except the seven explicitly damaged scans
- Parts 001–005: **part-complete at split level**
- Part 006: **in progress — 19 / 49 verified**
- continuous split-level assembled Tamil / English review: through scan **245** only
- full-source physical coverage from received derivatives: mapped through scan **294**, but canonical text only through scan 264

## Whole-work gate

**NOT ELIGIBLE.** Complete source extent, later scans, true ending/back matter, final Tamil audit and whole-work bilingual review remain open.

## Exact next activity

Reconcile **scan 265 / printed page 261** from user Iteration 25 against native source pixels, continuing chapter 30. Apply the strengthened second-pass old-Tamil-typeform rule to all vowel signs and printed-line-wrap questions. Do not run Part-006 Tamil audit or downstream gates yet.