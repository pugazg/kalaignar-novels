# Tamil / split-part audit — புதையல்

Status: **IN PROGRESS — Parts 001–006 part-complete; Part 007 canonical-complete; lexical-omission disposition required before Tamil audit**

Source: `TVA_BOK_0064097_புதையல்.pdf`

## Authority rule

Through scan 279, completed records retain earlier source-first decisions. From scan 280 onward, supplied Gemini transcription controls lexical wording/forms/spacing and the native scan controls page identity, headings, punctuation, quotations, paragraphing, physical boundaries, separators and chapter/scene structure. A complete baseline omission is flagged rather than silently source-filled.

For Part 007, uploaded `p7.md` is the controlling lexical baseline.

## Completed part checkpoints

| Part | Source scans | State |
|---|---:|---|
| 001 | 1–49 | part-complete |
| 002 | 50–98 | part-complete |
| 003 | 99–147 | part-complete |
| 004 | 148–196 | part-complete |
| 005 | 197–245 | part-complete with source-damage qualification |
| 006 | 246–294 | part-complete |

The seven physically damaged Part-005 records **215–219 and 223–224** remain `needs-review` by explicit source-damage qualification.

## Part 007 — canonical-complete checkpoint

Derivative: `TVA_BOK_0064097_புதையல்_part_007_pages_295-343.pdf`

- mapped physical pages: **49 / 49 — scans 295–343 / printed 291–339**
- derivative SHA-256: `9ead2089eb238273f7b0fd0dbe2f929095730fbf3fc218719e66fe0d472bb15c`
- lexical baseline: uploaded `p7.md`, SHA-256 `a804b914b88050ca8d31142cb00d7491c94e89ff1fb7e564fdd348bdf14b1c59`
- canonical records: **49 / 49**
- verified / structurally completed: **46 / 49**
- needs-review: **3 — scans 304, 305, 315**
- not-started: **0**
- state: **`canonical-complete / lexical-omission-disposition-pending`**
- Part-007 Tamil audit: **BLOCKED ONLY BY THE THREE EXPLICIT OMISSION DISPOSITIONS**

The unresolved Part-007 baseline omissions are:

- scan 304 — native `நீ` omitted by `p7.md`;
- scan 305 — native `என்ன` omitted by `p7.md`;
- scan 315 — native `சரி...... வா! வா!......` omitted by `p7.md`.

None has been source-inserted.

### Structural findings now complete through scan 343

- Part 006→007: `‘லாக்` + `அப்’பில்` → **`‘லாக் அப்’பில்`**;
- chapter 34 opens scan 297;
- chapter 35 opens scan 307;
- chapter 36 opens scan 317;
- scan 322 contains a native four-star transition; the supplied `விடியற்காலை...` span was structurally repositioned after the overnight dialogue without lexical change;
- chapter 37 opens scan 324;
- scan 330 contains a four-star internal transition and closes chapter 37 at the foot rule;
- chapter 38 opens scan 331;
- chapter 39 opens scan 340;
- scan 343 ends open at `அதிர்ஷ்`, so the derivative is not a chapter/novel ending;
- scan 343 retains baseline `అది` despite native Tamil `அது`, because it is a supplied lexical discrepancy rather than a baseline omission.

Latest fidelity record: [`notes/visual-fidelity-scans-318-343.md`](notes/visual-fidelity-scans-318-343.md).

## Aggregate canonical state

- records created: **343**
- verified / completed: **333**
- needs-review: **10 — Part 005 scans 215–219, 223–224; Part 007 scans 304, 305, 315**
- partial: **0**
- Parts 001–006: **part-complete**
- Part 007: **canonical-complete, audit pending omission disposition**
- assembled Tamil: part-reviewed through scan **294**
- source-checked / bilingual-reviewed English: through scan **294**
- physically received source coverage: through scan **343 / printed 339**

## Whole-work gate

**NOT ELIGIBLE.** Even after Part-007 split workflow completes, source beyond scan 343 is still required because the current derivative ends mid-utterance.

## Exact next activity

Explicitly disposition the three Part-007 baseline omissions at scans **304, 305 and 315**. Once they are resolved or explicitly accepted as qualified omissions, run the **Part-007 Tamil audit across scans 295–343**. Do not begin Part-007 assembled Tamil or English before that audit passes.