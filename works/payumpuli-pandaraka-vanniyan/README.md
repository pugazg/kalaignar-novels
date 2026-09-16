# பாயும்புலி பண்டாரக வன்னியன்

**ஆசிரியர்:** கலைஞர் மு. கருணாநிதி  
**பதிப்பகம்:** ராக்போர்ட் பப்ளிகேஷன்ஸ்  
**பதிப்பு:** முதல் பதிப்பு — 1991  
**Complete source:** 477 physical scans  
**Working source:** 16 split PDFs — all supplied  
**Source PDFs in repository:** No

## Current status

**PART001 ACTIVE / scans1–5 reviewed through T3 / scans6–15 T1 PARTIAL**

- source family: **TVA_BOK_0065744**
- source Parts: **16/16 SUPPLIED / REGISTERED**
- global physical coverage: **477/477**
- canonical page records: **15/477**
- T1 complete: **5/477** — scans1–5
- T1 partial: **10/477** — scans6–15
- T2 reviewed: **5/477**
- T3 reviewed: **5/477**
- verified: **2/477**
- needs-review: **3/477**
- partial: **10/477**
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

Current 10-page iteration:
- overall scans **6–15**
- Part001 local pages **6–15**

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

## Current source-fidelity hold

All ten scans6–15 were directly inspected and canonical records were created.

The available rendered view reliably supports:
- scan / Part-local identity;
- page/section function;
- visible printed-page numbers;
- source-visible headings.

It does **not** support a sufficiently reliable complete line-by-line transcription of the dense Tamil prose. The records therefore remain `partial`; no unreadable text has been reconstructed or guessed.

Detailed checkpoints:
- [`T1_BATCH_006_015.md`](T1_BATCH_006_015.md)
- [`SOURCE_ACCESS_REVIEW_T1_006_015.md`](SOURCE_ACCESS_REVIEW_T1_006_015.md)

A same-source official Tamil Digital Library access route was also checked. It confirms the exact source-family/edition identity, but did not expose a usable page-text layer or sufficiently detailed alternate rendering for exact Tamil transcription. No external wording was substituted.

## Exact next activity

Remain on **T1 overall scans6–15 / Part001 local pages6–15**.

Complete the full line-by-line Tamil source text for these ten records from a sufficiently detailed source rendering. Only after all ten are text-complete may they advance from `partial` to `needs-review` and T2 begin.

Do **not** advance to scans16–25 while scans6–15 remain text-incomplete.
