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

## Backward-integrity recovery

Central record: `works/pudhaiyal/notes/backward-integrity-audit-001-118.md`

Status: **COMPLETE through scan 118**.

Important repaired examples include scan 4 `நூல் நிலையப் பதிப்பு ரூ 6/-`, scan 11 `இருக்கிறான்னு`, scan 24 `அவர்களை நோக்கி`, scan 25 `எதோ மருந்தொன்றை`, scan 31 no assistant-inserted full stop after `மூர்ச்சை யடைந்தான்`, scan 75 `போயிட்டுதா?`, scan 99 restoration of `சொல்வேன் என்று... நான் யாருடைய...`, scan 104 `நெடு நாள் பழக்கமா?`, and scan 106 `நான் வரத்தான் வேண்டுமா?`.

## Canonical Tamil state

- page records created: **128**
- verified: **128**
- needs-review: **0**
- partial: **0**
- unresolved readings through scan 128: **0**
- known-prefix not-started: **22** — scans 129–150
- full-source page-map coverage: **INCOMPLETE**
- Tamil whole-work audit: not yet eligible
- assembled Tamil whole-work layer: not yet passed
- English whole-work verification: blocked until complete source
- release-readiness: blocked until complete source

Iteration 11 scans 119–128 / printed 117–126 are verified. Scan 128 closes chapter 13 and begins chapter 14 on the same physical page.

## User-approved split-part completion workflow

Going forward, **do not move immediately to the next split after transcription**.

Read and follow:

`works/pudhaiyal/PART_COMPLETION_WORKFLOW.md`

For each supplied split, complete every stage safely possible for that derivative before requesting/starting the next split:

1. page map and canonical pages;
2. native visual/textual fidelity pass;
3. resolution/documentation of uncertainty;
4. part-level Tamil audit;
5. incremental assembled Tamil reading layer;
6. controlled English translation under the shared translation plan;
7. part-level bilingual source check;
8. part status synchronization.

A derivative may reach `part-complete`, but the final whole-work Tamil audit, final assembled-Tamil pass, whole-work English verification and release report remain whole-source gates.

A split boundary is provenance only. It must never create a false chapter/scene boundary. Cross-split words, sentences and chapters must be joined reversibly in derived layers.

## Backfill status for first two supplied parts

Part-level Tamil audits have now been created and passed:

- `works/pudhaiyal/notes/part-001-tamil-audit.md` — scans 1–49: **PASSED**
- `works/pudhaiyal/notes/part-002-tamil-audit.md` — scans 50–98: **PASSED**
- work-level aggregation: `works/pudhaiyal/audit.md`

Both parts still need their downstream backfill under the new rule:

- incremental assembled Tamil;
- shared English translation plan / translation layer;
- part-level bilingual review;
- final `part-complete` checkpoint.

## Exact next activity

**Do not start scan 129 yet.**

Backfill the remaining workflow for **Part 001 first**, using only verified canonical `pages/` records and existing native-fidelity evidence:

1. create/check the incremental assembled Tamil for scans 1–49, preserving scan provenance and the scan 49 → 50 continuation;
2. establish the shared Pudhaiyal English translation plan and glossary conventions;
3. translate the audited Part 001 material in controlled batches;
4. source-check it against canonical Tamil;
5. record the Part 001 bilingual review and mark Part 001 `part-complete` only if all checks pass.

Then repeat the same downstream workflow for **Part 002 / scans 50–98**, including the scan 49 → 50 and scan 98 → 99 continuity checks.

Only after Parts 001 and 002 have been fully backfilled may forward transcription resume at **scan 129 / printed page 127 / part-003 page 31**.
