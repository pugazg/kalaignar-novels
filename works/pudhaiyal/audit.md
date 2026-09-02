# Tamil / split-part audit — புதையல்

Status: **IN PROGRESS — Parts 001–006 part-complete; Part 007 canonical reconciliation active through scan 317; whole-work gate not eligible**

Source: `TVA_BOK_0064097_புதையல்.pdf`

## Authority rule

Through scan 279, completed records retain the earlier source-first reconciliation decisions.

### Scan 280 onward — supplied lexical / native structural rule

By explicit user instruction:

- supplied Gemini transcription controls **words, spelling, suffixes, lexical forms, lexical wording and supplied lexical spacing**;
- native scan controls **headings, punctuation, quotation marks, long dashes, speaker-label spacing, paragraph structure, physical line/page breaks, separators, chapter/scene transitions and other structural findings**;
- do not override a supplied word from native visual reading;
- if the supplied baseline omits a lexical span, flag it rather than silently supplying source words.

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

## Part 007 — active canonical checkpoint

Derivative: `TVA_BOK_0064097_புதையல்_part_007_pages_295-343.pdf`

- physical pages mapped: **49 / 49 — scans 295–343 / printed 291–339**
- derivative SHA-256: `9ead2089eb238273f7b0fd0dbe2f929095730fbf3fc218719e66fe0d472bb15c`
- lexical baseline: uploaded `p7.md`, SHA-256 `a804b914b88050ca8d31142cb00d7491c94e89ff1fb7e564fdd348bdf14b1c59`
- source intake: [`notes/part-007-source-intake.md`](notes/part-007-source-intake.md)
- page map: [`indexes/part-007-page-map.md`](indexes/part-007-page-map.md)
- canonical records: **23 / 49 — scans 295–317**
- verified / structurally completed: **20 / 49**
- needs-review: **3 — scans 304–305, 315**
- not-started: **26 — scans 318–343**
- Part-007 Tamil audit: **NOT YET ELIGIBLE**
- Part-007 state: **`canonical-in-progress`**

### Verified continuity / structure through scan 317

- scan 294 `‘லாக்` + scan 295 `அப்’பில்` = **`‘லாக் அப்’பில்`**;
- scan 297 closes chapter 33 and begins chapter 34 under a horizontal rule + heading `34`;
- scan 302→303 physically establishes `பெற்` + `றான்` → `பெற்றான்`;
- scans 304–305 remain unresolved baseline lexical omissions (`நீ`, `என்ன`) with no source insertion;
- scan 306 closes chapter 34 with a source-printed horizontal rule;
- scan 307 begins chapter 35 under heading `35`;
- scan 310 contains a source-printed four-star internal transition;
- scan 313→314 continues `தன் படுக்கையைத்` → `திண்ணையிலே விரித்துக் கொண்டான்...`;
- scan 315 has a third complete baseline lexical omission: native source visibly prints `சரி...... வா! வா!......` inside the opening quotation, but `p7.md` omits that span. It was not inserted and scan 315 remains `needs-review`;
- scan 315→316 physically establishes `அவர்` + `கள்` → `அவர்கள்`;
- scan 316→317 continues `“அகப்பட்டுக் கொண்டோம்!”` → `என்ற ஏக்கத்தோடு...`;
- scan 317 closes chapter 35, prints a horizontal rule + heading **36**, and begins chapter 36; its endpoint `பரிமளா பங்களாவிலே` remains open into scan 318;
- the Part-007 endpoint spot-check at scan 343 / printed 339 ends at `அதிர்ஷ்`, still mid-utterance, so no chapter/novel ending may be inferred.

Latest fidelity record: [`notes/visual-fidelity-scans-313-317.md`](notes/visual-fidelity-scans-313-317.md).

## Aggregate canonical state

- records created: **317**
- verified / completed: **307**
- needs-review: **10 — Part 005 scans 215–219, 223–224; Part 007 scans 304–305, 315**
- partial: **0**
- clean contiguous fully verified coverage: through scan **214 / printed page 212**
- later completed coverage: through scan **317**, except the ten `needs-review` records above
- Parts 001–006: **part-complete at split level**
- Part 007: **canonical reconciliation active through scan 317**
- assembled Tamil remains part-reviewed through scan **294**
- source-checked / bilingual-reviewed English remains continuous through scan **294**
- physically received source derivative coverage: through scan **343 / printed 339**

## Whole-work gate

**NOT ELIGIBLE.** Part 007 still requires canonical reconciliation through scan 343, explicit disposition of the three baseline omissions at scans 304–305 and 315, Tamil audit, assembly, English source check and bilingual review. Source beyond scan 343 is also still required because the current derivative ends mid-utterance.

## Exact next activity

Process **scan 318 / printed 314**, chapter 36, under the `p7.md` lexical/native-structure rule. Verify `பரிமளா பங்களாவிலே` → `இருந்ததால் புலனாகிவிட்டது...`, then continue sequentially through scans 318–343. Do not pass the Part-007 Tamil audit while scans 304–305 and 315 remain unresolved `needs-review` lexical omissions.