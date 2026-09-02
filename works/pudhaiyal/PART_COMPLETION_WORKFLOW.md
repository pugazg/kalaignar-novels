# Split-PDF part-completion workflow — புதையல்

Split PDFs are access derivatives of one source edition. `part-complete` is a split-level state only; whole-work Tamil/English/release gates remain blocked until complete source coverage.

## Per-split sequence

1. map represented source scans;
2. reconcile canonical `pages/` records;
3. native visual/structural fidelity review;
4. resolve/retain every `needs-review` item;
5. part-level Tamil audit;
6. assembled Tamil from audited canonical pages;
7. controlled English translation;
8. English source check;
9. part-level bilingual review;
10. synchronize status.

## Lexical baseline rule — scan 280 onward

User-supplied Gemini transcription controls lexical wording/forms/spacing. Native scans control headings, paragraph boundaries, punctuation, quotations, physical boundaries, separators and chapter/scene structure.

- Part 007 baseline: `p7.md`; three explicit user-authorized omissions restored.
- Part 008 baseline: `p8.md`; **no complete lexical omission found**.

## Split checkpoints

- Parts 001–006 — `part-complete`
- Part 007 — scans **295–343** — `part-complete`
- Part 008 — scans **344–392** — **Tamil audit PASSED / assembled Tamil next**

## Part 008 gate state

- mapping: **PASS — 49 / 49**
- canonical: **PASS — 49 / 49**
- visual/structural fidelity: **PASS**
- Part-008 needs-review: **0**
- Tamil audit: **PASS**
- assembled Tamil: **NEXT**
- controlled English: blocked until assembly pass
- bilingual review: blocked until English source check

Part 008 continues Chapter 39 across the `அதிர்ஷ்` + `டம்` boundary and carries Chapters 40–45. Scan 392 ends Chapter 45 open at `நமது`; this is not the novel ending.

## Exact next activity

Build and consistency-check the Part-008 assembled Tamil layer from scans **344–392**, then advance to controlled English only if that check passes.
