# 2.1 Research Approach — VetBot
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
- **Design**: DSR Artifact (Agile sprints + RAGAS N=99 + 9-vet Likert + 32-owner SUS + thematic analysis)
- **APA7**: Alverde, E. A. P., Dangbis, J. R. F., Oghenekaro, V. M., Quimpo, P. E., & Verzola, J. F. ([n.d.]). VetBot: An AI-driven veterinary chatbot for canine and feline care guidance. Lorma Colleges. [MISSING: year, venue]
- **Fit**: Only Batch C source with an explicit mixed QUAL-QUAN evaluation (thematic vet feedback + RAGAS/SUS metrics) wrapped in Agile sprints — the evaluation-phase template, though DSR and epistemology are unnamed.
### Task 2 — Verdict
- **Verdict**: PARTIALLY USABLE (3 mechanisms, 2 slots)
- **Bullets**:
  - Why + recency: UNVERIFIED year; N=99 RAGAS plus 9-vet and 32-owner arms with 5-expert instrument validation and thematic analysis.
  - Slots populated → Features: [Exploratory-Sequential-QUAL-QUAN] → Features 1, 2; [Data-Phase-Artifact-Integration] → Features 1, 2, 4.
  - Missing: [DSR-Paradigm-Defense] (Agile named, DSR unnamed), [Epistemological-Rationale] ([NOT STATED] — triangulation unclaimed).
  - Panel use: deflects "evaluation unmodelled" — automated metrics plus expert Likert plus SUS plus thematic feedback in one study.
  - Caveat: transfer evaluation logic only; generative-triage content quarantined (CarePaws is records-first).
### Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Research Approach-Exploratory-Sequential-QUAL-QUAN | Thematic analysis of open-ended vet feedback alongside RAGAS and SUS quantification | 9 vets, 32 owners, N=99 queries, La Union | "Qualitative responses from the open-ended questions in the expert validation form were analyzed through thematic analysis" (Alverde et al., §3 Methodology, evaluation, para. 5) | N=99; 9 vets mean 4.56; 32 owners SUS 79.61 / [NOT STATED: sampling frame] | [CORROBORATION] CarePaws will pair the same thematic QUAL arm with its QUAN acceptance metrics [Features 1, 2] |
| 2 | Research Approach-Exploratory-Sequential-QUAL-QUAN | Five-expert instrument validation preceding veterinarian and owner data collection | 5 IT validators, La Union | "the Expert Evaluation Form was reviewed and validated by five (5) IT expert validators" (Alverde et al., §3 Methodology, evaluation, para. 3) | 5 validators; 9 vets; 32 owners / [NOT STATED: validity coefficients] | [CORROBORATION] CarePaws will validate its own instruments with the same expert-review gate before fielding [Feature 1] |
| 3 | Research Approach-Data-Phase-Artifact-Integration | Sprint-cycled RAGAS runs feeding retrieval, prompt, and knowledge-base refinement | Agile sprints, La Union build | "conducted iterative assessments of AI-generated responses using RAGAS across multiple sprint cycles, with each run informing subsequent refinements" (Alverde et al., §3 Methodology, Agile, para. 3) | N=99; 5 RAGAS dimensions / [NOT STATED: sprint length] | [CORROBORATION] CarePaws will integrate each sprint's evaluation data into the next increment the same cycle way [Features 1, 2, 4] |
Excluded: [1] candidate omitted (Data Privacy Act consent detail — ethics note, no approach mechanism).
