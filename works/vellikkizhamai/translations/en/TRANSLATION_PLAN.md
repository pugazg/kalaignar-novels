# English Translation Plan — வெள்ளிக்கிழமை

## 1. Objective

Create a clear, source-bound English translation of **மு. கருணாநிதியின் `வெள்ளிக்கிழமை`** from the audited 1968 second-edition Tamil preserved in this repository.

Working English title:

**_Friday_**

`வெள்ளிக்கிழமை` remains the authoritative archival title. `_Friday_` is the working English reading title, not a replacement bibliographic title.

The translation must preserve the novel's narrative sequence, dialogue, emotional intensity, irony, social criticism, religious/caste language, repetitions, abrupt turns, source oddities and chapter structure without turning it into a modern adaptation.

---

## 2. Source-authority hierarchy

Translation follows this authority order:

1. **Controlling source scan** — `TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf`; ultimate authority if a Tamil reading ever has to be reopened.
2. **Canonical audited Tamil page records** — `../../pages/`; controlling repository text for exact wording, punctuation, names, source oddities and provenance.
3. **PASSED assembled Tamil chapters** — `../../sections/`; continuous reading layer and already-verified page-boundary joins.
4. **Metadata / audit / page map** — `../../metadata/source.md`, `../../audit.md`, `../../indexes/page-map.md`.
5. **English translation** — derived layer only.

Normal translation review works from the canonical audited Tamil `pages/` plus the PASSED `sections/` layer. If the English review reveals a possible Tamil transcription problem, stop translation at that point and reopen the scan; never silently correct Tamil inside English.

Do not translate from OCR, memory, an internet edition, a later edition or a normalized retelling.

---

## 3. English file structure

Final English reading structure mirrors the 23 verified Tamil chapters one-to-one:

```text
works/vellikkizhamai/translations/en/
  TRANSLATION_PLAN.md
  README.md
  PROGRESS.md
  GLOSSARY.md
  TRANSLATION_REVIEW.md
  RELEASE_REPORT.md
  sections/
    README.md
    01-chapter-01.md
    ...
    23-chapter-23.md
```

Each English chapter file is created only when that chapter is translated. Empty translation files must not be pre-created merely to make the inventory look complete.

---

## 4. Controlled batch plan

Use a small bounded workflow. Batch 1 is the mandatory single-chapter pilot; subsequent default batches cover at most three contiguous chapters. A larger batch requires explicit user authorization.

| Batch | Tamil chapters | Source coverage | English destinations | Status |
|---|---|---|---|---|
| **1 — pilot** | 1 | scans 4–12 | `sections/01-chapter-01.md` | **REVIEWED / COMPLETE** |
| **2** | 2–4 | scan 13 → scan 45 before centered `5` | `02`–`04` | **NEXT / NOT STARTED** |
| **3** | 5–7 | scan 45 after centered `5` → scan 68 before centered `8` | `05`–`07` | planned |
| **4** | 8–10 | scan 68 after centered `8` → scan 92 before centered `11` | `08`–`10` | planned |
| **5** | 11–13 | scan 92 after centered `11` → scan 115 before centered `14` | `11`–`13` | planned |
| **6** | 14–16 | scan 115 after centered `14` → scan 134 before centered `17` | `14`–`16` | planned |
| **7** | 17–19 | scan 134 after centered `17` → scan 154 before centered `20` | `17`–`19` | planned |
| **8** | 20–21 | scan 154 after centered `20` → scan 166 before centered `22` | `20`–`21` | planned |
| **9** | 22–23 | scan 166 after centered `22` → final narrative scan 179 | `22`–`23` | planned |

Chapter boundaries remain exactly those of the PASSED Tamil reading layer. In particular, Chapter 15 ends on scan 126 and Chapter 16 begins cleanly at centered `16` on scan 127.

---

## 5. Pilot / style lock

Batch 1 / Chapter 1 was the style pilot and is now **REVIEWED / COMPLETE**.

