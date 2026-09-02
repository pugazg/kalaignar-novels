# Split-PDF part-completion workflow — புதையல்

The split PDFs are **access derivatives of one source edition**, not separate bibliographic works. A split may reach `part-complete`, but whole-work Tamil/English/release gates remain blocked until the complete edition is processed.

## Per-split sequence

1. map represented source scans;
2. create/reconcile canonical `pages/` records;
3. perform native visual/structural fidelity review;
4. resolve or explicitly retain every `needs-review` item;
5. run a part-level Tamil audit;
6. update assembled Tamil from audited canonical pages only;
7. translate the audited material;
8. source-check English against canonical Tamil;
9. run part-level bilingual review;
10. synchronize status before moving to the next split.

A derivative boundary is provenance only.

## Lexical baseline rule — scan 280 onward

User-supplied Gemini transcription controls lexical wording/forms/spacing. Native scans control headings, paragraph boundaries, punctuation, quotations, physical line/page breaks, separators and chapter/scene structure. Complete supplied-baseline omissions must be flagged rather than silently source-filled.

For Part 007, uploaded `p7.md` is the controlling lexical baseline.

## Completed split checkpoints

- Part 001 — scans **1–49** — `part-complete`
- Part 002 — scans **50–98** — `part-complete`
- Part 003 — scans **99–147** — `part-complete`
- Part 004 — scans **148–196** — `part-complete`
- Part 005 — scans **197–245** — `part-complete` with source-damage qualification
- Part 006 — scans **246–294** — `part-complete`

## Active split — Part 007

- source scans: **295–343**
- printed pages: **291–339**
- canonical records: **49 / 49**
- verified: **46 / 49**
- needs-review: **3 — scans 304, 305, 315**
- not-started: **0**
- state: **`canonical-complete / lexical-omission-disposition-pending`**
- Tamil audit: **blocked pending explicit disposition of those three omissions**

Unresolved baseline omissions:

- scan 304 — `நீ`;
- scan 305 — `என்ன`;
- scan 315 — `சரி...... வா! வா!......`.

No omitted source word/span has been silently inserted.

Structural reconciliation is complete through scan 343. Chapter 36 begins scan 317, Chapter 37 scan 324, Chapter 38 scan 331 and Chapter 39 scan 340. Scan 322 contains a four-star transition and a structure-only reordering of the unchanged `விடியற்காலை...` span. Scan 330 contains a four-star transition and Chapter-37 closing rule. Scan 343 ends open at `அதிர்ஷ்` and is not a true ending.

## Gate consequence

The canonical and native-structure stages for Part 007 are complete. The **only remaining prerequisite for the Part-007 Tamil audit** is explicit disposition of scans 304, 305 and 315. Once disposition is durable, run the Tamil audit across scans 295–343. Assembled Tamil and English remain blocked until that audit passes.

## Exact next activity

Record explicit disposition for scans **304, 305 and 315**, update those canonical/status records accordingly, then run the **Part-007 Tamil audit**.