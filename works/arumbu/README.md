# அரும்பு

**ஆசிரியர்:** கலைஞர் மு. கருணாநிதி  
**Source volume:** `அரும்பு` — தமிழ்க்கனி பதிப்பகம், முதற் பதிப்பு 1978  
**Source physical range:** scans **6–23** of `TVA_BOK_0064361_அரும்பு.pdf`  
**Source PDF committed:** No

## Current state

- work identity: **CONFIRMED from component title page**;
- collection/source intake: **COMPLETE**;
- physical component span: **18 scans**;
- canonical page records: **10 / 18** — scans **6–15**;
- verified pages: **5 / 18** — scans **6–10**;
- scans 6–10 T1/T2/T3: **PASS / COMPLETE**;
- scans 11–15 T1 direct visual transcription: **PASS / COMPLETE**;
- scans 11–15 page status: **5 `needs-review`**;
- scans 11–15 T2 historical-glyph re-read: **NEXT**;
- scans 11–15 T3 final source-fidelity closure: **BLOCKED by T2**;
- unresolved source readings in verified range: **0**;
- assembled Tamil: **BLOCKED**;
- English: **BLOCKED**.

This work is the first component of the 1978 four-story compilation and shares its title with the volume itself. Collection provenance is recorded at `../../collections/arumbu-1978/`.

## Active checkpoint workflow

Source batches follow root [`SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`](../../SOURCE_BATCH_CHECKPOINT_WORKFLOW.md). Each bounded batch is processed as three separately committed checkpoints:

1. **T1 — one direct visual transcription pass + canonical records + exact visible numbering** → synchronize controls → commit → stop;
2. **T2 — independent historical-glyph re-read** → synchronize controls → commit → stop;
3. **T3 — exhaustive final source-fidelity closure** → synchronize controls → commit → stop;
4. only after T3 may the next batch begin.

T1 must not absorb repeated character-level crop loops, the historical-glyph gate, or exhaustive fidelity checking. A difficult first-pass reading may remain `needs-review` for T2/T3 rather than delaying the T1 commit.

## Closed batch — scans 6–10

- [`T1_BATCH_006_010.md`](T1_BATCH_006_010.md) — PASS;
- [`T2_BATCH_006_010.md`](T2_BATCH_006_010.md) — PASS, 4 character-identity corrections / 0 unresolved;
- [`T3_BATCH_006_010.md`](T3_BATCH_006_010.md) — PASS, 19 additional source-fidelity corrections / 0 unresolved;
- all five canonical records — **VERIFIED**.

## Active batch — scans 11–15

[`T1_BATCH_011_015.md`](T1_BATCH_011_015.md) — **PASS / COMPLETE**.

Directly visible printed pages are **6, 7, 8, 10, 11**. The missing visible `9` is not inferred or invented.

Preserved physical joins:

- 11→12 `போய்` / `விட்டனர்.`;
- 13→14 `ஊற்றெடுத்துக் கிளம்பிவரும்` / `அருவி!`;
- scan 15 ends physically at `செல்லக்`; scan 16 was not inspected during T1.

Scan 13's large printed illustration is documented separately from narrative text. All five new records remain `needs-review` because T2 and T3 have not run.

## Exact next activity

**T2 for physical scans 11–15 only.** Independently re-read the five complete pages under `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`, correct only source-supported character identity, record corrections/unresolved forms, synchronize controls, commit T2, and stop before T3. Do not begin scan 16.
