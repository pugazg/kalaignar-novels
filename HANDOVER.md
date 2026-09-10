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

## Component map

1. `அரும்பு` — scans **6–23** — `works/arumbu/` — **ACTIVE**.
2. `சாரப்பள்ளம் சாமுண்டி` — scans **24–48** — queued.
3. `பெரிய இடத்துப் பெண்` — scans **49–74** — additional 1978 witness only; existing controlling source/canonical freeze unchanged.
4. `நடுத்தெரு நாராயணி` — scans **75–90** — queued.

Scans 1–5 are collection front matter; scans 91–92 publisher catalogue/back-cover matter.

## Small-task checkpoint workflow

Root `SOURCE_BATCH_CHECKPOINT_WORKFLOW.md` is authoritative:

1. **T1** — one direct visual transcription pass + canonical records + exact visible numbering → control sync → commit → stop;
2. **T2** — independent historical-glyph re-read → control sync → commit → stop;
3. **T3** — final source-fidelity closure → control sync → commit → stop;
4. only then may the next source batch begin.

Do not fold repeated crop loops, historical-glyph verification, or exhaustive fidelity checking into T1. A difficult T1 reading may remain `needs-review` for T2/T3.

## `அரும்பு` durable state

- work span: **18 scans — physical 6–23**;
- canonical records: **10 / 18 — scans 6–15**;
- verified canonical records: **5 / 18 — scans 6–10**;
- scans 6–10 T1/T2/T3: **PASS / COMPLETE**;
- scans 11–15 T1: **PASS / COMPLETE**;
- scans 11–15 T2: **NEXT**;
- scans 11–15 T3: BLOCKED by T2;
- scans 16–23: not started.

Scans 11–15 directly visible printed pages: **6, 7, 8, 10, 11**. Printed page **9 is not inferred**.

T1 physical joins/edges retained:

- 11→12: `போய்` / `விட்டனர்.`;
- 13→14: `ஊற்றெடுத்துக் கிளம்பிவரும்` / `அருவி!`;
- scan 15 ends physically at `செல்லக்`; scan 16 was not inspected during T1.

Scan 13 contains a large printed illustration, kept outside narrative text.

Checkpoint records:

- `works/arumbu/T1_BATCH_006_010.md` — PASS;
- `works/arumbu/T2_BATCH_006_010.md` — PASS;
- `works/arumbu/T3_BATCH_006_010.md` — PASS;
- `works/arumbu/T1_BATCH_011_015.md` — PASS.

## Numbering/source rule

Record printed page numbers only when directly visible. Never infer missing numbering from sequence. Source pixels control fidelity decisions; OCR/context is not authority.

## Exact next activity

Execute **`அரும்பு` scans 11–15 / T2 only**:

- independently re-read all five complete pages under `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`;
- focus on character identity and known historical-glyph families;
- create targeted crops only for actual uncertainty;
- correct only direct-source-supported character identities;
- record corrections and any unresolved forms;
- keep page status `needs-review` until T3;
- synchronize affected controls and commit T2 separately;
- stop before T3 and before scan 16.

Do not begin another component or the 1978 `பெரிய இடத்துப் பெண்` witness comparison in the same checkpoint.
