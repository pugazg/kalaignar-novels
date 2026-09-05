# Historical Glyph Audit — பெரிய இடத்துப் பெண்

## Status

**RETROSPECTIVE PASS COMPLETE — glyph-aware first-pass transcription active through scan 37; verification freeze remains active.**

The user identified a systematic transcription risk in this 1953 source: historical/pre-reform Tamil typeforms can be mistaken for modern glyphs by visual resemblance. The retrospective pass over scans **1–27** is complete. New canonical scans **28–37** were transcribed with the same historical-glyph checks applied before entry.

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

## Glyph-aware first-pass coverage — scans 28–32

These five pages were transcribed only after the 13-form check was applied. Scan 32 directly demonstrates the method: `கொலை` uses historical `லை`, while `தோன்றாமல்தான்` requires historical `றா` rather than apparent modern `று`. Internal heading `குமுதா` is directly confirmed on scan 32.

## Glyph-aware first-pass coverage — scans 33–37

All five pages were inspected at enlarged/high resolution before canonical entry. No page was marked verified.

- **scan 33 / printed 32:** old-form identities checked across the page, including `வீணாக்கிக்` (`ணா`), `என்றால்` (`றா`), `முல்லையும்` (`லை`), and `வளையல்களைத்தான்` (`ளை`). Printed line-wrap `கொள்வ` + `துண்டு` is joined as `கொள்வதுண்டு`; source wording `எந்த தூர் எண்ணங்களும்` and `கண்ணடி` is retained.
- **scan 34 / printed 33:** `லை / னை` families checked in `குலை`, `வேலைக்காரியாகச்`, `மாலை`, `என்னை`, and `வீரனைக்`. The page continues scan 33's final `சதா` with `என் இருதயப் பீடத்திலே...`.
- **scan 35 / printed 34:** historical `ணை` is explicitly decoded in `ஆணை`; historical `றா` is checked in `நின்றார்` and `தோற்றாய்`. Printed line-wraps `கட்டளை` + `யிட்டாள்` and `பிள்ளை` + `யைத்` are joined lexically. Final `அத` remains a physical page-boundary split.
- **scan 36 / printed 35:** `னொ / னை / லை` families checked in `இன்னொருவன்`, `என்னை`, `உன்னை`, and `வேலை`. Opening `னுடைய` resolves scan 35's `அத`; printed line-wrap `அடிமைப்` + `படுத்தவில்லை` is joined as `அடிமைப்படுத்தவில்லை`.
- **scan 37 / printed 36:** `னை / னா / ளை` families checked in `என்னை`, `என்னையே`, `அனுப்பினாளோ`, and `அவளை`. Printed line-wrap `கண்ணம்மாக்` + `களைக்` is joined as `கண்ணம்மாக்களைக்`. The page closes குமுதாவின் first-person statement with `இப்படிக்கு / இறக்கப் போகும் / குமுதா`.

No separate post-entry historical-glyph correction was required in scans 33–37 because the identities were decoded before transcription.

## Audit rule — mandatory for every remaining new page

For every page:

1. inspect complete glyph clusters at enlarged/native resolution;
2. check all 13 known historical forms explicitly;
3. identify character identity rather than copying apparent modern shape;
4. compare same-edition occurrences where useful;
5. encode the proven identity in modern Unicode;
6. do not normalize anything beyond proven glyph identity;
7. join ordinary within-page printed line-wrap fragments, but preserve physical page-boundary splits in the page records;
8. correct an independent transcription mismatch only with positive source-pixel support and record it separately;
9. keep the page `needs-review` under the current user-mandated verification freeze.

The 13-form chart is a minimum known reference set; remain alert for other legacy typographic ambiguity.

## Gate consequence

- canonical records: **37 / 49**;
- retrospective historical-glyph pass on scans 1–27: **27 / 27 — COMPLETE**;
- glyph-aware new-page coverage: **scans 28–37 complete**;
- `verified`: **0**;
- `needs-review`: **37 — scans 1–37**;
- `partial`: **0**;
- `not-started`: **12 — scans 38–49**;
- Tamil source audit: **NOT PASSED**;
- assembled Tamil: **blocked**;
- English translation: **blocked**.

## Exact next activity

Transcribe **scans 38–42 / printed pages 37–41** as the next source-first batch. Confirm scan 38's expected internal heading `வீரன்` directly from the source, apply the complete historical-glyph rule during first transcription, preserve physical page boundaries, create every page as `needs-review`, synchronize page-map/audit/READMEs/HANDOVER, and stop after scan 42.
