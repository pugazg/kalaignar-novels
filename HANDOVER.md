# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Current work: `works/pudhaiyal/`

## Current authority rule

The native scan controls page identity, headings, punctuation, quotation marks, paragraph/section structure, long dashes, physical line/page breaks, separators and chapter/scene transitions.

### Pudhaiyal lexical-preservation override — scan 280 onward

By explicit user instruction, supplied Gemini transcription controls **WORDS / lexical text** from scan 280 onward. Keep supplied words, spelling, suffixes, lexical forms, wording and supplied lexical spacing; do not source-correct a supplied form from native visual evidence.

For Part 007, uploaded `p7.md` is the controlling lexical baseline. Three complete omissions discovered during visual reconciliation were restored only after the user's explicit 2026-09-02 instruction **`insert all three omissions`**:

- scan 304 — `நீ`;
- scan 305 — `என்ன`;
- scan 315 — `சரி...... வா! வா!......`.

No broader lexical source-correction permission was given. Scan 343 therefore retains supplied `అది` despite native Tamil `அது`.

Source/split PDFs and uploaded baseline files must never be committed.

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
- verified / structurally completed: **49 / 49**
- Part-007 needs-review: **0**
- Tamil audit: **PASSED**
- assembled Tamil consistency check: **PASSED**
- assembled Tamil: **through scan 343 / printed 339**
- state: **`assembled-tamil-checked / controlled-English-next`**
- page map: `works/pudhaiyal/indexes/part-007-page-map.md`
- latest fidelity: `works/pudhaiyal/notes/visual-fidelity-scans-318-343.md`
- Tamil audit record: `works/pudhaiyal/notes/part-007-tamil-audit.md`
- assembled check: `works/pudhaiyal/notes/part-007-assembled-tamil-check.md`

### Verified assembled progression through scan 343

- scan 294→295: `‘லாக்` + `அப்’பில்` → **`‘லாக் அப்’பில்`** across the Part-006→007 derivative split;
- Chapter 33 continues through scan 297, where it closes before Chapter 34 opens;
- chapter 34 opens scan 297 and closes scan 306;
- chapter 35 opens scan 307 and closes scan 317;
- chapter 36 opens scan 317 and closes scan 324;
- scan 319 contains the first Chapter-36 four-star memory transition;
- scan 322 contains the second Chapter-36 four-star transition; `விடியற்காலை...` remains structurally repositioned after the overnight dialogue without lexical alteration;
- chapter 37 opens scan 324;
- scan 326 contains a four-star internal transition;
- scan 330 contains another four-star internal transition and closes chapter 37 at the foot rule;
- chapter 38 opens scan 331 and closes scan 340;
- chapter 39 opens scan 340 and remains open at scan 343;
- scan 343 ends at `அதிர்ஷ்`, with no closing quotation or sentence punctuation.

Part 007 is therefore **Tamil-audited and assembled-Tamil checked, but not yet translated/source-checked/bilingual-reviewed**. Its derivative endpoint is open and is not a novel ending. Source beyond scan 343 remains required for whole-work completion.

## Aggregate durable state

- canonical records: **343**
- verified / completed: **336**
- needs-review: **7 — only Part 005 scans 215–219, 223–224**
- partial: **0**
- Parts 001–006: **part-complete**
- Part 007: **Tamil audit + assembled-Tamil check PASSED**
- assembled Tamil: part-reviewed continuously through scan **343**
- source-checked / bilingual-reviewed English: through scan **294**
- received source coverage: through scan **343 / printed 339**
- whole-work Tamil / English / release gates: not yet eligible

## Exact next activity

Perform the **Part-007 controlled English translation and source check across scans 295–343** from the checked assembled Tamil layer. Continue Chapter 33 across the Part-006 boundary, translate Chapters 34–39 while preserving internal transitions and source-specific oddities, and leave Chapter 39 open where the Tamil stops at `அதிர்ஷ்`. After English source checking passes, run the Part-007 bilingual review before marking the split `part-complete`.