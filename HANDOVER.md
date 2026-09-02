# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Current work: `works/pudhaiyal/`

## Current authority rule

The native scan controls page identity, headings, punctuation, quotation marks, paragraph/section structure, long dashes, physical line/page breaks, separators and chapter/scene transitions.

### Pudhaiyal lexical-preservation override — scan 280 onward

By explicit user instruction, supplied Gemini transcription controls **WORDS / lexical text** from scan 280 onward. Keep supplied words, spelling, suffixes, lexical forms, wording and supplied lexical spacing; do not source-correct a supplied form from native visual evidence. If the supplied baseline omits a complete word/span, flag it rather than silently supplying source text.

For Part 007, uploaded `p7.md` is the controlling lexical baseline. Source/split PDFs and uploaded baseline files must never be committed.

## Source identity — புதையல்

- original filename: `TVA_BOK_0064097_புதையல்.pdf`
- author: கலைஞர் மு. கருணாநிதி, எம். எல். ஏ.
- publisher: அன்புப் பதிப்பகம், பொறையார் :: தஞ்சை மாவட்டம்
- edition: மூன்றாம் பதிப்பு — செப்டம்பர் 1961
- Tamil Digital Library bibliographic extent: 443 p.
- exact full-PDF scan count / full-source SHA-256: pending complete source access

## Completed derivatives

- Part 001 — scans 1–49 — **part-complete**
- Part 002 — scans 50–98 — **part-complete**
- Part 003 — scans 99–147 — **part-complete**
- Part 004 — scans 148–196 — **part-complete**
- Part 005 — scans 197–245 — **part-complete with explicit source-damage qualification**
- Part 006 — scans 246–294 — **part-complete**

Part-005 source-damage qualification remains attached to scans **215–219 and 223–224**.

## Active derivative — Part 007

Source: `TVA_BOK_0064097_புதையல்_part_007_pages_295-343.pdf`

- physical pages: **49**
- source scans: **295–343**
- printed pages: **291–339**
- derivative size: **57,055,891 bytes**
- derivative SHA-256: `9ead2089eb238273f7b0fd0dbe2f929095730fbf3fc218719e66fe0d472bb15c`
- lexical baseline: uploaded `p7.md`, SHA-256 `a804b914b88050ca8d31142cb00d7491c94e89ff1fb7e564fdd348bdf14b1c59`
- canonical records: **49 / 49**
- verified / structurally completed: **46 / 49**
- needs-review: **3 — scans 304, 305, 315**
- not-started: **0**
- state: **`canonical-complete / lexical-omission-disposition-pending`**
- page map: `works/pudhaiyal/indexes/part-007-page-map.md`
- latest fidelity: `works/pudhaiyal/notes/visual-fidelity-scans-318-343.md`

### Unresolved Part-007 lexical omissions

- scan 304 — native `நீ` is absent from `p7.md`;
- scan 305 — native `என்ன` is absent from `p7.md`;
- scan 315 — native quoted `சரி...... வா! வா!......` is absent from `p7.md`.

None has been silently inserted. These three records block the Part-007 Tamil audit until explicit disposition.

### Verified structural progression through scan 343

- scan 294→295: `‘லாக்` + `அப்’பில்` → **`‘லாக் அப்’பில்`**;
- scan 297 opens chapter 34;
- scan 307 opens chapter 35;
- scan 317 opens chapter 36;
- scan 322 has a native four-star internal transition; `விடியற்காலை...` was structurally repositioned after the overnight dialogue without lexical alteration;
- scan 324 closes chapter 36 and opens chapter **37**;
- scan 330 has a four-star internal transition and closes chapter 37 at the foot rule;
- scan 331 opens chapter **38**;
- scan 340 closes chapter 38 and opens chapter **39**;
- scan 343 remains chapter 39 and ends open at `அதிர்ஷ்`, with no closing quotation or sentence punctuation;
- scan 343 retains supplied `p7.md` lexical `అది` despite native Tamil `அது`, because the standing rule forbids source-correcting supplied lexical text.

Part 007 is therefore **canonical-complete but not Tamil-audited**. Its derivative endpoint is open and is not a novel ending. Source beyond scan 343 remains required for whole-work completion.

## Aggregate durable state

- canonical records: **343**
- verified / completed: **333**
- needs-review: **10 — Part 005 scans 215–219, 223–224; Part 007 scans 304, 305, 315**
- partial: **0**
- Parts 001–006: **part-complete**
- Part 007: **canonical-complete; audit blocked only by omission disposition**
- assembled Tamil: part-reviewed through scan **294**
- source-checked / bilingual-reviewed English: through scan **294**
- received source coverage: through scan **343 / printed 339**
- whole-work Tamil / English / release gates: not yet eligible

## Exact next activity

Obtain explicit user/baseline disposition for scans **304, 305 and 315**. If the source-visible omitted spans are authorized for insertion, update those three canonical records and their fidelity/status notes; if they are to remain omitted, record that qualification explicitly. Then run the **Part-007 Tamil audit across scans 295–343**. Do not begin Part-007 assembled Tamil or English until that audit passes.