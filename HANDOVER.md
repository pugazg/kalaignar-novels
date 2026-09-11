# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: pugazg/kalaignar-novels
- Branch: main
- **Live main is authoritative.**
- Active source: **1978 அரும்பு four-story compilation**
- Active work: **works/sarapallam-samundi/**
- works/arumbu/ is **RELEASE-READY / CLOSED**.

## Controlling source

`TVA_BOK_0064361_அரும்பு.pdf` — SHA-256 `04a3013e1f58a1800867acc5d2f159976c47994a64478036e6fe0201edf120bc`, **92 scans**, image-only, தமிழ்க்கனி பதிப்பகம், முதற் பதிப்பு 1978. **DO NOT COMMIT source PDF.**

## Active durable state

`சாரப்பள்ளம் சாமுண்டி` spans **scans 24–48 / 25 scans**.

- canonical records: **10 / 25 — scans 24–33**;
- verified: **5 / 25 — scans 24–28**;
- scans 24–28: **T1+T2+T3 PASS / VERIFIED**;
- scans 29–33: **T1 PASS / COMPLETE**;
- scans 29–33 T2: **NEXT**;
- scans 29–33 T3: **BLOCKED by T2**;
- scans 34–48: **NOT STARTED**.

Second-batch printed pages are directly visible as scan29=26, scan30=27, scan31=28, scan32=29, scan33=30. New records remain `needs-review` pending T2/T3.

## Exact next activity

Execute **T2 independent historical-glyph / character-identity re-read for scans 29–33 only**. Check each complete scan and all sensitive glyph families, make only source-pixel-supported character corrections, synchronize controls, commit, and stop before T3.

Do not begin scan 34 or the 1978 `பெரிய இடத்துப் பெண்` witness comparison in the same checkpoint.
