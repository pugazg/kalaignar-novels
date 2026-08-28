# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Fresh-chat prompt: `NEXT_NOVEL_CHAT_PROMPT.md`

---

# 1. Mandatory startup

Before changing the current/next work:

1. read `NOVEL_PROCESSING_GUIDE.md` completely;
2. read root `README.md`;
3. read this `HANDOVER.md` completely;
4. study `works/balipeedam-nokki/` only as the completed reference implementation;
5. inspect live repository state before creating files;
6. continue existing work rather than duplicating it;
7. inspect the actual scan before accepting metadata or transcription;
8. never commit source PDFs or split source PDFs.

---

# 2. Source / transcription policy

Authority order:

1. actual scan page;
2. source-printed bibliographic/page information;
3. canonical Tamil `pages/` records;
4. audited Tamil `sections/`;
5. verified English translation;
6. metadata / review documentation.

Do not silently modernize, repair, normalize, reconstruct or improve source-supported Tamil. Preserve spelling, punctuation, spacing, colloquial forms, typographical oddities, page boundaries and internal structure.

## Mandatory old-glyph rule

When the user supplies a transcription:

- use it as the comparison baseline;
- do not replace it because grammar/context suggests another form;
- inspect native split-source pixels for every disagreement;
- an assistant change survives only when the glyphs establish it;
- ambiguous old glyphs do **not** justify overriding the baseline;
- ambiguous pages are `needs-review`;
- `verified` requires a complete physical-page pass after all deltas are resolved.

---

# 3. Completed reference implementation — பலிபீடம் நோக்கி

`works/balipeedam-nokki/`

- Tamil page records: **34 / 34 verified**
- Tamil audit: **PASSED**
- English translation: **VERIFIED**
- release-readiness: **RELEASE-READY**
- source PDF committed: **No**

---

# 4. Current work — புதையல்

Work path: `works/pudhaiyal/`

Scan-established identity:

- title: **புதையல்**
- author: **கலைஞர் மு. கருணாநிதி, எம். எல். ஏ.**
- publisher: **அன்புப் பதிப்பகம்**
- place: **பொறையார் :: தஞ்சை மாவட்டம்**
- edition: **மூன்றாம் பதிப்பு**
- date: **செப்டம்பர், 1961**

Publication page now reverified as:

- `சாதாரணப் பதிப்பு ரூ 5/-`
- `நூல் நிலையப் பதிப்பு ரூ 6/-`
- `மூன்றாம் பதிப்பு: செப்டம்பர், 1961.`

The earlier assistant `ஸ்பெஷல் பதிப்பு` reading was wrong.

Original source filename: `TVA_BOK_0064097_புதையல்.pdf`

Known source facts:

- original attached size: **502,895,096 bytes**
- Tamil Digital Library bibliographic extent: **443 p.**
- exact full-PDF scan/page-object count: **pending**
- original SHA-256: **pending**
- source PDF committed: **No**

The former `150 pages total` conclusion was wrong. Scans 1–150 are only a known prefix.

---

# 5. Split-source workflow

## Part 001

`TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf`

- source scans: **1–49**
- transcription coverage: complete
- integrity state: verified after backward corrections
- committed: **No**

## Part 002

`TVA_BOK_0064097_புதையல்_part_002_pages_50-98.pdf`

- source scans: **50–98**
- transcription coverage: complete
- integrity state: scans 50–74 and 76–98 verified; scan 75 needs-review
- committed: **No**

## Part 003

`TVA_BOK_0064097_புதையல்_part_003_pages_99-147.pdf`

- source scans: **99–147**
- page records created through **scan 118 / printed page 116**
- scans 99–108: verified after backward-integrity corrections
- scans 109–118: **needs-review**; earlier Iteration-10 verification withdrawn
- user-confirmed protected readings:
  - scan 109 `என்னா பிரதர்!`
  - scan 110 `போய்ட்டு வர்ரேன்`
- committed: **No**

---

# 6. Backward integrity audit — ACTIVE GATE

Central record:

`works/pudhaiyal/notes/backward-integrity-audit-001-118.md`

