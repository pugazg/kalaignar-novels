# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Live `main` is authoritative.
- Active source: **1978 `அரும்பு` four-story compilation**.
- Active work: `works/arumbu/`.
- `works/vellikkizhamai/` remains RELEASE-READY / CLOSED.

## Controlling compilation source

`TVA_BOK_0064361_அரும்பு.pdf`

- SHA-256: `04a3013e1f58a1800867acc5d2f159976c47994a64478036e6fe0201edf120bc`
- size: **117,270,339 bytes**
- physical scans: **92**
- image-only
- publisher: **தமிழ்க்கனி பதிப்பகம், சென்னை-28**
- edition: **முதற் பதிப்பு — 1978**
- source PDF: **DO NOT COMMIT**.

Collection-level intake: `collections/arumbu-1978/` — **COMPLETE**.

## Component map

1. `அரும்பு` — scans **6–23** — **TAMIL SOURCE + ASSEMBLED TAMIL + ENGLISH PLAN PASSED; ENGLISH BATCHES 1–3 REVIEWED; BATCH 4 NEXT**.
2. `சாரப்பள்ளம் சாமுண்டி` — scans **24–48** — queued.
3. `பெரிய இடத்துப் பெண்` — scans **49–74** — additional 1978 witness only; existing controlling source/canonical freeze unchanged.
4. `நடுத்தெரு நாராயணி` — scans **75–90** — queued.

Scans 1–5 are collection front matter; scans 91–92 publisher catalogue/back-cover matter.

## `அரும்பு` durable state

- canonical / verified Tamil records: **18 / 18 — scans 6–23 contiguous**;
- all T1/T2/T3 source batches: **PASS / COMPLETE**;
- T2 corrections: **6**; unresolved historical glyphs: **0**;
- T3 corrections: **36**; unresolved source readings: **0**;
- whole-work Tamil audit: **PASS / COMPLETE**;
- assembled Tamil: **PASS / COMPLETE — 1 / 1 section**;
- English translation plan: **PASS / COMPLETE**;
- working English title: **The Bud**;
- English Batch 1 — scans **6–10**: **REVIEWED / COMPLETE**;
- English Batch 2 — scans **11–15**: **REVIEWED / COMPLETE**;
- English Batch 3 — scans **16–20**: **REVIEWED / COMPLETE**;
- current English coverage: **15 / 18 source scans — scans 6–20**;
- English Batch 4 — scans **21–23**: **NEXT**;
- whole-work bilingual review: **BLOCKED until Batch 4 closes**.

## Durable source findings

- scan 6 is unnumbered; no printed page 1 inferred;
- scans 7–13 print 2–8; scan 14 prints 10; scans 15–23 print 11–19; no page 9 invented;
- scan 23 is final and has no explicit `முற்றும்`;
- scan 22 `பேசினேன்`, scan 23 `அம்மனார்`, and final `இனி:......` are source-confirmed protected oddities;
- no source-backed chapter divisions exist;
- canonical `pages/` remain final textual authority.

## English Batch 3 checkpoint

`works/arumbu/translations/en/sections/01-arumbu.md` now contains reviewed English through scan **20**. Batch 3 was translated only from canonical pages `0016`–`0020` and checked back against all five records. Closure: **0 omissions / 0 source-like additions / 0 unresolved translation items**.

The established 15→16, 16→17, 17→18, 18→19 and 19→20 source continuities remain reversible. Batch 3 locks source-facing handling including `gomedhakam gem`, `Moodevi`, `thazhai frond`, and Kumar's fake/real/doll `Amma` contrast. No scan 21 prose is present.

## Exact next activity

Execute **English Batch 4 — scans 21–23 only**:

- read `NOVEL_PROCESSING_GUIDE.md` Sections 14–16, `TRANSLATION_PLAN.md`, current `PROGRESS.md`, `GLOSSARY.md`, `BATCH_03_REVIEW.md`, and the existing English section first;
- append only canonical Tamil corresponding to scans **21–23**;
- explicitly resolve/document scan 22 `பேசினேன்`, scan 23 `அம்மனார்`, and final `இனி:......`;
- preserve absence of explicit `முற்றும்` / “The End”;
- source-check the entire new span against canonical pages `0021`–`0023`;
- update glossary/progress/work/root controls;
- mark Batch 4 `reviewed` only after source comparison;
- commit and stop before Section 16 whole-work bilingual review;
- do **not** start `சாரப்பள்ளம் சாமுண்டி` or the 1978 `பெரிய இடத்துப் பெண்` witness comparison.
