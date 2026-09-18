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
- active Part — **Part002 / scans31–60**
- Part002 canonical records — **30/30**
- Part002 Pass 1 — **COMPLETE / PASS — 30/30 TEXT-COMPLETE**
- Part002 Pass 2A — **COMPLETE / PASS — 30/30 REVIEWED**
- Part002 Pass 2B — **COMPLETE / PASS — 30/30 REVIEWED**
- Part002 Pass 3 — **COMPLETE / PASS — 30/30 REVIEWED**
- Part002 Part audit — **PASS / COMPLETE**
- Part002 final metadata/status synchronization — **PASS / CLOSED**
- Part002 documentation synchronization — **PASS / COMPLETE**
- Part002 Tamil textual status — **30/30 verified**
- Part002 visual fidelity — **30/30 verified**
- Part002 unresolved status exceptions — **0**
- Part002 Tamil archival-ready — **PASS / CLOSED**
- Part002 assembled Tamil — **PASS / CLOSED — 5/5 VERIFIED**
- Part002 English planning/setup — **COMPLETE / PASS**
- Part002 English translated/source-checked — **1/5**
- Part002 E5 — **SOURCE-CHECKED / COMPLETE**
- Part002 English next — **E6 / section09 / scans35–41**
- Part003 — **SUPPLIED / REGISTERED / NOT ACTIVE**
- split-boundary classifications — **2 / 15 audited**

Audited boundaries:
- **30→31 — GENUINE CONTINUATION**
- **60→61 — CLEAN**

### Audited boundary — 60→61

Part002 scan60 / printed50 and Part003 scan61 / printed51 were directly compared.

Evidence:
- scan60 ends a complete sentence;
- scan61 starts a fresh quoted utterance;
- printed pagination continues **50 → 51**;
- no chapter heading appears at scan61;
- no word/sentence reconstruction is needed across the split;
- no Part003 canonical record was created.

Durable record:
- `PART_002_BOUNDARY_AUDIT_60_61.md`

## Batch-size policy

Normal Tamil verification iterations use **10 physical scans per batch**.

Exact next gate:
- **Part002 English E6 — section09 / scans35–41**

E6 draft + source-check must close before E7. Keep Part003 transcription blocked.
