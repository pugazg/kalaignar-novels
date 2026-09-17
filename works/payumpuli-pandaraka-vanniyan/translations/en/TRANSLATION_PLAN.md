# English Translation Plan — பாயும்புலி பண்டாரக வன்னியன் / Part001

Status: **E4 SOURCE-CHECKED / COMPLETE — 8/8 ENGLISH COMPLETE — GLOSSARY RECONCILIATION NEXT**

This is the control plan for the project-created English translation of **Part001 only**.

## Authority hierarchy

1. `works/payumpuli-pandaraka-vanniyan/pages/` — canonical audited Tamil; controlling authority.
2. `works/payumpuli-pandaraka-vanniyan/sections/` — **PASSED / CLOSED** assembled Tamil reading layer.
3. `works/payumpuli-pandaraka-vanniyan/translations/en/` — derived project-created English only.

If English conflicts with canonical Tamil, Tamil governs.

English work must never silently correct, regularize, modernize, fact-correct or rewrite the Tamil source layer.

## Translation objective

Produce readable English that remains reversible to the verified Part001 Tamil evidence.

Preserve:

- speaker and narrator agency;
- chronology and knowledge state;
- rhetorical questions, repetition, exclamations, irony and emphatic phrasing;
- paragraph/dialogue/display structure where meaningful;
- source-visible section/chapter structure;
- source-specific names, titles, offices and place names;
- historical and political framing as presented by the source;
- source quotations and verse without importing a published/standard English wording;
- the open Part001 ending at scan30.

Do not add explanatory history, geography, biography or literary interpretation inside translation prose unless the Tamil source itself supplies it.

## Source-structure rules

Part001 assembled Tamil contains **8 verified section files**:

1. `00-front-matter.md` — scans1–5
2. `01-anindurai.md` — scans6–9
3. `02-pathippurai.md` — scan10
4. `03-epigraph.md` — scan11
5. `04-title-divider.md` — scan12
6. `05-thorana-vayil.md` — scans13–20
7. `06-oru-iragasiyak-kaditham.md` — scans21–27
8. `07-vazhiyil-kanda-vayothigar.md` — scans28–30

English must preserve this Part-level order.

Front matter, foreword, publisher's note, epigraph and printed divider text are part of Part001 translation coverage. Visual-only material already excluded from the assembled Tamil layer is not invented as prose.

## Names and romanization

The initial glossary uses conservative project romanizations derived from the Tamil text itself.

Rules:

- keep personal names as names; do not translate their lexical meanings unless the source explicitly makes a wordplay;
- keep source honorifics/titles where they matter to speaker stance;
- use one locked romanization once a glossary form is adopted;
- do not silently replace a source-facing romanization with a web/official/modern spelling during drafting;
- any later romanization change must be recorded through glossary reconciliation and must not modify canonical Tamil.

## Titles, offices and kinship

Translate ordinary functional labels when their source meaning is clear, while preserving named titles/epithets where translation would erase identity.

Examples of source-derived categories include:

- `அணிந்துரை` — **Foreword**;
- `பதிப்புரை` — **Publisher's Note**;
- `பாளையக்கார மன்னர்கள்` — render functionally, with `palaiyakkarar` available where the historical office itself matters;
- `கலெக்டர் பதவிக்கு இணையான அரசப் பதவி` — preserve the source's own “equivalent to Collector” comparison rather than adding a modern administrative explanation.

No outside historical-office taxonomy is introduced by this plan.

## Place names

Use consistent source-facing romanizations from the project glossary.

Do not add modern jurisdictional or political descriptions that are absent from the Part001 Tamil.

Where the Tamil source itself uses `இலங்கை`, translate the country reference as **Sri Lanka**; this is a translation choice, not an external historical annotation.

## Culture-specific vocabulary

For culture-specific terms:

1. translate directly where the source meaning is unambiguous and ordinary;
2. retain a source-facing transliteration where a forced English equivalent could add or remove meaning;
3. give only a minimal in-text gloss when needed for comprehension;
4. do not add encyclopedia-style explanation to narrative prose;
5. lock recurring choices in `GLOSSARY.md`.

## Quotations, songs and verse

Part001 contains an epigraph, quoted speeches, a folk-song passage and other displayed source material.

Rules:

- preserve block/line structure where meaningful;
- translate from the verified project Tamil only;
- do not import remembered, published or web English versions;
- if a line cannot be translated securely from the project Tamil alone, retain the Tamil temporarily in the English draft, mark a translation hold, and resolve it through the source-check/glossary-review chain rather than guessing;
- quoted political/historical claims remain attributed to the source speaker or narrator and are not converted into project assertions.

## Source oddities and source framing

Preserve, do not silently reconcile:

- source-specific spellings and names already locked by Tamil verification;
- the source's own chronology and historical assertions;
- rhetoric about freedom, rule, sovereignty, colonial power and armed resistance as source framing;
- source quotation boundaries;
- unusual punctuation or abrupt rhetorical transitions when they carry tone;
- Part001's structurally incomplete chapter ending.

English may improve sentence flow only where the meaning, agency and rhetorical force remain unchanged.

## Paragraph, dialogue and display structure

