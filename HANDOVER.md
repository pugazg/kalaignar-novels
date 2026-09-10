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

1. `அரும்பு` — physical scans **6–23** — new work `works/arumbu/` — **ACTIVE / transcription 0 of 18**.
2. `சாரப்பள்ளம் சாமுண்டி` — scans **24–48** — new work `works/sarapallam-samundi/` — REGISTERED / QUEUED.
3. `பெரிய இடத்துப் பெண்` — scans **49–74** — existing `works/periya-idathup-pen/`; registered as **additional 1978 witness only**. Existing 1953 controlling source and verification freeze remain unchanged. No witness comparison has been run.
4. `நடுத்தெரு நாராயணி` — scans **75–90** — new work `works/nadutheru-narayani/` — REGISTERED / QUEUED.

Collection front matter: scans **1–5**. Publisher catalogue/back-cover matter: scans **91–92**.

## Numbering/source rule

The component opening scans 6, 24, 49 and 75 do not show a clearly visible printed page number. Use `printed_page: null` unless a number is directly visible; never infer missing numbers from sequence.

Historical Tamil glyph identity must be checked from source pixels from the first transcription batch onward. OCR/context is not authority.

## Closed prior work

`வெள்ளிக்கிழமை / Friday` is RELEASE-READY and must remain closed unless genuinely new direct-source evidence or a separately authorized new-edition/derived task appears.

## Exact next activity

Process **`அரும்பு` physical scans 6–10** as one five-scan batch:

1. visually read each full scan once;
2. create canonical page records under `works/arumbu/pages/` using source physical scan numbers;
3. preserve printed-number visibility exactly;
4. transcribe full printed narrative/illustration text without OCR guesswork or normalization;
5. apply the historical-glyph gate during the same pass;
6. create a batch audit record and update `page-map.md`, work README, audit, root HANDOVER and next prompt;
7. commit immediately after the five scans;
8. do not start scan 11 or another component in the same iteration.

Do not compare the 1978 `பெரிய இடத்துப் பெண்` witness yet; that is a separate later activity.