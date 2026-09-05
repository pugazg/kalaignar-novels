# English Translation Plan — பெரிய இடத்துப் பெண்

## 1. Objective

Create a clear, source-faithful English translation of **மு. கருணாநிதியின் `பெரிய இடத்துப் பெண்`** from the completed Tamil archival layers without rewriting it as a modern adaptation.

Working English title:

**The Woman of the Great House**

This is a provisional reading title for `பெரிய இடத்துப் பெண்`. The Tamil title remains authoritative. `Great House` is intended to preserve the source's recurring social-status / wealthy-household sense (`பணக்கார வீட்டுப்பெண்`, `சீமான் வீட்டுச் செல்வி`, `பெரிய இடத்து விஷயம்`) without treating the phrase as a formal aristocratic title. The English title may be reconsidered during final review, but only as an English editorial choice; the Tamil title must not be altered.

The translation must preserve the work's changing first-person viewpoints, satire, accusation, melodrama, moral argument, colloquial speech, repeated rhetorical questions, religious/mythological comparisons and contradictions between narrators.

---

## 2. Non-negotiable structural rule

**`பெரிய இடத்துப் பெண்` is one continuous work.**

The source-printed headings are internal character-account transitions, not separate stories or chapters invented by the archive:

1. `உத்தண்டி`
2. `கண்ணம்மா`
3. `குமுதா`
4. `வீரன்`
5. `உலகநாதர்`
6. `கண்ணம்மா`

The English layer must preserve this order and the fact that the accounts contradict, reinterpret and expose one another.

### Narrator-isolation rule

Translate each speaker's account from **that speaker's knowledge, assumptions and rhetoric at that point in the source**. Do not silently correct Veeran using Kannamma's later confession, do not rewrite Kannamma through Kumudha's perspective, and do not add explanatory hindsight from another section. Contradictions belong to the work and must remain visible to the reader.

---

## 3. Source-authority hierarchy

Translation authority is:

1. **controlling source scan** — ultimate authority if a Tamil reading is reopened;
2. **canonical Tamil `pages/` records** — controlling repository text for exact wording, punctuation, historical-glyph identity and page provenance;
3. **passed assembled Tamil `sections/`** — continuous reading layer and established cross-page joins;
4. **English translation** — derived layer;
5. metadata / audit / glossary notes — supporting editorial records only.

If assembled Tamil and canonical `pages/` appear to disagree, stop and follow the canonical page record unless the Tamil archival layer is explicitly corrected from source evidence first.

The user-mandated canonical verification freeze remains active: **0 `verified` / 49 `needs-review`**. English work must not change those statuses.

---

## 4. Planned English file structure

```text
works/periya-idathup-pen/translations/en/
  TRANSLATION_PLAN.md
  README.md
  PROGRESS.md
  GLOSSARY.md
  sections/
    01-opening.md
    02-uthandi.md
    03-kannamma-first.md
    04-kumudha.md
    05-veeran.md
    06-ulaganathar.md
    07-kannamma-conclusion.md
  TRANSLATION_REVIEW.md
  RELEASE_REPORT.md
```

The seven final English section files mirror the seven passed Tamil reading files. Translation may be worked in smaller batches, but the reader-facing structure remains the source-derived seven-section sequence.

---

## 5. Section and batch map

| Batch | Tamil assembled source | Scan coverage | English destination | Scope |
|---|---|---|---|---|
| **1 — pilot** | `sections/01-opening.md` | scan 8 → scan 15 before `உத்தண்டி` | `sections/01-opening.md` | title/opening narrative; Ulaganathar–Kannamma–Veeran frame; transition to character accounts |
| **2** | `sections/02-uthandi.md` | scan 15 `உத்தண்டி` → scan 19 before `கண்ணம்மா` | `sections/02-uthandi.md` | Uthandi's debt, employment and Kumudha account |
| **3A** | `sections/03-kannamma-first.md` | scan 19 heading → scan 24 | `sections/03-kannamma-first.md` | Kannamma's marriage, self-justification and relationship with Veeran |
| **3B** | same | scans 25–31 | same | abortion reference, Veeran's withdrawal, Ulaganathar's desire for Kumudha, Kannamma's scheme |
| **4** | `sections/04-kumudha.md` | scans 32–37 | `sections/04-kumudha.md` | Kumudha's written statement / account and its signed ending |
| **5** | `sections/05-veeran.md` | scans 38–44 | `sections/05-veeran.md` | Veeran's account, his reading of Kumudha and her death |
| **6** | `sections/06-ulaganathar.md` | scan 45 | `sections/06-ulaganathar.md` | Ulaganathar's brief first-person response |
| **7** | `sections/07-kannamma-conclusion.md` | scans 46–49 | `sections/07-kannamma-conclusion.md` | Kannamma's final confession, Kumudha's hidden letter, Calcutta ending, printer colophon |

