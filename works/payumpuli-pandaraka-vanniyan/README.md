# பாயும்புலி பண்டாரக வன்னியன்

**ஆசிரியர்:** கலைஞர் மு. கருணாநிதி  
**பதிப்பகம்:** ராக்போர்ட் பப்ளிகேஷன்ஸ்  
**பதிப்பு:** முதல் பதிப்பு — 1991  
**Complete source:** 477 physical scans  
**Working source:** 16 split PDFs — all supplied  
**Source PDFs in repository:** No

## Current status

**PART002 ACTIVE / scans1–5 reviewed through T3 / scans6–35 T1 PARTIAL INVENTORY**

- source family: **TVA_BOK_0065744**
- source Parts: **16/16 SUPPLIED / REGISTERED**
- global physical coverage: **477/477**
- canonical page records: **35/477**
- T1 complete: **5/477** — scans1–5
- T1 partial: **30/477** — scans6–35
- T2 reviewed: **5/477**
- T3 reviewed: **5/477**
- verified: **2/477**
- needs-review: **3/477**
- partial: **30/477**
- assembled Tamil: **BLOCKED**
- English: **BLOCKED until Tamil archival + assembled-Tamil gates pass**

Controls:
- [`SOURCE_INTAKE.md`](SOURCE_INTAKE.md)
- [`MULTIPART_SOURCE_POLICY.md`](MULTIPART_SOURCE_POLICY.md)
- [`metadata/source.md`](metadata/source.md)
- [`indexes/page-map.md`](indexes/page-map.md)
- [`audit.md`](audit.md)
- `SOURCE_INTAKE_PART_001.md` … `SOURCE_INTAKE_PART_016.md`

## Batch-size rule

The opening **scans1–5** batch was already underway before the batch size changed and is now reviewed through T3.

From scans6 onward, use **10 overall scans per iteration**.

Current completed inventory iteration:
- overall scans **26–35**
- Part001 local pages **26–30**
- Part002 local pages **1–5**
- boundary **30→31 = GENUINE CONTINUATION**

Next inventory iteration:
- overall scans **36–45**
- Part002 local pages **6–15**

## Multipart handling

This work follows the Kuraloviyam split-source pattern:

- overall `scan_page` never resets;
- page records preserve `part`, `part_page`, and exact split `source_filename`;
- one unified canonical `pages/` directory is used;
- split boundaries do not create artificial narrative boundaries;
- boundary state is classified only from adjacent rendered source pages.

## Current Part001 structure

Observed from the supplied source:

1. scan1 — illustrated cover;
2. scans2–5 — title / publisher / bibliographic front matter;
3. scans6–9 — `அணிந்துரை`;
4. scan10 — `பதிப்புரை`;
5. scan11 — epigraph / verse page;
6. scan12 — secondary title / illustrated divider;
7. scan13 onward — `தோரண வாயில்`; exact structural role remains provisional.

## Source-first rules

- source pixels control every reading;
- preserve printed spelling, punctuation, paragraph structure and historical glyph identity;
- do not normalize names, offices, place names or historical vocabulary;
- separate stamps / handwriting / library marks from printed text;
- unclear readings stay non-final;
- source PDFs remain outside Git.

## Current T1 state

Canonical records now exist through **overall scan35**.

- scans1–5: T1/T2/T3 reviewed;
- scans6–35: T1 page/provenance/printed-page inventory present, but complete printed Tamil text remains to be entered;
- all text-incomplete records remain `partial`;
- T2/T3 do not advance on partial pages.

The attached source itself is normal and authoritative. The partial backlog is not a source defect.

Detailed checkpoints:
- [`T1_BATCH_006_015.md`](T1_BATCH_006_015.md)
- [`T1_BATCH_016_025.md`](T1_BATCH_016_025.md)
- [`T1_BATCH_026_035.md`](T1_BATCH_026_035.md)

## Controlling-source clarification

The user confirmed that the attached split PDFs are the Tamil Digital Library source and that the Wikisource copy is the same copy. Routine transcription therefore uses **only the attached PDFs**. No external-site lookup or mirror comparison is required unless the user explicitly requests it.


## Exact next activity

Proceed with the next **10-scan T1 source-inventory batch: overall scans36–45 / Part002 local pages6–15**.

The incoming Part001→Part002 boundary is already audited as **GENUINE CONTINUATION**. Create canonical records with exact Part002 provenance and only visibly printed page numbers. Keep text-incomplete records `partial`; do not advance them to T2/T3.

The full-text backlog for scans6–35 remains mandatory before Tamil archival closure.
