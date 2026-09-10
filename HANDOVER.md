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

1. `அரும்பு` — scans **6–23** — `works/arumbu/` — **TAMIL SOURCE LAYER PASSED; ASSEMBLED TAMIL NEXT**.
2. `சாரப்பள்ளம் சாமுண்டி` — scans **24–48** — queued.
3. `பெரிய இடத்துப் பெண்` — scans **49–74** — additional 1978 witness only; existing controlling source/canonical freeze unchanged.
4. `நடுத்தெரு நாராயணி` — scans **75–90** — queued.

Scans 1–5 are collection front matter; scans 91–92 publisher catalogue/back-cover matter.

## Workflow

Root `SOURCE_BATCH_CHECKPOINT_WORKFLOW.md` governed bounded source batches: T1 direct visual transcription → sync/commit/stop; T2 independent historical-glyph re-read → sync/commit/stop; T3 final source-fidelity closure → sync/commit/stop.

`NOVEL_PROCESSING_GUIDE.md` Section 12 then requires a separate whole-work Tamil audit before the assembled Tamil reading layer. That audit has now passed for `அரும்பு`.

## `அரும்பு` durable state

- work span: **18 scans — physical 6–23**;
- canonical records: **18 / 18 — scans 6–23**;
- verified canonical records: **18 / 18 — scans 6–23 contiguous**;
- scans 6–10 T1/T2/T3: **PASS / COMPLETE**;
- scans 11–15 T1/T2/T3: **PASS / COMPLETE**;
- scans 16–20 T1/T2/T3: **PASS / COMPLETE**;
- scans 21–23 T1/T2/T3: **PASS / COMPLETE**;
- total dedicated T2 corrections across the work: **6**; unresolved historical glyphs: **0**;
- total T3 source-fidelity corrections across the work: **36**; unresolved source readings: **0**;
- whole-work Tamil audit: **PASS / COMPLETE**;
- Tamil source layer: **PASSED**;
- assembled Tamil: **NEXT**;
- English: **BLOCKED**.

## Whole-work Tamil audit findings

The Section 12 audit reconciled the complete page inventory, source/work metadata, printed-page mapping, physical continuity, non-body separation, unresolved-item state and source-exclusion policy.

Important durable findings:

- scan 6 remains `printed_page: null`; no printed `1` is inferred;
- scans 7–13 visibly print pages **2–8**;
- scan 14 visibly prints page **10**, so the source has a visible numbering jump **8 → 10**;
- no synthetic printed page 9 is inserted;
- physical narrative continuity across scans 13→14 is directly preserved: `ஊற்றெடுத்துக் கிளம்பிவரும்` / `அருவி!`;
- scan 23 is the final physical page of `அரும்பு`; no explicit `முற்றும்` is printed;
- source-confirmed unusual readings scan 22 `பேசினேன்` and scan 23 `அம்மனார்` remain unchanged;
- all historical-glyph/source-fidelity issues are resolved: **0 unresolved**;
- the controlling source PDF is absent from the live repository tree;
- no source-backed chapter divisions were identified inside `அரும்பு`, so the assembled layer must not invent chapters.

## Exact next activity

Execute the **assembled Tamil reading layer for `அரும்பு` only** under `NOVEL_PROCESSING_GUIDE.md` Section 13:

- create `works/arumbu/sections/README.md`;
- create `works/arumbu/sections/01-arumbu.md` as one continuous reading section unless direct source structure proves otherwise;
- derive only from the **18 verified canonical page records** — do not re-transcribe;
- preserve source spelling, punctuation, paragraph structure, rhetoric and documented oddities;
- resolve only already-established cross-page continuations in the reading layer and retain reversible source-page provenance comments;
- do not invent chapter divisions or a missing printed page 9;
- synchronize work/root controls and commit the assembled-Tamil checkpoint;
- stop before English translation and before `சாரப்பள்ளம் சாமுண்டி`.
