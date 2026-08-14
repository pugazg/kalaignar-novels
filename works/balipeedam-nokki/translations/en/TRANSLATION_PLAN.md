# English Translation Plan — பலிபீடம் நோக்கி

## 1. Objective

Create a clear, faithful English translation of **மு. கருணாநிதியின் `பலிபீடம் நோக்கி`** that carries the work's argument, historical-cinematic construction, satire, accusation, repetition, imagery, dialogue and political force into readable English **without recasting it as a modern literary adaptation**.

Working English title:

**Towards the Sacrificial Altar**

The title is a reading translation of `பலிபீடம் நோக்கி`; the Tamil title remains the authoritative work title in archival metadata.

The English must help a reader follow both levels of the work:

1. the governing `பலிபீடம்` / sacrificial-altar argument; and
2. the embedded `ராயசம் வெங்கண்ணு — தஞ்சை சரித்திரக் கதை` film-like historical sequence used inside that argument.

The translation must **not** turn those two levels into two separate works.

---

## 2. Non-negotiable structural rule

**`பலிபீடம் நோக்கி` is one continuous work.**

`ராயசம் வெங்கண்ணு — தஞ்சை சரித்திரக் கதை` is an internal cinematic-historical sequence, not a separate story/work for repository, translation or release purposes.

Source-supported architecture:

```text
பலிபீடம் நோக்கி
├── scans 4–7
│   opening polemical / ideological frame
├── scan 7
│   narrator explicitly introduces a film-like lesson
├── scans 8–29 + opening of scan 30
│   internal ராயசம் வெங்கண்ணு cinematic-historical sequence
├── scan 30
│   film end-card, then “படம் முடிந்துவிட்டது...”
└── scan 30 remainder–33
    return to the main பலிபீடம் argument and conclusion
```

The English may reproduce the internal title card prominently, but must label it as an **internal sequence of _Towards the Sacrificial Altar_**.

No separate work-level metadata, directory, release title, translation identity or bibliography entry is to be created for `ராயசம் வெங்கண்ணு`.

---

## 3. Source-authority hierarchy

Translation must follow this authority order:

1. **Canonical audited Tamil page records** — `../../pages/`  
   Final authority for exact wording, punctuation, names, source oddities and page provenance.
2. **Assembled Tamil reading layer** — `../../sections/`  
   Used for continuous reading and already-audited page-boundary joins.
3. **Metadata / audit files** — `../../metadata/source.md`, `../../audit.md`, `../../indexes/page-map.md`  
   Used for edition identity, structural decisions and audit history.
4. **External historical references** — only if a later editorial note genuinely requires them. They must never override the printed Tamil silently.

If the assembled Tamil and canonical page files appear to disagree, stop and follow the canonical `pages/` record unless a documented source correction is first made in the Tamil archival layer.

Do not translate from memory, from an internet edition, from OCR, or from a historically normalized retelling.

---

## 4. Translation file structure

Planned English layer:

```text
works/balipeedam-nokki/translations/en/
  TRANSLATION_PLAN.md
  README.md                     # create when translation begins
  PROGRESS.md                   # create when translation begins
  GLOSSARY.md                   # create with the pilot batch
  sections/
    01-opening-frame.md
    02-rayasam-vengannu-sequence.md
    03-return-and-conclusion.md
  TRANSLATION_REVIEW.md         # final fidelity/editorial review
  RELEASE_REPORT.md             # create only after final verification
```

The three English section files mirror the three audited Tamil reading sections. Translation work may be performed in smaller batches inside those files, but the final public structure remains one work with three reading sections.

---

## 5. Translation batches

The middle cinematic sequence is long, so translation will proceed in controlled batches while preserving the three-section final structure.

| Batch | Tamil assembled section | Source scans | English destination | Scope |
|---|---|---:|---|---|
| **1 — pilot** | `01-opening-frame.md` | 4–7 | `sections/01-opening-frame.md` | opening `பலிபீடம்` argument; Senguttuvan; transition into film |
| **2** | `02-rayasam-vengannu-sequence.md` | 8–13 | `sections/02-rayasam-vengannu-sequence.md` | internal title card, Nayak court, battle, fall of Vijayaraghava |
| **3** | same | 14–20 | same | Alagiri–Vengannu sequence; discovery of Sengamaladasan |
| **4** | same | 21–26 | same | Bijapur / Venkoji intervention; restoration; ministership conflict |
| **5** | same | 27–30 through the `வணக்கம்` film end-card | same | final Vengannu–Venkoji movement, fall of Sengamaladasan, film ending |
| **6** | `03-return-and-conclusion.md` | scan 30 beginning `படம் முடிந்துவிட்டது...` through 33 | `sections/03-return-and-conclusion.md` | return to governing argument and final polemical conclusion |

