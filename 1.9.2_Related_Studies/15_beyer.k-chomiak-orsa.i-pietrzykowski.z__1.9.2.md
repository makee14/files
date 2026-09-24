# 1.9.2 Related Studies — 15_beyer.k-chomiak-orsa.i-pietrzykowski.z
> Source: `Sources/15_beyer.k-chomiak-orsa.i-pietrzykowski.z.md` | Date: 2026-09-24 | Depth: standard
> Verdict (Task 2): PARTIALLY USABLE
---
### Task 1 — Bibliographic Classification
- **Title**: Digital Transformation and Business Process Improvement in Veterinary Clinics
- **Authors**: Karolina Beyer, Iwona Chomiak-Orsa, Zbigniew Pietrzykowski, Dominik Rozkrut
- **Year**: 2025
- **Recency**: PASS (2016–2026)
- **Outlet**: 28th European Conference on Artificial Intelligence (ECAI 2025), Intelligent Management Workshop
- **DOI/URL**: 10.18276/978-83-8419-028-9-15
- **Setting**: Foreign + "analysis of three veterinary clinics in Szczecin"
- **Design**: Qualitative Case (102 pet-owner IDIs + 3-clinic case study, Oct 2022–May 2023)
- **APA7**: Beyer, K., Chomiak-Orsa, I., Pietrzykowski, Z., & Rozkrut, D. (2025). Digital transformation and business process improvement in veterinary clinics. In *Proceedings of the 28th European Conference on Artificial Intelligence, Intelligent Management Workshop*. https://doi.org/10.18276/978-83-8419-028-9-15
- **Fit**: No counted build metrics, but quantified scheduling failures and named platforms (EHR, cloud, reminders) usable as 1.9.2 contrast.
### Task 2 — Verdict
- **Verdict**: PARTIALLY USABLE (2 mechanisms, 2 slots)
- **Bullets**:
  - Why + recency: PASS (2025); n=102 IDIs with percentages but no built stack, no topology, no ISO means.
  - Slots populated → Features: [Quantitative-Metric-Outcomes] → Feature 1; [Empirical-System-Architecture] → Features 2, 4.
  - Missing: [Hardware-Offline-Fallbacks], [Connectivity-Assumptions], [Acknowledged-Architectural-Flaws]; no SUS/latency.
  - Panel use: deflects "scheduling is fine as-is" — 30% queue waits despite appointments.
  - Caveat: Polish private clinics; AI-diagnostic content quarantined (CarePaws AI is non-diagnostic explainer only).
### Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Related Studies-Quantitative-Metric-Outcomes | Appointment-queue waits persisting despite booked slots | n=102 owners, Szczecin | "30% of respondents mentioned that despite having an appointment, they still had to wait in line" (Beyer et al. 2025, Results, para. 1) | 30%; n=102 / [NOT STATED: wait minutes] | [CORROBORATION] CarePaws will attack this same queue failure with slot control plus reminders [Feature 1] |
| 2 | Related Studies-Empirical-System-Architecture | Cloud EHR plus automated reminder platforms named as fielded tooling | 3-clinic case study | "These tools offer functionalities including automated appointment reminders, integration with animal ID databases, and cloud-based storage that enables remote access to records" (Beyer et al. 2025, Literature, para. 1) | [NOT STATED: n, metrics, versions] | [CORROBORATION] CarePaws will field the same reminders-plus-cloud-records pairing [Features 2, 4] |
Excluded: [2] candidates omitted (AI-diagnostic imaging — quarantined scope; telemedicine proposal — postulate without build).