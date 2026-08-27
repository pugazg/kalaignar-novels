# Preliminary fidelity record — புதையல் scans 50–62

Date: 2026-08-27

## Status

**BASELINE LOADED / SPLIT NOW AVAILABLE / FINE-GRAINED RECONCILIATION PENDING.**

The user supplied Iteration 5 for printed pages **48–60**, corresponding to original scans **50–62**.

The required split is now available in this conversation:

`TVA_BOK_0064097_புதையல்_part_002_pages_50-98.pdf`

- split pages: **49**
- represented original source scans: **50–98**
- this Iteration 5 range: **scans 50–62 / printed pages 48–60**
- split committed to repository: **No**

The earlier version of this note correctly kept these pages `needs-review` because the split had not yet been attached. That availability problem is now resolved. The **textual verification gate itself is still open**: the existing Iteration 5 baseline must now be compared page by page with the newly supplied split before any of scans 50–62 are promoted to `verified`.

## Structural facts already established and reconfirmed

- scan 50 visibly prints page **48** and continues scan 49's unfinished embedded historical tale;
- scan 51 visibly prints **49**;
- scan 52 visibly prints **50**, closes chapter `4`, and begins chapter `5` on the same physical page;
- scans 53–59 visibly print **51–57** and continue chapter `5`;
- scan 60 visibly prints **58**, closes chapter `5`, and begins chapter `6` on the same physical page;
- scans 61–62 visibly print **59–60** and continue chapter `6`.

Physical continuity checkpoints retained in the page records include:

- scan 52 → 53: `அந்த` / `வீட்டிற்கு...`;
- scan 54 → 55: `போயி` / `யைப்பாரு...`;
- scan 55 → 56: `வெளியேறியிருந்தாலும்-` / `அவர்கள்...`;
- scan 56 → 57: `பிறகு` / `பாடினாள்...`;
- scan 57 → 58: `ஆசைப்` / `படுகிறோம்...`.

## Current textual state

The page bodies in scans 50–62 still preserve the user's Iteration 5 transcription as the comparison baseline. They have **not yet been promoted to source-verified text**.

This is intentional. Earlier work on this project showed that ambiguous old-print Tamil must not be silently replaced from assistant inference. The next pass must isolate each apparent word / spacing / punctuation disagreement against the split image and apply only source-established differences.

## Records present

- `../pages/0050-pudhaiyal.md`
- `../pages/0051-pudhaiyal.md`
- `../pages/0052-pudhaiyal.md`
- `../pages/0053-pudhaiyal.md`
- `../pages/0054-pudhaiyal.md`
- `../pages/0055-pudhaiyal.md`
- `../pages/0056-pudhaiyal.md`
- `../pages/0057-pudhaiyal.md`
- `../pages/0058-pudhaiyal.md`
- `../pages/0059-pudhaiyal.md`
- `../pages/0060-pudhaiyal.md`
- `../pages/0061-pudhaiyal.md`
- `../pages/0062-pudhaiyal.md`

## Exact next activity

Perform a controlled source-fidelity reconciliation of **scans 50–72 / printed pages 48–70** against the now-attached split part 002:

1. reconcile Iteration 5 scans 50–62 first;
2. reconcile Iteration 6 scans 63–72 second;
3. preserve every physical page boundary;
4. apply only visually established wording / punctuation / spacing differences;
5. run a final page-by-page comparison;
6. promote only fully resolved pages to `verified`.

After that verification gate, continue from scan **73 / printed page 71** onward.