### Scan 30 rule

Scan 30 belongs to **two translation batches at a narrative boundary**, not because it is two source pages:

- Batch 5 translates the continuation from scan 29 through the internal film's `வணக்கம்` end-card.
- Batch 6 begins only at `படம் முடிந்துவிட்டது. பாடம் கற்றுக்கொண்டீர்களா?...`.

No sentence may be duplicated or omitted at this boundary.

---

## 6. Pilot and style lock

Batch 1 is the mandatory pilot.

Before Batch 2 starts, Batch 1 must be reviewed for:

- translation of the central `பலிபீடம்` metaphor;
- `ஆரியம்`, `தன்மானம்`, `மறம்`, `கொற்றம்`, `பகுத்தறிவு` and related political vocabulary;
- rhetorical questions and repeated exclamations;
- historical names and source-specific spellings;
- source metaphors that sound unusual in English;
- paragraph rhythm and direct address;
- treatment of the scan-7 transition into the internal film.

The resulting choices are then frozen in `GLOSSARY.md` / the translation conventions before continuing.

---

## 7. Core translation principles

1. **Argument before ornament** — preserve the sequence of Kalaignar's thought and rhetorical escalation.
2. **No summarising** — every substantive sentence, dialogue line, list, image, title card and rhetorical question must be represented.
3. **Natural but source-bound English** — do not reproduce Tamil syntax mechanically when it obscures meaning, but do not add interpretation absent from the source.
4. **Do not beautify** — this is not a literary adaptation or a rewritten historical novel.
5. **Preserve force** — accusation, ridicule, irony, anger, sarcasm, repetition and polemical intensity must not be softened.
6. **Do not intensify** — equally, do not make a statement harsher, more categorical or more historically specific than the Tamil.
7. **Preserve cinematic construction** — camera-like movement, screen language, music cues, title cards and bracketed directions are part of the work's form.
8. **Preserve source uncertainty/oddity** — an awkward or unusual verified Tamil reading is not permission to invent a smoother underlying source.
9. **Minimal editorial notes** — add a note only when an untranslated term, historical title, source anomaly or culturally specific expression materially affects comprehension.
10. **Traceability** — every translated batch must retain source-scan provenance and be checkable against the canonical page records.

---

## 8. Standard translator's note

Each final English section should carry a short standard note near the beginning:

> **Translator's note:** This English translation follows the audited first-edition Tamil source preserved in this repository. It aims to carry Kalaignar's argument, rhetoric, dialogue, historical-cinematic form and political intensity into clear English without modernising or silently correcting the Tamil. The audited Tamil page records remain authoritative. `ராயசம் வெங்கண்ணு — தஞ்சை சரித்திரக் கதை` is retained as an internal film-like sequence of `பலிபீடம் நோக்கி`, not treated as a separate work.

Section-specific notes may follow only where necessary.

---

## 9. Names, titles and place names

### General rule

Use a stable readable English form **without altering the canonical Tamil**.

Where a person's historically standardized English name is clear from the source identity, use the stable English form in translation. Where the source form is unusual, uncertain or itself rhetorically significant, transliterate conservatively and document the choice rather than silently replacing it with a historically reconstructed spelling.

### Initial consistency table

| Tamil source form | Planned English form | Policy |
|---|---|---|
| `சேரன் செங்குட்டுவன்` | **Cheran Senguttuvan** | retain Tamil historical name form |
| `விசயராகவன் / விசயராகவ` | **Vijayaraghava** | one English form; Tamil variation remains in source layer |
| `மன்னரு நாயக்கன்` | **Mannaru Nayak** | conservative transliteration |
| `குமார தாத்தாச்சார்யா` | **Kumar Tatacharya** | conservative readable form |
| `சொக்கநாத நாயக்கன்` | **Sokkanatha Nayak** | conservative transliteration |
| `வெங்கண்ணு` | **Vengannu** | preserve the source's internal-title spelling; do not silently change to Venganna |
| `செங்கமலதாசன்` | **Sengamaladasan** | conservative transliteration |
| `வெங்காஜி` | **Venkoji** | stable readable form; source form remains traceable |
| `ஷாஜி` | **Shahji** | stable English historical form |
| `சிவாஜி` | **Shivaji** | stable English form |
| `பீஜபூர்` | **Bijapur** | established place form |
| `தஞ்சை / தஞ்சாவூர்` | **Thanjavur** | use a consistent English place name; retain distinctions only where wording itself matters |
| `மதுரை` | **Madurai** | established form |
| `கும்பகோணம் / குடந்தை` | **Kumbakonam**; source alias may be noted where rhetorically relevant | do not erase a source alias if it matters |
| `பாபநாசம்` | **Papanasam** | established transliteration |
| `மன்னார்குடி` | **Mannargudi** | established transliteration |
| `நாகை` | **Nagai** unless an editorial note explicitly identifies the modern place name | preserve source-facing form |
| `ராயசம்` | **Rayasam** | retain as a source title/term; glossary note only if separately verified |

