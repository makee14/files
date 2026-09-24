# 2.5 System Requirements — VetBot
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
- **Design**: DSR Artifact (Flutter plus Django plus PostgreSQL plus ChromaDB plus Gemini 3 Flash; layered modular architecture)
- **APA7**: Alverde, E. A. P., Dangbis, J. R. F., Oghenekaro, V. M., Quimpo, P. E., & Verzola, J. F. ([MISSING: year]). VetBot: An AI-driven veterinary chatbot for canine and feline care guidance. Lorma Colleges. [MISSING: outlet, DOI]
- **Fit**: Only versioned five-component stack with a layered client-server-retrieval-generation topology — the strongest same-scope 2.5 precedent for the CarePaws layered build.
### Task 2 — Verdict
- **Verdict**: HIGHLY USABLE (4 mechanisms, 2 slots)
- **Bullets**:
  - Why + recency: UNCLASSIFIED (year unstated); five named engines plus an explicit three-layer plus retrieval-plus-generation topology.
  - Slots populated → Features: [Software-Stack-Architecture] → Features 2, 7; [Security-RBAC-Compliance] → Feature 2.
  - Missing: [Hardware-Minimum-Specification] (no client or server spec); [Network-Dependency-Offline-Mode] ([NOT STATED] — no bandwidth, no offline queue); email-TLS tokens absent.
  - Panel use: deflects "stack unproven in-province" — La Union canine and feline build with modular separation of transactional and retrieval stores.
  - Caveat: transfer the layered-stack precedent; the LLM retrieval engine itself belongs to Feature 7 design detail, and versioned CarePaws specs must come from the technical plan.
### Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | System Requirements-Software-Stack-Architecture | Mobile-interface engine pairing Flutter clients with a Django backend | Canine and feline chatbot, La Union | "The system was implemented with a Flutter mobile interface, a Django backend" (Alverde et al., Abstract, para. 2) | [NOT STATED: versions, sizing, latency] | [PRECEDENT] CarePaws will specify its client-plus-application layers with the same interface-plus-backend explicitness [Features 2, 7] |
| 2 | System Requirements-Software-Stack-Architecture | Dual-store data layer separating PostgreSQL transactional records from ChromaDB semantic retrieval | Canine and feline chatbot, La Union | "PostgreSQL for transactional data, and ChromaDB for semantic retrieval, with Gemini 3 Flash as the language model." (Alverde et al., Abstract, para. 2) | [NOT STATED: versions, schema types, index sizes] | [PRECEDENT] CarePaws will separate its transactional record store from its assistive-retrieval store the same way [Features 2, 7] |
| 3 | System Requirements-Software-Stack-Architecture | Layered client-server-retrieval-generation topology across presentation, application, retrieval, and knowledge layers | Canine and feline chatbot, La Union | "responses are produced through coordinated layers: the presentation layer (Flutter UI), the application layer (Django backend), the retrieval layer (ChromaDB vector database), and the knowledge layer (curated veterinary documents)." (Alverde et al., System Architecture, para. 1) | [NOT STATED: bandwidth, failover, sync rule] | [TEMPLATE] CarePaws will document its presentation, application, retrieval, and knowledge layers the same way [Features 2, 7] |
| 4 | System Requirements-Security-RBAC-Compliance | Role-scoped vet-portal chatbot control restricting clinical review to veterinary staff | La Union, six-scenario evaluation | "The vet portal includes a chatbot for veterinarians, allowing them to ask follow-up questions for decision support." (Alverde et al., Vet Portal, para. 2) | [NOT STATED: auth mechanism, permission matrix, audit log] | [SEED] CarePaws will scope its veterinarian-only decision-support controls the same way, adding the full RBAC matrix plus audit rule [Feature 2] |
Excluded: [1] candidate omitted (speech-to-text plus text-to-speech plus bilingual pipeline — accessibility NFR content for 2.3, not a 2.5 stack token).