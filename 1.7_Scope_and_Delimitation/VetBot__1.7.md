# 1.7 Scope and Delimitation — VetBot
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
- **Setting**: Local (Philippines) — "In provincial settings such as La Union, Philippines" (Abstract, para. 1)
- **Design**: DSR Artifact (RAG build with explicit scope/limitation section: canine/feline only, guidance-not-diagnosis, La Union locator)
- **APA7**: Alverde, E. A. P., Dangbis, J. R. F., Oghenekaro, V. M., Quimpo, P. E., & Verzola, J. F. (n.d.). *VetBot: An AI-driven veterinary chatbot for canine and feline care guidance*. Lorma Colleges. [MISSING: year — verify]
- **Fit**: Cleanest guidance-scope boundary in the batch: species, urgency-routing, locator, and diagnostic ceilings are each explicitly fenced — the Feature 7 delimitation model.

### Task 2 — Verdict
- **Verdict**: HIGHLY USABLE (4 mechanisms, 4 slots)
- **Bullets**:
  - Why + recency: UNVERIFIED year but full-pattern fit — every boundary names its mechanism and justification.
  - Slots populated → Features: [Population-Boundary] → Feature 7; [System-Feature-Boundary] → Feature 7; [Temporal-Pilot-Boundary] → Feature 7; [Deliberate-Exclusion-Justification] → Feature 7.
  - Missing: none — all four slots grounded.
  - Panel use: deflects "AI scope is unbounded" — the source fenced species, diagnosis, locator, and data window in one section.
  - Caveat: transfer the fencing pattern only; never the La Union site.

### Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Scope and Delimitation-Population-Boundary | Evaluation population bounded to 9 vets, 32 owners, and 99 queries | La Union, canine/feline scenarios | "factual accuracy and clinical suitability of VetBot's outputs were validated by nine (9) licensed veterinarians" (Alverde et al., RAGAS/Expert section, para. 5) | 9 vets; 32 owners; N=99 / [NOT STATED: recruitment frame] | [CORROBORATION] CarePaws will bound its evaluation population the same way: named expert, owner, and query counts [Feature 7] |
| 2 | Scope and Delimitation-System-Feature-Boundary | Feature ceiling bounded to triage, guidance, first aid, vet card, and locator | RAG build, English/Tagalog | "VetBot performs triage assessment, delivers general health guidance and safety-oriented first aid instructions, and provides limited home-based care advice for low-risk cases" (Alverde et al., Abstract, para. 2) | [NOT STATED: module counts] | [CORROBORATION] CarePaws will bound its guidance ceiling the same way: enumerated in-scope functions [Feature 7] |
| 3 | Scope and Delimitation-Temporal-Pilot-Boundary | Data/evaluation window bounded to curated corpus with dated retrieval | Two-corpus design, N=99 | "The RAG pipeline was evaluated with the RAGAS framework on 99 clinical test queries" (Alverde et al., Abstract, para. 3) | N=99 / [NOT STATED: window dates] | [CORROBORATION] CarePaws will bound its pilot window the same way: stated query set with corpus dates [Feature 7] |
| 4 | Scope and Delimitation-Deliberate-Exclusion-Justification | Diagnostic ceiling excluded: guidance never replaces clinical judgment | All urgency levels, safety-scoped | "connects owners to professional veterinary services without replacing clinical judgment" (Alverde et al., Abstract, para. 3) | Vet mean 4.56; SUS 79.61 / [NOT STATED: harm rate] | [CORROBORATION] CarePaws will justify its diagnostic exclusion the same way: explainer ceiling with referral routing [Feature 7] |
Excluded: [1] candidate omitted (ChromaDB cosine detail — retrieval internals, not a boundary).
