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
| 18 | 004 | `18-adhikaari-vazhangiya-aalosanai-part004.md` | 91–94 | chapter 11 continuation `அதிகாரி வழங்கிய ஆலோசனை` | **VERIFIED** |
| 19 | 004 | `19-mannippu-yaar-yaaridam.md` | 95–102 | `மன்னிப்பு யார்? யாரிடம்?` | **VERIFIED** |
| 20 | 004 | `20-maana-maraippu-marakkalaamaa.md` | 103–109 | `மான மறைப்பு மறக்கலாமா?` | **VERIFIED** |
| 21 | 004 | `21-aval-nadantha-paathai.md` | 110–115 | `அவள் நடந்த பாதை` | **VERIFIED** |
| 22 | 004 | `22-iruvar-ullam.md` | 116–120 | `இருவர் உள்ளம்` | **VERIFIED** |

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

### Part004 — PASS / CLOSED

- physical coverage — **scans91–120**
- canonical pages represented — **30/30**
- assembled files — **5/5 VERIFIED**
- omitted / duplicated canonical pages — **0 / 0**
- unsupported body insertion — **0**
- audit-note leakage — **0**
- Part005 text leakage — **0**
- canonical Part004 page mutations caused by assembly — **0**
- frozen Part001–Part003 assembled-file mutations — **0**
- validation — `../PART_004_ASSEMBLED_TAMIL_VALIDATION.md`

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

## Part004 boundary safeguards

- incoming **90→91 — GENUINE CONTINUATION / AUDITED**;
- no frozen Part003 body text is imported into Part004 section 18;
- outgoing **120→121 — GENUINE CONTINUATION / AUDITED**;
- scan120 remains terminal at `தனது காதல் விலை`; scan121 / Part005 body text is not imported.

## Part002 special structural cases

- scan32→33 split word is rendered continuously as `சுந்தரலிங்கத்தைப்` with an inline non-rendering provenance marker;
- scan49's large blank lower field remains visual structure and creates no invented text;
- scan59 remains one physical illustrated spread containing printed pages **48–49**; both verified textual panels and their printed-page order are retained, while the illustration remains visual/non-body matter.

## Part003 special structural cases

- scans64, 72, 79 and 87 retain no invented content for their intentional blank lower fields;
- scan71 copy-specific library stamp / handwriting remains excluded as non-body provenance;
- chapter-opening number/title material already present in verified canonical source-transcription blocks is retained;
- no Part003 literary illustration, photograph or caption requires separate readable-layer prose.

## Part004 special structural cases

- scans94, 102 and 109 retain no invented content for intentional blank lower fields;
- scan97 source-leading dash lineation remains readable body text;
- scan108 displayed letter closing/signature remains readable body text;
- scan113→114 split word is rendered continuously as `பிரச்சினையைப்` with an inline non-rendering provenance marker;
- chapter-opening number/title material already present in verified canonical source-transcription blocks is retained;
- no Part004 literary illustration, photograph or caption requires separate readable-layer prose.

## Part005 boundary safeguards

- incoming **120→121 — GENUINE CONTINUATION / AUDITED**;
- no frozen Part004 body text may be imported into the Part005 reading layer merely to complete the split word;
- outgoing **150→151 — GENUINE CONTINUATION / AUDITED**;
- scan150 remains terminal at `என்னுடன் வாழ வேண்டாம் என நான்`; Part006 scan151 body text must not be imported.

## Part005 special structural cases

- scan123 is a full-page colour illustration with no printed Tamil body text; assembly must not invent prose or a caption;
- scans128, 134 and 145 retain no invented content for intentional blank lower fields;
- scans130→131 preserve meaningful displayed verse lineation;
- scan140→141 preserves the verified lexical split `அரண்` + `மனையின்` while keeping canonical page provenance;
- chapter-opening number/title material already present in verified canonical source-transcription blocks is retained.

## Downstream state

Part001 — **FINAL CLOSED / FROZEN**.

Part002 — **FINAL CLOSED / FROZEN**; assembled Tamil remains **PASS / CLOSED — 5/5 VERIFIED**.

Part003 — **FINAL CLOSED / FROZEN**; assembled Tamil remains **PASS / CLOSED — 5/5 VERIFIED**.

Part004 — **FINAL CLOSED / FROZEN**; assembled Tamil remains **PASS / CLOSED — 5/5 VERIFIED**.

Part005:
- Tamil archival-ready — **PASS / CLOSED**
- canonical Tamil — **30/30 verified**
- visual fidelity — **30/30 verified**
- assembled Tamil — **NOT STARTED / NEXT GATE**
- canonical Part005 page mutations caused by archival-ready checkpoint — **0**
- Part006 canonical leakage — **0**
- expected reading-layer source structure — **7 section files / scans121–150**
- Part001–Part004 assembled files — **FROZEN / MUST NOT CHANGE**

## Exact next activity

Perform **Part005 assembled Tamil construction + audit**.

Build only from verified Part005 canonical `pages/` source-transcription blocks. Preserve both audited Part005 boundaries, exclude scan123 illustration-only matter from literary body, keep frozen Part001–Part004 assembled files unchanged, and do not import Part006 body text.
