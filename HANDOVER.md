# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- **LIVE MAIN IS AUTHORITATIVE.**
- Current active work: **`works/payumpuli-pandaraka-vanniyan/`**
- Source PDF is **not committed**.

## Active work — பாயும்புலி பண்டாரக வன்னியன்

### Source identity

- filename: `TVA_BOK_0065744_பாயும்புலி_பண்டாரக_வன்னியன்.pdf`
- physical scans: **477**
- file size: **456,236,783 bytes**
- format: **image-only scanned PDF**
- SHA-256: **PENDING**
- title: **பாயும்புலி பண்டாரக வன்னியன்**
- author: **கலைஞர் மு. கருணாநிதி**
- publisher: **ராக்போர்ட் பப்ளிகேஷன்ஸ்**
- edition: **முதல் பதிப்பு, 1991**

### Durable intake state

- source registration: **COMPLETE**
- opening source review: **scans1–20 COMPLETE for intake classification**
- preview/index limit: **150 rendered pages**; this is not the physical source extent
- scans151–477: **UNINSPECTED in current preview, not absent**
- canonical page records: **0 / 477**
- T1: **NOT STARTED**
- T2: **NOT STARTED**
- T3: **NOT STARTED**
- terminal boundary: **NOT YET AUDITED**
- assembled Tamil: **BLOCKED**
- English: **BLOCKED**

Opening observations:
- scan1 cover;
- scans2–5 title/publisher/bibliographic front matter;
- scans6–9 `அணிந்துரை`;
- scan10 `பதிப்புரை`;
- scan11 epigraph/verse page;
- scan12 secondary title divider;
- scans13–20 source-visible `தோரண வாயில்`, printed pages2–9.
- structural role of `தோரண வாயில்`: **PROVISIONAL until complete source transition review**.

Active authorities:
- `works/payumpuli-pandaraka-vanniyan/SOURCE_INTAKE.md`
- `works/payumpuli-pandaraka-vanniyan/metadata/source.md`
- `works/payumpuli-pandaraka-vanniyan/indexes/page-map.md`
- `works/payumpuli-pandaraka-vanniyan/README.md`
- `works/payumpuli-pandaraka-vanniyan/audit.md`
- root `NOVEL_PROCESSING_GUIDE.md`
- root `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`
- root `SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`

## Previous work — சுருளிமலை

Surulimalai remains **fully closed**:
- Tamil canonical pages **198/198 VERIFIED**;
- assembled Tamil **26/26 VERIFIED / PASS**;
- English **26/26 VERIFIED / COMPLETE / CLOSED**;
- unresolved English holds **0**.

Do not reopen it for routine continuation.

## Exact next activity

Perform **T1 direct transcription / canonical page creation for scans1–5 only** of `பாயும்புலி பண்டாரக வன்னியன்`.

Requirements:
1. read each scan directly from source pixels;
2. create one page record per physical scan;
3. preserve only visibly printed page numbers;
4. separate stamps / handwriting / accession marks from printed prose;
5. preserve source spelling, punctuation and historical glyph identity;
6. mark all five records `needs-review` pending T2;
7. update page map, work README, audit, handover and next prompts;
8. commit T1;
9. **stop before T2**.
