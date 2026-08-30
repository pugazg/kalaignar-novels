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

## Active split — Part 006

Source derivative: `TVA_BOK_0064097_புதையல்_part_006_pages_246-294.pdf`

- physical pages / mapped source scans: **49 / 49 — scans 246–294**
- visible printed pages: **242–290**
- derivative map: [`indexes/part-006-page-map.md`](indexes/part-006-page-map.md)
- canonical records: **4 / 49 — scans 246–249**
- verified: **4**
- needs-review: **0**
- not-started: **45 — scans 250–294**
- current native-fidelity record: [`notes/visual-fidelity-scans-246-249.md`](notes/visual-fidelity-scans-246-249.md)
- Tamil audit: **not eligible**
- assembled Tamil: **not eligible**
- controlled English: **not eligible**
- bilingual review: **not eligible**
- state: **`in-progress`**

Mandatory opening continuity is closed from native evidence:

- scan 245 ends `இருக்கவே`;
- scan 246 begins `இருக்கிறாள் பரிமளா, ...`;
- joined reading: `இருக்கவே இருக்கிறாள் பரிமளா, ...`.

Part-006 mapped chapter transitions: chapter 28 begins scan 247; 29 begins 254; 30 begins 262; 31 begins 271; 32 begins 278; 33 begins 288.

Do not run the Part-006 Tamil audit or any downstream stage until all scans 246–294 have canonical records and native-fidelity dispositions.

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

## Exact next activity

Reconcile the next Part-006 transcription batch beginning at **scan 250 / printed page 246** directly against native source pixels. Continue chapter 28 without treating the batch or derivative boundary as a narrative boundary.