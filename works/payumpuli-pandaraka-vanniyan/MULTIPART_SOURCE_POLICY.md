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
- active Part — **Part006 / scans151–180**
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
- Part005 — **FINAL CLOSED / FROZEN**
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
- English editorial review — **PASS / CLOSED**
- editorial English-only changes — **3**
- source-alignment corrections within editorial total — **1**
- unresolved editorial holds — **0**
- whole-Part bilingual review — **PASS / CLOSED**
- bilingual English-only corrections — **0**
- unresolved bilingual holds — **0**
- unresolved Tamil-fidelity holds — **0**
- release/readiness — **PASS / CLOSED**
- unresolved release/readiness blockers — **0**
- source PDFs in active work tree — **0**
- release-ready synchronization — **PASS / CLOSED**
- release-sync canonical/assembled/English body changes — **0**
- release-sync protected source-variant collapses — **0**
- Part006 leakage — **0**
- final closure — **PASS / CLOSED / FROZEN**
- Part006 — **ACTIVE / AUTHORIZED — E27–E33 SOURCE-CHECKED / GLOSSARY RECONCILIATION NEXT**
- Part006 canonical page records — **30/30 verified**
- Part006 visual fidelity — **30/30 verified**
- Part006 Pass1 / Pass2A / Pass2B / Pass3 — **COMPLETE / PASS**
- Part006 Part audit — **PASS / COMPLETE**
- Part006 final metadata/status synchronization — **PASS / CLOSED**
- Part006 documentation synchronization — **PASS / COMPLETE**
- Part006 documentation-sync canonical page changes — **0**
- Part006 Tamil archival-ready — **PASS / CLOSED**
- Part006 archival-ready canonical/page-status changes — **0**
- Part006 assembled Tamil — **PASS / CLOSED — 7/7 VERIFIED**
- Part006 English translation planning/setup — **COMPLETE / PASS**
- Part006 planned English batches — **E27–E33 / 7**
- Part006 translated/source-checked English files — **7/7**
- Part006 E27–E33 — **SOURCE-CHECKED / COMPLETE**
- Part006 unresolved English source-check holds — **0**
- Part006 English-batch canonical/assembled Tamil changes — **0**
- frozen Part001–Part005 English body changes caused by Part006 batches — **0**
- Part006 unresolved English planning holds — **0**
- Part006 planning canonical/assembled Tamil changes — **0**
- frozen Part001–Part005 English body changes caused by Part006 planning — **0**
- Part006 assembled canonical coverage — **30/30; omissions / duplicates 0 / 0**
- Part006 canonical page mutations caused by assembly — **0**
- frozen Part001–Part005 assembled-file mutations caused by Part006 assembly — **0**
- Part007 body leakage from Part006 assembly — **0**
- Part006 incoming 150→151 — **GENUINE CONTINUATION / AUDITED**
- Part006 outgoing 180→181 — **GENUINE CONTINUATION / AUDITED**
- Part007 canonical leakage — **0**
- split-boundary classifications — **6 / 15 audited**

Audited boundaries:
- **30→31 — GENUINE CONTINUATION**
- **60→61 — CLEAN**
- **90→91 — GENUINE CONTINUATION**
- **120→121 — GENUINE CONTINUATION**
- **150→151 — GENUINE CONTINUATION**
- **180→181 — GENUINE CONTINUATION**

Durable boundary records:
- `PART_003_BOUNDARY_AUDIT_90_91.md`
- `PART_004_BOUNDARY_AUDIT_120_121.md`
- `PART_005_BOUNDARY_AUDIT_150_151.md`
- `PART_006_BOUNDARY_AUDIT_180_181.md`

## Batch-size policy

Normal Tamil verification iterations use **10 physical scans per batch**.

Exact next gate:

**Part006 whole-Part English glossary reconciliation.**

Part001–Part005 remain frozen. Part007 remains supplied / registered / blocked until Part006 completes its maintained workflow and final closure.


## Part006 closure / Part007 activation

Part006 / scans151–180 is **FINAL CLOSED / FROZEN** after Tamil archival, assembled Tamil, maintained English, glossary, editorial, bilingual, release/readiness and release-ready synchronization all passed with zero unresolved blockers and zero post-release body drift.

