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

- canonical records: **5/25**;
- verified records: **5/25 — scans 24–28**;
- T1 scans 24–28: **PASS**;
- T2 scans 24–28: **PASS — 0 corrections / 0 unresolved glyphs**;
- T3 scans 24–28: **PASS — 3 corrections / 0 unresolved source readings**;
- scans 29–48: **NOT STARTED**.

T3 corrections: scan25 `அரணை`; scan26 later `கீழைச் சாளுக்கிய`; scan27 `செய்யப்பட்டு விட்டனவா?`. Scan28 remains unnumbered landscape spread. Boundary-only look at scan29 confirms 28→29 continuation; no scan29 record exists yet.

## Exact next activity

Execute **T1 direct transcription for scans 29–33 only** under SOURCE_BATCH_CHECKPOINT_WORKFLOW.md. Create five canonical records from direct source pixels, synchronize controls, commit, and stop before T2.

Do not start scans 34+ or the 1978 பெரிய இடத்துப் பெண் witness comparison.
