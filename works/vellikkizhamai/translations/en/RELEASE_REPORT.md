# Friday — Final Release Report

## Release identity

- Tamil work: **`வெள்ளிக்கிழமை`**
- Author: **மு. கருணாநிதி**
- Working English title: **_Friday_**
- Source edition: **Second edition, 1968**
- Publisher visible in source: **திராவிடப்பண்ணை**
- Source filename: `TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf`
- Source SHA-256: `ac241cbfbe3d47d76f22140f43c662176ba29a91521b826a1a8f5c75cf3081d3`
- Source scan count: **179**
- English narrative coverage: **scan 4 through final narrative scan 179**
- Source PDF committed to repository: **No**

This report records archival/editorial release readiness for the verified Tamil + English package. It does not change the authority of the audited Tamil source layer.

## Completion status

| Stage | Result |
|---|---|
| Source registration | **COMPLETE** |
| Tamil canonical scan-page records | **179 / 179 COMPLETE / VERIFIED** |
| Historical-glyph / full Tamil source audit | **PASSED** |
| Tamil assembled reading layer | **23 / 23 PASSED** |
| Final assembled Tamil consistency gate | **PASSED** |
| English translation plan | **COMPLETE** |
| English chapter files | **23 / 23 REVIEWED** |
| English source coverage | **scan 4 → final narrative scan 179** |
| Final bilingual review | **PASSED** |
| Whole-work English | **VERIFIED** |
| Unresolved Tamil / English holds | **0 / 0** |
| Release-readiness pass | **PASSED** |
| Canonical Tamil changed during release pass | **0** |
| Source PDF present in repository tree | **No** |

## Release contents

### Canonical Tamil preservation layer

- [`../../metadata/source.md`](../../metadata/source.md) — source identity, edition details and scan observations
- [`../../indexes/page-map.md`](../../indexes/page-map.md) — printed-page and 23-chapter source map
- [`../../audit.md`](../../audit.md) — Tamil, assembly, translation and release gate history
- [`../../pages/`](../../pages/) — **179 verified scan-page records**

The `pages/` layer remains the controlling archival text.

### Assembled Tamil reading layer

- [`../../sections/README.md`](../../sections/README.md) — 23-chapter inventory and assembly policy
- [`../../sections/01-chapter-01.md`](../../sections/01-chapter-01.md) — Chapter 1 / scans 4–12
- Chapters 2–22 continue one-to-one under `../../sections/`
- [`../../sections/23-chapter-23.md`](../../sections/23-chapter-23.md) — Chapter 23 / scan 172 after centered `23` through final narrative scan 179

### Verified English layer

- [`README.md`](README.md) — reader-facing English entry point
- [`TRANSLATION_PLAN.md`](TRANSLATION_PLAN.md) — translation policy and completed batch design
- [`PROGRESS.md`](PROGRESS.md) — translation, bilingual-review and release ledger
- [`GLOSSARY.md`](GLOSSARY.md) — recurring terminology and source-oddity decisions
- [`TRANSLATION_REVIEW.md`](TRANSLATION_REVIEW.md) — final whole-work bilingual review, **PASSED**
- [`sections/README.md`](sections/README.md) — complete 23-chapter English inventory
- [`sections/01-chapter-01.md`](sections/01-chapter-01.md) through [`sections/23-chapter-23.md`](sections/23-chapter-23.md) — **23 / 23 reviewed chapter files**

## Reader-facing navigation check — PASS

Navigation was checked against the current repository structure and synchronized during this gate:

1. root [`README.md`](../../../../README.md) → [`works/vellikkizhamai/README.md`](../../README.md);
2. work README → source metadata, page map, Tamil reading layer and English translation entry point;
3. Tamil [`sections/README.md`](../../sections/README.md) → all 23 Tamil chapter files;
4. English [`README.md`](README.md) → all 23 English chapters plus glossary, progress, bilingual review and this release report;
5. English [`sections/README.md`](sections/README.md) → all 23 English chapter files;
6. chapter ordering remains exactly 1–23 with mixed scans split only at source-centered chapter headings;
7. no source span is duplicated at mixed chapter boundaries.

