# Next Chat Prompt — Kalaignar Novels Archive / Next Source Intake

Continue in `pugazg/kalaignar-novels`, branch `main`. **LIVE MAIN IS AUTHORITATIVE.**

## Durable checkpoint

There is no active unfinished work at this checkpoint.

Latest completed work: `works/vellikkizhamai/` — **RELEASE-READY / CLOSED**.

`வெள்ளிக்கிழமை` durable state:

- canonical Tamil — **179 / 179 VERIFIED**;
- historical-glyph/full Tamil source audit — **PASSED**;
- assembled Tamil — **23 / 23 PASSED**;
- English chapters — **23 / 23 REVIEWED**;
- final bilingual review — **PASSED**;
- whole-work English — **VERIFIED**;
- Section 17 release-readiness — **PASSED**;
- unresolved Tamil / English holds — **0 / 0**;
- final release report — `works/vellikkizhamai/translations/en/RELEASE_REPORT.md`.

Do **not** reopen `வெள்ளிக்கிழமை` from an older prompt unless genuinely new direct-source evidence, another edition, or a separately authorized derived-edition task appears.

## Mandatory startup for the next source

Before changing anything:

1. fetch live `main` and preserve newer durable work;
2. read root `README.md`;
3. read `NOVEL_PROCESSING_GUIDE.md` completely;
4. read `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md` if the new source uses historical Tamil print;
5. read root `HANDOVER.md` and this prompt;
6. inspect `works/` to determine whether the supplied work already has a directory;
7. inspect the actual newly supplied source pages before trusting filename/title/year/edition assumptions;
8. use `works/balipeedam-nokki/` and completed `works/vellikkizhamai/` only as workflow references, never as templates that override the new source's structure;
9. do not commit any source PDF.

## Exact next activity

When the next source is supplied, run **source intake / registration**:

- establish title, author, publisher, edition/date and other bibliographic details from the actual scans;
- record filename, SHA-256, size, physical scan count and scan condition;
- identify printed-page numbering behaviour, blanks, illustrations, copy-specific marks and front/back matter;
- create or reuse the correct `works/<slug>/` directory;
- create/update `metadata/source.md`, initial `indexes/page-map.md`, work `README.md`, `audit.md`, root `HANDOVER.md` and this prompt;
- only then open page-level transcription under the guide's source-first workflow.

If no new source is attached, stop at the completed checkpoint rather than inventing a next work.
