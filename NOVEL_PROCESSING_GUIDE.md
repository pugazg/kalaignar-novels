# Novel / Story Processing Guide

இந்த repository-யில் கலைஞர் மு. கருணாநிதியின் புதினங்கள், வரலாற்றுக் கதைகள் மற்றும் தொடர்புடைய கதைநூல்களை ஒரே மாதிரியான **source-first archival workflow** மூலம் மின்னாக்குவதற்கான நிரந்தர வழிகாட்டி.

இந்த guide-ன் completed reference implementation:

`works/balipeedam-nokki/`

அந்த work-ன் structure, audit, assembled Tamil layer, English translation, bilingual review மற்றும் release report ஆகியவை புதிய work-களுக்கான model ஆக பயன்படுத்தலாம். ஆனால் புதிய source-ன் structure-ஐ reference work-க்கு force-fit செய்யக்கூடாது.

---

# 1. அடிப்படை விதி — source authority

> **மூல ஸ்கேன் தான் controlling source.**

Repository Markdown என்பது source preservation layer; அது silently corrected / modernized / reconstructed edition அல்ல.

Authority order:

1. actual source-page scan;
2. source-ல் அச்சிடப்பட்ட title / contents / publication / page numbering;
3. canonical Tamil `pages/` records;
4. assembled Tamil `sections/`;
5. English translation;
6. metadata / glossary / review notes.

ஒரு lower layer மேலுள்ள source authority-க்கு முரணானால் மேலுள்ள source தான் governing text.

## அமைதியாக செய்யக் கூடாதவை

- “பிழை” என்று தோன்றும் source spelling-ஐ திருத்துதல்;
- பழைய எழுத்து, சொல், sandhi, grammar ஆகியவற்றை modernize செய்தல்;
- punctuation, பெயர்கள், எண்கள், dates, titles standardize செய்தல்;
- இணையம், memory, later edition அல்லது historical knowledge கொண்டு source wording-ஐ மாற்றுதல்;
- unclear characters-ஐ sentence meaning வைத்து guess செய்தல்;
- source-ல் இல்லாத chapter / scene / speaker heading body text-க்குள் silently சேர்த்தல்;
- repeated words, unusual grammar, typographical forms, odd punctuation ஆகியவற்றை “improve” செய்தல்.

Source தவறாகத் தோன்றினாலும் canonical transcription source-ஐ faithfully preserve செய்ய வேண்டும்; editorial note வேண்டுமானால் source text-க்கு வெளியே தனியாக பதிவு செய்யலாம்.

---

# 2. Mandatory startup for every new novel/story

புதிய PDF கிடைத்ததும் transcription தொடங்குவதற்கு முன்:

1. repository root `README.md` படிக்கவும்;
2. இந்த `NOVEL_PROCESSING_GUIDE.md` முழுவதும் படிக்கவும்;
3. root `HANDOVER.md` படிக்கவும்;
4. `works/balipeedam-nokki/` completed reference implementation-ஐ structure reference ஆக மட்டும் ஆய்வு செய்யவும்;
5. repository-யை inspect செய்து target work ஏற்கனவே தொடங்கியுள்ளதா என்று உறுதி செய்யவும்;
6. work ஏற்கனவே இருந்தால் புதிய duplicate directory உருவாக்காமல் அதையே தொடரவும்;
7. attached PDF-ஐ actual scan pages மூலம் inspect செய்யவும்;
8. **filename-ஐ மட்டும் நம்பி title, edition, year, work identity அல்லது page structure தீர்மானிக்க வேண்டாம்**;
9. internal title-card / story-title / film-title போன்றவை source-ன் main work-இலிருந்து தனி work என உடனே கருத வேண்டாம் — surrounding narrative flow முதலில் ஆய்வு செய்ய வேண்டும்;
10. source PDF-ஐ repository-க்கு upload/commit செய்யக்கூடாது.

---

# 3. Source PDF policy

Source PDF repository-க்குள் commit செய்யப்படாது.

ஒவ்வொரு source-க்கும் `metadata/source.md`-ல் குறைந்தது பின்வரும் விவரங்கள் பதிவு செய்ய வேண்டும்:

- source filename;
- SHA-256 checksum;
- file size;
- scan page count;
- title as printed;
- author as printed;
- publisher / place as printed;
- edition / date / price / printer போன்ற visible bibliographic details;
- printed-page numbering behaviour;
- missing / repeated / unnumbered printed pages;
- scan condition;
- library stamps / accession marks;
- handwriting / underlining / later annotation;
- bleed-through / damage / scanner artefacts;
- cover / illustration / blank-page observations.