Part007 / scans181–210 is **NEXT ACTIVE / AUTHORIZED / NOT STARTED**. Its incoming 180→181 boundary is **GENUINE CONTINUATION / AUDITED**; outgoing 210→211 remains pending direct audit. Canonical Part007 records remain 0 until the next explicit continuation. First Pass1 batch: **scans181–190 / local pages1–10**.

## Part007 verified boundary/frontier synchronization

- Part007 canonical Tamil — **30/30 verified**
- Part007 visual fidelity — **30/30 verified**
- Part007 incoming 180→181 — **GENUINE CONTINUATION / AUDITED**
- Part007 outgoing 210→211 — **GENUINE CONTINUATION / AUDITED**
- split-boundary classifications — **7 / 15 audited**
- newly included audited boundary — **210→211 — GENUINE CONTINUATION**
- durable outgoing record — `PART_007_BOUNDARY_AUDIT_210_211.md`
- Part008 canonical records — **0**
- exact next gate — **Part007 Tamil archival-ready checkpoint**

Part001–Part006 remain frozen.

## Part007 assembled Tamil closure checkpoint

**PART007 ASSEMBLED TAMIL — COMPLETE / PASS / CLOSED.**

- canonical Tamil — **30/30 verified**
- visual fidelity — **30/30 verified**
- Part audit — **PASS / COMPLETE**
- final metadata/status synchronization — **PASS / CLOSED**
- documentation synchronization — **PASS / COMPLETE**
- Tamil archival-ready — **PASS / CLOSED**
- assembled Tamil — **6/6 VERIFIED / CLOSED**
- assembled canonical coverage — **30/30**
- omissions / duplicates — **0 / 0**
- unsupported Tamil body insertion — **0**
- audit-note leakage — **0**
- canonical Part007 page mutations caused by assembly — **0**
- frozen Part001–Part006 assembled-file mutations — **0**
- Part008 body leakage — **0**
- incoming 180→181 — **GENUINE CONTINUATION / AUDITED**
- outgoing 210→211 — **GENUINE CONTINUATION / AUDITED**
- Part008 canonical records — **0**
- unresolved blockers — **0**

Durable validation:
- `works/payumpuli-pandaraka-vanniyan/PART_007_ASSEMBLED_TAMIL_VALIDATION.md`

Exact next gate:

**Part007 English translation planning/setup.**

## Part007 English planning/setup checkpoint

**PART007 ENGLISH TRANSLATION PLANNING/SETUP — COMPLETE / PASS.**

- Tamil canonical pages — **30/30 verified**
- Tamil assembled files — **6/6 VERIFIED / CLOSED**
- planned English batches — **E34–E39 / 6**
- planned maintained English files — **6**
- translated files — **0/6**
- source-checked files — **0/6**
- unresolved planning holds — **0**
- English literary prose drafted in planning gate — **0**
- canonical Tamil edits caused by planning — **0**
- assembled Tamil edits caused by planning — **0**
- frozen Part001–Part006 English body edits — **0**
- incoming 180→181 — **GENUINE CONTINUATION / AUDITED**
- outgoing 210→211 — **GENUINE CONTINUATION / AUDITED**
- Part008 leakage — **0**

Active English controls:
- `translations/en/PART_007_TRANSLATION_PLAN.md`
- `translations/en/PART_007_GLOSSARY.md`
- `translations/en/PART_007_PROGRESS.md`

Exact next gate:

**E34 draft + source-check — section37 / scans181–183.**

## Part007 English E34–E39 closure checkpoint

**PART007 E34–E39 — SOURCE-CHECKED / COMPLETE.**

- canonical Tamil — **30/30 verified**
- assembled Tamil — **6/6 VERIFIED / CLOSED**
- maintained Part007 English files — **6/6**
- translated files — **6/6**
- source-checked files — **6/6**
- source coverage — **scans181–210 / all 30 physical pages**
- unresolved English source-check holds — **0**
- canonical Tamil edits caused by English — **0**
- assembled Tamil edits caused by English — **0**
- frozen Part001–Part006 English body edits — **0**
- incoming 180→181 boundary integrity — **PASS / AUDITED**
- outgoing 210→211 boundary integrity — **PASS / AUDITED**
- Part008 leakage — **0**

