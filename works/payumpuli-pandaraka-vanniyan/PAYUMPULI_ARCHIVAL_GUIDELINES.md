# பாயும்புலி பண்டாரக வன்னியன் — Part-by-Part Archival Guidelines

This is the work-specific operating guide for `works/payumpuli-pandaraka-vanniyan/`.

It adopts the **Kuraloviyam per-Part closure methodology** while retaining the novel repository's assembled-Tamil and release-readiness layers.

## 1. Controlling-source rule

The user-attached split PDFs are the controlling source. They are the Tamil Digital Library copy supplied by the user.

Do not use Tamil Digital Library, Wikisource or another mirror as a second witness unless the user explicitly requests comparison.

Source wording, punctuation, paragraphing, historical glyph identity, visible printed-page numbering and page structure control.

## 2. Multipart numbering

Complete source: **477 physical scans / 16 supplied Parts**.

- Parts001–015: 30 scans each
- Part016: 27 scans
- canonical `scan_page`: global 1–477, never resets
- `part_page`: local position inside the split PDF
- every page record carries exact `part`, `part_page` and `source_filename`

Split files are provenance/access boundaries only, not textual boundaries.

## 3. Mandatory Part lock

> **Finish the entire maintained workflow for the active Part before beginning transcription of the next Part.**

A later Part may be supplied/registered and used as the adjacent boundary witness needed to resolve the active Part's outgoing boundary, but it must not receive canonical transcription records, Pass work, assembled Tamil or English work until the active Part reaches final closure.

For Part001 this lock has now been fully satisfied:

**Tamil archival-ready + assembled Tamil closure + English completion + release/readiness report + release-ready synchronization + final Part closure — PASS / CLOSED.**

Part002 may therefore become the next active Part on the next explicit continuation.

## 4. Tamil Part workflow

For each Part, in order:

1. source intake
2. Pass 1 — complete physical capture/transcription
3. Pass 2A — direct textual verification
4. Pass 2B — independent lexical/historical-glyph reread
5. Pass 3 — meaningful visual/structural verification
6. Part audit
7. final metadata/status synchronization
8. documentation synchronization
9. Tamil archival-ready checkpoint

Final `verified` status is assigned only after the whole-Part verification/audit chain closes.

## 5. Novel-specific assembled Tamil layer

After Tamil archival-ready:

1. assemble readable Part-level Tamil sections only from audited canonical page records;
2. preserve source-page provenance and verified cross-page joins;
3. audit the assembled layer against the canonical pages;
4. close the assembled Tamil Part checkpoint.

The assembled layer never supersedes canonical `pages/`.

## 6. English workflow

English is a **project-created translation** and begins only after the Part's Tamil archival and assembled-Tamil gates are closed.

Permanent gate order:

**translation plan → draft → source-check → glossary reconciliation → editorial review → Part-level bilingual review → release/readiness report → release-ready synchronization → final Part closure**

Required controls include:

- `translations/en/TRANSLATION_PLAN.md`
- `translations/en/GLOSSARY.md`
- `translations/en/PROGRESS.md`
- `translations/en/TRANSLATION_REVIEW.md`
- `translations/en/BILINGUAL_REVIEW.md`
- `translations/en/RELEASE_REPORT.md`
- Part-specific release-ready synchronization record
- Part-specific final-closure record

## 7. Final Part closure

The durable Part001 closure record is:

`PART_001_FINAL_CLOSURE.md`

Result:

**PART001 FINAL CLOSURE — PASS / CLOSED**

It confirms:

- Tamil Part archival-ready;
- assembled Tamil closed;
- English translation complete;
- whole-Part bilingual review passed;
- release/readiness report passed;
- release-ready synchronization passed;
- unresolved blockers **0**;
- source/boundary state durable;
- unauthorized textual drift after release/readiness **0**.

Part002 transcription is now permitted by the Part lock, but it was not begun during the Part001 final-closure iteration.

## 8. Boundary rule

The next Part's first page may be inspected as an outgoing-boundary witness before the next Part is active.

For Part001/Part002:
- scan30 / Part001 local30 and scan31 / Part002 local1 were directly compared;
- **30→31 = GENUINE CONTINUATION**;
- Part001 Tamil ends `அவனுக்கு ஒரே மகிழ்ச்சி,`;
- Part001 English ends **“He was filled with joy,”**;
- scan31 text was not imported into Part001.

This boundary remains the incoming audited boundary for Part002.

## 9. Batch cadence

User-directed normal source batch size: **10 physical scans**, with a shorter final remainder.

A batch is only complete when the requested Pass work for those scans is complete. Page/provenance-only scaffolding is not Pass-1 completion.

Part001 is now **FINAL CLOSED** across Tamil, assembled Tamil, English, release/readiness and release synchronization. Part002 source intake is already registered for global scans **31–60**, but canonical Part002 page records remain **0** and Pass work remains **NOT STARTED**.

The next normal Pass-1 batch is **global scans31–40 / Part002 local pages1–10**.

## 10. Current Part frontier

- **Part001: FINAL CLOSURE — PASS / CLOSED**
- **Part002 source: SUPPLIED / REGISTERED**
- **Part002 canonical page records: 0**
- **Part002 transcription: AUTHORIZED / NOT STARTED**
- **Next active Part: Part002 / global scans31–60**
- **Exact next gate: activate Part002 and perform Pass 1 for global scans31–40 / local pages1–10**

Do not begin Part002 Pass 2A until Part002 Pass 1 covers all 30 scans.