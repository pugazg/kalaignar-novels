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

Canonical / verified records: **18 / 18 — scans 6–23 contiguous**.  
Whole-work Tamil audit: **PASS / COMPLETE**.  
Assembled Tamil: **PASS / COMPLETE — 1 / 1 section**.  
English batches: **4 / 4 REVIEWED / COMPLETE — scans 6–23 covered**.  
Section 16 was previously marked **PASS / English VERIFIED**, but Section 17 release preflight found a scan-17 source-fidelity blocker; a narrow Section 16 corrective re-open is **NEXT**.  
Section 17 release-readiness: **NOT READY / correction required**.  
Unresolved historical glyphs / canonical source readings: **0 / 0**.

## Printed-page behaviour

- scan 6 is unnumbered; no printed page 1 is inferred;
- scans 7–13 visibly print 2–8;
- scan 14 visibly prints 10, preserving the source jump **8 → 10**;
- scans 15–23 visibly print 11–19;
- no synthetic printed page 9 is created.

The number jump does not create a source gap: scan 13 ends `ஊற்றெடுத்துக் கிளம்பிவரும்` and scan 14 begins `அருவி!`.

## Established joins

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

Scan 23 is the final physical page and contains no explicit `முற்றும்`.

## Reading layers

- Tamil: `../sections/01-arumbu.md` — **PASSED / COMPLETE**;
- English: `../translations/en/sections/01-arumbu.md` — full scan coverage exists, but release closure is blocked pending the documented scan-17 correction;
- release preflight record: `../translations/en/RELEASE_REPORT.md`.

## Release-gate blocker

Canonical scan 17 reads `எனக்குப் பொய் அம்மா வேணும்!`, while current English inserts `don't` in “I don't want a fake Amma!”. The canonical/source affirmative must not be silently normalized. See `../translations/en/RELEASE_REPORT.md`.

## Exact next activity

Perform the **narrow Section 16 corrective re-open for scan 17 only**, synchronize English/review controls, and stop. Then rerun Section 17 release-readiness before beginning another component work.
