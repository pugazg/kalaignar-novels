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

1. `அரும்பு` — scans **6–23** — `works/arumbu/` — **TAMIL SOURCE + ASSEMBLED TAMIL + ENGLISH PLAN PASSED; ENGLISH BATCH 1 PILOT NEXT**.
2. `சாரப்பள்ளம் சாமுண்டி` — scans **24–48** — queued.
3. `பெரிய இடத்துப் பெண்` — scans **49–74** — additional 1978 witness only; existing controlling source/canonical freeze unchanged.
4. `நடுத்தெரு நாராயணி` — scans **75–90** — queued.

Scans 1–5 are collection front matter; scans 91–92 publisher catalogue/back-cover matter.

## Workflow

Root `SOURCE_BATCH_CHECKPOINT_WORKFLOW.md` governed bounded source batches: T1 direct visual transcription → sync/commit/stop; T2 independent historical-glyph re-read → sync/commit/stop; T3 final source-fidelity closure → sync/commit/stop.

`NOVEL_PROCESSING_GUIDE.md` Section 12 whole-work Tamil audit and Section 13 assembled Tamil have passed for `அரும்பு`. Section 14 English translation planning has now also passed. No English prose has yet been translated.

## `அரும்பு` durable state

- work span: **18 scans — physical 6–23**;
- canonical records: **18 / 18 — scans 6–23**;
- verified canonical records: **18 / 18 — scans 6–23 contiguous**;
- all four T1/T2/T3 source batches: **PASS / COMPLETE**;
- total dedicated T2 corrections: **6**; unresolved historical glyphs: **0**;
- total T3 source-fidelity corrections: **36**; unresolved source readings: **0**;
- whole-work Tamil audit: **PASS / COMPLETE**;
- Tamil source layer: **PASSED**;
- assembled Tamil: **PASS / COMPLETE — 1 / 1 section**;
- assembled section: `works/arumbu/sections/01-arumbu.md` — scans **6–23**;
- English translation plan: **PASS / COMPLETE**;
- working English title: **The Bud**;
- English prose: **NOT STARTED**;
- next English checkpoint: **Batch 1 pilot — scans 6–10**.

## Durable Tamil / assembly findings

- scan 6 remains unnumbered; no printed `1` is inferred;
- scans 7–13 visibly print **2–8**;
- scan 14 visibly prints **10**; no synthetic printed page 9 is inserted;
- scans 15–23 visibly print **11–19**;
- physical continuity across 13→14 remains `ஊற்றெடுத்துக் கிளம்பிவரும்` / `அருவி!`;
- scan 23 is the final physical page and has no explicit `முற்றும்`;
- source-confirmed scan 22 `பேசினேன்`, scan 23 `அம்மனார்`, and final `இனி:......` remain unchanged;
- no source-backed chapter divisions exist;
- assembled Tamil is one continuous reading section with reversible provenance;
- canonical `pages/` remain final textual authority.

## English planning checkpoint

Section 14 controls under `works/arumbu/translations/en/`:

- `TRANSLATION_PLAN.md` — **PASS / COMPLETE**;
- `README.md` — planned-state control;
- `PROGRESS.md` — initialized;
- `GLOSSARY.md` — initialized with provisional/protected terms;
- `PLAN_CHECKPOINT.md` — durable planning record.

The final English reading layer will remain one section but be translated in four source-aligned checkpoints:

1. scans **6–10** — pilot;
2. scans **11–15**;
3. scans **16–20**;
4. scans **21–23**.

The plan protects source oddities and prohibits silent normalization, including `பேசினேன்`, `அம்மனார்`, `இனி:......`, the printed-page 8→10 jump, and the absence of explicit `முற்றும்`.

## Exact next activity

Execute **English Batch 1 pilot — scans 6–10 only**:

- read `NOVEL_PROCESSING_GUIDE.md` Sections 14–16 and the completed `TRANSLATION_PLAN.md` first;
- translate only audited Tamil for scans **6–10** into `works/arumbu/translations/en/sections/01-arumbu.md`;
- use assembled Tamil for continuity but canonical page records 0006–0010 as final textual authority;
- retain reversible scan/page provenance;
- source-check the full pilot back against canonical Tamil;
- lock applicable translation/style/terminology decisions in `GLOSSARY.md`;
- update `README.md` and `PROGRESS.md`;
- mark Batch 1 `reviewed` only after source comparison;
- synchronize root/work controls, commit, and stop before Batch 2;
- do **not** start `சாரப்பள்ளம் சாமுண்டி` or the 1978 `பெரிய இடத்துப் பெண்` witness comparison.
