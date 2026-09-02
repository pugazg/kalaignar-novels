# Source page-count reconciliation — புதையல்

Date opened: 2026-08-25  
Last updated: 2026-09-02

## Why this note exists

The first onboarding pass incorrectly treated scans **1–150** as the complete PDF. That conclusion is permanently withdrawn.

Tamil Digital Library describes source identity `TVA_BOK_0064097` as **443 p.**. Bibliographic printed extent is therefore tracked separately from actually received source-scan coverage.

Current received derivative coverage:

- source scans **1–392**
- visible printed text through page **388**
- canonical records through scan **343**
- exact original PDF scan/page-object count: **still pending**

## Authority distinction from scan 280 onward

Supplied Gemini transcription controls lexical wording/forms/spacing; native scans control headings, punctuation, quotations, paragraphing, physical boundaries, separators and chapter/scene structure.

- Part 007 lexical baseline: uploaded `p7.md`.
- Part 008 lexical baseline: uploaded `p8.md`.

For Part 007, the three complete source-confirmed `p7.md` omissions were restored only after the user's explicit 2026-09-02 instruction **`insert all three omissions`**: scans 304 `நீ`, 305 `என்ன`, and 315 `சரி...... வா! வா!......`. No broader lexical source-correction was authorized.

For Part 008, any complete source-visible lexical span absent from `p8.md` must be quarantined for review rather than silently source-filled.

## Split-source state

1. Part 001 — scans **1–49** — part-complete
2. Part 002 — scans **50–98** — part-complete
3. Part 003 — scans **99–147** — part-complete
4. Part 004 — scans **148–196** — part-complete
5. Part 005 — scans **197–245** — part-complete with source-damage qualification
6. Part 006 — scans **246–294 / printed 242–290** — part-complete
7. Part 007 — scans **295–343 / printed 291–339** — part-complete
8. Part 008 — scans **344–392 / printed 340–388** — **intake complete / canonical reconciliation next**

### Part-008 intake

- derivative: `TVA_BOK_0064097_புதையல்_part_008_pages_344-392.pdf`
- physical pages: **49**
- file size: **54,567,816 bytes**
- SHA-256: `717d3ab75eb970313062e1e61517d442cffa188f2fd8cadb8f75263b5e9a8852`
- lexical baseline: `p8.md`, **159,525 bytes / 319 lines**
- baseline SHA-256: `aad52bdfeae873459d561a52826f4787fd04f72ac1c27886212a1942d8e89ca2`
- canonical records: **0 / 49**
- verified: **0 / 49**
- not-started: **49**

Part-007→008 continuity is conclusively verified: scan 343 ends `அதிர்ஷ்`; scan 344 begins `டம் அடிக்குது!`; therefore the continuing word/utterance is **`அதிர்ஷ்டம் அடிக்குது!`**.

Native intake landmarks:

- scan 347 closes Chapter 39;
- scan 348 begins Chapter 40;
- scan 355 begins Chapter 41 after Chapter 40 closes;
- scan 362 begins Chapter 42 after Chapter 41 closes;
- scan 369 begins Chapter 43 after Chapter 42 closes;
- scan 376 begins Chapter 44 after Chapter 43 closes;
- scan 387 begins Chapter 45 after Chapter 44 closes;
- scan 392 / printed 388 remains inside Chapter 45 and ends open at `நமது`.

Records:

- Part-008 intake: [`part-008-source-intake.md`](part-008-source-intake.md)
- Part-008 page map: [`../indexes/part-008-page-map.md`](../indexes/part-008-page-map.md)

## Current textual / derivative state

- canonical records: **343**
- verified/completed: **336**
- needs-review: **7 — only Part 005 scans 215–219 and 223–224**
- partial: **0**
- Parts 001–007: **part-complete** at split level
- Part 008: **received/mapped; canonical processing pending**
- assembled Tamil: **through scan 343**
- source-checked and bilingual-reviewed English: **through scan 343**
- physically represented source coverage: **through scan 392 / printed 388**
- full-source manifest: **incomplete beyond scan 392**

## Full-source extent track

Still required:

1. run Part-008 canonical reconciliation and all split-level gates;
2. obtain source beyond scan 392 and verify continuation from open `நமது`;
3. process all later source scans and true ending/back matter;
4. determine exact original PDF scan/page-object count and SHA-256;
5. only after complete-source coverage, run final whole-work Tamil/bilingual/release audits.

Do not infer final source extent or ending from the TDL printed-page count or repeated derivative sizes.

## Exact next activity

Run **Part-008 canonical reconciliation across scans 344–392 in bulk**, using `p8.md` lexical authority and the native Part-008 PDF for structure. Preserve the verified `அதிர்ஷ்` + `டம்` join and quarantine complete baseline omissions rather than silently repairing them.