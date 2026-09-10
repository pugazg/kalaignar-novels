# Audit — அரும்பு

## Gate state

| Stage | Status |
|---|---|
| Collection/source intake | **PASS / COMPLETE** |
| Work identity / scan boundary | **PASS — scans 6–23** |
| Page-level Tamil transcription | **IN PROGRESS — 15 / 18 canonical records** |
| Scans 6–10 T1/T2/T3 | **PASS / COMPLETE — VERIFIED** |
| Scans 11–15 T1/T2/T3 | **PASS / COMPLETE — VERIFIED** |
| Scans 16–20 T1 | **PASS / COMPLETE — 5 records / needs-review** |
| Scans 16–20 T2 | **NEXT** |
| Scans 16–20 T3 | BLOCKED by T2 |
| Verified canonical pages | **10 / 18 — scans 6–15 contiguous** |
| Scans 21–23 | not-started |
| Full Tamil audit | BLOCKED until all component pages complete |
| Assembled Tamil | BLOCKED |
| English | BLOCKED |

No source PDF is committed.

## Checkpoint model

The active workflow follows root `SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`: T1 direct visual first pass, T2 independent historical-glyph / character-identity re-read, T3 final source-fidelity closure. Each checkpoint synchronizes controls and commits separately.

## Closed batches

Scans 6–10 and 11–15 have T1 + T2 + T3 **PASS / COMPLETE** and are **VERIFIED**. The verified contiguous range is scans **6–15**.

## Active batch — scans 16–20

### T1 — PASS / COMPLETE

See [`T1_BATCH_016_020.md`](T1_BATCH_016_020.md).

- five direct visual first-pass records created;
- page states remain `needs-review`;
- directly visible printed pages: **12, 13, 14, 15, 16**;
- no numbering was inferred;
- preserved physical joins: 15→16 `செல்லக்` / `குழந்தையை—...`; 16→17 `அவர்களைக்-` / `கவனிக்கிறான்.`; 18→19 `செலவா` / `யிற்று.`; 19→20 `கடிந்துகொண்` / `டிருக்கிறாள்.`;
- no scan 21 text was inspected;
- no T2/T3 work was folded into T1.

### T2 — NEXT

Independently re-read scans 16–20 under `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`, correct only source-supported character identities, synchronize controls, commit, and stop before T3.

Do not begin scan 21.
