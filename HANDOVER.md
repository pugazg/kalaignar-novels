# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- **Live main is authoritative.**
- Active work: **`works/periya-idathup-pen/` — 1978 additional-witness comparison**
- `works/sarapallam-samundi/`: **RELEASE-READY / CLOSED**
- 1953 `பெரிய இடத்துப் பெண்` package: **RELEASE-READY WITH CANONICAL-TAMIL VERIFICATION QUALIFICATION**

## Controlling 1953 source

`TVA_BOK_0064090_பெரிய_இடத்துப்_பெண்_1953.pdf`

- SHA-256: `50db9c55d670065bd81088ee07e4527f5531a9ab15e3c4533d6b10eda8d09e9628`
- size: **70,952,481 bytes**
- scans: **49**
- edition: **எட்டாம் பதிப்பு — ஜூலை 1953**
- controlling source: **YES**
- source PDF committed: **No**
- canonical state: **0 verified / 49 needs-review — verification freeze ACTIVE**
- assembled Tamil: **PASSED**
- whole-work English: **VERIFIED**
- release verdict: **RELEASE-READY WITH CANONICAL-TAMIL VERIFICATION QUALIFICATION**

## Active 1978 additional witness

`TVA_BOK_0064361_அரும்பு.pdf`

- SHA-256: `04a3013e1f58a1800867acc5d2f159976c47994a64478036e6fe0201edf120bc`
- size: **117,270,339 bytes**
- compilation scans: **92**
- edition: **முதற் பதிப்பு — 1978**
- publisher: **தமிழ்க்கனி பதிப்பகம், சென்னை-28**
- witness physical scans: **49–74 / 26 scans**
- controlling source: **NO — witness only**
- source PDF committed: **No**

## Durable witness-comparison state

- comparison plan: `works/periya-idathup-pen/witness-comparison/arumbu-1978/COMPARISON_PLAN.md` — **PASS / COMPLETE**;
- source-visible map: `works/periya-idathup-pen/witness-comparison/arumbu-1978/SCAN_MAP.md` — **PASS / COMPLETE**;
- progress: **0 / 26 scans compared; 0 / 6 batches complete**;
- confirmed textual variants: **0**;
- confirmed paratext variants: **1** — the 1953 printer colophon is absent after the 1978 narrative ending;
- canonical / assembled / English changes: **0**.

Source-visible mapping facts:

- scan49 — unnumbered title/opening;
- scan50 — printed47;
- scan53 / p50 — `உத்தண்டி`;
- scan56 / p53 — `கண்ணம்மா`;
- scan57 — one physical spread containing printed **54–55**;
- scan64 / p62 — `குமுதா`;
- scan67 / p65 — `வீரன்`;
- scan71 / p69 — `உலகநாதர்`;
- scan72 / p70 — final `கண்ணம்மா`;
- scan74 / p72 — narrative ending.

## Authority rules

- The **1953 eighth edition remains controlling**.
- The 1978 printing is **additional witness only**.
- Comparison is **record-only**.
- Do not alter canonical Tamil, assembled Tamil, English, release status or the canonical verification freeze.
- Do not assume a later witness is corrected or superior.
- Read the 1978 source pixels directly; if uncertain, record **UNRESOLVED** rather than infer.
- Keep layout/illustration differences separate from lexical variants.

## Exact next activity

**W1 — compare 1978 scans 49–53 only.**

For each scan:

1. visually read the complete 1978 source page;
2. align it to the controlling 1953 canonical/assembled span;
3. record every confirmed variant in `witness-comparison/arumbu-1978/VARIANTS.md`;
4. update `PROGRESS.md`;
5. create a W1 review record;
6. synchronize controls and commit;
7. stop before scan54 / W2.

No controlling/assembled/English text changes are authorized.
