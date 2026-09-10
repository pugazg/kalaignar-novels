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

1. `அரும்பு` — scans **6–23** — **TAMIL/ASSEMBLED TAMIL PASSED; ENGLISH VERIFIED; SECTION 17 RELEASE-READINESS NEXT**.
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
- English coverage: **18 / 18 scans — scans 6–23**;
- Section 16 whole-work bilingual review: **PASS / COMPLETE**;
- whole-work English: **VERIFIED**;
- Section 16 English-only corrections: **3**;
- material omissions / source-like additions / unresolved translation items after review: **0 / 0 / 0**;
- canonical Tamil changes during Section 16: **0**;
- Section 17 release-readiness: **NEXT**.

## Durable source / translation findings

- scan 6 unnumbered; scans 7–13 print 2–8; scan 14 prints 10; scans 15–23 print 11–19; no page 9 invented;
- scan 23 is final and has no explicit `முற்றும்`;
- scan 22 `பேசினேன்` → English **I spoke** while canonical Tamil remains unchanged;
- scan 23 `அம்மனார்` → **Ammanar**, not Ammanur;
- final `இனி:......` → **from now on:......**;
- no source-backed chapters; English remains one continuous section;
- canonical `pages/` remain final textual authority.

Section 16 review is recorded at `works/arumbu/translations/en/TRANSLATION_REVIEW.md`. It independently compared the complete English against all 18 canonical Tamil records and made three English-only corrections: `safe and sound` at scan 15→16, explicit Kumar agency at scan 21→22, and `The feeling of motherhood belongs to womankind!` on scan 23.

## Exact next activity

Execute **Section 17 release-readiness for `அரும்பு` only**:

- read `NOVEL_PROCESSING_GUIDE.md` Section 17, this handover, work/audit/translation controls and `TRANSLATION_REVIEW.md`;
- create `works/arumbu/translations/en/RELEASE_REPORT.md`;
- verify source/work identity, Tamil page inventory, assembled Tamil inventory, English section inventory, Tamil audit and bilingual-review results, reader-facing navigation, authority hierarchy, one-work/one-section identity, documented source oddities, canonical-Tamil immutability during release pass, source-PDF exclusion, and any non-blocking editorial limitations;
- record a final **release-ready / not-ready** archival/editorial verdict;
- synchronize controls, commit, and stop.

Do **not** begin `சாரப்பள்ளம் சாமுண்டி` or the 1978 `பெரிய இடத்துப் பெண்` witness comparison in the same checkpoint.