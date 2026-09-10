# அரும்பு

**ஆசிரியர்:** கலைஞர் மு. கருணாநிதி  
**Source volume:** `அரும்பு` — தமிழ்க்கனி பதிப்பகம், முதற் பதிப்பு 1978  
**Source physical range:** scans **6–23** of `TVA_BOK_0064361_அரும்பு.pdf`  
**Source PDF committed:** No

## Current state

- work identity: **CONFIRMED from component title page**;
- collection/source intake: **COMPLETE**;
- physical component span: **18 scans**;
- canonical page records: **5 / 18** — scans **6–10**;
- scans 6–10 T1 direct visual transcription: **PASS / COMPLETE**;
- scans 6–10 T2 historical-glyph re-read: **PASS / COMPLETE**;
- scans 6–10 T3 final source-fidelity closure: **PASS / COMPLETE**;
- verified pages: **5 / 18**;
- unresolved source readings in verified range: **0**;
- next bounded batch: **scans 11–15 / T1 NEXT**;
- assembled Tamil: **BLOCKED**;
- English: **BLOCKED**.

This work is the first component of the 1978 four-story compilation and shares its title with the volume itself. Collection provenance is recorded at `../../collections/arumbu-1978/`.

## Active checkpoint workflow

Source batches follow root [`SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`](../../SOURCE_BATCH_CHECKPOINT_WORKFLOW.md). Each bounded source batch is processed through three separately durable checkpoints:

1. **T1 — direct transcription / canonical records** → synchronize controls → commit;
2. **T2 — independent historical-glyph re-read** → synchronize controls → commit;
3. **T3 — final source-fidelity closure** → synchronize controls → commit;
4. only after T3 may the next batch begin.

Crops/enhancements are created only for genuinely uncertain readings.

## Closed batch — scans 6–10

Checkpoint records:

- [`T1_BATCH_006_010.md`](T1_BATCH_006_010.md) — PASS;
- [`T2_BATCH_006_010.md`](T2_BATCH_006_010.md) — PASS, 4 character-identity corrections / 0 unresolved;
- [`T3_BATCH_006_010.md`](T3_BATCH_006_010.md) — PASS, 19 additional source-fidelity corrections / 0 unresolved.

Printed-page visibility is preserved exactly: scan 6 `null`; scans 7–10 show **2, 3, 4, 5**.

Physical joins remain in their source records:

- 7→8 `நடந்` / `தேறின.`;
- 8→9 `அபிநய` / `அசைவுகளை...`;
- 9→10 `...வைத்தியரை அழைத்து` / `வந்துவிடுகிறேன்”...`.

All five canonical records are now **VERIFIED**.

## Exact next activity

**T1 for physical scans 11–15 only.**

- visually transcribe each whole source page once;
- create one canonical record per scan under `pages/`;
- record a printed page number only when directly visible; never infer missing numbering from sequence;
- preserve page-boundary fragments, illustrations and non-body material exactly;
- leave the new records `needs-review` because their T2/T3 checkpoints will still be pending;
- synchronize controls and commit T1 immediately;
- stop before T2 for scans 11–15.

Do not begin scan 16 or another component in the same checkpoint.