Metadata உருவாக்கும் முன் relevant source scan pages நேரடியாகப் பார்க்க வேண்டும்.

---

# 4. Recommended work structure

ஒவ்வொரு புதிய work-க்கும்:

```text
works/<work-slug>/
  README.md
  metadata/
    source.md
  indexes/
    page-map.md
  pages/
    0001-....md
  audit.md
  sections/
    README.md
    01-....md
    02-....md
```

English translation gate திறந்த பின்:

```text
  translations/
    en/
      README.md
      TRANSLATION_PLAN.md
      PROGRESS.md
      GLOSSARY.md
      TRANSLATION_REVIEW.md
      RELEASE_REPORT.md
      sections/
        01-....md
        02-....md
```

Repository-level continuation files:

```text
HANDOVER.md
NEXT_NOVEL_CHAT_PROMPT.md
```

Structure source-க்கு ஏற்ப adapt செய்யலாம். தேவையில்லாத artificial chapters உருவாக்க வேண்டாம்.

---

# 5. Page-level archival record — every scan page is mandatory

ஒவ்வொரு scan page-க்கும் Markdown record இருக்க வேண்டும் — cover, blank, title page, publication note, contents, body text, illustration, advert, back cover அனைத்தும் உட்பட.

Example front matter:

```yaml
---
scan_page: 1
printed_page: null
work: "<work-slug>"
section: "front-matter"
page_type: "cover"
status: "verified"
language: "ta"
source_filename: "<source>.pdf"
transcription_method: "direct visual comparison with source scan"
---
```

## Required distinction

- `scan_page` = PDF scan order;
- `printed_page` = page number visibly printed on the source page;
- printed number தெரியாவிட்டால் / இல்லாவிட்டால் `null`; neighboring pages வைத்து silently infer செய்யக்கூடாது.

## Suggested page types

- `cover`
- `title-page`
- `publisher-note`
- `contents`
- `body`
- `illustration`
- `advertisement`
- `blank`
- `back-matter`

## Status values

- `not-started`
- `partial`
- `needs-review`
- `verified`
- `blocked`

`verified` என்பது direct visual scan comparison முடிந்த பின்னரே பயன்படுத்த வேண்டும்.

---

# 6. Printed text vs non-text marks

கீழ்கண்டவற்றை ஒரே body text ஆகக் கலக்கக்கூடாது:

- printed text;
- library stamp;
- accession number;
- handwriting;
- underline / circle / marginal mark;
- bleed-through;
- scanner artefact;
- photograph / illustration / ornament / cover artwork.

Non-text marks source-ல் இருந்தால் separate note அல்லது clearly labeled visual observation ஆக பதிவு செய்யவும்.

Unclear handwriting-ஐ guess செய்ய வேண்டாம்.

---

# 7. Direct visual transcription policy

Primary method: **direct visual inspection of source scan**.

OCR is not the authority. OCR பயன்படுத்தினாலும் அது discovery aid மட்டுமே; source scan comparison இன்றி OCR reading-ஐ `verified` என்று mark செய்யக்கூடாது.

Particularly difficult words:

1. enlarged source crop பார்க்கவும்;
2. character-by-character compare செய்யவும்;
3. certainty இல்லையெனில் `needs-review` வைத்திருக்கவும்;
4. contextual guess-ஐ canonical Tamil-ல் silently insert செய்ய வேண்டாம்;
5. later review resolution-ஐ audit / glossary / review document-ல் record செய்யவும்.

---

# 8. Fiction / historical prose / cinematic prose rules

- source paragraph boundaries preserve செய்யவும்;
- dialogue punctuation / quote style preserve செய்யவும்;
- dialogue speaker source-ல் explicit இல்லாவிட்டால் unnecessary speaker labels invent செய்ய வேண்டாம்;
- screenplay-like notation, cinematic directions, stage directions, title cards, sound effects ஆகியவை prose-ஆக flatten செய்யக்கூடாது;
- source cinematic vocabulary (`டைரக்ஷன்`, `திரைக்கதை`, `வசனம்`, `குளோசப்`, etc.) preserve செய்யவும்;
- song / verse / slogan / signboard / on-screen text தனித்த visual unit என இருந்தால் Markdown-ல் distinct ஆக வைத்திருக்கவும்;
- historical spelling / title / office / place-name source-ஐத் தாண்டி standardize செய்ய வேண்டாம்.

