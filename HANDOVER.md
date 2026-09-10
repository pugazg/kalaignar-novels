# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Live `main` is authoritative.
- Active source: **1978 `அரும்பு` four-story compilation**.
- Active work: `works/arumbu/`.
- `works/vellikkizhamai/` remains RELEASE-READY / CLOSED.

## Controlling compilation source

`TVA_BOK_0064361_அரும்பு.pdf`

- SHA-256: `04a3013e1f58a1800867acc5d2f159976c47994a64478036e6fe0201edf120bc`
- size: **117,270,339 bytes**
- physical scans: **92**
- image-only
- publisher: **தமிழ்க்கனி பதிப்பகம், சென்னை-28**
- edition: **முதற் பதிப்பு — 1978**
- source PDF: **DO NOT COMMIT**.

Collection-level intake: `collections/arumbu-1978/` — **COMPLETE**.

## Component map

1. `அரும்பு` — scans **6–23** — `works/arumbu/` — **ACTIVE; page-level T1/T2/T3 COMPLETE, whole-work Tamil audit NEXT**.
2. `சாரப்பள்ளம் சாமுண்டி` — scans **24–48** — queued.
3. `பெரிய இடத்துப் பெண்` — scans **49–74** — additional 1978 witness only; existing controlling source/canonical freeze unchanged.
4. `நடுத்தெரு நாராயணி` — scans **75–90** — queued.

Scans 1–5 are collection front matter; scans 91–92 publisher catalogue/back-cover matter.

## Small-task checkpoint workflow

Root `SOURCE_BATCH_CHECKPOINT_WORKFLOW.md` is authoritative for bounded source batches: T1 direct visual transcription → sync/commit/stop; T2 independent historical-glyph re-read → sync/commit/stop; T3 final source-fidelity closure → sync/commit/stop.

After full page-level coverage closes, `NOVEL_PROCESSING_GUIDE.md` Section 12 requires a separate whole-work Tamil audit before assembled Tamil or translation work.

## `அரும்பு` durable state

- work span: **18 scans — physical 6–23**;
- canonical records: **18 / 18 — scans 6–23**;
- verified canonical records: **18 / 18 — scans 6–23 contiguous**;
- scans 6–10 T1/T2/T3: **PASS / COMPLETE**;
- scans 11–15 T1/T2/T3: **PASS / COMPLETE**;
- scans 16–20 T1: **PASS / COMPLETE**;
- scans 16–20 T2: **PASS / COMPLETE — 1 correction / 0 unresolved**;
- scans 16–20 T3: **PASS / COMPLETE — 11 additional corrections / 0 unresolved**;
- scans 21–23 T1: **PASS / COMPLETE**;
- scans 21–23 T2: **PASS / COMPLETE — 0 corrections / 0 unresolved**;
- scans 21–23 T3: **PASS / COMPLETE — 4 additional corrections / 0 unresolved**;
- page-level source gates: **CLOSED / VERIFIED — 18 / 18**;
- whole-work Tamil audit: **NEXT**;
- assembled Tamil and English remain BLOCKED.

Final-batch T3 corrections:

- scan 21 `பார்த்தான்:` → `பார்த்தான்.`;
- scan 21 `கிடந்தன:` → `கிடந்தன.`;
- scan 22 `ஆஸ்பத்திரியிலே` → `ஆஸ்பத்திரியில்`;
- scan 23 `இனி......` → `இனி:......`.

T2-confirmed source readings `பேசினேன்` (scan 22) and `அம்மனார்` (scan 23) remain unchanged. Scans 21–23 directly visible printed pages are **17, 18, 19**. Scan 23 is the final physical page of `அரும்பு`; no explicit `முற்றும்` is printed.

Preserved final-batch continuity: 20→21 `அவனது அம்மா படம்!` / `அதை எடுத்து...`; 21→22 `அப்பா பாப்பாவை நினைத்து` / `அழுதுகொண்டே யிருக்கிறாரே!`; 22→23 completed sentence / new paragraph `அவளையறியாமல்,...`.

## Exact next activity

Execute the **whole-work Tamil audit gate for `அரும்பு` only** under `NOVEL_PROCESSING_GUIDE.md` Section 12:

- reconcile all **18 / 18** canonical records and the page map; confirm no coverage gap;
- confirm source/work metadata against the controlling compilation and `works/arumbu/metadata/source.md`;
- confirm printed-page mapping is source-supported and scan 6 remains unnumbered rather than inferred;
- confirm cross-page continuity, body/page-type identity and non-body separation;
- confirm all historical-glyph/source issues are resolved or explicitly documented; current unresolved count is 0;
- confirm no silent modernization/correction remains;
- confirm the source PDF is still excluded from the repository;
- record a clear whole-work Tamil audit PASS/hold result in `works/arumbu/audit.md` and synchronize affected controls;
- commit the audit checkpoint and stop.

Do **not** begin assembled Tamil, English, the 1978 `பெரிய இடத்துப் பெண்` witness comparison, or `சாரப்பள்ளம் சாமுண்டி` in the same checkpoint.
