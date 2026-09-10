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

1. `அரும்பு` — scans **6–23** — `works/arumbu/` — **TAMIL SOURCE + ASSEMBLED TAMIL PASSED; ENGLISH TRANSLATION PLAN NEXT**.
2. `சாரப்பள்ளம் சாமுண்டி` — scans **24–48** — queued.
3. `பெரிய இடத்துப் பெண்` — scans **49–74** — additional 1978 witness only; existing controlling source/canonical freeze unchanged.
4. `நடுத்தெரு நாராயணி` — scans **75–90** — queued.

Scans 1–5 are collection front matter; scans 91–92 publisher catalogue/back-cover matter.

## Workflow

Root `SOURCE_BATCH_CHECKPOINT_WORKFLOW.md` governed bounded source batches: T1 direct visual transcription → sync/commit/stop; T2 independent historical-glyph re-read → sync/commit/stop; T3 final source-fidelity closure → sync/commit/stop.

`NOVEL_PROCESSING_GUIDE.md` Section 12 then required a separate whole-work Tamil audit. That audit passed for `அரும்பு`. Section 13 assembled Tamil has now also passed as one continuous source-faithful reading section.

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
- assembled Tamil: **PASS / COMPLETE — 1 / 1 section**;
- assembled section: `works/arumbu/sections/01-arumbu.md` — scans **6–23**;
- English translation plan: **NEXT**;
- English prose: **BLOCKED until the Section 14 plan exists**.

## Durable Tamil findings

The Section 12 audit reconciled the complete page inventory, source/work metadata, printed-page mapping, physical continuity, non-body separation, unresolved-item state and source-exclusion policy. Section 13 then derived the reading layer only from those audited records.

Important durable findings:

- scan 6 remains `printed_page: null`; no printed `1` is inferred;
- scans 7–13 visibly print pages **2–8**;
- scan 14 visibly prints page **10**, so the source has a visible numbering jump **8 → 10**;
- no synthetic printed page 9 is inserted;
- physical narrative continuity across scans 13→14 is directly preserved: `ஊற்றெடுத்துக் கிளம்பிவரும்` / `அருவி!`;
- scan 23 is the final physical page of `அரும்பு`; no explicit `முற்றும்` is printed;
- source-confirmed unusual readings scan 22 `பேசினேன்` and scan 23 `அம்மனார்` remain unchanged;
- scan 23 final punctuation `இனி:......` remains unchanged;
- all historical-glyph/source-fidelity issues are resolved: **0 unresolved**;
- the controlling source PDF is absent from the live repository tree;
- no source-backed chapter divisions were identified inside `அரும்பு`.

## Assembled Tamil checkpoint

`works/arumbu/sections/README.md` records derivation, authority, section inventory, verified joins and the assembly consistency check.

`works/arumbu/sections/01-arumbu.md`:

- covers scans **6–23** exactly once and in source order;
- is derived only from the **18 verified canonical page records**;
- preserves source wording, punctuation, paragraphing, dialogue, rhetoric and period forms;
- joins only page continuations already established during source audit;
- retains reversible HTML source-provenance comments;
- does not invent chapter divisions, printed page 9 or `முற்றும்`;
- leaves canonical `pages/` unchanged.

**ASSEMBLED TAMIL READING LAYER — PASS / COMPLETE.**

## Exact next activity

Execute the **Section 14 English translation planning checkpoint for `அரும்பு` only**:

- create `works/arumbu/translations/en/TRANSLATION_PLAN.md`;
- define working English title, source authority hierarchy, one-section/batch strategy, translation style, names/transliteration, political/religious/caste terminology handling where applicable, historical/colloquial terms, punctuation/dialogue policy, source-oddity policy, page traceability and review states;
- initialize only the minimum English control files required for a clean planned state if needed;
- the audited `pages/` layer remains final textual authority; assembled Tamil is reader-continuity support;
- do **not** begin English prose translation in the same checkpoint;
- do **not** begin `சாரப்பள்ளம் சாமுண்டி` or the 1978 `பெரிய இடத்துப் பெண்` witness comparison;
- synchronize work/root controls, commit the planning checkpoint, and stop.
