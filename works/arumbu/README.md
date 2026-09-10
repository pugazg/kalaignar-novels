# அரும்பு

**ஆசிரியர்:** கலைஞர் மு. கருணாநிதி  
**Source volume:** `அரும்பு` — தமிழ்க்கனி பதிப்பகம், முதற் பதிப்பு 1978  
**Source physical range:** scans **6–23** of `TVA_BOK_0064361_அரும்பு.pdf`  
**Source PDF committed:** No

## Current state

- work identity: **CONFIRMED from component title page**;
- collection/source intake: **COMPLETE**;
- physical component span: **18 scans**;
- canonical page records: **0 / 18**;
- transcription: **NOT STARTED**;
- historical-glyph/source audit: **NOT STARTED**;
- assembled Tamil: **BLOCKED**;
- English: **BLOCKED**.

This work is the first component of the 1978 four-story compilation and shares its title with the volume itself. Collection provenance is recorded at `../../collections/arumbu-1978/`.

## Active checkpoint workflow

Source batches now follow root [`SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`](../../SOURCE_BATCH_CHECKPOINT_WORKFLOW.md). A five-scan batch is not completed in one large operation.

For each bounded batch:

1. **T1 — direct transcription / canonical records** → synchronize controls → commit;
2. **T2 — independent historical-glyph re-read** → synchronize controls → commit;
3. **T3 — final source-fidelity closure** → synchronize controls → commit;
4. only after T3 may the next batch begin.

Crops/enhancements are created only for genuinely uncertain readings.

## Exact next activity

**T1 for physical scans 6–10 only.**

- visually transcribe each whole page once;
- create one canonical page record per scan;
- preserve printed-page visibility exactly: scan 6 remains `null`; scans 7–10 use only the directly visible printed numbers;
- preserve illustrations/non-body material separately;
- leave the records non-final (`needs-review`) because T2 and T3 have not yet run;
- synchronize controls and commit immediately;
- stop before the independent historical-glyph re-read.

Do not begin scan 11 or another component in the same checkpoint.
