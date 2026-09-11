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
- scans: **49**
- edition: **எட்டாம் பதிப்பு — ஜூலை 1953**
- controlling source: **YES**
- canonical state: **0 verified / 49 needs-review — verification freeze ACTIVE**
- assembled Tamil: **PASSED**
- whole-work English: **VERIFIED**
- release verdict: **RELEASE-READY WITH CANONICAL-TAMIL VERIFICATION QUALIFICATION**
- source PDF committed: **No**

## Active 1978 additional witness

`TVA_BOK_0064361_அரும்பு.pdf`

- SHA-256: `04a3013e1f58a1800867acc5d2f159976c47994a64478036e6fe0201edf120bc`
- compilation scans: **92**
- edition: **முதற் பதிப்பு — 1978**
- publisher: **தமிழ்க்கனி பதிப்பகம், சென்னை-28**
- witness span: **49–74 / 26 scans**
- controlling source: **NO — witness only**
- source PDF committed: **No**

## Durable witness-comparison state

- plan / mapping: **PASS / COMPLETE**;
- W1 scans **49–53**: **REVIEWED / COMPLETE**;
- line-comparison coverage: **5 / 26 scans**;
- batches complete: **1 / 6**;
- W1 textual / structural variant entries: **36**;
- W1 non-textual witness features added: **1**;
- pre-existing confirmed paratext variant: **1** — 1953 printer colophon absent from the 1978 ending;
- unresolved W1 source readings: **0**;
- canonical / assembled / English changes: **0 / 0 / 0**.

W1 review:

`works/periya-idathup-pen/witness-comparison/arumbu-1978/W1_SCANS_049_053.md`

Variant register:

`works/periya-idathup-pen/witness-comparison/arumbu-1978/VARIANTS.md`

Representative confirmed W1 edition variants include:

- `பொன்னம்மாளாக` → `பொன்னம்மாவாக`;
- `மாநாடு` → `மகாநாடு`;
- `போதாதா?` → `போதாவா?`;
- `அதிரச் செய்தன` → `அதிரச் செய்தது`;
- `வெதறலைத்` → `உதறலைத்`;
- `விவகார தாட்சண்யமாக` → `வரவர தாட்சண்யமாக`;
- `நாக்கை நீட்டிக்கொண்டிருந்தான்` → `நாக்கைத் தீட்டிக்கொண்டிருந்தான்`;
- controlling `என் தகப்பனுக்கு என்னைச் ... புத்தித் தோன்றும்?` → 1978 `என் தகப்பனுக்கென்னச் ... புத்தி தோன்றும்?`.

## Authority rules

- The **1953 eighth edition remains controlling**.
- The 1978 printing is **additional witness only**.
- Comparison is **record-only**.
- Do not alter canonical Tamil, assembled Tamil, English, release status or the canonical verification freeze.
- Do not assume the later witness is corrected or superior.
- Read 1978 source pixels directly; uncertain forms are **UNRESOLVED**, never inferred from context.
- Keep illustration/layout differences separate from lexical variants.

## Exact next activity

**W2 — compare 1978 scans 54–58 only.**

Mapping:

- scan54 — printed 51;
- scan55 — printed 52;
- scan56 — printed 53 and contains the first `கண்ணம்மா` heading;
- scan57 — physical landscape spread containing printed **54–55**;
- scan58 — printed 56.

For W2, compare complete source text against the controlling 1953 span, record exact variants, create `W2_SCANS_054_058.md`, update controls, commit, and stop before scan59 / W3.

No controlling/assembled/English text changes are authorized.
