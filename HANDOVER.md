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
- scans 29–33 T1: **PASS / COMPLETE**;
- scans 29–33 T2: **PASS / COMPLETE — 9 corrections / 0 unresolved historical glyphs**;
- scans 29–33 T3: **NEXT**;
- scans 34–48: **NOT STARTED**.

T2 corrections include scan30 `ஆண்டவன்தானா`; scan31 `சிற்பங்களை`, `யோசனைகளை`, `ஊர்களை`; scan32 `அவளைச்`, `நன்றாகப்`, `நன்றாக`; scan33 both `தன்னாலான` occurrences. All five records remain `needs-review` pending T3.

## Exact next activity

Execute **T3 final source-fidelity closure for scans 29–33 only**. Check complete-page omissions/duplication/punctuation/joins and T2 findings, synchronize controls, commit, and stop before scan 34.
