# Historical Glyph Audit — பெரிய இடத்துப் பெண்

## Status

**RETROSPECTIVE PASS COMPLETE — glyph-aware first-pass transcription active through scan 47; verification freeze remains active.**

The retrospective pass over scans **1–27** is complete. New canonical scans **28–47** were transcribed with historical-glyph checks applied before entry. All canonical records remain `needs-review`; no page may be marked `verified` unless the user explicitly changes that policy.

Reusable repository-level procedure: [`../../HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`](../../HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md).

## User-supplied Periyar reform reference

Known historical forms must be decoded to these modern Unicode identities:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

The chart is a decoding reference, not permission to modernize spelling, grammar, punctuation, vocabulary, or wording. Every occurrence must be checked against its own source pixels; no global replacement is allowed.

## Confirmed historical-glyph corrections from the retrospective pass

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

## Retrospective pass checkpoint — scans 1–27

The retrospective page-by-page pass is **27 / 27 COMPLETE**. All those pages remain `needs-review`.

## Glyph-aware first-pass coverage — scans 28–42

Scans 28–42 were inspected at enlarged/high resolution and transcribed only after applying the complete 13-form check. Directly confirmed internal headings in that span include `குமுதா` (scan 32) and `வீரன்` (scan 38). No page was marked verified.

## Glyph-aware first-pass coverage — scans 43–47

- **scan 43 / printed 42:** `ளை / னை / லை` families checked; source-specific `போக்கியதைப்`, `ஒடித் தெரியத்`, `இளிச்சவாயனுக`, and `தண்டன்` retained. Final `கடவுள்` continues onto scan 44.
- **scan 44 / printed 43:** opening `பொறுப்பாரா?` resolves `கடவுள் பொறுப்பாரா?`; `கொலைகாரி`, `கல்யாணம்`, `என்னை` and related historical families checked.
- **scan 45 / printed 44:** internal heading `உலகநாதர்` directly confirmed; `லை / ளை / னை / னா` families checked before entry.
- **scan 46 / printed 45:** internal heading `கண்ணம்மா` directly confirmed; `ளை / னை / லை / ணை` families checked; source-specific `நானு ஆள்?` retained. Final `காரண` remains a physical split.
- **scan 47 / printed 46:** opening `மாயிருந்தேன்!` establishes `காரணமாயிருந்தேன்!`; historical families checked in `வைரத்தைத்`, `கவலைப்படவில்லை` and related clusters; source-specific `வக்குப் பேதி`, `அவமானந்`, `கல்மனங்`, `விட வேணு?` retained. Final `எழுதி` remains unresolved until scan 48.

No separate post-entry historical-glyph correction was required in scans 43–47 because character identities were decoded before transcription.

## Audit rule — mandatory for every remaining new page

For every page:

1. inspect complete glyph clusters at enlarged/native resolution;
2. check all 13 known historical forms explicitly;
3. identify character identity rather than copying apparent modern shape;
4. compare same-edition occurrences where useful;
5. encode the proven identity in modern Unicode;
6. do not normalize anything beyond proven glyph identity;
7. join ordinary within-page printed line-wrap fragments, but preserve physical page-boundary splits in page records;
8. correct an independent transcription mismatch only with positive source-pixel support and record it separately;
9. keep the page `needs-review` under the current user-mandated verification freeze.

## Gate consequence

- canonical records: **47 / 49**;
- retrospective historical-glyph pass on scans 1–27: **27 / 27 — COMPLETE**;
- glyph-aware new-page coverage: **scans 28–47 complete**;
- `verified`: **0**;
- `needs-review`: **47 — scans 1–47**;
- `partial`: **0**;
- `not-started`: **2 — scans 48–49**;
- Tamil source audit: **NOT PASSED**;
- assembled Tamil: **blocked**;
- English translation: **blocked**.

## Exact next activity

Transcribe **scans 48–49 / printed pages 47–48** as the final source-first batch. Resolve scan 47's trailing `எழுதி` only from scan 48, inspect scan 49's narrative ending and printer colophon directly, apply the complete historical-glyph rule, keep both pages `needs-review`, synchronize status documents, and stop.