# Next Novel — Fresh Chat Prompt

Copy the prompt below into a **new ChatGPT conversation** and attach the next Kalaignar novel/story PDF in that same conversation.

Repository state when this prompt was synchronized: **no active work**. Completed works must not be reopened merely because an older historical audit/review contains a stage-era `next activity` note.

---

## COPY FROM HERE

Continue the Kalaignar Novels / Story Books archival project with a **new source work**.

GitHub repository:

`https://github.com/pugazg/kalaignar-novels`

The **new source PDF is attached in this chat**.

Work directly in the existing repository using the GitHub connector.

### LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first. Preserve newer durable work. The repository currently has no active work unless live `main` says otherwise.

Completed works are reference implementations, not unfinished targets:

- `works/balipeedam-nokki/` — unqualified release-ready reference;
- `works/periya-idathup-pen/` — completed release workflow with **RELEASE-READY WITH CANONICAL-TAMIL VERIFICATION QUALIFICATION**; its canonical freeze remains **0 verified / 49 needs-review** unless the user explicitly changes it;
- `works/pudhaiyal/` — completed with its documented physical-loss qualifications.

### MANDATORY STARTUP

Before making any repository changes:

1. Read `NOVEL_PROCESSING_GUIDE.md` **completely**.
2. Read the repository root `README.md`.
3. Read the repository root `HANDOVER.md` **completely**.
4. Study completed reference implementations as needed:
   - `works/balipeedam-nokki/` for the ordinary source → Tamil → assembly → English → release pipeline;
   - `works/periya-idathup-pen/` for historical-glyph handling and a completed package whose canonical page statuses remain intentionally frozen. Its key records are `COMPLETION_SYNC_AUDIT.md`, `FULL_TAMIL_SOURCE_AUDIT.md`, `HISTORICAL_GLYPH_AUDIT.md`, `ASSEMBLED_TAMIL_AUDIT.md`, `translations/en/TRANSLATION_REVIEW.md`, and `translations/en/RELEASE_REPORT.md`.
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

### OLD / HISTORICAL TAMIL GLYPH PRE-CORRECTION CHECK

Before overriding a supplied/user baseline because a final character, vowel sign, or combining mark appears absent or different:

1. enlarge the **complete glyph cluster** at high resolution — not only the apparent terminal stroke;
2. explicitly consider old/historical Tamil typeforms, worn ink, faint vowel marks, ligatures, and uneven printing;
3. inspect the glyph at more than one useful zoom/contrast when the mark is faint;
4. compare the same typeform elsewhere in the same edition when useful;
5. change the baseline only when **positive native-pixel evidence** establishes a different reading;
6. if pixels remain genuinely ambiguous, retain the baseline and mark the reading `needs-review` rather than guessing;
7. never apply a global normalization or de-normalization rule from one confirmed glyph discovery.

Use `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`. Its completed `பெரிய இடத்துப் பெண்` evidence includes the `லை / றா / னா / ணா` corrections discovered across the whole-work audit.

A documented example in `புதையல்`: the old/faint final `லை` in `இல்லை` / `வில்லை` forms was initially mistaken for bare `ல்`, producing false assistant corrections such as `தெரியவில்லை` → `தெரியவில்ல`. The same edition also contains genuine source forms such as `தீண்ட வில்லையே` and `தெரியவில்லையே`, so mechanical replacement in either direction is prohibited.

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

The completed `பலிபீடம் நோக்கி` project is one reference example: `ராயசம் வெங்கண்ணா — தஞ்சை சரித்திரக் கதை` was correctly retained as an internal cinematic sequence, not promoted to a separate work. The completed `பெரிய இடத்துப் பெண்` is another: its character-name headings remain internal accounts in one continuous work.

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

Use `verified` only after direct visual comparison with the source scan and only when the work-specific verification policy permits it.

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
- difficult / old-type glyph corrections must have passed the pre-correction visual check above;
- Tamil `audit.md` must pass;
- source PDF must still be outside the repository.

After that, create a source-faithful assembled Tamil `sections/` layer derived only from audited `pages/` records.

A work-specific user instruction may intentionally keep page statuses at `needs-review` even after the source-comparison gate passes, as happened with `பெரிய இடத்துப் பெண்`. Such a freeze must be documented and preserved rather than silently overridden.

### ENGLISH TRANSLATION GATE

Only after the Tamil audit and assembled Tamil layer pass:

1. create `translations/en/TRANSLATION_PLAN.md`;
2. define batch structure, terminology, transliteration, political/religious/caste language, source oddity policy and traceability;
3. translate in controlled batches;
4. source-check every batch against audited Tamil pages;
5. maintain `PROGRESS.md` and `GLOSSARY.md`;
6. mark batches `reviewed` only after source comparison;
7. after all batches, create `TRANSLATION_REVIEW.md` and perform whole-work bilingual alignment;
8. only after that review passes may English be called `VERIFIED`;
9. then create `RELEASE_REPORT.md` and perform release-readiness/navigation/inventory checks;
10. if a canonical-status qualification remains, the release report must carry it explicitly rather than presenting the whole package as unqualified release-ready.

### GIT / DOCUMENTATION RULES

- Make narrow, descriptive commits.
- Update the work README and root `HANDOVER.md` at meaningful stage boundaries.
- Keep the exact next action in `HANDOVER.md` current.
- When a work reaches completion, perform a repository-wide documentation synchronization so old stage instructions are not mistaken for the current state.
- Keep historical batch/audit records source-faithful, but mark superseded stage instructions as historical/subsequent state rather than leaving misleading current `next activity` text.
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
