# 1.5 Conceptual Framework — VetBot
> Source: `Sources/VetBot.md` | Date: 2026-09-24 | Depth: standard
> Verdict (Task 2): HIGHLY USABLE
---
### Task 1 — Bibliographic Classification
- **Title**: VetBot: An AI-Driven Veterinary Chatbot for Canine and Feline Care Guidance
- **Authors**: Edward Andrew P. Alverde, James Robert F. Dangbis, Voke Michael Oghenekaro, Paul Emmanuelle Quimpo, Johnny F. Verzola
- **Year**: 2025 [INFERRED: no explicit date line; latest citations 2025, academic year 2024–2025 — treated as PASS with flag]
- **Recency**: PASS (2016–2026, provisional — explicit year [MISSING])
- **Outlet**: Lorma Colleges, College of Computer Studies and Engineering [MISSING: journal/conference, DOI/URL]
- **DOI/URL**: [MISSING: DOI/URL]
- **Setting**: Local (Philippines) + "La Union, Philippines" provincial gap; canine/feline scope
- **Design**: DSR Artifact (Agile SDLC: requirements, design, development, testing, deployment; RAG: Flutter/Django/PostgreSQL/ChromaDB/Gemini 3 Flash; RAGAS N=99; 9 vets overall 4.56; 32 owners SUS 79.61 Excellent)
- **APA7**: Alverde, E. A. P., Dangbis, J. R. F., Oghenekaro, V. M., Quimpo, P. E., & Verzola, J. F. (2025). *VetBot: An AI-driven veterinary chatbot for canine and feline care guidance* (Unpublished undergraduate thesis, Lorma Colleges). [MISSING: DOI/URL, explicit year]
- **Fit**: Richest AI-process plus output precedent for 1.5: names input baselines (symptom confusion, distance), a retrieve-generate-guardrail pipeline with inside-arrow escalation logic, Agile cycles, and a triple output bar (RAGAS + vets + SUS).

### Task 2 — Verdict
- **Verdict**: HIGHLY USABLE (4 mechanisms, 5 slots)
- **Bullets**:
  - Why + recency: provisional PASS (2025 inferred); Flutter/Django/PostgreSQL/ChromaDB/Gemini 3 Flash pipeline with ingestion→retrieval→generation→guardrail flow and Agile requirements-to-deployment chain.
  - Slots populated → Features: [Input-Clinic-Baselines] → Feature 7; [Process-RBAC-Engineering] → Features 4, 7; [Process-Agile-DSR-Cycles] → Features 1–7; [Process-Inside-The-Arrows-Causal-Logic] → Feature 7; [Output-Empirical-Usability-Baseline] → Feature 7.
  - Missing: [Input-ISO25010-Standards] (RAGAS/SUS used, not ISO 25010 by name).
  - Panel use: deflects "AI box is a black box" — every arrow (ingest, retrieve, generate, guardrail, escalate) is named with its metric.
  - Caveat: canine/feline only; transfer pipeline shape and metric bar, not weights or corpus.

### Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Conceptual Framework-Process-Agile-DSR-Cycles | Agile SDLC chain from requirements through deployment with continuous feedback | VetBot build, mobile + backend scope | "The development of VetBot followed the Agile Software Development Life Cycle (SDLC), which consists of the requirements, design, development, testing, and deployment" (Alverde et al. 2025, Methodology, para. 2) | [NOT STATED: sprint length, velocity] | [METHOD] CarePaws will run its process arrow as Agile requirements-to-deployment cycles with feedback loops [Features 1–7] |
| 2 | Conceptual Framework-Process-Inside-The-Arrows-Causal-Logic | Retrieve-generate-guardrail-escalate logic from chunks through grounded answers to referral | RAGAS N=99, curated veterinary sources | "The RAG workflow consists of an ingestion phase where curated veterinary documents are cleaned, chunked into 800-token segments with 200-token overlaps, embedded with text-embedding-3-small, indexed in ChromaDB, and retrieved through Maximal Marginal Relevance" (Alverde et al. 2025, Methodology RAG, para. 1) | 800-token chunks; 200-token overlap; N=99 / [NOT STATED: k, thresholds] | [CORROBORATION] CarePaws will write its Feature 7 inside-the-arrows logic the same way: retrieve → generate with citations → guardrail → escalate [Feature 7] |
| 3 | Conceptual Framework-Process-RBAC-Engineering | Owner-chatbot plus veterinarian-portal role split with gated access | Flutter owner app vs vet portal; 9 vets; 32 owners | "Triage Report Utility received the highest weighted mean (4.67), suggesting that the AI-generated triage reports provided to veterinarians were considered well-structured and useful for supporting case review" (Alverde et al. 2025, Results Table 2, para. 1) | Vet overall 4.56; triage 4.67; SUS 79.61 / [NOT STATED: permission matrix] | [CORROBORATION] CarePaws will gate its AI lane by role: owners query while veterinarians review structured summaries [Features 4, 7] |
| 4 | Conceptual Framework-Output-Empirical-Usability-Baseline | Triple output bar of retrieval-grounded generation, expert agreement, and usability | RAGAS N=99; 9 vets; 32 owners | "Faithfulness scored 0.889 and Answer Relevancy 0.906, indicating that responses drew on retrieved veterinary sources and addressed user queries directly" (Alverde et al. 2025, Abstract, para. 3) | Faithfulness 0.889; relevancy 0.906; precision 0.753; recall 0.691; correctness 0.517; vet 4.56; SUS 79.61 Excellent | [CORROBORATION] CarePaws will define its Feature 7 output box with groundedness plus expert-plus-usability thresholds at or above this bar [Feature 7] |
Excluded: [1] candidate omitted (vet-to-vet transfer recommendation — future work, not an IPO element).
