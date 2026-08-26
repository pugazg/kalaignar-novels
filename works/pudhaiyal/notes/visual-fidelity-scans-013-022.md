# Corrected visual-fidelity re-audit — புதையல் scans 13–22

Date: 2026-08-26

## Why this re-audit was required

The previous pass over scans **13–22** contained several assistant misreads of spacing and old-print Tamil forms. After the user identified hallucinated corrections in the following iteration, this entire earlier range was reopened rather than trusted.

The fresh pass used the embedded scan images extracted directly from `TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf` at their native image size (**3146 × 4826**) instead of relying only on the smaller renderer preview.

The source scan remains controlling. The user's transcription is the comparison baseline; apparent differences are not silently regularized.

## Scope

- boundary page rechecked: scan **12 / printed page 10** — no rollback required;
- primary re-audit: scans **13–22**;
- scan 13 remains a chapter-opening page with **no visibly printed page number**;
- scan 22 / printed page 20 still closes chapter 1 and begins chapter 2 on the same physical scan.

## Result

| Scan | Printed page | Structure | Result after fresh re-audit |
|---:|:---:|---|---|
| 12 | 10 | `அறிமுகம்` ends | verified; no correction required |
| 13 | — | chapter 1 begins | verified after correcting earlier assistant misreads |
| 14 | 12 | chapter 1 | verified |
| 15 | 13 | chapter 1 | verified after correcting earlier assistant misreads |
| 16 | 14 | chapter 1 | verified after correcting one spacing misread |
| 17 | 15 | chapter 1 | verified after correcting earlier assistant misreads |
| 18 | 16 | chapter 1 | verified |
| 19 | 17 | chapter 1 | verified after correcting earlier assistant misreads |
| 20 | 18 | chapter 1 | verified |
| 21 | 19 | chapter 1 | verified after correcting one spacing misread |
| 22 | 20 | chapter 1 closes / chapter 2 begins | verified |

**Unresolved readings in scans 12–22 after this re-audit: 0.**

## Assistant corrections that were WRONG and have now been withdrawn

### Scan 13

The previous pass incorrectly changed the user's readings to:

- `அப்போதுதான்`
- `கையிலும்`

Fresh high-resolution inspection shows:

- `அப்போது தான்`
- the physical line break is `கையிலே` / `யும்`, giving canonical `கையிலேயும்`

The earlier assistant claims are withdrawn and the canonical page record has been corrected.

### Scan 15

The previous pass incorrectly introduced:

- `நம்பிக்கையுண்டு`
- `அதனால்தான்`
- `தன உயிருக்கு`
- `அவர்களும் வந்துவிட்டார்கள்`

Fresh inspection supports:

- `நம்பிக்கை யுண்டு`
- `அதனால் தான்`
- `தன உயிருக்கே`
- `அவர்களும் வந்து விட்டார்கள்`

These have been corrected in `pages/0015-pudhaiyal.md`.

### Scan 16

The previous pass fused the phrase as `அடங்கிவிட்டதாகத் தானே`.

The scan supports:

- `அடங்கி விட்டதாகத் தானே`

The canonical page has been corrected.

### Scan 17

The previous pass incorrectly recorded:

- `இடையிலேதான்`
- `ஆராய்ந்து விட்டோமே`
- `சரியாகத்தான்`

The scan supports:

- `இடையிலே தான்`
- `ஆராய்ந்து விட்டோம்`
- `சரியாகத் தான்`

The canonical page has been corrected.

### Scan 19

The previous pass incorrectly recorded:

- `அவ்வளவுதான்`
- `ஜோசியர் கூறிய நாளை தவற விட்டு விட்டால்`

Fresh inspection supports:

- `அவ்வளவு தான்`
- `ஜோசியர் கூறிய நாளைத் தவற விட்டு விட்டால்`

The canonical page has been corrected.

### Scan 21

The previous pass incorrectly fused:

- `அடிபட்டுவிட்டதால்`

The scan supports:

- `அடிபட்டு விட்டதால்`

The canonical page has been corrected.

## Earlier corrections that ARE still supported by the scan

The re-audit also checked the earlier pass rather than assuming every difference was wrong. The following remain visually supported:

- scan 13: no printed page number is visible; `printed_page: null` remains correct;
- scan 13: `படை வசதியிலேதான்!` remains supported;
- scan 14: `மருங்கப் பள்ளத்தின்` and `பூமியைத் தோண்டிப்` remain supported;
- scan 15: `மெளனமாய்` / `மெளனமாக்கியது` are the printed forms;
- scan 16: the inscription continues through `கம்மாளர் கண்ணிலே......`;
- scan 18: four separate opening dialogue lines are visibly printed — `அத்தான்!`, `கண்ணே!`, `ராஜா!`, `என்னடி ராஜாத்தி!`;
- scan 18: later speech reads `மறக்க மாட்டீர்களே கண்ணே!`;
- scan 19: `வெளவாலிடம்` / `வெளவால்` are visibly printed;
- scan 22: chapter `2` begins on the same physical scan after the chapter-1 ending and printed divider.

## Page-boundary continuity reconfirmed

- scan 12 closes `அறிமுகம்`; scan 13 begins chapter `1`;
- scan 13 `அவன் மீதுள்ள` → scan 14 `அன்பால்`;
- scan 14 `அவரே குறித்துக்கொண்ட நாள்` → scan 15 `அல்ல; ஜோசியர் குறித்த நாள்.`;
- scan 15 `அவர்கள்` → scan 16 `ஒவ்வொருவரிடமும்`;
- scan 16 `படபடப்பை` → scan 17 `உண்டாக்கியது தெரியுமா?`;
- scan 17 leads into the four short dialogue lines on scan 18;
- scan 20 `அந்தப் பயலும்` → scan 21 `சிறுக்கியும்...`;
- scan 21 pursuit narrative continues onto scan 22 before the chapter-2 divider.

## Canonical files corrected in this re-audit

- `../pages/0013-pudhaiyal.md`
- `../pages/0015-pudhaiyal.md`
- `../pages/0016-pudhaiyal.md`
- `../pages/0017-pudhaiyal.md`
- `../pages/0019-pudhaiyal.md`
- `../pages/0021-pudhaiyal.md`

Scans 12, 14, 18, 20 and 22 were rechecked and did not require canonical text rollback in this pass.

## Workflow rule strengthened

For old-print Tamil, especially when a word crosses a physical line boundary, do not collapse or replace a user reading from a small preview. Use the native embedded scan image first. If a glyph or spacing remains genuinely ambiguous after native-resolution inspection, mark the page `needs-review` instead of asserting a correction.

## Gate state

- scans 1–22: **22 verified**;
- scans 23–32: **10 needs-review** because the later assistant pass was invalidated and the user's Iteration 3 transcription was restored;
- Tamil whole-work audit: **not started**;
- full-source manifest: **incomplete**;
- English translation: **blocked**.

## Exact next action

Before accepting any further transcription iteration, use the same native embedded-image method. The next unresolved archival range is still scans **23–32**, whose user-supplied text has been restored and remains `needs-review`; do not reintroduce the invalidated assistant substitutions.