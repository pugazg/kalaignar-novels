# English Translation Plan — அரும்பு

## 1. Objective

Create a clear, faithful English translation of **கலைஞர் மு. கருணாநிதியின் `அரும்பு`** from the audited 1978 first-edition source layer in this repository.

Working English title:

**The Bud**

The English title reflects the recurring `அரும்பு` / bud image that structures the story. The Tamil title remains the authoritative archival work title.

The translation must preserve the work's narrative movement, domestic emotion, irony, social commentary, dialogue, repetition, child-centered imagery and recurring botanical metaphor without turning the text into a modern adaptation.

---

## 2. Work identity and structural rule

`அரும்பு` is the first component work in the 1978 four-story compilation `அரும்பு`.

Source coverage:

- physical scans **6–23**;
- **18 / 18** canonical page records verified;
- Tamil source audit **PASSED**;
- assembled Tamil **PASSED** as one continuous section.

No source-backed chapter divisions were identified. Therefore the English reading layer will also remain **one continuous section**. Do not invent chapter headings or treat source-page boundaries as chapters.

The compilation title and this first story share the same Tamil title, but collection identity and work identity remain separate archival levels.

---

## 3. Source-authority hierarchy

Translation must follow this authority order:

1. **Audited canonical Tamil page records** — `../../pages/`  
   Final authority for wording, punctuation, names, source oddities and physical-page provenance.
2. **Assembled Tamil reading layer** — `../../sections/01-arumbu.md`  
   Used for continuous reading and already-audited cross-page joins.
3. **Work metadata / audit / page map** — `../../metadata/source.md`, `../../audit.md`, `../../indexes/page-map.md`  
   Used for edition identity, page mapping, structural decisions and documented source anomalies.
4. **External reference material** — only if a later clearly marked translator/editor note genuinely requires it. External information must never silently override the printed Tamil.

If an assembled reading differs from a canonical page record, the canonical page record governs unless the Tamil archival layer is first corrected from direct source evidence.

Do not translate from memory, OCR, an internet edition, a normalized retelling or an assumed later edition.

---

## 4. Planned English file structure

```text
works/arumbu/translations/en/
  TRANSLATION_PLAN.md            # PASS / COMPLETE
  README.md                      # current translation summary
  PROGRESS.md                    # batch progress
  GLOSSARY.md                    # terminology/style locks
  PLAN_CHECKPOINT.md             # planning checkpoint record
  sections/
    01-arumbu.md                 # built incrementally across four reviewed batches
  TRANSLATION_REVIEW.md          # create only after all English batches are reviewed
  RELEASE_REPORT.md              # create only after whole-work bilingual verification
```

---

## 5. Controlled translation batches

The final English structure is one section, but translation proceeds in four small source-aligned batches so every increment can be source-checked and committed independently.

| Batch | Source scans | Tamil basis | English destination | Role | Current state |
|---|---:|---|---|---|---|
| **1 — pilot** | **6–10** | audited pages + assembled continuity | `sections/01-arumbu.md` | opening, Gokul's background, Rathinam's wedding, first meeting with Gomathi | **REVIEWED / COMPLETE** |
| **2** | **11–15** | same | same | Gomathi's father's death, Gokul stays, Kumar's dream, Gomathi joins Gokul's household | **NEXT** |
| **3** | **16–20** | same | same | family formation, Kumar/Gomathi bond, birth and illness of the baby, growing conflict | BLOCKED until Batch 2 closes |
| **4 — final prose batch** | **21–23** | same | same | baby's death, Kumar's distress, Gokul's accident, final reconciliation and bud/leaf motif | BLOCKED |

Each batch must be completed as a narrow checkpoint:

`draft-translated → source-checked → reviewed → sync controls → commit → stop`

Do not start the next batch in the same checkpoint unless explicitly authorized.

---

## 6. Pilot and style lock

Batch 1 was the mandatory pilot and is now **REVIEWED / COMPLETE**. Its source-check locked the applicable decisions in `GLOSSARY.md` for:

- `அரும்பு` as title/metaphor → **The Bud / bud**;
- names and place-name spellings used in scans 6–10;
- `அக்கிரகாரம்`, `புரோகிதர்`, `ஓம குண்டம்`, `அம்மி`, `அரசாணி`;
- `புதுமை முறை` → source-neutral **new-style**, without importing an unprinted movement label;
- `வாழ்க்கை ஒப்பந்த விழா` → **life-contract ceremony**;
- colloquial dialogue register and direct `அப்பா` handling;
- ellipses, repeated exclamation marks, dashes and rhetorical punctuation;
- source-period borrowed terms such as `லீவு` and `சிகரெட்` where standard English is natural.

