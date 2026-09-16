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
- Part ranges:
  - 001 — **1–30**
  - 002 — **31–60**
  - 003 — **61–90**
  - 004 — **91–120**
  - 005 — **121–150**
  - 006 — **151–180**
  - 007 — **181–210**
  - 008 — **211–240**
  - 009 — **241–270**
  - 010 — **271–300**
  - 011 — **301–330**
  - 012 — **331–360**
  - 013 — **361–390**
  - 014 — **391–420**
  - 015 — **421–450**
  - 016 — **451–477**
- all split PDFs: **image-only / rendered pages control**
- split PDFs committed to Git: **No**
- split hashes: **PENDING**

### Multipart rules

Adapted from the Kuraloviyam split-source workflow:

1. canonical `scan_page` uses overall scans **1–477** and never resets per Part;
2. page records carry `part`, `part_page`, and exact `source_filename`;
3. there is one unified canonical `pages/` directory;
4. split boundaries are physical access boundaries only;
5. boundary state must be determined from adjacent source pages;
6. later Parts may serve as boundary witnesses but do not leapfrog the global active frontier.

Authoritative policy: `works/payumpuli-pandaraka-vanniyan/MULTIPART_SOURCE_POLICY.md`.

### Durable state

- overall source intake: **COMPLETE / REGISTERED**
- per-Part intake registration: **16 / 16 COMPLETE**
- global split coverage: **477 / 477**
- canonical page records: **5 / 477**
- T1: **5 / 477 COMPLETE through overall scan5 / Part001 local5**
- T2: **NOT STARTED**
- T3: **NOT STARTED**
- Part-boundary classifications: **pending direct visual audit**
- terminal page function at scan477: **pending direct visual audit**
- assembled Tamil: **BLOCKED**
- English: **BLOCKED**

### Part 001 opening observations

- scan1 cover;
- scans2–5 title/publisher/bibliographic front matter;
- scans6–9 `அணிந்துரை`;
- scan10 `பதிப்புரை`;
- scan11 epigraph/verse;
- scan12 secondary title divider;
- scan13 onward `தோரண வாயில்`, exact structural role provisional.

Active authorities:
- `works/payumpuli-pandaraka-vanniyan/README.md`
- `works/payumpuli-pandaraka-vanniyan/SOURCE_INTAKE.md`
- `works/payumpuli-pandaraka-vanniyan/MULTIPART_SOURCE_POLICY.md`
- `works/payumpuli-pandaraka-vanniyan/metadata/source.md`
- `works/payumpuli-pandaraka-vanniyan/indexes/page-map.md`
- `works/payumpuli-pandaraka-vanniyan/audit.md`
- `works/payumpuli-pandaraka-vanniyan/SOURCE_INTAKE_PART_001.md` … `SOURCE_INTAKE_PART_016.md`
- `NOVEL_PROCESSING_GUIDE.md`
- `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`
- `SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`

## Previous work — சுருளிமலை

Surulimalai remains fully closed. Do not reopen it for routine continuation.

## Exact next activity

Perform **Part 001 T3 — overall scans1–5 / local pages1–5** from:

`TVA_BOK_0065744_பாயும்புலி_பண்டாரக_வன்னியன்_part_001_pages_1-30.pdf`

T1 durable state:
- five unified canonical records exist for scans1–5;
- all five carry Part001 provenance;
- all five remain `needs-review`;
- T1 carried uncertainties: scan3 telephone-number digits; scan5 compact publication/bibliographic block.

T2 requirements:
1. independently re-read all five source pages;
2. explicitly apply the historical-glyph checklist;
3. revisit the two carried T1 uncertainties without guessing;
4. preserve source spelling/punctuation and non-body separation;
5. update only source-supported readings;
6. synchronize page map, README, audit, handover and next prompts;
7. commit T2;
8. **stop before T3**.
