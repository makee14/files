# 1.9.2 Related Studies — C-MALICDEM,+KIMBERLEY+P_Research+Article+Revised+3
> Source: `Sources/C-MALICDEM,+KIMBERLEY+P_Research+Article+Revised+3.md` | Date: 2026-09-25 | Depth: standard
> Verdict (Task 2): HIGHLY USABLE
---
### Task 1 — Bibliographic Classification
- **Title**: SMART Vet: A Knowledge Management Platform Application for Enhancing Local Government Unit Veterinary Services
- **Authors**: Kimberley P. Malicdem, Bernardo D. Lamadrid
- **Year**: 2025
- **Recency**: PASS (2016–2026)
- **Outlet**: DMMMSU Research and Extension Journal, 9(1), 139–156
- **DOI/URL**: [NOT FOUND]
- **Setting**: Local (Philippines) + "The research was conducted at the City Veterinarian Office of San Fernando, La Union, Philippines"
- **Design**: DSR Artifact (mixed-methods developmental build with descriptive quantitative and qualitative evaluation)
- **APA7**: Malicdem, K. P., & Lamadrid, B. D. (2025). SMART Vet: A knowledge management platform application for enhancing local government unit veterinary services. *DMMMSU Research and Extension Journal, 9*(1), 139–156. [MISSING: DOI]
- **Fit**: Empirical 2025 LGU veterinary platform build with a named cross-platform stack, two evaluation samples, ISO/IEC 25010 outcomes, connectivity constraints, and an acknowledged IT-support dependency.

### Task 2 — Verdict
- **Verdict**: HIGHLY USABLE (4 mechanisms, 4 slots)
- **Bullets**:
  - Why + recency: PASS (2025); the mixed-methods system build reports four grounded mechanisms across architecture, connectivity, measured usability, and deployment support.
  - Slots populated → Features: [Empirical-System-Architecture] → Features 1, 2, 4, 6; [Connectivity-Assumptions] → Features 1, 2, 4, 6; [Quantitative-Metric-Outcomes] → Features 1, 2, 4, 6; [Acknowledged-Architectural-Flaws] → Features 1, 2, 4, 6.
  - Missing: [Hardware-Offline-Fallbacks] (no hardware, local cache, offline queue, or reconnect test); DB engine, framework versions, latency, and SD are [NOT STATED].
  - Panel use: deflects “no measured LGU precedent” with n=30 usability and n=9 acceptability evidence tied to a named local veterinary platform.
  - Caveat: the lead author both developed and evaluated the system; livestock-oriented participants and modules exceed CarePaws’ canine/feline boundary, so transfer is limited to the in-scope mechanisms.

### Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Related Studies-Empirical-System-Architecture | Flutter mobile client, JSON front-end/back-end exchange, and hosted web delivery formed the cross-platform stack | n=30 usability respondents and n=9 focus-group veterinarians; San Fernando City LGU veterinary office; no prior digital platform | "Flutter served as the primary development framework for mobile application development [...] Data management utilized JavaScript Object Notation (JSON) for efficient data structuring and exchange between front-end and back-end components [...] Web deployment infrastructure was established through Z.com domain registration services and dedicated web hosting subscriptions" (Malicdem & Lamadrid 2025, Materials and Methods, Implementation phase, para. 1) | [NOT STATED: framework versions, DB engine, backend language, offline cache/sync] | [CORROBORATION] CarePaws will document its client, data-exchange, and web-deployment layers for scheduling, records, reminders, and invoicing [Features 1, 2, 4, 6] |
| 2 | Related Studies-Connectivity-Assumptions | The deployment remained exposed to internet-connectivity constraints at government facilities | City Government of San Fernando LGU deployment; office without an existing digital platform | "implementation challenges included inadequate technological infrastructure within government facilities, limited internet connectivity" (Malicdem & Lamadrid 2025, Abstract, para. 2) | Limited internet connectivity reported; [NOT STATED: bandwidth, uptime, outage count, offline behavior] | [CONTRADICTION] CarePaws will queue appointment and record changes locally and verify reconnect synchronization under simulated connectivity loss [Features 1, 2, 4, 6] |
| 3 | Related Studies-Quantitative-Metric-Outcomes | The ISO/IEC 25010 evaluation produced an overall mean of 4.49/5 across eight quality characteristics | n=30 usability respondents, six stakeholder groups × five; 5-point Likert; San Fernando City LGU | "achieving an overall mean rating of 4.49 corresponding to an  \"Excellent\" rating and \"Very Highly Usable\" interpretation according to established evaluation standards" (Malicdem & Lamadrid 2025, Results and Discussion, para. 1) | Overall mean=4.49/5; n=30; [INCOMPLETE STATISTICAL REPORTING: SD and per-item results not stated] | [CORROBORATION] CarePaws will report overall and characteristic-level ISO/IEC 25010 means for its evaluated features [Features 1, 2, 4, 6] |
| 4 | Related Studies-Acknowledged-Architectural-Flaws | The workflow depended on external IT support because the veterinary office had no dedicated IT staff | n=9 veterinarians; 2 LGU and 7 private-practice participants; qualitative focus group | "An IT person should handle this application because they are the ones who manage systems, we don't have IT staff, we'll have difficulty using it" (Malicdem & Lamadrid 2025, Results and Discussion, Usability and Accessibility, participant excerpt 3) | n=9; no dedicated LGU IT staff reported; [NOT STATED: support hours, training duration, failure rate] | [CONTRADICTION] CarePaws will provide trained administrator ownership and role-specific support for scheduling, records, reminders, and billing [Features 1, 2, 4, 6] |
Excluded: [3] candidates omitted (app-store review state; unnamed database schema; impound/adoption features quarantined outside Features 1–7).