# Towards the Sacrificial Altar — Final Release Report

## Release identity

- Tamil work: **`பலிபீடம் நோக்கி`**
- Author: **மு. கருணாநிதி**
- Working English title: **_Towards the Sacrificial Altar_**
- Source edition: **First edition, April 1947**
- Publisher visible in source: **எரிமலைப் பதிப்பகம், துறையூர்**
- Source scan: **34 pages**
- English body-text coverage: **scans 4–33**
- Source PDF committed to repository: **No**

This release report records the editorial and archival readiness of the verified Tamil + English package in this repository. It does not change the authority of the audited Tamil source layer.

## Completion status

| Stage | Result |
|---|---|
| Source registration | **Complete** |
| Tamil scan-page records | **34 / 34** |
| Tamil page-level verification | **34 / 34 verified** |
| Tamil source audit | **PASSED** |
| Assembled Tamil reading layer | **PASSED** |
| English translation plan | **Complete** |
| English translation batches | **6 / 6 reviewed** |
| English body-text coverage | **scans 4–33 complete** |
| Final bilingual alignment | **PASSED** |
| Whole-work English translation | **VERIFIED** |
| Release-readiness pass | **PASSED** |
| Canonical Tamil changed during release pass | **0** |
| Source PDF present in repository | **No** |

## Release contents

### Canonical Tamil preservation layer

- [`../../metadata/source.md`](../../metadata/source.md) — source identity, bibliographic details and scan observations
- [`../../indexes/page-map.md`](../../indexes/page-map.md) — scan/printed-page manifest
- [`../../audit.md`](../../audit.md) — completed Tamil transcription and assembly audit
- [`../../pages/`](../../pages/) — **34 verified scan-page records**, including cover, front matter, body and blank/back matter

The `pages/` layer is the controlling archival text.

### Assembled Tamil reading layer

- [`../../sections/README.md`](../../sections/README.md) — assembly policy and section map
- [`../../sections/01-opening-frame.md`](../../sections/01-opening-frame.md) — scans 4–7
- [`../../sections/02-rayasam-vengannu-sequence.md`](../../sections/02-rayasam-vengannu-sequence.md) — scans 8–29 + scan 30 through the internal-film `வணக்கம்` end-card
- [`../../sections/03-return-and-conclusion.md`](../../sections/03-return-and-conclusion.md) — scan 30 from `படம் முடிந்துவிட்டது...` through scan 33

This layer is derived for continuous reading. It does not supersede the page-level Tamil records.

### Verified English layer

- [`README.md`](README.md) — reader-facing English access point
- [`TRANSLATION_PLAN.md`](TRANSLATION_PLAN.md) — translation policy and source hierarchy
- [`PROGRESS.md`](PROGRESS.md) — batch history and verification state
- [`GLOSSARY.md`](GLOSSARY.md) — recurring terminology and source-oddity decisions
- [`TRANSLATION_REVIEW.md`](TRANSLATION_REVIEW.md) — final whole-work bilingual alignment review
- [`sections/01-opening-frame.md`](sections/01-opening-frame.md) — opening frame
- [`sections/02-rayasam-vengannu-sequence.md`](sections/02-rayasam-vengannu-sequence.md) — complete internal cinematic sequence
- [`sections/03-return-and-conclusion.md`](sections/03-return-and-conclusion.md) — return and conclusion

## Reader-facing navigation check — PASS

The repository paths referenced from the root README, work README and English README were checked against the current repository tree.

Verified navigation:

1. root `README.md` → `works/balipeedam-nokki/README.md`;
2. work README → Tamil audit, assembled Tamil sections and English translation entry point;
3. English README → all three English reading sections, glossary, progress and final translation review;
4. section 2 stops at the internal film's `வணக்கம்` end-card;
5. section 3 begins exactly at `படம் முடிந்துவிட்டது. பாடம் கற்றுக்கொண்டீர்களா?`;
6. no source text is duplicated at the scan-30 split.

**Navigation result: PASS.**

## Authority hierarchy

For every future correction, reuse or derived edition, authority remains:

1. **audited Tamil `pages/` records** — controlling text;
2. **assembled Tamil `sections/`** — verified reading layer derived from the page records;
3. **verified English translation** — source-bound translation, not a replacement for Tamil;
4. metadata/review files — documentation of provenance, decisions and status.

If a derived English or Tamil reading conflicts with a canonical page record, the page record governs unless a new direct source audit first establishes a documented correction.

## Structural identity — PASS

`பலிபீடம் நோக்கி` is released as **one continuous work**.

The source-printed **`ராயசம் வெங்கண்ணு — தஞ்சை சரித்திரக் கதை`** remains an **internal cinematic-historical sequence**. It is not released as a separate work, translation project or bibliographic identity.

The verified structure remains:

```text
பலிபீடம் நோக்கி
├── opening frame
├── internal cinematic-historical sequence: ராயசம் வெங்கண்ணு
└── return to frame / conclusion
```

## Source-fidelity and editorial policy

The release preserves the source's historical spelling, punctuation, unusual grammar, source-specific names, repetitions, cinematic directions, dialogue, screen text, sound effects and polemical force.

Difficult verified forms are documented rather than silently repaired. Examples include *mitthanamathan*, *kilathirukkirathu*, *thegidu thaththakkar*, *Tharppakurar*, *Pulikkir veera*, *vanavaninam* and *pasalu*. The final bilingual review also retained the cautious contextual rendering **“a new demon”** for `புத்த பூதம்` without treating it as a correction of the canonical Tamil.

The release-readiness pass made **no change** to the canonical Tamil page layer.

## Source PDF exclusion — PASS

The source PDF is intentionally external to the repository. Repository-tree inspection found **no committed `.pdf` file**.

The archival package therefore preserves source identity, checksum and page provenance without redistributing the supplied scan itself.

## Publication / reuse notes

This repository release is an **editorially verified archival and translation package**. It establishes source fidelity and repository readiness; it does **not** by itself establish copyright, licensing, republication or commercial-use permission for the underlying work, scan or translation.

Anyone preparing a public, print, ebook, commercial or otherwise redistributed edition should determine the applicable rights and permissions separately. Any such derived edition should preserve provenance to this first-edition scan and should not present normalized or reconstructed readings as though they were the audited source text.

The historical claims and rhetoric in the work are translated as source content. The archival workflow does not independently verify every historical assertion made by the text.

## Non-blocking editorial limitations

These are intentional and do not block repository release:

- the source PDF is not bundled;
- several unusual source forms remain transliterated or cautiously rendered rather than conjecturally normalized;
- the English is organized as three reading sections rather than one merged file;
- individual English section front matter retains batch-level `reviewed` status, while whole-work `VERIFIED` is recorded by `TRANSLATION_REVIEW.md` and repository-level status files;
- external historical fact-checking and legal rights clearance are outside this archival release gate.

## Release verdict

**Tamil archival package: RELEASE-READY.**  
**Verified English translation package: RELEASE-READY.**  
**Combined repository edition of `பலிபீடம் நோக்கி` / _Towards the Sacrificial Altar_: RELEASE-READY within this archive.**

This verdict means the source-preservation, reading-layer, translation, bilingual-alignment, navigation and repository-inventory gates have passed. The audited Tamil `pages/` layer remains the controlling authority.
