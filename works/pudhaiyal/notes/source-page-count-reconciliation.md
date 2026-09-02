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

## Authority distinction for Part 006 / continuation

Through scan 279, completed records retain earlier source-first lexical reconciliation.

From **scan 280 onward**, user instruction establishes:

- Gemini transcription controls words/spellings/suffixes/lexical forms/wording/supplied lexical spacing;
- native scan controls headings, punctuation, quotation marks, long dashes, paragraph/speaker spacing, physical line/page breaks, separators and chapter/scene structure;
- native visual reading must not override Gemini lexical text;
- a Gemini lexical omission must be flagged rather than silently filled from source pixels.

Unless the user changes the rule, continuation work beyond scan 294 should preserve the same authority split.

## Split-source workaround

Received access derivatives:

1. Part 001 — scans **1–49** — **part-complete**
2. Part 002 — scans **50–98** — **part-complete**
3. Part 003 — scans **99–147** — **part-complete**
4. Part 004 — scans **148–196** — **part-complete**
5. Part 005 — scans **197–245** — **part-complete with explicit source-damage qualification**
6. Part 006 — scans **246–294 / printed 242–290** — **full split workflow PASSED / part-complete**
   - physical pages mapped: **49 / 49**
   - canonical records created: **49 / 49**
   - verified / structurally completed: **49 / 49**
   - needs-review: **0**
   - derivative SHA-256: `34a5ea5eb91a71ca8674760257779eb4ed6bdc6640517f8830b9ee70aa34aec7`
   - Tamil audit: [`part-006-tamil-audit.md`](part-006-tamil-audit.md)
   - assembled Tamil check: [`part-006-assembled-tamil-check.md`](part-006-assembled-tamil-check.md)
   - English source check: [`../translations/en/PART_006_ENGLISH_CHECK.md`](../translations/en/PART_006_ENGLISH_CHECK.md)
   - bilingual review: [`../translations/en/PART_006_REVIEW.md`](../translations/en/PART_006_REVIEW.md)

No split is committed to GitHub.

## Part-006 completed checkpoints

The Part-006 Tamil audit passed 49/49 coverage, page-map/canonical agreement, all required page joins, chapter/internal-transition structure, scan-280-onward Gemini lexical preservation, native structural fidelity and open endpoint handling at scan 294.

The assembled Tamil split-level check passed and established a continuous reading layer through scan 294.

The controlled English source check and bilingual review also passed. Reviewed English:

- completes chapter 27 through scan 247;
- covers chapters 28–33 through scan 294;
- retains the scan-251 four-star internal transition and real chapter boundaries;
- carries all audited physical-page joins continuously;
- respects the scan-280-onward Gemini lexical authority in controlling Tamil;
- retains source-specific satire, threats, violence, romantic delusion, coercion and caste-marked wording;
- remains open exactly where scan 294 stops.

English-only bilingual-review corrections included conservative **Chakkili** handling, removal of over-interpretive readings, preservation of a source anomaly without inserting a missing object, and stable **Raja Madam** glossary handling. Canonical Tamil was not changed.

Chapter 32 closes and chapter 33 begins on scan **288 / printed 284** via the source-printed transition.

Scan **294 / printed 290** ends at open Tamil `‘லாக்` / English `‘Lock` inside dialogue, with no closing punctuation, chapter close or work-ending marker. Part 006's endpoint is therefore only an access-derivative boundary and cannot be treated as the novel's ending.

## Current textual / derivative state

- canonical page records created: **294**
- verified / completed: **287**
- needs-review: **7 — Part 005 scans 215–219, 223–224**
- partial: **0**
- clean contiguous fully verified range: **1–214**
- later completed pages: through scan **294**, except the seven damaged Part-005 records
- Parts 001–006: **part-complete at split level**
- assembled Tamil: **part-reviewed continuously through scan 294**
- source-checked / bilingual-reviewed English: **continuous through scan 294**
- source scans physically mapped from received derivatives: **through scan 294**
- full-source manifest: **still incomplete beyond scan 294**

## Full-source extent track

Still required:

1. obtain the next source material beyond scan 294 and verify the open `‘லாக்` continuation;
2. establish the actual next source-scan / printed-page map from that source rather than assuming it;
3. process every later source scan through the same split workflow;
4. identify true final text / back matter / closing leaves;
5. determine exact original PDF scan/page-object count;
6. calculate the exact original full-source SHA-256 when byte-level access is available;
7. only after complete-source coverage, run final whole-work Tamil and bilingual audits and release-readiness checks.

Do not infer any of those values from the TDL printed-page count or from the 49-page size of earlier derivatives.

## Exact next activity

Obtain / resolve the **next source derivative beyond scan 294**, inspect its first page, and verify continuation from the open scan-294 `‘லாக்` boundary before any new canonical write. Do not assume the next part range, continuation word, chapter boundary or ending without source evidence.