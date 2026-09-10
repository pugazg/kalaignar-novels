# Audit — அரும்பு

## Gate state

| Stage | Status |
|---|---|
| Collection/source intake | **PASS / COMPLETE** |
| Work identity / scan boundary | **PASS — scans 6–23** |
| Page-level Tamil transcription | **IN PROGRESS — 5 / 18 canonical records** |
| Active batch T1 scans 6–10 | **PASS / COMPLETE** |
| Historical-glyph gate | **T2 NEXT — scans 6–10** |
| Final source-fidelity closure | **T3 BLOCKED by T2** |
| Full Tamil audit | BLOCKED |
| Assembled Tamil | BLOCKED |
| English | BLOCKED |

No source PDF is committed.

## Checkpoint model

The active source workflow follows root `SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`:

- **T1** — direct visual transcription + canonical page records + printed-page visibility; control sync + commit;
- **T2** — independent historical-glyph re-read; control sync + commit;
- **T3** — final source-fidelity closure; control sync + commit.

Each checkpoint is a separate durable commit.

## Active batch — scans 6–10

### T1 — PASS / COMPLETE

Canonical records:

- `pages/0006-arumbu-01.md` — printed page `null`;
- `pages/0007-arumbu-02.md` — printed page `2`;
- `pages/0008-arumbu-03.md` — printed page `3`;
- `pages/0009-arumbu-04.md` — printed page `4`;
- `pages/0010-arumbu-05.md` — printed page `5`.

All five remain `needs-review`.

Physical joins retained in-place:

- scan 7→8: `நடந்` / `தேறின.`;
- scan 8→9: `அபிநய` / `அசைவுகளை...`;
- scan 9→10: `...வைத்தியரை அழைத்து` / `வந்துவிடுகிறேன்”...`.

T1 checkpoint audit: [`T1_BATCH_006_010.md`](T1_BATCH_006_010.md).

### T2 — NEXT

Run an independent full-page historical-glyph re-read across scans 6–10. The T1 transcription does **not** constitute this gate. Record source-supported corrections and unresolved forms separately.

### T3 — BLOCKED

Do not run final source-fidelity closure until T2 is durably committed.

## Exact next activity

Execute **T2 only** for physical scans **6–10**, synchronize controls, commit, and stop before T3. Do not begin scan 11.
