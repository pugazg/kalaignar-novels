# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- **LIVE MAIN IS AUTHORITATIVE.**
- Active work: **`works/payumpuli-pandaraka-vanniyan/`**

## Active work — பாயும்புலி பண்டாரக வன்னியன்

### Complete source family

- source family: **TVA_BOK_0065744**
- complete physical extent: **477 scans**
- working source Parts: **16 / 16 supplied**
- Parts001–015: **30 pages each**
- Part016: **27 pages**
- source PDFs remain outside Git
- canonical `scan_page` uses the global **1–477** sequence and never resets per Part

Controlling multipart policy:
- `works/payumpuli-pandaraka-vanniyan/MULTIPART_SOURCE_POLICY.md`

## Durable state

- source intake: **COMPLETE / REGISTERED**
- per-Part registration: **16/16 COMPLETE**
- split coverage: **477/477**
- canonical page records: **35/477**
- T1 text-complete: **5/477 — scans1–5**
- T1 partial inventory: **30/477 — scans6–35**
- T2 reviewed: **5/477**
- T3 reviewed: **5/477**
- verified: **2/477**
- needs-review: **3/477**
- partial: **30/477**
- audited split boundaries: **1/15**
- assembled Tamil: **BLOCKED**
- English: **BLOCKED**

## Opening scans1–5

Reviewed through T3.

- scans1–2 — **VERIFIED**
- scan3 — **needs-review**: small telephone-number digits unresolved
- scan4 — **needs-review**: copy-specific handwritten/stamp detail unresolved
- scan5 — **needs-review**: compact publication/bibliographic block unresolved

Checkpoint files:
- `T1_BATCH_001_005.md`
- `T2_BATCH_001_005.md`
- `T3_BATCH_001_005.md`

## T1 inventory through scan35

User-requested iteration size from scan6 onward: **10 overall scans**.

Checkpoint files:
- `works/payumpuli-pandaraka-vanniyan/T1_BATCH_006_015.md`
- `works/payumpuli-pandaraka-vanniyan/T1_BATCH_016_025.md`
- `works/payumpuli-pandaraka-vanniyan/T1_BATCH_026_035.md`

Observed structure:
- scans6–9 — `அணிந்துரை`
- scan10 — `பதிப்புரை`
- scan11 — verse / epigraph; attribution `எழுச்சிக் கவிஞர் காசி ஆனந்தன்`
- scan12 — secondary illustrated title/divider
- scan13 onward — `தோரண வாயில்` body flow

Visible printed page mapping is continuous from scan13:
- scan13 → 2
- …
- scan30 → 19
- scan31 → 20
- …
- scan35 → 24

## Split boundary 30→31

Directly audited from the attached Part001 and Part002 PDFs.

Classification: **GENUINE CONTINUATION**.

- scan30 = Part001 local30 / printed page19
- scan31 = Part002 local1 / printed page20
- body flow continues across the split
- no artificial textual break is introduced

## Source rule

The attached split PDFs are the controlling source. The user confirmed these are the Tamil Digital Library copy and that Wikisource is the same copy.

Do not access external mirrors unless explicitly asked. Do not characterize the source as defective or unusually dense merely because canonical text entry is incomplete.

Forward T1 inventory may continue while full-text entry remains backlogged, but:
- text-incomplete pages remain `partial`;
- T2/T3 do not advance on partial pages;
- assembled Tamil / English remain blocked;
- final archival closure requires full-text backlog resolution.

## Exact next activity

Process **overall scans36–45 / Part002 local pages6–15** as the next 10-scan T1 source-inventory batch.

For each scan:
1. inspect the attached Part002 page;
2. create one canonical record;
3. preserve global `scan_page`, `part: 2`, local `part_page`, and exact Part002 `source_filename`;
4. record only visibly printed page numbers;
5. preserve section/page function and non-body marks;
6. enter any source text that can be read safely;
7. keep text-incomplete records `partial`;
8. synchronize controls and commit;
9. stop before scans46–55.

Do not start T2/T3 for partial pages.

Full-text backlog currently: **scans6–35**.
