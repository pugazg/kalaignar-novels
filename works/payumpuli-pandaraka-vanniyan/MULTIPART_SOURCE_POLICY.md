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

The split is an access/provenance device, not a content division.

Normal order remains:

**source intake → T1 capture → T2 historical-glyph/text fidelity → T3 visual/structural fidelity → audit/status closure → assembled Tamil → English**.

Processing may advance Part by Part, but canonical scan numbering and cross-Part textual continuity are global.

## Current state

- 16 / 16 split PDFs: **SUPPLIED / REGISTERED**
- 477 / 477 source pages accounted for by split ranges
- canonical page records: **5 / 477**
- T1: **5 / 477 COMPLETE through scan5**
- T2: **0 / 477**
- T3: **0 / 477**
- split-boundary classifications: **not yet audited**
- exact active gate: **Part 001 T2 scans 1–5**
