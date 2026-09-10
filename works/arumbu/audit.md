# Audit — அரும்பு

## Gate state

| Stage | Status |
|---|---|
| Collection/source intake | **PASS / COMPLETE** |
| Work identity / scan boundary | **PASS — scans 6–23** |
| Page-level Tamil transcription | **IN PROGRESS — 5 / 18 canonical records** |
| Scans 6–10 T1 | **PASS / COMPLETE** |
| Scans 6–10 T2 historical-glyph gate | **PASS / COMPLETE — 4 corrections / 0 unresolved** |
| Scans 6–10 T3 final source-fidelity closure | **PASS / COMPLETE — 19 additional corrections / 0 unresolved** |
| Verified canonical pages | **5 / 18 — scans 6–10** |
| Full Tamil audit | BLOCKED until all component pages complete |
| Assembled Tamil | BLOCKED |
| English | BLOCKED |

No source PDF is committed.

## Checkpoint model

The active source workflow follows root `SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`:

- **T1** — direct visual transcription + canonical page records + printed-page visibility; control sync + commit;
- **T2** — independent historical-glyph re-read; control sync + commit;
- **T3** — final source-fidelity closure; control sync + commit.

Each checkpoint is kept as a separate durable state.

## Closed batch — scans 6–10

### T1 — PASS / COMPLETE

Canonical records created for scans 6–10. Printed-page visibility: `null`, `2`, `3`, `4`, `5`.

### T2 — PASS / COMPLETE

Independent historical-glyph re-read completed across all five pages. Four direct character-identity corrections were made and **0 unresolved historical glyphs** remain. See [`T2_BATCH_006_010.md`](T2_BATCH_006_010.md).

### T3 — PASS / COMPLETE

Final source-fidelity re-read completed across all five pages. It checked omissions, duplicated/displaced text, paragraph/page structure, printed-page visibility, non-body material, physical joins and the retained T2 fixes.

T3 made **19 additional source-pixel corrections** and left **0 unresolved source readings**. See [`T3_BATCH_006_010.md`](T3_BATCH_006_010.md).

The five canonical page records are therefore **VERIFIED**.

Physical joins retained in-place:

- scan 7→8: `நடந்` / `தேறின.`;
- scan 8→9: `அபிநய` / `அசைவுகளை...`;
- scan 9→10: `...வைத்தியரை அழைத்து` / `வந்துவிடுகிறேன்”...`.

## Active batch — scans 11–15

- T1 — **NEXT**;
- T2 — BLOCKED by T1;
- T3 — BLOCKED by T2.

## Exact next activity

Execute **T1 only** for physical scans **11–15**: visually transcribe each complete page, create canonical page records with only directly visible printed-page numbers, preserve physical joins/non-body material, leave records `needs-review`, synchronize controls, commit, and stop before T2. Do not begin scan 16.
