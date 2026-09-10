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
- scans 16–20 T1: **PASS / COMPLETE**;
- scans 16–20 T2: **PASS / COMPLETE — 1 correction / 0 unresolved**;
- scans 16–20 T3: **PASS / COMPLETE — 11 additional corrections / 0 unresolved**;
- scans 21–23 T1: **PASS / COMPLETE**;
- scans 21–23 T2: **PASS / COMPLETE — 0 corrections / 0 unresolved**;
- scans 21–23 T3: **PASS / COMPLETE — 4 additional corrections / 0 unresolved**;
- page-level source gates: **PASS / COMPLETE — 18 / 18 VERIFIED**;
- whole-work Tamil audit: **NEXT**;
- assembled Tamil: **BLOCKED by whole-work Tamil audit**;
- English: **BLOCKED**.

This is the first component of the 1978 four-story compilation. Collection provenance is recorded at `../../collections/arumbu-1978/`.

## Checkpoint workflow

Source batches follow [`SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`](../../SOURCE_BATCH_CHECKPOINT_WORKFLOW.md): T1 direct transcription → sync/commit/stop; T2 independent historical-glyph re-read → sync/commit/stop; T3 final source-fidelity closure → sync/commit/stop.

## Closed batches

### Scans 6–10

T1/T2/T3 **PASS / COMPLETE**; five records **VERIFIED**. T2: 4 corrections; T3: 19 additional corrections; unresolved: 0.

### Scans 11–15

T1/T2/T3 **PASS / COMPLETE**; five records **VERIFIED**. T2: 1 correction; T3: 2 additional corrections; unresolved: 0.

### Scans 16–20

- [`T1_BATCH_016_020.md`](T1_BATCH_016_020.md) — PASS;
- [`T2_BATCH_016_020.md`](T2_BATCH_016_020.md) — PASS, 1 character-identity correction / 0 unresolved;
- [`T3_BATCH_016_020.md`](T3_BATCH_016_020.md) — PASS, 11 additional source-fidelity corrections / 0 unresolved;
- five records — **VERIFIED**.

### Scans 21–23 — CLOSED / VERIFIED

- [`T1_BATCH_021_023.md`](T1_BATCH_021_023.md) — **PASS / COMPLETE**;
- [`T2_BATCH_021_023.md`](T2_BATCH_021_023.md) — **PASS / COMPLETE — 0 corrections / 0 unresolved**;
- [`T3_BATCH_021_023.md`](T3_BATCH_021_023.md) — **PASS / COMPLETE — 4 corrections / 0 unresolved**;
- canonical records — scans 21, 22, 23 / printed pages **17, 18, 19** — all **VERIFIED**;
- T3 corrected scan-21 punctuation `பார்த்தான்:` / `கிடந்தன:` to source periods, scan-22 `ஆஸ்பத்திரியிலே` → `ஆஸ்பத்திரியில்`, and scan-23 final `இனி......` → `இனி:......`;
- T2-confirmed `பேசினேன்` and `அம்மனார்` remain source-faithful and unchanged;
- scan 23 is the final physical page of `அரும்பு`; no explicit `முற்றும்` is printed.

Preserved final continuity:

- 20→21: `அவனது அம்மா படம்!` → `அதை எடுத்து...`;
- 21→22: `அப்பா பாப்பாவை நினைத்து` → `அழுதுகொண்டே யிருக்கிறாரே!`;
- 22→23: completed sentence → new paragraph `அவளையறியாமல்,...`.

## Exact next activity

Run the **whole-work Tamil audit gate for `அரும்பு` only** under `NOVEL_PROCESSING_GUIDE.md` Section 12. Reconcile all 18 canonical records, the page map, metadata, structural identity, page-number evidence, cross-page continuity, unresolved-item state, historical-glyph coverage and source-PDF exclusion. Confirm that no silent modernization/correction remains and record a clear PASS/hold result. Stop before assembled Tamil, English, or `சாரப்பள்ளம் சாமுண்டி`.
