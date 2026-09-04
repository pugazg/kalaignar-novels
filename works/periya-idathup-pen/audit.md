# Transcription Audit — பெரிய இடத்துப் பெண்

## Audit scope

Source: `TVA_BOK_0064090_பெரிய_இடத்துப்_பெண்_1953.pdf`  
Source pages: **49**  
Source PDF committed to repository: **No**

This audit is **open**. Canonical transcription exists through scan 27, but the former page-level verification state has been withdrawn because a historical pre-reform Tamil glyph was misidentified in multiple places.

## Current gate

| Check | Current result |
|---|---|
| Source identity inspected from scan | complete |
| Scan pages mapped | **49 / 49** |
| Canonical page records | **27 / 49** |
| `verified` page records | **0** |
| `needs-review` page records | **27 — scans 1–27** |
| `partial` page records | **0** |
| Remaining `not-started` | **22 — scans 28–49** |
| Historical-glyph retrospective audit | **OPEN — scans 1–27 required** |
| Full body visual audit | reopened because glyph identity was misread |
| Page-boundary continuity audit | provisional through scan 27 |
| Internal structural audit | preliminary only |
| Source PDF excluded from repository | yes |
| Tamil source layer | **NOT PASSED** |
| Assembled Tamil reading layer | **BLOCKED** |
| English translation gate | **CLOSED** |

## Historical-glyph verification failure

The user identified the key failure: this 1953 edition uses a historical pre-reform glyph corresponding to modern Unicode `றா`. Its printed shape can resemble modern `று`. The earlier workflow treated the visual resemblance as the character identity and therefore recorded false “odd source forms.”

This means the previous statement that scans 1–27 were verified is no longer valid. Every existing page record has been changed to `needs-review`, and no page in this work may be marked `verified` while the retrospective glyph audit is open.

Confirmed corrections at this checkpoint:

| Scan | Printed page | Earlier reading | Correct reading |
|---:|:---:|---|---|
| 20 | 19 | `நன்றுகத்` | `நன்றாகத்` |
| 21 | 20 | `நன்றுகத்தான்` | `நன்றாகத்தான்` |
| 24 | 23 | `நன்றுக` | `நன்றாக` |
| 24 | 23 | `விழுவேன் என்றுனா?` | `விழுவேன் என்றானா?` |

These are not editorial modernization. They are corrections to the Unicode identity of a historical Tamil glyph.

Full tracking: [`HISTORICAL_GLYPH_AUDIT.md`](HISTORICAL_GLYPH_AUDIT.md).

## Existing transcription coverage

- scans 1–7: front matter transcription exists, now `needs-review`;
- scans 8–27: narrative transcription exists, now `needs-review`;
- scans 28–49: `not-started`.

The existing page-boundary joins and structural observations remain useful evidence, but they do not confer `verified` status on any page.

## Boundary observations retained provisionally

- scan 11 `கிடப்ப` + scan 12 `தாகக்` → `கிடப்பதாகக்`;
- scan 14 `நினைக்` + scan 15 `காதே!` → `நினைக்காதே!`;
- scan 15 `தெரிந்` + scan 16 `தது.` → `தெரிந்தது.`;
- scan 16 `நம்` + scan 17 `வீட்டு` → `நம் வீட்டு`;
- scan 17 `கண்டது` + scan 18 `போலத்தானே!`;
- scan 19 `என்` + scan 20 `னிலே` → `என்னிலே`;
- scan 20 `நானும்` + scan 21 `நன்றாகத்தான்`;
- scan 22 `மட்` + scan 23 `டும்` → `மட்டும்`;
- scan 24 `‘ஒய்யா` + scan 25 `ரக்` → `‘ஒய்யாரக்`;
- scan 25 `கவலை` + scan 26 `யில்லை.` → `கவலையில்லை.`;
- scan 26 `நிலையி` + scan 27 `லேயே` → `நிலையிலேயே`;
- scan 27 parenthetical continuation remains open for scan 28.

## Historical-glyph audit rule

1. Inspect complete native/high-resolution glyph clusters, not isolated apparent modern shapes.
2. Explicitly distinguish pre-reform glyph identity from modern visual resemblance.
3. The user-confirmed old `றா` form must be encoded as modern Unicode `றா`, not copied as `று` merely because it resembles that modern form.
4. Compare same-edition occurrences where useful.
5. Do not mechanically global-replace a shape; every occurrence must be checked against the scan.
6. Do not normalize spelling, grammar, punctuation or vocabulary beyond proven glyph identity.
7. Keep every page `needs-review` while this project-wide audit is open.
8. Do not call any page verified unless the user explicitly authorizes a verification state later.

## Structural finding

The source still supports one continuous work, `பெரிய இடத்துப் பெண்`, with front matter on scans 1–7 and narrative beginning on scan 8. `உத்தண்டி` and `கண்ணம்மா` are visibly printed internal headings; this structural observation does not change their page status from `needs-review`.

## Translation gate

English translation and assembled Tamil `sections/` remain blocked. They must not begin while the historical-glyph audit is open.

## Next activity

Do **not** continue to scans 28–32.

Retroactively audit canonical scans **1–27** in source order for historical/pre-reform Tamil glyphs, beginning with the user-confirmed `றா` failure pattern. Record every correction with scan and printed-page provenance. Keep all pages `needs-review`. Only after this retrospective pass is complete should transcription resume at scan 28.
