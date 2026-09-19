# Multipart Source Policy — பாயும்புலி பண்டாரக வன்னியன்

## Source family

- source family: **TVA_BOK_0065744**
- complete physical extent: **477 scans**
- supplied working splits: **16 PDFs**
- split-page total: **477**
- split PDFs remain outside Git.

## Canonical numbering rule

Repository `scan_page` is always the **overall physical scan number 1–477** and never resets per split.

Each canonical page record preserves:
- `scan_page`
- `part`
- `part_page`
- exact `source_filename`

## Boundary rule

Split boundaries are physical-file boundaries only.

For every `N→N+1` boundary:
1. inspect the final scan of the earlier Part;
2. inspect the first scan of the next Part;
3. classify as **CLEAN**, **GENUINE CONTINUATION**, or another source-supported state;
4. never reconstruct text across the split;
5. the next Part's first page may serve only as a witness until that Part becomes active.

## Workflow rule

**source intake → Pass 1 → Pass 2A → Pass 2B → Pass 3 → Part audit → status sync → documentation sync → Tamil archival-ready → assembled Tamil → English → release/readiness → release-ready synchronization → final Part closure → next Part**

## Current state

- 16 / 16 split PDFs — **SUPPLIED / REGISTERED**
- Part001 — **FINAL CLOSURE / CLOSED / FROZEN**
- Part002 — **FINAL CLOSURE / CLOSED / FROZEN**
- active Part — **Part005 / scans121–150**
- Part003 canonical records — **30/30**
- Part003 Pass 1 — **COMPLETE / PASS — 30/30 TEXT-COMPLETE**
- Part003 Pass 2A — **COMPLETE / PASS — 30/30 REVIEWED**
- Part003 Pass 2B — **COMPLETE / PASS — 30/30 REVIEWED**
- Part003 Pass 3 — **COMPLETE / PASS — 30/30 REVIEWED**
- Part003 Part audit — **PASS / COMPLETE**
- Part003 final metadata/status synchronization — **PASS / CLOSED**
- Part003 documentation synchronization — **PASS / COMPLETE**
- Part003 Tamil textual status — **30/30 verified**
- Part003 visual fidelity — **30/30 verified**
- Part003 unresolved status exceptions — **0**
- Part003 Tamil archival-ready — **PASS / CLOSED**
- Part003 assembled Tamil — **PASS / CLOSED — 5/5 VERIFIED**
- Part003 English planning/setup — **COMPLETE / PASS**
- Part003 English translated/source-checked — **5/5**
- Part003 E10–E14 — **SOURCE-CHECKED / COMPLETE**
- Part003 unresolved English holds — **0**
- Part003 English glossary reconciliation — **RECONCILED / PASS**
- Part003 glossary-reconciliation English section edits — **0**
- Part003 English editorial review — **PASS / CLOSED**
- Part003 editorial English-only changes — **49**
- Part003 source-alignment corrections within editorial total — **2**
- Part003 unresolved editorial holds — **0**
- Part003 bilingual review — **PASS / CLOSED**
- Part003 bilingual English-only corrections — **2**
- Part003 unresolved bilingual holds — **0**
- Part003 release/readiness — **PASS / CLOSED**
- Part003 unresolved release/readiness blockers — **0**
- Part003 release-ready synchronization — **PASS / CLOSED**
- Part003 release-sync canonical/assembled/English body changes — **0**
- Part003 release-sync source-variant collapses — **0**
- Part003 final closure — **PASS / CLOSED / FROZEN**