- preserve paragraph order;
- preserve dialogue speaker order and question/answer structure;
- retain meaningful displayed verse/list blocks;
- do not collapse distinct source paragraphs merely for smoother English;
- do not invent headings;
- assembled Tamil provenance comments may be carried into English as non-rendering HTML comments where useful for reversibility.

## Provenance-comment policy

English section files should carry:

- source Tamil section reference;
- source scan range;
- source-facing section title;
- non-rendering boundary comments at meaningful physical joins when needed to keep translation reversible.

Provenance comments are metadata, not translation prose.

## Part001 terminal-boundary rule

This rule is absolute:

- scan30 / printed19 is the final Part001 source page;
- scan30 ends `அவனுக்கு ஒரே மகிழ்ச்சி,`;
- **30→31 = GENUINE CONTINUATION**;
- scan31 belongs to Part002 and is only a boundary witness;
- do not import or translate scan31 in Part001;
- do not invent a completion for the open sentence;
- Part001 English must end in a way that visibly preserves the incomplete source continuation.

## Batch plan

Batches follow the already-verified Tamil section boundaries.

| Batch | Tamil assembled coverage | Scans | English state |
|---|---|---:|---|
| **E1** | sections 00–04: front matter + `அணிந்துரை` + `பதிப்புரை` + epigraph + title divider | **1–12** | **SOURCE-CHECKED / COMPLETE** |
| **E2** | section 05: `தோரண வாயில்` | **13–20** | **SOURCE-CHECKED / COMPLETE** |
| **E3** | section 06: `ஒரு இரகசியக் கடிதம்!` | **21–27** | **SOURCE-CHECKED / COMPLETE** |
| **E4** | section 07: `வழியில் கண்ட வயோதிகர்!` | **28–30** | **SOURCE-CHECKED / COMPLETE** |

Each batch must complete its draft and source-check before the next batch becomes active.

## Per-batch source-check gates

Every English batch must pass:

1. coverage/order check;
2. paragraph/display-structure check;
3. source-meaning and agency check;
4. dialogue/register check;
5. names/place/title consistency check;
6. quotation/verse check;
7. provenance/boundary check;
8. source-oddity preservation check;
9. no unsupported explanatory insertion;
10. no-silent-Tamil-change check.

A batch is not closed merely because English prose exists.

## Glossary reconciliation gate

After E1–E4 are drafted and source-checked:

- reconcile all recurring names, places, titles, offices and culture-specific terms;
- identify accidental romanization variants;
- reconcile only the English layer;
- do not modify canonical Tamil to make English consistency easier;
- record every intentional source-facing retention.

## Editorial review gate

After glossary reconciliation:

- improve readability without changing source meaning, agency, chronology or rhetoric;
- preserve source section structure and open Part boundary;
- reject smoothing that silently resolves a source ambiguity or contradiction.

## Whole-Part bilingual review

Before release/readiness:

- verify all 8 Tamil assembled sections are represented in English;
- verify scan coverage remains **1–30 only**;
- verify no Part002 content appears;
- verify quotations, verse and dialogue remain aligned;
- verify unresolved English holds = **0**;
- verify canonical Tamil changes caused by English = **0**.

## Release/readiness gate

Create the maintained release/readiness report only after the whole-Part bilingual review passes.

It must confirm:

- Tamil/English coverage;
- bilingual alignment;
- glossary consistency;
- unresolved items;
- navigation/provenance;
- Part001 terminal boundary;
- source-PDF exclusion from Git;
- canonical Tamil unchanged.

## Final rule

English is always a derived project translation.

It cannot authorize a canonical Tamil correction.

A genuine Tamil-fidelity issue discovered during English work must be recorded and routed back through an explicit Tamil reopening decision rather than silently fixed through translation.

## E1 closure

E1 — sections00–04 / scans1–12 — is **SOURCE-CHECKED / COMPLETE** with **0 unresolved holds** and **0 canonical Tamil edits**.

Detailed closure: `E1_SOURCE_CHECK.md`.

## E2 closure

E2 — `தோரண வாயில்` / scans13–20 — is **SOURCE-CHECKED / COMPLETE** with **0 unresolved holds** and **0 canonical Tamil edits**.

Detailed closure: `E2_SOURCE_CHECK.md`.

## E3 closure

E3 — `ஒரு இரகசியக் கடிதம்!` / scans21–27 — is **SOURCE-CHECKED / COMPLETE** with **0 unresolved holds** and **0 canonical Tamil edits**.

Detailed closure: `E3_SOURCE_CHECK.md`.

## E4 closure

E4 — `வழியில் கண்ட வயோதிகர்!` / scans28–30 — is **SOURCE-CHECKED / COMPLETE** with **0 unresolved holds** and **0 canonical Tamil edits**.

The open scan30 fragment is preserved and scan31 is not imported.

Part001 English draft + per-batch source-check coverage is **8/8 COMPLETE**.

Detailed closure: `E4_SOURCE_CHECK.md`.

## Exact next activity

**Whole-Part English glossary reconciliation** across E1–E4 / scans1–30.

Do not begin editorial review until glossary reconciliation closes.
