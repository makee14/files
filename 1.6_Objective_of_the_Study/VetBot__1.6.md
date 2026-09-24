# 1.6 Objective of the Study — VetBot
> Source: `Sources/VetBot.md` | Date: 2026-09-24 | Depth: standard
> Verdict (Task 2): HIGHLY USABLE
---
### Task 1 — Bibliographic Classification
- **Title**: VetBot: An AI-Driven Veterinary Chatbot for Canine and Feline Care Guidance
- **Authors**: Edward Andrew P. Alverde, James Robert F. Dangbis, Voke Michael Oghenekaro, Paul Emmanuelle Quimpo, Johnny F. Verzola
- **Year**: [NOT STATED — Gemini 3 Flash + 5S/6S methods date it ca. 2025–2026; VERIFY]
- **Recency**: UNVERIFIED (no year printed; treat as recent-pattern precedent with caution)
- **Outlet**: Lorma Colleges, College of Computer Studies and Engineering (capstone manuscript)
- **DOI/URL**: [NOT FOUND]
- **Setting**: Local (Philippines) — "In provincial settings such as La Union, Philippines, limited clinic access and geographic distance compound these gaps" (Abstract, para. 1)
- **Design**: DSR Artifact (Flutter/Django/PostgreSQL/ChromaDB/Gemini 3 Flash RAG build + RAGAS N=99 + 9-vet Likert review + 32-owner SUS)
- **APA7**: Alverde, E. A. P., Dangbis, J. R. F., Oghenekaro, V. M., Quimpo, P. E., & Verzola, J. F. (n.d.). *VetBot: An AI-driven veterinary chatbot for canine and feline care guidance*. Lorma Colleges. [MISSING: year — verify]
- **Fit**: Strongest local design-develop-evaluate verb chain with triple numeric bars (RAGAS, vet means, SUS) — models phased 1.6 verbs plus measurable thresholds for guidance scope.

### Task 2 — Verdict
- **Verdict**: HIGHLY USABLE (5 mechanisms, 5 slots)
- **Bullets**:
  - Why + recency: UNVERIFIED year but exceptional slot fit — design/develop/evaluate verbs with RAGAS N=99, vet mean 4.56, and SUS 79.61.
  - Slots populated → Features: [General-Objective-Action] → Feature 7; [Phase1-QUAL-Requirements-Objective] → Feature 7; [Phase2-Agile-Engineering-Objective] → Feature 7; [Phase4-QUAN-Evaluation-Objective] → Feature 7; [Measurable-Metric-Threshold] → Feature 7.
  - Missing: [Phase3-Technical-Verification-Objective] as a distinct functional-pass verb ([NOT STATED] — RAGAS/vet/SUS cover evaluation, not pre-release verification).
  - Panel use: deflects "AI objectives are untestable" — every verb carries a named instrument and numeric bar.
  - Caveat: transfer verb + threshold pattern only; never the La Union site or canine/feline-only scope.

### Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Objective of the Study-General-Objective-Action | Design-develop-evaluate composite for canine/feline care guidance | La Union provincial baseline, symptom-interpretation gap | "This study designed, developed, and evaluated VetBot: An AI-Driven Veterinary Chatbot for Canine and Feline Care Guidance, based on a Retrieval-Augmented Generation (RAG) architecture" (Alverde et al., Abstract, para. 2) | N=99 RAGAS; 9 vets; 32 owners | [CORROBORATION] CarePaws will phrase its general objective as design-develop-evaluate for guidance scope [Feature 7] |
| 2 | Objective of the Study-Phase1-QUAL-Requirements-Objective | Owner-plus-vet requirements elicitation grounding the build | 75 owners + 4 vets, La Union | "Data were collected through surveys with 75 pet owners to understand their experiences, needs, and preferences and through interviews with four veterinarians" (Alverde et al., Methods, Requirements, para. 1) | n=75 owners + 4 vets / [NOT STATED: instrument alpha] | [CORROBORATION] CarePaws will phrase its Phase 1 objective as owner-survey plus vet-interview requirements elicitation [Feature 7] |
| 3 | Objective of the Study-Phase2-Agile-Engineering-Objective | Stack-specified RAG delivery with triage plus guidance modules | Flutter/Django/PostgreSQL/ChromaDB/Gemini 3 Flash | "The system was implemented with a Flutter mobile interface, a Django backend, PostgreSQL for transactional data, and ChromaDB for semantic retrieval, with Gemini 3 Flash as the language model" (Alverde et al., Abstract, para. 2) | [NOT STATED: sprint length, velocity] | [CORROBORATION] CarePaws will phrase its Phase 2 objective as stack-specified delivery of the guidance module [Feature 7] |
| 4 | Objective of the Study-Phase4-QUAN-Evaluation-Objective | Triple-instrument evaluation: RAGAS plus vet review plus SUS | N=99 queries; 9 vets; 32 owners | "The RAG pipeline was evaluated with the RAGAS framework on 99 clinical test queries" (Alverde et al., Abstract, para. 3) | RAGAS N=99; vet mean 4.56; SUS 79.61 | [CORROBORATION] CarePaws will phrase its Phase 4 objective as multi-instrument evaluation with named bars [Feature 7] |
| 5 | Objective of the Study-Measurable-Metric-Threshold | Vet-mean plus SUS bars as the acceptability threshold | 5-point Likert; SUS scale | "Nine (9) licensed veterinarians evaluated VetBot's outputs on a 5-point Likert scale across nine criteria, yielding an overall mean of 4.56" (Alverde et al., Abstract, para. 3) | Mean 4.56 Strongly Agree; SUS 79.61 Excellent | [CORROBORATION] CarePaws will set its measurable threshold at Strongly-Agree vet means with Excellent-range usability [Feature 7] |
Excluded: [1] candidate omitted (ChromaDB cosine-similarity detail — retrieval internals for 2.x, not an objective verb).
