# Source page-count reconciliation — புதையல்

Date opened: 2026-08-25  
Last updated: 2026-09-02

## Why this note exists

The first onboarding pass incorrectly treated scans **1–150** as the complete PDF. That conclusion is permanently withdrawn.

Tamil Digital Library describes source identity `TVA_BOK_0064097` as **443 p.** and exposes the item as **PDF — 2 Files**. The repository therefore distinguishes:

- bibliographic printed extent: **443 p.**;
- source scans currently represented by received derivatives: **1–294**;
- canonical source-scan records currently created: **1–294**;
- exact original PDF scan/page-object count: **still pending**.

## Authority distinction for Part 006

Through scan 279, completed records retain earlier source-first lexical reconciliation.

From **scan 280 onward**, user instruction establishes:

- Gemini transcription controls words/spellings/suffixes/lexical forms/wording/supplied lexical spacing;
- native scan controls headings, punctuation, quotation marks, long dashes, paragraph/speaker spacing, physical line/page breaks, separators and chapter/scene structure;
- native visual reading must not override Gemini lexical text;
- a Gemini lexical omission must be flagged rather than silently filled from source pixels.

## Split-source workaround

Received access derivatives:

1. Part 001 — scans **1–49** — **part-complete**
2. Part 002 — scans **50–98** — **part-complete**
3. Part 003 — scans **99–147** — **part-complete**
4. Part 004 — scans **148–196** — **part-complete**
5. Part 005 — scans **197–245** — **part-complete with explicit source-damage qualification**
6. Part 006 — scans **246–294 / printed 242–290** — **Tamil audit PASSED + assembled Tamil PASSED; controlled English next**
   - physical pages mapped: **49 / 49**
   - canonical records created: **49 / 49**
   - verified / structurally completed: **49 / 49**
   - needs-review: **0**
   - derivative SHA-256: `34a5ea5eb91a71ca8674760257779eb4ed6bdc6640517f8830b9ee70aa34aec7`
   - Tamil audit record: [`part-006-tamil-audit.md`](part-006-tamil-audit.md)
   - assembled Tamil check: [`part-006-assembled-tamil-check.md`](part-006-assembled-tamil-check.md)

No split is committed to GitHub.

## Part-006 completed Tamil checkpoints

The Part-006 Tamil audit passed:

- 49/49 physical-page and canonical coverage;
- page-map/canonical agreement;
- Part 005→006 opening continuity;
- page-boundary joins and chapter transitions;
- scan-280-onward Gemini lexical preservation;
- native structural fidelity;
- no unresolved Gemini lexical omission;
- open endpoint handling at scan 294.

The assembled Tamil split-level check also passed:

- chapter 27 is completed through scan 247 without creating a false split boundary;
- chapters 28–33 are assembled from audited canonical records only;
- the source-printed four-star transition on scan 251 is retained;
- real chapter transitions are preserved at scans 254, 262, 271, 278 and 288;
- verified physical-page joins are resolved only in the reading layer with reversible provenance;
- scans 280–294 remain lexically controlled by Gemini;
- chapter 33 remains open at scan 294.

Chapter 32 closes and chapter 33 begins on scan **288 / printed 284** via the source-printed transition.

Scan **294 / printed 290** ends at open `‘லாக்` inside dialogue, with no closing punctuation, chapter close or work-ending marker. Part 006's endpoint is therefore only an access-derivative boundary and cannot be treated as the novel's ending.

## Current textual / derivative state

- canonical page records created: **294**
- verified / completed: **287**
- needs-review: **7 — Part 005 scans 215–219, 223–224**
- partial: **0**
- clean contiguous fully verified range: **1–214**
- later completed pages: through scan **294**, except the seven damaged Part-005 records
- Parts 001–005: **part-complete at split level**
- Part 006: **`assembled-part-checked`; controlled English next**
- assembled Tamil: **part-reviewed continuously through scan 294**
- controlled English / bilingual review: **part-reviewed continuously through scan 245 only**
- source scans physically mapped from received derivatives: **through scan 294**
- full-source manifest: **still incomplete beyond scan 294**

## Full-source extent track

Still required:

1. complete the **Part-006 controlled English translation** from the checked assembled Tamil layer through scan 294;
2. source-check the Part-006 English against canonical Tamil and run the Part-006 bilingual review before calling Part 006 `part-complete`;
3. obtain later source splits beyond scan 294;
4. process every later source scan;
5. identify true final text / back matter / closing leaves;
6. determine exact original PDF scan/page-object count;
7. calculate the exact original full-source SHA-256 when byte-level access is available;
8. only after complete-source coverage, run final whole-work Tamil and bilingual audits and release-readiness checks.

Do not infer any of those values from the TDL printed-page count.

## Exact next activity

Begin the **Part-006 controlled English translation** from the checked assembled Tamil layer: extend chapter 27 through its close on scan 247, translate chapters 28–33 through scan 294, preserve the scan-251 internal transition and real chapter boundaries, and leave chapter 33 open at `‘லாக்`. Do not start the Part-006 bilingual review until the English translation is complete and source-checked.