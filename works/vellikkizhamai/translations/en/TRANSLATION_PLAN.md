# English Translation Plan — வெள்ளிக்கிழமை

## 1. Objective

Create a clear, source-bound English translation of **மு. கருணாநிதியின் `வெள்ளிக்கிழமை`** from the audited 1968 second-edition Tamil preserved in this repository.

Working English title: **_Friday_**.

`வெள்ளிக்கிழமை` remains the authoritative archival title. `_Friday_` is a working English reading title, not a replacement bibliographic title.

The English must preserve narrative sequence, dialogue, emotional intensity, irony, humour, social criticism, religious/caste language, repetition, abrupt turns, source oddities and the 23-chapter structure without turning the novel into a modern adaptation.

## 2. Source-authority hierarchy

Translation follows this order:

1. controlling source scan — `TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf`, if a Tamil reading must ever be reopened;
2. canonical audited Tamil `../../pages/` records — controlling repository text for exact wording, punctuation, names, source oddities and provenance;
3. PASSED assembled Tamil `../../sections/` — continuous reading layer and verified page-boundary joins;
4. metadata/audit/page-map controls;
5. English translation — derived layer only.

If English review exposes a possible Tamil problem, stop translation at that point and reopen the source. Never silently repair Tamil through English. Do not translate from OCR, memory, an internet edition, a later edition or a normalized retelling.

## 3. English structure

The final English reading layer mirrors the 23 verified Tamil chapters one-to-one:

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

Create a chapter file only when that chapter is actually translated. Do not pre-create empty prose files.

## 4. Controlled batch map

| Batch | Chapters | Source coverage | Status |
|---|---:|---|---|
| **1 — pilot** | 1 | scans 4–12 | **REVIEWED / COMPLETE** |
| **2** | 2–4 | scan 13 → scan 45 before centered `5` | **REVIEWED / COMPLETE** |
| **3** | 5–7 | scan 45 after centered `5` → scan 68 before centered `8` | **NEXT / NOT STARTED** |
| 4 | 8–10 | scan 68 after centered `8` → scan 92 before centered `11` | planned |
| 5 | 11–13 | scan 92 after centered `11` → scan 115 before centered `14` | planned |
| 6 | 14–16 | scan 115 after centered `14` → scan 134 before centered `17` | planned |
| 7 | 17–19 | scan 134 after centered `17` → scan 154 before centered `20` | planned |
| 8 | 20–21 | scan 154 after centered `20` → scan 166 before centered `22` | planned |
| 9 | 22–23 | scan 166 after centered `22` → final narrative scan 179 | planned |

Default post-pilot batches cover at most three contiguous chapters. A larger batch requires explicit user authorization.

## 5. Pilot / style lock

Chapter 1 was the mandatory pilot and is **REVIEWED**. Its decisions remain controlling unless later source context requires a documented change.

Pilot lock includes:

- `_Friday_` / repeated **Friday** handling;
- readable but source-bound narration;
- standard English dialogue quotation marks;
- preservation of rhetorical questions, repetition and abrupt turns;
- source-scan comments and reversible join comments;
- source-bound treatment of religious/cultural terms and embedded Tiruppavai lines;
- no explanatory theology, folklore or modern social commentary inside prose.

`GLOSSARY.md` is the live consistency ledger for these choices.

## 6. Core translation principles

1. **No summarising.** Represent every substantive narrative paragraph, dialogue unit, quotation, verse unit, list and rhetorical question.
2. **Readable but source-bound English.** Reorder syntax only when necessary for intelligibility; do not add interpretation absent from Tamil.
3. **Preserve agency.** Do not change who acts, speaks, accuses, suffers, decides or knows something.
4. **Preserve force.** Anger, ridicule, shame, affection, melodrama, irony, accusation and repetition must not be softened.
5. **Do not intensify.** Do not make sexual, caste, religious, moral or violent language harsher or more categorical than the source.
6. **Do not beautify.** This is not a contemporary literary rewrite.
7. **Preserve source strangeness.** Verified awkwardness/discontinuity is not permission to invent the presumed intended Tamil.
8. **No modern explanations inside prose.** Necessary consistency/context belongs in `GLOSSARY.md` or a clearly marked translator note.
9. **Keep chapter alignment exact.** English Chapter N corresponds only to Tamil Chapter N.
10. **Auditability over smoothness.** When fidelity and elegance conflict, preserve fidelity and document the issue.

## 7. Names, transliteration and shortened forms

Use stable readable romanization without diacritics unless an established English form is clearly preferable. Preserve source distinctions between full and shortened/familiar names.

Locked examples after Batches 1–2 include:

- Chintamani;
- Azhagappan / Azhagu;
- Naina Muhammad / Naina;
- Anandi;
- Sivanesar;
- Sivakami;
- Tiger;
- Vembu;
- Balagangadhara Thevar;
- Vedapuram;
- Bangalore.

The full live table is in `GLOSSARY.md`. English name choices never authorize changes to canonical Tamil.

## 8. Religious, caste, sexual-stigma and socially charged language

Translate charged language as the source narrator's or character's rhetoric.

