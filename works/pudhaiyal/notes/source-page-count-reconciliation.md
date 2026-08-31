# Source page-count reconciliation — புதையல்

Date opened: 2026-08-25  
Last updated: 2026-08-31

## Why this note exists

The first onboarding pass incorrectly treated scans **1–150** as the complete PDF. That conclusion is permanently withdrawn.

Tamil Digital Library describes source identity `TVA_BOK_0064097` as **443 p.** and exposes the item as **PDF — 2 Files**. The repository therefore distinguishes:

- bibliographic printed extent: **443 p.**;
- source scans currently represented by received derivatives: **1–294**;
- canonical source-scan records currently created: **1–281**;
- exact original PDF scan/page-object count: **still pending**.

## Authority distinction for active Part 006

Through scan 279, completed records retain earlier source-first lexical reconciliation.

From **scan 280 onward**, user instruction establishes:

- Gemini transcription controls words/spellings/suffixes/lexical forms;
- native scan controls headings, punctuation, quotation marks, long dashes, paragraph/speaker spacing, physical line/page breaks, separators and chapter/scene structure;
- native visual reading must not override Gemini lexical words;
- a Gemini lexical omission must be flagged rather than silently filled from source pixels.

## Split-source workaround

Received access derivatives:

1. Part 001 — scans **1–49** — **part-complete**
2. Part 002 — scans **50–98** — **part-complete**
3. Part 003 — scans **99–147** — **part-complete**
4. Part 004 — scans **148–196** — **part-complete**
5. Part 005 — scans **197–245** — **part-complete with explicit source-damage qualification**
6. Part 006 — scans **246–294 / printed 242–290** — **in progress**
   - physical pages mapped: **49 / 49**
   - canonical records created: **36 / 49 — scans 246–281**
   - complete / structurally verified: **36**
   - needs-review: **0**
   - not-started: **13 — scans 282–294**
   - derivative SHA-256: `34a5ea5eb91a71ca8674760257779eb4ed6bdc6640517f8830b9ee70aa34aec7`

No split is committed to GitHub.

## Current hybrid-policy checkpoint

- scan 280 is the first page processed under the Gemini-lexical/native-structure policy;
- scan 281 / printed 277 continues chapter 32 with Gemini words unchanged;
- native source supplies punctuation, quotation structure, paragraphing and physical line breaks;
- source long dash `உணர்ந்து — நம்` is preserved;
- physical word-internal line breaks include `இசைத்` / `துக்`, `தன்` / `னைக்`, `உள்` / `ளத்தைப்`, `பரி` / `மளா`, and `தன்` / `னைத்`;
- no source-printed chapter/scene transition occurs on scan 281;
- physical endpoint: `பைத்யக்காரன்.`;
- no lexical source-vs-Gemini discrepancy is adjudicated under the active policy.

## Part-006 physical structure map

- chapter 28 begins scan 247 / printed 243;
- four-star internal transition scan 251 / printed 247;
- chapter 29 begins scan 254 / printed 250 and closes scan 262 / printed 258;
- chapter 30 begins scan 262 / printed 258 and closes scan 271 / printed 267;
- chapter 31 begins scan 271 / printed 267 and closes scan 278 / printed 274;
- chapter 32 begins scan 278 / printed 274;
- chapter 33 begins scan 288 / printed 284 and continues through scan 294 / printed 290.

This is structure mapping only for scans 282–294; they remain not-started until processed.

## Current textual state

- canonical page records created: **281**
- verified / completed: **274**
- needs-review: **7**
- partial: **0**
- clean contiguous fully verified range: **1–214**
- later completed pages: through scan **281**, except the seven damaged Part-005 records
- Parts 001–005: **part-complete at split level**
- Part 006: **in progress — 36 / 49 complete**
- continuous split-level assembled Tamil / English review: **through scan 245 only**
- source scans physically mapped from received derivatives: **through scan 294**
- full-source manifest: **still incomplete beyond scan 294**

## Full-source extent track

Still required:

1. process Part-006 scans **282–294** under the active Gemini-lexical/native-structure workflow;
2. complete the Part-006 Tamil audit, assembled Tamil, controlled English and bilingual review before calling Part 006 `part-complete`;
3. obtain later source splits beyond scan 294;
4. process every later source scan;
5. identify true final text / back matter / closing leaves;
6. determine exact original PDF scan/page-object count;
7. calculate the exact original full-source SHA-256 when byte-level access is available;
8. only after complete-source coverage, run final whole-work Tamil and bilingual audits and release-readiness checks.

Do not infer any of those values from the TDL printed-page count.

## Exact next activity

Process **scan 282 / printed page 278**, continuing chapter 32. Keep Gemini's words exactly; use native scan evidence only for structural/presentation findings.