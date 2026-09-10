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

No source-backed chapter divisions were identified. Therefore the English reading layer also remains **one continuous section**. Do not invent chapter headings or treat source-page boundaries as chapters.

The compilation title and this first story share the same Tamil title, but collection identity and work identity remain separate archival levels.

---

## 3. Source-authority hierarchy

Translation follows this authority order:

1. **Audited canonical Tamil page records** — `../../pages/` — final authority for wording, punctuation, names, source oddities and physical-page provenance.
2. **Assembled Tamil reading layer** — `../../sections/01-arumbu.md` — continuous-reading support and already-audited cross-page joins.
3. **Work metadata / audit / page map** — structural, edition and provenance controls.
4. **External reference material** — only for a clearly marked later editorial note when genuinely required; never to override the printed Tamil silently.

If the assembled Tamil and canonical page files appear to disagree, canonical `pages/` governs unless the Tamil archival layer is first corrected from direct source evidence.

Do not translate from memory, OCR, an internet edition, a normalized retelling or an assumed later edition.

---

## 4. Planned English file structure

```text
works/arumbu/translations/en/
  TRANSLATION_PLAN.md
  README.md
  PROGRESS.md
  GLOSSARY.md
  PLAN_CHECKPOINT.md
  sections/
    01-arumbu.md
  TRANSLATION_REVIEW.md          # create only after all English batches are reviewed
  RELEASE_REPORT.md              # create only after whole-work bilingual verification
```

---

## 5. Controlled translation batches

The final English structure is one section, but translation proceeds in four small source-aligned batches so every increment can be source-checked and committed independently.

| Batch | Source scans | Tamil basis | English destination | Role | Current state |
|---|---:|---|---|---|---|
| **1 — pilot** | **6–10** | audited pages + assembled continuity | `sections/01-arumbu.md` | opening, Gokul's background, Rathinam's wedding, first meeting with Gomathi | **REVIEWED / COMPLETE** |
| **2** | **11–15** | same | same | Gomathi's father's death, Gokul stays, Kumar's dream, Gomathi joins Gokul's household | **REVIEWED / COMPLETE** |
| **3** | **16–20** | same | same | family formation, Kumar/Gomathi bond, birth and illness of the baby, growing conflict | **NEXT** |
| **4 — final prose batch** | **21–23** | same | same | baby's death, Kumar's distress, Gokul's accident, final reconciliation and bud/leaf motif | BLOCKED until Batch 3 closes |

Each batch is a narrow checkpoint:

`draft-translated → source-checked → reviewed → sync controls → commit → stop`

Do not start the next batch in the same checkpoint unless explicitly authorized.

---

## 6. Style lock through Batch 2

Batch 1 established the mandatory pilot style; Batch 2 confirmed it and added only source-required terms. Locked principles include:

- `அரும்பு` as title/metaphor → **The Bud / bud**;
- source-facing names/place names;
- conservative handling of ritual/cultural terms;
- `புதுமை முறை` → source-neutral **new-style**, without importing an unprinted movement label;
- `வாழ்க்கை ஒப்பந்த விழா` → **life-contract ceremony**;
- direct emotional `அப்பா` → **Appa** while ordinary narration uses **father**;
- colloquial dialogue remains colloquial without caricature;
- ellipses, repetition, exclamation and rhetorical breaks remain visible when meaningful;
- natural English syntax is allowed only without adding motive, explanation or historical identification absent from Tamil;
- reversible scan/page provenance is mandatory.

Batch 2 additionally locks Mayavaram, Madras Mail, `oppari`, `Aararo`, `aunt's son`, `pottu`, `mangalyam`, `Mahalakshmi`, and source-period `“rowdy” gang` handling.

Later batches preserve these locks unless a direct conflict with the audited source is explicitly documented.

---

## 7. Core translation principles