English batch records:
- `translations/en/E34_SOURCE_CHECK.md`
- `translations/en/E35_SOURCE_CHECK.md`
- `translations/en/E36_SOURCE_CHECK.md`
- `translations/en/E37_SOURCE_CHECK.md`
- `translations/en/E38_SOURCE_CHECK.md`
- `translations/en/E39_SOURCE_CHECK.md`

Exact next gate:

**Part007 whole-Part English glossary reconciliation across E34–E39.**

## Part007 final closure checkpoint

**PART007 FINAL CLOSURE — PASS / CLOSED / FROZEN.**

- complete Tamil / assembled / English chain — **CLOSED**
- release/readiness — **PASS / CLOSED**
- release-ready synchronization — **PASS / CLOSED**
- unresolved blockers — **0**
- Part008 leakage — **0**
- Part001–Part007 — **FINAL CLOSED / FROZEN**
- Part008 — **NEXT ACTIVE / AUTHORIZED / NOT STARTED**
- Part008 canonical records — **0**
- next activity — **Part008 Pass1 scans211–220 / local pages1–10**

## Current authoritative frontier — Part008 documentation synchronized

- Part001–Part007 — **FINAL CLOSED / FROZEN**
- Part008 / scans211–240 — **ACTIVE / VERIFIED / DOCUMENTATION SYNCHRONIZED**
- Part008 canonical records — **30/30**
- Part008 Tamil textual status — **30/30 verified**
- Part008 visual fidelity — **30/30 verified**
- Part008 Pass1 / Pass2A / Pass2B / Pass3 — **COMPLETE / PASS**
- Part008 correction ledger — **2 Pass2A + 3 Pass2B + 0 Pass3**
- Part008 Part audit — **PASS / COMPLETE**
- Part008 final metadata/status synchronization — **PASS / CLOSED**
- Part008 documentation synchronization — **PASS / COMPLETE**
- Part008 incoming 210→211 — **GENUINE CONTINUATION / AUDITED**
- Part008 outgoing 240→241 — **GENUINE CONTINUATION / AUDITED**
- documentation-sync canonical page changes — **0**
- Part009 canonical records — **0**
- split-boundary classifications — **8 / 15 audited**

Audited boundaries through the current frontier:
- **30→31 — GENUINE CONTINUATION**
- **60→61 — CLEAN**
- **90→91 — GENUINE CONTINUATION**
- **120→121 — GENUINE CONTINUATION**
- **150→151 — GENUINE CONTINUATION**
- **180→181 — GENUINE CONTINUATION**
- **210→211 — GENUINE CONTINUATION**
- **240→241 — GENUINE CONTINUATION**

Exact next gate: **Part008 Tamil archival-ready checkpoint**.

Part009 remains supplied / registered / blocked until Part008 completes its maintained workflow and final closure.

## Current authoritative frontier — Part008 Tamil archival-ready

- Part001–Part007 — **FINAL CLOSED / FROZEN**
- Part008 / scans211–240 — **ACTIVE / TAMIL ARCHIVAL-READY / ASSEMBLY NEXT**
- Part008 canonical records — **30/30 verified**
- Part008 visual fidelity — **30/30 verified**
- Part008 Pass1 / Pass2A / Pass2B / Pass3 — **COMPLETE / PASS**
- Part008 correction ledger — **2 Pass2A + 3 Pass2B + 0 Pass3**
- Part008 Part audit — **PASS / COMPLETE**
- Part008 final metadata/status synchronization — **PASS / CLOSED**
- Part008 documentation synchronization — **PASS / COMPLETE**
- Part008 Tamil archival-ready — **PASS / CLOSED**
- Part008 incoming 210→211 — **GENUINE CONTINUATION / AUDITED**
- Part008 outgoing 240→241 — **GENUINE CONTINUATION / AUDITED**
- archival-ready canonical/page-status changes — **0 / 0**
- Part009 canonical records — **0**
- split-boundary classifications — **8 / 15 audited**

Exact next gate: **Part008 assembled Tamil construction + audit**.

Part009 remains supplied / registered / blocked until Part008 completes its maintained workflow and final closure.