- Part004 — **FINAL CLOSURE / CLOSED / FROZEN**
- Part004 canonical page records — **30/30**
- Part004 Pass 1 — **COMPLETE / PASS — 30/30 TEXT-COMPLETE**
- Part004 unresolved Pass-1 source-reading holds — **0**
- Part004 Pass 2A — **COMPLETE / PASS — 30/30 REVIEWED — 0 corrections; 0 unresolved**
- Part004 Pass 2B — **COMPLETE / PASS — 30/30 REVIEWED — 3 lexical/source-text corrections; 0 historical-glyph corrections; 0 unresolved**
- Part004 Pass 3 — **COMPLETE / PASS — 30/30 REVIEWED — 0 textual corrections; 0 unresolved visual/structural questions**
- Part004 Part audit — **PASS / COMPLETE**
- Part004 final metadata/status synchronization — **PASS / CLOSED**
- Part004 Tamil textual status — **30/30 verified**
- Part004 visual fidelity — **30/30 verified**
- Part004 unresolved status exceptions — **0**
- Part004 documentation synchronization — **PASS / COMPLETE**
- Part004 Tamil archival-ready — **PASS / CLOSED**
- Part004 assembled Tamil — **PASS / CLOSED — 5/5 VERIFIED**
- Part004 English planning/setup — **COMPLETE / PASS**
- Part004 English translated/source-checked — **5/5**
- Part004 E15 — **SOURCE-CHECKED / COMPLETE**
- Part004 E16 — **SOURCE-CHECKED / COMPLETE**
- Part004 E17 — **SOURCE-CHECKED / COMPLETE**
- Part004 E18 — **SOURCE-CHECKED / COMPLETE**
- Part004 E19 — **SOURCE-CHECKED / COMPLETE**
- Part004 English glossary reconciliation — **RECONCILED / PASS**
- Part004 glossary-reconciliation English section edits — **0**
- Part004 unresolved glossary holds — **0**
- Part004 English editorial review — **PASS / CLOSED**
- Part004 editorial English-only changes — **25**
- Part004 whole-Part bilingual review — **PASS / CLOSED**
- Part004 bilingual English-only corrections — **0**
- Part004 release/readiness — **PASS / CLOSED**
- Part004 release-ready synchronization — **PASS / CLOSED**
- Part004 final closure — **PASS / CLOSED / FROZEN**
- Part005 — **ACTIVE / AUTHORIZED — GLOSSARY RECONCILED / EDITORIAL NEXT**
- Part005 canonical page records — **30/30 — scans121–150**
- Part005 Pass 1 — **COMPLETE / PASS — 30/30 TEXT-COMPLETE**
- Part005 incoming 120→121 — **GENUINE CONTINUATION / AUDITED**
- Part005 outgoing 150→151 — **GENUINE CONTINUATION / AUDITED**
- Part005 Pass 2A — **COMPLETE / PASS — 30/30 REVIEWED — 7 source-text corrections; 0 unresolved**
- Part005 Pass 2B — **COMPLETE / PASS — 30/30 REVIEWED — 4 source-text / lexical / spacing corrections; 0 historical-glyph corrections; 0 unresolved**
- Part005 Pass 3 — **COMPLETE / PASS — 30/30 REVIEWED — 0 textual corrections; 0 unresolved visual/structural questions**
- Part005 Part audit — **PASS / COMPLETE**
- Part005 final metadata/status synchronization — **PASS / CLOSED**
- Part005 Tamil textual status — **30/30 verified; 0 needs-review**
- Part005 visual fidelity — **30/30 verified; 0 needs-review**
- Part005 unresolved status exceptions — **0**
- Part005 documentation synchronization — **PASS / COMPLETE**
- Part005 canonical page mutations caused by documentation sync — **0**
- Part006 canonical leakage — **0**
- Part005 Tamil archival-ready — **PASS / CLOSED**
- Part005 canonical page mutations caused by archival-ready checkpoint — **0**
- Part006 canonical leakage — **0**
- Part005 assembled Tamil — **PASS / CLOSED — 7/7 VERIFIED**
- Part005 canonical page mutations caused by assembly — **0**
- frozen Part001–Part004 assembled-file mutations — **0**
- Part006 body leakage — **0**
- Part005 English translation planning/setup — **COMPLETE / PASS**
- planned English batches — **E20–E26 / 7**
- translated/source-checked English files — **7/7**
- E20–E26 — **SOURCE-CHECKED / COMPLETE**
- English glossary reconciliation — **RECONCILED / PASS**
- glossary-reconciliation English section edits — **0**
- unresolved glossary holds — **0**
- English editorial review — **NOT STARTED / NEXT GATE**
- split-boundary classifications — **5 / 15 audited**

Audited boundaries:
- **30→31 — GENUINE CONTINUATION**
- **60→61 — CLEAN**
- **90→91 — GENUINE CONTINUATION**
- **120→121 — GENUINE CONTINUATION**
- **150→151 — GENUINE CONTINUATION**

Durable boundary records:
- `PART_003_BOUNDARY_AUDIT_90_91.md`
- `PART_004_BOUNDARY_AUDIT_120_121.md`
- `PART_005_BOUNDARY_AUDIT_150_151.md`

## Batch-size policy

Normal Tamil verification iterations use **10 physical scans per batch**.

Exact next gate:

**Part005 English translation planning/setup.**

Part001–Part004 remain frozen. Preserve both audited Part005 boundaries. Use the closed Part005 canonical/assembled Tamil authority; preserve frozen prior-Part English and do not import Part006 body text.
