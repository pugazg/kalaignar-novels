# Historical Glyph Audit — பெரிய இடத்துப் பெண்

## Status

**RETROSPECTIVE PASS COMPLETE — verification freeze remains active.**

The user identified a systematic transcription risk in this 1953 source: historical/pre-reform Tamil typeforms can be mistaken for modern glyphs by visual resemblance. The retrospective pass over every currently existing canonical record, scans **1–27**, is now complete. All canonical records remain `needs-review`; no page may be marked `verified` unless the user explicitly changes that policy.

The same glyph-aware method is mandatory from the first pass for every new page beginning with scan 28.

## User-supplied Periyar reform reference

Known historical forms must be decoded to these modern Unicode identities:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

The chart is a decoding reference, not permission to modernize spelling, grammar, punctuation, vocabulary, or wording. Every occurrence must be checked against its own source pixels; no global replacement is allowed.

## Confirmed historical-glyph corrections

| Scan | Printed page | Incorrect transcription | Correct Unicode reading | Historical identity |
|---:|:---:|---|---|---|
| 14 | 13 | `ஆவிலைக்` | `ஆவலைக்` | `லை` |
| 14 | 13 | `நின்றூர்` | `நின்றார்` | `றா` |
| 16 | 15 | `போகிறயே` | `போகிறாயே` | `றா` |
| 20 | 19 | `நன்றுகத்` | `நன்றாகத்` | `றா` |
| 21 | 20 | `நன்றுகத்தான்` | `நன்றாகத்தான்` | `றா` |
| 24 | 23 | `நன்றுக` | `நன்றாக` | `றா` |
| 24 | 23 | `விழுவேன் என்றுனா?` | `விழுவேன் என்றானா?` | `றா` |
| 25 | 24 | `வேலை மட்டுந்தானு?` | `வேலை மட்டுந்தானா?` | `னா` |

The scan-25 correction is the first confirmed error in this work caused by the historical `னா` form being copied according to apparent modern shape rather than character identity.

## Other source-text corrections found during the retrospective pass

| Scan | Printed page | Earlier reading | Source-supported reading | Kind |
|---:|:---:|---|---|---|
| 4 | — | `சமூகத்தின்` | `சமுதாயத்தின்` | lexical/source-text correction |
| 5 | — | `அற்பிய` | `அரும்பிய` | lexical/source-text correction |
| 5 | — | `சமூகமும்` | `சமுதாயம்` | lexical/source-text correction |
| 7 | 6 | `உள்ளங்களை` | `உள்ளங்களே` | line-break/source-text correction |
| 12 | 11 | `தாவும்போது பயப்பட்ட பூனை` | `தாவும்போது பயப்படாத பூனை` | lexical/source-text correction |
| 12 | 11 | `பயப்பட்டது போல -` | `பயப்பட்டதுபோல -` | source-word/spacing correction |
| 19 | 18 | `செக்கச் செவேலென்றோன்றின.` | `செக்கச் செவேலென்றேதோன்றின.` | direct source-text correction |

## Retrospective pass progress

| Scan range | Printed pages | Result | Page status |
|---|---|---|---|
| 1–13 | cover/front matter through 12 | completed in prior passes; corrections recorded above and in page records | `needs-review` |
| 14 | 13 | `ஆவலைக்` and `நின்றார்` historical identities corrected | `needs-review` |
| 15 | 14 | full 13-form sweep; no text correction | `needs-review` |
| 16 | 15 | `போகிறாயே` historical `றா` corrected | `needs-review` |
| 17–18 | 16–17 | full 13-form sweep; no text correction | `needs-review` |
| 19 | 18 | full 13-form sweep; `செவேலென்றேதோன்றின` source-text correction | `needs-review` |
| 20–21 | 19–20 | earlier `நன்றாகத்` / `நன்றாகத்தான்` historical `றா` corrections re-confirmed | `needs-review` |
| 22–23 | 21–22 | full 13-form sweep; no text correction | `needs-review` |
| 24 | 23 | earlier `நன்றாக` / `என்றானா?` historical `றா` corrections re-confirmed; no additional correction | `needs-review` |
| 25 | 24 | historical `னா` corrected `மட்டுந்தானு?` → `மட்டுந்தானா?` | `needs-review` |
| 26–27 | 25–26 | full 13-form sweep; no canonical text correction | `needs-review` |

### Final retrospective batch — scans 24–27

All four pages were inspected independently at enlarged/high resolution.

- **scan 24 / printed 23:** the previously established `நன்றாக` and `விழுவேன் என்றானா?` readings were directly re-confirmed. The source also contains correctly encoded historical `ணை / லை / ளை / றா / னா / னை` occurrences. No new correction.
- **scan 25 / printed 24:** the apparent `னு` at `மட்டுந்தானு?` is the historical `னா` form. Canonical text is corrected to **`மட்டுந்தானா?`**. Historical `லை / னா / னை / னொ / னோ` occurrences were checked.
- **scan 26 / printed 25:** historical `லை / ளை / னை` occurrences were already encoded correctly; no text correction.
- **scan 27 / printed 26:** historical `ணை / லை / ளை / னை / னொ` occurrences were already encoded correctly; no text correction.

Physical boundary evidence remains source evidence only and does not confer verification: scan 24 `‘ஒய்யா` → scan 25 `ரக்`; scan 25 `கவலை` → scan 26 `யில்லை.`; scan 26 `நிலையி` → scan 27 `லேயே`. Scan 27 ends inside a parenthetical sentence that must be continued only from scan 28.

**Retrospective progress: 27 / 27 existing canonical scans reviewed — COMPLETE.** Every page remains `needs-review` by user instruction.

## Audit rule — still mandatory for new pages

For every page:

1. inspect complete glyph clusters at enlarged/native resolution;
2. check all 13 known historical forms explicitly;
3. identify character identity rather than copying apparent modern shape;
4. compare same-edition occurrences where useful;
5. encode the proven identity in modern Unicode;
6. do not normalize anything beyond proven glyph identity;
7. correct an independent transcription mismatch only with positive source-pixel support and record it separately;
8. keep the page `needs-review` under the current user-mandated verification freeze.

The 13-form chart is a minimum known reference set; remain alert for other legacy typographic ambiguity.

## Gate consequence

- canonical records: **27 / 49**;
- retrospective historical-glyph pass on existing records: **27 / 27 — COMPLETE**;
- `verified`: **0**;
- `needs-review`: **27 — scans 1–27**;
- `partial`: **0**;
- `not-started`: **22 — scans 28–49**;
- Tamil source audit: **NOT PASSED**;
- assembled Tamil: **blocked**;
- English translation: **blocked**.

## Exact next activity

Resume new-page transcription at **scans 28–32 / printed pages 27–31** as the next source-first batch. Apply the full historical-glyph rule during first transcription rather than retrospectively, preserve scan 27's open parenthetical continuation from the visible opening of scan 28, treat scan 32's `குமுதா` as an internal heading unless the source proves otherwise, create every new page as `needs-review`, synchronize the page map/audit/work README/root README/HANDOVER, and stop after scan 32.
