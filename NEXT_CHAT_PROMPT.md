# NEXT CHAT PROMPT — பாயும்புலி பண்டாரக வன்னியன் / T1 source inventory scans26–35

Continue directly in `pugazg/kalaignar-novels`, branch `main`, active work `works/payumpuli-pandaraka-vanniyan/`. **LIVE MAIN IS AUTHORITATIVE.**

## Source family

- source family: **TVA_BOK_0065744**
- complete extent: **477 physical scans**
- source Parts: **16 / 16 supplied**
- Part001: overall scans1–30
- Part002: overall scans31–60

Controlling source files for this batch:
- `TVA_BOK_0065744_பாயும்புலி_பண்டாரக_வன்னியன்_part_001_pages_1-30.pdf`
- `TVA_BOK_0065744_பாயும்புலி_பண்டாரக_வன்னியன்_part_002_pages_31-60.pdf`

## Controlling-source rule

Use only the user-attached split PDFs. They are normal authoritative source copies. Do not access Tamil Digital Library, Wikisource, or other mirrors unless explicitly asked.

Do not describe a normal source page as defective, unusually dense, or source-resolution-blocked merely because canonical text entry is incomplete.

## Durable state

- canonical page records: **25/477**
- T1 text-complete: **5/477 — scans1–5**
- T1 partial inventory: **20/477 — scans6–25**
- T2 reviewed: **5/477**
- T3 reviewed: **5/477**
- verified: **2/477**
- needs-review: **3/477**
- partial: **20/477**
- assembled Tamil / English: **BLOCKED**

Existing T1 inventory checkpoints:
- `works/payumpuli-pandaraka-vanniyan/T1_BATCH_006_015.md`
- `works/payumpuli-pandaraka-vanniyan/T1_BATCH_016_025.md`

## Work-specific forward-inventory rule

The complete-text backlog on partial pages does not imply a source defect. T1 page inventory may continue in 10-scan batches.

However:
- all text-incomplete pages remain `partial`;
- T2/T3 do not advance for them;
- final Tamil audit/assembly/English remain blocked until complete text is entered and audited.

## Exact next activity

Process **overall scans26–35** as one 10-scan T1 source-inventory iteration.

Mapping:
- scans26–30 → Part001 local pages26–30;
- scans31–35 → Part002 local pages1–5.

Mandatory boundary action:
- inspect overall scan30 and overall scan31 directly;
- classify the Part001→Part002 boundary as **CLEAN**, **GENUINE CONTINUATION**, or another source-supported state;
- do not treat the PDF split itself as a textual break.

For each scan:
1. inspect the attached page;
2. create one canonical page record;
3. preserve global `scan_page`, correct `part`, local `part_page`, and exact split `source_filename`;
4. record only visibly printed page numbers;
5. preserve page/section function and non-body marks;
6. enter any source text that can be read safely;
7. keep incomplete records `partial`;
8. synchronize page map / README / audit / source controls / handover / prompts;
9. commit and stop before scans36–45.

Do not start T2/T3 for partial pages.
