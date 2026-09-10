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

1. `அரும்பு` — scans **6–23** — `works/arumbu/` — **TAMIL SOURCE + ASSEMBLED TAMIL + ENGLISH PLAN PASSED; ENGLISH BATCH 1 REVIEWED; BATCH 2 NEXT**.
2. `சாரப்பள்ளம் சாமுண்டி` — scans **24–48** — queued.
3. `பெரிய இடத்துப் பெண்` — scans **49–74** — additional 1978 witness only; existing controlling source/canonical freeze unchanged.
4. `நடுத்தெரு நாராயணி` — scans **75–90** — queued.

Scans 1–5 are collection front matter; scans 91–92 publisher catalogue/back-cover matter.

## `அரும்பு` durable state

- work span: **18 scans — physical 6–23**;
- canonical / verified records: **18 / 18 — scans 6–23 contiguous**;
- all four T1/T2/T3 source batches: **PASS / COMPLETE**;
- T2 corrections: **6**; unresolved historical glyphs: **0**;
- T3 source-fidelity corrections: **36**; unresolved source readings: **0**;
- whole-work Tamil audit: **PASS / COMPLETE**;
- Tamil source layer: **PASSED**;
- assembled Tamil: **PASS / COMPLETE — 1 / 1 section**;
- English translation plan: **PASS / COMPLETE**;
- working English title: **The Bud**;
- English Batch 1 pilot — scans **6–10**: **REVIEWED / COMPLETE**;
- current English coverage: **5 / 18 source scans**;
- English Batch 2 — scans **11–15**: **NEXT**;
- whole-work bilingual review: **BLOCKED**.

## Durable source / assembly findings

- scan 6 remains unnumbered; no printed `1` is inferred;
- scans 7–13 visibly print **2–8**;
- scan 14 visibly prints **10**; no synthetic printed page 9 is inserted;
- scans 15–23 visibly print **11–19**;
- physical continuity across 13→14 remains `ஊற்றெடுத்துக் கிளம்பிவரும்` / `அருவி!`;
- scan 23 is the final physical page and has no explicit `முற்றும்`;
- source-confirmed scan 22 `பேசினேன்`, scan 23 `அம்மனார்`, and final `இனி:......` remain unchanged;
- no source-backed chapter divisions exist;
- canonical `pages/` remain final textual authority.

## English Batch 1 pilot checkpoint

`works/arumbu/translations/en/sections/01-arumbu.md` now contains English prose for scans **6–10 only**.

The pilot was derived from audited canonical pages `0006`–`0010` and then checked back against those records. Review result: **PASS / REVIEWED** with **0 omissions, 0 source-like additions, 0 unresolved translation items**.

Pilot style and terminology are locked in `works/arumbu/translations/en/GLOSSARY.md`, including:

- **The Bud / bud** for `அரும்பு`;
- Gokul, Gomathi, Kumar, Rathinam, Thirukkuvalai, Ammanur, Chennai;
- `agraharam`, `priest`, `homa fire-pit`, `ammi`, `arasani`;
- **new-style** for `புதுமை முறை` without importing an unprinted movement label;
- **life-contract ceremony** for `வாழ்க்கை ஒப்பந்த விழா`;
- `Appa` in emotional direct address and contextual `father` in narration;
- source ellipses/repetition/rhetorical force preserved where material;
- reversible source scan/page comments retained.

No scan 11 English prose has been started.

## Exact next activity

Execute **English Batch 2 — scans 11–15 only**:

- read `NOVEL_PROCESSING_GUIDE.md` Sections 14–16, `TRANSLATION_PLAN.md`, current `PROGRESS.md` and `GLOSSARY.md` first;
- append only audited Tamil corresponding to scans **11–15** to `translations/en/sections/01-arumbu.md`;
- use assembled Tamil for continuity but canonical pages `0011`–`0015` as final textual authority;
- retain reversible scan/page provenance;
- source-check the entire new span back against the five canonical page records;
- preserve locked Batch 1 decisions unless a source-backed conflict is explicitly documented;
- update glossary/progress/work/root controls;
- mark Batch 2 `reviewed` only after source comparison;
- commit and stop before Batch 3;
- do **not** begin `சாரப்பள்ளம் சாமுண்டி` or the 1978 `பெரிய இடத்துப் பெண்` witness comparison.
