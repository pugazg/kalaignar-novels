# Page Map — அரும்பு

Source physical span: **scans 6–23** of the 92-scan 1978 compilation.

| Physical scan | Printed page | Canonical record | State |
|---:|:---:|---|---|
| 6 | null — not visibly printed | `../pages/0006-arumbu-01.md` | **VERIFIED — T1+T2+T3 PASS** |
| 7 | 2 | `../pages/0007-arumbu-02.md` | **VERIFIED — T1+T2+T3 PASS** |
| 8 | 3 | `../pages/0008-arumbu-03.md` | **VERIFIED — T1+T2+T3 PASS** |
| 9 | 4 | `../pages/0009-arumbu-04.md` | **VERIFIED — T1+T2+T3 PASS** |
| 10 | 5 | `../pages/0010-arumbu-05.md` | **VERIFIED — T1+T2+T3 PASS** |
| 11 | 6 | `../pages/0011-arumbu-06.md` | **VERIFIED — T1+T2+T3 PASS** |
| 12 | 7 | `../pages/0012-arumbu-07.md` | **VERIFIED — T1+T2+T3 PASS** |
| 13 | 8 | `../pages/0013-arumbu-08.md` | **VERIFIED — T1+T2+T3 PASS** |
| 14 | 10 | `../pages/0014-arumbu-10.md` | **VERIFIED — T1+T2+T3 PASS** |
| 15 | 11 | `../pages/0015-arumbu-11.md` | **VERIFIED — T1+T2+T3 PASS** |
| 16 | 12 | `../pages/0016-arumbu-12.md` | **VERIFIED — T1+T2+T3 PASS** |
| 17 | 13 | `../pages/0017-arumbu-13.md` | **VERIFIED — T1+T2+T3 PASS** |
| 18 | 14 | `../pages/0018-arumbu-14.md` | **VERIFIED — T1+T2+T3 PASS** |
| 19 | 15 | `../pages/0019-arumbu-15.md` | **VERIFIED — T1+T2+T3 PASS** |
| 20 | 16 | `../pages/0020-arumbu-16.md` | **VERIFIED — T1+T2+T3 PASS** |
| 21 | 17 | `../pages/0021-arumbu-17.md` | **VERIFIED — T1+T2+T3 PASS** |
| 22 | 18 | `../pages/0022-arumbu-18.md` | **VERIFIED — T1+T2+T3 PASS** |
| 23 | 19 | `../pages/0023-arumbu-19.md` | **VERIFIED — T1+T2+T3 PASS** |

Canonical page records: **18 / 18 — scans 6–23**.  
Verified canonical records: **18 / 18 — scans 6–23 contiguous**.  
Whole-work Tamil audit: **PASS / COMPLETE**.  
Tamil source layer: **PASSED**.  
Assembled Tamil: **PASS / COMPLETE — 1 / 1 section (`../sections/01-arumbu.md`)**.  
English translation plan: **PASS / COMPLETE**.  
English prose: **NOT STARTED**.  
Next English checkpoint: **Batch 1 pilot — scans 6–10**.  
Unresolved historical glyphs: **0**.  
Unresolved source readings: **0**.

## Printed-page behaviour

- scan 6 is the opening page and has no clearly visible printed number; `null` is retained rather than inferring `1`;
- visible printed numbers run **2–8** on scans 7–13;
- scan 14 visibly prints **10**, producing a source-visible numbering jump **8 → 10**;
- scans 15–23 visibly print **11–19**;
- no synthetic printed page 9 is created.

The printed-number jump does not create a physical source-coverage gap: scan 13 ends `ஊற்றெடுத்துக் கிளம்பிவரும்` and scan 14 begins `அருவி!`, preserving direct narrative continuity.

## Closed source batches

- scans 6–10 — T1+T2+T3 PASS / VERIFIED;
- scans 11–15 — T1+T2+T3 PASS / VERIFIED;
- scans 16–20 — T1+T2+T3 PASS / VERIFIED;
- scans 21–23 — T1+T2+T3 PASS / VERIFIED.

Across the full component, T2 left **0 unresolved historical glyphs** and T3 left **0 unresolved source readings**.

Representative preserved page-level joins include:

- 7→8: `நடந்` → `தேறின.`;
- 8→9: `அபிநய` → `அசைவுகளை`;
- 9→10: `வைத்தியரை அழைத்து` → `வந்துவிடுகிறேன்”`;
- 11→12: `போய்` → `விட்டனர்.`;
- 13→14: `ஊற்றெடுத்துக் கிளம்பிவரும்` → `அருவி!`;
- 15→16: `செல்லக்` → `குழந்தையை—...`;
- 16→17: `அவர்களைக்-` → `கவனிக்கிறான்.`;
- 17→18: `குமார்` → `பள்ளிக்கூடத்தில்...`;
- 18→19: `செலவா` → `யிற்று.`;
- 19→20: `கடிந்துகொண்` → `டிருக்கிறாள்.`;
- 20→21: `அவனது அம்மா படம்!` → `அதை எடுத்து...`;
- 21→22: `அப்பா பாப்பாவை நினைத்து` → `அழுதுகொண்டே யிருக்கிறாரே!`;
- 22→23: completed sentence → new paragraph `அவளையறியாமல்,...`.

Scan 23 is the final physical page of this component and contains no explicit `முற்றும்`.

## Assembled reading layer

Section 13 assembly is complete:

- `../sections/README.md` records derivation and verification;
- `../sections/01-arumbu.md` covers scans **6–23** in one continuous section;
- all cross-page joins used in the reading layer remain reversible through HTML source comments;
- no source-backed chapter division or printed page 9 was invented;
- canonical page records remain unchanged.

## English planning layer

Section 14 planning is complete under `../translations/en/`:

- `TRANSLATION_PLAN.md` — **PASS / COMPLETE**;
- working English title — **The Bud**;
- planned final English structure — one section;
- controlled batches — **6–10**, **11–15**, **16–20**, **21–23**;
- no English prose has yet been translated.

## Exact next activity

Execute **English Batch 1 pilot — scans 6–10 only**, source-check against canonical Tamil, update English controls, synchronize project controls, commit, and stop before Batch 2 or another compilation component.
