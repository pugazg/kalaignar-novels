# Assembled Tamil Reading Layer — பாயும்புலி பண்டாரக வன்னியன்

This `sections/` directory is the maintained source-faithful Tamil reading layer derived from verified canonical `../pages/` records.

Canonical `pages/` remain authoritative if any conflict is ever discovered.

## Closed Parts represented

### Part001 — PASS / CLOSED / FROZEN

- physical coverage — **scans1–30**
- canonical pages represented — **30/30**
- assembled files — **8/8 VERIFIED**
- validation — `../PART_001_ASSEMBLED_TAMIL_VALIDATION.md`

Part001 section files `00-*.md` through `07-*.md` are frozen.

### Part002 — PASS / CLOSED

- physical coverage — **scans31–60**
- canonical pages represented — **30/30**
- assembled files — **5/5 VERIFIED**
- omitted / duplicated canonical pages — **0 / 0**
- unsupported body insertion — **0**
- audit-note leakage — **0**
- Part003 text leakage — **0**
- canonical Part002 page mutations caused by assembly — **0**
- frozen Part001 assembled-file mutations — **0**
- validation — `../PART_002_ASSEMBLED_TAMIL_VALIDATION.md`

## Section inventory

| Order | Part | File | Source scans | Source structure | Status |
|---:|---:|---|---:|---|---|
| 0 | 001 | `00-front-matter.md` | 1–5 | cover / title / publisher / bibliographic front matter | **VERIFIED** |
| 1 | 001 | `01-anindurai.md` | 6–9 | `அணிந்துரை` | **VERIFIED** |
| 2 | 001 | `02-pathippurai.md` | 10 | `பதிப்புரை` | **VERIFIED** |
| 3 | 001 | `03-epigraph.md` | 11 | epigraph / verse | **VERIFIED** |
| 4 | 001 | `04-title-divider.md` | 12 | illustrated title divider | **VERIFIED** |
| 5 | 001 | `05-thorana-vayil.md` | 13–20 | `தோரண வாயில்` | **VERIFIED** |
| 6 | 001 | `06-oru-iragasiyak-kaditham.md` | 21–27 | `ஒரு இரகசியக் கடிதம்!` | **VERIFIED** |
| 7 | 001 | `07-vazhiyil-kanda-vayothigar.md` | 28–30 | `வழியில் கண்ட வயோதிகர்!` — Part001 terminal continuation | **VERIFIED** |
| 8 | 002 | `08-vazhiyil-kanda-vayothigar-part002.md` | 31–34 | chapter 3 continuation `வழியில் கண்ட வயோதிகர்!` | **VERIFIED** |
| 9 | 002 | `09-kuruvichchi-naachchiyar.md` | 35–41 | `குருவிச்சி நாச்சியார்` | **VERIFIED** |
| 10 | 002 | `10-naalu-kaal-mandapaththil.md` | 42–49 | `நாலு கால் மண்டபத்தில்!` | **VERIFIED** |
| 11 | 002 | `11-kandiyin-vaarisup-potti.md` | 50–56 | `கண்டியின் வாரிசுப் போட்டி!` | **VERIFIED** |
| 12 | 002 | `12-theevukkul-theeyavargal.md` | 57–60 | `தீவுக்குள் தீயவர்கள்!` | **VERIFIED** |

## Assembly rules

1. Source text comes only from each canonical page's verified `## Source transcription` block.
2. Preserve source spelling, punctuation, paragraph/dialogue order, displayed text and historical forms.
3. Preserve physical-page provenance with non-rendering HTML boundary comments.
4. Exclude review/audit notes, page YAML, page furniture, copy marks and visual-only matter already classified non-body.
5. Join a physical split word only where the closed canonical evidence explicitly establishes the join.
6. Canonical `pages/` always govern; this reading layer never authorizes silent correction of canonical Tamil.
7. Do not cross a Part boundary by importing adjacent-Part body text merely to make a section self-contained.

## Part002 boundary safeguards

- incoming **30→31 — GENUINE CONTINUATION / AUDITED**;
- Part001 terminal body text remains only in frozen Part001 section 07;
- Part002 scan31 begins from its own verified canonical source-transcription block;
- outgoing **60→61 — CLEAN / AUDITED**;
- scan61 / Part003 text is not imported.

## Part002 special structural cases

- scan32→33 split word is rendered continuously as `சுந்தரலிங்கத்தைப்` with an inline non-rendering provenance marker;
- scan49's large blank lower field remains visual structure and creates no invented text;
- scan59 remains one physical illustrated spread containing printed pages **48–49**; both verified textual panels and their printed-page order are retained, while the illustration remains visual/non-body matter.

## Downstream state

Part001 remains **FINAL CLOSED / FROZEN**.

Part002:
- Tamil archival-ready — **PASS / CLOSED**
- assembled Tamil — **PASS / CLOSED — 5/5 VERIFIED**
- English planning/setup — **COMPLETE / PASS**
- English translated/source-checked files — **1/5**
- E5 — **SOURCE-CHECKED / COMPLETE**
- English next — **E6 / section09 / scans35–41**
- release/readiness — **BLOCKED**
- final Part002 closure — **BLOCKED**
- Part003 transcription — **BLOCKED / NOT ACTIVE**

## Exact next activity

Use the PASSED Part002 assembled section 09 as the normal reading authority for **English E6 / scans35–41**, with canonical `../pages/` controlling any discrepancy.

Do not alter this verified Tamil reading layer merely to smooth English.
