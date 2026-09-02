# Source page-count reconciliation — புதையல்

Date opened: 2026-08-25  
Last updated: 2026-09-02

## Why this note exists

The first onboarding pass incorrectly treated scans **1–150** as the complete PDF. That conclusion is permanently withdrawn.

Tamil Digital Library describes source identity `TVA_BOK_0064097` as **443 p.**. Bibliographic printed extent is therefore tracked separately from actually received source-scan coverage.

Current received derivative coverage:

- source scans **1–343**
- visible printed text through page **339**
- canonical records through scan **343**
- exact original PDF scan/page-object count: **still pending**

## Authority distinction from scan 280 onward

Supplied Gemini transcription controls lexical wording/forms/spacing; native scans control headings, punctuation, quotations, paragraphing, physical boundaries, separators and chapter/scene structure. Supplied lexical omissions are flagged rather than silently source-filled. For Part 007, uploaded `p7.md` is controlling.

## Split-source state

1. Part 001 — scans **1–49** — part-complete
2. Part 002 — scans **50–98** — part-complete
3. Part 003 — scans **99–147** — part-complete
4. Part 004 — scans **148–196** — part-complete
5. Part 005 — scans **197–245** — part-complete with source-damage qualification
6. Part 006 — scans **246–294 / printed 242–290** — part-complete
7. Part 007 — scans **295–343 / printed 291–339** — **canonical-complete**
   - canonical: **49 / 49**
   - verified: **46 / 49**
   - needs-review: **3 — scans 304, 305, 315**
   - not-started: **0**

Part-006→007 continuity is conclusively `‘லாக்` + `அப்’பில்` → **`‘லாக் அப்’பில்`**.

## Part-007 structural result

- chapter 34 opens scan 297
- chapter 35 opens scan 307
- chapter 36 opens scan 317
- scan 322 contains a four-star transition and a structure-only repositioning of unchanged `விடியற்காலை...` material
- chapter 37 opens scan 324
- scan 330 contains a four-star transition and Chapter-37 closing rule
- chapter 38 opens scan 331
- chapter 39 opens scan 340
- scan 343 ends open at `அதிர்ஷ்`, so Part 007 is not a true ending

The three Part-007 complete-baseline omissions remain scan 304 `நீ`, scan 305 `என்ன`, and scan 315 `சரி...... வா! வா!......`. None was silently inserted.

Scan 343 also retains supplied lexical `అది` despite native Tamil `அது`, in accordance with the lexical-authority rule.

## Current textual / derivative state

- canonical records: **343**
- verified/completed: **333**
- needs-review: **10 — Part 005 scans 215–219, 223–224; Part 007 scans 304, 305, 315**
- partial: **0**
- Parts 001–006: **part-complete**
- Part 007: **canonical-complete; Tamil audit pending omission disposition**
- assembled Tamil: **through scan 294**
- source-checked / bilingual-reviewed English: **through scan 294**
- physically represented source coverage: **through scan 343 / printed 339**
- full-source manifest: **incomplete beyond scan 343**

## Full-source extent track

Still required:

1. explicitly disposition Part-007 omissions 304, 305, 315;
2. run Part-007 Tamil audit, assembled-Tamil check, English source check and bilingual review;
3. obtain source beyond scan 343 and verify continuation from open `அதிர்ஷ்`;
4. process all later source scans and true ending/back matter;
5. determine exact original PDF scan/page-object count and SHA-256;
6. only after complete-source coverage, run final whole-work Tamil/bilingual/release audits.

Do not infer final source extent or ending from the TDL printed-page count or repeated derivative sizes.

## Exact next activity

Explicitly disposition scans **304, 305 and 315**, then run the **Part-007 Tamil audit across scans 295–343**.