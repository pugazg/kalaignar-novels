# Source page-count reconciliation — புதையல்

Date opened: 2026-08-25  
Last updated: 2026-09-03

Tamil Digital Library describes source identity `TVA_BOK_0064097` as **443 p.** Bibliographic printed extent is tracked separately from received derivative scan coverage.

## Current received coverage

- source derivatives cover scans **1–448**;
- visible printed narrative reaches page **443** on scan **447**;
- scan **448** is unnumbered printer back matter / colophon;
- canonical records now cover **1–448**;
- verified canonical records: **440 / 448**;
- needs-review: **8** — seven qualified Part-005 damage records plus Part-010 scan 445;
- assembled Tamil remains through scan **392 / printed 388**;
- source-checked and bilingual-reviewed English remain through scan **392 / printed 388**;
- exact original full-PDF scan/page-object count: **pending full-source byte/page reconciliation**.

The received material visibly contains the actual narrative ending on scan **447 / printed 443**, followed by printer imprint `அன்பு அச்சகம், பொறையார்.` on scan **448**.

## Split-source state

1. Part 001 — scans 1–49 — part-complete
2. Part 002 — scans 50–98 — part-complete
3. Part 003 — scans 99–147 — part-complete
4. Part 004 — scans 148–196 — part-complete
5. Part 005 — scans 197–245 — part-complete with source-damage qualification
6. Part 006 — scans 246–294 — part-complete
7. Part 007 — scans 295–343 — part-complete
8. Part 008 — scans 344–392 / printed 340–388 — part-complete
9. Part 009 — scans **393–441 / printed 389–437** — **49/49 verified; Tamil audit PASSED**
10. Part 010 — scans **442–448 / printed 438–443 + colophon** — **7/7 canonical; 6 verified; scan 445 needs-review**

### Part 009

- PDF: **49 pages / 57,643,045 bytes**
- SHA-256: `8e104e151ced62916de64d320afe41a4ede549af6712fba8c654ae6c1385cbce`
- lexical baseline: `p9.md`, **164,794 bytes / 242 logical lines**
- baseline SHA-256: `b0b227ba8bce1650f65a10b114f53f4601a4c7d72f5649993de20bf991071664`
- opening join: scan 392 `நமது` + scan 393 `வாழ்க்கையை` → **`நமது வாழ்க்கையை`**
- closing join: scan 441 `அம்ப` + scan 442 `லமே` → **`அம்பலமே`**
- canonical/verified: **49 / 49**
- needs-review: **0**
- Tamil audit: **PASSED**

### Part 010

- PDF: **7 pages / 7,206,369 bytes**
- SHA-256: `27660cd6a8abe288ea1924f4ca02c23747713afc5883b010fb2f58a61b6ebbd0`
- lexical baseline: `p10.md`, **17,559 bytes / 165 logical lines**
- baseline SHA-256: `938407860a3a80e14da3a5d6a273675b8cdcc3e70e8a0e538f40dcceb871dc3a`
- canonical: **7 / 7**
- verified: **6 / 7**
- needs-review: **scan 445 / printed 441**
- scan 447 / printed 443: actual narrative ending
- scan 448: printer colophon

Native scan 445 contains complete word **`விடு`** in `தங்கத்திற்குப் பக்கத்திலே புதைத்து விடு!”`; `p10.md` omits it. The word is withheld pending explicit user disposition.

## Aggregate canonical state

- canonical: **448**
- verified/completed: **440**
- needs-review: **8**
- partial: **0**
- Parts 001–008: **part-complete**
- Part 009: **Tamil audit PASSED**
- Part 010: **Tamil audit BLOCKED on one lexical omission**

## Still required

1. resolve Part-010 scan-445 `விடு` omission and close Part-010 Tamil audit;
2. assemble Tamil for scans 393–447 / Chapters 45–51 and keep scan448 back matter separate;
3. controlled English translation, source check and bilingual review through the ending;
4. final whole-work Tamil/bilingual/release audits;
5. exact full-source SHA-256 and full-PDF page-object count if/when the original full file is byte-resolved.

## Exact next activity

Obtain explicit user disposition for scan-445 native word **`விடு`**. If authorized, restore it narrowly and continue downstream gates.
