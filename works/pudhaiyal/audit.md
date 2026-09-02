# Tamil / split-part audit — புதையல்

Status: **IN PROGRESS — Parts 001–006 part-complete; Part 007 Tamil audit + assembled-Tamil check PASSED; controlled English next**

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
| 007 | 295–343 | **Tamil audit + assembled-Tamil check PASSED; controlled English pending** |

The seven physically damaged Part-005 records **215–219 and 223–224** remain `needs-review` by explicit source-damage qualification.

## Part 007 — Tamil / assembly result

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
- assembled Tamil coverage: **through scan 343 / printed 339**
- state: **`assembled-tamil-checked / controlled-English-next`**

### Structural findings preserved in assembled Tamil

- Part 006→007: `‘லாக்` + `அப்’பில்` → **`‘லாக் அப்’பில்`**;
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
- scan 343 ends open at `அதிர்ஷ்`, so the derivative is not a chapter/novel ending;
- scan 343 retains baseline `అది` despite native Tamil `அது`, because no source-correction authorization was given for that supplied lexical form.

## Aggregate canonical state

- records created: **343**
- verified / completed: **336**
- needs-review: **7 — only Part 005 scans 215–219, 223–224**
- partial: **0**
- Parts 001–006: **part-complete**
- Part 007: **Tamil audit + assembled-Tamil check PASSED**
- assembled Tamil: part-reviewed continuously through scan **343**
- source-checked / bilingual-reviewed English: through scan **294**
- physically received source coverage: through scan **343 / printed 339**

## Whole-work gate

**NOT ELIGIBLE.** Even after the Part-007 split workflow completes, source beyond scan 343 is still required because the current derivative ends mid-utterance.

## Exact next activity

Perform the **Part-007 controlled English translation and source check for scans 295–343** from the checked assembled Tamil layer. Continue Chapter 33, translate Chapters 34–39 with all source transitions preserved, and leave Chapter 39 open at the final `அதிர்ஷ்` fragment. Bilingual review follows only after the English source check passes.