1. **No summarising** — every substantive sentence, dialogue turn, rhetorical question and image must be represented.
2. **Natural but source-bound English** — improve readability only at the level of English syntax; do not add content, explanation or motive absent from Tamil.
3. **Preserve agency** — who acts, speaks, accuses, comforts, misunderstands or remembers must not shift.
4. **Preserve emotional force** — grief, jealousy, affection, irony, anger and childlike confusion must not be softened or intensified.
5. **Preserve meaningful repetition** — repeated words, cries, names and rhetorical patterns are part of the prose rhythm.
6. **Do not modernize social language silently.**
7. **Do not repair source oddities silently in English.**
8. **Minimal notes** — only where an anomaly or culture-bound term materially affects comprehension.
9. **One work, one section** — no artificial chapters.
10. **Traceability** — every English batch remains reversible to physical scans and canonical page records.

---

## 8. Names and place names

Use stable readable English forms while leaving Tamil source untouched.

| Tamil source form | English form | State / policy |
|---|---|---|
| `கோகுல்` | **Gokul** | **LOCKED** |
| `கோமதி` | **Gomathi** | **LOCKED** |
| `குமார்` | **Kumar** | **LOCKED** |
| `ரத்தினம்` | **Rathinam** | **LOCKED** |
| `திருக்குவளை` | **Thirukkuvalai** | **LOCKED** |
| `அம்மனூர்` | **Ammanur** | **LOCKED** for normal source form |
| `மாயவரம்` | **Mayavaram** | **LOCKED** — preserve source-period place form |
| `சென்னை` | **Chennai** | **LOCKED** |
| `மதராஸ் மெயில்` | **Madras Mail** | **LOCKED** — preserve source-period train name |

### Scan 23 `அம்மனார்` exception

The final page independently confirms **`அம்மனார்`**, even though earlier pages use `அம்மனூர்`. English must **not silently normalize this occurrence to Ammanur**. Batch 4 must retain a conservative source-facing form such as **Ammanar** and document the decision if needed.

---

## 9. Cultural, ritual and social terminology

Use the least interpretive rendering that remains readable.

| Tamil | English handling | State / rule |
|---|---|---|
| `அக்கிரகாரம்` | **agraharam** | **LOCKED** |
| `புரோகிதர்` | **priest** | **LOCKED** |
| `ஓம குண்டம்` | **homa fire-pit** | **LOCKED** |
| `அம்மி` | **ammi** | **LOCKED** |
| `அரசாணி` | **arasani** | **LOCKED** |
| `புதுமை முறை` | **new-style / new-style manner** | **LOCKED** |
| `அறிவு முறை` | **a rational manner** | **LOCKED** |
| `வாழ்க்கை ஒப்பந்த விழா` | **life-contract ceremony** | **LOCKED** |
| `ஒப்பாரி` | **oppari** | **LOCKED** |
| `ஆராரோ` | **Aararo** | **LOCKED** |
| `காக்கா பிடிக்க` | **curry favour** | **LOCKED** |
| `பாட்டி` in direct address | **Paatti** | **LOCKED** |
| `அத்தை மகன்` | **aunt's son** | **LOCKED** — preserve repeated source kinship wording |
| `பொட்டு` | **pottu** | **LOCKED** |
| `மாங்கல்யம்` | **mangalyam** | **LOCKED** |
| `மகாலட்சுமி` | **Mahalakshmi** | **LOCKED** |
| `ரெளடிக் கும்பல்` | **“rowdy” gang** | **LOCKED** |

Political, religious, caste or social criticism, where present, must be translated as the author's own rhetoric. Do not soften it, intensify it, or turn implied context into asserted external fact.

---

## 10. Recurring metaphor and child register

`அரும்பு` is both the title and a recurring metaphor for the child / young life. English preserves a stable **bud** image wherever Tamil deliberately returns to that image.

Related imagery such as `இரு இலை; ஒரு மொட்டு`, `அரும்பு பொதியவிழாச் செடி`, `அந்த அரும்பு`, and the final movement toward `இரு இலை, இரு மொட்டு` must remain recognizably connected.

Kumar's child speech and misunderstandings should sound like a child in English without becoming comic caricature. Batch 2 also preserves the dream register and source metaphors even when unusual in English.

---

