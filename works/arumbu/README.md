# அரும்பு

**ஆசிரியர்:** கலைஞர் மு. கருணாநிதி  
**Source volume:** `அரும்பு` — தமிழ்க்கனி பதிப்பகம், முதற் பதிப்பு 1978  
**Source physical range:** scans **6–23** of `TVA_BOK_0064361_அரும்பு.pdf`  
**Source PDF committed:** No

## Current state

- work identity: **CONFIRMED from component title page**;
- collection/source intake: **COMPLETE**;
- physical component span: **18 scans**;
- canonical page records: **15 / 18 — scans 6–20**;
- verified pages: **10 / 18 — scans 6–15 contiguous**;
- scans 6–10 T1/T2/T3: **PASS / COMPLETE**;
- scans 11–15 T1/T2/T3: **PASS / COMPLETE**;
- scans 16–20 T1 direct visual transcription: **PASS / COMPLETE**;
- scans 16–20 page status: **5 `needs-review`**;
- scans 16–20 T2 historical-glyph re-read: **NEXT**;
- scans 16–20 T3 final source-fidelity closure: **BLOCKED by T2**;
- scans 21–23: **not started**;
- assembled Tamil: **BLOCKED**;
- English: **BLOCKED**.

This work is the first component of the 1978 four-story compilation and shares its title with the volume itself. Collection provenance is recorded at `../../collections/arumbu-1978/`.

## Active checkpoint workflow

Source batches follow root [`SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`](../../SOURCE_BATCH_CHECKPOINT_WORKFLOW.md):

1. **T1** — one direct visual transcription pass + canonical records + exact visible numbering → control sync → commit → stop;
2. **T2** — independent historical-glyph / character-identity re-read → control sync → commit → stop;
3. **T3** — exhaustive final source-fidelity closure → control sync → commit → stop;
4. only after T3 may the next batch begin.

T1 must not absorb repeated character-level crop loops, historical-glyph verification, or exhaustive T3 checking.

## Closed batches

### Scans 6–10

- [`T1_BATCH_006_010.md`](T1_BATCH_006_010.md) — PASS;
- [`T2_BATCH_006_010.md`](T2_BATCH_006_010.md) — PASS, 4 character-identity corrections / 0 unresolved;
- [`T3_BATCH_006_010.md`](T3_BATCH_006_010.md) — PASS, 19 additional source-fidelity corrections / 0 unresolved;
- five records — **VERIFIED**.

### Scans 11–15

- [`T1_BATCH_011_015.md`](T1_BATCH_011_015.md) — PASS;
- [`T2_BATCH_011_015.md`](T2_BATCH_011_015.md) — PASS, 1 historical `ளை` correction / 0 unresolved;
- [`T3_BATCH_011_015.md`](T3_BATCH_011_015.md) — PASS, 2 additional source-fidelity corrections / 0 unresolved;
- five records — **VERIFIED**.

## Active batch — scans 16–20

[`T1_BATCH_016_020.md`](T1_BATCH_016_020.md) — **PASS / COMPLETE**.

Directly visible printed pages are **12, 13, 14, 15, 16**. All five new records remain `needs-review` because T2 and T3 have not run.

Preserved physical joins:

- 15→16 `செல்லக்` / `குழந்தையை—...`;
- 16→17 `அவர்களைக்-` / `கவனிக்கிறான்.`;
- 18→19 `செலவா` / `யிற்று.`;
- 19→20 `கடிந்துகொண்` / `டிருக்கிறாள்.`.

## Exact next activity

**T2 for physical scans 16–20 only.** Independently re-read the five complete pages under `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`, correct only source-supported character identity, record corrections/unresolved forms, synchronize controls, commit T2, and stop before T3. Do not begin scan 21.
