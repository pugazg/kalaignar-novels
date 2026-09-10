# Next Chat Prompt — அரும்பு / Section 17 release-readiness

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
- scans 6–23 — `அரும்பு` — **TAMIL + ASSEMBLED TAMIL PASSED / ENGLISH VERIFIED / SECTION 17 NEXT**;
- scans 24–48 — `சாரப்பள்ளம் சாமுண்டி` — queued;
- scans 49–74 — `பெரிய இடத்துப் பெண்` — additional witness only;
- scans 75–90 — `நடுத்தெரு நாராயணி` — queued;
- scans 91–92 — publisher catalogue/back cover.

## Mandatory startup

Read before Section 17:

1. `NOVEL_PROCESSING_GUIDE.md`, especially Section 17;
2. root `HANDOVER.md`;
3. `works/arumbu/README.md`;
4. `works/arumbu/audit.md`;
5. `works/arumbu/sections/README.md`;
6. `works/arumbu/translations/en/TRANSLATION_PLAN.md`;
7. `works/arumbu/translations/en/README.md`;
8. `works/arumbu/translations/en/PROGRESS.md`;
9. `works/arumbu/translations/en/GLOSSARY.md`;
10. `works/arumbu/translations/en/TRANSLATION_REVIEW.md`;
11. complete English `works/arumbu/translations/en/sections/01-arumbu.md`;
12. page map / metadata controls needed to verify inventory and navigation.

Do not reopen closed Tamil work or verified English unless genuine source evidence or a concrete release-gate inconsistency requires correction.

## Durable `அரும்பு` state

- canonical Tamil records: **18 / 18 VERIFIED**;
- all T1/T2/T3 source gates: **PASS / COMPLETE**;
- whole-work Tamil audit: **PASS / COMPLETE**;
- assembled Tamil: **PASS / COMPLETE — 1 / 1 section**;
- English translation plan: **PASS / COMPLETE**;
- English Batches 1–4: **4 / 4 REVIEWED / COMPLETE**;
- English coverage: **18 / 18 scans — scans 6–23**;
- Section 16 whole-work bilingual review: **PASS / COMPLETE**;
- whole-work English: **VERIFIED**;
- Section 16 corrections: **3 English-only**;
- material omissions / source-like additions / unresolved items after review: **0 / 0 / 0**;
- canonical Tamil changes during Section 16: **0**;
- Section 17 release-readiness: **NEXT**.

## Section 16 protected final state

- scan 22 `பேசினேன்` → **I spoke**;
- scan 23 `அம்மனார்` → **Ammanar**, not Ammanur;
- final `இனி:......` → **from now on:......**;
- no source `முற்றும்` → no **The End**;
- the central bud/leaf motif remains connected through the final sentence;
- source scan/page provenance remains reversible;
- no source-backed chapter divisions exist.

## Exact next activity — Section 17 only

Create `works/arumbu/translations/en/RELEASE_REPORT.md` and execute the release-readiness gate required by `NOVEL_PROCESSING_GUIDE.md`:

- verify work identity and 1978 source-edition identity;
- verify Tamil canonical inventory **18/18** and assembled Tamil **1/1**;
- verify English section inventory and Section 16 **PASS / VERIFIED** state;
- check reader-facing navigation and links;
- reconfirm authority hierarchy and one-work/one-section structural identity;
- document source oddities/pagination anomaly;
- confirm canonical Tamil was not changed during the release pass;
- confirm the source PDF is not committed;
- record any non-blocking editorial limitations;
- issue a final **release-ready / not-ready archival/editorial verdict**;
- synchronize controls, commit, and stop.

Do **not** begin `சாரப்பள்ளம் சாமுண்டி` or the 1978 `பெரிய இடத்துப் பெண்` witness comparison in the same checkpoint.