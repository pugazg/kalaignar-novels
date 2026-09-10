# Audit — அரும்பு

## Gate state

| Stage | Status |
|---|---|
| Collection/source intake | **PASS / COMPLETE** |
| Work identity / scan boundary | **PASS — scans 6–23** |
| Page-level Tamil transcription | **COMPLETE — 18 / 18 canonical records** |
| Scans 6–10 T1/T2/T3 | **PASS / COMPLETE — VERIFIED** |
| Scans 11–15 T1/T2/T3 | **PASS / COMPLETE — VERIFIED** |
| Scans 16–20 T1/T2/T3 | **PASS / COMPLETE — VERIFIED** |
| Scans 21–23 T1/T2/T3 | **PASS / COMPLETE — VERIFIED** |
| Verified canonical pages | **18 / 18 — scans 6–23 contiguous** |
| Historical-glyph unresolved items | **0** |
| Source-fidelity unresolved items | **0** |
| Whole-work Tamil audit | **PASS / COMPLETE** |
| Tamil source layer | **PASSED** |
| Assembled Tamil | **PASS / COMPLETE — 1 / 1 section** |
| English translation plan | **PASS / COMPLETE** |
| English prose | **NOT STARTED** |
| Next English checkpoint | **Batch 1 pilot — scans 6–10** |

No source PDF is committed.

## Checkpoint model

Bounded source work followed root `SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`: T1 direct visual first pass, T2 independent historical-glyph / character-identity re-read, and T3 final source-fidelity closure. Every bounded checkpoint was synchronized and committed separately. After full page-level closure, the separate whole-work Tamil audit required by `NOVEL_PROCESSING_GUIDE.md` Section 12 passed before the Section 13 assembled reading layer was created.

## Closed page-level batches

All four source ranges are closed:

- scans **6–10** — T1/T2/T3 PASS / VERIFIED;
- scans **11–15** — T1/T2/T3 PASS / VERIFIED;
- scans **16–20** — T1/T2/T3 PASS / VERIFIED;
- scans **21–23** — T1/T2/T3 PASS / VERIFIED.

Across the component, the dedicated T2 passes made **6 source-supported character-identity corrections** and left **0 unresolved historical glyphs**. The T3 passes made **36 additional source-fidelity corrections** and left **0 unresolved source readings**.

Final-batch source-confirmed unusual readings remain unchanged: scan 22 **`பேசினேன்`** and scan 23 **`அம்மனார்`**. They were not context-normalized.

## Whole-work Tamil audit — PASS / COMPLETE

The Section 12 Tamil audit reconciled the controlling 1978 compilation, work metadata, page map, all closed T1/T2/T3 batch records, and all 18 verified canonical page records.

Durable findings:

- physical work span: **scans 6–23**, exactly **18 scans**;
- canonical / verified records: **18 / 18**;
- scan 6 has no visibly printed page number and remains `null`;
- scans 7–13 visibly print **2–8**;
- scan 14 visibly prints **10**;
- scans 15–23 visibly print **11–19**;
- no synthetic printed page 9 is inserted;
- physical continuity across 13→14 is `ஊற்றெடுத்துக் கிளம்பிவரும்` → `அருவி!`;
- scan 23 is the final page and has no explicit `முற்றும்`;
- no source-backed chapter divisions exist;
- historical-glyph unresolved items: **0**;
- source-fidelity unresolved items: **0**;
- controlling PDF remains excluded from the repository.

**TAMIL SOURCE AUDIT — PASS / COMPLETE.**

## Assembled Tamil reading layer — PASS / COMPLETE

Section 13 was completed only after the Tamil source audit passed.

Artifacts:

- `sections/README.md` — derivation/authority, section inventory, join inventory and verification record;
- `sections/01-arumbu.md` — one continuous reading section covering scans **6–23**.

Checks passed:

- scans **6–23** represented once and in source order;
- **18 / 18** canonical records represented;
- no artificial chapter split;
- only previously established page continuations joined;
- reversible scan/page provenance retained;
- printed-page 8→10 jump preserved without inventing 9;
- `பேசினேன்`, `அம்மனார்`, and `இனி:......` retained;
- no unprinted `முற்றும்` added;
- canonical `pages/` unchanged.

**ASSEMBLED TAMIL READING LAYER — PASS / COMPLETE.**

## Section 14 English translation plan — PASS / COMPLETE

The required translation plan now exists at `translations/en/TRANSLATION_PLAN.md`.

Planning decisions:

- working English title: **The Bud**;
- final English reading structure: **one section**, matching the audited Tamil structure;
- controlled source-aligned translation batches: **6–10**, **11–15**, **16–20**, **21–23**;
- Batch 1 is the mandatory pilot;
- audited `pages/` are final textual authority; assembled Tamil is continuity support;
- names/transliteration, cultural/ritual terminology, dialogue/punctuation, child register and recurring `அரும்பு` / bud imagery have explicit policies;
- scan 22 `பேசினேன்`, scan 23 `அம்மனார்`, scan 23 `இனி:......`, the visible printed-page 8→10 jump and the absence of `முற்றும்` are protected from silent normalization;
- `translations/en/README.md`, `PROGRESS.md`, `GLOSSARY.md` and `PLAN_CHECKPOINT.md` are initialized;
- **no English prose has been created**.

**SECTION 14 ENGLISH TRANSLATION PLAN — PASS / COMPLETE.**

## Exact next activity

Execute **English Batch 1 pilot — scans 6–10 only** under `NOVEL_PROCESSING_GUIDE.md` Section 15:

- translate only audited Tamil for scans **6–10**;
- write the pilot span into `translations/en/sections/01-arumbu.md`;
- preserve scan/page provenance;
- source-check every translated paragraph back against canonical page records 0006–0010;
- update/lock applicable `GLOSSARY.md` decisions;
- update `translations/en/README.md` and `PROGRESS.md`;
- mark Batch 1 `reviewed` only after source comparison;
- synchronize controls and commit;
- stop before Batch 2, `சாரப்பள்ளம் சாமுண்டி`, or the 1978 `பெரிய இடத்துப் பெண்` witness comparison.
