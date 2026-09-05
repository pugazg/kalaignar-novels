# Historical Glyph Audit — பெரிய இடத்துப் பெண்

## Status

**RETROSPECTIVE PASS COMPLETE — glyph-aware first-pass transcription now active; verification freeze remains active.**

The user identified a systematic transcription risk in this 1953 source: historical/pre-reform Tamil typeforms can be mistaken for modern glyphs by visual resemblance. The retrospective pass over scans **1–27** is complete. New canonical scans **28–32** were transcribed with the same historical-glyph checks applied before entry.

All canonical records remain `needs-review`; no page may be marked `verified` unless the user explicitly changes that policy.

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

The scan-25 correction confirms the risk is not limited to old `றா`; historical `னா` can also resemble a different modern sequence.

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

Key historical-glyph corrections are listed above. Scans without corrections were still checked against the full 13-form set at enlarged/native resolution. Physical page-boundary evidence does not confer verification.

## Glyph-aware first-pass coverage — scans 28–32

These five new canonical pages were inspected at enlarged/high resolution and transcribed only after the 13-form check was applied.

- **scan 28 / printed 27:** `னை / லை / ளை / னா`-family clusters checked; no separate post-entry glyph correction required. Opening `மகள்.` resolves scan 27's `அவனுக்கு ஒரு` continuation. Source-specific wording/punctuation retained.
- **scan 29 / printed 28:** historical clusters in `என்னை`, `குமுதாவையும்`, `வீரனையும்`, `வீரனை`, `வேலை` and related forms checked; no separate post-entry correction.
- **scan 30 / printed 29:** old-form identities in `வேலைக்காரியாக`, `குமுதாவை`, `பெண்ணை`, `நினைத்துக்கொண்டு` and related `லை / னை` clusters checked; no separate post-entry correction.
- **scan 31 / printed 30:** historical `லை / ளை / னை / னா` clusters checked, including `காலை`, `கொல்லைப்புறத்`, `கண்களைத்`, `வீரனை`, `குமுதாவை`, and `கொலை`; no separate post-entry correction.
- **scan 32 / printed 31:** direct legacy-form decoding was essential: `கொலை` uses historical `லை`, and `தோன்றாமல்தான்` contains historical `றா` rather than apparent modern `று`. `குமுதா` is directly confirmed as an internal heading.

No page in scans 28–32 is marked verified.

## Audit rule — mandatory for every remaining new page

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

- canonical records: **32 / 49**;
- retrospective historical-glyph pass on scans 1–27: **27 / 27 — COMPLETE**;
- glyph-aware new-page coverage: **scans 28–32 complete**;
- `verified`: **0**;
- `needs-review`: **32 — scans 1–32**;
- `partial`: **0**;
- `not-started`: **17 — scans 33–49**;
- Tamil source audit: **NOT PASSED**;
- assembled Tamil: **blocked**;
- English translation: **blocked**.

## Exact next activity

Transcribe **scans 33–37 / printed pages 32–36** as the next source-first batch. Apply the full historical-glyph rule during first transcription, preserve exact spelling/punctuation/page boundaries, create every page as `needs-review`, synchronize page-map/audit/READMEs/HANDOVER, and stop after scan 37. Do not begin scan 38, assembled Tamil, or English translation in that activity.