No source text may be duplicated or omitted at the scan-15 and scan-19 mid-page heading splits.

---

## 6. Pilot and style lock

Batch 1 is the mandatory pilot.

Before Batch 2 begins, review Batch 1 for:

- the working English title and translation of `பெரிய இடத்து` social-status language;
- Ulaganathar / Kannamma / Veeran name forms;
- source satire and deliberately exaggerated comparison;
- colloquial dialogue and class/status vocabulary;
- treatment of `எஜமான் / எஜமானி`, `அம்மாள்`, `சீமான்`, `பணக்காரர்` and related household-status terms;
- rhetorical punctuation, ellipses and repeated exclamations;
- paragraph mapping and scan provenance.

Only after the pilot review should recurring choices be locked into `GLOSSARY.md` and the translation conventions.

---

## 7. Core translation principles

1. **No summarising.** Every substantive sentence, dialogue unit, rhetorical question, list, repeated insult, comparison and source-printed heading must be represented.
2. **Natural but source-bound English.** Tamil word order may be adjusted for intelligibility, but meaning, agency, blame and rhetorical direction must not change.
3. **Do not beautify.** Preserve abruptness, melodrama, repetition and deliberately coarse or satirical language where the Tamil uses them.
4. **Do not soften.** Terms condemning adultery, prostitution, sexual conduct, class behaviour, religion or social morality must not be euphemised merely for modern comfort.
5. **Do not intensify.** A loaded Tamil term must not be made harsher than its local context supports.
6. **Preserve viewpoint.** First-person self-justification, unreliable assumptions and contradictions are structural features, not errors to reconcile.
7. **Preserve source oddities.** A strange audited Tamil form is not permission to invent a normalized Tamil source behind it.
8. **Preserve paragraph rhythm.** Default is one English paragraph for one assembled-Tamil paragraph. Split/merge only when absolutely necessary and document the reason in review notes.
9. **Minimal visible notes.** Use a translator's note only when a retained Tamil term, historical office, kinship term or source anomaly materially affects comprehension.
10. **Traceability.** Every English section must remain reversible to the assembled section and canonical scan range.

---

## 8. Standard translator's note

Each final English section should carry a concise note near the beginning:

> **Translator's note:** This translation follows the source-audited Tamil preserved in this repository. The canonical Tamil page records remain authoritative. The English preserves the work's source-printed character accounts, rhetoric, colloquial language and historical-period vocabulary without silently modernising the Tamil. The canonical pages remain under the project's separate verification freeze.

Do not repeat long editorial explanations inside the prose.

---

## 9. Names and transliteration policy

Use readable romanization without academic diacritics unless a later release policy requires them.

| Tamil source form | Planned English form | Rule |
|---|---|---|
| `உலகநாதர்` | **Ulaganathar** | character name; do not translate semantically |
| `உலகநாத முதலியார்` | **Ulaganatha Mudaliar** | retain `Mudaliar` when explicitly printed; do not silently erase the title/form |
| `கண்ணம்மா` | **Kannamma** | default character form |
| `கண்ணம்மாள்` | **Kannammal** when the source form itself matters; otherwise **Kannamma** in ordinary narration | source variation remains traceable in Tamil |
| `உத்தண்டி` | **Uthandi** | stable readable transliteration |
| `குமுதா` | **Kumudha** | preserve this source form |
| `குமுதம்` | **Kumudam** | preserve distinction from `குமுதா`; the source itself comments on the name relationship |
| `வீரன்` | **Veeran** | proper name; do not translate as “hero” |
| `கல்கத்தா` | **Calcutta** | preserve the period-facing English place form rather than silently modernising to Kolkata |

### Kinship / address forms

- `அத்தான்`: do not automatically flatten to “husband” or “cousin.” In Kumudha's context the source establishes Veeran as Uthandi's sister's son and intended husband. The pilot should test retaining **Aththan** with a short first-use gloss.
- `மாமா`: translate contextually as **uncle** where the family relation is explicit.
- `அண்ணி`: do not force a literal kinship equivalent if the household-address usage would mislead. Retain **Anni** with a brief gloss if needed.
- `அம்மா / அம்மாள்`: distinguish ordinary respectful address from a formal name/title; do not mechanically transliterate every occurrence.

---

## 10. Social, moral and sexual vocabulary

These are glossary candidates requiring context-sensitive but consistent treatment:

| Tamil | Initial English handling | Policy |
|---|---|---|
| `கற்பு` | **chastity / sexual fidelity** | choose by context; do not reduce every occurrence to one English noun |
| `பத்தினி` | **chaste / devoted wife** | preserve the moral-religious register |
| `விபசாரி` | **adulteress / prostitute** | decide by local accusation/context; do not euphemise or over-intensify |
| `வேசி` | **whore / prostitute** | stronger invective than neutral description; pilot must lock tone |
| `கற்பழிக்கப்பட்டாள்` | **was raped / was sexually violated** | use the direct meaning supported by the passage; do not obscure agency |
| `சீதனம்` | **dowry / marriage property** | glossary candidate; use the term that best fits each sentence without importing legal detail absent from source |
| `வைதீக உலகம்` | **Vaidika / orthodox religious world** | preserve the source's polemical framing; glossary if retained |
| `குடியானவன்` | **tenant cultivator / cultivator** | do not invent a precise legal tenancy status not established by the source |
| `பண்ணையாள்` | **estate/farm labourer** | context-sensitive |
| `கூலிக்காரன்` | **wage labourer / labourer** | preserve class register |
| `எஜமான்` | **master / employer** | choose according to household/employment context |
| `எஜமானி` | **mistress of the house / female employer** | avoid modern sexual sense of “mistress” where misleading; phrase explicitly when needed |

The text's class and gender judgments are the speakers'/author's source rhetoric. Translation must neither endorse nor sanitize them through added commentary.

---

## 11. Religious and mythological vocabulary

The work repeatedly uses religious language both devotionally and satirically. Preserve that dual use.

Initial glossary candidates include:

- `நைவேத்தியம்` — retain **naivedyam** or translate **ritual offering** according to sentence; first use may carry a short gloss;
- `பக்தி`, `பக்திமணி`, `பக்த சிரோன்மணி` — preserve the elevated devotional register and its irony where present;
- `யம லோகம்` — **Yama's realm / Yamaloka**, decision to be locked in pilot/glossary;
- `மோட்ச சாம்ராஜ்யம்` — preserve the salvation/heavenly-kingdom rhetoric without doctrinal expansion;
- mythological names `அகல்யை`, `தாரை`, `பார்வதி`, `பிரம்மா`, `பத்திர காளி`, `இந்திரன்`, `இந்திராணி`, `ரதி`, `மன்மதன்` — use stable readable English forms (Ahalya, Tara, Parvati, Brahma, Bhadrakali, Indra, Indrani, Rati, Manmatha) while translating only what the source states about them.

Do not use outside mythological knowledge to complete, correct or reinterpret the source's allusions inside the translation.

---

## 12. Historical office / household vocabulary

Terms such as `தலையாரி`, `பண்ணைக்காரர்`, `மண்டிக்கடை`, `உத்தியோகம்`, and status forms such as `முதலியார்` must not be assigned a highly specific historical English equivalent unless the source and repository evidence support it.

Policy:

- use a cautious functional translation where the immediate context is sufficient;
- retain/transliterate the Tamil term with a glossary note where an English equivalent would overstate institutional precision;
- never silently rewrite the Tamil source to match the chosen English gloss.

`தலையாரி` is a priority pilot glossary item because Uthandi's role is important to the class/debt structure of the story.

---

## 13. Source-specific and difficult Tamil forms

The completed Tamil audit intentionally preserves unusual source readings. English translation must not pretend a normalized Tamil form was printed.

Priority examples include:

- `குரூபப்பற்றி`
- `எண்ணப்பட்டாளம்`
- `குவலிக் கிடப்பார்`
- `பச்சப் வார்த்தைகளைப்`
- `வக்குப் பேதி`
- `அவமானந்`
- `கல்மனங்`
- `தண்டன்`
- `ஒடித் தெரியத்`
- `வேசின்`
- `தத்தம்`
- `போகவேண்டு மென்னிருக்கலே`
- `பாடங்`

For any such form:

1. translate only the meaning genuinely supported by the audited context;
2. if confidence remains limited, use cautious English and record the exact Tamil in a source note / review log;
3. do not silently normalize the canonical Tamil;
4. if translation work exposes a plausible Tamil transcription problem, stop and re-open the source evidence before changing either layer.

The canonical historical-glyph corrections (`கண்ணாடி`, `இளிச்சவாயனாக`, `நானா ஆள்?`, `விட வேணா?` and earlier corrections) are already settled source readings and must be translated from those corrected forms.

---

## 14. Dialogue, punctuation and typography