## Internal text vs separate work

ஒரு publication-ல் புதிய heading தோன்றினாலே அது separate work அல்ல.

முதலில் examine செய்ய வேண்டியது:

- preceding narrator transition;
- following return-to-frame text;
- title-card vocabulary;
- section continuity;
- source publication identity.

If the source clearly frames the unit as an embedded story, play, film, dream, letter, speech, quotation or historical episode, preserve it as an **internal section of the main work** unless source evidence establishes a distinct bibliographic work.

`பலிபீடம் நோக்கி`-யில் `ராயசம் வெங்கண்ணு — தஞ்சை சரித்திரக் கதை` internal cinematic sequence என்று தீர்மானிக்கப்பட்டது — இது structural reasoning-க்கு reference example மட்டுமே.

---

# 9. Page map

`indexes/page-map.md` source manifest ஆக இருக்க வேண்டும்.

ஒவ்வொரு scan-க்கும்:

- scan page;
- visible printed page;
- page type;
- work / section;
- transcription status;
- short note where useful.

Page map தான் coverage gaps, duplicate records, numbering mistakes கண்டுபிடிக்க primary checklist.

---

# 10. Batch workflow — Tamil source layer

Recommended sequence:

1. inspect repository and source;
2. register source metadata;
3. build initial page map;
4. create front matter page records;
5. transcribe body in small batches;
6. update page map after each batch;
7. mark uncertain pages `needs-review`;
8. maintain work README current status;
9. update root `HANDOVER.md` with exact next action;
10. after full coverage, perform targeted character-level review of all uncertain pages;
11. perform complete page/metadata/continuity audit;
12. only then mark Tamil source layer `PASSED`.

## Narrow commits

Prefer small descriptive commits such as:

- `Register source metadata for <work>`
- `Transcribe scans 8-12 of <work>`
- `Resolve scan 21 source reading`
- `Complete Tamil source audit for <work>`

Large mixed commits should be avoided when practical.

---

# 11. Source-page markers and cross-page joins

Canonical page records must retain page provenance.

Example:

```html
<!-- மூல ஸ்கேன் பக்கம்: 12; அச்சுப் பக்கம்: 11 -->
```

A word/sentence split across pages must remain source-traceable.

In the canonical `pages/` layer, preserve each page's actual text. In an assembled reading layer, verified cross-page fragments may be joined for readability **only if** provenance remains reversible via comments/markers.

Example:

```html
<!-- source join: scan 19 ends `பாது`; scan 20 begins `காத்துக்கொள்` -->
```

---

# 12. Tamil audit gate

Tamil transcription complete என்பது translation-ready என்பதல்ல.

Translation தொடங்குவதற்கு முன்:

- all scan pages have records;
- page map has no coverage gap;
- body pages direct visually audited;
- all `needs-review` items resolved or explicitly documented;
- metadata matches source;
- printed-page mapping is source-supported;
- cross-page continuities checked;
- internal structural units correctly identified;
- no silent modernization/correction found;
- source PDF still excluded from repository;
- `audit.md` states result clearly.

Only after this gate passes may translation planning begin.

---

# 13. Assembled Tamil reading layer

After canonical page-level Tamil passes audit, create `sections/` for readable continuity.

Rules:

- derive only from audited `pages/` records;
- do not re-transcribe independently;
- do not modernize spelling/punctuation;
- preserve important title cards / cinematic markers / verse structure;
- source-page boundaries remain traceable via comments;
- section split should follow actual narrative structure;
- internal sequence must not become a false separate work.

`sections/README.md` must explain:

- derivation source;
- section ranges;
- any verified cross-page joins;
- structural interpretation;
- authority relationship to `pages/`.

After its own consistency check, mark assembled Tamil layer `PASSED`.

---

# 14. English translation plan — mandatory before translation prose

Create:

`translations/en/TRANSLATION_PLAN.md`

The plan should define:

- working English title;
- source authority hierarchy;
- section / batch plan;
- translation style;
- name/transliteration policy;
- political / religious / caste terminology policy;
- handling of historical offices / ritual terms;
- cinematic vocabulary;
- punctuation / dialogue policy;
- source oddity policy;
- page traceability;
- review states and gates.

