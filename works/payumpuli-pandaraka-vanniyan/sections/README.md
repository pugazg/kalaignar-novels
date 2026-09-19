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
| 13 | 003 | `13-theevukkul-theeyavargal-part003.md` | 61–64 | chapter 7 continuation `தீவுக்குள் தீயவர்கள்!` | **VERIFIED** |
| 14 | 003 | `14-kaakkai-vanniyan.md` | 65–72 | `காக்கை வன்னியன்!` | **VERIFIED** |
| 15 | 003 | `15-muthu-maaligai.md` | 73–79 | `முத்து மாளிகை!` | **VERIFIED** |
| 16 | 003 | `16-silandhi-valaiyo-siriya-poochchiyo.md` | 80–87 | `சிலந்தி வலையோ? சிறிய பூச்சியோ?` | **VERIFIED** |
| 17 | 003 | `17-adhikaari-vazhangiya-aalosanai.md` | 88–90 | `அதிகாரி வழங்கிய ஆலோசனை` | **VERIFIED** |

### Part003 — PASS / CLOSED

- physical coverage — **scans61–90**
- canonical pages represented — **30/30**
- assembled files — **5/5 VERIFIED**
- omitted / duplicated canonical pages — **0 / 0**
- unsupported body insertion — **0**
- audit-note leakage — **0**
- Part004 text leakage — **0**
- canonical Part003 page mutations caused by assembly — **0**
- frozen Part001/Part002 assembled-file mutations — **0**
- validation — `../PART_003_ASSEMBLED_TAMIL_VALIDATION.md`

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
- outgoing **60→61 — CLEAN / AUDITED**.

## Part003 boundary safeguards

- incoming **60→61 — CLEAN / AUDITED**;
- no frozen Part002 body text is imported into Part003 section 13;
- outgoing **90→91 — GENUINE CONTINUATION / AUDITED**;
- scan90 remains terminal at `என்னைப்`; scan91 / Part004 body text is not imported.

## Part002 special structural cases

- scan32→33 split word is rendered continuously as `சுந்தரலிங்கத்தைப்` with an inline non-rendering provenance marker;
- scan49's large blank lower field remains visual structure and creates no invented text;
- scan59 remains one physical illustrated spread containing printed pages **48–49**; both verified textual panels and their printed-page order are retained, while the illustration remains visual/non-body matter.

## Part003 special structural cases

- scans64, 72, 79 and 87 retain no invented content for their intentional blank lower fields;
- scan71 copy-specific library stamp / handwriting remains excluded as non-body provenance;
- chapter-opening number/title material already present in verified canonical source-transcription blocks is retained;
- no Part003 literary illustration, photograph or caption requires separate readable-layer prose.

## Downstream state

Part001 — **FINAL CLOSED / FROZEN**.

Part002 — **FINAL CLOSED / FROZEN**; assembled Tamil remains **PASS / CLOSED — 5/5 VERIFIED**.

Part003:
- Tamil archival-ready — **PASS / CLOSED**
- assembled Tamil — **PASS / CLOSED — 5/5 VERIFIED**
- canonical scans represented — **30/30**
- English planning/setup — **COMPLETE / PASS**
- English translated/source-checked — **5/5**
- E10–E14 — **SOURCE-CHECKED / COMPLETE**
- unresolved English holds — **0**
- Part003 English glossary reconciliation — **RECONCILED / PASS**
- Part003 glossary-reconciliation English section edits — **0**
- Part003 English editorial review — **PASS / CLOSED**
- Part003 editorial English-only changes — **49**
- Part003 source-alignment corrections within editorial total — **2**
- Part003 unresolved editorial holds — **0**
- Part003 bilingual review — **PASS / CLOSED**
- Part003 bilingual English-only corrections — **2**
- Part003 unresolved bilingual holds — **0**
- Part003 release/readiness — **PASS / CLOSED**
- Part003 unresolved release/readiness blockers — **0**
- Part003 release-ready synchronization — **PASS / CLOSED**
- Part003 release-sync canonical/assembled/English body changes — **0**
- Part003 release-sync source-variant collapses — **0**
- Part003 final closure — **NEXT GATE / NOT STARTED**

- Part004 — **BLOCKED**

## Exact next activity

Create and verify **Part003 final closure** `PART_003_FINAL_CLOSURE.md`.

Do not begin Part004 transcription until final Part003 closure passes.