This table is a translation consistency tool, not permission to rewrite the Tamil page files.

---

## 10. Central ideological / social vocabulary

These terms must be translated consistently but contextually, not by blind one-to-one substitution.

| Tamil | Default English handling | Notes |
|---|---|---|
| `பலிபீடம்` | **sacrificial altar** | central governing metaphor; avoid drifting among unrelated synonyms |
| `ஆரியம்` | **Aryanism / the Aryan order / Aryan** | choose noun/adjective form according to sentence; do not turn it into a modern racial-science claim |
| `ஆரிய பலிபீடம்` | **Aryan sacrificial altar** | preserve polemical metaphor |
| `தன்மானம்` | **self-respect / dignity** | choose by rhetorical context; glossary should lock recurring usage after pilot |
| `பகுத்தறிவு` | **rationalism / reason** | preserve movement-era force; do not flatten to generic "common sense" |
| `அந்தணர்` | **Brahmins / Brahmin community** where context clearly carries caste identity | do not euphemize or intensify |
| `பார்ப்பனியம்` if encountered | **Brahminism** | ideological/system term, distinct from an individual Brahmin |
| `சூத்திரர்` | **Shudras** | retain historical/caste term; glossary note as needed |
| `அக்கிரகாரம்` | **agraharam** | retain Indian/Tamil institutional term; glossary on first use |
| `இந்துமதம்` | **Hinduism / Hindu religion** | choose according to sentence; preserve the work's criticism as source rhetoric |
| `மனுதர்மம்` | **Manudharma** or **the law/order of Manu** | pilot should decide consistent readable form |

### Polemical-language rule

The work contains explicit attacks on caste hierarchy, religious institutions, Hinduism, Brahminical/Aryan structures and social practices. Translate these statements as **the author's historical rhetoric**:

- do not censor or soften them;
- do not add present-day justification or condemnation inside the translation;
- do not turn metaphor into external historical fact;
- do not replace historically specific political vocabulary with later academic terminology unless the source itself supports it.

Any contextual explanation belongs in a clearly marked translator/editor note, not in the translated sentence.

---

## 11. Cinematic vocabulary and form

The internal historical sequence deliberately imitates a film. That form must remain obvious in English.

Default handling:

| Tamil source | English handling |
|---|---|
| `எரிமலை ‘ரிலீஸ்’` | **Erimalai ‘Release’** |
| `டைரக்ஷன்` | **Direction** |
| `திரைக்கதை அமைப்பு` | **Screenplay** / **Screenplay construction** — choose during pilot/title-card review and use consistently |
| `வசனம்` | **Dialogue** |
| `காமிரா` | **camera** |
| `குளோசப் / குளோசப்பில்` | **close-up / in close-up** |
| `திரையில்` | **on the screen** |
| `பின்னணி இசை / சங்கீதம்` | **background music** |
| bracketed action directions | retain as **[bracketed directions]** |
| visible title/credit cards | preserve as distinct block formatting |
| `வணக்கம்` end-card | translate in the film-ending context while noting/preserving the source card if needed |

Do not convert screenplay-like prose into ordinary novelistic narration. If the source says the screen shifts, a close-up appears, music sounds, lettering rolls or a scene changes, the English must retain that visual grammar.

---

## 12. Dialogue, quotation and punctuation conventions

1. Spoken dialogue will use standard English double quotation marks in the final English layer.
2. A quotation inside spoken dialogue will use single quotation marks.
3. Printed bracketed directions remain bracketed and on their own line when the source presents them distinctly.
4. Rhetorical ellipses, repeated exclamation and abrupt fragments should retain their force; they need not reproduce every historical typesetting dot mechanically if doing so damages readability.
5. Do not merge separate source paragraphs merely to create smoother English prose.
6. Do not silently close a quotation at a source-page boundary where the Tamil intentionally continues onto the next page.
7. Lists, slogans, signboards, title cards and closing verse/chant material should retain visibly distinct formatting.

---

## 13. Source oddities and historical spellings

The Tamil source audit has already confirmed several unusual forms. Translation must not use them as an excuse to rewrite the Tamil or pretend that a normalized Tamil reading was printed.

Important audited examples include:

- `பேனுப் பிடிக்கும்`
- `மித்தானமத்தனுக்குக்`
- `முச்சுற்றுப்படுத்திருக்கும்`
- `மளமள வென்று`
- `என்றுன் பேதை!`
- `களேபாரப்படுகிறது`
- `தர்ப்பாகூரர்`
- `விபரீதத்தை ஏற்கத்`
- `ஒரு காரணம்!`