**Navigation result: PASS.**

## Authority hierarchy

For every future correction, reuse or derived edition, authority remains:

1. actual controlling source scan;
2. canonical audited Tamil `pages/` records;
3. PASSED assembled Tamil `sections/`;
4. VERIFIED English translation;
5. metadata, glossary, review and release documentation.

If a derived layer conflicts with a canonical Tamil page record, the Tamil page record governs unless genuinely new direct-source evidence first establishes a documented correction.

## Structural identity — PASS

`வெள்ளிக்கிழமை` is preserved as **one 23-chapter novel** in this 1968 second edition. English mirrors the same 23 chapters one-to-one.

Mixed physical scans are divided only at source-printed centered chapter headings. The verified chapter openings/boundaries occur at scans **4, 13, 23, 33, 45, 52, 59, 68, 75, 85, 92, 99, 107, 115, 120, 127, 134, 142, 149, 154, 160, 166 and 172**. Chapter 23 ends with the final narrative on scan **179 / printed 178**.

## Documented source oddities — PASS

The release preserves, rather than silently repairs, the source-specific conditions already established by the Tamil and bilingual gates:

- scan **66** visibly prints only **`5`**; printed `65` is never inferred;
- scan **117→118**: literal discontinuity `உட்` → `எவ்வளவோ முயன்றும் நடக்கவில்லை.`;
- scan **122→123**: `...அவளுக்குப் பக்கத்திலே` → `கார்ந்து கொண்டாள்.` without inferred missing grammar;
- scan **156→157**: `தலையிலும் காயம்` → `நயினா எதிர்த்தே அடிக்கவில்லை.` without supplied punctuation or missing text;
- scan **179** contributes only the final narrative; the lower printed illustration and later handwritten marks remain non-body material;
- late `நயினு` is retained as a source spelling variant of the established Naina character without altering canonical Tamil;
- the real/fake Balagangadhara Thevar identity is allowed to resolve only where the narrative itself reveals it.

## Canonical-Tamil preservation during release pass — PASS

The Section 17 pass changed only release/navigation/status documentation. It made **0 changes** to canonical Tamil `works/vellikkizhamai/pages/` and **0 changes** to assembled Tamil chapter prose `works/vellikkizhamai/sections/01-23`.

The earlier Section 16 bilingual review made seven English-only fidelity/presentation corrections and likewise made no canonical Tamil change.

## Source PDF exclusion — PASS

The source PDF is intentionally external to the Git repository. Recursive repository-tree inspection at the release gate found **no committed `.pdf` path**.

The repository preserves the source filename, SHA-256, edition identity, page map and provenance without redistributing the supplied scan.

## Non-blocking editorial limitations

These conditions are intentional and do not block archival/editorial release:

- the controlling source PDF is not bundled;
- three physical source discontinuities remain visibly unresolved rather than conjecturally repaired;
- scan 66 retains its anomalous printed `5` exactly as visible;
- English is organized as 23 chapter files rather than one merged ebook manuscript;
- individual English chapter front matter remains `translation_status: reviewed`, while whole-work `VERIFIED` is recorded by the bilingual review and repository controls;
- the translation preserves historical/source rhetoric, including religious, caste, sexual-stigma, self-harm and social language, without independently fact-checking every claim made by the text;
- copyright, licensing, republication, public-domain and commercial-use clearance are outside this archival release gate.

## Publication / reuse note

This repository release establishes source fidelity, provenance, structural integrity, bilingual verification, navigation and repository readiness. It does **not** by itself establish legal permission to reproduce or commercially publish the underlying work, scan or translation. Rights and permissions must be assessed separately for any public, print, ebook or commercial redistribution.

## Release verdict

**Tamil archival package: RELEASE-READY.**  
**Verified English translation package: RELEASE-READY.**  
**Combined repository edition of `வெள்ளிக்கிழமை` / _Friday_: RELEASE-READY within this archive.**

**Section 17 result: PASS.** The source-preservation, assembled-reading, English-translation, bilingual-verification, navigation, inventory and repository-exclusion gates are complete. The work may now be treated as a completed reference implementation unless genuinely new direct-source evidence requires reopening it.
