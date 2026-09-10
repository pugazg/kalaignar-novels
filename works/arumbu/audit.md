# Audit — அரும்பு

## Gate state

| Stage | Status |
|---|---|
| Collection/source intake | **PASS / COMPLETE** |
| Work identity / scan boundary | **PASS — scans 6–23** |
| Page-level Tamil transcription | **IN PROGRESS — 5 / 18 canonical records** |
| Active batch T1 scans 6–10 | **PASS / COMPLETE** |
| Active batch T2 scans 6–10 | **PASS / COMPLETE — 4 character-identity corrections / 0 unresolved** |
| Final source-fidelity closure | **T3 NEXT — scans 6–10** |
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

T1 checkpoint audit: [`T1_BATCH_006_010.md`](T1_BATCH_006_010.md).

### T2 — PASS / COMPLETE

Every complete scan was independently re-read against the full known historical set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`.

Corrections from direct source pixels:

| Scan | T1 reading | T2 source-supported reading | Classification |
|---:|---|---|---|
| 7 | `மனத்திற்குப்` | `மணத்திற்குப்` | additional character identity |
| 8 | `கிழவனுக்குவா` | `கிழவனாகவா` | historical `னா` |
| 8 | `கிழவனுக்குவும்` | `கிழவனாகவும்` | historical `னா` |
| 10 | `அவனுடைய` | `அவளுடைய` | additional character identity |

- total character-identity corrections: **4**;
- corrections within the mandatory 13-family set: **2**, both `னா` on scan 8;
- additional character-identity corrections: **2**;
- unresolved glyphs after T2: **0**;
- canonical page states remain **5 `needs-review` / 0 verified**.

T2 checkpoint audit: [`T2_BATCH_006_010.md`](T2_BATCH_006_010.md).

### T3 — NEXT

Perform the final independent source-fidelity closure for scans 6–10. Check omissions, duplicated or misplaced text, physical joins, printed-page visibility, illustration/body separation and the T2 corrections. Only T3 may close/verify this batch if all source checks pass.

## Exact next activity

Execute **T3 only** for physical scans **6–10**, synchronize controls, commit separately, and stop before scan 11.
