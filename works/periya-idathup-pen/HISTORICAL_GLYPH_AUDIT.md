# Historical Glyph Audit — பெரிய இடத்துப் பெண்

## Status

**RETROSPECTIVE PASS COMPLETE — glyph-aware first-pass transcription active through scan 42; verification freeze remains active.**

The user identified a systematic transcription risk in this 1953 source: historical/pre-reform Tamil typeforms can be mistaken for modern glyphs by visual resemblance. The retrospective pass over scans **1–27** is complete. New canonical scans **28–42** were transcribed with the same historical-glyph checks applied before entry.

All canonical records remain `needs-review`; no page may be marked `verified` unless the user explicitly changes that policy.

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

## Glyph-aware first-pass coverage — scans 28–37

Scans 28–37 were inspected at enlarged/high resolution and transcribed only after applying the complete 13-form check. Internal heading `குமுதா` is directly confirmed on scan 32. Scan 37 closes குமுதாவின் signed first-person statement. No page was marked verified.

## Glyph-aware first-pass coverage — scans 38–42

All five pages were inspected at enlarged/high resolution before canonical entry. No page was marked verified.

- **scan 38 / printed 37:** internal heading `வீரன்` directly confirmed. Historical families checked include `வளைவுகள்` (`ளை`), `பண்ணைத்` (`ணை`), `கல்யாணம்` (`ணா`) and related clusters.
- **scan 39 / printed 38:** `இன்னொருநாள்` checked as historical `னொ`; `மற்றொருநாள்` explicitly decoded as historical `றொ`; `லை / ணை / னை` families checked across the page.
- **scan 40 / printed 39:** `பண்ணையைப்` checked as historical `ணை`; `லை / னை / றா` families checked before entry. Opening `தொண்டைக்` continues scan 39's final `ஈரமில்லாத`.
- **scan 41 / printed 40:** `புரியவில்லையே` was checked as a complete old/faint `லை`-family cluster rather than shortened by visual appearance; `ளை / னை / லை / ணா` families checked. Final `கல்யா` remains a physical page split.
- **scan 42 / printed 41:** opening `ணத்தை` resolves `கல்யாணத்தை`; `லை / ளை / னை / ணா` families checked before canonical entry.

No separate post-entry historical-glyph correction was required in scans 38–42 because character identities were decoded before transcription.

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

The 13-form chart is a minimum known reference set; remain alert for other legacy typographic ambiguity. The reusable root guide contains the full decision procedure and examples for future works.

## Gate consequence

- canonical records: **42 / 49**;
- retrospective historical-glyph pass on scans 1–27: **27 / 27 — COMPLETE**;
- glyph-aware new-page coverage: **scans 28–42 complete**;
- `verified`: **0**;
- `needs-review`: **42 — scans 1–42**;
- `partial`: **0**;
- `not-started`: **7 — scans 43–49**;
- Tamil source audit: **NOT PASSED**;
- assembled Tamil: **blocked**;
- English translation: **blocked**.

## Exact next activity

Transcribe **scans 43–47 / printed pages 42–46** as the next source-first batch. Apply the complete historical-glyph rule during first transcription, directly confirm expected internal headings `உலகநாதர்` on scan 45 and `கண்ணம்மா` on scan 46 before recording them, preserve physical page boundaries, create every page as `needs-review`, synchronize status documents, and stop after scan 47.