# Historical Glyph Audit — பெரிய இடத்துப் பெண்

## Status

**OPEN — blocking page verification.**

The user identified a systematic transcription risk in this 1953 source: historical/pre-reform Tamil typeforms can be mistaken for modern glyphs by visual resemblance. All canonical records for scans **1–27** remain `needs-review`. No page may be marked `verified` while this audit is open unless the user explicitly changes that policy.

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

The scan-24 corrections were established earlier from the user's direct challenge and remain recorded even though scan 24 has not yet reached its retrospective page-audit turn.

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
| 17 | 16 | full 13-form sweep; no text correction | `needs-review` |
| 18 | 17 | full 13-form sweep; no text correction | `needs-review` |
| 19 | 18 | full 13-form sweep; `செவேலென்றேதோன்றின` source-text correction | `needs-review` |
| 20 | 19 | earlier `நன்றாகத்` historical `றா` correction re-confirmed; no new correction | `needs-review` |
| 21 | 20 | earlier `நன்றாகத்தான்` historical `றா` correction re-confirmed; no new correction | `needs-review` |
| 22 | 21 | full 13-form sweep; no text correction | `needs-review` |
| 23 | 22 | full 13-form sweep; no text correction | `needs-review` |

### Batch finding — scans 14–23

All ten pages were inspected independently at enlarged/high resolution. Important directly source-supported findings include:

- scan 14: historical `லை` resolves `ஆவலைக்`; historical `றா` resolves `நின்றார்`;
- scan 16: historical `றா` resolves `போகிறாயே`;
- scan 19: source visibly reads `செக்கச் செவேலென்றேதோன்றின.`;
- scans 20–21: the previously corrected `நன்றாகத்` / `நன்றாகத்தான்` readings were re-confirmed from the historical `றா` form;
- scans 15, 17, 18, 22 and 23 required no canonical text change in this pass.

Page-boundary evidence remains physical-source evidence only and does not confer verification: scan 14 `நினைக்` → scan 15 `காதே!`; scan 15 `தெரிந்` → scan 16 `தது.`; scan 16 `நம்` → scan 17 `வீட்டு`; scan 17 `கண்டது` → scan 18 `போலத்தானே!`; scan 18 `என்` → scan 19 `றேன்.`; scan 19 `என்` → scan 20 `னிலே`; scan 21 `காலக்ஷேபங்` → scan 22 `கூட`; scan 22 `மட்` → scan 23 `டும்`.

**Progress: 23 / 27 existing canonical scans reviewed; scans 24–27 pending.** All reviewed pages remain `needs-review`.

## Audit rule

For every page:

1. inspect complete glyph clusters at enlarged/native resolution;
2. check all 13 known historical forms explicitly;
3. identify character identity rather than copying apparent modern shape;
4. compare same-edition occurrences where useful;
5. encode the proven identity in modern Unicode;
6. do not normalize anything beyond proven glyph identity;
7. correct an independent transcription mismatch only with positive source-pixel support and record it separately;
8. keep the page `needs-review` while the work-wide audit remains open.

The 13-form chart is a minimum known reference set; remain alert for other legacy typographic ambiguity.

## Gate consequence

- canonical records: **27 / 49**;
- retrospective historical-glyph pass: **23 / 27 — scans 1–23**;
- `verified`: **0**;
- `needs-review`: **27 — scans 1–27**;
- `partial`: **0**;
- `not-started`: **22 — scans 28–49**;
- Tamil source audit: **NOT PASSED**;
- assembled Tamil: **blocked**;
- English translation: **blocked**.

## Exact next activity

Audit **scans 24–27 / printed pages 23–26** next as the remaining four-page retrospective batch. Re-confirm the already known scan-24 `றா` corrections from the source, inspect every page against all 13 historical forms, make only pixel-supported corrections, keep every page `needs-review`, update the audit trackers, and stop after scan 27.
