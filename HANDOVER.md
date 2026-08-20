# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary reusable guide: `NOVEL_PROCESSING_GUIDE.md`
- Fresh-chat prompt: `NEXT_NOVEL_CHAT_PROMPT.md`

This handover is now **project-level**, not a continuation of unfinished work on `பலிபீடம் நோக்கி`.

---

# 1. Mandatory startup in a new chat

Before doing any work on the next novel/story:

1. Read `NOVEL_PROCESSING_GUIDE.md` completely.
2. Read root `README.md`.
3. Read this `HANDOVER.md` completely.
4. Study `works/balipeedam-nokki/` as the completed reference implementation, especially:
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
5. Inspect repository state before creating a new work directory.
6. If the next work already exists, continue it; do not create a duplicate.
7. Inspect the **actual attached PDF scan** before metadata creation. Do not trust filename alone.
8. Do not upload or commit the source PDF.

---

# 2. Controlling source policy

The authority order for every work is:

1. actual source scan page;
2. source-printed bibliographic / page information;
3. audited Tamil `pages/` records;
4. verified assembled Tamil `sections/`;
5. verified English translation;
6. metadata / glossary / review documentation.

Do not silently modernize, correct, normalize, reconstruct or improve source-supported Tamil.

Preserve source-supported:

- historical spelling;
- punctuation;
- unusual grammar;
- names / titles / numbers;
- repetitions;
- typographical forms;
- cinematic / dramatic notation;
- source oddities.

Separate printed text from stamps, handwriting, underlines, later annotations, bleed-through and scan artefacts.

---

# 3. Completed reference implementation — பலிபீடம் நோக்கி

Work: **பலிபீடம் நோக்கி**  
Author: **மு. கருணாநிதி**  
Source edition: **First edition, April 1947**  
Source scan: **34 pages**

External source filename:

`TVA_BOK_0065570_பலிபீடம்_நோக்கி.pdf`

SHA-256:

`c4700c9043da8eadbf25144e7127a66a9270326512c095d99e1113a4feb464fe`

Source PDF in repository: **No**.

## Final status

- source registration — **complete**
- Tamil page records — **34 / 34**
- Tamil direct visual verification — **34 / 34 verified**
- unresolved Tamil readings — **0**
- Tamil source audit — **PASSED**
- assembled Tamil reading layer — **PASSED**
- English translation plan — **complete**
- English translation batches — **6 / 6 reviewed**
- final bilingual alignment — **PASSED**
- whole-work English — **VERIFIED**
- release-readiness pass — **PASSED**
- combined archival package — **RELEASE-READY within this repository**

Reference release report:

`works/balipeedam-nokki/translations/en/RELEASE_REPORT.md`

---

# 4. Important structural lesson from the completed reference

`பலிபீடம் நோக்கி` is **one continuous work**.

The source heading:

`ராயசம் வெங்கண்ணா — தஞ்சை சரித்திரக் கதை`

was initially capable of being mistaken for a separate work, but source flow showed it to be an **internal cinematic-historical sequence** introduced and later exited by the narrator.

Therefore, for every new novel:

> A title card, embedded story, dream, film, play, speech, letter or historical episode must not automatically become a separate repository work.

Inspect surrounding pages and narrative framing first.

---

# 5. Required structure for the next work

After source identity is established, create or continue:

```text
works/<next-work-slug>/
  README.md
  metadata/
    source.md
  indexes/
    page-map.md
  pages/
    0001-....md
  audit.md
  sections/
    README.md
```

Later, after Tamil audit passes:

```text
  translations/
    en/
      README.md
      TRANSLATION_PLAN.md
      PROGRESS.md
      GLOSSARY.md
      TRANSLATION_REVIEW.md
      RELEASE_REPORT.md
      sections/
```

Do not create English translation files before the Tamil audit gate unless the user explicitly changes the project policy.

---

# 6. Next work — exact onboarding sequence

When the user attaches the next novel/story PDF, perform these steps in order:

1. inspect repository tree / search for existing work;
2. inspect actual PDF cover, title, publication and representative body pages;
3. determine source identity from the scan itself;
4. calculate / record SHA-256, file size and page count;
5. identify printed-page numbering behaviour;
6. note scan condition, stamps, handwriting, bleed-through, illustrations and damage;
7. determine whether the publication contains one work or internal textual units;
8. choose a stable work slug;
9. create/update `metadata/source.md`;
10. create initial `indexes/page-map.md` covering every scan page;
11. create front-matter records;
12. begin Tamil body transcription in small batches;
13. after each batch update page map, work README and this handover;
14. leave uncertain forms `needs-review` rather than guessing.

Do **not** jump directly to English translation.

---

# 7. Verification rules

Page status values:

- `not-started`
- `partial`
- `needs-review`
- `verified`
- `blocked`

Use `verified` only after direct visual comparison with the source scan.

OCR, if used at all, is only an aid and never the authority.

For difficult words:

- enlarge/crop the scan;
- compare character by character;
- preserve odd source forms if visually supported;
- document cautious readings;
- never normalize Tamil merely because an expected word seems more plausible.

---

# 8. Translation and release gates

After Tamil source audit passes:

1. build source-faithful assembled Tamil `sections/`;
2. check section continuity and page provenance;
3. create `translations/en/TRANSLATION_PLAN.md`;
4. translate in controlled batches;
5. source-check each batch;
6. record recurring terms and uncertain forms in `GLOSSARY.md`;
7. mark each batch `reviewed` only after source check;
8. perform whole-work `TRANSLATION_REVIEW.md`;
9. only then mark English `VERIFIED`;
10. create `RELEASE_REPORT.md` and perform final navigation/inventory pass.

Release-ready means archival/editorial readiness, **not** automatic copyright/licensing clearance.

---

# 9. Git practice

Prefer narrow descriptive commits.

Examples:

- `Register source metadata for <work>`
- `Create page map for <work>`
- `Transcribe scans 1-5 of <work>`
- `Resolve scan 18 source reading`
- `Complete Tamil source audit for <work>`
- `Create assembled Tamil reading layer for <work>`
- `Translate English Batch 1 for <work>`
- `Complete final bilingual review for <work>`
- `Mark <work> release-ready`

Do not include the source PDF in any commit.

---

# 10. Current exact next action

**Wait for / use the next attached Kalaignar novel or story PDF.**

Then execute the onboarding sequence in Section 6.

No further mandatory archival work remains for `பலிபீடம் நோக்கி`.

If the next chat receives both this repository URL and a new PDF, it should immediately begin with repository/source inspection and source registration — not ask the user to repeat the established workflow.

---

# 11. Fresh-chat continuation prompt

Use:

`NEXT_NOVEL_CHAT_PROMPT.md`

Copy that file into a new ChatGPT conversation together with the next source PDF.

The prompt deliberately instructs the new chat to read this handover and the processing guide before doing any transcription.