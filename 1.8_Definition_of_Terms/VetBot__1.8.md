# 1.8 Definition of Terms — VetBot
> Source: `Sources/VetBot.md` | Date: 2026-09-24 | Depth: standard
> Verdict (Task 2): PARTIALLY USABLE
---
### Task 1 — Bibliographic Classification
- **Title**: VetBot: An AI-Driven Veterinary Chatbot for Canine and Feline Care Guidance
- **Authors**: Edward Andrew P. Alverde, James Robert F. Dangbis, Voke Michael Oghenekaro, Paul Emmanuelle Quimpo, Johnny F. Verzola
- **Year**: [NOT STATED — Gemini 3 Flash + 5S/6S methods date it ca. 2025–2026; VERIFY]
- **Recency**: UNVERIFIED (no year printed; treat as recent-pattern precedent with caution)
- **Outlet**: Lorma Colleges, College of Computer Studies and Engineering (capstone manuscript)
- **DOI/URL**: [NOT FOUND]
- **Setting**: Local (Philippines) — "In provincial settings such as La Union, Philippines" (Abstract, para. 1)
- **Design**: DSR Artifact (RAG chatbot with triage, first aid, vet-card, and locator modules)
- **APA7**: Alverde, E. A. P., Dangbis, J. R. F., Oghenekaro, V. M., Quimpo, P. E., & Verzola, J. F. (n.d.). *VetBot: An AI-driven veterinary chatbot for canine and feline care guidance*. Lorma Colleges. [MISSING: year — verify]
- **Fit**: Defines two glossable pairs — RAG chatbot (explainer) and triage assessment — each with a conceptual source-line plus a CarePaws-operational use; the Feature 7 term anchor.

### Task 2 — Verdict
- **Verdict**: PARTIALLY USABLE (2 term pairs)
- **Bullets**:
  - Why + recency: UNVERIFIED year but precise term mechanics — retrieval-grounded generation plus urgency routing with safety ceilings.
  - Slots populated → Features: [Term-Conceptual-Definition] + [Term-Operational-Definition] for "retrieval-augmented-generation chatbot" and "triage assessment" → Feature 7.
  - Missing: the other locked terms (all [NOT STATED]).
  - Panel use: anchors explainer and triage to a locally evaluated build with named bars, not dictionary senses.
  - Caveat: transfer definition structure only; never present guidance as diagnosis.

### Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Definition of Terms-Term-Conceptual-Definition | Retrieval-augmented-generation chatbot: language-model answers grounded in retrieved veterinary sources | Gemini 3 Flash + ChromaDB, curated corpus | "based on a Retrieval-Augmented Generation (RAG) architecture" with "Gemini 3 Flash as the language model" (Alverde et al., Abstract, para. 2) | Faithfulness 0.889; relevancy 0.906 | [CORROBORATION] CarePaws will define RAG explainer conceptually as retrieval-grounded generated guidance [Feature 7] |
| 2 | Definition of Terms-Term-Operational-Definition | Retrieval-augmented-generation chatbot: in CarePaws, the explainer answering FAQs from curated sources with referral routing | Canine/feline guidance scope, English/Tagalog | "VetBot performs triage assessment, delivers general health guidance and safety-oriented first aid instructions" (Alverde et al., Abstract, para. 2) | SUS 79.61 Excellent / [NOT STATED: query volume] | [CORROBORATION] CarePaws will define explainer operationally as curated-source FAQs with referral routing [Feature 7] |
| 3 | Definition of Terms-Term-Conceptual-Definition | Triage assessment: urgency classification routing cases to guidance or referral | Non-urgent/urgent/emergency scenarios, 9-vet review | "VetBot performs triage assessment" across "three levels of urgency: non-urgent, urgent, and emergency" (Alverde et al., Abstract + Expert section) | Urgency means 4.65/4.57/4.47 | [CORROBORATION] CarePaws will define triage conceptually as urgency classification with referral routing [Feature 7] |
| 4 | Definition of Terms-Term-Operational-Definition | Triage assessment: in CarePaws, the explainer's urgency routing that escalates emergencies to veterinarians | Safety-scoped, low-risk home advice only | "connects owners to professional veterinary services without replacing clinical judgment" (Alverde et al., Abstract, para. 3) | Escalation 4.59; safety 4.61 | [CORROBORATION] CarePaws will define triage operationally as escalate-to-vet routing for urgent cases [Feature 7] |
Excluded: [1] candidate omitted (digital vet card gloss — module feature, not a locked term).
