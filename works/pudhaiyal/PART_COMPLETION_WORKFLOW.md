# Split-PDF part-completion workflow — புதையல்

Split PDFs are access derivatives of one source edition. `part-complete` is a split-level state only; whole-work Tamil/English/release gates remain separate.

## Per-split sequence

1. map represented source scans;
2. reconcile canonical `pages/` records;
3. native visual/structural fidelity review;
4. resolve/retain every `needs-review` item;
5. part-level Tamil audit;
6. assembled Tamil from audited canonical pages;
7. controlled English translation;
8. English source check;
9. part-level bilingual review;
10. synchronize status.

## Lexical baseline rule — scan 280 onward

User-supplied Gemini transcription controls lexical wording/forms/spacing. Native scans control headings, paragraph boundaries, punctuation, quotations, physical boundaries, separators, chapter/scene/work-ending structure and back matter.

- Part 007 baseline: `p7.md`; three explicit user-authorized omissions restored.
- Part 008 baseline: `p8.md`; user-authorized scan-384 phrase **`தகட்டில் இருக்கிறபடி`** restored.
- Part 009 baseline: `p9.md`; **no complete lexical omission found**.
- Part 010 baseline: `p10.md`; native scan 445 complete word **`விடு`** was absent from baseline and was explicitly authorized/restored on 2026-09-03.

A user-authorized restoration is narrow to the documented omission and does not establish general source-correction authority.

## Split checkpoints

- Parts 001–008 — `part-complete`
- Part 009 — scans **393–441** — **Tamil audit PASSED + assembled Tamil PASSED; controlled English draft through Chapter 50 / scan 438 portion**
- Part 010 — scans **442–448** — **Tamil audit PASSED + assembled Tamil PASSED; controlled English pending**

## Part 009 gate state

- mapping: **PASS — 49 / 49**
- canonical: **PASS — 49 / 49**
- visual/structural fidelity: **PASS**
- needs-review: **0**
- Tamil audit: **PASS** — [`notes/part-009-tamil-audit.md`](notes/part-009-tamil-audit.md)
- assembled Tamil: **PASS** — [`notes/part-009-assembled-tamil-check.md`](notes/part-009-assembled-tamil-check.md)
- controlled English draft: **IN PROGRESS — Chapter 45 continuation through Chapter 50 close / scan 438 portion**
- English source check: **PENDING until complete Part-009 draft**
- bilingual review: **PENDING**

Part 009 continues Chapter 45 across scan392→393 and carries Chapters 45–51 through scan 441. The endpoint `அம்ப` is a physical split only and joins Part010 `லமே` as **`அம்பலமே`**.

The English Chapter-45 continuation resolves the already-audited scan392 `நமது` + scan393 `வாழ்க்கையை` boundary. Chapters 46–50 are now draft-translated continuously through the Chapter-50 close on scan 438 portion. Chapter 48 preserves the source's Aravan/Bhima wording, caste-marked insult and `kalappali` language without external correction. Chapter 49 preserves the source's village-violence wording and rekla pursuit toward Manora. Chapter 50 preserves Mayandi's repeated `சாவுக் கண்ணீர்` image, his death and the source's Ambalam-at-sea ending without downstream review claims. These draft units are not yet promoted to `source-checked` or `reviewed`.

## Part 010 gate state

- mapping: **PASS — 7 / 7**
- canonical: **PASS — 7 / 7**
- verified: **PASS — 7 / 7**
- needs-review: **0**
- Tamil audit: **PASS** — [`notes/part-010-tamil-audit.md`](notes/part-010-tamil-audit.md)
- assembled Tamil: **PASS** — [`notes/part-010-assembled-tamil-check.md`](notes/part-010-assembled-tamil-check.md)
- controlled English / downstream gates: **PENDING**

Authorized source/baseline difference:

- native: `தங்கத்திற்குப் பக்கத்திலே புதைத்து விடு!”`
- `p10.md`: `தங்கத்திற்குப் பக்கத்திலே புதைத்து` + closing quote
- omitted complete word: **`விடு`**
- user authorization: **granted 2026-09-03**
- canonical restoration: **complete on scan 445**

Scan **447 / printed443** is the actual novel narrative ending. Scan **448** is separate printer-colophon back matter (`அன்பு அச்சகம், பொறையார்.`).

## Exact next activity

Continue the **Part 009 controlled English draft with the Chapter 51 Part-009 portion**, beginning at scan **438 portion** and translating continuously through scan **441**. Preserve the audited open split endpoint `அம்ப` and do not pull Part-010 `லமே` into the Part-009 derivative. After the Part-009 draft is complete, run the Part-009 English source check before bilingual review.
