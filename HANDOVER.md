# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: pugazg/kalaignar-novels
- Branch: main
- **Live main is authoritative.**
- Active source: **1978 அரும்பு four-story compilation**
- Active work: **works/sarapallam-samundi/**
- works/arumbu/ is **RELEASE-READY / CLOSED**.

## Controlling source

TVA_BOK_0064361_அரும்பு.pdf — SHA-256 04a3013e1f58a1800867acc5d2f159976c47994a64478036e6fe0201edf120bc, **92 scans**, image-only, தமிழ்க்கனி பதிப்பகம், முதற் பதிப்பு 1978. **DO NOT COMMIT source PDF.**

## Active durable state

சாரப்பள்ளம் சாமுண்டி spans **scans 24–48 / 25 scans**.

- canonical records: **25 / 25 — COMPLETE / VERIFIED**;
- page-level T1/T2/T3: **PASS / COMPLETE**;
- whole-work Tamil audit: **PASS / COMPLETE after 1 residual direct-source correction**;
- residual correction: scan29 / printed26 வாயாலிருந்துவிட்டான் → **வாளாயிருந்துவிட்டான்**;
- unresolved historical glyphs: **0**;
- unresolved source readings: **0**;
- assembled Tamil: **PASS / COMPLETE — 1 / 1 section**;
- English translation plan: **PASS / COMPLETE**;
- English coverage: **15 / 25 scans**;
- English Batches 1–3 — scans **24–38: REVIEWED / COMPLETE**;
- English Batch 4 — scans **39–43: NEXT**;
- whole-work English: **IN PROGRESS / NOT VERIFIED**.

Whole-work mapping and continuity passed, including scan28's unnumbered landscape illustration spread and scan48's narrative-ending / separately printed historical-note distinction.

Audit report: works/sarapallam-samundi/FULL_TAMIL_SOURCE_AUDIT.md.

## Assembled Tamil closure

`works/sarapallam-samundi/sections/01-sarapallam-samundi.md` is **PASS / COMPLETE** as the single source-backed Tamil reading section for scans 24–48. It is derived only from audited canonical records and passes coverage, order, provenance-marker, verified-join and text-consistency checks. Scan 28 illustration material is not narrated, and scan 48 keeps the story ending distinct from the source-printed `குறிப்பு :`.

## English translation planning closure

`works/sarapallam-samundi/translations/en/TRANSLATION_PLAN.md` is **PASS / COMPLETE**. Working English title: **Sarapallam Samundi**. The one-section translation is divided into five controlled five-scan batches: **24–28**, **29–33**, **34–38**, **39–43**, **44–48**. Batch boundaries are workflow boundaries only, not source structure.

## English Batch 1 closure

The pilot translation for scans **24–28** is **REVIEWED / COMPLETE**. `translations/en/README.md`, `PROGRESS.md`, `GLOSSARY.md`, `BATCH_01_REVIEW.md`, and the in-progress one-section English file are now established. Source-check found **0 material omissions, 0 source-like additions and 0 unresolved items**. The scan-28 illustration is excluded, and the 28→29 sentence is intentionally left open until Batch 2.

## English Batch 2 closure

Scans **29–33** are **REVIEWED / COMPLETE**. The prior 28→29 open sentence is closed using scan 29 only; verified joins and the scan-29 corrected reading are preserved; terminology decisions are locked in the glossary. Cumulative English coverage is **10/25 scans**, with **0 material omissions / 0 source-like additions / 0 unresolved items** through Batch 2.

## English Batch 3 closure

Scans **34–38** are **REVIEWED / COMPLETE**. Source-check preserves Azhagi's royal audience, Sarapallam naming, protected source oddities, the 35→36 split `தாண்`+`டவ`, 36→37 dancer-model continuation and Rajaraja/Iniyan sequence. Cumulative English coverage is **15/25 scans** with **0 omissions / 0 source-like additions / 0 unresolved items**. Scan 38 remains deliberately open into scan 39; scan-39 prose is absent.

## Exact next activity

**English Batch 4 — scans 39–43 only.** Complete the open 38→39 sentence using scan 39, continue/source-check only that span, update controls, commit, and stop before Batch 5. Do not begin the 1978 பெரிய இடத்துப் பெண் witness comparison.