Do not begin prose translation until this plan exists.

---

# 15. Controlled English translation workflow

Maintain:

- `translations/en/README.md`
- `translations/en/PROGRESS.md`
- `translations/en/GLOSSARY.md`
- `translations/en/sections/*.md`

Recommended statuses:

- `draft-translated`
- `source-checked`
- `reviewed`
- whole-work `verified`

Translate in controlled batches. For each batch:

1. translate only audited Tamil source;
2. preserve rhetoric, agency, dialogue, repetition and structural form;
3. source-check the English back against canonical Tamil pages;
4. document unusual source forms;
5. update glossary decisions;
6. mark batch `reviewed` only after source comparison;
7. do not call whole-work translation `verified` until final bilingual review.

## Translation principle

English should be readable but source-bound.

Do not:

- soften political/religious/caste rhetoric;
- intensify it beyond source;
- add modern explanations inside translated prose;
- convert metaphors into asserted historical facts;
- invent meanings for unclear words;
- erase source strangeness merely to make English smoother.

When lexical force is uncertain, conservative transliteration or cautious contextual rendering is preferable, with documentation in `GLOSSARY.md`.

---

# 16. Final bilingual review gate

After all English batches are `reviewed`, create:

`translations/en/TRANSLATION_REVIEW.md`

Whole-work review must explicitly check:

- complete coverage;
- ordering;
- no duplicate span;
- no material omission;
- no source-like addition;
- speaker attribution;
- agency/responsibility;
- recurring names and titles;
- recurring terminology;
- political/religious/caste rhetorical force;
- cinematic directions / screen text / sound effects;
- cross-page joins;
- section boundaries;
- source-specific difficult readings;
- internal-vs-separate-work identity.

Only after this review passes may English be called **whole-work `verified`**.

---

# 17. Release-readiness gate

After whole-work English verification, create:

`translations/en/RELEASE_REPORT.md`

Release report should record:

- work identity;
- source edition identity;
- Tamil page inventory;
- Tamil assembled-section inventory;
- English section inventory;
- Tamil audit result;
- bilingual review result;
- reader-facing navigation check;
- authority hierarchy;
- structural identity;
- documented source oddities;
- confirmation canonical Tamil was not changed during release pass;
- confirmation no source PDF is committed;
- non-blocking editorial limitations;
- final release-ready / not-ready verdict.

**Release-ready is an archival/editorial verdict only.** It is not automatically a copyright, licensing, commercial republication or public-domain determination.

---

# 18. README synchronization

At major gates update:

- root `README.md`;
- `works/<work>/README.md`;
- `translations/en/README.md` when applicable;
- `PROGRESS.md`;
- root `HANDOVER.md`.

Status claims must agree across files.

Never leave one README saying “pending” after another file says “verified”.

---

# 19. Handover requirements

`HANDOVER.md` should always contain:

- repository and branch;
- mandatory startup instructions;
- current target work;
- source filename / checksum / page count;
- current stage;
- completed artifacts;
- unresolved readings/issues;
- structural notes;
- translation/release status if applicable;
- exact next action;
- explicit reminder that source PDF is not committed.

When a work is finished, retain it as a completed reference implementation and switch `Current exact next action` to onboarding the next source.

---

# 20. New-chat continuation prompt

For a fresh ChatGPT conversation, use root:

`NEXT_NOVEL_CHAT_PROMPT.md`

The prompt must be used together with the newly attached source PDF.

The new chat must not assume the filename is authoritative, must inspect the repository before creating a work directory, and must begin at source registration rather than jumping directly into transcription or translation.

---

# 21. Definition of done for one source edition

A source edition is fully complete only when applicable stages are finished:

```text
source registration
→ page map
→ page-level Tamil transcription
→ targeted source review
→ full Tamil audit
→ assembled Tamil reading layer
→ English translation plan
→ controlled English translation batches
→ whole-work bilingual review
→ release-readiness report
```

For a Tamil-only project, English stages may be intentionally skipped, but that decision must be explicit.

For the completed reference `பலிபீடம் நோக்கி`, all stages above have passed.

---

# 22. Final preservation principle

> **Do not make the archive cleaner by making the source less true.**

Unusual spelling, old punctuation, awkward grammar, repetition, unexplained terms and source-specific anomalies are part of the archival record when the scan supports them.

Readable derived layers may help the reader, but provenance must always lead back to the audited Tamil page records.