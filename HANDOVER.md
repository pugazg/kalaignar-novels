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

The former `150 pages total` conclusion is permanently withdrawn. Scans 1–150 are only a known prefix.

## Available access derivatives

- Part 001: `TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf` — source scans 1–49 — **part-complete**
- Part 002: `TVA_BOK_0064097_புதையல்_part_002_pages_50-98.pdf` — source scans 50–98 — **part-complete**
- Part 003: `TVA_BOK_0064097_புதையல்_part_003_pages_99-147.pdf` — source scans 99–147 — **part-complete**

These are access derivatives of one edition, not separate bibliographic works.

## User-approved split-part completion workflow

Going forward, **finish the complete safe workflow for each supplied split before moving to the next split**.

Read and follow:

`works/pudhaiyal/PART_COMPLETION_WORKFLOW.md`

For each split:

1. page map and canonical `pages/` records;
2. native visual/textual fidelity pass;
3. resolution/documentation of uncertainty;
4. part-level Tamil audit;
5. incremental assembled Tamil reading layer;
6. controlled English translation under the shared translation plan;
7. part-level bilingual source check;
8. part status synchronization and `part-complete` checkpoint.

A split boundary is provenance only. It must never create a false chapter/scene boundary. Cross-split words, sentences, paragraphs and chapters must remain continuous in derived layers.

Final whole-work Tamil audit, final whole-work assembled-Tamil pass, whole-work English `verified`, and release-readiness remain blocked until the complete source edition and true ending/back matter are known.

## Backward-integrity recovery

Central record: `works/pudhaiyal/notes/backward-integrity-audit-001-118.md`

Status: **COMPLETE through scan 118**.

Representative repaired/protected readings include scan 4 `நூல் நிலையப் பதிப்பு ரூ 6/-`, scan 11 `இருக்கிறான்னு`, scan 24 `அவர்களை நோக்கி`, scan 25 `எதோ மருந்தொன்றை`, scan 31 no assistant-inserted full stop after `மூர்ச்சை யடைந்தான்`, scan 75 `போயிட்டுதா?`, scan 99 restoration of `சொல்வேன் என்று... நான் யாருடைய...`, scan 104 `நெடு நாள் பழக்கமா?`, scan 106 `நான் வரத்தான் வேண்டுமா?`, and the later native-fidelity records through scan 147.

## Canonical Tamil state

- page records created: **147**
- verified: **147**
- needs-review: **0**
- partial: **0**
- unresolved readings through scan 147: **0**
- known-prefix not-started: **3** — scans 148–150
- full-source page-map coverage: **INCOMPLETE**
- Tamil whole-work audit: not yet eligible
- assembled Tamil whole-work final pass: not yet eligible
- English whole-work verification: not yet eligible
- release-readiness: blocked until complete source

Part-003 fidelity coverage:

- scans 99–108 — verified;
- scans 109–118 — verified after backward-integrity re-audit;
- scans 119–128 — verified;
- scans 129–137 — verified;
- scans 138–147 — verified from the final supplied Part-003 baseline plus native source inspection.

Part-003 protected examples include:

- scan 131 `நிச்சயமாகத் தெரிகிறது—நீங்கள் பைத்தியக்காரர் இல்லை!`;
- scan 137 `பிறந்தத் தரணி—`, source-odd `புழுதி மண்ணுகப்`;
- scan 137 `வாழ்` → scan 138 `விலே` = `வாழ்விலே`;
- scans 141–142 source-odd `பழுமாகப்`;
- scan 144 source-odd `தடுப்பானேன்`, `அவர்களே ஊமையாகியது`;
- scan 145 `சிறுவனுயிற்றே நீ`;
- scan 146 `இளம் தளிராக!`;
- scan 147 `சூடு ஆறிவிடாமல் அருந்துகிற தேநீர்`;
- scan 147 physical endpoint `அடங்கித்தான் போய்` — incomplete, no continuation inferred.

## Part-completion status

### Part 001 — scans 1–49

**`part-complete`**

- canonical Tamil: 49 / 49 verified
- part Tamil audit: PASSED
- assembled Tamil: PASSED
- English source check: PASSED
- bilingual review: PASSED
- review: `works/pudhaiyal/translations/en/PART_001_REVIEW.md`

### Part 002 — scans 50–98

**`part-complete`**

- canonical Tamil: 49 / 49 verified
- part Tamil audit: PASSED
- assembled Tamil: PASSED
- English source check: PASSED
- bilingual review: PASSED
- review: `works/pudhaiyal/translations/en/PART_002_REVIEW.md`

Boundary checks closed:

- scan 49 → 50 — one continuous chapter-4 embedded-tale sentence;
- scan 98 → 99 — scan 98's four-star separator is source-printed and chapter 10 continues on scan 99.

### Part 003 — scans 99–147

**`part-complete`**

- canonical Tamil: **49 / 49 verified**
- part Tamil audit: **PASSED**
- assembled Tamil: **PASSED through scan 147**
- English source check: **PASSED through scan 147**
- bilingual review: **PASSED**
- Tamil audit: `works/pudhaiyal/notes/part-003-tamil-audit.md`
- bilingual review: `works/pudhaiyal/translations/en/PART_003_REVIEW.md`

Structure inside the derivative:

- scan 101 closes chapter 10;
- scan 102 begins chapter 11;
- scan 110 closes chapter 11 / begins chapter 12;
- scan 119 begins chapter 13;
- scan 128 closes chapter 13 / begins chapter 14;
- scan 138 closes chapter 14 / begins chapter 15;
- scan 146 closes chapter 15 / begins chapter 16;
- scan 147 remains chapter 16 and ends mid-sentence.

## Exact next activity

Do **not** continue from grammar or the page-map placeholder alone.

Obtain / attach the next source derivative beginning at **scan 148 / printed page 146**. On receipt:

1. fetch live `main` first;
2. inspect the new derivative's first native page;
3. establish the continuation of scan 147's incomplete **`அடங்கித்தான் போய்`** from source pixels;
4. map the entire new derivative;
5. complete that derivative's full per-PDF workflow through `part-complete` before moving to another split.

Do not infer the true ending, full scan count, later chapter structure or back matter until source evidence is available.