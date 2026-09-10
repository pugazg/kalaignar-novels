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

1. `அரும்பு` — scans **6–23** — `works/arumbu/` — **ACTIVE; final batch T1 complete, T2 next**.
2. `சாரப்பள்ளம் சாமுண்டி` — scans **24–48** — queued.
3. `பெரிய இடத்துப் பெண்` — scans **49–74** — additional 1978 witness only; existing controlling source/canonical freeze unchanged.
4. `நடுத்தெரு நாராயணி` — scans **75–90** — queued.

Scans 1–5 are collection front matter; scans 91–92 publisher catalogue/back-cover matter.

## Small-task checkpoint workflow

Root `SOURCE_BATCH_CHECKPOINT_WORKFLOW.md` is authoritative: T1 direct visual transcription → sync/commit/stop; T2 independent historical-glyph re-read → sync/commit/stop; T3 final source-fidelity closure → sync/commit/stop. Do not fold later-stage work into an earlier checkpoint.

## `அரும்பு` durable state

- work span: **18 scans — physical 6–23**;
- canonical records: **18 / 18 — scans 6–23**;
- verified canonical records: **15 / 18 — scans 6–20 contiguous**;
- scans 6–10 T1/T2/T3: **PASS / COMPLETE**;
- scans 11–15 T1/T2/T3: **PASS / COMPLETE**;
- scans 16–20 T1: **PASS / COMPLETE**;
- scans 16–20 T2: **PASS / COMPLETE — 1 correction / 0 unresolved**;
- scans 16–20 T3: **PASS / COMPLETE — 11 additional corrections / 0 unresolved**;
- scans 21–23 T1: **PASS / COMPLETE**;
- scans 21–23 T2: **NEXT**;
- scans 21–23 T3: BLOCKED by T2;
- assembled Tamil and English remain BLOCKED.

Scans 21–23 directly visible printed pages: **17, 18, 19**. Scan 21 T1 was committed separately at `89c41ba57f634bf222cb484d605f32217ccb7176`; scans 22–23 completed the bounded T1 range and the controls are now synchronized.

Preserved final-batch continuity: 20→21 `அவனது அம்மா படம்!` / `அதை எடுத்து...`; 21→22 `அப்பா பாப்பாவை நினைத்து` / `அழுதுகொண்டே யிருக்கிறாரே!`; 22→23 completed sentence / new paragraph `அவளையறியாமல்,...`.

Scan 23 is the final physical page of `அரும்பு`; no explicit `முற்றும்` is printed. The three final records remain `needs-review` until T2 and T3 pass.

## Exact next activity

Execute **`அரும்பு` scans 21–23 / T2 only**:

- independently re-read all three complete physical scans against `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`;
- explicitly check the sensitive historical glyph families required by the guide;
- correct character identity only when direct source pixels support it;
- use crops/enhancements only for genuinely uncertain readings;
- record corrections and any unresolved glyphs in the work/batch audit;
- synchronize affected controls and commit T2 immediately;
- stop before T3 and before starting `சாரப்பள்ளம் சாமுண்டி`.
