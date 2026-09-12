# Next Chat Prompt — நடுத்தெரு நாராயணி / whole-work Tamil source audit

Continue directly in `pugazg/kalaignar-novels`, branch `main`. **LIVE MAIN IS AUTHORITATIVE.**

## Controlling source

`TVA_BOK_0064361_அரும்பு.pdf`

- SHA-256: `04a3013e1f58a1800867acc5d2f159976c47994a64478036e6fe0201edf120bc`
- edition: **முதற் பதிப்பு — 1978**
- work span: **75–90 / 16 physical scans**
- source PDF committed: **No**

## Durable state

- canonical page records: **16 / 16**;
- T1: **PASS / COMPLETE**;
- T2 scans 75–90: **PASS / COMPLETE**;
- verified pages: **16 / 16**;
- needs-review pages: **0 / 16**;
- cumulative T2 source-proven corrections: **40**;
- unresolved T2 readings: **0**;
- assembled Tamil / English: **NOT STARTED**;
- Tamil source audit: **NEXT / NOT YET PASSED**.

T2 batch 3 — scans **85–90**:

- **6 / 6 verified**;
- **12 source-proven corrections / 0 unresolved**;
- scan85: `பேச்சு வரவேயில்லை` → `பேச வாயெழவில்லை`; `காமன` → `காமனை`; `தூபம் போட்ட ஆரம்பித்தான்` → `தூபம் போட ஆரம்பித்தான்`;
- scan86: `இல்லைன்னா` → `இல்லேன்னு`; source-confirmed `தல தப்பாதடி, தல தப்பாது` replaces T1 `தலை...` and is a genuine short form, not a historical-`லை` misread;
- scan87: `புரிந்துகொண்டேன்` → `புரிந்து கொண்டேன்`;
- scan88: no correction; `ஒரு கடாரம் பத்திருக்கு` **CONFIRMED / RETAINED**;
- scan89: six corrections, including `பகற் கொள்ளைக்காரனைப்`, `டுமீல்! டுமீல்!`, and source-resolved `அவர்கள் அய்யரை வீரராக்கிவிட்டார்கள்`;
- scan90: no correction; work ending and terminal rule confirmed;
- all 13 historical-glyph-sensitive families were explicitly considered on every page.

The page map has also been repaired/synchronized so scans **75–90** all show **verified — T2 pass**.

## Exact next activity

Perform the **whole-work Tamil source audit across scans 75–90**.

Independently verify:

1. all **16 physical scans** are represented exactly once and in source order;
2. printed-page mapping: scan75 unnumbered; scans76–79 = 74–77; scan80 = printed 78–79 two-page illustrated spread; scans81–90 = 80–89;
3. every canonical page against controlling source pixels, with special attention to all **40 T2 corrections**;
4. all confirmed joins: 76→77, 78→79, 79→80, 81→82, 83→84, 84→85, 85→86, 86→87, 87→88, 88→89, 89→90;
5. protected source oddities including scan81 `பூணால் வலையில்`, scan82 `வைப்பு / ஒய்ப் / வைப்`, scan84 `பதி சொல் தட்டாத`, scan88 `ஒரு கடாரம் பத்திருக்கு`, scan89 `வீரராக்கிவிட்டார்கள்`;
6. all 13 historical-glyph-sensitive families, with **0 silent normalization**;
7. scan80 illustration handling and scan90 narrative ending / terminal rule;
8. metadata, README, page-map and audit controls against the canonical layer;
9. source PDF remains excluded from the repository.

If a residual mismatch is positively source-proven, correct it and record it. Create a durable whole-work audit record (following the repository precedent, e.g. `FULL_TAMIL_SOURCE_AUDIT.md`), synchronize controls, commit, and stop before assembled Tamil or English.
