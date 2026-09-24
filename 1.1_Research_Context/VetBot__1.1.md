# 1.1 Research Context — VetBot
> Source: `Sources/VetBot.md` | Date: 2026-09-24 | Depth: standard
> Verdict (Task 2): PARTIALLY USABLE
---
### Task 1 — Bibliographic Classification
- **Title**: VetBot: An AI-Driven Veterinary Chatbot for Canine and Feline Care Guidance
- **Authors**: Edward Andrew P. Alverde, James Robert F. Dangbis, Voke Michael Oghenekaro, Paul Emmanuelle Quimpo, Johnny F. Verzola
- **Year**: 2025 [INFERRED: no explicit date line in mined text; latest citations 2025, academic year 2024–2025 — treated as PASS with flag]
- **Recency**: PASS (2016–2026, provisional — explicit year [MISSING])
- **Outlet**: Lorma Colleges, College of Computer Studies and Engineering [MISSING: journal/conference, DOI/URL]
- **DOI/URL**: [MISSING: DOI/URL]
- **Setting**: Local (Philippines) + "provincial settings such as La Union, Philippines" with "limited clinic access and geographic distance"
- **Design**: DSR Artifact (RAG chatbot Flutter/Django/PostgreSQL/ChromaDB/Gemini 3 Flash; RAGAS N=99; 9 vets Likert; 32 owners SUS)
- **APA7**: Alverde, E. A. P., Dangbis, J. R. F., Oghenekaro, V. M., Quimpo, P. E., & Verzola, J. F. (2025). *VetBot: An AI-driven veterinary chatbot for canine and feline care guidance* (Unpublished undergraduate thesis, Lorma Colleges). [MISSING: DOI/URL, explicit year]
- **Fit**: Provincial-access anchor for 1.1: documents symptom-interpretation gaps compounded by distance — transfers as the demand-side context for a guidance feature, not a clinical baseline.

### Task 2 — Verdict
- **Verdict**: PARTIALLY USABLE (2 mechanisms, 2 slots)
- **Bullets**:
  - Why + recency: provisional PASS (2025 inferred); La Union provincial gap with RAGAS and SUS metrics supporting the problem claim.
  - Slots populated → Features: [Meso-Rural-Provincial-Constraints] → Features 4, 7; [Micro-Clinical-Breaking-Points] → Feature 7. No manual-ledger or statutory content.
  - Missing: [Macro-Digital-Transformation], [Manual-Ledger-Vulnerabilities], [Statutory-Imperatives-RA10173-RA9268] (all [NOT STATED] in this source for 1.1).
  - Panel use: deflects "why guidance for provincial owners" — distance plus inability to judge visit urgency.
  - Caveat: student build, canine/feline only; transfer access-gap pattern only.

### Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Research Context-Meso-Rural-Provincial-Constraints | Limited clinic access with geographic distance compounding owner knowledge gaps | La Union provincial setting, canine/feline owners | "Pet owners often struggle to interpret symptoms, apply basic first aid, or judge when a veterinary visit is necessary. In provincial settings such as La Union, Philippines, limited clinic access and geographic distance compound these gaps" (Alverde et al. 2025, Abstract, para. 1) | [NOT STATED: no distance km, no access rate] | [PROVINCIAL] CarePaws will add a non-diagnostic symptom explainer with visit-urgency signposting so distant owners judge next steps safely [Feature 7] |
| 2 | Research Context-Micro-Clinical-Breaking-Points | Owner inability to judge seriousness of fatigue, appetite loss, minor injury, and distress | Owner-observed symptom baseline per cited prior research | "Pet owners regularly encounter situations in which their pets display concerning symptoms, including persistent fatigue, loss of appetite, minor injuries, and signs of distress" (Alverde et al. 2025, Introduction, para. 1) | [NOT STATED: no misjudgment rate] | [MECHANISM] CarePaws will route such symptom queries to safety-oriented first-aid information plus referral prompts rather than leaving owners to guess [Feature 7] |
Excluded: [2] candidates omitted (RAGAS/SUS scores — evaluation outcomes for 1.5/2.6, not 1.1 context).
