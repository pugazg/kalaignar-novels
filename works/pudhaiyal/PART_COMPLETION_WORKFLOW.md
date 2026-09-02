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
- state: **`tamil-audit-passed / assembled-tamil-next`**

Structural reconciliation is complete through scan 343. Chapter 36 begins scan 317, Chapter 37 scan 324, Chapter 38 scan 331 and Chapter 39 scan 340. Scan 322 contains a four-star transition and a structure-only reordering of unchanged `விடியற்காலை...` baseline text. Scan 330 contains a four-star transition and the Chapter-37 closing rule. Scan 343 ends open at `அதிர்ஷ்` and is not a true ending.

Tamil audit record: [`notes/part-007-tamil-audit.md`](notes/part-007-tamil-audit.md).

## Gate consequence

Part 007 has passed canonical reconciliation, structural fidelity and Tamil audit. The next gate is the **assembled Tamil reading layer** from scans 295–343. English remains blocked until the assembled-Tamil consistency check passes.

## Exact next activity

Build and consistency-check the **Part-007 assembled Tamil layer**, continuing Chapter 33 across the Part-006 boundary, assembling Chapters 34–39 with all audited joins and transitions, and leaving Chapter 39 open at `அதிர்ஷ்`.