# English Translation Plan — பெரிய இடத்துப் பெண்

## Execution status — FULLY EXECUTED

This plan has been completed end to end.

- English section files: **7 / 7 reviewed**;
- planned translation batches: **8 / 8 reviewed**;
- final bilingual review: **PASSED**;
- whole-work English: **VERIFIED**;
- release report: **COMPLETE**;
- release-readiness: **PASSED WITH CANONICAL-TAMIL VERIFICATION QUALIFICATION**;
- canonical Tamil freeze: **ACTIVE — 0 verified / 49 `needs-review`**.

Sections 1–18 below remain the controlling translation policy/history. Sections 19–20 record the completed final/release state rather than an unfinished next activity.

## 1. Objective

Create a clear, source-faithful English translation of **மு. கருணாநிதியின் `பெரிய இடத்துப் பெண்`** from the completed Tamil archival layers without rewriting it as a modern adaptation.

Working English title:

**The Woman of the Great House**

This is the English reading title used for `பெரிய இடத்துப் பெண்`. The Tamil title remains authoritative. `Great House` preserves the source's recurring social-status / wealthy-household sense (`பணக்கார வீட்டுப்பெண்`, `சீமான் வீட்டுச் செல்வி`, `பெரிய இடத்து விஷயம்`) without treating the phrase as a formal aristocratic title.

The translation preserves the work's changing first-person viewpoints, satire, accusation, melodrama, moral argument, colloquial speech, repeated rhetorical questions, religious/mythological comparisons and contradictions between narrators.

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

The English layer preserves this order and the fact that the accounts contradict, reinterpret and expose one another.

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

The user-mandated canonical verification freeze remains active: **0 `verified` / 49 `needs-review`**. English work does not change those statuses.

---

## 4. English file structure

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

The seven final English section files mirror the seven passed Tamil reading files. Translation was worked in eight controlled batches because the first Kannamma section was split into Batches 3A and 3B.

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

No source text is duplicated or omitted at the scan-15 and scan-19 mid-page heading splits.

---

## 6. Pilot and style lock

Batch 1 was the mandatory pilot. It was reviewed before later batches proceeded.

The pilot locked recurring choices for:

- the working English title and translation of `பெரிய இடத்து` social-status language;
- Ulaganathar / Kannamma / Veeran name forms;
- source satire and deliberately exaggerated comparison;
- colloquial dialogue and class/status vocabulary;
- treatment of `எஜமான் / எஜமானி`, `அம்மாள்`, `சீமான்`, `பணக்காரர்` and related household-status terms;
- rhetorical punctuation, ellipses and repeated exclamations;
- paragraph mapping and scan provenance.

Later recurring decisions were added to `GLOSSARY.md` through Batch 7 and the final bilingual review.

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

Each final English section carries or follows the policy represented by this concise note:

> **Translator's note:** This translation follows the source-audited Tamil preserved in this repository. The canonical Tamil page records remain authoritative. The English preserves the work's source-printed character accounts, rhetoric, colloquial language and historical-period vocabulary without silently modernising the Tamil. The canonical pages remain under the project's separate verification freeze.

Long editorial explanations are kept outside the prose.

---

## 9. Names and transliteration policy

Use readable romanization without academic diacritics unless a later release policy requires them.

| Tamil source form | English form | Rule |
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

- `அத்தான்`: retain **Aththan** where the relation/address matters. In Kumudha's context the source establishes Veeran as Uthandi's sister's son and intended husband.
- `மாமா`: translate contextually as **uncle** where the family relation is explicit.
- `அண்ணி`: do not force a literal kinship equivalent if the household-address usage would mislead. Retain **Anni** where needed.
- `அம்மா / அம்மாள்`: distinguish ordinary respectful address from a formal name/title; do not mechanically transliterate every occurrence.

---

## 10. Social, moral and sexual vocabulary

These are context-sensitive but controlled choices:

| Tamil | English handling | Policy |
|---|---|---|
| `கற்பு` | **chastity / sexual fidelity** | choose by context; do not reduce every occurrence to one English noun |
| `பத்தினி` | **chaste / devoted wife** | preserve the moral-religious register |
| `விபசாரி` | **adulteress** in the contexts used here | do not euphemise or over-intensify |
| `வேசி` | **whore / prostitute** according to sentence | stronger invective; preserve speaker attribution |
| `கற்பழிக்கப்பட்டாள்` | **was raped** | final direct rendering; do not obscure the coercion |
| `சீதனம்` | **dowry** | do not import legal detail absent from source |
| `வைதீக உலகம்` | **Vaidika world** | preserve the source's polemical framing |
| `குடியானவன்` | **cultivator** | do not invent a precise legal tenancy status not established by the source |
| `பண்ணையாள்` | **estate labourer** | functional class description supported by context |
| `கூலிக்காரன்` | **wage labourer / labourer** | preserve class register |
| `எஜமான்` | **master / employer** | choose according to household/employment context |
| `எஜமானி` | **lady of the house / female employer** | avoid the misleading modern sexual sense of “mistress” |

The text's class and gender judgments are the speakers'/author's source rhetoric. Translation neither endorses nor sanitizes them through added commentary.

---

## 11. Religious and mythological vocabulary

The work repeatedly uses religious language both devotionally and satirically. Preserve that dual use.

Controlled forms include:

- `நைவேத்தியம்` — **naivedyam**, with contextual gloss where needed;
- `பக்தி`, `பக்திமணி`, `பக்த சிரோன்மணி` — elevated devotional register and irony preserved;
- `யம லோகம்` — **Yama's realm**;
- `மோட்ச சாம்ராஜ்யம்` — salvation/heavenly-kingdom rhetoric without doctrinal expansion;
- mythological names `அகல்யை`, `தாரை`, `பார்வதி`, `பிரம்மா`, `பத்திர காளி`, `இந்திரன்`, `இந்திராணி`, `ரதி`, `மன்மதன்` — stable readable English forms Ahalya, Tara, Parvati, Brahma, Bhadrakali, Indra, Indrani, **Rati**, Manmatha.

Do not use outside mythological knowledge to complete, correct or reinterpret the source's allusions inside the translation.

---

## 12. Historical office / household vocabulary

Terms such as `தலையாரி`, `பண்ணைக்காரர்`, `மண்டிக்கடை`, `உத்தியோகம்`, and status forms such as `முதலியார்` must not be assigned a highly specific historical English equivalent unless the source and repository evidence support it.

Policy:

- use a cautious functional translation where the immediate context is sufficient;
- retain/transliterate the Tamil term with a glossary note where an English equivalent would overstate institutional precision;
- never silently rewrite the Tamil source to match the chosen English gloss.

`தலையாரி` is retained as **talaiyari** rather than over-specifying the office.

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

The canonical historical-glyph corrections (`கண்ணாடி`, `இளிச்சவாயனாக`, `நானா ஆள்?`, `விட வேணா?` and earlier corrections) are settled source readings and are translated from those corrected forms.

---

## 14. Dialogue, punctuation and typography

- Preserve who speaks and the source's quotation scope; do not invent missing speaker labels.
- English quotation marks may be typographically standardized, but quotation **content and boundary** must remain source-driven.
- Preserve rhetorical questions and exclamation density where they carry the voice.
- Preserve meaningful ellipses / repeated-dot pauses; do not collapse them merely for house style.
- Em dashes or parentheses may be used only where they correspond to source punctuation/structure or are necessary for English syntax without changing meaning.
- Do not add terminal punctuation at a source page boundary merely because English style would prefer it; assembled source joins govern continuity.
- Preserve Kumudha's letter-like rhetoric and signed closing as a distinct visual unit.
- Preserve the final printer colophon as **non-narrative source matter**, not as part of Kannamma's speech.

---

## 15. Translation traceability

Each English section uses front matter tied to its source section/scans and canonical source. Unobtrusive HTML provenance comments are retained at meaningful scan boundaries and established joins.

Example:

```html
<!-- source: scan 12; printed page: 11 -->
```

For an established join:

```html
<!-- source join: scan 14 `நினைக்` + scan 15 `காதே!` → `நினைக்காதே!` -->
```

The provenance comments are not visible explanatory prose in the normal reader.

---

## 16. English review states

The workflow used:

- `draft-translated` — complete first English draft exists for the stated range;
- `source-checked` — every paragraph/dialogue unit checked against canonical Tamil and provenance;
- `reviewed` — meaning, voice, terminology, names, rhetoric and English readability reviewed;
- whole-work `verified` — final bilingual alignment and section-boundary review complete.

Final section files intentionally retain batch-level `reviewed`. Whole-work English **VERIFIED** is recorded by `TRANSLATION_REVIEW.md`.

English verification is an English-layer status only. It does **not** change the canonical Tamil verification freeze or convert any Tamil page from `needs-review`.

---

## 17. Per-batch review checklist

After every batch the workflow checked:

1. every Tamil paragraph / dialogue / heading represented;
2. names, kinship terms, numbers, money amounts, places and occupations;
3. speaker agency and viewpoint;
4. accusations, insults, sexual/moral vocabulary, irony and rhetorical questions for unintended softening/intensification;
5. mythological/religious comparisons only from source content;
6. page-boundary joins against canonical `pages/`;
7. unusual Tamil forms against silent normalization;
8. recurring source-supported decisions in `GLOSSARY.md`;
9. progress/status documentation;
10. section status only after source-check and English review.

All eight planned batches passed their review records.

---

## 18. Final bilingual review

After all batches were complete, `TRANSLATION_REVIEW.md` checked end-to-end for:

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

**Result: PASSED.** One final English consistency correction changed scan-49 **Rathi → Rati**; no Tamil text changed.

---

## 19. Completed release gate under the verification freeze

Translation was permitted because the dedicated Tamil source-comparison audit was complete and the assembled Tamil layer had PASSED. The final bilingual review subsequently PASSED and established whole-work English **VERIFIED**.

`RELEASE_REPORT.md` was then created and the release-readiness/navigation/inventory checks PASSED.

Because the user-mandated canonical freeze still remains **0 `verified` / 49 `needs-review`**, the release report explicitly carries that qualification. English completion does not override it.

Final package wording:

> **English layer release-ready; archival package RELEASE-READY WITH CANONICAL-TAMIL VERIFICATION QUALIFICATION — 0 verified / 49 `needs-review`, freeze ACTIVE.**

---

## 20. Final completion state

**Tamil canonical coverage:** 49 / 49  
**Dedicated Tamil source comparison:** COMPLETE  
**Assembled Tamil:** PASSED  
**Canonical verification freeze:** ACTIVE — 0 verified / 49 `needs-review`  
**English translation plan:** COMPLETE / FULLY EXECUTED  
**English sections:** 7 / 7 reviewed  
**Translation batches:** 8 / 8 reviewed  
**Final bilingual review:** PASSED  
**Whole-work English:** VERIFIED  
**Release report:** COMPLETE  
**Release-readiness:** PASSED WITH CANONICAL-TAMIL VERIFICATION QUALIFICATION

There is **no remaining translation activity** for this source edition under the current instructions. Preserve the final glossary/review/release records and the canonical freeze. Reopen only if the user explicitly changes the freeze or asks to revisit source/translation evidence.