Later batches preserve these locks unless a direct conflict with the audited source is explicitly documented.

---

## 7. Core translation principles

1. **No summarising** — every substantive sentence, dialogue turn, rhetorical question and image must be represented.
2. **Natural but source-bound English** — improve readability only at the level of English syntax; do not add content, explanation or motive absent from the Tamil.
3. **Preserve agency** — who acts, speaks, accuses, comforts, misunderstands or remembers must not shift in translation.
4. **Preserve emotional force** — grief, jealousy, affection, irony, anger and childlike confusion must not be softened or intensified.
5. **Preserve repetition when meaningful** — repeated words, cries, names and rhetorical patterns are part of the prose rhythm.
6. **Do not modernize social language silently** — period social/familial vocabulary should be translated faithfully rather than rewritten into present-day explanatory prose.
7. **Do not repair source oddities inside English silently** — unusual verified Tamil must remain visible through a literal/conservative rendering or a minimal translator note.
8. **Minimal notes** — use notes only when a source-specific anomaly or culture-bound term materially affects comprehension.
9. **One work, one section** — no artificial chapters.
10. **Traceability** — every English batch must remain reversible to physical scan ranges and canonical page records.

---

## 8. Names and place names

Use stable readable English forms while leaving the Tamil source untouched.

| Tamil source form | English form | State / policy |
|---|---|---|
| `கோகுல்` | **Gokul** | **LOCKED** |
| `கோமதி` | **Gomathi** | **LOCKED** |
| `குமார்` | **Kumar** | **LOCKED** |
| `ரத்தினம்` | **Rathinam** | **LOCKED** |
| `திருக்குவளை` | **Thirukkuvalai** | **LOCKED** |
| `அம்மனூர்` | **Ammanur** | **LOCKED** for normal source form |
| `மாயவரம்` | **Mayavaram** | preserve period/source place form; lock when encountered in Batch 2 |
| `சென்னை` | **Chennai** | **LOCKED** |
| `மதராஸ் மெயில்` | **Madras Mail** | preserve source-period train expression; lock when encountered |

### Scan 23 `அம்மனார்` exception

The final page independently confirms the printed form **`அம்மனார்`**, even though earlier pages use `அம்மனூர்`. The English must **not silently normalize this occurrence to Ammanur**.

Default handling for Batch 4: retain a conservative source-facing form such as **Ammanar** and document the anomaly in `GLOSSARY.md` / a minimal translator note. Any different treatment requires an explicit documented editorial decision; the canonical Tamil remains unchanged.

---

## 9. Cultural, ritual and social terminology

Use the least interpretive rendering that remains readable.

| Tamil | English handling | State / rule |
|---|---|---|
| `அக்கிரகாரம்` | **agraharam** | **LOCKED**; conservative transliteration |
| `புரோகிதர்` | **priest** | **LOCKED** |
| `ஓம குண்டம்` | **homa fire-pit** | **LOCKED** |
| `அம்மி` | **ammi** | **LOCKED**; do not invent ritual explanation |
| `அரசாணி` | **arasani** | **LOCKED**; conservative transliteration |
| `மாங்கல்யம்` | **mangalyam** / context-sensitive rendering | later-batch decision |
| `புதுமை முறை` | **new-style / new-style manner** | **LOCKED**; do not automatically label it “Self-Respect marriage” unless source/authorized note establishes that identification |
| `அறிவு முறை` | **a rational manner** | **LOCKED** |
| `வாழ்க்கை ஒப்பந்த விழா` | **life-contract ceremony** | **LOCKED** |

Political, religious, caste or social criticism, where present, must be translated as the author's own rhetoric. Do not soften it, intensify it, or turn an implied context into asserted external fact.

---

## 10. Recurring metaphor and child register

`அரும்பு` is both the title and a recurring metaphor for the child / young life. The English preserves a stable **bud** image wherever the Tamil deliberately returns to that image.

Related imagery such as `இரு இலை; ஒரு மொட்டு`, `அரும்பு பொதியவிழாச் செடி`, `அந்த அரும்பு`, and the final movement toward `இரு இலை, இரு மொட்டு` must remain recognizably connected in English. Do not replace these with unrelated idioms merely for fluency.

