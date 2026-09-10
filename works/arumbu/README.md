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
- verified pages: **15 / 18 — scans 6–20 contiguous**;
- scans 6–10 T1/T2/T3: **PASS / COMPLETE**;
- scans 11–15 T1/T2/T3: **PASS / COMPLETE**;
- scans 16–20 T1: **PASS / COMPLETE**;
- scans 16–20 T2: **PASS / COMPLETE — 1 correction / 0 unresolved**;
- scans 16–20 T3: **PASS / COMPLETE — 11 additional corrections / 0 unresolved**;
- scans 21–23 T1: **PASS / COMPLETE**;
- scans 21–23 T2: **NEXT**;
- scans 21–23 T3: BLOCKED by T2;
- assembled Tamil: **BLOCKED**;
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

Directly visible printed pages: **12, 13, 14, 15, 16**.

Preserved physical joins:

- 15→16 `செல்லக்` / `குழந்தையை—...`;
- 16→17 `அவர்களைக்-` / `கவனிக்கிறான்.`;
- 18→19 `செலவா` / `யிற்று.`;
- 19→20 `கடிந்துகொண்` / `டிருக்கிறாள்.`.

## Active final batch — scans 21–23

- [`T1_BATCH_021_023.md`](T1_BATCH_021_023.md) — **PASS / COMPLETE**;
- canonical records — scans 21, 22, 23 / printed pages **17, 18, 19** — all `needs-review`;
- scan 21 T1 was committed separately at `89c41ba57f634bf222cb484d605f32217ccb7176`; scans 22–23 complete the bounded T1 range;
- scan 23 is the final physical page of `அரும்பு`; no explicit `முற்றும்` is printed;
- T2 — **NEXT**;
- T3 — BLOCKED by T2.

Preserved continuity:

- 20→21: `அவனது அம்மா படம்!` → `அதை எடுத்து...`;
- 21→22: `அப்பா பாப்பாவை நினைத்து` → `அழுதுகொண்டே யிருக்கிறாரே!`;
- 22→23: completed sentence → new paragraph `அவளையறியாமல்,...`.

## Exact next activity

**T2 for final physical scans 21–23 only.** Independently re-read all three complete source pages against the historical-Tamil glyph guide, correct character identity only when direct pixels support it, record corrections/unresolved glyphs, synchronize controls, commit T2, and stop before T3. Do not begin `சாரப்பள்ளம் சாமுண்டி` in the same checkpoint.
