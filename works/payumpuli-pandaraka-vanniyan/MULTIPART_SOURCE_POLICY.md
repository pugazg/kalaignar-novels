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
- active Part — **Part003 / scans61–90**
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
- Part003 final closure — **NEXT GATE / NOT STARTED**

- Part004 transcription — **BLOCKED**
- split-boundary classifications — **3 / 15 audited**

Audited boundaries:
- **30→31 — GENUINE CONTINUATION**
- **60→61 — CLEAN**
- **90→91 — GENUINE CONTINUATION**

Durable Part003 outgoing-boundary record:
- `PART_003_BOUNDARY_AUDIT_90_91.md`

## Batch-size policy

Normal Tamil verification iterations use **10 physical scans per batch**.

Exact next gate:

**Part003 final closure.**

Part001 and Part002 remain frozen. Do not begin Part004 transcription until Part003 final closure passes.
