# Initial Page Map — அரும்பு

Source physical span: **scans 6–23** of the 92-scan 1978 compilation.

| Physical scan | Printed page | State |
|---:|:---:|---|
| 6 | null — not visibly printed | not-started |
| 7 | 2 — directly visible | not-started |
| 8 | 3 — directly visible | not-started |
| 9 | 4 — directly visible | not-started |
| 10 | 5 — directly visible | not-started |
| 11–23 | record only after direct page inspection | not-started |

Canonical page records: **0 / 18**.

## Active checkpoint

Scans **6–10** remain the first bounded source batch, but the batch is split under root `SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`:

- T1 — direct transcription + canonical records — **NEXT**;
- T2 — independent historical-glyph re-read — BLOCKED by T1;
- T3 — final source-fidelity closure — BLOCKED by T2.

Every checkpoint must synchronize controls and commit separately.
