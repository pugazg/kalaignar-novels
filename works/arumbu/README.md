# அரும்பு

**ஆசிரியர்:** கலைஞர் மு. கருணாநிதி  
**Source volume:** `அரும்பு` — தமிழ்க்கனி பதிப்பகம், முதற் பதிப்பு 1978  
**Source physical range:** scans **6–23** of `TVA_BOK_0064361_அரும்பு.pdf`  
**Source PDF committed:** No

## Current state

- work identity: **CONFIRMED from component title page**;
- collection/source intake: **COMPLETE**;
- physical component span: **18 scans**;
- canonical page records: **10 / 18 — scans 6–15**;
- verified pages: **10 / 18 — scans 6–15 contiguous**;
- scans 6–10 T1/T2/T3: **PASS / COMPLETE**;
- scans 11–15 T1: **PASS / COMPLETE**;
- scans 11–15 T2: **PASS / COMPLETE — 1 historical-glyph correction / 0 unresolved**;
- scans 11–15 T3: **PASS / COMPLETE — 2 source-fidelity corrections / 0 unresolved**;
- next bounded batch: **scans 16–20 / T1 NEXT**;
- assembled Tamil: **BLOCKED**;
- English: **BLOCKED**.

This work is the first component of the 1978 four-story compilation and shares its title with the volume itself. Collection provenance is recorded at `../../collections/arumbu-1978/`.

## Active checkpoint workflow

Source batches follow root [`SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`](../../SOURCE_BATCH_CHECKPOINT_WORKFLOW.md):

1. **T1** — one direct visual transcription pass + canonical records + exact visible numbering → control sync → commit → stop;
2. **T2** — independent historical-glyph / character-identity re-read → control sync → commit → stop;
3. **T3** — final source-fidelity closure → control sync → commit → stop;
4. only after T3 may the next batch begin.

T1 must not absorb repeated character-level crop loops, historical-glyph verification, or exhaustive T3 checking.

## Closed batch — scans 6–10

- [`T1_BATCH_006_010.md`](T1_BATCH_006_010.md) — PASS;
- [`T2_BATCH_006_010.md`](T2_BATCH_006_010.md) — PASS, 4 character-identity corrections / 0 unresolved;
- [`T3_BATCH_006_010.md`](T3_BATCH_006_010.md) — PASS, 19 additional source-fidelity corrections / 0 unresolved;
- five records — **VERIFIED**.

## Closed batch — scans 11–15

- [`T1_BATCH_011_015.md`](T1_BATCH_011_015.md) — PASS;
- [`T2_BATCH_011_015.md`](T2_BATCH_011_015.md) — PASS, 1 historical `ளை` correction / 0 unresolved;
- [`T3_BATCH_011_015.md`](T3_BATCH_011_015.md) — PASS, 2 additional source-fidelity corrections / 0 unresolved;
- five records — **VERIFIED**.

Directly visible printed pages in scans 11–15 are **6, 7, 8, 10, 11**; printed page 9 is not inferred. Scan 13's illustration remains separate from narrative text.

Preserved physical joins/edges:

- 11→12 `போய்` / `விட்டனர்.`;
- 13→14 `ஊற்றெடுத்துக் கிளம்பிவரும்` / `அருவி!`;
- scan 15 ends physically at `செல்லக்`; its continuation was not inferred during the closed batch.

## Exact next activity

**T1 for physical scans 16–20 only.**

Visually transcribe each whole page once, create one `needs-review` canonical record per scan, record only directly visible printed-page numbers, preserve physical joins/non-body material, synchronize controls, commit T1 immediately, and stop before T2. Do not begin scan 21 in the same checkpoint.
