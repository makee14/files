# 1.9.3 Synthesis of the State-of-the-Art — C-MALICDEM,+KIMBERLEY+P_Research+Article+Revised+3
> Source: `Sources/C-MALICDEM,+KIMBERLEY+P_Research+Article+Revised+3.md` | Date: 2026-09-25 | Depth: standard
> Verdict (Task 2): HIGHLY USABLE
---

## Task 1 — Bibliographic Classification

- **Title**: SMART Vet: A Knowledge Management Platform Application for Enhancing Local Government Unit Veterinary Services
- **Authors**: Kimberley P. Malicdem and Bernardo D. Lamadrid
- **Year**: 2025
- **Recency**: PASS (2016–2026)
- **Outlet**: DMMMSU Research and Extension Journal, 9(1), 139–156
- **DOI/URL**: [NOT FOUND]
- **Setting**: Local (Philippines) — “The research was conducted at the City Veterinarian Office of San Fernando, La Union, Philippines...” (Malicdem & Lamadrid, 2025, Materials and Methods, para. 1)
- **Design**: DSR Artifact
- **APA7**: Malicdem, K. P., & Lamadrid, B. D. (2025). SMART Vet: A knowledge management platform application for enhancing local government unit veterinary services. *DMMMSU Research and Extension Journal, 9*(1), 139–156.
- **Fit**: The locally built and evaluated veterinary platform exposes four synthesis gaps—sample strata, site transferability, connectivity dependence, and outcome-reporting depth—while its broader LGU scope remains transferable only at the gap-analysis level.

## Task 2 — Verdict

- **Verdict**: HIGHLY USABLE (4 gap mechanisms across 4 slots)
- **Recency and evidential basis**: PASS; this 2025 developmental artifact reports a five-phase Waterfall build, n=30 ISO/IEC 25010 usability responses, and n=9 veterinarian acceptability participants.
- **Slots populated → Features**: Methodological-Gap, Geographical-Gap, Architectural-Gap, and Empirical-Gap → Features 1, 2, 3, 4, and 6.
- **Missing evidence**: No clinic-staff or IT-expert stratum, Urdaneta City validation, offline recovery test, item-level statistics, inferential tests, task timings, uptime, or failure-rate data were reported; CarePaws-Synthesis-Resolution remains author synthesis.
- **Panel use**: This citation deflects the claim that a Philippine platform with a 4.49/5 usability mean and unanimous professional endorsement already proves transferability, implementation readiness, or technical reliability for another clinic.
- **Transfer caveat**: Do not transfer the Waterfall method, livestock/public-health functions, impoundment features, or adoption workflow; use only the four gap mechanisms within CarePaws Features 1–7.

## Task 3 — Extraction Bank

| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote ≤60w + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Synthesis of the State-of-the-Art-Methodological-Gap | Sample-stratum gap: the usability sample enumerated six stakeholder groups but did not report clinic receptionists/staff or IT experts as respondent strata, leaving administrative-workflow and support usability untested. | n=30 usability respondents across six groups; n=9 veterinarians for acceptability; one Philippine LGU office; post-build evaluation. | “For usability assessment, 30 respondents were carefully selected representing six distinct stakeholder categories, with five participants from each group: veterinarians (both LGU and private sector), pet owners, farmers, livestock raisers, meat vendors, and animal transporters.” (Malicdem & Lamadrid, 2025, Materials and Methods, para. 6) | n=30; n=9; 6 usability groups; clinic-staff and IT-expert participation [NOT STATED] | [DEPARTURE] CarePaws will include receptionist/staff and IT-expert strata in usability and acceptance testing [Feature 2] [Feature 4] |
| 2 | Synthesis of the State-of-the-Art-Geographical-Gap | Site-transferability gap: evaluation in one La Union LGU office does not establish transferability to the single-site Urdaneta City companion-animal clinic. | One City Veterinarian Office; San Fernando, La Union; LGU veterinary services; no Urdaneta validation reported. | “The research was conducted at the City Veterinarian Office of San Fernando, La Union, Philippines, following formal ethical approval and administrative clearance from the City Mayor's office.” (Malicdem & Lamadrid, 2025, Materials and Methods, para. 1) | 1 Philippine LGU site; Urdaneta City validation [NOT STATED] | [CORROBORATION] CarePaws will validate appointment, record, vaccination, and portal workflows with PetCare clinic users in Urdaneta City [Feature 1] [Feature 2] [Feature 3] [Feature 4] |
| 3 | Synthesis of the State-of-the-Art-Architectural-Gap | Connectivity-dependency gap: web delivery was coupled to commercial hosting, adequate bandwidth, server maintenance, and IT support, while no offline cache, reconnect synchronization, or recovery path was reported. | Web-and-mobile artifact; Z.com-hosted deployment; resource-constrained Philippine LGU setting; baseline manual processes. | “Web deployment infrastructure was established through Z.com domain registration services and dedicated web hosting subscriptions, ensuring reliable 24/7 accessibility with adequate bandwidth and server maintenance protocols to support concurrent user access typical of municipal government operations.” (Malicdem & Lamadrid, 2025, Materials and Methods, para. 4) | Claimed 24/7 access; offline cache, reconnect synchronization, recovery time, and measured uptime [NOT STATED] | [DEPARTURE] CarePaws will provide a local offline queue and reconnect synchronization for appointment, clinical-record, vaccination, and portal transactions [Feature 1] [Feature 2] [Feature 3] [Feature 4] |
| 4 | Synthesis of the State-of-the-Art-Empirical-Gap | Outcome-reporting gap: aggregate ISO/IEC 25010 means and unanimous endorsement were reported without item-level distributions, inferential tests, task timings, uptime, or failure-rate data. | n=30 post-build questionnaire; n=9 veterinarian focus group; one LGU platform; ISO/IEC 25010 evaluation. | “The comprehensive usability evaluation demonstrated exceptional performance across all assessed quality characteristics, achieving an overall mean rating of 4.49 corresponding to an ‘Excellent’ rating and ‘Very Highly Usable’ interpretation according to established evaluation standards.” (Malicdem & Lamadrid, 2025, Results and Discussion, para. 1) | Overall mean=4.49/5; Performance Efficiency=4.59; Portability=4.67; SD, p values, task time, uptime, and failure rate [NOT STATED] | [CONTRADICTION] CarePaws will report item-level results, task completion time, latency, availability, and failure counts separately from satisfaction ratings [Feature 1] [Feature 2] [Feature 3] [Feature 4] [Feature 6] |

Excluded: 5 candidates omitted (no target-gap mechanism / outside Features 1–7 / no independent metric).
