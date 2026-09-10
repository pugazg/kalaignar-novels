# வெள்ளிக்கிழமை

**ஆசிரியர் (source cover):** மு. கருணாநிதி  
**வெளியீடு:** திராவிடப்பண்ணை, 34, சிந்தாமணி, திருச்சி-2  
**பதிப்பு:** இரண்டாம் பதிப்பு — 1968  
**Source PDF:** `TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf`  
**Source PDF committed:** No

## Current archival status

- source scans: **179**; bytes: **251,126,214**;
- SHA-256: `ac241cbfbe3d47d76f22140f43c662176ba29a91521b826a1a8f5c75cf3081d3`;
- manifest: **179 / 179**;
- canonical page records: **179 / 179 — COMPLETE / VERIFIED**;
- final narrative: **scan 179 / printed 178**, ending `திரும்பினர்கள்.`;
- unresolved source holds: **0**;
- forward historical-glyph coverage: **PASS scans 1–179**;
- second historical-glyph re-audit: **COMPLETE — scans 119–179 / 61 of 61 PASS**;
- second-pass corrections: **5 total / 0 unresolved**;
- full Tamil source audit: **PASSED**;
- Tamil source layer: **PASSED**;
- assembled Tamil: **PASSED — Chapters 1–23 / 23 VERIFIED**;
- final assembled Tamil consistency gate: **PASSED — 0 unresolved / 0 canonical changes**;
- English translation plan: **COMPLETE**;
- English Batch 1 pilot / Chapter 1: **REVIEWED / COMPLETE**;
- English chapters present/reviewed: **1 / 23**;
- English source coverage: **scans 4–12**;
- next English activity: **Batch 2 — Chapters 2–4**.

## Canonical authority

`pages/` is the archival preservation layer and remains controlling. The PASSED `sections/` layer is the continuous Tamil reading layer. English is a derived layer only; if English conflicts with canonical Tamil, canonical Tamil governs.

Completed Tamil source/glyph/assembly gates must not be reopened without genuinely new direct-source evidence.

## Assembled Tamil progress

All **23 / 23 chapters are VERIFIED and the assembled Tamil layer is PASSED**. Chapter 15 ends on scan 126; Chapter 16 begins cleanly at centered `16` on scan 127. The known literal discontinuities at scans 117→118, 122→123 and 156→157 remain unrepaired. Scan 179 contributes final narrative only; its lower illustration and later handwriting remain excluded.

## English translation state

Working English title: **_Friday_**.

English controls under [`translations/en/`](translations/en/):

- [`TRANSLATION_PLAN.md`](translations/en/TRANSLATION_PLAN.md) — **COMPLETE**;
- [`README.md`](translations/en/README.md);
- [`PROGRESS.md`](translations/en/PROGRESS.md);
- [`GLOSSARY.md`](translations/en/GLOSSARY.md) — pilot style/terminology lock complete;
- [`sections/README.md`](translations/en/sections/README.md);
- [`TRANSLATION_REVIEW.md`](translations/en/TRANSLATION_REVIEW.md) — blocked until all chapters are reviewed;
- [`RELEASE_REPORT.md`](translations/en/RELEASE_REPORT.md) — blocked until bilingual review passes.

The final English structure mirrors the Tamil one-to-one as 23 chapter files. Batch 1 was the mandatory single-chapter pilot; subsequent default batches contain at most three contiguous chapters unless explicitly enlarged by the user.

## English Batch 1 pilot closure

[`translations/en/sections/01-chapter-01.md`](translations/en/sections/01-chapter-01.md) covers **scans 4–12** and is **REVIEWED**.

The pilot was checked against canonical page records `0004` through `0012` and passed:

- complete paragraph/dialogue/quoted-verse representation;
- source scan and printed-page provenance;
- reversible joins at scans 4→5, 5→6, 8→9 and 10→11;
- first-person interior monologue / third-person narration transition;
- rhetorical questions, humour, repetition and emotional force;
- religious/cultural terminology without added doctrinal explanation;
- Tiruppavai excerpts translated only from the lines printed in this edition;
- no canonical Tamil changes.

Pilot result: **PASS / REVIEWED — 0 unresolved / 0 Tamil changes**.

Recurring pilot decisions are locked in `translations/en/GLOSSARY.md`.

## Exact next activity

Run **English Batch 2 — Chapters 2–4**:

- Chapter 2 — scans **13–22**;
- Chapter 3 — scan **23 through scan 33 before centered `4`**;
- Chapter 4 — scan **33 after centered `4` through scan 45 before centered `5`**.

Create `translations/en/sections/02-chapter-02.md` through `04-chapter-04.md`, source-check against canonical `pages/`, review the entire bounded batch, update controls and commit. Do not start Chapter 5 in the same default iteration.