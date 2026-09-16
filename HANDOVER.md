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
- Part001: **overall scans1–30**
- all split PDFs are image-only working sources and are not committed to Git
- canonical `scan_page` uses the global **1–477** sequence and never resets per Part

Multipart policy:
- `works/payumpuli-pandaraka-vanniyan/MULTIPART_SOURCE_POLICY.md`

## Durable state

- overall source intake: **COMPLETE / REGISTERED**
- per-Part intake registration: **16 / 16 COMPLETE**
- global split coverage: **477 / 477**
- canonical page records: **15 / 477**
- T1 complete: **5 / 477** — scans1–5
- T1 partial: **10 / 477** — scans6–15
- T2 reviewed: **5 / 477**
- T3 reviewed: **5 / 477**
- verified: **2 / 477**
- needs-review: **3 / 477**
- partial: **10 / 477**
- assembled Tamil: **BLOCKED**
- English: **BLOCKED**

### Opening scans1–5

Reviewed through T3.

- scans1–2 — **VERIFIED**
- scan3 — **needs-review**: small telephone-number digits unresolved
- scan4 — **needs-review**: copy-specific handwritten/stamp detail unresolved
- scan5 — **needs-review**: compact publication/bibliographic block unresolved

Checkpoint files:
- `T1_BATCH_001_005.md`
- `T2_BATCH_001_005.md`
- `T3_BATCH_001_005.md`

### Current 10-page batch — scans6–15

User-requested iteration size from this point: **10 scans**.

The ten source pages were directly inspected and ten canonical records were created.

Structural capture:
- scans6–9 — `அணிந்துரை`
- scan10 — `பதிப்புரை`
- scan11 — verse / epigraph
- scan12 — secondary title / illustrated divider
- scans13–15 — `தோரண வாயில்`
- visible printed pages:
  - scan13 → **2**
  - scan14 → **3**
  - scan15 → **4**

Current state: **T1 PARTIAL**.

Reason: the current rendered page view supports structure/page-number identification but not a sufficiently reliable complete character-by-character transcription of the dense Tamil prose. No unreadable body text was invented or reconstructed.

Detailed checkpoint:
- `works/payumpuli-pandaraka-vanniyan/T1_BATCH_006_015.md`

## Exact next activity

Remain on **Part001 T1 overall scans6–15 / local pages6–15**.

Complete the full line-by-line Tamil source text for all ten `partial` canonical records from a sufficiently detailed source rendering. Only then:
1. promote the ten records from `partial` to `needs-review`;
2. synchronize controls;
3. commit T1 completion;
4. move to T2 for scans6–15.

Do **not** advance to scans16–25 while scans6–15 remain text-incomplete.
