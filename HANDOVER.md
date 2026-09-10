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

1. `அரும்பு` — scans **6–23** — **TAMIL SOURCE + ASSEMBLED TAMIL + ENGLISH PLAN PASSED; ENGLISH BATCHES 1–4 REVIEWED; SECTION 16 BILINGUAL REVIEW NEXT**.
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
- English Batches 1–4: **4 / 4 REVIEWED / COMPLETE**;
- English prose coverage: **18 / 18 source scans — scans 6–23**;
- Batch 4 closure: **0 omissions / 0 source-like additions / 0 unresolved translation items**;
- whole-work bilingual review: **NEXT — Section 16**;
- whole-work English: **NOT YET VERIFIED**;
- release-readiness: **BLOCKED until Section 16 passes**.

## Durable source findings

- scan 6 is unnumbered; no printed page 1 inferred;
- scans 7–13 print 2–8; scan 14 prints 10; scans 15–23 print 11–19; no page 9 invented;
- scan 23 is final and has no explicit `முற்றும்`;
- scan 22 `பேசினேன்`, scan 23 `அம்மனார்`, and final `இனி:......` are source-confirmed oddities;
- no source-backed chapter divisions exist;
- canonical `pages/` remain final textual authority.

## English Batch 4 checkpoint

`works/arumbu/translations/en/sections/01-arumbu.md` now contains reviewed English for the complete work, scans **6–23**.

Batch 4 used canonical pages `0021`–`0023` and was checked back against all three. Protected decisions are durably documented in `GLOSSARY.md` and `BATCH_04_REVIEW.md`:

- `பேசினேன்` → **I spoke**, preserving first-person;
- `அம்மனார்` → **Ammanar**, not Ammanur;
- `இனி:......` → **from now on:......**, retaining source punctuation;
- no source `முற்றும்` → no **The End**.

All four controlled English batches are reviewed, but the whole-work English must not be called VERIFIED until Section 16 independently passes.

## Exact next activity

Execute **Section 16 whole-work bilingual review for `அரும்பு` only**:

- create `works/arumbu/translations/en/TRANSLATION_REVIEW.md`;
- read the complete English `sections/01-arumbu.md` and canonical Tamil pages scans **6–23**;
- check complete coverage/order, duplicates, material omissions/additions, speaker attribution, actor agency, recurring names and terminology, political/religious/social rhetoric, all cross-page joins, recurring bud/leaf imagery, protected source oddities, final-page treatment, provenance and one-work/one-section identity;
- if PASS, mark whole-work English **VERIFIED**, synchronize all affected controls, commit, and stop;
- do **not** perform Section 17 release-readiness in the same checkpoint;
- do **not** begin `சாரப்பள்ளம் சாமுண்டி` or the 1978 `பெரிய இடத்துப் பெண்` witness comparison.
