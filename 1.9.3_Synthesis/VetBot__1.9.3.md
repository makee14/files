# 1.9.3 Synthesis — VetBot
> Source: `Sources/VetBot.md` | Date: 2026-09-24 | Depth: standard
> Verdict (Task 2): PARTIALLY USABLE
---
### Task 1 — Bibliographic Classification
- **Title**: VetBot: An AI-Driven Veterinary Chatbot for Canine and Feline Care Guidance
- **Authors**: Edward Andrew P. Alverde, James Robert F. Dangbis, Voke Michael Oghenekaro, Paul Emmanuelle Quimpo, Johnny F. Verzola
- **Year**: [NOT STATED in text — references through 2025]
- **Recency**: UNVERIFIED (stack and citations indicate 2025–2026)
- **Outlet**: [NOT STATED — Lorma Colleges manuscript in text]
- **DOI/URL**: [NOT FOUND]
- **Setting**: Local (Philippines) + La Union province, low-resource provincial setting
- **Design**: DSR Artifact (RAG build + RAGAS N=99 + 9-vet Likert + 32-owner SUS)
- **APA7**: Alverde, E. A. P., Dangbis, J. R. F., Oghenekaro, V. M., Quimpo, P. E., & Verzola, J. F. ([n.d.]). VetBot: An AI-driven veterinary chatbot for canine and feline care guidance. Lorma Colleges. [MISSING: year, venue]
- **Fit**: Best-measured build in Batch C, yet retrieval coverage, emergency handling, response time, and single-province scope remain open — feeds empirical, architectural, and geographical gaps.
### Task 2 — Verdict
- **Verdict**: PARTIALLY USABLE (3 mechanisms, 3 slots)
- **Bullets**:
  - Why + recency: UNVERIFIED year; triple evaluation published but recall 0.691, correctness 0.517 wording penalty, and response-time complaint unquantified.
  - Slots populated → Features: [Empirical-Gap] → Features 1, 2; [Architectural-Gap] → Features 2, 4; [Geographical-Gap] → Features 1, 2, 4.
  - Missing: [Methodological-Gap] (Agile+sprints stated, sampling uncritiqued), [CarePaws-Synthesis-Resolution] (author synthesis).
  - Panel use: deflects "best build closes all gaps" — strongest metrics still leave latency, coverage, and locale open.
  - Caveat: transfer gaps only; generative-diagnosis path quarantined (CarePaws is records-first).
### Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Synthesis-Empirical-Gap | Reference-phrasing penalty depressing correctness despite high grounding | N=99 RAGAS, single reference per query | "so any response that conveyed the same information in different wording was scored lower even if it was factually correct" (Alverde et al., Abstract, para. 2) | Correctness 0.517 vs faithfulness 0.889; N=99 / [METRIC UNREPORTED: latency-ms] | [CORROBORATION] CarePaws will close this metric-fragility gap with multi-rater acceptance plus timed trials alongside any automated score [Features 1, 2] |
| 2 | Synthesis-Architectural-Gap | Retrieval-coverage shortfall with slower emergency performance and unmeasured response time | La Union deployment, vet feedback | "Context Recall (0.691) reflected moderately high retrieval performance, with room for improvement in retrieval coverage" (Alverde et al., Abstract, para. 2) | Recall 0.691; emergency 4.47 vs non-urgent 4.65 / [METRIC UNREPORTED: latency-ms] | [CORROBORATION] CarePaws will close this responsiveness gap with a ≤1.2s NFR plus local records with queued sync [Features 2, 4] |
| 3 | Synthesis-Geographical-Gap | Single-province deployment bounded to selected La Union clinics | La Union, low-resource setting | "There is no integrated system that combines symptom-based triage assessment, first aid guidance, and location-specific clinic information for provincial or low-resource settings such as La Union" (Alverde et al., §1 Introduction, gap statement, para. 1) | 9 vets; 32 owners; N=99 queries / [NOT STATED: multi-site replication] | [CORROBORATION] CarePaws will extend this provincial precedent by fielding and measuring in its own locale rather than assuming transfer [Features 1, 2, 4] |
Excluded: [1] candidate omitted (rare-case coverage suggestion — future-work note, no gap mechanism).
