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

- canonical records: **20 / 25 — scans 24–43**;
- verified: **20 / 25 — scans 24–43**;
- scans 24–38: **T1+T2+T3 PASS / VERIFIED**;
- scans 39–43: **T1+T2+T3 PASS / VERIFIED**;
- scans 39–43 T3: **8 corrections / 0 unresolved source readings**;
- final historical-glyph corrections scans 39–43: **3 / 0 unresolved**;
- scans 44–48: **NOT STARTED**.

Key T3 corrections include scan39 `ஏற்பட்ட வில்லையென்று`; scan40 `குளிர் மொழிகள்` / `கலை மட்டுமே`; scan41 `ஆனந்தத் தாண்டவம் என்றான்` / `தலைமைப் பீடத்தை`; scan43 `கலைக் கண்`, `உருகிக்கொண்டிருக்கிறான்`, `வழக்கத்திற்கு மாறாக`.

## Exact next activity

Execute **T1 direct transcription for scans 44–48 only** under SOURCE_BATCH_CHECKPOINT_WORKFLOW.md. Create the final five canonical records from direct source pixels, synchronize controls, commit, and stop before T2.

Do not begin the 1978 பெரிய இடத்துப் பெண் witness comparison.
