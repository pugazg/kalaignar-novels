# பாயும்புலி பண்டாரக வன்னியன்

**ஆசிரியர்:** கலைஞர் மு. கருணாநிதி  
**பதிப்பகம்:** ராக்போர்ட் பப்ளிகேஷன்ஸ்  
**பதிப்பு:** முதல் பதிப்பு — 1991  
**Complete source:** 477 physical scans  
**Working source:** 16 split PDFs — all supplied  
**Source PDFs in repository:** No

## Current status

**OPENING BATCH scans1–5 T1/T2/T3 CLOSED / NEXT T1 scans6–15 (10 pages)**

- source family: **TVA_BOK_0065744**
- source Parts: **16/16 SUPPLIED / REGISTERED**
- split ranges: **1–30, 31–60, …, 421–450, 451–477**
- global physical coverage: **477/477**
- aggregate split bytes: **456,282,569**
- image-only scans; no usable parsed text layer
- canonical page records: **5/477**
- T1: **5/477 COMPLETE through scan5**
- T2: **5 / 477 COMPLETE through scan5**
- T3: **5 / 477 COMPLETE through scan5**
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

Perform **Part 001 T1 — overall scans6–15 / local pages6–15** under `SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`.

T1 durable state:
- five canonical page records exist;
- all five carry Part001 split provenance;
- all five remain `needs-review`;
- scan3 telephone digits and scan5 compact publication block are explicit T1 uncertainties.

After T2:
- synchronize page records and controls;
- commit;
- stop before T3.
