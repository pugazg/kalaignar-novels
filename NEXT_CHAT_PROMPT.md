# NEXT CHAT PROMPT — பாயும்புலி பண்டாரக வன்னியன் / Part008 Part audit

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
- Pass2A — **COMPLETE / PASS — 30/30 REVIEWED**
- Pass2A corrections — **2**
- Pass2B — **COMPLETE / PASS — 30/30 REVIEWED**
- Pass2B corrections — **3 source spacing / word-boundary**
- Pass2B historical-glyph corrections — **0**
- Pass3 — **COMPLETE / PASS — 30/30 REVIEWED**
- Pass3 textual corrections — **0**
- Pass3 unresolved visual / structural questions — **0**
- all Part008 records remain `status: "needs-review"` / `visual_fidelity: "needs-review"`
- visible printed-page coverage — **202–232**
- scan233 — **illustrated-two-page-spread / printed224–225**
- incoming 210→211 — **GENUINE CONTINUATION / AUDITED**
- outgoing 240→241 — **GENUINE CONTINUATION / AUDITED**
- Part009 canonical records — **0**
- Part audit — **NOT STARTED / NEXT GATE**

Pass2A corrections already applied:
- scan217 / printed208 — `உமக்கு எப்போதும்` → `உமக்கெப்போதும்`
- scan219 / printed210 — `பயமெல்லாம் -` → `பயமெல்லாம்-`

Pass2B corrections already applied:
- scan231 / printed222 — `தெரியவில்லையா?` → `தெரிய வில்லையா?`
- scan232 / printed223 — `படிகளில்` → `படி களில்`
- scan238 / printed230 — `ஆக்கப்பட்டவளுமான` → `ஆக்கப் பட்டவளுமான`

Pass3 durable structural findings:
- chapter openings — scans **213, 219, 226, 232, 238**
- intentional chapter-closing blank lower fields — scans **212, 218, 225, 231, 237**
- scan233 — one physical illustrated two-page spread, printed **224–225**, upper colour illustration spanning both printed pages, lower text read left→right
- incoming/outgoing split boundaries structurally consistent
- textual corrections — **0**
- unresolved visual / structural questions — **0**

Read first:
1. `HANDOVER.md`
2. `works/payumpuli-pandaraka-vanniyan/PAYUMPULI_ARCHIVAL_GUIDELINES.md`
3. `works/payumpuli-pandaraka-vanniyan/SOURCE_INTAKE_PART_008.md`
4. `works/payumpuli-pandaraka-vanniyan/PART_008_PASS1_PROGRESS.md`
5. `works/payumpuli-pandaraka-vanniyan/PART_008_PASS2A_PROGRESS.md`
6. `works/payumpuli-pandaraka-vanniyan/PART_008_PASS2B_PROGRESS.md`
7. `works/payumpuli-pandaraka-vanniyan/PART_008_PASS3_PROGRESS.md`
8. `works/payumpuli-pandaraka-vanniyan/PART_007_BOUNDARY_AUDIT_210_211.md`
9. `works/payumpuli-pandaraka-vanniyan/PART_008_BOUNDARY_AUDIT_240_241.md`
10. `works/payumpuli-pandaraka-vanniyan/indexes/page-map.md`

## Exact activity

Perform **Part008 Part audit** across scans211–240.

Requirements:
- reconcile all 30 canonical page records with Pass1, Pass2A, Pass2B and Pass3 evidence;
- verify the cumulative correction ledger: **2 Pass2A + 3 Pass2B + 0 Pass3**;
- verify all 30 page records contain formal Pass2A / Pass2B / Pass3 evidence blocks;
- reconcile canonical scan/local/printed-page mapping, including scan233 `printed_page: 224` + `printed_page_end: 225`;
- verify chapter structure:
  - chapter32 continuation/close — scans211–212
  - chapter33 — scans213–218
  - chapter34 — scans219–225
  - chapter35 — scans226–231
  - chapter36 — scans232–237
  - chapter37 — scans238–240, continuing beyond Part008
- verify chapter-opening page types at scans213, 219, 226, 232 and238;
- verify intentional blank lower fields at scans212, 218, 225, 231 and237;
- verify scan233 spread metadata and left→right reading order;
- reconcile incoming 210→211 and outgoing 240→241 audited boundaries;
- confirm Part009 canonical records remain **0** and frozen Parts001–007 were not mutated;
- audit current metadata while keeping it `needs-review` during the audit itself;
- write a durable `PART_008_AUDIT.md` with PASS/FAIL accounting and any blockers;
- do **not** begin final metadata/status synchronization in the same activity unless the audit itself passes and the workflow explicitly requires a separate next gate.

Stop after the Part008 Part audit is complete and control documents are synchronized.
