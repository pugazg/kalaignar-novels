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

## Completed split checkpoints

- Part 001 — scans **1–49** — **`part-complete`**
- Part 002 — scans **50–98** — **`part-complete`**
- Part 003 — scans **99–147** — **`part-complete`**
- Part 004 — scans **148–196** — **`part-complete`**

## Part 005 — scans 197–245

Source derivative: `TVA_BOK_0064097_புதையல்_part_005_pages_197-245.pdf`

Current state:

- split pages: **49**
- canonical records created: **20 — scans 197–216**
- `verified`: **18 — scans 197–214**
- `needs-review`: **2 — scans 215–216**
- not-started: **29 — scans 217–245**
- fidelity: [`notes/visual-fidelity-scans-197-216.md`](notes/visual-fidelity-scans-197-216.md)
- derivative map: [`indexes/part-005-page-map.md`](indexes/part-005-page-map.md)
- Tamil audit: **not yet eligible**
- assembled Tamil / English: **not started for Part 005**
- state: **in progress**

Structure established so far:

- chapter 22 continues from Part 004 through scans **197–205** and closes on scan 205;
- chapter **23** begins on scan **206** and closes on scan **214**;
- chapter **24** begins on scan **215**.

Source-condition exception:

- scans **215 / printed 213** and **216 / printed 214** are crossed by a broad repair/tape strip that hides letter sequences;
- user baseline is retained on those pages, but they remain `needs-review` because hidden characters cannot be certified from native pixels;
- the derivative contains a later duplicate physical scan of printed page 214 (with adjacent repeated material). Treat every repeated scan as distinct provenance and use it only as an alternate source witness if it actually exposes additional letters.

## Exact next source activity

First test the later duplicate witness(es) against scans 215–216. Resolve only letters genuinely exposed by source pixels. Otherwise retain `needs-review`. Then continue from **scan 217 / printed page 215**.

Do not begin Part-005 assembled Tamil or English until all 49 scans are canonically resolved/verified and the Part-005 Tamil audit passes.
