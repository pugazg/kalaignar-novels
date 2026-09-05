# Assembled Tamil Consistency Audit — பெரிய இடத்துப் பெண்

## Scope

Assembled reader: `sections/`  
Canonical authority: `pages/`  
Controlling source: `TVA_BOK_0064090_பெரிய_இடத்துப்_பெண்_1953.pdf`

This audit checks the **derived assembled Tamil reading layer only**. It does not change the verification status of canonical page records.

## Preconditions

Before assembly:

- canonical records: **49 / 49**;
- dedicated whole-work source comparison: **49 / 49 directly reviewed — COMPLETE**;
- `verified`: **0**;
- `needs-review`: **49**;
- verification freeze: **ACTIVE**;
- historical/source corrections from the completed source audit already synchronized into canonical pages.

## Reader scope decision

The continuous reader begins with the source title / narrative opening on **scan 8**. Scans **1–7** are front matter / copy and publication material and remain fully preserved in canonical page records rather than duplicated into the narrative reader.

Narrative coverage assembled: **scans 8–49**.

The separate printer colophon on scan 49 is retained after the narrative as explicitly labeled non-narrative source matter.

## Section-boundary audit

The work is one continuous text. The assembled layer uses seven files only to expose source-printed internal structure and manageable reading continuity.

| Order | File | Source boundary check | Result |
|---:|---|---|---|
| 1 | `sections/01-opening.md` | scan 8 → scan 15 immediately before `உத்தண்டி` | PASS |
| 2 | `sections/02-uthandi.md` | scan 15 `உத்தண்டி` → scan 19 immediately before `கண்ணம்மா` | PASS |
| 3 | `sections/03-kannamma-first.md` | scan 19 first `கண்ணம்மா` → scan 31 | PASS |
| 4 | `sections/04-kumudha.md` | scans 32–37 | PASS |
| 5 | `sections/05-veeran.md` | scans 38–44 | PASS |
| 6 | `sections/06-ulaganathar.md` | scan 45 | PASS |
| 7 | `sections/07-kannamma-conclusion.md` | scans 46–49 + separate colophon | PASS |

Mid-page source headings on scans **15** and **19** were checked specifically: preceding text remains in the preceding section, the heading starts the next section, and no text is duplicated or omitted at either split.

## Internal-heading audit

Required source-printed headings and order:

1. `உத்தண்டி` — scan 15 / printed 14;
2. `கண்ணம்மா` — scan 19 / printed 18;
3. `குமுதா` — scan 32 / printed 31;
4. `வீரன்` — scan 38 / printed 37;
5. `உலகநாதர்` — scan 45 / printed 44;
6. `கண்ணம்மா` — scan 46 / printed 45.

Result: **PASS — all six represented in source order; none promoted to a separate work.**

## Cross-page continuity audit

All character-level joins established by the completed source audit are represented with reversible HTML provenance comments. Checked joins include:

- `கிடப்ப` + `தாகக்` → `கிடப்பதாகக்`;
- `நினைக்` + `காதே!` → `நினைக்காதே!`;
- `தெரிந்` + `தது.` → `தெரிந்தது.`;
- `என்` + `றேன்.` → `என்றேன்.`;
- `என்` + `னிலே` → `என்னிலே`;
- `காலக்ஷேபங்` + `கூட` → `காலக்ஷேபங்கூட`;
- `மட்` + `டும்` → `மட்டும்`;
- `‘ஒய்யா` + `ரக்` → `‘ஒய்யாரக்`;
- `கவலை` + `யில்லை.` → `கவலையில்லை.`;
- `நிலையி` + `லேயே` → `நிலையிலேயே`;
- `அத` + `னுடைய` → `அதனுடைய`;
- `கல்யா` + `ணத்தை` → `கல்யாணத்தை`;
- `காரண` + `மாயிருந்தேன்!` → `காரணமாயிருந்தேன்!`;
- `எழுதி` + `யிருந்தாள்.` → `எழுதியிருந்தாள்.`.

Phrase continuities already established in `FULL_TAMIL_SOURCE_AUDIT.md` are preserved without invented wording or punctuation. In particular, scan **9 → 10** remains without an invented terminal mark.

Result: **PASS**.

## Historical-glyph propagation audit

Dedicated-audit corrections were checked in the assembled reader:

- scan 33: `கண்ணாடி` — present;
- scan 43: `இளிச்சவாயனாக` — present;
- scan 46: `நானா ஆள்?` — present;
- scan 47: `விட வேணா?` — present.

Earlier historical corrections, including `ஆவலைக்`, `நின்றார்`, `போகிறாயே`, `நன்றாகத்`, `நன்றாகத்தான்`, `நன்றாக`, `விழுவேன் என்றானா?`, and `வேலை மட்டுந்தானா?`, were preserved from the canonical source layer.

Result: **PASS**.

## Final-source audit

Checked in `sections/07-kannamma-conclusion.md`:

- scan 47 `எழுதி` + scan 48 `யிருந்தாள்.` → `எழுதியிருந்தாள்.` — PASS;
- scan 48 `ஒரு பெரிய` + scan 49 `ஜோதி நிரந்தரமாக...` — PASS;
- narrative ending `...எங்களிடம் வரவேண்டும், தெரியுமா?` — present;
- source-specific `வேசின்`, `தத்தம்`, `அழுக்குப்பட்டு`, `உச்ச ஸ்தாயியை`, `போகவேண்டு மென்னிருக்கலே`, `பாடங்` — retained;
- separate printer colophon `ஸ்ரீமகள் அச்சகம், சென்னை-1` — retained outside the narrative.

Result: **PASS**.

## Canonical-layer immutability check

Assembly introduces new `sections/` files and work-level status/audit documentation only. It does **not** authorize canonical page verification or source normalization.

Required post-assembly canonical state:

- canonical pages: **49 / 49**;
- `verified`: **0**;
- `needs-review`: **49**;
- verification freeze: **ACTIVE**.

## Final result

**ASSEMBLED TAMIL: PASSED.**

Canonical `pages/` remain the controlling text and remain under the active verification freeze.

## Subsequent completion state

The English stages that were once future work have been completed from this passed assembled layer:

- translation plan: **COMPLETE**;
- English section files: **7 / 7 reviewed**;
- translation batches: **8 / 8 reviewed**;
- final bilingual review: **PASSED**;
- whole-work English: **VERIFIED**;
- release-readiness pass: **PASSED WITH CANONICAL-TAMIL VERIFICATION QUALIFICATION**;
- completion documentation sync: [`COMPLETION_SYNC_AUDIT.md`](COMPLETION_SYNC_AUDIT.md).

No English or release review required a new Tamil canonical correction. The assembled layer remains **PASSED**, while canonical page statuses remain **0 verified / 49 `needs-review`** under the user-mandated freeze.

There is no remaining assembly-stage activity for this title under the current instructions.