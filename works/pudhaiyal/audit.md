# Tamil / split-part audit — புதையல்

Status: **IN PROGRESS — Parts 001–006 part-complete; Part 007 canonical reconciliation active through scan 312; whole-work gate not eligible**

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
- canonical records: **18 / 49 — scans 295–312**
- verified / structurally completed: **16 / 49**
- needs-review: **2 — scans 304–305**
- not-started: **31 — scans 313–343**
- Part-007 Tamil audit: **NOT YET ELIGIBLE**
- Part-007 state: **`canonical-in-progress`**

### Verified continuity / structure through scan 312

- scan 294 `‘லாக்` + scan 295 `அப்’பில்` = **`‘லாக் அப்’பில்`**, proving Part-006→007 continuity inside the same Sub-Inspector dialogue;
- scan 295 ends with a source-printed four-star internal transition;
- scan 297 closes chapter 33 and begins chapter 34 under a horizontal rule + heading `34`;
- scan 302→303 physically establishes `பெற்` + `றான்` → `பெற்றான்`;
- scan 304 has one complete baseline lexical omission: native source visibly prints `நீ` in `“நீ?……”`, while `p7.md` does not. The word has not been source-inserted;
- scan 305 has one complete baseline lexical omission: native source visibly prints `என்ன` after `ஒப்புக் கொள்ளா விட்டால்...`, while `p7.md` omits it. The word has not been source-inserted;
- scan 306 closes chapter 34 with a source-printed horizontal rule;
- scan 307 begins chapter 35 under heading `35`;
- scan 307→308 preserves `அவனை ஆட்டி வைத்த ‘மிருகம்’` → `பதுங்கி விட்டது.`;
- scan 308→309 preserves `வாழ்க்கைக்` → `காவியத்தை...`;
- scan 309→310 preserves `...படாமல் இந்த` → `ஊரை விட்டு...`;
- scan 310 contains a source-printed four-star internal transition and ends at physical `போவ`;
- scan 311 begins `தென்று`, completing `போவதென்று`, and ends `பேசிக் கொண்டிருந்து`;
- scan 312 begins `விட்டு,`; no new complete baseline lexical omissions were found on scans 308–312;
- the Part-007 endpoint spot-check at scan 343 / printed 339 ends at `அதிர்ஷ்`, still mid-utterance, so no chapter/novel ending may be inferred.

Latest fidelity record: [`notes/visual-fidelity-scans-308-312.md`](notes/visual-fidelity-scans-308-312.md).

## Aggregate canonical state

- records created: **312**
- verified / completed: **303**
- needs-review: **9 — Part 005 scans 215–219, 223–224; Part 007 scans 304–305**
- partial: **0**
- clean contiguous fully verified coverage: through scan **214 / printed page 212**
- later completed coverage: through scan **312**, except the nine `needs-review` records above
- Parts 001–006: **part-complete at split level**
- Part 007: **canonical reconciliation active through scan 312**
- assembled Tamil remains part-reviewed through scan **294**
- source-checked / bilingual-reviewed English remains continuous through scan **294**
- physically received source derivative coverage: through scan **343 / printed 339**

## Whole-work gate

**NOT ELIGIBLE.** Part 007 still requires complete canonical reconciliation, explicit disposition of the two baseline omissions at scans 304–305, Tamil audit, assembly, English source check and bilingual review. Source beyond scan 343 is also still required because the current derivative ends mid-utterance.

## Exact next activity

Process **scan 313 / printed 309** under the `p7.md` lexical/native-structure rule and continue sequentially through scans 313–343. Do not pass the Part-007 Tamil audit while scans 304–305 remain unresolved `needs-review` lexical omissions.