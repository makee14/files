# 2.3 Requirements Analysis — 15_beyer.k-chomiak-orsa.i-pietrzykowski.z
> Source: `Sources/15_beyer.k-chomiak-orsa.i-pietrzykowski.z.md` | Date: 2026-09-24 | Depth: standard
> Verdict (Task 2): PARTIALLY USABLE
---
### Task 1 — Bibliographic Classification
- **Title**: Digital Transformation and Business Process Improvement in Veterinary Clinics
- **Authors**: Karolina Beyer, Iwona Chomiak-Orsa, Zbigniew Pietrzykowski, Dominik Rozkrut
- **Year**: 2025
- **Recency**: PASS (2016–2026)
- **Outlet**: 28th ECAI (2025), Intelligent Management Workshop
- **DOI/URL**: 10.18276/978-83-8419-028-9-15
- **Setting**: Foreign + "analysis of three veterinary clinics in Szczecin"
- **Design**: Qualitative Case (102 owner IDIs + 3-clinic case; elicited needs only; no FR table, no thresholds)
- **APA7**: Beyer, K., Chomiak-Orsa, I., Pietrzykowski, Z., & Rozkrut, D. (2025). Digital transformation and business process improvement in veterinary clinics. In *Proceedings of the 28th European Conference on Artificial Intelligence, Intelligent Management Workshop*. https://doi.org/10.18276/978-83-8419-028-9-15
- **Fit**: No enumerated FRs or quantified NFRs, but elicited owner demands (online booking, reminders, record access) that seed functional requirements.
### Task 2 — Verdict
- **Verdict**: PARTIALLY USABLE (2 mechanisms, 1 slot)
- **Bullets**:
  - Why + recency: PASS (2025); counted demand percentages for booking/reminder/record functions, but no thresholds.
  - Slots populated → Features: [Functional-Requirement-FR] → Features 1, 2, 4.
  - Missing: all four ISO slots (no latency/bcrypt/TLS/availability/SUS); unquantified adjectives excluded.
  - Panel use: deflects "FRs have no owner demand" — 102 counted elicitations with percentages.
  - Caveat: transfer demand seeds only; thresholds from the technical plan.
### Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Requirements Analysis-Functional-Requirement-FR | Online appointment-arrangement demand with current-coverage percentage | n=102, Szczecin | "Only 12% of respondents reported that it was possible to arrange an appointment online" (Beyer et al. 2025, Results, para. 1) | 12%; n=102 / [NOT STATED: latency] | [CORROBORATION] CarePaws will convert this unmet demand into its online-booking FR [Feature 1] |
| 2 | Requirements Analysis-Functional-Requirement-FR | Reminder-plus-record-access demand pairing (vaccination reminders, record availability) | n=102 | "to arrange appointments online, receive reminders for vaccinations or regular check-ups, and access telemedicine consultations" (Beyer et al. 2025, Results, para. 1) | [NOT STATED: n for sub-item, metrics] | [CORROBORATION] CarePaws will convert this demand pairing into its reminder and records FRs [Features 2, 4] |
Excluded: [2] candidates omitted (AI-diagnostic support — quarantined scope; telemedicine — out-of-scope modality).