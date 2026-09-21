# NEXT CHAT PROMPT — பாயும்புலி பண்டாரக வன்னியன் / Part008 final metadata/status synchronization

Continue directly in `pugazg/kalaignar-novels`, branch `main`, active work `works/payumpuli-pandaraka-vanniyan/`. **LIVE MAIN IS AUTHORITATIVE.**

## Durable release state

Parts **001–007 are FINAL CLOSED / FROZEN**.

## Active Part008 state

- source — `TVA_BOK_0065744_பாயும்புலி_பண்டாரக_வன்னியன்_part_008_pages_211-240.pdf`
- local PDF pages — **30**
- canonical overall scans — **211–240**
- source size — **28,438,285 bytes**
- SHA-256 — `f495ebc09a6a002d3dbd12385eb332133c2e6a3b746fb1e88adfff5277cc5ec9`
- canonical Part008 records — **30/30 — scans211–240**
- Pass1 — **COMPLETE / PASS — 30/30 TEXT-COMPLETE**
- Pass2A — **COMPLETE / PASS — 30/30 REVIEWED — 2 corrections**
- Pass2B — **COMPLETE / PASS — 30/30 REVIEWED — 3 spacing / word-boundary corrections**
- Pass2B historical-glyph corrections — **0**
- Pass3 — **COMPLETE / PASS — 30/30 REVIEWED — 0 textual corrections**
- Part audit — **PASS / COMPLETE**
- unresolved Tamil / glyph / visual / structural questions — **0**
- all Part008 records still carry `status: "needs-review"` / `visual_fidelity: "needs-review"`
- visible printed-page coverage — **202–232**
- scan233 — **illustrated-two-page-spread / printed224–225**
- incoming 210→211 — **GENUINE CONTINUATION / AUDITED**
- outgoing 240→241 — **GENUINE CONTINUATION / AUDITED**
- Part009 canonical records — **0**
- final metadata/status synchronization — **NOT STARTED / NEXT GATE**

Correction ledger already closed:
- Pass2A scan217 — `உமக்கு எப்போதும்` → `உமக்கெப்போதும்`
- Pass2A scan219 — `பயமெல்லாம் -` → `பயமெல்லாம்-`
- Pass2B scan231 — `தெரியவில்லையா?` → `தெரிய வில்லையா?`
- Pass2B scan232 — `படிகளில்` → `படி களில்`
- Pass2B scan238 — `ஆக்கப்பட்டவளுமான` → `ஆக்கப் பட்டவளுமான`

Audit-confirmed structure:
- chapter32 continuation/close — scans211–212
- chapter33 — scans213–218
- chapter34 — scans219–225
- chapter35 — scans226–231
- chapter36 — scans232–237
- chapter37 — scans238–240, continuing into Part009
- chapter openings — scans **213, 219, 226, 232, 238**
- intentional blank lower fields — scans **212, 218, 225, 231, 237**
- scan233 — one physical illustrated two-page spread / printed **224–225**

Read first:
1. `HANDOVER.md`
2. `works/payumpuli-pandaraka-vanniyan/PAYUMPULI_ARCHIVAL_GUIDELINES.md`
3. `works/payumpuli-pandaraka-vanniyan/SOURCE_INTAKE_PART_008.md`
4. `works/payumpuli-pandaraka-vanniyan/PART_008_PASS1_PROGRESS.md`
5. `works/payumpuli-pandaraka-vanniyan/PART_008_PASS2A_PROGRESS.md`
6. `works/payumpuli-pandaraka-vanniyan/PART_008_PASS2B_PROGRESS.md`
7. `works/payumpuli-pandaraka-vanniyan/PART_008_PASS3_PROGRESS.md`
8. `works/payumpuli-pandaraka-vanniyan/PART_008_AUDIT.md`
9. `works/payumpuli-pandaraka-vanniyan/PART_007_BOUNDARY_AUDIT_210_211.md`
10. `works/payumpuli-pandaraka-vanniyan/PART_008_BOUNDARY_AUDIT_240_241.md`
11. `works/payumpuli-pandaraka-vanniyan/indexes/page-map.md`

## Exact activity

Perform **Part008 final metadata/status synchronization**.

Requirements:
- this is a **metadata-only gate**;
- update all 30 Part008 canonical page records, scans211–240;
- change only:
  - `status: "needs-review"` → `status: "verified"`
  - `visual_fidelity: "needs-review"` → `visual_fidelity: "verified"`
- do **not** alter canonical Tamil body wording;
- do **not** alter punctuation, word boundaries, historical-glyph decisions, paragraph/dialogue structure, `section`, `page_type`, printed-page mapping, source filename, scan/Part-page provenance, Pass2A/Pass2B/Pass3 evidence or boundary classifications;
- after the 30 page updates, verify **30/30 status verified** and **30/30 visual_fidelity verified**;
- verify the change set contains exactly the expected 30 Part008 page files and no unrelated canonical/body changes;
- create durable `PART_008_FINAL_STATUS_SYNC.md`;
- synchronize control documents to the verified 30/30 state;
- keep Parts001–007 frozen;
- keep Part009 canonical records at **0**;
- do **not** begin documentation synchronization in the same activity.

Stop after final metadata/status synchronization is **PASS / CLOSED** and the exact next gate is Part008 documentation synchronization.
