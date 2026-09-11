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
- English translation plan: **NEXT**;
- English prose: **BLOCKED until plan exists**.

Whole-work mapping and continuity passed, including scan28's unnumbered landscape illustration spread and scan48's narrative-ending / separately printed historical-note distinction.

Audit report: works/sarapallam-samundi/FULL_TAMIL_SOURCE_AUDIT.md.

## Assembled Tamil closure

`works/sarapallam-samundi/sections/01-sarapallam-samundi.md` is **PASS / COMPLETE** as the single source-backed Tamil reading section for scans 24–48. It is derived only from audited canonical records and passes coverage, order, provenance-marker, verified-join and text-consistency checks. Scan 28 illustration material is not narrated, and scan 48 keeps the story ending distinct from the source-printed `குறிப்பு :`.

## Exact next activity

Create the mandatory English translation plan at `works/sarapallam-samundi/translations/en/TRANSLATION_PLAN.md` under Section 14 of `NOVEL_PROCESSING_GUIDE.md`. Do not translate English prose until that plan is committed. Do not begin the 1978 பெரிய இடத்துப் பெண் witness comparison.
