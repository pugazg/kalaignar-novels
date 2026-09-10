# Next Chat Prompt — அரும்பு / Section 16 whole-work bilingual review

Continue in `pugazg/kalaignar-novels`, branch `main`, active source `collections/arumbu-1978/`, active work `works/arumbu/`. **LIVE MAIN IS AUTHORITATIVE.**

## Controlling source

`TVA_BOK_0064361_அரும்பு.pdf`

- SHA-256 `04a3013e1f58a1800867acc5d2f159976c47994a64478036e6fe0201edf120bc`
- **117,270,339 bytes**
- **92 physical scans**
- image-only
- தமிழ்க்கனி பதிப்பகம், சென்னை-28
- முதற் பதிப்பு 1978
- source PDF must **not** be committed.

## Durable compilation structure

- scans 1–5 — collection front matter;
- scans 6–23 — `அரும்பு` — **TAMIL SOURCE + ASSEMBLED TAMIL + ENGLISH PLAN PASSED; ENGLISH BATCHES 1–4 REVIEWED; SECTION 16 NEXT**;
- scans 24–48 — `சாரப்பள்ளம் சாமுண்டி` — queued;
- scans 49–74 — `பெரிய இடத்துப் பெண்` — additional witness only;
- scans 75–90 — `நடுத்தெரு நாராயணி` — queued;
- scans 91–92 — publisher catalogue/back cover.

## Mandatory startup

Read before Section 16 work:

1. `NOVEL_PROCESSING_GUIDE.md`, especially Section 16;
2. root `HANDOVER.md`;
3. `works/arumbu/README.md`;
4. `works/arumbu/audit.md`;
5. `works/arumbu/translations/en/TRANSLATION_PLAN.md`;
6. `works/arumbu/translations/en/README.md`;
7. `works/arumbu/translations/en/PROGRESS.md`;
8. `works/arumbu/translations/en/GLOSSARY.md`;
9. `works/arumbu/translations/en/BATCH_03_REVIEW.md`;
10. `works/arumbu/translations/en/BATCH_04_REVIEW.md`;
11. complete English `works/arumbu/translations/en/sections/01-arumbu.md`;
12. all canonical Tamil page records `works/arumbu/pages/0006-arumbu-01.md` through `0023-arumbu-19.md`.

Do not reopen closed Tamil work or reviewed English batches unless the whole-work review identifies a concrete mismatch that must be documented and corrected.

## Durable `அரும்பு` state

- canonical Tamil records: **18 / 18 VERIFIED**;
- all T1/T2/T3 page-level gates: **PASS / COMPLETE**;
- whole-work Tamil audit: **PASS / COMPLETE**;
- assembled Tamil: **PASS / COMPLETE — 1 / 1 section**;
- English translation plan: **PASS / COMPLETE**;
- Batch 1 scans **6–10**: **REVIEWED / COMPLETE**;
- Batch 2 scans **11–15**: **REVIEWED / COMPLETE**;
- Batch 3 scans **16–20**: **REVIEWED / COMPLETE**;
- Batch 4 scans **21–23**: **REVIEWED / COMPLETE**;
- English coverage: **18 / 18 source scans — scans 6–23**;
- whole-work English: **NOT YET VERIFIED**;
- Section 16 whole-work bilingual review: **NEXT**.

## Locked final-batch source decisions

Preserve these unless the review finds an actual source/translation mismatch:

- scan 22 `பேசினேன்` → **I spoke**, preserving source first-person;
- scan 23 `அம்மனார்` → **Ammanar**, not normalized to Ammanur;
- scan 23 `இனி:......` → **from now on:......**, retaining the colon-plus-six-dot form;
- scan 23 has no explicit `முற்றும்` → no **The End**.

## Exact next activity — Section 16 only

Create `works/arumbu/translations/en/TRANSLATION_REVIEW.md` and perform an independent whole-work bilingual review of scans **6–23**. Explicitly check:

- complete coverage and source order;
- no duplicate source span;
- no material omission;
- no source-like addition;
- speaker attribution and actor agency;
- recurring names/titles/terminology;
- political/religious/social rhetorical force;
- all established cross-page joins;
- one-section structural identity;
- recurring bud/leaf imagery through the ending;
- protected source oddities;
- final-page punctuation and absence of an unprinted ending marker;
- scan/page provenance.

If and only if all checks pass, mark whole-work English **VERIFIED**, synchronize translation/work/root controls, commit, and stop.

Do **not** perform Section 17 release-readiness, start `சாரப்பள்ளம் சாமுண்டி`, or begin the 1978 `பெரிய இடத்துப் பெண்` witness comparison in the same checkpoint.
