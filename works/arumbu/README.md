# அரும்பு

**ஆசிரியர்:** கலைஞர் மு. கருணாநிதி  
**Source volume:** `அரும்பு` — தமிழ்க்கனி பதிப்பகம், முதற் பதிப்பு 1978  
**Source physical range:** scans **6–23** of `TVA_BOK_0064361_அரும்பு.pdf`  
**Source PDF committed:** No

## Current state

- work identity: **CONFIRMED**;
- collection/source intake: **COMPLETE**;
- physical component span: **18 scans**;
- canonical page records: **18 / 18 — scans 6–23**;
- verified pages: **18 / 18 — scans 6–23 contiguous**;
- scans 6–10 T1/T2/T3: **PASS / COMPLETE**;
- scans 11–15 T1/T2/T3: **PASS / COMPLETE**;
- scans 16–20 T1/T2/T3: **PASS / COMPLETE**;
- scans 21–23 T1/T2/T3: **PASS / COMPLETE**;
- whole-work Tamil audit: **PASS / COMPLETE**;
- Tamil source layer: **PASSED**;
- assembled Tamil: **1 / 1 section — PASSED**;
- English translation plan: **PASS / COMPLETE**;
- English prose: **NOT STARTED**;
- next English checkpoint: **Batch 1 pilot — scans 6–10**.

This is the first component of the 1978 four-story compilation. Collection provenance is recorded at `../../collections/arumbu-1978/`.

## Checkpoint workflow

Source batches followed [`SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`](../../SOURCE_BATCH_CHECKPOINT_WORKFLOW.md): T1 direct transcription → sync/commit/stop; T2 independent historical-glyph re-read → sync/commit/stop; T3 final source-fidelity closure → sync/commit/stop. After all 18 pages closed, the separate Section 12 whole-work Tamil audit passed before the Section 13 reading layer was derived.

## Closed source batches

### Scans 6–10

T1/T2/T3 **PASS / COMPLETE**; five records **VERIFIED**. T2: 4 corrections; T3: 19 additional corrections; unresolved: 0.

### Scans 11–15

T1/T2/T3 **PASS / COMPLETE**; five records **VERIFIED**. T2: 1 correction; T3: 2 additional corrections; unresolved: 0.

### Scans 16–20

T1/T2/T3 **PASS / COMPLETE**; five records **VERIFIED**. T2: 1 character-identity correction; T3: 11 additional source-fidelity corrections; unresolved: 0.

### Scans 21–23

- [`T1_BATCH_021_023.md`](T1_BATCH_021_023.md) — **PASS / COMPLETE**;
- [`T2_BATCH_021_023.md`](T2_BATCH_021_023.md) — **PASS / COMPLETE — 0 corrections / 0 unresolved**;
- [`T3_BATCH_021_023.md`](T3_BATCH_021_023.md) — **PASS / COMPLETE — 4 corrections / 0 unresolved**;
- three records — **VERIFIED**;
- directly visible printed pages: **17, 18, 19**;
- scan 23 is the final physical page; no explicit `முற்றும்` is printed.

Source-confirmed unusual readings `பேசினேன்` (scan 22) and `அம்மனார்` (scan 23) remain unchanged.

## Whole-work Tamil audit

**PASS / COMPLETE.** See [`audit.md`](audit.md).

The audit confirms complete contiguous physical coverage, source-supported printed-page mapping, source-PDF exclusion, 0 unresolved historical glyphs, 0 unresolved source readings, and no source-backed chapter divisions.

The visible printed-page jump scan 13 / printed 8 → scan 14 / printed 10 is preserved without inventing printed page 9. Physical narrative continuity remains `ஊற்றெடுத்துக் கிளம்பிவரும்` → `அருவி!`.

## Assembled Tamil reading layer

**PASS / COMPLETE — 1 / 1 section.**

- [`sections/README.md`](sections/README.md) records derivation, authority, section coverage and assembly verification;
- [`sections/01-arumbu.md`](sections/01-arumbu.md) covers physical scans **6–23** as one continuous source-faithful reading section;
- the layer is derived only from the audited canonical `pages/` records; canonical page files were not changed;
- verified cross-page fragments are joined only for readability and remain reversible through inline source-provenance comments;
- source-confirmed `பேசினேன்`, `அம்மனார்`, and final `இனி:......` are retained unchanged;
- no artificial chapter divisions and no unprinted `முற்றும்` were added.

## English translation plan

**SECTION 14 — PASS / COMPLETE.**

English controls now live under [`translations/en/`](translations/en/):

- [`TRANSLATION_PLAN.md`](translations/en/TRANSLATION_PLAN.md) — governing plan;
- [`README.md`](translations/en/README.md) — planned-state summary;
- [`PROGRESS.md`](translations/en/PROGRESS.md) — batch progress;
- [`GLOSSARY.md`](translations/en/GLOSSARY.md) — provisional/protected terminology;
- [`PLAN_CHECKPOINT.md`](translations/en/PLAN_CHECKPOINT.md) — durable planning checkpoint.

Working English title: **The Bud**.

The final English structure remains one section, but prose will be produced in four controlled source-aligned batches: **6–10**, **11–15**, **16–20**, **21–23**. Batch 1 is the mandatory pilot. Audited `pages/` remain final textual authority; assembled Tamil is continuity support.

The plan explicitly protects scan 22 `பேசினேன்`, scan 23 `அம்மனார்`, final `இனி:......`, the printed-page 8→10 jump, and the absence of explicit `முற்றும்` from silent normalization.

## Exact next activity

Execute **English Batch 1 pilot — scans 6–10 only**:

- translate only audited Tamil for scans **6–10**;
- create/update `translations/en/sections/01-arumbu.md` for the pilot span;
- retain reversible scan/page provenance;
- source-check English back against canonical page records `0006`–`0010`;
- lock applicable name, terminology, cultural-term, punctuation and dialogue decisions in `GLOSSARY.md`;
- update `translations/en/README.md` and `PROGRESS.md`;
- mark Batch 1 `reviewed` only after source comparison;
- synchronize controls, commit, and stop before Batch 2;
- do **not** begin `சாரப்பள்ளம் சாமுண்டி` or the 1978 `பெரிய இடத்துப் பெண்` witness comparison.