- do not censor or euphemize;
- do not intensify;
- do not add present-day approval/disapproval;
- distinguish source voice from modern editorial voice by simply not adding editorial voice to the prose;
- preserve explicit religious difference and astrological/ritual humour;
- preserve historically loaded chastity/sexual-stigma language at its source force and document recurring choices in `GLOSSARY.md`.

Chapter 3 establishes specific handling for `கற்பு`, forced violation, `பாப விமோசனம்`, `பிராயச்சித்தம்` and related rhetoric. These renderings are source-fidelity decisions, not endorsement of the source's social assumptions.

## 9. Culture-specific, ritual and period terms

Use a direct English equivalent when it does not distort meaning. Retain a readable transliteration when a specifically Tamil/Indian object, institution, ritual term or period term would be flattened by a loose substitute.

Locked/established examples include:

- kolam;
- mangalyam;
- kumkum;
- Tiruppavai;
- yaazh;
- kuduguduppai;
- paladai;
- kendi;
- gosha;
- panchangam;
- dosha;
- sastras.

Use `GLOSSARY.md` for first-use and consistency decisions rather than inserting essays into translated prose.

## 10. Dialogue, punctuation and paragraph policy

1. Spoken dialogue uses standard English double quotation marks.
2. Quotations inside speech use single quotation marks.
3. Do not invent speaker labels.
4. Preserve source paragraph units unless English grammar requires only a minimal split.
5. Preserve rhetorical ellipses, repeated exclamation and abrupt fragments in force; exact historical dot counts need not be reproduced mechanically.
6. Never silently complete a source-boundary fragment that audited Tamil leaves incomplete.
7. Preserve visually distinct songs/verses/quoted units as distinct Markdown blocks.
8. Chapter headings remain simple numbered headings matching Tamil structure.

## 11. Source oddities and discontinuities

The PASSED Tamil layer deliberately preserves physical discontinuities that English must not repair by inference.

Known whole-work examples:

- scan 117→118: `உட்` → `எவ்வளவோ முயன்றும் நடக்கவில்லை.`;
- scan 122→123: `...அவளுக்குப் பக்கத்திலே` → `கார்ந்து கொண்டாள்.`;
- scan 156→157: `தலையிலும் காயம்` → `நயினா எதிர்த்தே அடிக்கவில்லை.`.

Preserve the supported abruptness/uncertainty, retain provenance, and reopen the controlling scan if a later translation review genuinely raises doubt about Tamil.

Printed-page anomalies are also preserved. Scan 66 visibly prints only `5`; English provenance must never silently infer printed page 65.

## 12. Page/source traceability

Each English chapter file includes front matter with work, chapter, language, translation status, batch, source section, source scans and canonical source.

Retain unobtrusive HTML comments at meaningful scan boundaries and verified cross-page joins, for example:

```html
<!-- source: scan 45; printed page: 44; Chapter 4 before centered 5 -->
```

```html
<!-- source join: scan X fragment → scan Y continuation -->
```

Mixed chapter-boundary scans must be split only at the source-printed centered heading.

## 13. Glossary policy

`GLOSSARY.md` is a controlled consistency ledger, not a dictionary. Record recurring names, shortened forms, places, religious/caste/social terms, period terms, source metaphors/wordplay, difficult source forms and any later change in an earlier English decision.

Do not populate it speculatively. Lock entries when reviewed source context supports them.

## 14. Review statuses and per-batch gate

Statuses:

- `planned`;
- `draft-translated`;
- `source-checked`;
- `reviewed`;
- whole-work `verified` only after final bilingual review.

For each batch:

1. translate only PASSED Tamil;
2. create only files in the authorized batch;
3. preserve provenance;
4. source-check against canonical authority;
5. verify names, numbers, places, relationships, quoted wording and agency;
6. verify rhetoric, humour, insults, emotional force and charged language;
7. verify joins and mixed chapter-boundary scans;
8. ensure no source oddity was silently repaired;
9. update glossary and progress/status controls;
10. commit the bounded batch before starting another.

## 15. Final bilingual review and release

After all 23 chapters are `reviewed`, complete `TRANSLATION_REVIEW.md` for coverage/order, omissions/duplications, additions, agency, names, charged terminology, rhetoric, dialogue, boundaries, discontinuities, provenance and readability without modernization.

Only after that review passes may whole-work English be called **verified**.

Then complete `RELEASE_REPORT.md`, confirming Tamil authority, 23/23 reviewed English chapters, glossary consistency, navigation, no unauthorized Tamil changes, source-PDF exclusion, and archival/editorial release readiness separate from copyright/licensing questions.

## 16. Current status / exact next activity

**Tamil canonical source:** PASSED  
**Tamil assembled reading layer:** PASSED  
**English translation plan:** COMPLETE  
**English chapters reviewed:** **4 / 23**  
**English coverage:** **scan 4 through scan 45 before centered `5`**  
**Whole-work English:** NOT VERIFIED

### Next

Run **Batch 3 — Chapters 5–7**:

- `sections/05-chapter-05.md` — scan 45 after centered `5` through scan 51;
- `sections/06-chapter-06.md` — scan 52 through scan 59 before centered `7`;
- `sections/07-chapter-07.md` — scan 59 after centered `7` through scan 68 before centered `8`.

Translate, source-check, review, synchronize and commit those three chapters only. **Do not start Chapter 8 in the same default iteration.**