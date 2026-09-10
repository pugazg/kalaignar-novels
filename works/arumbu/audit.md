# Audit — அரும்பு

## Gate state

| Stage | Status |
|---|---|
| Collection/source intake | **PASS / COMPLETE** |
| Work identity / scan boundary | **PASS — scans 6–23** |
| Page-level Tamil transcription | **IN PROGRESS — 10 / 18 canonical records** |
| Scans 6–10 T1/T2/T3 | **PASS / COMPLETE — VERIFIED** |
| Scans 11–15 T1 | **PASS / COMPLETE** |
| Scans 11–15 T2 | **PASS / COMPLETE — 1 correction / 0 unresolved** |
| Scans 11–15 T3 | **PASS / COMPLETE — 2 corrections / 0 unresolved** |
| Verified canonical pages | **10 / 18 — scans 6–15 contiguous** |
| Scans 16–20 T1 | **NEXT** |
| Full Tamil audit | BLOCKED until all component pages complete |
| Assembled Tamil | BLOCKED |
| English | BLOCKED |

No source PDF is committed.

## Checkpoint model

The active workflow follows root `SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`:

- **T1** — one direct visual transcription pass + canonical records + exact visible numbering; control sync + commit;
- **T2** — independent historical-glyph / character-identity re-read; control sync + commit;
- **T3** — final source-fidelity closure; control sync + commit.

Each checkpoint remains a separate durable state.

## Closed batch — scans 6–10

T1, T2 and T3 are **PASS / COMPLETE**. Five canonical records are **VERIFIED**. T2 made 4 character-identity corrections; T3 made 19 additional source-fidelity corrections; unresolved readings: 0.

## Closed batch — scans 11–15

### T1 — PASS / COMPLETE

Five direct visual first-pass records created. Directly visible printed pages: **6, 7, 8, 10, 11**. Printed page 9 was not inferred. Scan 13 illustration was kept separate from body text.

### T2 — PASS / COMPLETE

One historical-glyph correction on scan 12: `திருக்குவள நண்பன்` → **`திருக்குவளை நண்பன்`**. Unresolved historical glyphs: **0**.

### T3 — PASS / COMPLETE

Final source-fidelity closure found **2** additional corrections, both on scan 12:

1. `கோமதி அழுது அழுது கொண்டிருப்பதைப் பார்த்தான்.` → **`கோமதி அழுது கொண்டிருப்பதைப் பார்த்தான்.`**;
2. `சாப்பாடுகூடப் போடவில்லை!` → source-visible **`சாப்பாடுகூடப் போட்டவில்லையே!`**.

Scans 11, 13, 14 and 15 required no T3 text correction. Unresolved source readings: **0**.

Physical joins/edges retained:

- 11→12 `போய்` / `விட்டனர்.`;
- 13→14 `ஊற்றெடுத்துக் கிளம்பிவரும்` / `அருவி!`;
- scan 15 ends at `செல்லக்`; no scan-16 completion was inferred during this closed batch.

The five scans are now **VERIFIED**.

## Active batch — scans 16–20

- T1 — **NEXT**;
- T2 — BLOCKED by T1;
- T3 — BLOCKED by T2.

## Exact next activity

Execute **T1 only** for physical scans **16–20**: visually transcribe each complete page once, create canonical `needs-review` records using only directly visible printed-page numbers, preserve physical joins/non-body material, synchronize controls, commit, and stop before T2. Do not begin scan 21.
