# Source page-count reconciliation — புதையல்

Date opened: 2026-08-25  
Last updated: 2026-09-02

## Why this note exists

The first onboarding pass incorrectly treated scans **1–150** as the complete PDF. That conclusion is permanently withdrawn.

Tamil Digital Library describes source identity `TVA_BOK_0064097` as **443 p.**. The repository therefore distinguishes bibliographic printed extent from actually received source-scan coverage.

Current received derivative coverage now reaches:

- source scans **1–343**;
- visible printed text through page **339**;
- canonical records currently created through scan **307**;
- exact original PDF scan/page-object count: **still pending**.

## Authority distinction from scan 280 onward

By explicit user instruction:

- supplied Gemini transcription controls words/spellings/suffixes/lexical forms/wording/supplied lexical spacing;
- native scan controls headings, punctuation, quotation marks, long dashes, paragraph/speaker spacing, physical line/page breaks, separators and chapter/scene structure;
- native visual reading must not override supplied lexical text;
- a supplied lexical omission must be flagged rather than silently filled from source pixels.

For Part 007, uploaded `p7.md` is the controlling lexical baseline.

## Split-source workaround

Received access derivatives:

1. Part 001 — scans **1–49** — **part-complete**
2. Part 002 — scans **50–98** — **part-complete**
3. Part 003 — scans **99–147** — **part-complete**
4. Part 004 — scans **148–196** — **part-complete**
5. Part 005 — scans **197–245** — **part-complete with explicit source-damage qualification**
6. Part 006 — scans **246–294 / printed 242–290** — **full split workflow PASSED / part-complete**
7. Part 007 — scans **295–343 / printed 291–339** — **ACTIVE**
   - physical pages mapped: **49 / 49**
   - derivative file size: **57,055,891 bytes**
   - derivative SHA-256: `9ead2089eb238273f7b0fd0dbe2f929095730fbf3fc218719e66fe0d472bb15c`
   - lexical baseline: uploaded `p7.md`, SHA-256 `a804b914b88050ca8d31142cb00d7491c94e89ff1fb7e564fdd348bdf14b1c59`
   - canonical: **13 / 49 — scans 295–307**
   - verified: **11 / 49**
   - needs-review: **2 — scans 304–305**
   - source intake: [`part-007-source-intake.md`](part-007-source-intake.md)
   - page map: [`../indexes/part-007-page-map.md`](../indexes/part-007-page-map.md)

No split PDF or uploaded baseline file is committed to GitHub.

## Part-006 → Part-007 boundary now resolved

Part 006 ended at scan **294 / printed 290** with open `‘லாக்`.

Part-007 scan **295 / printed 291** physically begins `அப்’பில் தானிருக்கிறார்கள்...`.

Therefore the cross-part term is conclusively **`‘லாக் அப்’பில்`**. This derivative boundary is provenance only, not a sentence/scene/chapter boundary.

## Part-007 structural state through scan 307

- scan 295 — chapter 33 continues; four-star internal transition at page foot;
- scan 296 — chapter 33 continues after that transition;
- scan 297 — chapter 33 closes; horizontal rule + heading 34; chapter 34 begins;
- scan 297→298 — `அவனை அனுதாபத்தோடு` continues as `தொட்டுத் தூக்கிடும் போதும்...`;
- scan 302→303 — physical `பெற்` + `றான்` establishes baseline word `பெற்றான்`;
- scan 304 — baseline omits source-visible complete lexical word `நீ`; canonical status `needs-review`, no source insertion;
- scan 305 — baseline omits source-visible complete lexical word `என்ன`; canonical status `needs-review`, no source insertion;
- scan 306 — chapter 34 closes with a horizontal rule;
- scan 307 — chapter 35 begins under heading `35`; page ends open after `அவனை ஆட்டி வைத்த ‘மிருகம்’`.

A native endpoint spot-check of scan **343 / printed 339** shows the text ending mid-utterance at `அதிர்ஷ்`. The `p7.md` lexical baseline ends its source transcription at the same fragment. Therefore Part 007 is another open derivative boundary and cannot be treated as the novel ending.

## Current textual / derivative state

- canonical page records created: **307**
- verified / completed: **298**
- needs-review: **9 — Part 005 scans 215–219, 223–224; Part 007 scans 304–305**
- partial: **0**
- clean contiguous fully verified range: **1–214**
- later completed pages: through scan **307**, except the nine `needs-review` records
- Parts 001–006: **part-complete at split level**
- Part 007: **canonical-in-progress; 36 scans remain**
- assembled Tamil: **part-reviewed through scan 294**
- source-checked / bilingual-reviewed English: **through scan 294**
- source scans physically represented by received derivatives: **through scan 343**
- full-source manifest: **still incomplete beyond scan 343**

## Full-source extent track

Still required:

1. complete Part-007 canonical/structural reconciliation for scans 308–343;
2. explicitly resolve/disposition Part-007 baseline omissions at scans 304–305;
3. run Part-007 Tamil audit, assembled Tamil check, English source check and bilingual review;
4. obtain source beyond scan 343 and verify continuation from the open `அதிர்ஷ்` fragment;
5. process every later source scan;
6. identify true final text / back matter / closing leaves;
7. determine exact original PDF scan/page-object count;
8. calculate the exact original full-source SHA-256 when byte-level access is available;
9. only after complete-source coverage, run final whole-work Tamil and bilingual audits and release-readiness checks.

Do not infer final source extent or ending from the TDL printed-page count or from the repeated 49-page derivative sizes.

## Exact next activity

Process **scan 308 / printed 304** from `p7.md` plus native Part-007 page 14, verifying `‘மிருகம்’` → `பதுங்கி விட்டது...`. Continue sequentially through the derivative.