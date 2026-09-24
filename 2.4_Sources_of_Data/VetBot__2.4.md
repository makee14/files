# 2.4 Sources of Data — VetBot
> Source: `Sources/VetBot.md` | Date: 2026-09-24 | Depth: standard
> Verdict (Task 2): HIGHLY USABLE
---
### Task 1 — Bibliographic Classification
- **Title**: VetBot: An AI-Driven Veterinary Chatbot for Canine and Feline Care Guidance
- **Authors**: Edward Andrew P. Alverde, James Robert F. Dangbis, Voke Michael Oghenekaro, Paul Emmanuelle Quimpo, Johnny F. Verzola
- **Year**: [MISSING: year not stated in extracted text]
- **Recency**: UNCLASSIFIED (year unstated; FAIL rule applies only to verified pre-2016)
- **Outlet**: [MISSING: outlet not stated in extracted text; Lorma Colleges capstone manuscript]
- **DOI/URL**: [MISSING: DOI not stated in extracted text]
- **Setting**: Local (Philippines) + "College of Computer Studies and Engineering, Lorma Colleges" plus "In provincial settings such as La Union, Philippines"
- **Design**: Mixed evaluation (purposive interviews with 3 veterinarians during development; 9 licensed veterinarians on five-point Likert; 32 pet owners on SUS)
- **APA7**: Alverde, E. A. P., Dangbis, J. R. F., Oghenekaro, V. M., Quimpo, P. E., & Verzola, J. F. ([MISSING: year]). VetBot: An AI-driven veterinary chatbot for canine and feline care guidance. Lorma Colleges. [MISSING: outlet, DOI]
- **Fit**: Counted three-stratum source plan (purposive vet interviews, licensed-vet Likert panel, owner SUS cohort) — the closest same-country template for the CarePaws 2.4 population frame plus triangulation.
### Task 2 — Verdict
- **Verdict**: HIGHLY USABLE (3 mechanisms, 3 slots)
- **Bullets**:
  - Why + recency: UNCLASSIFIED (year unstated); counted strata (3 vets, 9 vets, 32 owners) across interview, Likert, and SUS instruments.
  - Slots populated → Features: [Interview-Protocol-Design] → Feature 7; [Survey-Questionnaire-Design] → Features 4, 7; [Population-Sampling-Frame] → Features 1, 2, 7.
  - Missing: [Triangulation-Strategy] as a named plan ([NOT STATED] — multi-instrument convergence implied but not labeled); inclusion and exclusion criteria and the interview guide text absent.
  - Panel use: deflects "no expert stratum" — licensed veterinarians plus practicing-owner strata with counted n.
  - Caveat: transfer the stratum structure and instrument pairing, not VetBot's scores as CarePaws targets.
### Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Sources of Data-Interview-Protocol-Design | Purposive veterinarian interviews informing system design during development | n=3 veterinarians, La Union | "The proponents conducted interviews with three (3) veterinarians in La Union to understand the common challenges in veterinary care and gather expert input to inform the system's design." (Alverde et al., Interview Results, para. 1) | n=3, purposive / [NOT STATED: guide items, duration] | [TEMPLATE] CarePaws will protocol its Phase 1 veterinarian interviews the same purposive way, recording guide items and duration [Feature 7] |
| 2 | Sources of Data-Survey-Questionnaire-Design | Five-point Likert expert instrument plus SUS owner instrument pairing | n=9 vets plus n=32 owners, La Union | "Nine (9) licensed veterinarians evaluated VetBot's outputs on a 5-point Likert scale across nine criteria" (Alverde et al., Abstract, para. 3) | n=9, 9 criteria, mean 4.56; n=32, SUS 79.61 / [NOT STATED: alpha] | [TEMPLATE] CarePaws will pair its Likert evaluation questionnaire with the SUS owner instrument the same way [Features 4, 7] |
| 3 | Sources of Data-Population-Sampling-Frame | Three-stratum population frame of consulting veterinarians, licensed evaluators, and pet owners | La Union, canine and feline scope | "Thirty-two (32) pet owners completed the System Usability Scale (SUS)" (Alverde et al., Abstract, para. 3) | n=3 interviews, n=9 experts, n=32 owners / [NOT STATED: inclusion and exclusion criteria] | [TEMPLATE] CarePaws will frame its veterinarian, staff, and owner strata the same way, adding explicit inclusion and exclusion criteria [Features 1, 2, 7] |
Excluded: [1] candidate omitted (RAGAS N=99 automated run — engineering benchmark content for later chapters, not a human data source).