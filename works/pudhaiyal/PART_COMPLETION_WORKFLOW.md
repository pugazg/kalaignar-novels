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

User-supplied Gemini transcription controls lexical wording/forms/spacing. Native scans control headings, paragraph boundaries, punctuation, quotations, physical line/page breaks, separators and chapter/scene structure.

For Part 007, uploaded `p7.md` is the controlling lexical baseline. The three complete source-confirmed omissions at scans 304, 305 and 315 were restored only after the user's explicit 2026-09-02 instruction `insert all three omissions`. No broader source-correction permission is implied.

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
- verified: **49 / 49**
- Part-007 needs-review: **0**
- not-started: **0**
- Tamil audit: **PASSED**
- assembled Tamil consistency check: **PASSED**
- controlled English source check: **PASSED**
- assembled Tamil: **through scan 343**
- source-checked English: **through scan 343**
- bilingual review: **pending**
- state: **`english-source-checked / bilingual-review-next`**

Structural reconciliation and assembly are complete through scan 343. Chapter 33 continues across the Part-006→007 boundary. Chapter 34 begins scan 297, Chapter 35 scan 307, Chapter 36 scan 317, Chapter 37 scan 324, Chapter 38 scan 331 and Chapter 39 scan 340. Source transitions remain preserved, including the scan-322 structure-only placement of unchanged `விடியற்காலை...` material. Scan 343 ends open at `அதிர்ஷ்`; source-checked English ends correspondingly inside `luc` and does not invent a true ending.

Tamil audit record: [`notes/part-007-tamil-audit.md`](notes/part-007-tamil-audit.md).  
Assembled-Tamil check: [`notes/part-007-assembled-tamil-check.md`](notes/part-007-assembled-tamil-check.md).  
English source check: [`translations/en/PART_007_ENGLISH_CHECK.md`](translations/en/PART_007_ENGLISH_CHECK.md).

## Gate consequence

Part 007 has passed canonical reconciliation, structural fidelity, Tamil audit, assembled-Tamil consistency and controlled-English source checking. The sole remaining split-level gate is the **Part-007 bilingual review**. It must pass before `part-complete` is assigned.

## Exact next activity

Run the **Part-007 bilingual review across scans 295–343**, comparing source-checked English against canonical/assembled Tamil for semantic fidelity, dialogue coverage, names/terms, humour, violence, romance, rhetorical force, internal transitions and the open derivative endpoint. If it passes, mark Part 007 `part-complete`, then move to source beyond scan 343.