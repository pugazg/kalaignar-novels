# Next Chat Prompt — நடுத்தெரு நாராயணி / assembled Tamil reading layer

Continue directly in `pugazg/kalaignar-novels`, branch `main`. **LIVE MAIN IS AUTHORITATIVE.**

## Controlling source

`TVA_BOK_0064361_அரும்பு.pdf`

- SHA-256: `04a3013e1f58a1800867acc5d2f159976c47994a64478036e6fe0201edf120bc`
- edition: **முதற் பதிப்பு — 1978**
- work span: **75–90 / 16 physical scans**
- source PDF committed: **No**

## Durable Tamil state

- canonical page records: **16 / 16**;
- T1: **PASS / COMPLETE**;
- T2: **PASS / COMPLETE — scans 75–90**;
- canonical verified pages: **16 / 16**;
- cumulative source-proven T2 corrections: **40**;
- unresolved T2 readings: **0**;
- whole-work Tamil source audit: **PASS / COMPLETE**;
- whole-work residual canonical corrections: **0**;
- unresolved historical glyphs / source readings: **0 / 0**;
- Tamil source layer: **PASS / COMPLETE**;
- assembled Tamil: **NOT STARTED / NEXT**;
- English: **NOT STARTED / BLOCKED until assembled Tamil consistency passes**.

Whole-work audit record: `works/nadutheru-narayani/FULL_TAMIL_SOURCE_AUDIT.md`.

The whole-work audit independently reconciled all **16 physical scans**, confirmed the scan/printed-page inventory, all **11 recorded cross-scan continuities**, the cumulative **40 T2 corrections**, all protected source oddities, scan80's printed **78–79** illustrated spread, scan90's work ending / terminal rule, and source-PDF exclusion. No residual canonical Tamil mismatch was found.

## Exact next activity

Build the **assembled Tamil reading layer**.

Use:

- `works/nadutheru-narayani/pages/` as the only textual authority;
- `works/nadutheru-narayani/indexes/page-map.md` for the confirmed joins and provenance;
- one continuous section unless source evidence requires otherwise.

Create:

- `works/nadutheru-narayani/sections/README.md`;
- `works/nadutheru-narayani/sections/01-nadutheru-narayani.md`.

Requirements:

1. include all source narrative from scans **75–90** exactly once and in order;
2. retain reversible scan/printed-page provenance markers;
3. join only the confirmed split fragments recorded in `indexes/page-map.md`;
4. do **not** convert scan80's illustration into prose;
5. preserve source forms including `பூணால் வலையில்`, `வைப்பு / ஒய்ப் / வைப்`, `பதி சொல் தட்டாத`, `தல தப்பாதடி, தல தப்பாது`, `ஒரு கடாரம் பத்திருக்கு`, `பகற் கொள்ளைக்காரனைப்`, `டுமீல்! டுமீல்!`, and `அவர்கள் அய்யரை வீரராக்கிவிட்டார்கள்`;
6. preserve scan90's terminal horizontal rule / work-ending identity;
7. run an assembled-vs-canonical consistency check for **16/16 scans**, update README/audit/handover controls, commit, and stop before English translation planning.

Do not modify the canonical page wording unless a genuinely new source-fidelity issue is discovered.