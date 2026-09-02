# Source page-count reconciliation — புதையல்

Date opened: 2026-08-25  
Last updated: 2026-09-02

## Why this note exists

The first onboarding pass incorrectly treated scans **1–150** as the complete PDF. That conclusion is permanently withdrawn.

Tamil Digital Library describes source identity `TVA_BOK_0064097` as **443 p.**. The repository therefore distinguishes bibliographic printed extent from actually received source-scan coverage.

Current received derivative coverage now reaches:

- source scans **1–343**;
- visible printed text through page **339**;
- canonical records currently created through scan **297**;
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
   - canonical / verified: **3 / 49 — scans 295–297**
   - source intake: [`part-007-source-intake.md`](part-007-source-intake.md)
   - page map: [`../indexes/part-007-page-map.md`](../indexes/part-007-page-map.md)

No split PDF or uploaded baseline file is committed to GitHub.

## Part-006 → Part-007 boundary now resolved

Part 006 ended at scan **294 / printed 290** with open `‘லாக்`.

Part-007 scan **295 / printed 291** physically begins `அப்’பில் தானிருக்கிறார்கள்...`.

Therefore the cross-part term is conclusively:

**`‘லாக் அப்’பில்`**

This derivative boundary is provenance only, not a sentence/scene/chapter boundary.

## Part-007 structural state through scan 297

- scan 295 — chapter 33 continues; four-star internal transition at page foot;
- scan 296 — chapter 33 continues after that transition;
- scan 297 — chapter 33 closes; horizontal rule + heading 34; chapter 34 begins;
- scan 297 ends mid-sentence at `அவனை அனுதாபத்தோடு`;
- scan 298 is the next canonical reconciliation target.

A native endpoint spot-check of scan **343 / printed 339** shows the text ending mid-utterance at `அதிர்ஷ்`. The `p7.md` lexical baseline ends its source transcription at the same fragment. Therefore Part 007 is another open derivative boundary and cannot be treated as the novel ending.

## Current textual / derivative state

- canonical page records created: **297**
- verified / completed: **290**
- needs-review: **7 — Part 005 scans 215–219, 223–224**
- partial: **0**
- clean contiguous fully verified range: **1–214**
- later completed pages: through scan **297**, except the seven damaged Part-005 records
- Parts 001–006: **part-complete at split level**
- Part 007: **canonical-in-progress; 46 scans remain**
- assembled Tamil: **part-reviewed through scan 294**
- source-checked / bilingual-reviewed English: **through scan 294**
- source scans physically represented by received derivatives: **through scan 343**
- full-source manifest: **still incomplete beyond scan 343**

## Full-source extent track

Still required:

1. complete Part-007 canonical/structural reconciliation for scans 298–343;
2. run Part-007 Tamil audit, assembled Tamil check, English source check and bilingual review;
3. obtain source beyond scan 343 and verify continuation from the open `அதிர்ஷ்` fragment;
4. process every later source scan;
5. identify true final text / back matter / closing leaves;
6. determine exact original PDF scan/page-object count;
7. calculate the exact original full-source SHA-256 when byte-level access is available;
8. only after complete-source coverage, run final whole-work Tamil and bilingual audits and release-readiness checks.

Do not infer final source extent or ending from the TDL printed-page count or from the repeated 49-page derivative sizes.

## Exact next activity

Process **scan 298 / printed 294** from `p7.md` plus native Part-007 page 4, preserving the chapter-34 sentence continuation from scan 297. Continue sequentially through the derivative.