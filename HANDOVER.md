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

1. `அரும்பு` — scans **6–23** — `works/arumbu/` — **TAMIL SOURCE + ASSEMBLED TAMIL + ENGLISH PLAN PASSED; ENGLISH BATCHES 1–2 REVIEWED; BATCH 3 NEXT**.
2. `சாரப்பள்ளம் சாமுண்டி` — scans **24–48** — queued.
3. `பெரிய இடத்துப் பெண்` — scans **49–74** — additional 1978 witness only; existing controlling source/canonical freeze unchanged.
4. `நடுத்தெரு நாராயணி` — scans **75–90** — queued.

Scans 1–5 are collection front matter; scans 91–92 publisher catalogue/back-cover matter.

## `அரும்பு` durable state

- canonical / verified Tamil records: **18 / 18 — scans 6–23 contiguous**;
- all four T1/T2/T3 source batches: **PASS / COMPLETE**;
- T2 corrections: **6**; unresolved historical glyphs: **0**;
- T3 source-fidelity corrections: **36**; unresolved source readings: **0**;
- whole-work Tamil audit: **PASS / COMPLETE**;
- assembled Tamil: **PASS / COMPLETE — 1 / 1 section**;
- English translation plan: **PASS / COMPLETE**;
- working English title: **The Bud**;
- English Batch 1 pilot — scans **6–10**: **REVIEWED / COMPLETE**;
- English Batch 2 — scans **11–15**: **REVIEWED / COMPLETE**;
- current English coverage: **10 / 18 source scans — scans 6–15**;
- English Batch 3 — scans **16–20**: **NEXT**;
- whole-work bilingual review: **BLOCKED**.

## Durable source findings

- scan 6 remains unnumbered; no printed page 1 is inferred;
- scans 7–13 visibly print **2–8**;
- scan 14 visibly prints **10**; no synthetic printed page 9 is inserted;
- scans 15–23 visibly print **11–19**;
- scan 23 is final and has no explicit `முற்றும்`;
- source-confirmed scan 22 `பேசினேன்`, scan 23 `அம்மனார்`, and final `இனி:......` remain unchanged;
- no source-backed chapter divisions exist;
- canonical `pages/` remain final textual authority.

## English translation checkpoints

`works/arumbu/translations/en/sections/01-arumbu.md` now contains reviewed English prose through scan **15** only.

Batch 1, scans **6–10**, and Batch 2, scans **11–15**, were each translated from the audited canonical Tamil and source-checked before being marked reviewed. Each closed with **0 omissions, 0 source-like additions and 0 unresolved translation items**.

Batch 2 specifically preserves:

- the 11→12 `போய்` / `விட்டனர்.` continuation;
- the 13→14 `ஊற்றெடுத்துக் கிளம்பிவரும்` / `அருவி!` continuation;
- the visible printed-page **8 → 10** jump without inventing page 9;
- Mayavaram and Madras Mail as source-period forms;
- newly locked `oppari`, `Aararo`, `aunt's son`, `pottu`, `mangalyam`, `Mahalakshmi`, and `“rowdy” gang` handling;
- the intentional scan-15 open fragment corresponding to `செல்லக்`; no scan 16 English prose is present.

## Exact next activity

Execute **English Batch 3 — scans 16–20 only**:

- read `NOVEL_PROCESSING_GUIDE.md` Sections 14–16, the translation plan, current `PROGRESS.md`, `GLOSSARY.md`, and existing English section first;
- append only audited Tamil corresponding to scans **16–20**;
- use assembled Tamil for continuity but canonical pages `0016`–`0020` as final textual authority;
- retain reversible scan/page provenance;
- source-check the entire new span;
- preserve locked decisions unless a direct source conflict requires documented review;
- synchronize translation/work/root controls;
- mark Batch 3 `reviewed` only after source comparison;
- commit and stop before Batch 4;
- do **not** begin `சாரப்பள்ளம் சாமுண்டி` or the 1978 `பெரிய இடத்துப் பெண்` witness comparison.
