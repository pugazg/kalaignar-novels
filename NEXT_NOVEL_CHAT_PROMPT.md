# Next Chat Prompt — அரும்பு / scans 16–20 / T3 source-fidelity checkpoint

Continue in `pugazg/kalaignar-novels`, branch `main`, active source `collections/arumbu-1978/`, active work `works/arumbu/`. **LIVE MAIN IS AUTHORITATIVE.**

## Controlling source

`TVA_BOK_0064361_அரும்பு.pdf`

- SHA-256 `04a3013e1f58a1800867acc5d2f159976c47994a64478036e6fe0201edf120bc`
- **117,270,339 bytes**
- **92 physical scans**
- image-only
- தமிழ்க்கனி பதிப்பகம், சென்னை-28
- முதற் பதிப்பு 1978
- source PDF must **not** be committed.

## Durable compilation structure

- scans 1–5 — collection front matter;
- scans 6–23 — `அரும்பு` — ACTIVE;
- scans 24–48 — `சாரப்பள்ளம் சாமுண்டி` — queued;
- scans 49–74 — `பெரிய இடத்துப் பெண்` — additional witness only;
- scans 75–90 — `நடுத்தெரு நாராயணி` — queued;
- scans 91–92 — publisher catalogue/back cover.

## Mandatory startup

Read before source-dependent work:

1. `SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`;
2. root `HANDOVER.md`;
3. `works/arumbu/README.md`;
4. `works/arumbu/indexes/page-map.md`;
5. `works/arumbu/audit.md`;
6. `works/arumbu/T1_BATCH_016_020.md`;
7. `works/arumbu/T2_BATCH_016_020.md`;
8. canonical records `works/arumbu/pages/0016-arumbu-12.md` through `0020-arumbu-16.md`.

## Durable state

Scans 6–15 are CLOSED / VERIFIED after T1+T2+T3.

Scans 16–20:

- T1 — **PASS / COMPLETE**;
- T2 — **PASS / COMPLETE — 1 character-identity correction / 0 unresolved**;
- T3 — **NEXT**;
- five canonical records exist and remain `needs-review`;
- directly visible printed pages: **12, 13, 14, 15, 16**.

T2 correction:

- scan 17 / printed 13: `தனியாத பாசத்தைத்` → **`தணியாத பாசத்தைத்`**; source shows retroflex `ண`.

Preserved joins/edges:

- 15→16 `செல்லக்` / `குழந்தையை—...`;
- 16→17 `அவர்களைக்-` / `கவனிக்கிறான்.`;
- 18→19 `செலவா` / `யிற்று.`;
- 19→20 `கடிந்துகொண்` / `டிருக்கிறாள்.`.

## Small-task discipline

- **T1** = one direct visual transcription pass only.
- **T2** = independent historical-glyph / character-identity re-read only.
- **T3** = exhaustive final source-fidelity closure.
- synchronize controls and commit after each stage, then stop.

## Exact next activity — scans 16–20 / T3 only

- compare all five complete canonical records line-by-line against direct source pixels;
- check omissions, duplicated or misplaced text, source spelling, punctuation and spacing, dialogue marks, paragraph boundaries, physical joins and any non-body material;
- do not silently normalize grammar or vocabulary;
- apply only direct-source-supported corrections;
- if any reading remains genuinely unresolved, keep the affected page `needs-review` and record the hold;
- if the batch fully passes, mark all five pages `verified`;
- create/update dedicated `T3_BATCH_016_020.md`;
- synchronize controls and commit T3 immediately;
- stop.

Do **not** inspect or transcribe scan 21, begin another component, or start the 1978 `பெரிய இடத்துப் பெண்` witness comparison in this checkpoint.
