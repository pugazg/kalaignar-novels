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
- scans 11–15 T2 historical-glyph re-read: **PASS / COMPLETE — 1 correction / 0 unresolved**;
- scans 11–15 page status: **5 `needs-review`**;
- scans 11–15 T3 final source-fidelity closure: **NEXT**;
- unresolved historical glyphs in T2-complete range: **0**;
- unresolved source readings in verified range: **0**;
- assembled Tamil: **BLOCKED**;
- English: **BLOCKED**.

This work is the first component of the 1978 four-story compilation and shares its title with the volume itself. Collection provenance is recorded at `../../collections/arumbu-1978/`.

## Active checkpoint workflow

Source batches follow root [`SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`](../../SOURCE_BATCH_CHECKPOINT_WORKFLOW.md). Each bounded batch is processed as three separately committed checkpoints:

1. **T1 — one direct visual transcription pass + canonical records + exact visible numbering** → synchronize controls → commit → stop;
2. **T2 — independent historical-glyph / character-identity re-read** → synchronize controls → commit → stop;
3. **T3 — exhaustive final source-fidelity closure** → synchronize controls → commit → stop;
4. only after T3 may the next batch begin.

T1 must not absorb repeated character-level crop loops, the historical-glyph gate, or exhaustive fidelity checking. T2 is confined to independent glyph/character identity; T3 owns the exhaustive fidelity pass.

## Closed batch — scans 6–10

- [`T1_BATCH_006_010.md`](T1_BATCH_006_010.md) — PASS;
- [`T2_BATCH_006_010.md`](T2_BATCH_006_010.md) — PASS, 4 character-identity corrections / 0 unresolved;
- [`T3_BATCH_006_010.md`](T3_BATCH_006_010.md) — PASS, 19 additional source-fidelity corrections / 0 unresolved;
- all five canonical records — **VERIFIED**.

## Active batch — scans 11–15

- [`T1_BATCH_011_015.md`](T1_BATCH_011_015.md) — **PASS / COMPLETE**;
- [`T2_BATCH_011_015.md`](T2_BATCH_011_015.md) — **PASS / COMPLETE — 1 correction / 0 unresolved**;
- T3 — **NEXT**.

T2 corrected scan 12 `திருக்குவள நண்பன்` to source-supported **`திருக்குவளை நண்பன்`**, restoring the historical `ளை` identity. No other T2 character-identity correction was required.

Directly visible printed pages remain **6, 7, 8, 10, 11**. The missing visible `9` is not inferred or invented.

Preserved physical joins:

- 11→12 `போய்` / `விட்டனர்.`;
- 13→14 `ஊற்றெடுத்துக் கிளம்பிவரும்` / `அருவி!`;
- scan 15 ends physically at `செல்லக்`; scan 16 has not been inspected.

Scan 13's large printed illustration remains separate from narrative text. All five records remain `needs-review` until T3 passes.

## Exact next activity

**T3 for physical scans 11–15 only.** Perform the final source-fidelity closure for omissions, duplicated/displaced text, punctuation/spacing, paragraph structure, page joins, printed-page visibility and non-body separation. Apply only direct-source-supported corrections, mark records `verified` only if T3 fully passes, synchronize controls, commit T3 separately, and stop before scan 16.
