# பாயும்புலி பண்டாரக வன்னியன்

**ஆசிரியர்:** கலைஞர் மு. கருணாநிதி  
**பதிப்பகம்:** ராக்போர்ட் பப்ளிகேஷன்ஸ்  
**பதிப்பு:** முதல் பதிப்பு — 1991  
**Complete source:** 477 physical scans  
**Working source:** 16 split PDFs — all supplied  
**Source PDFs in repository:** No

## Current status

**MULTIPART SOURCE FAMILY REGISTERED / TAMIL T1 NOT STARTED**

- source family: **TVA_BOK_0065744**
- source Parts: **16/16 SUPPLIED / REGISTERED**
- split ranges: **1–30, 31–60, …, 421–450, 451–477**
- global physical coverage: **477/477**
- aggregate split bytes: **456,282,569**
- image-only scans; no usable parsed text layer
- canonical page records: **0/477**
- T1/T2/T3: **NOT STARTED**
- assembled Tamil: **BLOCKED**
- English: **BLOCKED until Tamil archival + assembled-Tamil gates pass**

Controls:
- [`SOURCE_INTAKE.md`](SOURCE_INTAKE.md)
- [`MULTIPART_SOURCE_POLICY.md`](MULTIPART_SOURCE_POLICY.md)
- [`metadata/source.md`](metadata/source.md)
- [`indexes/page-map.md`](indexes/page-map.md)
- [`audit.md`](audit.md)
- `SOURCE_INTAKE_PART_001.md` … `SOURCE_INTAKE_PART_016.md`

## Multipart handling

This work adopts the Kuraloviyam split-source pattern:

- overall `scan_page` **never resets**;
- page records carry `part` + `part_page` + exact `source_filename`;
- one unified canonical `pages/` directory is used;
- split boundaries do not create artificial narrative boundaries;
- boundary state is classified only from adjacent rendered source pages;
- later Parts remain source-ready but do not leapfrog the global active frontier.

## Initial Part 001 structure

Observed from the supplied source:

1. scan1 — illustrated cover;
2. scans2–5 — title / publisher / bibliographic front matter;
3. scans6–9 — `அணிந்துரை`;
4. scan10 — `பதிப்புரை`;
5. scan11 — epigraph / verse page;
6. scan12 — secondary title divider;
7. scan13 onward — `தோரண வாயில்`, exact structural role still provisional.

## Source-first rules

- source pixels control every reading;
- preserve printed spelling, punctuation, paragraph structure and historical glyph identity;
- do not normalize names, offices, place names or historical vocabulary;
- separate stamps / handwriting / library marks from printed text;
- unclear readings remain `needs-review`;
- source PDFs remain outside Git.

## Exact next activity

Perform **Part 001 T1 — overall scans1–5 / local pages1–5** under `SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`.

After T1:
- five canonical page records must exist;
- each must carry Part-001 split provenance;
- page map / audit / README / handover / next-chat controls must be synchronized;
- commit;
- stop before T2.
