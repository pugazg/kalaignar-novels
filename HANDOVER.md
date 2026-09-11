# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: pugazg/kalaignar-novels
- Branch: main
- **Live main is authoritative.**
- Active source: **1978 அரும்பு four-story compilation**.
- Active work: **works/sarapallam-samundi/**.
- works/arumbu/ is **RELEASE-READY / CLOSED**.

## Controlling source

TVA_BOK_0064361_அரும்பு.pdf — SHA-256 04a3013e1f58a1800867acc5d2f159976c47994a64478036e6fe0201edf120bc, **117,270,339 bytes**, **92 physical scans**, image-only, தமிழ்க்கனி பதிப்பகம், முதற் பதிப்பு 1978. **DO NOT COMMIT source PDF.**

## Active component durable state

சாரப்பள்ளம் சாமுண்டி spans scans **24–48 / 25 scans**.

- canonical records: **5 / 25 — scans 24–28**;
- verified: **0 / 25**;
- T1 scans 24–28: **PASS / COMPLETE**;
- T2 scans 24–28: **PASS / COMPLETE — 0 corrections / 0 unresolved glyphs**;
- T3 scans 24–28: **NEXT**;
- scans 29–48: **NOT STARTED**.

Source layout: scan 24 unnumbered opening; scans 25–27 print 21–23; scan 28 is an unnumbered landscape two-page illustration spread. No synthetic 24/25 is assigned.

T2 independently checked all five scans against direct source pixels and explicitly covered the known historical-glyph families. All page records remain needs-review because T3 is pending.

## Exact next activity

Execute **T3 final source-fidelity closure for scans 24–28 only** under SOURCE_BATCH_CHECKPOINT_WORKFLOW.md. Check omissions, duplication, page joins, printed-page visibility, non-body separation and the T2 findings. If the gate passes, mark these five records verified, synchronize controls, commit, and stop before scan 29.
