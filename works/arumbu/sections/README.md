# Assembled Tamil Reading Layer — அரும்பு

இந்த `sections/` அடுக்கு வாசிப்பு தொடர்ச்சிக்காக உருவாக்கப்பட்ட **source-faithful derived layer**. இது canonical transcription அல்ல.

## Authority

Controlling archival Tamil layer: `../pages/`.

Scans **6–23**-க்கு உரிய **18 / 18** canonical page records அனைத்தும் T1, independent historical-glyph T2, final source-fidelity T3 மற்றும் whole-work Tamil audit ஆகியவற்றை முடித்து `verified` நிலையில் உள்ளன.

> முரண்பாடு ஏற்பட்டால் `pages/` record-தான் controlling archival text.

Source PDF repository-க்குள் commit செய்யப்படவில்லை; commit செய்யக்கூடாது.

## Work identity and structure

`அரும்பு` 1978 நான்கு-கதைத் தொகுப்பின் முதல் component work. Source-backed chapter divisions இல்லை. ஆகவே assembled Tamil ஒரு continuous section மட்டுமே.

| File | Source coverage | State |
|---|---|---|
| `01-arumbu.md` | scans **6–23** | **VERIFIED / PASSED** |

Printed-page provenance source-ஐப் போலவே காக்கப்படுகிறது: scan 6 unnumbered; scans 7–13 printed 2–8; scan 14 printed 10; scans 15–23 printed 11–19. Printed page 9 infer செய்யப்படவில்லை.

## Assembly controls

- text derives only from the 18 audited `pages/` records;
- source spelling, punctuation, dialogue, rhetoric and unusual readings remain unchanged;
- page-level audit notes and non-body observations are excluded from reading prose;
- the scan-6 title is retained; illustration content is not turned into prose;
- reversible source comments preserve physical provenance and established joins;
- no artificial chapter split or synthetic printed page is introduced;
- scan 23 remains without an unprinted `முற்றும்`.

The assembled Tamil layer was reconciled against all 18 verified page records and is **PASS / COMPLETE**.

## Downstream English state

English planning and all four translation batches are complete. The Section 16 whole-work bilingual review was previously marked PASS, but the subsequent Section 17 release-readiness preflight found one concrete English/source mismatch on scan 17:

- canonical source: `எனக்குப் பொய் அம்மா வேணும்!`;
- current English: `I don't want a fake Amma!`.

The English inserts a negation absent from the audited source. `../translations/en/RELEASE_REPORT.md` therefore records **NOT READY** and requires a narrow Section 16 corrective re-open. This finding does **not** alter the assembled Tamil or canonical Tamil layers.

## Current next activity

Correct and reverify the scan-17 English sentence under a narrow Section 16 corrective checkpoint, synchronize controls, and stop. Section 17 must then be rerun before another compilation component begins.
