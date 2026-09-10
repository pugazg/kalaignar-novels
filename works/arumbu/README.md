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
- assembled Tamil: **NEXT**;
- English: **BLOCKED**.

This is the first component of the 1978 four-story compilation. Collection provenance is recorded at `../../collections/arumbu-1978/`.

## Checkpoint workflow

Source batches followed [`SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`](../../SOURCE_BATCH_CHECKPOINT_WORKFLOW.md): T1 direct transcription → sync/commit/stop; T2 independent historical-glyph re-read → sync/commit/stop; T3 final source-fidelity closure → sync/commit/stop. After all 18 pages closed, the separate Section 12 whole-work Tamil audit was completed before any reading-layer derivation.

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

The audit confirms:

- complete contiguous physical coverage for scans **6–23** and **18 / 18 VERIFIED** page records;
- collection/work metadata agreement and source-PDF exclusion;
- source-supported printed-page mapping, including scan 6 unnumbered and the visible scan 13→14 printed-number jump **8 → 10** without inventing page 9;
- physical narrative continuity across that jump (`ஊற்றெடுத்துக் கிளம்பிவரும்` → `அருவி!`);
- historical-glyph and final source-fidelity unresolved counts both **0**;
- source spelling, punctuation, period forms and unusual readings preserved without silent modernization;
- no source-backed chapter divisions requiring multiple assembled sections.

## Exact next activity

Create the **assembled Tamil reading layer only**:

- `sections/README.md`;
- `sections/01-arumbu.md` as a continuous source-faithful reading layer unless direct structure evidence requires otherwise;
- derive only from verified canonical `pages/` records;
- preserve source wording and retain reversible page provenance comments;
- join only already-established cross-page continuations;
- do not invent chapters or begin English translation;
- synchronize controls and commit, then stop before `சாரப்பள்ளம் சாமுண்டி`.
