# 2.2 Software Development Methodology — VetBot
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
- **Setting**: Local (Philippines) + La Union province, low-resource setting
- **Design**: DSR Artifact (Agile sprints: planning, design, implementation, testing, review and refinement + per-sprint RAGAS)
- **APA7**: Alverde, E. A. P., Dangbis, J. R. F., Oghenekaro, V. M., Quimpo, P. E., & Verzola, J. F. ([n.d.]). VetBot: An AI-driven veterinary chatbot for canine and feline care guidance. Lorma Colleges. [MISSING: year, venue]
- **Fit**: Closest Scrum-adjacent precedent in Batch C: named iterative sprints with per-cycle evaluation feeding refinement — but no cadence length, no backlog, no per-sprint deliverable mapping, so sprint slots stay empty.
### Task 2 — Verdict
- **Verdict**: PARTIALLY USABLE (2 mechanisms, 1 slot)
- **Bullets**:
  - Why + recency: UNVERIFIED year; Agile sprints named with planning → review-and-refinement repeated across cycles plus per-sprint RAGAS.
  - Slots populated → Features: [Artifact-Progression-Matrix-Deliverable] → Features 1, 2, 4.
  - Missing: [Scrum-Sprint-Cadence], [Sprint1-RBAC-Deliverable], [Sprint2-Records-Deliverable], [Sprint3-Notification-Deliverable], [Sprint4-Evaluation-Deliverable] (all [NOT STATED] — no 2–4-week cadence, no backlog, no sprint-to-feature map).
  - Panel use: proves sprint-cycled evaluation-into-refinement works in a Philippine veterinary build — the closest sprint precedent available.
  - Caveat: Agile ≠ Scrum; do not relabel its cycles as CarePaws sprints.
### Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Software Development Methodology-Artifact-Progression-Matrix-Deliverable | Five-stage Agile cycle repeated across sprints per component | La Union build, La Union | "consisting of planning, design, implementation, testing, and review and refinement phases" (Alverde et al., §3 Methodology, Agile, para. 1) | [NOT STATED: sprint length, velocity, backlog] | [DEPARTURE] CarePaws will progress its artifacts through the same plan-to-refinement cycle, run as 2–4-week Scrum sprints per the methods plan [Features 1–7] |
| 2 | Software Development Methodology-Artifact-Progression-Matrix-Deliverable | Per-sprint RAGAS assessment feeding retrieval, prompt, and knowledge-base refinement | N=99 queries, La Union build | "conducted iterative assessments of AI-generated responses using RAGAS across multiple sprint cycles, with each run informing subsequent refinements" (Alverde et al., §3 Methodology, Agile, para. 3) | N=99; 5 RAGAS dimensions / [NOT STATED: sprint mapping, defect counts] | [CORROBORATION] CarePaws will place an equivalent evaluate-then-refine deliverable inside every sprint gate [Features 1, 2] |
Excluded: [1] candidate omitted (Flutter/Django stack detail — architecture content for 1.9.2, not a deliverable).