## Current authoritative frontier — Part008 assembled Tamil closed

- Part001–Part007 — **FINAL CLOSED / FROZEN**
- Part008 / scans211–240 — **ACTIVE / ASSEMBLED TAMIL CLOSED / ENGLISH PLANNING NEXT**
- Part008 canonical Tamil — **30/30 verified**
- Part008 visual fidelity — **30/30 verified**
- Part008 Tamil archival-ready — **PASS / CLOSED**
- Part008 assembled Tamil — **PASS / CLOSED — 6/6 VERIFIED**
- Part008 assembled coverage — **30/30**
- Part008 assembly omissions / duplicates — **0 / 0**
- Part008 assembly unsupported body / audit-note leakage — **0 / 0**
- Part008 canonical page mutations caused by assembly — **0**
- frozen Part001–Part007 assembled-file mutations — **0**
- Part009 body leakage — **0**
- Part009 canonical records — **0**

Exact next gate: **Part008 English translation planning/setup**.

Part009 remains supplied / registered / blocked until Part008 completes its maintained workflow and final closure.

## Part008 English planning downstream state

**PART008 ENGLISH TRANSLATION PLANNING/SETUP — COMPLETE / PASS.**

- live batch-number collision check — **PASS**
- prior closed frontier — **E39**
- Part008 reserved sequence — **E40–E45**
- planned maintained English files — **6**
- translated files — **0/6**
- source-checked files — **0/6**
- unresolved planning holds — **0**
- English literary prose drafted in planning — **0**
- canonical Tamil edits caused by planning — **0**
- assembled Tamil edits caused by planning — **0**
- frozen Part001–Part007 English body edits — **0**
- incoming 210→211 — **GENUINE CONTINUATION / AUDITED**
- outgoing 240→241 — **GENUINE CONTINUATION / AUDITED**
- Part009 English leakage — **0**

Planning controls:
- `translations/en/PART_008_TRANSLATION_PLAN.md`
- `translations/en/PART_008_GLOSSARY.md`
- `translations/en/PART_008_PROGRESS.md`

Exact next gate: **E40 draft + source-check — section43 / scans211–212**.

E41 remains blocked until E40 is **SOURCE-CHECKED / COMPLETE**.

## Part008 English E40–E45 downstream state

**PART008 E40–E45 — SOURCE-CHECKED / COMPLETE.**

- English batches — **E40–E45 / 6**
- maintained English files — **6/6**
- source coverage — **scans211–240 / 30**
- translated/source-checked — **6/6 / 6/6**
- unresolved English source-check holds — **0**
- canonical Tamil edits caused by English — **0**
- assembled Tamil edits caused by English — **0**
- frozen Part001–Part007 English body edits — **0**
- incoming 210→211 — **GENUINE CONTINUATION / AUDITED**
- outgoing 240→241 — **GENUINE CONTINUATION / AUDITED**
- Part009 English leakage — **0**

Exact next gate: **Part008 whole-Part English glossary reconciliation across E40–E45**.

Do not begin editorial review until glossary reconciliation closes.

## Part008 release-ready synchronization checkpoint

**PART008 RELEASE-READY SYNCHRONIZATION — PASS / CLOSED.**

- canonical Tamil — **30/30 verified**
- assembled Tamil — **6/6 VERIFIED / CLOSED**
- E40–E45 — **6/6 SOURCE-CHECKED / COMPLETE**
- whole-Part glossary reconciliation — **RECONCILED / PASS**
- English editorial review — **PASS / CLOSED**
- editorial English-only changes — **1**
- whole-Part bilingual review — **PASS / CLOSED**
- bilingual English-only corrections — **1**
- release/readiness — **PASS / CLOSED**
- unresolved blockers — **0**
- canonical / assembled / English body changes in release-ready synchronization — **0 / 0 / 0**
- frozen Part001–Part007 body changes — **0**
- Part009 canonical/body leakage — **0**
- incoming 210→211 — **GENUINE CONTINUATION / AUDITED**
- outgoing 240→241 — **GENUINE CONTINUATION / AUDITED**

Exact next gate: **Part008 final closure**.

Do not begin Part009 canonical transcription until final closure passes.
