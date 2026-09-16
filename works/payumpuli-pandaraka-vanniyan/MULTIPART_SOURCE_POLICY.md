# Multipart Source Policy — பாயும்புலி பண்டாரக வன்னியன்

This work follows the durable split-source pattern used by `works/kuraloviyam/` in `pugazg/kalaignar-literary-commentary`.

## Source family

- source family: **TVA_BOK_0065744**
- complete physical extent: **477 scans**
- supplied working splits: **16 PDFs**
- split-page total: **477**
- aggregate split-file bytes: **456,282,569**
- original monolithic PDF is not committed to Git
- split PDFs are working sources and are not committed to Git

## Canonical numbering rule

Repository `scan_page` is always the **overall physical scan number 1–477**.

It never restarts at 1 for a split PDF.

Every canonical page record created from a split must carry:

```yaml
scan_page: <overall 1-477>
part: <1-16>
part_page: <local page inside split>
source_filename: "<exact supplied split filename>"
```

Mapping:

- `part_page = scan_page - part_start + 1`
- `scan_page = part_start + part_page - 1`

## Split manifest

| Part | Overall scans | Local pages | Exact supplied filename | Intake state |
|---:|---:|---:|---|---|
| 001 | 1–30 | 30 | `TVA_BOK_0065744_பாயும்புலி_பண்டாரக_வன்னியன்_part_001_pages_1-30.pdf` | supplied / registered |
| 002 | 31–60 | 30 | `TVA_BOK_0065744_பாயும்புலி_பண்டாரக_வன்னியன்_part_002_pages_31-60.pdf` | supplied / registered |
| 003 | 61–90 | 30 | `TVA_BOK_0065744_பாயும்புலி_பண்டாரக_வன்னியன்_part_003_pages_61-90.pdf` | supplied / registered |
| 004 | 91–120 | 30 | `TVA_BOK_0065744_பாயும்புலி_பண்டாரக_வன்னியன்_part_004_pages_91-120.pdf` | supplied / registered |
| 005 | 121–150 | 30 | `TVA_BOK_0065744_பாயும்புலி_பண்டாரக_வன்னியன்_part_005_pages_121-150.pdf` | supplied / registered |
| 006 | 151–180 | 30 | `TVA_BOK_0065744_பாயும்புலி_பண்டாரக_வன்னியன்_part_006_pages_151-180.pdf` | supplied / registered |
| 007 | 181–210 | 30 | `TVA_BOK_0065744_பாயும்புலி_பண்டாரக_வன்னியன்_part_007_pages_181-210.pdf` | supplied / registered |
| 008 | 211–240 | 30 | `TVA_BOK_0065744_பாயும்புலி_பண்டாரக_வன்னியன்_part_008_pages_211-240.pdf` | supplied / registered |
| 009 | 241–270 | 30 | `TVA_BOK_0065744_பாயும்புலி_பண்டாரக_வன்னியன்_part_009_pages_241-270.pdf` | supplied / registered |
| 010 | 271–300 | 30 | `TVA_BOK_0065744_பாயும்புலி_பண்டாரக_வன்னியன்_part_010_pages_271-300.pdf` | supplied / registered |
| 011 | 301–330 | 30 | `TVA_BOK_0065744_பாயும்புலி_பண்டாரக_வன்னியன்_part_011_pages_301-330.pdf` | supplied / registered |
| 012 | 331–360 | 30 | `TVA_BOK_0065744_பாயும்புலி_பண்டாரக_வன்னியன்_part_012_pages_331-360.pdf` | supplied / registered |
| 013 | 361–390 | 30 | `TVA_BOK_0065744_பாயும்புலி_பண்டாரக_வன்னியன்_part_013_pages_361-390.pdf` | supplied / registered |
| 014 | 391–420 | 30 | `TVA_BOK_0065744_பாயும்புலி_பண்டாரக_வன்னியன்_part_014_pages_391-420.pdf` | supplied / registered |
| 015 | 421–450 | 30 | `TVA_BOK_0065744_பாயும்புலி_பண்டாரக_வன்னியன்_part_015_pages_421-450.pdf` | supplied / registered |
| 016 | 451–477 | 27 | `TVA_BOK_0065744_பாயும்புலி_பண்டாரக_வன்னியன்_part_016_pages_451-477.pdf` | supplied / registered |

## Boundary rule

Split boundaries are physical-file boundaries only. They must never be treated as textual boundaries without visual evidence.

For every `N→N+1` Part boundary:

1. inspect the last source scan of the earlier Part;
2. inspect the first source scan of the next Part;
3. classify the boundary as **CLEAN**, **GENUINE CONTINUATION**, or another source-supported state;
4. do not reconstruct text across the split;
5. if the current batch ends at a split boundary, the first page of the next Part may be used only as a boundary witness unless that next Part has become active.

All 16 Parts are now supplied, so no boundary is blocked by missing source. Boundaries remain **unclassified until directly audited**.

## Page-layer rule

There is one unified canonical directory:

`works/payumpuli-pandaraka-vanniyan/pages/`

Do **not** create duplicate per-Part page trees. Filenames use the overall scan number.

A page record's `part`, `part_page`, and `source_filename` preserve the split provenance.

## Workflow rule

This work now follows the **Kuraloviyam per-Part closure model**. The split is an access/provenance device, not a content division.

Permanent Part order:

**source intake → Pass 1 complete transcription → Pass 2A direct textual verification → Pass 2B independent lexical/historical-glyph reread → Pass 3 visual/structural verification → Part audit → final status sync → documentation sync → Tamil archival-ready → assembled Tamil closure → English translation/review → release/readiness report → final Part closure → next Part**

A later Part may be supplied/registered and may serve as an adjacent boundary witness, but its transcription must not begin before the active Part's final closure.

Authoritative work-specific guide:
- `PAYUMPULI_ARCHIVAL_GUIDELINES.md`

## Current state

- 16 / 16 split PDFs: **SUPPLIED / REGISTERED**
- 477 / 477 source pages accounted for by split ranges
- **active Part: Part001 / scans1–30**
- canonical Part001 records: **30/30 present**
- Part001 Pass 1 text-complete: **30/30**
- Part001 Pass 1 partial: **0/30**
- formal Pass 2A: **COMPLETE — 30/30 reviewed**
- formal Pass 2B: **COMPLETE — 30/30 reviewed**
- formal Pass 3: **NOT STARTED**
- Part001 Tamil archival-ready: **BLOCKED**
- Part001 English/release: **BLOCKED**
- Part002 transcription: **BLOCKED until Part001 final closure**
- split-boundary classifications: **1 / 15 audited — 30→31 GENUINE CONTINUATION**
- exact active gate: **Part001 Pass 3 scans1–10**

## Batch-size policy

The legacy opening batch **scans1–5** was already in progress before the user changed the iteration size; it is now closed through T3.

Normal source iterations use **10 physical scans per batch**, with a shorter final remainder.

For Part001 Pass 1:
- completed: **scans6–15 — text-complete / needs-review**;
- completed: **scans16–25 — text-complete / needs-review**;
- completed: **scans26–30 — text-complete / needs-review**;
- Pass 1 is now **30/30 complete**; formal Pass 2A is the next gate from scan1.


## Audited boundary — 30→31

Part001 final page / overall scan30 and Part002 first page / overall scan31 were directly compared.

Classification: **GENUINE CONTINUATION**.

Evidence:
- both pages remain in the same continuous body flow;
- no new title/front-matter break appears at scan31;
- visible printed pagination continues **19 → 20**;
- no text is reconstructed across the split.
