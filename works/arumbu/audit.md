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
| Assembled Tamil | **NEXT** |
| English | BLOCKED until assembled Tamil is complete |

No source PDF is committed.

## Checkpoint model

Bounded source work followed root `SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`: T1 direct visual first pass, T2 independent historical-glyph / character-identity re-read, and T3 final source-fidelity closure. Every bounded checkpoint was synchronized and committed separately. After full page-level closure, this document records the separate whole-work Tamil audit required by `NOVEL_PROCESSING_GUIDE.md` Section 12.

## Closed page-level batches

All four source ranges are closed:

- scans **6–10** — T1/T2/T3 PASS / VERIFIED;
- scans **11–15** — T1/T2/T3 PASS / VERIFIED;
- scans **16–20** — T1/T2/T3 PASS / VERIFIED;
- scans **21–23** — T1/T2/T3 PASS / VERIFIED.

Across the component, the dedicated T2 passes made **6 source-supported character-identity corrections** and left **0 unresolved historical glyphs**. The T3 passes made **36 additional source-fidelity corrections** and left **0 unresolved source readings**.

Final-batch source-confirmed unusual readings remain unchanged: scan 22 **`பேசினேன்`** and scan 23 **`அம்மனார்`**. They were not context-normalized.

## Whole-work Tamil audit — PASS / COMPLETE

The Section 12 Tamil audit was reconciled against the controlling 1978 compilation, work metadata, page map, all closed T1/T2/T3 batch records, and the 18 verified canonical page records.

### Inventory and coverage

- physical work span: **scans 6–23**, exactly **18 scans**;
- canonical records: **18 / 18**;
- verified records: **18 / 18**;
- physical scan coverage is contiguous with no repository record gap;
- all body pages have completed direct visual source review through T3.

### Source identity and metadata

The work metadata agrees with the registered collection source:

- `TVA_BOK_0064361_அரும்பு.pdf`;
- SHA-256 `04a3013e1f58a1800867acc5d2f159976c47994a64478036e6fe0201edf120bc`;
- **92** physical scans in the compilation;
- `அரும்பு` component at scans **6–23**;
- தமிழ்க்கனி பதிப்பகம், சென்னை-28;
- முதற் பதிப்பு — **1978**.

The volume title and first component story share the title `அரும்பு`; collection and work identities remain separately represented.

### Printed-page mapping

Printed numbers are recorded only when directly visible:

- scan 6 — `null`; opening page has no clearly visible printed number and none is inferred;
- scans 7–13 — printed **2–8**;
- scan 14 — printed **10**;
- scans 15–23 — printed **11–19**.

The visible numbering therefore jumps **8 → 10** between physical scans 13 and 14. No synthetic printed page 9 is inserted. Physical narrative continuity across that jump is directly preserved by scan 13 ending `ஊற்றெடுத்துக் கிளம்பிவரும்` and scan 14 beginning `அருவி!`.

### Continuity, structure and non-body separation

- all documented cross-page joins remain traceable in the physical page records and batch audits;
- final joins remain confirmed: 20→21 `அவனது அம்மா படம்!` / `அதை எடுத்து...`; 21→22 `அப்பா பாப்பாவை நினைத்து` / `அழுதுகொண்டே யிருக்கிறாரே!`; 22→23 completed sentence / new paragraph `அவளையறியாமல்,...`;
- scan 23 is the final physical page of `அரும்பு`; no explicit `முற்றும்` is printed;
- page type and narrative/non-body separation remain explicit; for example scan 21 footer `க. க—2` remains outside the narrative body;
- no source-backed chapter divisions are recorded inside this short work, so downstream assembly must not invent artificial chapters.

### Fidelity and unresolved-item state

- historical-glyph review: **complete, 0 unresolved**;
- final source-fidelity review: **complete, 0 unresolved**;
- source oddities and period forms are preserved rather than silently modernized;
- source-confirmed `பேசினேன்` and `அம்மனார்` demonstrate that contextual expectation did not override source pixels;
- no outstanding `needs-review` canonical page remains.

### Source exclusion

A recursive live-tree check at the page-level closure checkpoint found no repository path matching `TVA_BOK_0064361_அரும்பு.pdf`. The controlling PDF remains excluded from version control as required.

## Audit result

**TAMIL SOURCE AUDIT — PASS / COMPLETE.**

`அரும்பு` now has a fully verified source-level Tamil layer: **18 / 18 canonical records**, all page-level T1/T2/T3 gates closed, **0 unresolved historical glyphs**, and **0 unresolved source readings**.

This PASS opens the assembled Tamil reading-layer stage. It does not authorize English translation or the next compilation component in the same checkpoint.

## Exact next activity

Build the **assembled Tamil reading layer for `அரும்பு` only** under `NOVEL_PROCESSING_GUIDE.md` Section 13:

- create `works/arumbu/sections/README.md`;
- create a source-faithful continuous reading section, expected as `works/arumbu/sections/01-arumbu.md` unless direct structure evidence requires otherwise;
- derive only from the 18 audited canonical page records — do not re-transcribe;
- preserve source spelling, punctuation, paragraphs and documented unusual readings;
- join only positively established physical page continuations while retaining reversible page provenance comments;
- do not invent chapter divisions;
- synchronize controls, commit the assembled-Tamil checkpoint, and stop before English or `சாரப்பள்ளம் சாமுண்டி`.
