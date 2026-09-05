# Historical Glyph Audit — பெரிய இடத்துப் பெண்

## Status

**OPEN — blocking page verification.**

The user identified a systematic transcription risk in this 1953 source: historical/pre-reform Tamil typeforms can be mistaken for modern glyphs by visual resemblance. All canonical records for scans **1–27** remain `needs-review`. No page may be marked `verified` while this audit is open unless the user explicitly changes that policy.

## User-supplied Periyar reform reference

Known historical forms must be decoded to these modern Unicode identities:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

The chart is a decoding reference, not permission to modernize spelling, grammar, punctuation, vocabulary, or wording. Every occurrence must be checked against its own source pixels; no global replacement is allowed.

## Confirmed historical-glyph corrections

| Scan | Printed page | Incorrect transcription | Correct Unicode reading |
|---:|:---:|---|---|
| 20 | 19 | `நன்றுகத்` | `நன்றாகத்` |
| 21 | 20 | `நன்றுகத்தான்` | `நன்றாகத்தான்` |
| 24 | 23 | `நன்றுக` | `நன்றாக` |
| 24 | 23 | `விழுவேன் என்றுனா?` | `விழுவேன் என்றானா?` |

## Other source-text corrections found during the retrospective pass

| Scan | Printed page | Earlier reading | Source-supported reading | Kind |
|---:|:---:|---|---|---|
| 4 | — | `சமூகத்தின்` | `சமுதாயத்தின்` | lexical/source-text correction |
| 5 | — | `அற்பிய` | `அரும்பிய` | lexical/source-text correction |
| 5 | — | `சமூகமும்` | `சமுதாயம்` | lexical/source-text correction |
| 7 | 6 | `உள்ளங்களை` | `உள்ளங்களே` | line-break/source-text correction |

## Retrospective pass progress

| Scan | Printed page | Historical-glyph pass | Result | Page status |
|---:|:---:|---|---|---|
| 1 | — | complete | no correction | `needs-review` |
| 2 | — | complete | no source-work print; later label checked, no correction | `needs-review` |
| 3 | — | complete | `லை / னை / னா` occurrences already encoded correctly | `needs-review` |
| 4 | — | complete | six historical-form occurrences confirmed; `சமூகத்தின்` → `சமுதாயத்தின்` | `needs-review` |
| 5 | — | complete | four historical-form occurrences confirmed; two lexical corrections | `needs-review` |
| 6 | — | complete | five historical-form occurrences confirmed; no text correction | `needs-review` |
| 7 | 6 | complete | seven historical-form occurrences confirmed; `உள்ளங்களை` → `உள்ளங்களே` | `needs-review` |
| 8 | — | complete | nine historical-form occurrences confirmed; no text correction | `needs-review` |

### Scan 1

Cover checked against the complete 13-form reference. No conversion or text correction required.

### Scan 2

No original 1953 source-work print is present. The later printed gift label was checked against the complete reference; no conversion required. Handwriting remains copy-specific and outside canonical source-work text.

### Scan 3

Positive historical forms already encoded correctly: `ஜூலை` (`லை`), `விலை` (`லை`), `விற்பனை` (`னை`), `சைனா` (`னா`), `சென்னை` (`னை`).

### Scan 4

Positive historical forms already encoded correctly: `தலையிடுவது` (`லை`), `பார்ப்பதில்லை` (`லை`), `ஆனால்` (`னா`), `எத்தனையோ` (`னை`), `ஆனாலும்` (`னா`), `கருணாநிதி` (`ணா`). Independent correction: `சமூகத்தின்` → `சமுதாயத்தின்`.

### Scan 5

Positive historical forms already encoded correctly: `அதினைச்` (`னை`), `அதினை` (`னை`), `கருத்துக்களைத்` (`ளை`), `மூலை` (`லை`). Independent corrections: `அற்பிய` → `அரும்பிய`; `சமூகமும்` → `சமுதாயம்`. Source-specific `விலாவொடியப்`, `ஏற்பட்டச்`, and `அவர்கட்கு` retained.

### Scan 6

Positive historical forms already encoded correctly: `கருணாநிதி` (`ணா`), `நிலையில்` (`லை`), `இல்லை` (`லை`), `அதனால்` (`னா`), `கற்பனைதான்` (`னை`). No independent text correction required. Source-supported `வனிதையர்களின்`, `வாலிபக் கிழங்களோடு`, `புரையோடிக்கொண்டிருக்கும்`, and `நம்முன். காட்சியளிக்கத்தான்` retained.

### Scan 7

Positive historical forms already encoded correctly: `வெள்ளை` (`ளை`), `விற்பனையாவதிலிருந்து` (`னை`), `மலை` (`லை`), `இன்னொரு` (`னொ`), `மூலை` (`லை`), `போகிறாள்` (`றா`), `முன்னிலையில்` (`லை`). Direct enlarged inspection showed source `உள்ளங்` + `களே`, so `உள்ளங்களை` was corrected to **`உள்ளங்களே`**. Source-supported punctuation and wording were retained.

### Scan 8

The first narrative page was re-read in full at enlarged/high resolution.

Positive historical forms already encoded correctly:

- `நினைத்தவாறே` — `றா`;
- `வேலை` — `லை`;
- `தோன்றவில்லை` — `லை`;
- `தோள்களை` — `ளை`;
- `விழவில்லை` — `லை`;
- `சிந்தனையைச்` — `னை`;
- `லீலைகள்` — `லை`;
- `ஆனால்` — `னா`;
- `திருப்பினாள்` — `னா`.

No historical-glyph conversion or independent text correction was required. Source-supported `வேலை யெல்லாம்`, `அணிச்சக்`, `இதயப் படுதாவில்`, `ஊர்க் கடைசியிலுள்ள`, the dotted pause before `இருக்கீங்க?`, and the paragraph structure were retained unchanged.

**Progress: 8 / 27 existing canonical scans reviewed; scans 9–27 pending.** All reviewed pages remain `needs-review`.

## Audit rule

For every page:

1. inspect complete glyph clusters at enlarged/native resolution;
2. check all 13 known historical forms explicitly;
3. identify character identity rather than copying apparent modern shape;
4. compare same-edition occurrences where useful;
5. encode the proven identity in modern Unicode;
6. do not normalize anything beyond proven glyph identity;
7. correct any independent transcription mismatch only with positive source-pixel support and record it separately;
8. keep the page `needs-review` while the work-wide audit remains open.

The 13-form chart is a minimum known reference set; remain alert for other legacy typographic ambiguity.

## Gate consequence

- canonical records: **27 / 49**;
- retrospective historical-glyph pass: **8 / 27 — scans 1–8**;
- `verified`: **0**;
- `needs-review`: **27 — scans 1–27**;
- `partial`: **0**;
- `not-started`: **22 — scans 28–49**;
- Tamil source audit: **NOT PASSED**;
- assembled Tamil: **blocked**;
- English translation: **blocked**.

## Exact next activity

Audit **scan 9 only** next. Inspect the whole scan at enlarged/high resolution against the complete 13-form reference, make only pixel-supported corrections, record the result, keep scan 9 `needs-review`, and stop.
