# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- **Live main is authoritative.**
- Active work: **`works/nadutheru-narayani/`**
- Prior `பெரிய இடத்துப் பெண்` witness comparison: **PASS / COMPLETE / CLOSED**

## Active source — நடுத்தெரு நாராயணி

`TVA_BOK_0064361_அரும்பு.pdf`

- SHA-256: `04a3013e1f58a1800867acc5d2f159976c47994a64478036e6fe0201edf120bc`
- edition: **முதற் பதிப்பு — 1978**
- publisher: **தமிழ்க்கனி பதிப்பகம், சென்னை-28**
- work span: **75–90 / 16 physical scans**
- source PDF committed: **No**

## Durable Tamil state

- source intake: **COMPLETE**;
- component boundary: **CONFIRMED**;
- canonical page records: **16 / 16**;
- T1 transcription: **PASS / COMPLETE — scans 75–90**;
- verified pages: **16 / 16**;
- current statuses: **16 verified / 0 needs-review**;
- scan80 is a **two-page illustrated spread, printed 78–79**;
- scan90 is the source-visible work ending;
- T2 / historical-glyph source-fidelity review: **PASS / COMPLETE — scans 75–90**;
- whole-work Tamil source audit: **PASS / COMPLETE — 0 residual canonical corrections / 0 unresolved**;
- Tamil source layer: **PASS / COMPLETE**;
- assembled Tamil: **PASS / COMPLETE — 1 / 1 section**;
- assembled-vs-canonical consistency: **PASS — 16 / 16 scans / 11 joins / 0 mutation**;
- English translation plan: **PASS / COMPLETE**;
- English coverage: **0 / 16 scans — NOT STARTED**;
- English Batch 1 pilot: **PLANNED / NEXT — scans 75–79**.

T1 closure: `works/nadutheru-narayani/T1_COMPLETION.md`.

T2 is **PASS / COMPLETE across scans 75–90**: **40 source-proven corrections / 0 unresolved readings / 16 of 16 pages verified**. The independent whole-work Tamil source audit has also **PASSED** with **0 residual canonical corrections / 0 unresolved historical glyphs / 0 unresolved source readings**. All 11 recorded cross-scan continuities, scan80's printed 78–79 illustrated spread, scan90's source-visible ending, protected source oddities, and source-PDF exclusion were reconfirmed.

Whole-work audit record: `works/nadutheru-narayani/FULL_TAMIL_SOURCE_AUDIT.md`.

Assembled Tamil records:

- `works/nadutheru-narayani/sections/README.md`;
- `works/nadutheru-narayani/sections/01-nadutheru-narayani.md`.

English planning/control records:

- `works/nadutheru-narayani/translations/en/TRANSLATION_PLAN.md`;
- `works/nadutheru-narayani/translations/en/README.md`;
- `works/nadutheru-narayani/translations/en/PROGRESS.md`;
- `works/nadutheru-narayani/translations/en/GLOSSARY.md`.

## Exact next activity

Process **English Batch 1 pilot — scans 75–79 only**.

Requirements:

1. create `translations/en/sections/01-nadutheru-narayani.md`;
2. translate only canonical Tamil from scans **75–79**;
3. preserve scan provenance and verified joins within the batch;
4. do not import scan80 English prose; scan79→80 remains an open cross-batch continuity;
5. apply the locked title/name/caste/religious/colloquial policies;
6. lock pilot terminology decisions in `GLOSSARY.md`;
7. source-check the English back against canonical Tamil for omissions, additions, speaker/agency drift, rhetoric and boundary handling;
8. mark Batch 1 reviewed only if the source-check passes;
9. synchronize controls, commit, and stop before Batch 2.

Do not alter canonical Tamil unless genuinely new source evidence appears.
