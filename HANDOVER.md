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

- Part 001: `TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf` — source scans 1–49
- Part 002: `TVA_BOK_0064097_புதையல்_part_002_pages_50-98.pdf` — source scans 50–98
- Part 003: `TVA_BOK_0064097_புதையல்_part_003_pages_99-147.pdf` — source scans 99–147

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

Important repaired examples include scan 4 `நூல் நிலையப் பதிப்பு ரூ 6/-`, scan 11 `இருக்கிறான்னு`, scan 24 `அவர்களை நோக்கி`, scan 25 `எதோ மருந்தொன்றை`, scan 31 no assistant-inserted full stop after `மூர்ச்சை யடைந்தான்`, scan 75 `போயிட்டுதா?`, scan 99 restoration of `சொல்வேன் என்று... நான் யாருடைய...`, scan 104 `நெடு நாள் பழக்கமா?`, and scan 106 `நான் வரத்தான் வேண்டுமா?`.

## Canonical Tamil state

- page records created: **137**
- verified: **137**
- needs-review: **0**
- partial: **0**
- unresolved readings through scan 137: **0**
- known-prefix not-started: **13** — scans 138–150
- full-source page-map coverage: **INCOMPLETE**
- Tamil whole-work audit: not yet eligible
- assembled Tamil whole-work layer: not yet eligible for final pass
- English whole-work verification: not yet eligible
- release-readiness: blocked until complete source

Part 003 canonical progress:

- scans 99–118 — verified after backward-integrity re-audit;
- scans 119–128 — verified from the previous Iteration-11 baseline pass;
- scans 129–137 — **9 / 9 verified** against native split pages 31–39;
- latest fidelity record: `works/pudhaiyal/notes/visual-fidelity-scans-129-137.md`.

Important latest source-established results:

- scan 130 `பயன்படுத்திக்கொள்வதாக்கும்`;
- scan 131 `இதை நிச்சயமாகத் தெரிந்து கொள்!`;
- scan 131 `நிச்சயமாகத் தெரிகிறது—நீங்கள் பைத்தியக்காரர் இல்லை!`;
- the user baseline was labelled printed pages 126–135 but actually stopped at printed 134; scan 137 / printed 135 was restored directly from native source;
- scan 137 preserves `பிறந்தத் தரணி—`, source-odd `புழுதி மண்ணுகப்`, and the physical endpoint `என் சோக வாழ்` without guessing the continuation.

Scan 128 closes chapter 13 and begins chapter 14 on the same physical page. Scan 137 remains inside chapter 14 and ends mid-word; scan 138 continues it and also contains the known chapter 14 → 15 transition.

## Part-completion status

### Part 001 — scans 1–49

**`part-complete`**

- canonical Tamil: 49 / 49 verified
- part Tamil audit: PASSED
- assembled Tamil: PASSED through scan 49
- English source check: PASSED through scan 49
- bilingual review: PASSED
- review: `works/pudhaiyal/translations/en/PART_001_REVIEW.md`

### Part 002 — scans 50–98

**`part-complete`**

- canonical Tamil: 49 / 49 verified
- part Tamil audit: PASSED
- assembled Tamil: PASSED through scan 98
- English source check: PASSED through scan 98
- bilingual review: PASSED
- review: `works/pudhaiyal/translations/en/PART_002_REVIEW.md`

Boundary checks closed:

- scan 49 → 50 — one continuous chapter-4 embedded-tale sentence; no derivative break introduced;
- scan 98 → 99 — scan 98's four-star separator is source-printed; verified scan 99 remains chapter 10, so the derivative boundary is not a chapter or novel ending.

### Part 003 — scans 99–147

**IN PROGRESS — not part-complete**

- scans 99–137: canonical Tamil verified
- scans 138–147: canonical Tamil not started
- structural native preflight through scan 147: complete
- part-level Tamil audit: not yet eligible
- assembled Tamil / English / bilingual review: must wait until the whole derivative's canonical Tamil is complete

## Exact next activity

Resume **Part 003 canonical Tamil at scan 138 / printed page 136 / split part-003 page 40** using the next user-supplied baseline and the permanent old-glyph rule.

Important boundary:

- scan 137 ends physically at `என் சோக வாழ்`;
- do not guess its continuation;
- scan 138 is source-confirmed to close chapter 14 and begin chapter 15 on the same physical page.

Do not start a later split and do not begin Part-003 English translation early.

After scans **138–147** are all source-verified, complete the remaining workflow for **Part 003 then and there**:

1. synchronize the part-003 page map/status documents;
2. run the Part-003 Tamil audit across scans 99–147;
3. assemble Part-003 Tamil, preserving the verified scan 98 → 99 continuity and all later physical joins;
4. translate the audited Part-003 material under the shared English plan;
5. source-check the English against canonical Tamil;
6. run the Part-003 bilingual review;
7. mark Part 003 `part-complete` only if every applicable check passes;
8. only then move to the next PDF split.
