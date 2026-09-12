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
- assembled Tamil: **NOT STARTED / NEXT**.

T1 closure: `works/nadutheru-narayani/T1_COMPLETION.md`.

T2 is **PASS / COMPLETE across scans 75–90**: **40 source-proven corrections / 0 unresolved readings / 16 of 16 pages verified**. The independent whole-work Tamil source audit has also **PASSED** with **0 residual canonical corrections / 0 unresolved historical glyphs / 0 unresolved source readings**. All 11 recorded cross-scan continuities, scan80's printed 78–79 illustrated spread, scan90's source-visible ending, protected source oddities, and source-PDF exclusion were reconfirmed.

Whole-work audit record: `works/nadutheru-narayani/FULL_TAMIL_SOURCE_AUDIT.md`.

## Exact next activity

Create the **assembled Tamil reading layer** from the audited canonical pages.

Requirements:

1. derive only from `works/nadutheru-narayani/pages/` — do not re-transcribe from the PDF;
2. use one continuous section unless the source itself supplies a genuine structural split;
3. preserve reversible source provenance for scans **75–90**;
4. join only the confirmed page-boundary continuities already recorded in `indexes/page-map.md`;
5. keep scan80's illustration out of prose while preserving its page provenance;
6. preserve all source spelling, punctuation, dialect, rhetoric and protected oddities;
7. preserve scan90's work ending and terminal rule;
8. create/update `sections/README.md` and the assembled Tamil section, run a consistency gate against all 16 canonical records, synchronize controls, commit, and stop before English translation planning.

Do not begin English translation yet.
