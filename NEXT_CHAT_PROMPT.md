# NEXT CHAT PROMPT — சுருளிமலை / terminal full-198-page reconciliation

Continue directly in `pugazg/kalaignar-novels`, branch `main`, active work `works/surulimalai/`. **LIVE MAIN IS AUTHORITATIVE.**

Fetch live `main` first and preserve any newer durable work. Last observed main while preparing this prompt: `f626026d49c5bd5309a9bc7a26069927e41d8726`.

## Durable transcription state

- scans **1–4 front matter VERIFIED**;
- scans **5–198 T1/T2/T3 VERIFIED**;
- latest closed batch: scans **185–198 — 14/14 VERIFIED**;
- scans185–198 T2 corrections independently re-confirmed: **20/20**;
- scans185–198 additional T3 source-fidelity changes: **13**;
- unresolved after latest T3: **0**;
- omissions / duplicate body spans after latest T3: **0 / 0**;
- visible printed pages **183–195** occur on scans185–197;
- scan198 is **back-cover / publisher-device** matter with no story body;
- chapter **26** — scan186 / printed184;
- chapter **27** — scan193 / printed191;
- scan189 source-visible centered bullet scene dividers are represented as `●`;
- scan189→190 split: `சாதமூட்டை` / `களுடன்`;
- scan190→191 split: `குதிக்காமல்` / `தடுப்பேன்!`;
- scan194→195 split: `தயங்` / `கிற்று.`;
- scan197 source-visible ending: `[முற்றிற்று.]`;
- scan198 publisher device: `திராவிடப்பண்ணை` / `திருச்சி`, plus wrapper-printer imprint.

Latest T3 authority:

`works/surulimalai/T3_AUDIT_185_198.md`

## Exact next activity

Perform the **terminal/full-198-page reconciliation only**.

Do **not** restart T1/T2/T3. Do **not** begin English translation or assembled Tamil work until this reconciliation passes.

The goal is to reconcile the complete physical-source structure and all repository control files so the Tamil archival work can be declared closed without stale parser-era assumptions.

## Read first

1. `HANDOVER.md`
2. `works/surulimalai/README.md`
3. `works/surulimalai/audit.md`
4. `works/surulimalai/indexes/page-map.md`
5. `works/surulimalai/metadata/source.md`
6. `works/surulimalai/TERMINAL_BOUNDARY_AUDIT.md`
7. `works/surulimalai/T3_AUDIT_170_184.md`
8. `works/surulimalai/T3_AUDIT_185_198.md`

## Required reconciliation checks

### 1. Physical source extent

Re-confirm the source structure as **198 physical scans**:

- scans1–4 — front matter;
- scans5–197 — textual/body matter through visible printed page195;
- scan197 — source-visible `[முற்றிற்று.]`;
- scan198 — back-cover / publisher-device, no story body.

Use the complete source representation and/or the already source-verified split derivatives. **Do not use the old 150-page Files-parser ceiling as source authority.**

### 2. Canonical page-record coverage

Verify exactly one canonical record for every physical scan **1–198**.

Important known cleanup point:

- `works/surulimalai/pages/0150-back-cover.md` is an **invalidated parser-era structural record** and must not count as a canonical physical scan record.
- the canonical scan150 record is `works/surulimalai/pages/0150-page-148.md`.

Resolve this stale record cleanly during reconciliation rather than leaving an apparent 199-record canonical set.

### 3. Page-map consistency

Audit `works/surulimalai/indexes/page-map.md` against the canonical page files.

Known inconsistencies to resolve:

- scan **48** and scan **49** canonical records exist and are VERIFIED, but their rows are currently absent from the manifest;
- the manifest currently starts with scan50–54 rows before the table header, a parser-era formatting artifact;
- rows for scans **170–198** are VERIFIED but still contain stale note fragments such as `T3 pending` followed by appended T3-change text.

Rebuild/normalize the manifest so scans **1–198 appear exactly once**, in physical order, with current final status.

### 4. Chapter / continuity sequence

Reconcile all source-visible chapter markers and physical splits from the verified page records.

At minimum preserve the already closed terminal sequence:

- chapter24 — scan174;
- chapter25 — scan181;
- chapter26 — scan186;
- chapter27 — scan193;
- scan169→170 `அந்தப்` / `பொறுப்பினால்`;
- scan175→176 `தவறு` / `களுக்காக`;
- scan181→182 sentence continuation;
- scan189→190 `சாதமூட்டை` / `களுடன்`;
- scan190→191 `குதிக்காமல்` / `தடுப்பேன்!`;
- scan194→195 `தயங்` / `கிற்று.`.

Do not infer missing chapter numbers from sequence alone; use only source-verified records.

### 5. Stale control documents

Update all stale project-control text to the actual final Tamil state.

In particular:

- `works/surulimalai/metadata/source.md` still contains older parser-era statements such as scans95–109 pending T3 and incomplete mapping;
- `works/surulimalai/audit.md` still says intake **IN PROGRESS** and lists terminal reconciliation as open;
- `works/surulimalai/TERMINAL_BOUNDARY_AUDIT.md` is currently the old **INVALIDATED / DO NOT USE** audit and must be superseded by the completed reconciliation result if the gate passes;
- README / HANDOVER / page-map counts and next-activity text must agree.

### 6. Checksum

If the exact full controlling PDF bytes are available in the runtime, compute and record its SHA-256 in `works/surulimalai/metadata/source.md`.

If the exact full source bytes are not available, **do not guess a checksum**. Record checksum as the only remaining provenance item if necessary, but do not conflate that with transcription completeness.

## Pass criteria

Terminal reconciliation passes only if:

- physical scans **1–198** are structurally accounted for;
- exactly one canonical record exists per physical scan;
- canonical scan records **1–198 are VERIFIED**;
- page-map has exactly one ordered row per scan1–198;
- front matter, body, work ending, and scan198 wrapper classification are consistent;
- chapter and split continuity is internally consistent;
- no stale 150-page parser inference survives in active controls;
- README, audit, metadata/source, terminal audit, page-map, and HANDOVER agree;
- no unresolved body-text fidelity issue is reopened.

If all pass, create/update a durable terminal reconciliation document such as:

`works/surulimalai/FINAL_RECONCILIATION.md`

and mark the Tamil archival transcription **CLOSED / PASS — physical scans1–198 fully reconciled**.

## Stop condition

After terminal reconciliation and control-file cleanup, **STOP**.

Do not start English translation or assembled Tamil work in the same activity unless a new explicit next activity in the updated handover calls for it.

No OCR, no web, no alternate edition, no guessing, no modernization. Source pixels and already verified canonical page records remain authoritative.
