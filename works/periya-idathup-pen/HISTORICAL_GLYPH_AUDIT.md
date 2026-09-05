# Historical Glyph Audit — பெரிய இடத்துப் பெண்

## Status

**RETROSPECTIVE PASS COMPLETE — glyph-aware first-pass transcription complete through scan 49; verification freeze remains active.**

The retrospective page-by-page pass over scans **1–27** is complete. Canonical scans **28–49** were transcribed with historical-glyph checks applied before entry. All **49 / 49** canonical records remain `needs-review`; no page may be marked `verified` unless the user explicitly changes that policy.

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

## Coverage checkpoint

- scans **1–27**: retrospective historical-glyph pass complete;
- scans **28–49**: glyph-aware first-pass transcription complete;
- all canonical pages remain `needs-review`.

### Final batch — scans 48–49

- **scan 48 / printed 47:** `லை / னை` families checked in `விடவில்லை`, `வேலையில்`, `கவலை`, `என்னைச்`, `அவனைச்`; scan 47 `எழுதி` + scan 48 `யிருந்தாள்.` → `எழுதியிருந்தாள்.`; source-specific `வேசின்` and `தத்தம்` retained.
- **scan 49 / printed 48:** `லை / ளை / னை` families checked in `நிலையத்தை`, `கேளுங்கள்` and related clusters; scan 48 `ஒரு பெரிய` + scan 49 `ஜோதி நிரந்தரமாக...`; source-specific `அழுக்குப்பட்டு`, `உச்ச ஸ்தாயியை`, `போகவேண்டு மென்னிருக்கலே`, and `பாடங்` retained; printer colophon directly read as `ஸ்ரீமகள் அச்சகம், சென்னை-1`.

No post-entry historical-glyph correction was required in scans 28–49 because character identities were decoded during first transcription.

## Dedicated whole-work source audit interaction

The later full Tamil source/audit review is separate from this completed retrospective glyph pass but must continue using the same 13-form rule.

Current full-source audit checkpoint: **scans 1–20 / 49 directly reviewed**.

Within scans 11–20, the dedicated pass independently reconfirmed:

- scan 14 `ஆவலைக்` (`லை`) and `நின்றார்` (`றா`);
- scan 16 `போகிறாயே` (`றா`);
- scan 20 `நன்றாகத்` (`றா`);
- no new historical-glyph correction was discovered in scans 11–20.

The next full-source batch, scans **21–30**, must explicitly recheck scan 21 `நன்றாகத்தான்`, scan 24 `நன்றாக` / `விழுவேன் என்றானா?`, and scan 25 `வேலை மட்டுந்தானா?` from the source pixels rather than relying on this table.

## Audit rule

For any future correction or re-review in this work:

1. inspect complete glyph clusters at enlarged/native resolution;
2. check all 13 known historical forms explicitly;
3. identify character identity rather than copying apparent modern shape;
4. compare same-edition occurrences where useful;
5. encode only the proven modern Unicode identity;
6. do not normalize wording, grammar, punctuation or vocabulary;
7. never global-replace;
8. keep the page `needs-review` under the current verification freeze.

## Gate consequence

- canonical records: **49 / 49**;
- dedicated full-source audit: **20 / 49 reviewed — in progress**;
- `verified`: **0**;
- `needs-review`: **49**;
- `partial`: **0**;
- `not-started`: **0**;
- Tamil source audit: **NOT PASSED — in progress**;
- assembled Tamil: **blocked**;
- English translation: **blocked**.

## Exact next activity

Continue the dedicated **full Tamil source/audit review with scans 21–30 / printed pages 20–29**. Recheck historical-glyph identity from source pixels for every occurrence, with explicit attention to the known scan-21, scan-24 and scan-25 corrections. Do not mark pages verified and do not proceed to assembled Tamil or English.