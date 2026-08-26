# Native-resolution re-audit — புதையல் scans 23–32

Date: 2026-08-26

## Status

**FRESH NATIVE-RESOLUTION RE-AUDIT COMPLETED. CANONICAL USER BASELINE NOT SILENTLY ALTERED.**

This re-audit was performed after the previous assistant visual pass was invalidated for hallucinated corrections.

Controlling access split:

`TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf`

Method used for this pass:

- the split PDF was inspected directly;
- the embedded page images for scans 23–32 were extracted at their native **3146 × 4826** resolution;
- no OCR-derived reading was treated as authority;
- the user's restored Iteration 3 transcription remained the canonical baseline during review;
- where the native scan appears to disagree with the baseline, the canonical page text has **not** been silently changed; the discrepancy is recorded here for confirmation.

## Result by scan

| Scan | Printed page | Structure | Current status | Re-audit result |
|---:|:---:|---|---|---|
| 23 | 21 | chapter 2 | needs-review | one clear omitted word-group candidate + punctuation differences |
| 24 | 22 | chapter 2 | needs-review | two clear inflection candidates; one previously disputed glyph/word candidate; punctuation differences |
| 25 | 23 | chapter 2 | needs-review | lexical content broadly consistent; source punctuation / spacing not yet reconciled |
| 26 | 24 | chapter 2 | needs-review | user lexical readings `உண்மை தான்`, `மிக கூர்மையாக`, `வேகம் குறைந்தது` confirmed; punctuation / spacing still differs |
| 27 | 25 | chapter 2 | needs-review | lexical content broadly consistent; source punctuation differs |
| 28 | 26 | chapter 2 | needs-review | one clear word-form candidate (`அவன்` / `அவன`) + punctuation differences |
| 29 | 27 | chapter 2 | needs-review | two clear source-specific wording candidates plus spacing / punctuation |
| 30 | 28 | chapter 2 closes / chapter 3 begins | needs-review | one clear spelling candidate + punctuation; physical chapter transition confirmed |
| 31 | 29 | chapter 3 | needs-review | lexical content broadly consistent; several clear source spacing / dash / word-boundary differences |
| 32 | 30 | chapter 3 | needs-review | one clear compound-word candidate + punctuation differences; page still ends at `காலைத்` |

No page in scans 23–32 is promoted to `verified` yet because the unresolved source-vs-baseline discrepancies must be explicitly reconciled first.

## High-confidence source-vs-baseline candidates

These are visually clear in the native page images, but **have not been applied to the canonical page records** in this pass.

### Scan 23 / printed page 21

After:

`காதலர்கள் ஒளிந்திருந்த அந்த மதகின் மேலேயே அவர்கள் நின்று பேசிக்கொண்டிருந்தார்கள்.`

the native scan visibly continues:

`மதகின் உள்ளேயிருந்தவர்களுக்கு ...`

The restored user baseline currently has only:

`உள்ளேயிருந்தவர்களுக்கு ...`

So `மதகின்` is a candidate omitted word-group requiring confirmation before canonical alteration.

### Scan 24 / printed page 22

The native scan clearly prints:

- `சிறு ஆறுதல் அளித்தது`
- `சற்று ஆறுதல் அளித்தது`

The restored baseline currently has:

- `சிறு ஆறுதலை அளித்தது`
- `சற்று ஆறுதலை அளித்தது`

The native image also strongly appears to print:

`அவர்களே நோக்கி`

where the restored baseline has:

`அவர்களை நோக்கி`

Because this last reading was part of the earlier disputed assistant pass, it remains an **explicit unresolved candidate** rather than an applied correction.

### Scan 28 / printed page 26

The native scan clearly prints:

`அவன் முதுகில் யாரோ கை வைத்து அழுத்தினார்கள்.`

The restored baseline currently has:

`அவன முதுகில் யாரோ கை வைத்து அழுத்தினார்கள்.`

No silent change has been made.

### Scan 29 / printed page 27

The native scan visibly contains the source-specific forms:

