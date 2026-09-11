# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- **Live main is authoritative.**
- Active source: **1978 அரும்பு four-story compilation**
- Active work: **`works/sarapallam-samundi/`**
- `works/arumbu/` is **RELEASE-READY / CLOSED**.

## Controlling source

`TVA_BOK_0064361_அரும்பு.pdf` — SHA-256 `04a3013e1f58a1800867acc5d2f159976c47994a64478036e6fe0201edf120bc`, **92 scans**, image-only, தமிழ்க்கனி பதிப்பகம், முதற் பதிப்பு 1978. **DO NOT COMMIT source PDF.**

## Active durable state

`சாரப்பள்ளம் சாமுண்டி` spans **scans 24–48 / 25 scans**.

- canonical records: **10 / 25 — scans 24–33**;
- verified: **10 / 25 — scans 24–33**;
- scans 24–28: **T1+T2+T3 PASS / VERIFIED**;
- scans 29–33: **T1+T2+T3 PASS / VERIFIED**;
- scans 29–33 T3: **13 correction items / 0 unresolved source readings**;
- final historical-glyph corrections scans 29–33: **11 / 0 unresolved**;
- scans 34–48: **NOT STARTED**.

Important corrective history: the original scans 29–33 T2 checkpoint found 9 historical-glyph corrections; T3 caught two additional historical identities (`சிலைகளை`, `பிரமராயனை`) and substantial ordinary source-fidelity issues, including a major scan-33 omitted/reconstructed block.

## Exact next activity

Execute **T1 direct transcription for scans 34–38 only** under `SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`. Create five canonical records from direct source pixels, synchronize controls, commit, and stop before T2.

Do not begin scan 39 or the 1978 `பெரிய இடத்துப் பெண்` witness comparison.
