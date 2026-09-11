# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- **Live `main` is authoritative.**
- Active source: **1978 `அரும்பு` four-story compilation**.
- Active work: **`works/sarapallam-samundi/`**.
- `works/arumbu/` is **RELEASE-READY / CLOSED**.
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

## Component state

1. `அரும்பு` scans 6–23 — **RELEASE-READY / CLOSED**.
2. `சாரப்பள்ளம் சாமுண்டி` scans 24–48 — **ACTIVE NEXT; T1 scans 24–28**.
3. `பெரிய இடத்துப் பெண்` scans 49–74 — additional 1978 witness only; do not replace its existing controlling edition.
4. `நடுத்தெரு நாராயணி` scans 75–90 — queued.

## Closed `அரும்பு` result

- canonical Tamil **18/18 VERIFIED**;
- assembled Tamil **1/1 PASS**;
- English **18/18 scans / VERIFIED**;
- Section 16 **PASS**, including scan-17 corrective re-open;
- Section 17 rerun **PASS / COMPLETE**;
- final archival/editorial verdict **RELEASE-READY**;
- source PDF excluded.

## Active `சாரப்பள்ளம் சாமுண்டி` state

- work span: **scans 24–48 / 25 scans**;
- scan 24 visibly opens title `சாரப்பள்ளம் சாமுண்டி`;
- scan 24 printed number: not visibly recorded;
- scan 25 prints **21**; scan 48 prints **45**;
- canonical records: **0/25**;
- T1/T2/T3: **NOT STARTED**.

## Exact next activity

Execute **T1 direct transcription for scans 24–28 only** under `SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`. Create/complete five canonical page records, synchronize affected controls, commit, and stop before T2.

Do not begin scans 29+ or any `பெரிய இடத்துப் பெண்` witness comparison in that checkpoint.
