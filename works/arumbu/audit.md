# Audit — அரும்பு

## Gate state

| Stage | Status |
|---|---|
| Collection/source intake | **PASS / COMPLETE** |
| Work identity / scan boundary | **PASS — scans 6–23** |
| Page-level Tamil transcription | **COMPLETE — 18 / 18 canonical records** |
| All T1/T2/T3 source batches | **PASS / COMPLETE — VERIFIED** |
| Historical-glyph unresolved items | **0** |
| Source-fidelity unresolved items | **0** |
| Whole-work Tamil audit | **PASS / COMPLETE** |
| Assembled Tamil | **PASS / COMPLETE — 1 / 1 section** |
| English translation plan | **PASS / COMPLETE** |
| English Batches 1–4 | **4 / 4 REVIEWED / COMPLETE** |
| English coverage | **18 / 18 scans — scans 6–23** |
| Section 16 whole-work bilingual review | **CORRECTIVE RE-OPEN REQUIRED** |
| Whole-work English VERIFIED label | **SUSPENDED pending recheck** |
| Section 17 release-readiness | **NOT READY — 1 fidelity blocker** |

No source PDF is committed.

## Tamil archival state

All **18/18** canonical records remain VERIFIED. T2 corrections: **6**, unresolved historical glyphs: **0**. T3 corrections: **36**, unresolved source readings: **0**. Whole-work Tamil audit and assembled Tamil remain **PASS / COMPLETE**.

Canonical Tamil was **not changed** during the Section 17 release preflight.

## Section 17 release-preflight blocker

Canonical scan 17 / printed page 13 reads:

`எனக்குப் பொய் அம்மா வேணும்! நிஜ அம்மாதான் வேணும்!`

Current English reads:

`I don't want a fake Amma! I want my real Amma!`

The English adds the negation `don't`, which is absent from the verified canonical Tamil. Direct re-inspection of the controlling scan supports the affirmative `வேணும்`. Because source strangeness cannot be silently repaired from context, this is release-blocking and requires a narrow Section 16 corrective re-open.

See `translations/en/RELEASE_REPORT.md`.

## Other release checks

- work/source identity: **PASS**;
- Tamil inventory: **18/18 VERIFIED**;
- assembled Tamil inventory: **1/1 PASSED**;
- English physical coverage: **18/18 scans present**;
- one-work/one-section structure: **PASS**;
- source pagination anomaly 8→10: **preserved**;
- source-PDF exclusion: **PASS — no `.pdf` path in live recursive tree**;
- protected `பேசினேன்` / `அம்மனார்` / `இனி:......` / no-`முற்றும்` handling: **retained**;
- stale `indexes/page-map.md` and `sections/README.md`: **synchronized during Section 17 preflight**.

## Exact next activity

Perform the narrow Section 16 corrective re-open for scan 17, update English/review/glossary controls, recheck the affected paragraph and joins, and restore VERIFIED only if it passes. Then rerun Section 17 release-readiness. Do not start another component first.
