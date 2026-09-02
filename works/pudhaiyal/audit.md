# Tamil / split-part audit — புதையல்

Status: **IN PROGRESS — Parts 001–006 part-complete; Part 007 Tamil audit + assembled-Tamil check + controlled-English source check PASSED; bilingual review next**

Source: `TVA_BOK_0064097_புதையல்.pdf`

## Authority rule

Through scan 279, completed records retain earlier source-first decisions. From scan 280 onward, supplied Gemini transcription controls lexical wording/forms/spacing and the native scan controls page identity, headings, punctuation, quotations, paragraphing, physical boundaries, separators and chapter/scene structure.

For Part 007, uploaded `p7.md` is the controlling lexical baseline. The three complete omissions identified during reconciliation were restored only after explicit user instruction `insert all three omissions` on 2026-09-02:

- scan 304 — `நீ`;
- scan 305 — `என்ன`;
- scan 315 — `சரி...... வா! வா!......`.

This does not authorize source-correction of any other supplied lexical difference.

## Completed part checkpoints

| Part | Source scans | State |
|---|---:|---|
| 001 | 1–49 | part-complete |
| 002 | 50–98 | part-complete |
| 003 | 99–147 | part-complete |
| 004 | 148–196 | part-complete |
| 005 | 197–245 | part-complete with source-damage qualification |
| 006 | 246–294 | part-complete |
| 007 | 295–343 | **Tamil audit + assembled-Tamil check + controlled-English source check PASSED; bilingual review pending** |

The seven physically damaged Part-005 records **215–219 and 223–224** remain `needs-review` by explicit source-damage qualification.

## Part 007 — current split result

Derivative: `TVA_BOK_0064097_புதையல்_part_007_pages_295-343.pdf`

- mapped physical pages: **49 / 49 — scans 295–343 / printed 291–339**
- derivative SHA-256: `9ead2089eb238273f7b0fd0dbe2f929095730fbf3fc218719e66fe0d472bb15c`
- lexical baseline: uploaded `p7.md`, SHA-256 `a804b914b88050ca8d31142cb00d7491c94e89ff1fb7e564fdd348bdf14b1c59`
- canonical records: **49 / 49**
- verified / structurally completed: **49 / 49**
- Part-007 needs-review: **0**
- not-started: **0**
- Tamil audit: **PASSED** — [`notes/part-007-tamil-audit.md`](notes/part-007-tamil-audit.md)
- assembled Tamil consistency check: **PASSED** — [`notes/part-007-assembled-tamil-check.md`](notes/part-007-assembled-tamil-check.md)
- controlled English source check: **PASSED** — [`translations/en/PART_007_ENGLISH_CHECK.md`](translations/en/PART_007_ENGLISH_CHECK.md)
- assembled Tamil coverage: **through scan 343 / printed 339**
- source-checked English coverage: **through scan 343 / printed 339**
- bilingual review: **pending**
- state: **`english-source-checked / bilingual-review-next`**

### Structural / translation findings through scan 343

- Part 006→007: `‘லாக்` + `அப்’பில்` → **`‘லாக் அப்’பில்`**, continuously translated as **lock-up**;
- chapter 34 opens scan 297;
- chapter 35 opens scan 307;
- chapter 36 opens scan 317;
- scan 319 contains a four-star memory transition;
- scan 322 contains another native four-star transition; unchanged `விடியற்காலை...` baseline text remains structurally repositioned after the overnight dialogue;
- chapter 37 opens scan 324;
- scan 326 contains a four-star internal transition;
- scan 330 contains a four-star internal transition and closes chapter 37 at the foot rule;
- chapter 38 opens scan 331;
- chapter 39 opens scan 340;
- scan 343 ends open at `அதிர்ஷ்`; source-checked English ends correspondingly inside `luc`;
- scan 343 retains baseline `అది` despite native Tamil `அது`; English renders contextual sense without changing Tamil.

The English source check also records controlled handling of source-specific terms and two English-layer corrections: Chapter 38 **“Of this house!”** and the Chapter-39 Saibu alms recipient.

## Aggregate canonical state

- records created: **343**
- verified / completed: **336**
- needs-review: **7 — only Part 005 scans 215–219, 223–224**
- partial: **0**
- Parts 001–006: **part-complete**
- Part 007: **English source check PASSED; bilingual review pending**
- assembled Tamil: part-reviewed continuously through scan **343**
- source-checked English: continuously through scan **343**
- bilingual-reviewed English: through scan **294**
- physically received source coverage: through scan **343 / printed 339**

## Whole-work gate

**NOT ELIGIBLE.** Even after the Part-007 split workflow completes, source beyond scan 343 is still required because the current derivative ends mid-utterance.

## Exact next activity

Run the **Part-007 bilingual review across scans 295–343**. Part 007 may become `part-complete` only after that review passes.