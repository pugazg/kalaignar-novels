# Audit — அரும்பு

## Gate state

| Stage | Status |
|---|---|
| Collection/source intake | **PASS / COMPLETE** |
| Work identity / scan boundary | **PASS — scans 6–23** |
| Page-level Tamil transcription | **IN PROGRESS — 15 / 18 canonical records** |
| Scans 6–10 T1/T2/T3 | **PASS / COMPLETE — VERIFIED** |
| Scans 11–15 T1/T2/T3 | **PASS / COMPLETE — VERIFIED** |
| Scans 16–20 T1 | **PASS / COMPLETE** |
| Scans 16–20 T2 | **PASS / COMPLETE — 1 correction / 0 unresolved** |
| Scans 16–20 T3 | **NEXT** |
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
- directly visible printed pages: **12, 13, 14, 15, 16**;
- physical joins preserved;
- no scan 21 text was inspected.

### T2 — PASS / COMPLETE

See [`T2_BATCH_016_020.md`](T2_BATCH_016_020.md).

All five complete scans were independently re-read under `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md` and the mandatory families `ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ` were checked.

T2 found **1 direct character-identity correction / 0 unresolved**:

1. scan 17 / printed 13: `தனியாத பாசத்தைத்` → **`தணியாத பாசத்தைத்`**. Direct pixels show retroflex `ண`; this is outside the minimum 13-family set.

Known 13-family corrections in this batch: **0**. All five page records remain `needs-review` because T3 has not yet run.

Preserved joins/edges:

- 15→16 `செல்லக்` / `குழந்தையை—...`;
- 16→17 `அவர்களைக்-` / `கவனிக்கிறான்.`;
- 18→19 `செலவா` / `யிற்று.`;
- 19→20 `கடிந்துகொண்` / `டிருக்கிறாள்.`.

### T3 — NEXT

Perform final source-fidelity closure for scans 16–20 only. Check omissions, duplication/misplacement, source spelling/punctuation/spacing, joins and non-body separation. Apply only direct-source-supported corrections, synchronize controls, commit T3 separately, and stop before scan 21.