Policy:

- translate the meaning only when the meaning is genuinely supported by the surrounding audited source;
- where a source oddity materially affects confidence, use the closest cautious English and add a short source note containing the exact Tamil form;
- never silently replace the archival Tamil with the inferred normalized word;
- if translation review reveals a possible Tamil transcription problem, stop and reopen the Tamil audit before changing the English.

---

## 14. Central metaphor and rhetorical repetition

`பலிபீடம்` is not merely a physical altar in this work. Kalaignar repeatedly uses it as a governing political-social metaphor.

The English must therefore preserve repetition rather than stylistically varying it away:

- `பலிபீடம்` → **sacrificial altar**
- `பலிபீடம் நோக்கி` → normally **towards the sacrificial altar** / **look towards the sacrificial altar**, according to grammar
- repeated imperatives such as `நோக்குங்கள்` should remain repeated where the Tamil repeats them.

Do not substitute a series of synonyms such as *altar*, *slaughter-place*, *sacrificial platform*, *pyre* merely for stylistic variety.

---

## 15. Translation traceability

Every English section file must include front matter similar to:

```yaml
---
work: "balipeedam-nokki"
language: "en"
translation_status: "draft-translated"
source_section: "../../sections/01-opening-frame.md"
source_scans: "4-7"
canonical_source: "../../pages/"
---
```

Within the English text, source provenance should be retained with unobtrusive HTML comments at meaningful page boundaries, for example:

```html
<!-- source: scan 8; printed page: — -->
```

For a verified cross-page join:

```html
<!-- source join: scan 29 `அப்படித்` → scan 30 `தத்தளிக்கிறான்...` -->
```

These markers are for auditability and must not appear as visible editorial prose in normal Markdown rendering.

---

## 16. Review statuses

Use the following English-layer statuses:

- `draft-translated` — complete first English draft exists for the stated source range;
- `source-checked` — every English paragraph checked against canonical audited Tamil pages;
- `reviewed` — meaning, rhetoric, dialogue, terminology, names and English readability reviewed;
- `verified` — final bilingual alignment and section-boundary check complete.

A section cannot be marked `verified` merely because it reads well in English.

---

## 17. Per-batch review checklist

After each batch:

1. verify that every Tamil paragraph / dialogue unit in the batch is represented;
2. verify names, numbers, places, titles and quoted wording;
3. verify rhetorical questions, repetition, insults, irony and emphatic contrast;
4. verify cinematic directions and title-card elements;
5. compare all page-boundary joins against canonical `pages/` records;
6. check that no source oddity was silently normalized;
7. update glossary / consistency table only when a recurring decision is established;
8. update `PROGRESS.md` and work `README.md`;
9. do not mark the batch `verified` until source-check and English review are both complete.

Because the Tamil source layer has already passed direct scan audit, the normal translation review compares English primarily to the canonical audited Tamil page files. If any discrepancy raises doubt about the Tamil, reopen the scan before proceeding.

---

## 18. Final bilingual / editorial review

After all six translation batches are complete, create:

`TRANSLATION_REVIEW.md`

The final review must check the complete work end-to-end for:

- omitted or duplicated Tamil material;
- changed responsibility / agency;
- softened or intensified polemic;
- inconsistent translation of `பலிபீடம்`, `ஆரியம்`, caste/religious terminology and movement vocabulary;
- inconsistent historical names or titles;
- loss of cinematic language;
- quotation / dialogue errors;
- scan-30 transition integrity;
- source-oddity notes;
- English readability without modernization of content;
- preservation of the one-work structure.

Only after this review is complete may all three English section files be marked `verified`.

---

## 19. Release gate

English release is permitted only when all of the following are true:

- Tamil page layer: **PASSED**;
- assembled Tamil layer: **PASSED**;
- all six English translation batches: complete;
- all three English section files: `verified`;
- `GLOSSARY.md`: consistency-checked;
- `TRANSLATION_REVIEW.md`: complete;
- no unresolved omission/addition findings;
- one-work structural rule preserved;
- `RELEASE_REPORT.md`: created.

The audited Tamil remains authoritative even after English release.

---

## 20. Current status and next action

**Tamil canonical source:** PASSED  
**Tamil assembled reading layer:** PASSED  
**English translation plan:** COMPLETE  
**English prose translation:** NOT STARTED

### Next exact activity

Begin **Batch 1 — pilot translation of scans 4–7 / `sections/01-opening-frame.md`**.

Before translating Batch 2, review Batch 1 and lock the initial glossary / style decisions, especially the central `பலிபீடம்` metaphor, `ஆரியம்`, self-respect / rationalist vocabulary, rhetorical repetition, names and the transition into the internal film.
