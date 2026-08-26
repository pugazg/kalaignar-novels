# Native-resolution fidelity audit — புதையல் scans 23–32

Date: 2026-08-26

## Status

**COMPLETED — scans 23–32 reconciled and VERIFIED against native embedded source images.**

This range was reopened after the earlier assistant visual-correction pass was invalidated for hallucinated readings.

Controlling access split:

`TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf`

Method:

- inspected the split PDF directly;
- extracted and inspected the embedded page images at **3146 × 4826**;
- used the user's Iteration 3 transcription as the comparison baseline;
- treated the scan, not OCR or grammar expectations, as textual authority;
- reconciled source spelling, spacing, punctuation and page boundaries only after repeated native-image checks;
- performed a final page-by-page pass before promoting the records to `verified`.

## Result

| Scan | Printed page | Structure | Status |
|---:|:---:|---|---|
| 23 | 21 | chapter 2 | verified |
| 24 | 22 | chapter 2 | verified |
| 25 | 23 | chapter 2 | verified |
| 26 | 24 | chapter 2 | verified |
| 27 | 25 | chapter 2 | verified |
| 28 | 26 | chapter 2 | verified |
| 29 | 27 | chapter 2 | verified |
| 30 | 28 | chapter 2 closes / chapter 3 begins | verified |
| 31 | 29 | chapter 3 | verified |
| 32 | 30 | chapter 3 | verified |

**Unresolved readings in scans 23–32: 0.**

## Reconciled source readings

### Scan 23 / printed page 21

- source: `மதகின் உள்ளேயிருந்தவர்களுக்கு`; the clean baseline had omitted the first `மதகின்`;
- source confirms the user's `முரடர்களின் பேச்சு கூட`; the earlier assistant reading `பேச்சுக் கூட` was wrong;
- systematic doubled clean-draft punctuation was replaced by the punctuation visible in the scan.

### Scan 24 / printed page 22

- `சிறு ஆறுதல் அளித்தது`;
- `சற்று ஆறுதல் அளித்தது`;
- source-specific `அவர்களே நோக்கி` is visibly printed and retained without grammatical regularization;
- `அப்போது தான்` retained.

### Scan 25 / printed page 23

The long dream explanation was rechecked in full. Source-supported forms include:

- `ஏதோ`;
- `முடியாமற் போனதாகவும்`;
- `இயலாமற் போனதாகவும்`;
- `உணர்ந்ததாகவும்`.

The clean baseline's separated `போன தாகவும்` / `உணர்ந்த தாகவும்` forms were not retained. Source dialogue punctuation and dashes were restored.

### Scan 26 / printed page 24

The native scan confirms the user's readings that the earlier assistant had wrongly questioned:

- `உண்மை தான்`;
- `மிக கூர்மையாக`;
- `அவனது நடையிலே வேகம் குறைந்தது`.

### Scan 27 / printed page 25

- first prayer occurrence `உதவுகிறது.` confirmed;
- `குளிர்காற்று` confirmed;
- the clean draft's extra ellipsis after `போலத்தானா?` is not printed and was removed.

### Scan 28 / printed page 26

- source clearly prints `அவன் முதுகில்`; the restored baseline's `அவன முதுகில்` was corrected.

### Scan 29 / printed page 27

A second native-image check corrected two mistakes in the earlier candidate report itself:

- source is **`அவர்களே தான்`**, with the words separated; the earlier candidate `அவர்களேதான்` is withdrawn;
- source is `கடல் பார்த்துக் கொண்டிருந்தாள்`, not baseline `கடலை பார்த்துக் கொண்டிருந்தாள்`;
- source confirms the user's **`அவளை அவன் காப்பாற்றித் தீர வேண்டும்`**; the earlier candidate `அவளே அவன்...` was a misreading and is withdrawn;
- the two-line `சாவுக் கண்ணீர்!` cry is preserved.

### Scan 30 / printed page 28

- source `பழைய பிரார்த்தனையில்`; clean baseline `பழைய பிரார்ந்தனையில்` corrected;
- chapter `2` closes and chapter `3` begins on the same physical scan after the printed rule.

### Scan 31 / printed page 29

- source has a full stop after `மூர்ச்சை யடைந்தான்.`; the earlier assistant claim of missing punctuation is withdrawn;
- `அவனைத் தழுவிக்`;
- `முயன்றும்—விடாமல்`;
- `கட்டிவிட்டார்`.

### Scan 32 / printed page 30

- source `தும்பைப்பூ தாடியிலே`;
- source dash sequences in `சாந்தமும்—அமைதியும்—அடக்கமும்—...` restored;
- physical page ends at `காலைத்`; no continuation was inferred.

## Punctuation reconciliation

The supplied clean transcription systematically used terminal forms such as `..`, `!.`, and `?.`. Native inspection established that these are not generally the source punctuation in this range. The canonical records now follow the visible print: ordinary stops, question/exclamation marks, and the source's dashes / longer pauses.

This was a source-fidelity correction, not stylistic modernization.

## Page-boundary / structural checks

Final native-image pass confirms:

1. scan 23 → 24 continues the same dialogue;
2. scan 24 `கடற்கரை வந்து` → scan 25 `விடும்.`;
3. scan 26 `பூரணமாக விளங்குவதற்கு` → scan 27 `உதவியாக...`;
4. scan 29 `சாவுக் கண்ணீர்!` → scan 30 `என்ற ஒலிதான் அது!`;
5. chapter `2` closes and chapter `3` begins on scan 30 / printed page 28;
6. scan 32 ends at `காலைத்`.

## Canonical records finalized

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

## Gate state after this audit

- page records created through scan 32: **32**
- `verified`: **32**
- `needs-review`: **0**
- unresolved readings in scans 1–32: **0**
- known-prefix rows `not-started`: **118**
- full-source manifest: **incomplete**
- Tamil whole-work audit: **not started**
- assembled Tamil layer: **blocked**
- English translation: **blocked**

## Exact next activity

Process the user's next transcription iteration for **scans 33–42 / printed pages 31–40** from split part 001. This continues chapter `3` and crosses into chapter `4` at scan 40 / printed page 38.

Use the same native-image comparison method. Do not silently override supplied text from a small preview; establish any disagreement against the native scan before changing canonical text.