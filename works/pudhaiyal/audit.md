# Tamil / split-part audit — புதையல்

Status: **IN PROGRESS — Parts 001–005 part-complete; Part 006 Tamil audit PASSED; assembled Tamil pending; whole-work gate not eligible**

Source: `TVA_BOK_0064097_புதையல்.pdf`

## Authority rule

Through scan 279, the completed records retain the earlier source-first reconciliation decisions.

### Scan 280 onward — Gemini lexical / native structural rule

By explicit user instruction:

- Gemini controls **words, spelling, suffixes, lexical forms, lexical wording and supplied lexical spacing**;
- native scan controls **headings, punctuation, quotation marks, long dashes, speaker-label spacing, paragraph structure, physical line/page breaks, separators, chapter/scene transitions and other structural findings**;
- do not override a Gemini word from native visual reading;
- if Gemini omits a lexical span, flag it rather than silently supplying source words;
- this rule is prospective from scan 280 and does not reopen scans 246–279.

## Completed part checkpoints

| Part | Source scans | State |
|---|---:|---|
| 001 | 1–49 | part-complete |
| 002 | 50–98 | part-complete |
| 003 | 99–147 | part-complete |
| 004 | 148–196 | part-complete |
| 005 | 197–245 | part-complete with source-damage qualification |

The seven physically damaged Part-005 records **215–219 and 223–224** remain `needs-review` by explicit source-damage qualification.

## Part 006 — Tamil-audit checkpoint

Derivative: `TVA_BOK_0064097_புதையல்_part_006_pages_246-294.pdf`

- physical pages mapped: **49 / 49 — scans 246–294 / printed 242–290**
- canonical records created: **49 / 49**
- verified / structurally completed: **49 / 49**
- needs-review: **0**
- partial: **0**
- not-started: **0**
- derivative map: [`indexes/part-006-page-map.md`](indexes/part-006-page-map.md)
- latest fidelity record: [`notes/visual-fidelity-scan-294.md`](notes/visual-fidelity-scan-294.md)
- Part-006 Tamil audit: **PASSED** — [`notes/part-006-tamil-audit.md`](notes/part-006-tamil-audit.md)
- assembled Tamil: **ELIGIBLE — NOT YET BUILT / CHECKED**
- English / bilingual review: **NOT ELIGIBLE until assembled Tamil passes its split-level check**
- state: **`part-tamil-audit-passed`**

### Part-006 Tamil-audit findings

The Part-006 audit confirmed:

- **49 / 49** physical pages represented exactly once in the page map;
- **49 / 49** canonical page records present and `verified`;
- Part 005→006 opening continuity `இருக்கவே` / `இருக்கிறாள் பரிமளா, ...` remains provenance-only across the derivative split;
- chapter and internal-transition structure agrees with canonical records;
- scan-280-onward Gemini lexical wording remains the controlling text while native scan evidence is restricted to structural/presentation findings;
- no unresolved Gemini lexical omission remains;
- cross-page continuities are preserved, including 282→283, 284→285, 285→286, 287→288, 289→290, 291→292, 292→293 and 293→294;
- scan **288 / printed 284** closes chapter 32 and begins chapter 33 under the source-printed transition;
- scan **294 / printed 290** remains an open derivative endpoint at `‘லாக்`, not a chapter or novel ending.

The full audit record is `notes/part-006-tamil-audit.md`.

## Aggregate canonical state

- records created: **294**
- verified / completed: **287**
- needs-review: **7 — Part 005 scans 215–219, 223–224**
- partial: **0**
- clean contiguous fully verified coverage: through scan **214 / printed page 212**
- later completed coverage: through scan **294**, except the seven damaged Part-005 records
- Parts 001–005: **part-complete at split level**
- Part 006: **Tamil audit PASSED; assembled Tamil pending**
- continuous split-level assembled Tamil / English review: through scan **245** only
- full-source physical coverage from received derivatives: through scan **294**

## Whole-work gate

**NOT ELIGIBLE.** Source beyond scan 294, the true ending/back matter, complete-source Tamil audit and whole-work bilingual review remain open.

## Exact next activity

Build the **Part-006 assembled Tamil reading layer from audited canonical pages only**:

1. extend `sections/27-chapter-27.md` from scan 245 through the chapter-27 close on scan 247;
2. create / populate assembled chapter files **28 through 33** from scans 247–294;
3. preserve the scan-251 four-star transition, chapter boundaries, reversible source-page provenance and verified page joins;
4. leave chapter 33 explicitly open at scan 294 / `‘லாக்`;
5. update `sections/README.md` after a split-level assembled consistency check.

Do not begin Part-006 English translation until the assembled Tamil layer passes that check.