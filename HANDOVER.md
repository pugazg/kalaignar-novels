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

1. `அரும்பு` — scans **6–23** — `works/arumbu/` — **ACTIVE**.
2. `சாரப்பள்ளம் சாமுண்டி` — scans **24–48** — queued.
3. `பெரிய இடத்துப் பெண்` — scans **49–74** — additional 1978 witness only; existing controlling source/canonical freeze unchanged.
4. `நடுத்தெரு நாராயணி` — scans **75–90** — queued.

Scans 1–5 are collection front matter; scans 91–92 publisher catalogue/back-cover matter.

## Small-task checkpoint workflow

Root `SOURCE_BATCH_CHECKPOINT_WORKFLOW.md` is authoritative: T1 direct visual transcription → sync/commit/stop; T2 independent historical-glyph re-read → sync/commit/stop; T3 final source-fidelity closure → sync/commit/stop. Do not fold later-stage work into an earlier checkpoint.

## `அரும்பு` durable state

- work span: **18 scans — physical 6–23**;
- canonical records: **15 / 18 — scans 6–20**;
- verified canonical records: **15 / 18 — scans 6–20 contiguous**;
- scans 6–10 T1/T2/T3: **PASS / COMPLETE**;
- scans 11–15 T1/T2/T3: **PASS / COMPLETE**;
- scans 16–20 T1: **PASS / COMPLETE**;
- scans 16–20 T2: **PASS / COMPLETE — 1 correction / 0 unresolved**;
- scans 16–20 T3: **PASS / COMPLETE — 11 additional corrections / 0 unresolved**;
- scans 21–23 T1: **NEXT**;
- assembled Tamil and English remain BLOCKED.

Scans 16–20 directly visible printed pages: **12, 13, 14, 15, 16**. Preserved joins: 15→16 `செல்லக்` / `குழந்தையை—...`; 16→17 `அவர்களைக்-` / `கவனிக்கிறான்.`; 18→19 `செலவா` / `யிற்று.`; 19→20 `கடிந்துகொண்` / `டிருக்கிறாள்.`.

T3 restored source-supported wording including `அனுயாசமாகக்`, `இருதயத்திலே`, `அடியெடுத்து வைத்த`, `அலுவலகத்திலிருந்து`, `என்ற ஆராய்ச்சியில்`, `பழகும், வளமும் இருக்கும் போதே`, scan-19 wording/spacing, and scan-20 `தூங்காமல் புரண்டுகொண்டிருந்த குமார், மெதுவாக எழுந்தான்.`. Unresolved source readings: **0**.

## Exact next activity

Execute **`அரும்பு` scans 21–23 / T1 only**:

- visually transcribe each complete physical scan once;
- create canonical `needs-review` records;
- record only directly visible printed-page numbers;
- preserve physical joins, illustrations and non-body marks separately;
- synchronize affected controls and commit T1 immediately;
- stop before T2 and before starting `சாரப்பள்ளம் சாமுண்டி`.
