# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Live `main` is authoritative.
- Active source: **1978 `அரும்பு` four-story compilation**.
- Active work: `works/arumbu/`.
- Latest completed work remains `works/vellikkizhamai/` — RELEASE-READY / CLOSED.

## Controlling compilation source

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

The volume contains four distinct Kalaignar stories; the first story supplies the compilation title.

## Component map

1. `அரும்பு` — physical scans **6–23** — `works/arumbu/` — **ACTIVE**.
2. `சாரப்பள்ளம் சாமுண்டி` — scans **24–48** — `works/sarapallam-samundi/` — REGISTERED / QUEUED.
3. `பெரிய இடத்துப் பெண்` — scans **49–74** — existing `works/periya-idathup-pen/`; **additional 1978 witness only**. Existing 1953 controlling source and canonical verification freeze remain unchanged.
4. `நடுத்தெரு நாராயணி` — scans **75–90** — `works/nadutheru-narayani/` — REGISTERED / QUEUED.

Collection front matter: scans **1–5**. Publisher catalogue/back-cover matter: scans **91–92**.

## Small-task checkpoint workflow

Root [`SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`](SOURCE_BATCH_CHECKPOINT_WORKFLOW.md) is authoritative for active page-level batches:

1. **T1 — direct transcription / canonical records / printed-page visibility** → control sync → commit → stop;
2. **T2 — independent historical-glyph re-read** → control sync → commit → stop;
3. **T3 — final source-fidelity closure** → control sync → commit → stop;
4. only then may the next bounded source batch begin.

## `அரும்பு` durable state

- work span: **18 scans — physical 6–23**;
- canonical records: **5 / 18**;
- current covered range: **scans 6–10**;
- scans 6–10 T1 direct visual transcription: **PASS / COMPLETE**;
- scans 6–10 page states: **5 `needs-review` / 0 verified**;
- scans 6–10 T2 historical-glyph re-read: **NEXT**;
- scans 6–10 T3 final source-fidelity closure: **BLOCKED by T2**;
- scans 11–15: **BLOCKED until scans 6–10 T3 passes**.

Printed-page visibility in the committed T1 range:

- scan 6 — `null` / no visible printed number;
- scan 7 — `2`;
- scan 8 — `3`;
- scan 9 — `4`;
- scan 10 — `5`.

Physical page joins retained in their source records:

- 7→8: `நடந்` / `தேறின.`;
- 8→9: `அபிநய` / `அசைவுகளை...`;
- 9→10: `...வைத்தியரை அழைத்து` / `வந்துவிடுகிறேன்”...`.

T1 audit: `works/arumbu/T1_BATCH_006_010.md`.

## Exact next activity

Run **`அரும்பு` scans 6–10 / T2 only**:

- independently re-read every full page under `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`;
- explicitly check `ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`;
- compare same-edition forms where needed;
- correct only character identity supported by source pixels;
- do not modernize source wording;
- create crops/enhancements only for actual uncertainty;
- record corrections/unresolved forms in page/work audit;
- synchronize controls, commit T2, and stop before T3.

Do not begin scan 11, another component, or the 1978 `பெரிய இடத்துப் பெண்` witness comparison in the same checkpoint.
