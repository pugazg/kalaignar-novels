# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- **Live `main` is authoritative.**
- Active source: **1978 `அரும்பு` four-story compilation**.
- Active work: `works/arumbu/`.
- `works/vellikkizhamai/` remains RELEASE-READY / CLOSED.

## Source

`TVA_BOK_0064361_அரும்பு.pdf` — SHA-256 `04a3013e1f58a1800867acc5d2f159976c47994a64478036e6fe0201edf120bc`, **117,270,339 bytes**, **92 scans**, image-only, தமிழ்க்கனி பதிப்பகம், முதற் பதிப்பு 1978. **DO NOT COMMIT source PDF.**

## Component map

1. `அரும்பு` scans **6–23** — **TAMIL / ASSEMBLED TAMIL PASSED; ENGLISH VERIFIED AFTER CORRECTIVE RE-OPEN; SECTION 17 RERUN NEXT**.
2. `சாரப்பள்ளம் சாமுண்டி` scans **24–48** — queued.
3. `பெரிய இடத்துப் பெண்` scans **49–74** — additional 1978 witness only.
4. `நடுத்தெரு நாராயணி` scans **75–90** — queued.

## Durable `அரும்பு` state

- canonical Tamil: **18/18 VERIFIED**;
- T1/T2/T3: **PASS / COMPLETE**;
- T2 corrections **6**, unresolved historical glyphs **0**;
- T3 corrections **36**, unresolved source readings **0**;
- whole-work Tamil audit: **PASS / COMPLETE**;
- assembled Tamil: **1/1 PASS**;
- English Batches 1–4: **4/4 REVIEWED**;
- English coverage: **18/18 scans**;
- Section 16: **PASS / COMPLETE after scan-17 corrective re-open**;
- whole-work English: **VERIFIED**;
- total Section-16 English-only corrections: **4**;
- unresolved translation items: **0**;
- canonical Tamil changes during corrective re-open: **0**;
- Section 17: **RERUN NEXT**.

## Corrective finding resolved

The failed Section 17 preflight found canonical `எனக்குப் பொய் அம்மா வேணும்!` had been rendered with an inserted English negative. It is now source-faithfully preserved as:

**“I want a fake Amma! It's my real Amma I want!”**

Direct source pixels and canonical scan 17 support affirmative `வேணும்`. The full scan-17 paragraph plus 16→17 / 17→18 joins passed corrective recheck. `TRANSLATION_REVIEW.md` and `GLOSSARY.md` record the decision.

Previously protected oddities remain: **I spoke / Ammanar / from now on:...... / no The End**.

## Exact next activity

Rerun **Section 17 release-readiness for `அரும்பு` only**. Read Section 17 of `NOVEL_PROCESSING_GUIDE.md`, `RELEASE_REPORT.md`, corrected English and synchronized controls; verify inventories/navigation/authority/structure/source oddities/canonical-Tamil immutability/source-PDF exclusion; issue final archival/editorial verdict; commit and stop.

Do **not** start `சாரப்பள்ளம் சாமுண்டி` or the 1978 `பெரிய இடத்துப் பெண்` witness comparison in that checkpoint.
