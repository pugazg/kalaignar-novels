# Split-PDF part-completion workflow — புதையல்

Split PDFs are access derivatives of one source edition. `part-complete` is a split-level state only; whole-work Tamil/English/release gates remain separate.

## Per-split sequence

1. map represented source scans;
2. reconcile canonical `pages/` records;
3. native visual/structural fidelity review;
4. resolve/retain every `needs-review` item;
5. part-level Tamil audit;
6. assembled Tamil from audited canonical pages;
7. controlled English translation;
8. English source check;
9. part-level bilingual review;
10. synchronize status.

## Lexical baseline rule — scan 280 onward

User-supplied Gemini transcription controls lexical wording/forms/spacing. Native scans control headings, paragraph boundaries, punctuation, quotations, physical boundaries, separators, chapter/scene/work-ending structure and back matter.

- Part 007 baseline: `p7.md`; three explicit user-authorized omissions restored.
- Part 008 baseline: `p8.md`; user-authorized scan-384 phrase **`தகட்டில் இருக்கிறபடி`** restored.
- Part 009 baseline: `p9.md`; **no complete lexical omission found**.
- Part 010 baseline: `p10.md`; native scan 445 contains complete word **`விடு`** absent from baseline, currently pending user disposition.

A user-authorized restoration is narrow to the documented omission and does not establish general source-correction authority.

## Split checkpoints

- Parts 001–008 — `part-complete`
- Part 009 — scans **393–441** — **Tamil audit PASSED; assembled Tamil pending**
- Part 010 — scans **442–448** — **canonical 7/7; 6 verified; Tamil audit BLOCKED on scan445 omission**

## Part 009 gate state

- mapping: **PASS — 49 / 49**
- canonical: **PASS — 49 / 49**
- visual/structural fidelity: **PASS**
- needs-review: **0**
- Tamil audit: **PASS** — [`notes/part-009-tamil-audit.md`](notes/part-009-tamil-audit.md)
- assembled Tamil: **PENDING**
- controlled English / downstream gates: **PENDING**

Part 009 continues Chapter 45 across scan392→393 and carries Chapters 45–51 through scan 441. The endpoint `அம்ப` is a physical split only and joins Part010 `லமே` as **`அம்பலமே`**.

## Part 010 gate state

- mapping: **PASS — 7 / 7**
- canonical: **PASS — 7 / 7 represented**
- verified: **6 / 7**
- needs-review: **1 — scan445 / printed441**
- Tamil audit: **BLOCKED** — [`notes/part-010-tamil-audit.md`](notes/part-010-tamil-audit.md)
- assembled Tamil / English: **BLOCKED until Tamil audit passes**

Blocking source/baseline difference:

- native: `தங்கத்திற்குப் பக்கத்திலே புதைத்து விடு!”`
- `p10.md`: `தங்கத்திற்குப் பக்கத்திலே புதைத்து` + closing quote
- omitted complete word: **`விடு`**

Scan **447 / printed443** is the actual novel narrative ending. Scan **448** is separate printer-colophon back matter (`அன்பு அச்சகம், பொறையார்.`).

## Exact next activity

Resolve Part-010 scan-445 **`விடு`**. If the user authorizes restoration, insert it narrowly, rerun Part-010 Tamil audit, then build the assembled Tamil layer continuously from scan **393 through scan 447**, with scan448 retained separately as back matter.
