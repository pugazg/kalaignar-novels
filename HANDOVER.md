# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- **Live `main` is authoritative.**
- Active source: **1978 `அரும்பு` four-story compilation**.
- Active work: `works/arumbu/`.
- `works/vellikkizhamai/` remains RELEASE-READY / CLOSED.

## Controlling compilation source

`TVA_BOK_0064361_அரும்பு.pdf`

- SHA-256: `04a3013e1f58a1800867acc5d2f159976c47994a64478036e6fe0201edf120bc`
- size: **117,270,339 bytes**
- physical scans: **92**
- image-only
- publisher: **தமிழ்க்கனி பதிப்பகம், சென்னை-28**
- edition: **முதற் பதிப்பு — 1978**
- source PDF: **DO NOT COMMIT**.

Collection intake: `collections/arumbu-1978/` — **COMPLETE**.

## Component map

1. `அரும்பு` — scans **6–23** — **TAMIL / ASSEMBLED TAMIL PASSED; SECTION 17 NOT READY — scan-17 English correction required**.
2. `சாரப்பள்ளம் சாமுண்டி` — scans **24–48** — queued.
3. `பெரிய இடத்துப் பெண்` — scans **49–74** — additional 1978 witness only; existing controlling source/canonical freeze unchanged.
4. `நடுத்தெரு நாராயணி` — scans **75–90** — queued.

Scans 1–5 are collection front matter; scans 91–92 publisher catalogue/back-cover matter.

## `அரும்பு` durable state

- canonical / verified Tamil records: **18 / 18 — scans 6–23 contiguous**;
- all T1/T2/T3 source batches: **PASS / COMPLETE**;
- T2 corrections: **6**; unresolved historical glyphs: **0**;
- T3 corrections: **36**; unresolved source readings: **0**;
- whole-work Tamil audit: **PASS / COMPLETE**;
- assembled Tamil: **PASS / COMPLETE — 1 / 1 section**;
- English translation plan: **PASS / COMPLETE**;
- English Batches 1–4: **4 / 4 REVIEWED / COMPLETE**;
- English physical coverage: **18 / 18 scans — scans 6–23**;
- Section 16 was previously marked PASS / whole-work English VERIFIED;
- Section 17 release preflight: **NOT READY**;
- release blocker: **1 scan-17 English/source fidelity mismatch**;
- whole-work VERIFIED label: **SUSPENDED pending corrective recheck**;
- canonical Tamil changes during release preflight: **0**.

## Release-preflight blocker

Canonical scan 17 / printed 13 reads:

`எனக்குப் பொய் அம்மா வேணும்! நிஜ அம்மாதான் வேணும்!`

Current English reads:

`I don't want a fake Amma! I want my real Amma!`

The English inserts a negative not printed in the audited Tamil. Direct scan re-inspection supports affirmative `வேணும்`. Source strangeness must be preserved, not repaired from context. See `works/arumbu/translations/en/RELEASE_REPORT.md`.

The release preflight also found stale English-status text in `works/arumbu/indexes/page-map.md` and `works/arumbu/sections/README.md`; both have now been synchronized.

Other protected source handling remains valid: scan 22 `பேசினேன்` → **I spoke**; scan 23 `அம்மனார்` → **Ammanar**; final `இனி:......` → **from now on:......**; no source `முற்றும்` → no **The End**.

## Exact next activity

Perform a **narrow Section 16 corrective re-open for scan 17 only**:

- change the English clause to preserve the source-confirmed affirmative `பொய் அம்மா வேணும்` rather than inserting `don't`;
- document the oddity/correction in `GLOSSARY.md` and `TRANSLATION_REVIEW.md`;
- recheck the full affected paragraph and 16→17 / 17→18 joins against canonical Tamil;
- restore whole-work English VERIFIED only if that corrective review passes;
- synchronize English/work/root controls, commit, and stop.

Then rerun Section 17 release-readiness. Do **not** start `சாரப்பள்ளம் சாமுண்டி` or the 1978 `பெரிய இடத்துப் பெண்` witness comparison first.
