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
| Scans 16–20 T3 | **PASS / COMPLETE — 11 corrections / 0 unresolved** |
| Verified canonical pages | **15 / 18 — scans 6–20 contiguous** |
| Scans 21–23 T1 | **NEXT** |
| Full Tamil audit | BLOCKED until all component pages complete |
| Assembled Tamil | BLOCKED |
| English | BLOCKED |

No source PDF is committed.

## Checkpoint model

The active workflow follows root `SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`: T1 direct visual first pass, T2 independent historical-glyph / character-identity re-read, T3 final source-fidelity closure. Every checkpoint synchronizes controls and commits separately.

## Closed batches

Scans 6–10 and 11–15 have T1 + T2 + T3 **PASS / COMPLETE** and are **VERIFIED**.

### Scans 16–20 — CLOSED / VERIFIED

- T1 — PASS / COMPLETE;
- T2 — PASS / COMPLETE, **1** character-identity correction (`தனியாத` → `தணியாத`), 0 unresolved;
- T3 — PASS / COMPLETE, **11** additional source-fidelity corrections, 0 unresolved;
- directly visible printed pages: **12, 13, 14, 15, 16**;
- five page records now **VERIFIED**.

T3 corrections include `அனுயாசமாகக்`, `இருதயத்திலே`, `அடியெடுத்து வைத்த`, `அலுவலகத்திலிருந்து`, `என்ற ஆராய்ச்சியில்`, restoration of `பழகும், வளமும் இருக்கும் போதே`, scan-19 wording/spacing fixes, and restoration on scan 20 of `தூங்காமல் புரண்டுகொண்டிருந்த குமார், மெதுவாக எழுந்தான்.` with source punctuation.

Physical joins retained: 15→16 `செல்லக்` / `குழந்தையை—...`; 16→17 `அவர்களைக்-` / `கவனிக்கிறான்.`; 18→19 `செலவா` / `யிற்று.`; 19→20 `கடிந்துகொண்` / `டிருக்கிறாள்.`.

## Exact next activity

Execute **T1 only for physical scans 21–23**: one direct visual transcription pass per page, create three `needs-review` canonical records, preserve only directly visible numbering and page-boundary/non-body observations, synchronize controls, commit, and stop before T2 or the next component.