The pilot review checked:

- narrator voice and paragraph rhythm;
- handling of `வெள்ளிக்கிழமை` / Friday as a repeated thematic word;
- rhetorical questions, exclamations and repetition;
- religious references and comparisons;
- colloquial speech versus narration;
- names/place forms encountered in the pilot;
- source-page provenance comments;
- treatment of source punctuation without mechanical modernization;
- translation of Tiruppavai excerpts only from the lines printed in this source edition.

The resulting recurring choices are now locked in `GLOSSARY.md` unless later source context genuinely requires a documented change.

---

## 6. Core translation principles

1. **No summarising.** Every substantive paragraph, dialogue unit, list, quotation, rhetorical question and narratorial aside must be represented.
2. **Readable but source-bound English.** Reorder syntax only as needed for intelligibility; do not add explanation absent from Tamil.
3. **Preserve agency.** Do not change who acts, speaks, accuses, suffers, decides or knows something.
4. **Preserve force.** Anger, ridicule, shame, affection, melodrama, irony, accusation and repetition must not be softened.
5. **Do not intensify.** Do not make sexual, caste, religious, moral or violent language harsher or more categorical than the Tamil.
6. **Do not beautify.** Do not convert the novel into polished contemporary literary English at the cost of source character.
7. **Preserve source strangeness.** Verified awkwardness or discontinuity is not permission to invent the presumed intended Tamil.
8. **No modern explanations inside prose.** Necessary context belongs only in a clearly marked translator note or `GLOSSARY.md`.
9. **Keep chapters aligned.** English chapter 1 corresponds only to Tamil chapter 1, and so on through chapter 23.
10. **Auditability over smoothness.** When source fidelity and stylistic smoothness conflict, preserve fidelity and document the issue.

---

## 7. Names, shortened forms and place names

Use stable readable romanization without diacritics unless an established English form is clearly preferable. Preserve source distinctions between a full name and a shortened/familiar form.

Chapter 1-confirmed entries are locked in `GLOSSARY.md`; later names below remain seed decisions until first reviewed use.

| Tamil source form | Planned English form | Policy |
|---|---|---|
| `சிந்தாமணி` | **Chintamani** | **LOCKED in Chapter 1** |
| `அழகப்பன்` | **Azhagappan** | full name; seed |
| `அழகு` | **Azhagu** | preserve shortened/familiar source form; seed |
| `நயினா முகம்மது` | **Naina Muhammad** | stable readable form; seed |
| `நயினா` | **Naina** | preserve source-shortened form; seed |
| `ஆனந்தி` | **Anandi** | conservative readable form; seed |
| `சிவகாமி` | **Sivakami** | conservative readable form; seed |
| `சிவநேசர்` | **Sivanesar** | conservative readable form; seed |
| `டைகர்` | **Tiger** | source itself uses the English-derived name |
| `பாலகங்காதரத் தேவர்` | **Balagangadhara Thevar** | conservative form; do not add an external historical identity |
| `இடும்பன்` | **Idumban** | conservative readable form |
| `வேதபுரம்` | **Vedapuram** | **LOCKED in Chapter 1** |
| `பாலையூர்` | **Palaiyur** | source-facing place form; seed |
| `பெங்களூர்` | **Bangalore** | stable English form appropriate to the source period |

This table is a consistency tool for English only. It never authorizes changes to Tamil `pages/` or `sections/`.

If a later chapter supplies a clearer name/title relationship, update the glossary with an audit note rather than retroactively guessing.

---

## 8. Religious, caste and socially charged vocabulary

The novel contains explicit religious references, caste language, inter-religious relationship language, sexual/moral stigma and social judgement. Translate these as the source's narrative/dialogue rhetoric.

Policy:

- `முஸ்லீம்` → **Muslim**;
- `சாதி` → normally **caste**, according to sentence grammar;
- `மதம்` → **religion / faith** according to context; do not erase the distinction when characters explicitly discuss conversion or difference;
- `ராமாயணம்` → **Ramayana**;
- `மணிமேகலை` → **Manimekalai**;
- Christian / church references use standard English terms when the Tamil clearly uses those identities;
- terms carrying sexual or moral stigma such as `விபச்சாரி`, `வேசி`, `வைப்பாட்டி` must be translated with equivalent force appropriate to the immediate sentence — neither euphemized nor intensified — and recurring choices must be documented in `GLOSSARY.md`;
- caste/religious insults, jokes, criticism or polemic belong to the source voice or character voice; do not add present-day approval/disapproval inside the translation.

Where a term has no clean English equivalent, conservative transliteration plus a short glossary note is preferable to an invented explanation.

---

## 9. Cultural, ritual, kinship and period vocabulary

For culture-specific vocabulary:

1. use a direct English equivalent when one exists without loss;
2. retain a readable transliteration when the term denotes a specifically Tamil/Indian institution, kinship relation, ritual object or social practice that would be distorted by an approximate English substitute;
3. explain only on first materially important use, preferably in `GLOSSARY.md` rather than interrupting prose;
4. preserve period objects and borrowed vocabulary as period language rather than updating them to present-day equivalents.

Source-era loanwords such as railway/police/lock-up/Horlicks-type vocabulary should be rendered according to their clear meaning while preserving the period setting. Do not infer brands, institutions or offices not actually supported by the Tamil.

---

## 10. Dialogue, quotation, punctuation and paragraph policy

1. Spoken dialogue uses standard English double quotation marks.
2. Quotation inside dialogue uses single quotation marks.
3. Do not invent speaker labels where the Tamil identifies speakers only through narration/context.
4. Preserve paragraph boundaries unless English grammar requires a minimal split; never merge separate source paragraphs merely for smoothness.
5. Preserve rhetorical ellipses, repeated exclamation, abrupt fragments and pauses in force. Exact historical dot counts need not be copied mechanically when normal English typography can preserve the same effect.
6. Do not silently close or complete a sentence at a source boundary when the audited Tamil does not support completion.
7. Preserve songs, slogans, letters, quoted passages or visually distinct textual units as distinct Markdown blocks when encountered.
8. Chapter headings remain simple numbered chapter headings matching the Tamil structure.

---

## 11. Source oddity / discontinuity policy

The PASSED Tamil layer deliberately preserves physical discontinuities that must **not** be repaired by English inference.

Known examples:

- scan **117→118**: `உட்` followed by `எவ்வளவோ முயன்றும் நடக்கவில்லை.`;
- scan **122→123**: `...அவளுக்குப் பக்கத்திலே` followed by source-visible `கார்ந்து கொண்டாள்.`;
- scan **156→157**: `தலையிலும் காயம்` followed by `நயினா எதிர்த்தே அடிக்கவில்லை.` with no supplied punctuation.

English handling:

- preserve the abruptness or uncertainty;
- never invent the missing word/sentence from grammar or plot expectation;
- add an unobtrusive source comment and, only if necessary for reader understanding, a short translator note;
- if a later English review suggests the Tamil record may itself be wrong, reopen the controlling scan before changing anything.

Printed-page anomalies are also preserved in provenance. For example, scan 66 visibly prints only `5`; English provenance must not silently infer printed page 65.

---

## 12. Page/source traceability

Each English chapter file includes front matter similar to:

```yaml
---
work: "vellikkizhamai"
chapter: 1
language: "en"
translation_status: "reviewed"
source_section: "../../../sections/01-chapter-01.md"
source_scans: "4-12"
canonical_source: "../../../pages/"
---
```

Retain unobtrusive HTML comments at meaningful source boundaries:

```html
<!-- source: scan 12; printed page: 11 -->
```

For a verified cross-page join:

```html
<!-- source join: scan X `fragment` → scan Y `continuation` -->
```

