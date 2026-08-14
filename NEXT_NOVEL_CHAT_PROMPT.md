# Next Novel — Fresh Chat Prompt

Copy the prompt below into a **new ChatGPT conversation** and attach the next Kalaignar novel/story PDF in that same conversation.

---

## COPY FROM HERE

Continue the Kalaignar Novels / Story Books archival project with a **new source work**.

GitHub repository:

`https://github.com/pugazg/kalaignar-novels`

The **new source PDF is attached in this chat**.

Work directly in the existing repository using the GitHub connector.

### MANDATORY STARTUP

Before making any repository changes:

1. Read `NOVEL_PROCESSING_GUIDE.md` **completely**.
2. Read the repository root `README.md`.
3. Read the repository root `HANDOVER.md` **completely**.
4. Study `works/balipeedam-nokki/` only as the completed reference implementation, especially:
   - `README.md`
   - `metadata/source.md`
   - `indexes/page-map.md`
   - `audit.md`
   - `sections/README.md`
   - `translations/en/TRANSLATION_PLAN.md`
   - `translations/en/PROGRESS.md`
   - `translations/en/GLOSSARY.md`
   - `translations/en/TRANSLATION_REVIEW.md`
   - `translations/en/RELEASE_REPORT.md`
5. Inspect the current repository first and confirm whether this new work has already been started. If work exists, continue it instead of creating duplicate files/directories.
6. Inspect the **actual attached PDF scan** before creating metadata. Do **not** rely on the filename alone for title, author, edition, year, work identity, or structure.
7. Do **not** upload or commit the source PDF to GitHub.

### SOURCE AUTHORITY

The attached source scan is the controlling source for this edition.

Do not silently modernize, correct, normalize, reconstruct, regularize, or improve the Tamil.

Preserve source-supported:

- spelling;
- punctuation;
- wording;
- names and titles;
- dates and numbers;
- repetition;
- unusual grammar;
- typographical forms;
- dialogue format;
- cinematic / dramatic notation;
- sound effects;
- source-specific oddities.

If something looks like a typo but the scan supports it, preserve it.

If a reading is uncertain, do not guess from context. Mark it `needs-review` and revisit the source visually.

Separate printed text from:

- library stamps;
- accession marks;
- handwriting;
- underlining / circles / marginal marks;
- bleed-through;
- scan artefacts;
- illustrations / photographs / ornaments.

### STRUCTURAL CAUTION

Do not assume every internal heading or title card is a separate work.

First inspect the surrounding narrative.

An embedded story, historical episode, film-like sequence, play, dream, letter, speech or quotation may be an internal section of the main work.

The completed `பலிபீடம் நோக்கி` project is the reference example: `ராயசம் வெங்கண்ணு — தஞ்சை சரித்திரக் கதை` was correctly retained as an internal cinematic sequence, not promoted to a separate work.

Decide the new source's structure from the new source itself.

### INITIAL WORKFLOW — DO THIS FIRST

For the attached new PDF:

1. inspect repository state;
2. inspect cover, title/publication pages and representative body pages;
3. identify title and author from the scan;
4. identify edition/publication details visible in the scan;
5. determine scan page count and file size;
6. calculate/record SHA-256;
7. inspect printed-page numbering behaviour;
8. note scan condition and non-text markings;
9. determine whether the source contains one continuous work or internal textual units;
10. choose/reuse a stable `works/<slug>/` path;
11. create/update `metadata/source.md`;
12. create initial `indexes/page-map.md` covering **every scan page**, including cover/front matter/blank/back matter;
13. create the first page records;
14. begin Tamil transcription in small source-verified batches.

Every scan page must eventually have a record.

Use separate `scan_page` and `printed_page` values. Do not infer a printed page number when it is not visibly printed.

### PAGE STATUS

Use only:

- `not-started`
- `partial`
- `needs-review`
- `verified`
- `blocked`

Use `verified` only after direct visual comparison with the source scan.

OCR, if used at all, is only an aid. It is never the textual authority.

### TAMIL COMPLETION GATE

Do **not** begin English translation merely because transcription coverage is complete.

Before translation:

- every scan page must have a record;
- body pages must be directly visually audited;
- unresolved readings must be resolved or explicitly documented;
- page map / metadata / README statuses must agree;
- page-boundary continuity must be checked;
- internal structure must be correctly identified;
- Tamil `audit.md` must pass;
- source PDF must still be outside the repository.

After that, create a source-faithful assembled Tamil `sections/` layer derived only from audited `pages/` records.

### ENGLISH TRANSLATION GATE

Only after the Tamil audit and assembled Tamil layer pass:

1. create `translations/en/TRANSLATION_PLAN.md`;
2. define batch structure, terminology, transliteration, political/religious/caste language, cinematic vocabulary, source oddity policy and traceability;
3. translate in controlled batches;
4. source-check every batch against audited Tamil pages;
5. maintain `PROGRESS.md` and `GLOSSARY.md`;
6. mark batches `reviewed` only after source comparison;
7. after all batches, create `TRANSLATION_REVIEW.md` and perform whole-work bilingual alignment;
8. only after that review passes may English be called `VERIFIED`;
9. then create `RELEASE_REPORT.md` and perform release-readiness/navigation/inventory checks.

### GIT / DOCUMENTATION RULES

- Make narrow, descriptive commits.
- Update the work README and root `HANDOVER.md` at meaningful stage boundaries.
- Keep the exact next action in `HANDOVER.md` current.
- Do not create duplicate work structures.
- Do not commit the PDF.
- Do not change already verified source readings merely for stylistic modernization.

### HOW TO PROCEED IN THIS CHAT

Do not ask me to restate this workflow.

Start by reading the required repository documents, inspecting the repository and attached PDF, and then perform the **next concrete archival activity**.

At the end of each activity, tell me:

- exactly what was completed;
- which files were created/updated;
- current transcription/audit/translation status;
- unresolved items, if any;
- the exact next activity.

Then stop and wait for my instruction to proceed.

## END PROMPT