Kumar's child speech and misunderstandings should sound like a child in English without becoming comic caricature. Family terms are translated contextually and consistently. Batch 1 locks direct emotional `அப்பா` as **Appa** while ordinary narration uses **father**.

---

## 11. Dialogue, punctuation and typography

- Use English quotation marks consistently while preserving speaker boundaries exactly.
- Preserve ellipses where they carry hesitation, interruption, grief or rhetorical delay.
- Preserve emphatic repetition and exclamation where it is part of the source voice.
- Dashes may be rendered with readable English punctuation, but they must not erase a source contrast or rhetorical break.
- Do not turn dialogue into indirect speech.
- Paragraph boundaries should follow the audited/assembled Tamil unless a purely typographic English adjustment is necessary; material restructuring is not allowed.
- Source-page comments remain outside visible prose as HTML provenance markers.

### Final punctuation anomaly

Scan 23 ends with the verified source punctuation **`இனி:......`** inside the closing sentence. Batch 4 must not silently regularize this. The English treatment must be documented during source-check and remain traceable to the Tamil punctuation.

---

## 12. Source-oddity policy

### Scan 22 — `பேசினேன்`

The source prints first-person **`பேசினேன்`** within otherwise third-person narration. English must not silently change this to “he spoke”, “he answered” or similar. Final wording is locked during Batch 4 source-check.

### Scan 23 — `அம்மனார்`

Retain the source anomaly as described above; do not silently substitute earlier `அம்மனூர்`.

Other verified odd spellings, spacing or punctuation receive the same treatment: canonical Tamil first, conservative English second, clearly labeled note only if necessary.

---

## 13. Page and scan traceability

The English section retains reversible provenance with HTML comments, for example:

```html
<!-- source: scan 6; printed page: — -->
<!-- source: scan 14; printed page: 10 -->
```

Rules:

- scan order **6–23** is preserved;
- scan 6 remains visibly unnumbered in provenance;
- scan 13 / printed 8 → scan 14 / printed 10 remains explicit;
- **do not invent printed page 9**;
- already-established cross-page joins may be translated continuously, but provenance comments keep the join reversible;
- scan 23 remains the final source page;
- **do not add `முற்றும்` / “The End”** because no such ending is printed.

---

## 14. Review states and gates

For each translation batch:

1. **draft-translated** — English prose created from audited Tamil only;
2. **source-checked** — English compared back to canonical Tamil page records for the batch;
3. **reviewed** — omissions, additions, agency, dialogue, names, terminology, punctuation, metaphors and provenance checked; glossary decisions synchronized;
4. update `README.md`, `PROGRESS.md`, `GLOSSARY.md` and affected project controls;
5. commit the batch and stop.

After all four batches are reviewed:

- create `TRANSLATION_REVIEW.md`;
- run the whole-work bilingual review required by `NOVEL_PROCESSING_GUIDE.md` Section 16;
- only after that passes may whole-work English be called **VERIFIED**;
- only after whole-work English verification may `RELEASE_REPORT.md` be created under Section 17.

---

## 15. Planning checkpoint result

**SECTION 14 ENGLISH TRANSLATION PLAN — PASS / COMPLETE.**

Planning controls were initialized before prose translation. Batch execution state is tracked in `README.md`, `PROGRESS.md`, `GLOSSARY.md` and this plan's batch table.

## Batch 1 execution result

**BATCH 1 PILOT — SCANS 6–10 — REVIEWED / COMPLETE.**

The pilot was translated from audited pages `0006`–`0010`, checked back against all five canonical records, and closed with **0 omissions, 0 source-like additions and 0 unresolved translation items**. Pilot terminology/style decisions are locked in `GLOSSARY.md`. No scan 11 English prose is present.

## Exact next activity

Execute **Batch 2 — scans 11–15 only**:

- append only the audited Tamil corresponding to scans **11–15** to `translations/en/sections/01-arumbu.md`;
- retain scan/page provenance;
- source-check the new span back against canonical `pages/0011...0015`;
- preserve Batch 1 locks unless a direct source conflict requires documented review;
- add/lock only genuinely new Batch 2 terminology in `GLOSSARY.md`;
- update `README.md`, `PROGRESS.md` and affected work/root controls;
- mark Batch 2 `reviewed` only after source comparison;
- synchronize controls, commit, and stop before Batch 3;
- do not begin `சாரப்பள்ளம் சாமுண்டி` or the 1978 `பெரிய இடத்துப் பெண்` witness comparison.
