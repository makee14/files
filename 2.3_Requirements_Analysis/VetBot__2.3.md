# 2.3 Requirements Analysis — VetBot
> Source: `Sources/VetBot.md` | Date: 2026-09-24 | Depth: standard
> Verdict (Task 2): HIGHLY USABLE
---
### Task 1 — Bibliographic Classification
- **Title**: VetBot: An AI-Driven Veterinary Chatbot for Canine and Feline Care Guidance
- **Authors**: Edward Andrew P. Alverde, James Robert F. Dangbis, Voke Michael Oghenekaro, Paul Emmanuelle Quimpo, Johnny F. Verzola
- **Year**: [MISSING: year not stated in extracted text]
- **Recency**: UNCLASSIFIED (year unstated; stack indicates contemporary work; FAIL rule applies only to verified pre-2016)
- **Outlet**: [MISSING: outlet not stated in extracted text; Lorma Colleges capstone manuscript]
- **DOI/URL**: [MISSING: DOI not stated in extracted text]
- **Setting**: Local (Philippines) + "In provincial settings such as La Union, Philippines, limited clinic access and geographic distance compound these gaps."
- **Design**: DSR Artifact (RAG chatbot; RAGAS N=99; 9 licensed veterinarians; 32 pet owners, SUS 79.61)
- **APA7**: Alverde, E. A. P., Dangbis, J. R. F., Oghenekaro, V. M., Quimpo, P. E., & Verzola, J. F. ([MISSING: year]). VetBot: An AI-driven veterinary chatbot for canine and feline care guidance. Lorma Colleges. [MISSING: outlet, DOI]
- **Fit**: Only source with a scored assistive-triage function plus a digital pet-profile record — the direct 2.3 precedent for Features 7 and 2.
### Task 2 — Verdict
- **Verdict**: HIGHLY USABLE (4 mechanisms, 2 slots)
- **Bullets**:
  - Why + recency: UNCLASSIFIED (year unstated; Gemini-3-Flash RAG stack marks contemporary work); triage plus vet-card functions with expert and SUS scoring.
  - Slots populated → Features: [Functional-Requirements-Features-1-7] → Features 2, 7; [Non-Functional-ISO25010-NFR] → Feature 7.
  - Missing: [RBAC-Permission-Matrix-Rule] ([NOT STATED] — vet portal exists but no permission matrix); [Data-Flow-Inventory-Ledger-Map] ([NOT STATED]); clinic-locator module quarantined (geolocation outside Features 1–7).
  - Panel use: deflects "AI explainer has no scoped precedent" — non-diagnostic triage with vet-retained authority plus Strongly Agree expert means.
  - Caveat: transfer the triage, vet-card, and accessibility pattern; RAGAS tuning parameters are engineering detail for later chapters.
### Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Requirements Analysis-Functional-Requirements-Features-1-7 | Triage-assessment function delivering general health guidance, safety-oriented first aid, and limited low-risk home-care advice | Canine and feline cases, La Union, owner-uncertainty baseline | "VetBot performs triage assessment, delivers general health guidance and safety-oriented first aid instructions, and provides limited home-based care advice for low-risk cases." (Alverde et al., Abstract, para. 2) | Triage Report Utility 4.67 / [NOT STATED: response latency, case n] | [PRECEDENT] CarePaws will specify its symptom-explainer function with the same triage plus first-aid plus low-risk-advice bounding and a vet-consultation disclaimer [Feature 7] |
| 2 | Requirements Analysis-Functional-Requirements-Features-1-7 | Pet-profiling function issuing a digital vet card per animal | Canine and feline cases, La Union, paper-record baseline | "Supporting modules include pet profiling with a digital vet card" (Alverde et al., Abstract, para. 2) | [NOT STATED: n, card fields, adoption rate] | [PRECEDENT] CarePaws will specify its profiling function with the same per-animal digital-card mechanism [Feature 2] |
| 3 | Requirements Analysis-Non-Functional-ISO25010-NFR | Accessibility NFR combining speech-to-text, text-to-speech, and bilingual English plus Tagalog support | La Union pet owners, low-access provincial baseline | "accessibility features comprising speech-to-text, text-to-speech, and bilingual English and Tagalog support" (Alverde et al., Abstract, para. 2) | [NOT STATED: n, WCAG audit, language split] | [CORROBORATION] CarePaws will state its owner-side accessibility NFR with the same voice plus bilingual mechanism [Feature 7] |
| 4 | Requirements Analysis-Non-Functional-ISO25010-NFR | Owner-rated usability outcome on the System Usability Scale | n=32 pet owners, La Union | "Thirty-two (32) pet owners completed the System Usability Scale (SUS), producing a score of 79.61" (Alverde et al., Abstract, para. 3) | SUS 79.61, Grade A-, Excellent, n=32 / [NOT STATED: SD] | [CALIBRATION] CarePaws will benchmark its owner-side usability NFR against the same SUS 79.61 Excellent reading [Features 4, 7] |
Excluded: [1] candidate omitted (clinic-locator module covering La Union — geolocation content outside Features 1–7, quarantined scope).