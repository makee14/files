# 1.2 Purpose and Description of the Study — VetBot
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
- **Design**: DSR Artifact (RAG: Flutter mobile, Django backend, PostgreSQL transactions, ChromaDB retrieval, Gemini 3 Flash; RAGAS N=99; 9 vets Likert overall 4.56; 32 owners SUS 79.61 Excellent)
- **APA7**: Alverde, E. A. P., Dangbis, J. R. F., Oghenekaro, V. M., Quimpo, P. E., & Verzola, J. F. (2025). *VetBot: An AI-driven veterinary chatbot for canine and feline care guidance* (Unpublished undergraduate thesis, Lorma Colleges). [MISSING: DOI/URL, explicit year]
- **Fit**: Direct Feature 7 purpose analogue for 1.2: bounds an AI guidance purpose (triage, first aid, home-care for low-risk cases) as decision support without replacing clinical judgment, with measured RAGAS/expert/SUS targets.

### Task 2 — Verdict
- **Verdict**: HIGHLY USABLE (4 mechanisms, 4 slots)
- **Bullets**:
  - Why + recency: provisional PASS (2025 inferred); built RAG system with faithfulness 0.889, relevancy 0.906, precision 0.753, recall 0.691, correctness 0.517; vets 4.56; SUS 79.61.
  - Slots populated → Features: [Primary-Intervention-Mechanism] → Feature 7; [Function-Feature-1-7] → Features 2, 4, 7; [Role-Gated-Value-Creation] → Features 4, 7; [Metric-Change-Target] → Feature 7.
  - Missing: [System-Novelty] only partly (RAG-over-curated-sources is an application pattern, not a novel model).
  - Panel use: deflects "AI diagnosis overreach" — scope is explicitly guidance plus referral, validated safe by 9 vets including emergency scenarios (4.47).
  - Caveat: canine/feline only; transfer scope-and-metric pattern, not weights or knowledge base.

### Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Purpose and Description-Primary-Intervention-Mechanism | RAG chatbot delivering triage, first-aid, and low-risk home-care guidance without replacing judgment | La Union provincial access gap, canine/feline scope | "VetBot performs triage assessment, delivers general health guidance and safety-oriented first aid instructions, and provides limited home-based care advice for low-risk cases" (Alverde et al. 2025, Abstract, para. 2) | N=99 queries; faithfulness 0.889; relevancy 0.906 / [NOT STATED: deployment n] | [PRECEDENT] CarePaws will bound its Feature 7 purpose identically: triage signposting plus safety-oriented first-aid information with referral, never diagnosis [Feature 7] |
| 2 | Purpose and Description-Function-Feature-1-7 | Support-module set of pet profiling with digital vet card, clinic locator, and bilingual voice access | Built Flutter/Django/PostgreSQL/ChromaDB/Gemini 3 Flash system | "Supporting modules include pet profiling with a digital vet card, a clinic locator covering La Union, and accessibility features comprising speech-to-text, text-to-speech, and bilingual English and Tagalog support" (Alverde et al. 2025, Abstract, para. 2) | [NOT STATED: per-module scores] | [MECHANISM] CarePaws will describe the same support ring: pet profile [Feature 2], clinic/portal contact [Feature 4], and explainer access [Feature 7] |
| 3 | Purpose and Description-Role-Gated-Value-Creation | Dual-role value split between owner chatbot output and veterinarian triage-report utility | 9 vets across 6 scenarios; 32 owners | "Triage Report Utility received the highest weighted mean (4.67), suggesting that the AI-generated triage reports provided to veterinarians were considered well-structured and useful for supporting case review" (Alverde et al. 2025, Results Table 2, para. 1) | Overall vet mean 4.56; triage utility 4.67; SUS 79.61 / [NOT STATED: consult-time delta] | [CORROBORATION] CarePaws will gate AI value by role: owners get guidance while veterinarians get structured pre-consult summaries [Features 2, 7] |
| 4 | Purpose and Description-Metric-Change-Target | Dual acceptance bar of retrieval-grounded generation plus usability | RAGAS N=99; 9 vets; 32 owners | "Faithfulness scored 0.889 and Answer Relevancy 0.906, indicating that responses drew on retrieved veterinary sources and addressed user queries directly" (Alverde et al. 2025, Abstract, para. 3) | Faithfulness 0.889; relevancy 0.906; precision 0.753; recall 0.691; correctness 0.517; SUS 79.61 | [TRANSFER] CarePaws will state its Feature 7 target as groundedness plus usability at or above these thresholds [Feature 7] |
Excluded: [1] candidate omitted (vet-to-vet transfer recommendation — future work, not a built mechanism).
