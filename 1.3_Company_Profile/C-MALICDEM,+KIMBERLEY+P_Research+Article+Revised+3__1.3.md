# 1.3 Company Profile — C-MALICDEM,+KIMBERLEY+P_Research+Article+Revised+3
> Source: `Sources/C-MALICDEM,+KIMBERLEY+P_Research+Article+Revised+3.md` | Date: 2026-09-25 | Depth: standard
> Verdict (Task 2): HIGHLY USABLE
---

### Task 1 — Bibliographic Classification
- **Title**: SMART Vet: A Knowledge Management Platform Application for Enhancing Local Government Unit Veterinary Services
- **Authors**: Kimberley P. Malicdem and Bernardo D. Lamadrid
- **Year**: 2025
- **Recency**: PASS (2016–2026)
- **Outlet**: DMMMSU Research and Extension Journal, 9(1), 139–156
- **DOI/URL**: [NOT FOUND]
- **Setting**: Local (Philippines) + proof quote “The research was conducted at the City Veterinarian Office of San Fernando, La Union, Philippines...”
- **Design**: DSR Artifact
- **APA7**: Malicdem, K. P., & Lamadrid, B. D. (2025). SMART Vet: A knowledge management platform application for enhancing local government unit veterinary services. *DMMMSU Research and Extension Journal, 9*(1), 139–156. [MISSING: DOI/URL]
- **Fit**: Supplies a Philippine LGU veterinary-office profile and documented technology, role, and support constraints that can benchmark (but not replace) PetCare's own single-clinic fieldwork.

### Task 2 — Verdict
- **Verdict**: HIGHLY USABLE (≥3 mechanisms, ≥2 slots)
- **Bullets (3–5)**:
  - Recency passes (2025), and the source supplies four mechanisms spanning operational workflow, technology baseline, implementation support, and role-gated access; usability n=30 and acceptability n=9 are reported.
  - Slots populated: Operational-Profile, Technology-Baseline, Vulnerability-Audit, Org-Staff-Roles → Features 1, 2, and 4 (appointment, records, and communication analogues).
  - Missing: PetCare-specific throughput, hardware assets, headcount, manual-friction counts, production latency/availability, and security findings; no direct evidence for Features 3, 5, or 7.
  - Panel use: Deflects the claim that Philippine resource-constrained veterinary offices cannot adopt digital workflows, while showing that IT support and training are prerequisites.
  - Transfer risk: The study site is a San Fernando, La Union LGU office with livestock/public-health functions; those functions and local-government governance must not be imported into PetCare's single canine/feline clinic profile.

### Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote ≤60w + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Company Profile-Operational-Profile | Veterinary office lacked a digital platform and relied on traditional manual processes, limiting data collection, storage, and analysis. | City Veterinarian Office, San Fernando, La Union; n=[NOT STATED] | “The city's veterinary office lacks any existing digital platform, continuing to rely entirely on traditional manual processes that limit efficient data collection, storage, and analysis capabilities essential for informed decision-making and improved service delivery.” (Malicdem & Lamadrid 2025, Introduction, p. 141, para. 3) | [NOT STATED] | [CORROBORATION] CarePaws will document manual clinical-record data flows before implementing digital records [Feature 2] |
| 2 | Company Profile-Technology-Baseline | Flutter/Dart enabled a single-codebase Android application implementation for a resource-constrained LGU platform. | Philippine LGU setting; n=[NOT STATED] | “Flutter served as the primary development framework for mobile application development, selected for its ability to create high performance, visually consistent applications across Android platforms using a single codebase.” (Malicdem & Lamadrid 2025, Materials and Methods, p. 142, para. 2) | [NOT STATED] | [CORROBORATION] CarePaws will select a cross-platform technology baseline compatible with clinic and owner devices for digital health records [Feature 2] |
| 3 | Company Profile-Vulnerability-Audit | Absence of dedicated IT staff was identified as an operational risk that could make the application difficult to use. | Acceptability focus group, 9 veterinarians (2 LGU, 7 private); n=9 | “Ni IT kuma ti aghandle daytoy nga application ta suda met ti agmamanage ti systems gamin awan met ti IT mi, marigatan kami agusar” (Malicdem & Lamadrid 2025, Usability and Accessibility, p. 149, para. 2) | n=9 veterinarians; IT-staff baseline [NOT STATED] | [DEPARTURE] CarePaws will assign maintenance ownership and user support procedures to mitigate clinic IT-capacity risk [Feature 2] |
| 4 | Company Profile-Org-Staff-Roles | Role-based access and veterinarian credential verification were built into the platform's user management. | San Fernando, La Union LGU veterinary office; n=30 usability respondents across six stakeholder categories | “Multi-platform accessibility through both web and mobile interfaces eliminates traditional bureaucratic barriers, with sophisticated user management systems incorporating role-based access for administrators, veterinarians, and non-veterinarian clients, PRC license verification for veterinarian registration, and secure authentication processes that maintain professional standards while ensuring data privacy compliance.” (Malicdem & Lamadrid 2025, Results and Discussion, p. 146, para. 2) | n=30 usability respondents; role/access metric [NOT STATED] | [CORROBORATION] CarePaws will define role-based access for veterinarian, clinic staff, and pet-owner workflows while retaining veterinarian authority [Feature 2] |

Excluded: 0 candidates omitted (all selected rows had a mechanism, verbatim quote, and locator).