## 11. Dialogue, punctuation and typography

- Use English quotation marks consistently while preserving speaker boundaries exactly.
- Preserve ellipses where they carry hesitation, interruption, grief or rhetorical delay.
- Preserve emphatic repetition and exclamation where they are part of source voice.
- Dashes may be rendered with readable English punctuation but must not erase contrast or rhetorical break.
- Do not turn dialogue into indirect speech.
- Paragraph boundaries follow audited/assembled Tamil unless a purely typographic English adjustment is necessary.
- Source-page comments remain outside visible prose as HTML provenance markers.

### Final punctuation anomaly

Scan 23 ends with verified **`இனி:......`**. Batch 4 must not silently regularize it; English treatment must remain documented and traceable.

---

## 12. Source-oddity policy

### Scan 22 — `பேசினேன்`

The source prints first-person **`பேசினேன்`** within otherwise third-person narration. English must not silently change it to third person. Final wording is locked during Batch 4 source-check.

### Scan 23 — `அம்மனார்`

Retain the source anomaly; do not silently substitute earlier `அம்மனூர்`.

Other verified odd spellings, spacing or punctuation receive the same treatment: canonical Tamil first, conservative English second, clearly labeled note only if necessary.

---

## 13. Page and scan traceability

English retains reversible provenance with HTML comments.

Rules:

- scan order **6–23** is preserved;
- scan 6 remains visibly unnumbered;
- scan 13 / printed 8 → scan 14 / printed 10 remains explicit;
- **do not invent printed page 9**;
- established cross-page joins may be translated continuously, but provenance keeps them reversible;
- scan 23 remains final;
- **do not add `முற்றும்` / “The End”** because none is printed.

---

## 14. Review states and gates

For each translation batch:

1. **draft-translated**;
2. **source-checked** against canonical Tamil page records;
3. **reviewed** for omissions, additions, agency, dialogue, names, terminology, punctuation, metaphors and provenance;
4. synchronize `README.md`, `PROGRESS.md`, `GLOSSARY.md` and affected project controls;
5. commit and stop.

After all four batches are reviewed:

- create `TRANSLATION_REVIEW.md`;
- run the whole-work bilingual review required by `NOVEL_PROCESSING_GUIDE.md` Section 16;
- only after that passes may whole-work English be called **VERIFIED**;
- only after whole-work English verification may `RELEASE_REPORT.md` be created under Section 17.

---

## 15. Execution state

**SECTION 14 ENGLISH TRANSLATION PLAN — PASS / COMPLETE.**

### Batch 1 execution result

**BATCH 1 PILOT — SCANS 6–10 — REVIEWED / COMPLETE.**

Translated from audited pages `0006`–`0010`, checked back against all five records, and closed with **0 omissions, 0 source-like additions and 0 unresolved translation items**.

### Batch 2 execution result

**BATCH 2 — SCANS 11–15 — REVIEWED / COMPLETE.**

Translated from audited pages `0011`–`0015`, then checked back against all five canonical records. The checkpoint closed with **0 omissions, 0 source-like additions and 0 unresolved translation items**. The scan 11→12 and 13→14 joins remain reversible; the visible printed-page jump **8 → 10** is retained without inventing page 9. Scan 15 remains intentionally open at its final source fragment; no scan 16 English prose is present.

Current English coverage: **10 / 18 source scans — scans 6–15**.

## Exact next activity

Execute **Batch 3 — scans 16–20 only**:

- append only audited Tamil corresponding to scans **16–20** to `translations/en/sections/01-arumbu.md`;
- retain scan/page provenance;
- source-check the new span against canonical `pages/0016...0020`;
- preserve Batches 1–2 locks unless a direct source conflict requires documented review;
- add/lock only genuinely new Batch 3 terminology in `GLOSSARY.md`;
- update translation/work/root controls;
- mark Batch 3 `reviewed` only after source comparison;
- commit and stop before Batch 4;
- do not begin `சாரப்பள்ளம் சாமுண்டி` or the 1978 `பெரிய இடத்துப் பெண்` witness comparison.
