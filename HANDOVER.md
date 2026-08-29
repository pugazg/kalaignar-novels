# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Fresh-chat prompt: `NEXT_NOVEL_CHAT_PROMPT.md`

## Mandatory startup

Before changing the current work:

1. read `NOVEL_PROCESSING_GUIDE.md` completely;
2. read root `README.md`;
3. read this `HANDOVER.md` completely;
4. read `works/pudhaiyal/README.md`;
5. read `works/pudhaiyal/PART_COMPLETION_WORKFLOW.md` completely;
6. inspect live `main` and treat it as authoritative;
7. inspect the controlling split scan before changing canonical Tamil;
8. never commit the original source PDF or any split derivative PDF.

## Permanent source rule

The scan is the textual authority. User-supplied transcription is the comparison baseline. Do not replace an old-print Tamil reading because another form appears grammatically or orthographically more plausible. Any assistant-introduced change must be established from native source pixels. Ambiguous readings remain baseline-preserving and `needs-review`.

## Current work — புதையல்

Path: `works/pudhaiyal/`

Source identity:

- original filename: `TVA_BOK_0064097_புதையல்.pdf`
- author: கலைஞர் மு. கருணாநிதி, எம். எல். ஏ.
- publisher: அன்புப் பதிப்பகம், பொறையார் :: தஞ்சை மாவட்டம்
- edition: மூன்றாம் பதிப்பு
- edition line: `மூன்றாம் பதிப்பு: செப்டம்பர், 1961.`
- original attached size: 502,895,096 bytes
- Tamil Digital Library bibliographic extent: 443 p.
- exact full-PDF scan/page-object count: pending
- original SHA-256: pending exact byte-level access
- source/split PDFs committed: No

The former `150 pages total` conclusion is permanently withdrawn. The source extends beyond that early prefix.

## User-approved split-part workflow

Finish the complete safe workflow for each supplied split before moving to the next split. Follow `works/pudhaiyal/PART_COMPLETION_WORKFLOW.md`:

1. canonical `pages/` records and page mapping;
2. native visual/textual fidelity;
3. uncertainty resolution / `needs-review` handling;
4. part-level Tamil audit;
5. assembled Tamil;
6. controlled English translation;
7. bilingual source check;
8. status synchronization and `part-complete`.

A split boundary is provenance only. It must never create a false word, sentence, paragraph, scene or chapter boundary.

Final whole-work Tamil audit, final assembled-Tamil pass, whole-work English `verified`, and release-readiness remain blocked until the complete source edition and true ending/back matter are known.

## Completed access derivatives

| Part | Split | Source scans | Printed range | State |
|---|---|---:|---:|---|
| 001 | `TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf` | 1–49 | through 47 | **part-complete** |
| 002 | `TVA_BOK_0064097_புதையல்_part_002_pages_50-98.pdf` | 50–98 | 48–96 | **part-complete** |
| 003 | `TVA_BOK_0064097_புதையல்_part_003_pages_99-147.pdf` | 99–147 | 97–145 | **part-complete** |
| 004 | `TVA_BOK_0064097_புதையல்_part_004_pages_148-196.pdf` | 148–196 | 146–194 | **part-complete** |

All four supplied splits have passed canonical Tamil fidelity, part Tamil audit, assembled Tamil, English source check and bilingual review.

## Part 004 completion checkpoint

- source scans: **148–196**
- canonical pages: **49 / 49 verified**
- needs-review: **0**
- unresolved readings: **0**
- Tamil audit: `works/pudhaiyal/notes/part-004-tamil-audit.md` — **PASSED**
- assembled Tamil: **PASSED through scan 196**
- English bilingual review: `works/pudhaiyal/translations/en/PART_004_REVIEW.md` — **PASSED**
- derivative-local map: `works/pudhaiyal/indexes/part-004-page-map.md` — **49 / 49 verified / part-complete**

Important continuity checks include:

- scan 147 `அடங்கித்தான் போய்` + scan 148 `விட்டார்கள்.` = `அடங்கித்தான் போய் விட்டார்கள்.`
- scan 158 `டாக்` + scan 159 `துரைக்கு` = `டாக்துரைக்கு`
- scan 173 `வள்ளி வெட்டப்` + scan 174 `பட வேண்டும்` = `வள்ளி வெட்டப்பட வேண்டும்`
- scan 187 `அதுகூட` + scan 188 `இல்லை எனக்கு.` = `அதுகூட இல்லை எனக்கு.`
- scan 193 `ஆகா` + scan 194 `ரமும்` = `ஆகாரமும்`
- scan 194 `வேண்டா` + scan 195 `மென்று` = `வேண்டாமென்று`
- scan 195 `ஒரு பெருமாள் கோவில்` + scan 196 `வாசல்—`

Part-004 chapter structure:

- scans 148–154: chapter 16 continuation; chapter 16 closes on scan 154
- scans 155–163: chapter 17; scan 163 closes 17 / begins 18
- scans 163–171: chapter 18
- scans 172–179: chapter 19; scan 179 closes 19 / begins 20
- scans 179–187: chapter 20; scan 187 closes 20 / begins 21
- scans 187–196: chapter 21; scan 196 closes 21 / begins chapter **22**

Scan **196 / printed page 194** is only the Part-004 endpoint. Chapter 22 continues in the next source split. Do not infer the next text.

## Aggregate durable state

- canonical page records: **196**
- verified continuously through scan **196**
- needs-review: **0**
- partial: **0**
- unresolved readings through scan 196: **0**
- backward integrity audit: **COMPLETE through scan 118**
- Parts 001–004: **part-complete**
- assembled Tamil: part-reviewed through scan 196
- English: bilingual part-reviewed through scan 196
- full-source page map: incomplete beyond scan 196
- final Tamil audit / English verification / release: not yet eligible

## Exact next activity

Obtain / attach the next source split beginning at **scan 197 / printed page 195**.

The first native-source check must continue chapter **22** from scan 196. Do not infer the continuation from grammar, context, OCR or an outside edition.

Then complete the full per-split workflow for that derivative before moving to another split.
