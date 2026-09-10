# Next Chat Prompt — அரும்பு / scans 11–15 / T3 final source-fidelity checkpoint

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
6. `works/arumbu/T1_BATCH_011_015.md`;
7. `works/arumbu/T2_BATCH_011_015.md`;
8. canonical records `works/arumbu/pages/0011-arumbu-06.md` through `0015-arumbu-11.md`.

## Durable state

Scans 6–10 are CLOSED / VERIFIED after T1+T2+T3.

Scans 11–15:

- T1 — **PASS / COMPLETE**;
- T2 — **PASS / COMPLETE — 1 correction / 0 unresolved**;
- T3 — **NEXT**;
- five canonical records remain `needs-review`;
- directly visible printed pages: **6, 7, 8, 10, 11**;
- **do not infer printed page 9**.

T2 correction:

- scan 12 `திருக்குவள நண்பன்` → **`திருக்குவளை நண்பன்`** — historical `ளை` confirmed from source pixels.

Preserved joins/edges:

- 11→12 `போய்` / `விட்டனர்.`;
- 13→14 `ஊற்றெடுத்துக் கிளம்பிவரும்` / `அருவி!`;
- scan 15 ends physically at `செல்லக்`; scan 16 has not been inspected.

Scan 13's large illustration is non-body material.

## Updated small-task discipline

- **T1** = one direct visual transcription pass only.
- **T2** = independent historical-glyph / character-identity re-read only.
- **T3** = exhaustive final source-fidelity closure.
- synchronize controls and commit after each stage, then stop.

## Exact next activity — scans 11–15 / T3 only

- re-read the five complete scans directly against their canonical records;
- check for omissions, duplicated/displaced text, wrong words, punctuation/spacing, paragraph structure, physical page joins, visible numbering and non-body separation;
- use enlarged crops only where a real T3 reading is uncertain;
- apply only source-supported fidelity corrections;
- retain the T2 `திருக்குவளை` correction unless direct source evidence contradicts it;
- mark all five records `verified` only if the full T3 pass succeeds with no unresolved readings;
- synchronize controls and commit T3 immediately;
- stop.

Do **not** inspect scan 16, start the next batch, begin another component, or start the 1978 `பெரிய இடத்துப் பெண்` witness comparison in this checkpoint.
