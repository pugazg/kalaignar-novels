# Audit — அரும்பு

## Gate state

| Stage | Status |
|---|---|
| Collection/source intake | **PASS / COMPLETE** |
| Work identity / scan boundary | **PASS — scans 6–23** |
| Page-level Tamil transcription | **COMPLETE — 18 / 18 canonical records** |
| Scans 6–10 T1/T2/T3 | **PASS / COMPLETE — VERIFIED** |
| Scans 11–15 T1/T2/T3 | **PASS / COMPLETE — VERIFIED** |
| Scans 16–20 T1 | **PASS / COMPLETE** |
| Scans 16–20 T2 | **PASS / COMPLETE — 1 correction / 0 unresolved** |
| Scans 16–20 T3 | **PASS / COMPLETE — 11 corrections / 0 unresolved** |
| Scans 21–23 T1 | **PASS / COMPLETE** |
| Scans 21–23 T2 | **PASS / COMPLETE — 0 corrections / 0 unresolved** |
| Scans 21–23 T3 | **PASS / COMPLETE — 4 corrections / 0 unresolved** |
| Verified canonical pages | **18 / 18 — scans 6–23 contiguous** |
| Whole-work Tamil audit | **NEXT** |
| Assembled Tamil | BLOCKED until whole-work Tamil audit passes |
| English | BLOCKED |

No source PDF is committed.

## Checkpoint model

The active workflow follows root `SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`: T1 direct visual first pass, T2 independent historical-glyph / character-identity re-read, T3 final source-fidelity closure. Every bounded source checkpoint is synchronized and committed separately.

## Closed page-level batches

Scans 6–10, 11–15, 16–20 and 21–23 now have T1 + T2 + T3 **PASS / COMPLETE** and all **18 / 18** canonical records are **VERIFIED**.

### Scans 16–20 — CLOSED / VERIFIED

- T1 — PASS / COMPLETE;
- T2 — PASS / COMPLETE, **1** character-identity correction (`தனியாத` → `தணியாத`), 0 unresolved;
- T3 — PASS / COMPLETE, **11** additional source-fidelity corrections, 0 unresolved.

### Scans 21–23 — CLOSED / VERIFIED

- T1 — PASS / COMPLETE;
- T2 — PASS / COMPLETE, **0** character-identity corrections / **0** unresolved historical glyphs;
- T3 — PASS / COMPLETE, **4** additional source-fidelity corrections / **0** unresolved source readings;
- directly visible printed pages: **17, 18, 19**;
- scan 23 is the final physical page of `அரும்பு`; no explicit `முற்றும்` is printed.

T3 corrections:

1. scan 21 `குமார் எழுந்து பார்த்தான்:` → `குமார் எழுந்து பார்த்தான்.`;
2. scan 21 `சன்னல்கள் எல்லாம் மூடிக் கிடந்தன:` → `சன்னல்கள் எல்லாம் மூடிக் கிடந்தன.`;
3. scan 22 `ஆஸ்பத்திரியிலே` → `ஆஸ்பத்திரியில்`;
4. scan 23 final `இனி......` → `இனி:......`.

T2-confirmed source readings remain unchanged:

- scan 22 — `பேசினேன்`;
- scan 23 — `அம்மனார்`.

Physical continuity retained across the component, including final joins: 20→21 `அவனது அம்மா படம்!` / `அதை எடுத்து...`; 21→22 `அப்பா பாப்பாவை நினைத்து` / `அழுதுகொண்டே யிருக்கிறாரே!`; 22→23 completed sentence / new paragraph.

## Whole-work Tamil audit — pending

Page-level verification is complete, but the Section 12 Tamil audit in `NOVEL_PROCESSING_GUIDE.md` has not yet been declared PASS. That audit must reconcile:

- complete 18-record inventory and page-map coverage;
- source/work metadata and structural identity;
- source-supported printed-page mapping;
- cross-page continuity and page-type/non-body separation;
- historical-glyph coverage and unresolved-item state;
- absence of silent modernization/correction;
- source PDF exclusion from the repository.

## Exact next activity

Execute the **whole-work Tamil audit gate for `அரும்பு` only**. Record a clear PASS/hold result, synchronize controls, commit, and stop before assembled Tamil, English, or `சாரப்பள்ளம் சாமுண்டி`.
