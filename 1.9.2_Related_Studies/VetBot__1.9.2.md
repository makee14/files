# 1.9.2 Related Studies — VetBot
> Source: `Sources/VetBot.md` | Date: 2026-09-24 | Depth: standard
> Verdict (Task 2): HIGHLY USABLE
---
### Task 1 — Bibliographic Classification
- **Title**: VetBot: An AI-Driven Veterinary Chatbot for Canine and Feline Care Guidance
- **Authors**: Edward Andrew P. Alverde, James Robert F. Dangbis, Voke Michael Oghenekaro, Paul Emmanuelle Quimpo, Johnny F. Verzola
- **Year**: [NOT STATED in text — references through 2025]
- **Recency**: UNVERIFIED (year not stated; stack and citations indicate 2025–2026)
- **Outlet**: [NOT STATED — Lorma Colleges manuscript in text]
- **DOI/URL**: [NOT FOUND]
- **Setting**: Local (Philippines) + La Union province, limited clinic access
- **Design**: DSR Artifact (Flutter/Django/PostgreSQL/ChromaDB/Gemini 3 Flash RAG build + RAGAS N=99 + 9-vet Likert + 32-owner SUS)
- **APA7**: Alverde, E. A. P., Dangbis, J. R. F., Oghenekaro, V. M., Quimpo, P. E., & Verzola, J. F. ([n.d.]). VetBot: An AI-driven veterinary chatbot for canine and feline care guidance. Lorma Colleges. [MISSING: year, venue]
- **Fit**: Strongest empirical build in Batch C: named four-layer stack, chunk/re-rank pipeline, triple evaluation (RAGAS, experts, SUS) — core 1.9.2 record.
### Task 2 — Verdict
- **Verdict**: HIGHLY USABLE (4 mechanisms, 4 slots)
- **Bullets**:
  - Why + recency: UNVERIFIED year but fully specified stack (Flutter, Django, PostgreSQL, ChromaDB, Gemini 3 Flash) with N=99 RAGAS, 9-vet mean 4.56, 32-owner SUS 79.61.
  - Slots populated → Features: [Empirical-System-Architecture] → Features 1, 2, 4; [Quantitative-Metric-Outcomes] → Features 1, 2; [Acknowledged-Architectural-Flaws] → Features 2, 4; [Connectivity-Assumptions] → Feature 4.
  - Missing: [Hardware-Offline-Fallbacks] ([NOT STATED] — no offline queue/cache); no latency-ms despite response-time complaint.
  - Panel use: deflects "no measured precedent" — retrieval-grounded build with published faithfulness, relevancy, precision, recall, and usability.
  - Caveat: year/venue unverified; online-LLM dependency quarantined (CarePaws is records-first, no generative diagnosis).
### Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Related Studies-Empirical-System-Architecture | Four-layer separation of Flutter frontend, Django backend, PostgreSQL records, and LLM+RAG AI layer | La Union build, canine/feline scope | "organized into four interconnected layers: the Frontend layer, implemented as a Flutter mobile interface; the Backend layer, built on Django API and business logic" (Alverde et al., §4 Results, Architecture, para. 1) | [NOT STATED: versions, specs, latency-ms] | [CORROBORATION] CarePaws will adopt the same presentation-backend-data separation for its Features 1–7 build [Features 1, 2, 4] |
| 2 | Related Studies-Quantitative-Metric-Outcomes | RAGAS retrieval-grounding profile with high faithfulness and relevancy but moderate recall | N=99 clinical test queries, curated references | "Faithfulness scored 0.889 and Answer Relevancy 0.906" (Alverde et al., Abstract, para. 2) | Faithfulness 0.889; relevancy 0.906; precision 0.753; recall 0.691; correctness 0.517; N=99 / [NOT STATED: latency-ms] | [CORROBORATION] CarePaws will report the same multi-metric counted profile rather than adjectives for its evaluated modules [Features 1, 2] |
| 3 | Related Studies-Quantitative-Metric-Outcomes | Dual human-acceptance result from veterinarians and pet owners | 9 licensed vets, 32 owners, La Union | "yielding an overall mean of 4.56" (Alverde et al., Abstract, expert evaluation, para. 2) | Vets 4.56 overall (triage utility 4.67; non-urgent 4.65, urgent 4.57, emergency 4.47); owners SUS 79.61 Grade A- Excellent, N=32 / [NOT STATED: SD] | [CORROBORATION] CarePaws will replicate this dual expert-plus-owner acceptance gate for its own build [Features 1, 2] |
| 4 | Related Studies-Acknowledged-Architectural-Flaws | Retrieval-coverage gap with slower emergency handling and response-time complaint | La Union deployment, stated feedback | "Context Recall (0.691) reflected moderately high retrieval performance, with room for improvement in retrieval coverage" (Alverde et al., Abstract, para. 2) | Recall 0.691; emergency mean 4.47 vs 4.65 non-urgent / [NOT STATED: latency-ms, failure rates] | [CONTRADICTION] CarePaws will avoid this online-retrieval failure mode with local records plus queued sync and a measured response-time NFR [Features 2, 4] |
Excluded: [1] candidate omitted (900-char chunk/20-to-6 re-rank detail — component tuning, thin for 1.9.2 architecture claim).
