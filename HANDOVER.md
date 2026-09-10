# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Live `main` is authoritative.
- Active source: **1978 `அரும்பு` four-story compilation**.
- Active work: `works/arumbu/`.
- Latest completed work remains `works/vellikkizhamai/` — RELEASE-READY / CLOSED.

## New controlling compilation source

`TVA_BOK_0064361_அரும்பு.pdf`

- SHA-256: `04a3013e1f58a1800867acc5d2f159976c47994a64478036e6fe0201edf120bc`
- size: **117,270,339 bytes**
- physical scans: **92**
- image-only
- title: **அரும்பு**
- author: **கலைஞர் மு. கருணாநிதி**
- publisher: **தமிழ்க்கனி பதிப்பகம், சென்னை-28**
- edition: **முதற் பதிப்பு — 1978**
- source PDF: **DO NOT COMMIT**.

Collection-level intake: `collections/arumbu-1978/` — **COMPLETE**.

The publisher note establishes that the volume contains four Kalaignar stories and uses the first story's title as the volume title.

## Component map

1. `அரும்பு` — physical scans **6–23** — new work `works/arumbu/` — **ACTIVE / transcription 0 of 18 durably committed**.
2. `சாரப்பள்ளம் சாமுண்டி` — scans **24–48** — new work `works/sarapallam-samundi/` — REGISTERED / QUEUED.
3. `பெரிய இடத்துப் பெண்` — scans **49–74** — existing `works/periya-idathup-pen/`; registered as **additional 1978 witness only**. Existing 1953 controlling source and verification freeze remain unchanged. No witness comparison has been run.
4. `நடுத்தெரு நாராயணி` — scans **75–90** — new work `works/nadutheru-narayani/` — REGISTERED / QUEUED.

Collection front matter: scans **1–5**. Publisher catalogue/back-cover matter: scans **91–92**.

## Numbering/source rule

The component opening scans 6, 24, 49 and 75 do not show a clearly visible printed page number. Use `printed_page: null` unless a number is directly visible; never infer missing numbers from sequence.

Historical Tamil glyph identity must be checked from source pixels. OCR/context is not authority.

## New small-task checkpoint workflow

The user explicitly requested that source batches be broken into smaller durable tasks. Root [`SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`](SOURCE_BATCH_CHECKPOINT_WORKFLOW.md) is now authoritative for active page-level batches.

For each bounded five-scan range:

1. **T1 — direct transcription / canonical page records / printed-page visibility**; synchronize controls and commit; stop.
2. **T2 — independent historical-glyph re-read**; create crops only for actual uncertainty; synchronize controls and commit; stop.
3. **T3 — final source-fidelity closure / page verification where permitted**; synchronize controls and commit; stop.
4. only after T3 may the next scan batch begin.

Do not combine T1, T2 and T3 by default. Every smaller task gets its own control synchronization and commit.

## Closed prior work

`வெள்ளிக்கிழமை / Friday` is RELEASE-READY and must remain closed unless genuinely new direct-source evidence or a separately authorized new-edition/derived task appears.

## Exact next activity

Execute **`அரும்பு` scans 6–10 / T1 only**:

- visually transcribe each whole scan once;
- create canonical page records under `works/arumbu/pages/`;
- preserve exact printed-number visibility: scan 6 is unnumbered; record scans 7–10 only from directly visible numbers;
- preserve illustrations/non-body marks separately;
- leave records non-final because T2/T3 are pending;
- synchronize `works/arumbu/README.md`, `indexes/page-map.md`, `audit.md`, root HANDOVER, next prompt and root README as affected;
- commit T1 immediately and stop.

Do **not** perform the independent historical-glyph re-read in the same checkpoint. Do not begin scan 11 or another component.