- `அவர்களேதான்` (baseline: `அவர்களே தான்`)
- `கடல் பார்த்துக் கொண்டிருந்தாள்` (baseline: `கடலை பார்த்துக் கொண்டிருந்தாள்`)
- `அவளே அவன் காப்பாற்றித் தீர வேண்டும்` (baseline: `அவளை அவன் காப்பாற்றித் தீர வேண்டும்`)

The last two are wording differences, not merely punctuation. They are recorded for explicit confirmation before changing canonical text.

### Scan 30 / printed page 28

The native scan clearly prints:

`பழைய பிரார்த்தனையில் ...`

The restored baseline currently has:

`பழைய பிரார்ந்தனையில் ...`

The chapter `2` → `3` transition remains confirmed on this same physical scan.

### Scan 31 / printed page 29

The native scan clearly shows source word-boundary / punctuation forms including:

- `அவனைத் தழுவிக்` (baseline: `அவனைத்தழுவிக்`)
- `முயன்றும்—விடாமல்` (baseline has no source dash)
- `கட்டிவிட்டார்` (baseline: `கட்டி விட்டார்`)

These are not applied in this pass.

### Scan 32 / printed page 30

The native scan clearly prints:

`தும்பைப்பூ தாடியிலே`

The restored baseline currently has:

`தும்பை பூ தாடியிலே`

The physical page still ends mid-sentence at `காலைத்`.

## Readings from the restored baseline confirmed by native scan

The fresh pass also confirms that some user readings which the earlier assistant had incorrectly replaced are indeed supported by the native scan. Examples include:

- scan 26: `உண்மை தான்`;
- scan 26: `மிக கூர்மையாக`;
- scan 26: `அவனது நடையிலே வேகம் குறைந்தது`;
- scan 27: the first prayer occurrence has `உதவுகிறது.` rather than an exclamation mark;
- scan 27: `குளிர்காற்று`.

This is why the earlier all-at-once assistant correction pass must not be reused.

## Systematic punctuation issue in the supplied Iteration 3 baseline

The native scan does **not** support the baseline's systematic doubled terminal forms such as:

- `..`
- `!.`
- `?.`

The print generally uses ordinary single stops, question marks, exclamation marks and source dashes / long pauses. This punctuation difference exists throughout the ten-page range.

Because the user explicitly requested that no further assistant-inferred corrections be silently imposed, the canonical page text has not been punctuation-normalized during this re-audit. Punctuation reconciliation must be handled explicitly as a separate source-fidelity step.

## Page-boundary / structural checks retained

The native scan confirms:

1. scan 23 continues onto scan 24 inside the same dialogue;
2. scan 24 ends at `கடற்கரை வந்து` and scan 25 begins `விடும்.`;
3. scan 26 ends `பூரணமாக விளங்குவதற்கு` and scan 27 begins `உதவியாக...`;
4. scan 29 closes with the `சாவுக் கண்ணீர்!` cry and scan 30 continues it;
5. chapter `2` closes and chapter `3` begins on scan 30 / printed page 28;
6. scan 32 physically ends at `காலைத்`.

## Canonical-text action in this pass

**None.**

The restored user transcription in:

- `../pages/0023-pudhaiyal.md`
- `../pages/0024-pudhaiyal.md`
- `../pages/0025-pudhaiyal.md`
- `../pages/0026-pudhaiyal.md`
- `../pages/0027-pudhaiyal.md`
- `../pages/0028-pudhaiyal.md`
- `../pages/0029-pudhaiyal.md`
- `../pages/0030-pudhaiyal.md`
- `../pages/0031-pudhaiyal.md`
- `../pages/0032-pudhaiyal.md`

remains unchanged pending explicit reconciliation of the candidates above.

## Gate state

- page records created through scan 32: **32**
- `verified`: **22** — scans 1–22
- `needs-review`: **10** — scans 23–32
- Tamil whole-work audit: **not started**
- full-source manifest: **incomplete**
- English translation: **blocked**

## Exact next action

Reconcile the listed scan 23–32 candidates with the user, then apply only the confirmed source readings and source punctuation to the canonical page records. After that, perform one final page-by-page visual comparison of scans 23–32 before changing them to `verified`.

Do **not** advance to scans 33–42 until this range is resolved.