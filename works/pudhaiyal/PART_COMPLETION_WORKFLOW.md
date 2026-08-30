# Split-PDF part-completion workflow — புதையல்

The split PDFs are **access derivatives of one source edition**, not separate bibliographic works. A split may reach `part-complete`, but whole-work Tamil/English/release gates remain blocked until the complete edition is processed.

## Per-split sequence

1. map represented source scans;
2. create/reconcile canonical `pages/` records;
3. perform native visual/textual fidelity review;
4. resolve or explicitly retain every `needs-review` item;
5. run a part-level Tamil audit;
6. update assembled Tamil from audited canonical pages only;
7. translate the audited material;
8. source-check English against canonical Tamil;
9. run part-level bilingual review;
10. synchronize status before moving to the next split.

A derivative boundary is provenance only. Do not invent word, sentence, paragraph, scene or chapter boundaries from it.

A part Tamil gate normally passes with all pages verified. Where the controlling physical source itself is damaged and stronger witnesses do not exist, the audit may instead record an **explicit source-damage disposition**. Such pages remain `needs-review`; they are never silently promoted to `verified`. Subsequent assembled/English work must preserve that provenance and may not claim whole-work verification from it.

## Completed split checkpoints

- Part 001 — scans **1–49** — **`part-complete`**
- Part 002 — scans **50–98** — **`part-complete`**
- Part 003 — scans **99–147** — **`part-complete`**
- Part 004 — scans **148–196** — **`part-complete`**
- Part 005 — scans **197–245** — **`part-complete` with explicit source-damage qualification**

## Part 005 — durable completion record

Source derivative: `TVA_BOK_0064097_புதையல்_part_005_pages_197-245.pdf`

- split pages / canonical records: **49 / 49 — scans 197–245**
- `verified`: **42**
- `needs-review`: **7 — scans 215–219, 223–224**
- not-started: **0**
- Tamil audit: [`notes/part-005-tamil-audit.md`](notes/part-005-tamil-audit.md) — **`part-tamil-audit-source-damage-closed`**
- assembled Tamil: **completed and part-reviewed**
- controlled English translation: **completed and source-checked**
- bilingual review: [`translations/en/PART_005_REVIEW.md`](translations/en/PART_005_REVIEW.md) — **PASSED WITH SOURCE-DAMAGE QUALIFICATION**
- state: **`part-complete`**

Source-condition exceptions remain permanently explicit unless stronger source evidence becomes available:

- scans **215–219** are affected by repair/tape obstruction, including duplicate printed-page witnesses;
- scans **223–224** have substantial physical tear/loss;
- user baseline is retained where source pixels are hidden, but those scans remain `needs-review`;
- no uncertainty is closed from grammar/context alone.

Structure established:

- chapter 22 closes on scan **205**;
- chapter 23 begins scan **206**, closes scan **214**;
- chapter 24 begins scan **215**, closes scan **225**;
- chapter 25 begins scan **226**, closes scan **235**;
- chapter **26** begins on scan **235**, closes scan **240**;
- chapter **27** begins scan **241** and continues beyond the Part-005 endpoint;
- scan **245 / printed 241** ends mid-sentence at `இருக்கவே`.

## Exact next activity

Obtain / attach the next source split beginning at **scan 246 / printed page 242**. Continue chapter 27 directly from the source after `இருக்கவே`. Do not infer the continuation, and do not treat Part 005's derivative endpoint as a chapter or novel ending.
