# Transcription Audit — பெரிய இடத்துப் பெண்

## Audit scope

Source: `TVA_BOK_0064090_பெரிய_இடத்துப்_பெண்_1953.pdf`  
Source pages: **49**  
Source PDF committed to repository: **No**

This audit is **open**. Canonical transcription exists through scan 27, but the former page-level verification state has been withdrawn because historical/pre-reform Tamil glyphs were misidentified.

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
| Historical-glyph retrospective audit | **OPEN — 4 / 27 reviewed; scans 1–4** |
| Full body visual audit | reopened because glyph identity was misread |
| Page-boundary continuity audit | provisional through scan 27 |
| Internal structural audit | preliminary only |
| Source PDF excluded from repository | yes |
| Tamil source layer | **NOT PASSED** |
| Assembled Tamil reading layer | **BLOCKED** |
| English translation gate | **CLOSED** |

## Historical-glyph verification failure

The first confirmed failure involved a historical form corresponding to modern Unicode `றா` being read as apparent modern `று`. The user then supplied a clearer Periyar reform chart showing that the retrospective audit must cover a broader set of historical forms, not only `றா`.

The 13 modern Unicode identities represented by the supplied historical forms are:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Historical typeform decoding is not editorial modernization. When a source glyph is positively identified as one of these old forms, canonical Markdown must encode its actual Tamil identity in modern Unicode while preserving the source word, spelling, grammar, punctuation and structure.

Every existing page record remains `needs-review`, and no page in this work may be marked `verified` while the retrospective glyph audit is open.

Confirmed historical-glyph corrections at this checkpoint:

| Scan | Printed page | Earlier reading | Correct reading |
|---:|:---:|---|---|
| 20 | 19 | `நன்றுகத்` | `நன்றாகத்` |
| 21 | 20 | `நன்றுகத்தான்` | `நன்றாகத்தான்` |
| 24 | 23 | `நன்றுக` | `நன்றாக` |
| 24 | 23 | `விழுவேன் என்றுனா?` | `விழுவேன் என்றானா?` |

Full tracking: [`HISTORICAL_GLYPH_AUDIT.md`](HISTORICAL_GLYPH_AUDIT.md).

## Retrospective audit progress

### Scan 1 — cover

Re-read in full against the complete 13-form reference. No printed occurrence required historical-form conversion and no glyph-identity correction was required. Scan 1 remains `needs-review`.

### Scan 2 — copy-specific marks / later gift label

No original 1953 source-work printed narrative/publication text is present. The later gift label was checked against the full 13-form reference; no conversion was required. Handwriting remains outside canonical source-work text. Scan 2 remains `needs-review`.

### Scan 3 — publication details

Five historical forms were positively identified and were already encoded correctly:

- `ஜூலை` → `லை`;
- `விலை` → `லை`;
- `விற்பனை` → `னை`;
- `சைனா` → `னா`;
- `சென்னை` → `னை`.

No lexical replacement was necessary. Scan 3 remains `needs-review`.

### Scan 4 — `திரை விலக`

The entire page was re-read at enlarged/high resolution. Historical forms positively identified:

- `தலையிடுவது` → `லை`;
- `பார்ப்பதில்லை` → `லை`;
- `ஆனால்` → `னா`;
- `எத்தனையோ` → `னை`;
- `ஆனாலும்` → `னா`;
- `கருணாநிதி` → `ணா`.

All six historical forms were already encoded with the correct modern Unicode identities.

The re-audit exposed one independent source-text error in the earlier transcription: **`சமூகத்தின்` → `சமுதாயத்தின்`**. This is a direct scan-supported lexical correction, not a historical-glyph normalization. The page record has been corrected and remains `needs-review`.

Retrospective progress is therefore **4 / 27 scans reviewed; scans 5–27 pending**.

## Existing transcription coverage

- scans 1–7: front matter transcription exists, all `needs-review`;
- scans 8–27: narrative transcription exists, all `needs-review`;
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
2. Explicitly check the complete user-supplied reference set: `ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`.
3. Distinguish historical/pre-reform glyph identity from modern visual resemblance.
4. Compare same-edition occurrences where useful.
5. Do not mechanically global-replace a shape; every occurrence must be checked against the scan.
6. Encode the proven historical character identity in modern Unicode.
7. Do not normalize spelling, grammar, punctuation or vocabulary beyond proven glyph identity.
8. If an independent source-text error is positively visible during the pass, correct and document it separately from glyph conversion.
9. Keep every page `needs-review` while this project-wide audit is open.
10. Do not call any page verified unless the user explicitly authorizes a verification state later.

The supplied 13-form chart is a known decoding reference set, not evidence that no other legacy typographic ambiguity can occur.

## Structural finding

The source still supports one continuous work, `பெரிய இடத்துப் பெண்`, with front matter on scans 1–7 and narrative beginning on scan 8. `உத்தண்டி` and `கண்ணம்மா` are visibly printed internal headings; this structural observation does not change their page status from `needs-review`.

## Translation gate

English translation and assembled Tamil `sections/` remain blocked. They must not begin while the historical-glyph audit is open.

## Next activity

Do **not** continue to scans 28–32.

Audit **scan 5 only** next using the same one-page method. Inspect the entire page at enlarged/high resolution, examine every printed glyph cluster against the complete 13-form historical reference, make only pixel-supported corrections, record findings with provenance, and leave the page `needs-review`.