This audit was opened because assistant visual passes repeatedly hallucinated old-print readings and then labelled them source-confirmed.

Material corrections already applied include:

- scan 4 `நூல் நிலையப் பதிப்பு`, colon after `மூன்றாம் பதிப்பு`;
- scan 11 `இருக்கிறான்னு`;
- scan 24 `அவர்களை நோக்கி`;
- scan 25 `எதோ`;
- scan 31 no full stop after `மூர்ச்சை யடைந்தான்`, plus `அவனைத்தழுவிக்`;
- scan 75 `போயிடுச்சா?` assistant claim withdrawn; user's `போய்ட்டுதா?` restored as baseline, page reopened;
- scan 99 `சொல்வேன் என்று... நான் யாருடைய...`;
- scan 101 `அவரைப் பற்றி நன்கு விசாரிக்கவேண்டும் என்ற ஒரு ஆவல்...`;
- scan 104 `நெடு நாள் பழக்கமா?`; `உடல் வளர்த்து` remains confirmed;
- scan 106 `நான் வரத்தான் வேண்டுமா?`;
- scans 109–118 downgraded to `needs-review`.

The audit does **not** blindly revert every assistant delta. Source-supported earlier corrections remain when native images confirm them.

---

# 7. Current Tamil state

- page records created: **118**
- verified: **107**
- needs-review: **11** — scan 75 and scans 109–118
- partial: **0**
- known-prefix not-started: **32** — scans 119–150
- full-source page-map coverage: **INCOMPLETE**
- backward integrity audit: **OPEN**
- forward transcription: **FROZEN**
- Tamil whole-work audit: **not started**
- assembled Tamil layer: **blocked**
- English translation: **blocked**

Relevant fidelity records:

- `works/pudhaiyal/notes/visual-fidelity-scans-001-012.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-013-022.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-023-032.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-033-049.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-050-062.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-063-072.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-073-082.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-083-098.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-099-108.md`
- `works/pudhaiyal/notes/backward-integrity-audit-001-118.md`

---

# 8. Structural state established so far

- scans 7–12 — `அறிமுகம்`;
- scan 13 — chapter 1 begins;
- scan 22 — chapter 1 → 2;
- scan 30 — chapter 2 → 3;
- scan 40 — chapter 3 → 4;
- scan 46 — four-star internal transition;
- scan 47 — embedded historical tale inside chapter 4;
- scan 52 — chapter 4 → 5;
- scan 60 — chapter 5 → 6;
- scan 68 — chapter 6 closes;
- scan 69 — chapter 7 begins;
- scan 75 — chapter 7 → 8;
- scan 83 — chapter 8 closes;
- scan 84 — chapter 9 begins;
- scan 92 — chapter 9 closes;
- scan 93 — chapter 10 begins;
- scan 98 — internal transition;
- scan 101 — chapter 10 closes;
- scan 102 — chapter 11 begins;
- scan 107 — internal transition;
- scan 110 — chapter 11 → 12;
- scan 118 — internal transition inside chapter 12.

Textual verification of scans 109–118 is reopened even though their physical structure is mapped.

---

# 9. Translation gate

Do not begin English translation until the complete Tamil source, source extent, visual audit, structural audit and assembled Tamil layer all pass. Source PDFs remain outside the repository.

---

# 10. Exact next activity

Do **not** begin scan 119.

1. Re-audit **scans 109–118 / printed pages 107–116** from part 003 at native resolution.
2. Use the user's Iteration 10 as baseline.
3. Protect the user-confirmed scan-109 `என்னா பிரதர்!` and scan-110 `போய்ட்டு வர்ரேன்` from assistant reinterpretation.
4. For every assistant delta, classify it `confirmed`, `withdrawn`, or `ambiguous`.
5. Promote each page to `verified` only after the whole physical page passes.
6. Then resolve scan 75's old-glyph reading.
7. Only after all 11 `needs-review` pages are closed may forward transcription resume from scan 119.

Do not start English translation.

---

# 11. Fresh-chat rule

Use `NEXT_NOVEL_CHAT_PROMPT.md` together with the relevant split source. Current live GitHub state and this handover govern over stale summaries.
