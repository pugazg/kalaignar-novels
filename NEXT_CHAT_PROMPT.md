# NEXT CHAT PROMPT — பாயும்புலி பண்டாரக வன்னியன் / Part009 English translation planning/setup

Continue directly in `pugazg/kalaignar-novels`, branch `main`, active work `works/payumpuli-pandaraka-vanniyan/`. **LIVE MAIN IS AUTHORITATIVE.**

## Durable release state

Parts **001–008 are FINAL CLOSED / FROZEN**.

## Part009 closed Tamil state

- source — `TVA_BOK_0065744_பாயும்புலி_பண்டாரக_வன்னியன்_part_009_pages_241-270.pdf`
- source SHA-256 — `144aecae1ab4c2e72e9e7fae2260745cf0c0ff8fe0ae6e8119e9a6b220a9ffcf`
- scans — **241–270 / 30**
- printed pages — **233–262**
- canonical Tamil — **30/30 verified**
- visual fidelity — **30/30 verified**
- Tamil archival-ready — **PASS / CLOSED**
- assembled Tamil — **6/6 VERIFIED / CLOSED**
- assembled coverage — **30/30**
- omissions / duplicates — **0 / 0**
- unsupported Tamil body insertion — **0**
- audit-note leakage — **0**
- canonical page mutations caused by assembly — **0**
- frozen Part001–Part008 section mutations — **0**
- Part010 body leakage — **0**
- incoming 240→241 — **GENUINE CONTINUATION / AUDITED**
- outgoing 270→271 — **PENDING direct audit**
- unresolved Tamil / assembly blockers — **0**

## Maintained Part009 Tamil reading units

1. `sections/49-inaiyatra-inai-part009.md` — scans241–243 — chapter37 continuation/close;
2. `sections/50-narivaal-kunjam.md` — scans244–249;
3. `sections/51-thalaivanum-thalaiviyum.md` — scans250–255;
4. `sections/52-pasaik-kodi-adaiyaalam.md` — scans256–261;
5. `sections/53-thanikaimalai-aavesam.md` — scans262–266;
6. `sections/54-maraindha-maayam-ennavo.md` — scans267–270.

Durable validation:
- `PART_009_ASSEMBLED_TAMIL_VALIDATION.md`

## Exact activity

Perform **Part009 English translation planning/setup only**.

Requirements:
- inspect live `translations/en/` before allocating any Part009 English batch IDs;
- perform a collision check against all existing maintained English batches/files;
- determine the next contiguous six-batch sequence for the six Part009 Tamil reading units;
- create/update only the Part009 English planning controls:
  - `translations/en/PART_009_TRANSLATION_PLAN.md`
  - `translations/en/PART_009_GLOSSARY.md`
  - `translations/en/PART_009_PROGRESS.md`
- map each of the six Part009 Tamil sections to one planned English batch/file;
- establish source ranges, terminology/glossary obligations, fidelity rules and review sequence;
- preserve exact Tamil authority in canonical `pages/` and assembled `sections/`;
- keep Parts001–008 English body files frozen;
- keep outgoing **270→271 PENDING direct audit**; do not import Part010 content into Part009 English planning;
- **do not draft English literary prose in this setup gate**;
- canonical Tamil changes — **0**;
- assembled Tamil changes — **0**;
- frozen prior English body changes — **0**.

Stop after planning/setup is formally **COMPLETE / PASS** with collision-free batch allocation and **0 English prose drafted**.

Expected next gate: draft + source-check the first Part009 English batch only.