- Preserve who speaks and the source's quotation scope; do not invent missing speaker labels.
- English quotation marks may be typographically standardized, but quotation **content and boundary** must remain source-driven.
- Preserve rhetorical questions and exclamation density where they carry the voice.
- Preserve meaningful ellipses / repeated-dot pauses; do not collapse them merely for house style during drafting.
- Em dashes or parentheses may be used only where they correspond to source punctuation/structure or are necessary for English syntax without changing meaning.
- Do not add terminal punctuation at a source page boundary merely because English style would prefer it; assembled source joins govern continuity.
- Preserve Kumudha's letter-like rhetoric and signed closing as a distinct visual unit.
- Preserve the final printer colophon as **non-narrative source matter**, not as part of Kannamma's speech.

---

## 15. Translation traceability

Each English section should begin with front matter such as:

```yaml
---
work: "periya-idathup-pen"
language: "en"
translation_status: "draft-translated"
source_section: "../../../sections/01-opening.md"
source_scans: "8-15 (before Uthandi heading)"
canonical_source: "../../../pages/"
---
```

Retain unobtrusive HTML provenance comments at meaningful scan boundaries, for example:

```html
<!-- source: scan 12; printed page: 11 -->
```

For an established join:

```html
<!-- source join: scan 14 `நினைக்` + scan 15 `காதே!` → `நினைக்காதே!` -->
```

The provenance comments must not become visible explanatory prose in the normal reader.

---

## 16. English review states

Use:

- `draft-translated` — complete first English draft exists for the stated range;
- `source-checked` — every paragraph/dialogue unit checked against canonical Tamil and provenance;
- `reviewed` — meaning, voice, terminology, names, rhetoric and English readability reviewed;
- `verified` — final bilingual alignment and section-boundary review complete.

English `verified` is an English-layer status only. It does **not** change the canonical Tamil verification freeze or convert any Tamil page from `needs-review`.

---

## 17. Per-batch review checklist

After every batch:

1. confirm every Tamil paragraph / dialogue / heading in the batch is represented;
2. confirm names, kinship terms, numbers, money amounts, places and occupations;
3. confirm speaker agency and viewpoint have not shifted;
4. confirm accusations, insults, sexual/moral vocabulary, irony and rhetorical questions are neither softened nor intensified;
5. confirm mythological/religious comparisons are translated only from source content;
6. verify all page-boundary joins against canonical `pages/`;
7. verify no unusual Tamil form was silently normalized;
8. update `GLOSSARY.md` only for recurring decisions supported by the text;
9. update `PROGRESS.md`, translation `README.md`, work `README.md` and handover;
10. do not mark a section `verified` until source-check and English review are both complete.

---

## 18. Final bilingual review

After all batches are complete, create `TRANSLATION_REVIEW.md` and check end-to-end for:

- omitted or duplicated material;
- changed speaker responsibility / chronology;
- contradictions accidentally harmonized between Uthandi, Kannamma, Kumudha, Veeran and Ulaganathar;
- softened/intensified gender, class, religious or sexual rhetoric;
- inconsistent names and kinship terms;
- inconsistent handling of `கற்பு`, `விபசாரி`, `வேசி`, `சீதனம்`, `எஜமான்` and related terms;
- loss of Kumudha's letter form or source headings;
- dialogue / quotation errors;
- page-boundary continuity errors;
- final Calcutta sequence and printer-colophon separation;
- English readability without rewriting the source.

---

## 19. Release gate under the verification freeze

Translation may proceed because the dedicated Tamil source-comparison audit is complete and the assembled Tamil layer is PASSED. However, completing English does **not** automatically make the whole archival package release-ready.

A future release report must explicitly record the canonical state then in force. If the user-mandated freeze still remains **0 `verified` / 49 `needs-review`**, the report must carry that qualification or wait for explicit user disposition; English completion must not silently override it.

---

## 20. Current status and exact next activity

**Tamil canonical coverage:** 49 / 49  
**Dedicated Tamil source comparison:** COMPLETE  
**Assembled Tamil:** PASSED  
**Canonical verification freeze:** ACTIVE — 0 verified / 49 `needs-review`  
**English translation plan:** COMPLETE  
**English prose:** NOT STARTED

### Next exact activity

Begin **Batch 1 — pilot translation of `sections/01-opening.md`**, covering scan 8 through scan 15 immediately before the `உத்தண்டி` heading.

At the start of the pilot, create/update `translations/en/README.md`, `PROGRESS.md` and the initial `GLOSSARY.md`. Before Batch 2, source-check and review the pilot and lock the first recurring decisions: the working English title, `பெரிய இடத்து` status language, names, household/class terms, dialogue tone, rhetorical punctuation and initial glossary entries.
