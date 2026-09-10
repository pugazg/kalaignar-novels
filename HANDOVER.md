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

1. `அரும்பு` — scans **6–23** — `works/arumbu/` — **ACTIVE; final batch T1+T2 complete, T3 next**.
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
- scans 21–23 T2: **PASS / COMPLETE — 0 corrections / 0 unresolved**;
- scans 21–23 T3: **NEXT**;
- assembled Tamil and English remain BLOCKED.

Scans 21–23 directly visible printed pages: **17, 18, 19**. All three records remain `needs-review` pending T3.

The T2 independent re-read explicitly checked the full known historical-glyph family set on each complete page. No character-identity corrections were required and no historical glyph remains unresolved. Enlarged source pixels directly confirm scan 22 `பேசினேன்` and scan 23 `அம்மனார்`; preserve both unless new direct source evidence proves otherwise.

Preserved final-batch continuity: 20→21 `அவனது அம்மா படம்!` / `அதை எடுத்து...`; 21→22 `அப்பா பாப்பாவை நினைத்து` / `அழுதுகொண்டே யிருக்கிறாரே!`; 22→23 completed sentence / new paragraph `அவளையறியாமல்,...`.

Scan 23 is the final physical page of `அரும்பு`; no explicit `முற்றும்` is printed.

## Exact next activity

Execute **`அரும்பு` scans 21–23 / T3 only**:

- independently compare all three complete physical scans against direct source pixels;
- check omissions, duplicated or unsupported text, source wording, punctuation and paragraph structure;
- confirm page joins, printed-page visibility, page type and non-body separation;
- confirm the T2 character identities and retain source-confirmed `பேசினேன்` / `அம்மனார்` unless pixels directly prove otherwise;
- resolve only what the source directly supports;
- if all mandatory gates pass, mark scans 21–23 verified and close the `அரும்பு` component;
- synchronize affected controls and commit T3 immediately;
- stop before starting `சாரப்பள்ளம் சாமுண்டி`.
