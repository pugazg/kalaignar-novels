# Audit — அரும்பு

## Gate state

| Stage | Status |
|---|---|
| Collection/source intake | **PASS / COMPLETE** |
| Work identity / scan boundary | **PASS — scans 6–23** |
| Page-level Tamil transcription | **IN PROGRESS — 10 / 18 canonical records** |
| Scans 6–10 T1 | **PASS / COMPLETE** |
| Scans 6–10 T2 historical-glyph gate | **PASS / COMPLETE — 4 corrections / 0 unresolved** |
| Scans 6–10 T3 final source-fidelity closure | **PASS / COMPLETE — 19 additional corrections / 0 unresolved** |
| Scans 11–15 T1 | **PASS / COMPLETE — 5 records / needs-review** |
| Scans 11–15 T2 | **NEXT** |
| Scans 11–15 T3 | BLOCKED by T2 |
| Verified canonical pages | **5 / 18 — scans 6–10** |
| Full Tamil audit | BLOCKED until all component pages complete |
| Assembled Tamil | BLOCKED |
| English | BLOCKED |

No source PDF is committed.

## Checkpoint model

The active source workflow follows root `SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`:

- **T1** — one direct visual transcription pass + canonical page records + exact visible printed-page numbering; control sync + commit;
- **T2** — independent historical-glyph re-read; control sync + commit;
- **T3** — final source-fidelity closure; control sync + commit.

T1 does not absorb repeated crop loops, independent glyph verification, or exhaustive fidelity checking. Difficult first-pass readings may remain `needs-review` for T2/T3.

## Closed batch — scans 6–10

T1, T2 and T3 are **PASS / COMPLETE**. Five records are **VERIFIED**. See `T1_BATCH_006_010.md`, `T2_BATCH_006_010.md`, `T3_BATCH_006_010.md`.

## Active batch — scans 11–15

### T1 — PASS / COMPLETE

See [`T1_BATCH_011_015.md`](T1_BATCH_011_015.md).

- five direct visual first-pass records created;
- page states remain `needs-review`;
- directly visible printed pages: **6, 7, 8, 10, 11**;
- printed page 9 is **not inferred**;
- scan 13 illustration is separated from body text;
- joins preserved: 11→12 `போய்` / `விட்டனர்.` and 13→14 `ஊற்றெடுத்துக் கிளம்பிவரும்` / `அருவி!`;
- scan 15 ends at source-visible `செல்லக்`; scan 16 was not inspected;
- no T2/T3 work was folded into T1.

### T2 — NEXT

Independently re-read scans 11–15 under `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`, correct only source-supported character identities, synchronize controls, commit, and stop before T3.

Do not begin scan 16.