Use the already-verified Tamil `sections/` markers as the guide to joins, then source-check against canonical `pages/` before marking the English batch reviewed.

---

## 13. Glossary policy

`GLOSSARY.md` is a controlled consistency ledger, not a dictionary.

Record:

- recurring names and shortened forms;
- place-name decisions;
- religious/caste/social terminology;
- kinship and ritual terms whose English handling needs consistency;
- period loanwords where multiple English forms are possible;
- source oddities that materially affect English;
- any decision changed after later context, with the reason and affected chapters.

Do not fill the glossary speculatively. Add or lock entries only when source context supports them.

---

## 14. Review statuses

Use these statuses:

- `planned` — no translation prose yet;
- `draft-translated` — complete first English draft exists for the stated chapter/range;
- `source-checked` — every English paragraph/dialogue unit checked against canonical Tamil pages;
- `reviewed` — source fidelity, rhetoric, names/terms, dialogue/agency and English readability reviewed;
- whole-work `verified` — final bilingual alignment across all 23 chapters has passed.

No chapter is `reviewed` merely because it reads fluently.

---

## 15. Per-batch workflow / checklist

For each batch:

1. translate only the PASSED Tamil layer;
2. create only the chapter files in that batch;
3. preserve source-scan provenance comments;
4. source-check every English paragraph/dialogue unit against canonical `pages/`;
5. verify names, numbers, places, relationships, quoted wording and agency;
6. verify rhetorical questions, repetition, insults, irony, emotional intensity and socially charged language;
7. verify every cross-page join and mixed chapter-boundary scan;
8. confirm no source oddity/discontinuity was silently repaired;
9. update `GLOSSARY.md` only for established recurring decisions;
10. update `PROGRESS.md`, English `README.md`, work `README.md`, root `HANDOVER.md` and `NEXT_NOVEL_CHAT_PROMPT.md`;
11. commit the completed bounded batch before starting another;
12. report batch result and next exact batch.

---

## 16. Final bilingual review gate

After all 23 English chapters are `reviewed`, complete `TRANSLATION_REVIEW.md` across the whole work.

The final review must check:

- complete 23-chapter coverage and ordering;
- no omitted or duplicated Tamil span;
- no material source-like addition;
- speaker attribution and agency;
- recurring names, shortened forms, kinship and titles;
- religious/caste/socially charged terminology;
- recurring metaphors and rhetorical repetition;
- dialogue / quotation integrity;
- every mixed chapter-boundary scan;
- source discontinuities and oddities;
- page provenance;
- English readability without modernization or adaptation.

Only after this gate passes may whole-work English be called **verified**.

---

## 17. Release gate

After whole-work English verification, complete `RELEASE_REPORT.md` and confirm:

- Tamil canonical page layer: **PASSED**;
- assembled Tamil: **PASSED**;
- English chapters: **23 / 23 present and reviewed**;
- final bilingual review: **PASSED**;
- glossary consistency: checked;
- reader navigation: checked;
- source PDF remains uncommitted;
- canonical Tamil remains unchanged by translation/release work;
- archival/editorial release verdict is stated separately from copyright/licensing questions.

---

## 18. Current status / next action

**Tamil canonical source:** PASSED  
**Tamil assembled reading layer:** PASSED  
**English translation plan:** COMPLETE  
**English package scaffolding:** INITIALIZED  
**English translation prose:** **1 / 23 chapters REVIEWED**  
**Pilot style / glossary lock:** **COMPLETE**

### Exact next activity

Run **Batch 2 — Chapters 2–4**:

- Chapter 2 — scans **13–22**;
- Chapter 3 — scan **23 through scan 33 before centered `4`**;
- Chapter 4 — scan **33 after centered `4` through scan 45 before centered `5`**.

Create `sections/02-chapter-02.md` through `04-chapter-04.md`, source-check each against canonical Tamil `pages/`, review the complete bounded batch and update controls before starting Chapter 5.