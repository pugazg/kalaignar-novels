# Source page-count reconciliation — புதையல்

Date opened: 2026-08-25  
Last updated: 2026-08-30

## Why this note exists

The first onboarding pass incorrectly treated scans **1–150** as the complete PDF. That conclusion is permanently withdrawn.

Tamil Digital Library describes source identity `TVA_BOK_0064097` as **443 p.** and exposes the item as **PDF — 2 Files**. The repository therefore distinguishes:

- bibliographic printed extent: **443 p.**;
- source scans currently represented by received derivatives: **1–294**;
- canonical source-scan records currently created: **1–270**;
- exact original PDF scan/page-object count: **still pending**.

## Authority distinction

The source scan controls exact text, edition wording, punctuation and page structure. Catalogue information is used only for bibliographic / completeness reconciliation.

## Split-source workaround

Received access derivatives:

1. Part 001 — scans **1–49** — **part-complete**
2. Part 002 — scans **50–98** — **part-complete**
3. Part 003 — scans **99–147** — **part-complete**
4. Part 004 — scans **148–196** — **part-complete**
5. Part 005 — scans **197–245** — **part-complete with explicit source-damage qualification**
6. Part 006 — scans **246–294 / printed 242–290** — **in progress**
   - physical pages mapped: **49 / 49**
   - canonical records created: **25 / 49 — scans 246–270**
   - native verified: **25**
   - needs-review: **0**
   - not-started: **24 — scans 271–294**
   - derivative SHA-256: `34a5ea5eb91a71ca8674760257779eb4ed6bdc6640517f8830b9ee70aa34aec7`

No split is committed to GitHub.

## Part-006 current reconciliation

The strengthened source-fidelity rule applies to **all vowel signs / combining marks**: any old/faint vowel-sign, same-word glyph, or line-wrap spacing disagreement requires a second independent high-resolution pass before overriding the baseline; a printed line break alone never establishes word spacing.

### Iteration 26 opening — scan 270

- scan 269 ends `முட்களை சமாளித்துக் கொண்டும்,`;
- scan 270 begins `பரிமளா, தீராத வேதனையைச்...`; the source therefore establishes one continuous sentence across the physical page boundary;
- user Iteration-26 baseline is substantively source-supported;
- source punctuation includes `எல்லாம் பொய் — பொழுது விடியும் வரையில்...`;
- source reads `புதரோரத்திலே`, not baseline `புதரோரத்தில்`;
- source preserves `தொடர்ந்தபடி யிருந்தாள்`, `மண்ணாங்கட்டியுமில்லை`, `மனதுக்குள்ளே`, `முணகல் சப்தம்`, `கீழ் ஸ்தாயியில்`, `புதரண்டை`, and `பெருக்கெடுத்த படியிருந்தது`;
- second old-type pass confirms complete `சாமியாருமில்லை`, `மண்ணாங்கட்டியுமில்லை`, `ரகசியமுமில்லை`, `கையில்லை`, `முடியவில்லை`, and `பரிமளாவினால்`;
- scan 270 physical endpoint: `‘தூக்குங்கள்!’ என்று கத்தினாள்.`.

## Part-006 physical structure map

- chapter 28 begins scan 247 / printed 243;
- four-star internal transition scan 251 / printed 247;
- chapter 29 begins scan 254 / printed 250 and closes scan 262 / printed 258;
- chapter 30 begins scan 262 / printed 258;
- chapter 31 begins scan 271 / printed 267;
- chapter 32 begins scan 278 / printed 274;
- chapter 33 begins scan 288 / printed 284 and continues through scan 294 / printed 290.

This is structure mapping only for scans 271–294; their text remains `not-started` until native reconciliation.

## Current textual state

- canonical page records created: **270**
- verified: **263**
- needs-review: **7**
- partial: **0**
- clean contiguous fully verified range: **1–214**
- individually source-verified later pages: through scan **270**, except the seven damaged Part-005 records
- Parts 001–005: **part-complete at split level**
- Part 006: **in progress — 25 / 49 verified**
- continuous split-level assembled Tamil / English review: **through scan 245 only**
- source scans physically mapped from received derivatives: **through scan 294**
- full-source manifest: **still incomplete beyond scan 294**

## Full-source extent track

Still required:

1. reconcile Part-006 scans **271–294** under the same canonical/fidelity workflow;
2. complete the Part-006 Tamil audit, assembled Tamil, controlled English and bilingual review before calling Part 006 `part-complete`;
3. obtain later source splits beyond scan 294;
4. process every later source scan under the same workflow;
5. identify true final text / back matter / closing leaves;
6. determine exact original PDF scan/page-object count;
7. calculate the exact original full-source SHA-256 when byte-level access is available;
8. only after complete-source coverage, run final whole-work Tamil and bilingual audits and release-readiness checks.

Do not infer any of those values from the TDL printed-page count.

## Exact next activity

Reconcile **scan 271 / printed page 267** directly against native Part-006 source pixels, completing chapter 30 and capturing the source-printed chapter-31 heading/transition on the same physical page. Apply the strengthened two-pass old-Tamil-typeform / line-wrap rule to every vowel-sign question.