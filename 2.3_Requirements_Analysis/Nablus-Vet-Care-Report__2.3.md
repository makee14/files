# 2.3 Requirements Analysis — Nablus-Vet-Care-Report
> Source: `Sources/Nablus-Vet-Care-Report.md` | Date: 2026-09-24 | Depth: standard
> Verdict (Task 2): HIGHLY USABLE
---
### Task 1 — Bibliographic Classification
- **Title**: Nablus Vet Care: A Unified Solution for Veterinary Operations, Client Services, and Business Management
- **Authors**: Baker Razi Wael Yaeesh, Yousef Faed Mahmoud Salman (supervised by Hanal Abuzant)
- **Year**: 2026
- **Recency**: PASS (2016–2026)
- **Outlet**: An-Najah National University, Faculty of Engineering, Dept. of Computer Engineering (graduation project)
- **DOI/URL**: [NOT FOUND]
- **Setting**: Foreign + "regions like Nablus, where clinics face additional challenges in accessing specialized expertise"
- **Design**: DSR Artifact (five role portals; JWT/RBAC; scheduling/records/billing/notification modules; no quantified NFR thresholds)
- **APA7**: Yaeesh, B. R. W., & Salman, Y. F. M. (2026). *Nablus Vet Care: A unified solution for veterinary operations, client services, and business management* (Unpublished bachelor's project, An-Najah National University). [MISSING: pages]
- **Fit**: Richest FR evidence in the batch: enumerated scheduling, records, billing, and notification functions plus JWT/RBAC and multi-layer validation.
### Task 2 — Verdict
- **Verdict**: HIGHLY USABLE (4 mechanisms, 3 slots)
- **Bullets**:
  - Why + recency: PASS (Jan 2026); field-level scheduling/records/billing functions with named security mechanisms.
  - Slots populated → Features: [Functional-Requirement-FR] → Features 1, 2, 6; [ISO25010-Security-Bcrypt-TLS] → Features 1, 2; [ISO25010-Reliability-Availability] → Feature 2.
  - Missing: [ISO25010-Performance-Efficiency] (no ms), [ISO25010-Usability] (no SUS/means); bcrypt≥12/TLS 1.3/99.5% absent.
  - Panel use: deflects "requirements unfielded" — appointment-to-invoice workflow with slot bounds and integrity rules.
  - Caveat: Stripe/diagnostic-AI quarantined; transfer functional + security patterns only.
### Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Requirements Analysis-Functional-Requirement-FR | Slot-bounded appointment scheduling function with conflict detection | Nablus build | "Time slot management from 8:00 AM to 6:30 PM" (Yaeesh & Salman 2026, System Features, para. 1) | 8:00–18:30; 15–120 min durations / [NOT STATED: n] | [CORROBORATION] CarePaws will bound its scheduling FR with equivalent operating-hour and duration rules [Feature 1] |
| 2 | Requirements Analysis-Functional-Requirement-FR | Invoice-generation function with auto-calculated line totals and status tracking | Nablus build | "The invoice contains one or more invoice_items (e.g., 'Consultation Fee', 'Medication'), which automatically calculate the total_price based on quantity and unit price" (Yaeesh & Salman 2026, Methods, para. 1) | [NOT STATED: n, ms] | [CORROBORATION] CarePaws will specify its manual-recorded billing FR with the same auto-calculation rule [Feature 6] |
| 3 | Requirements Analysis-ISO25010-Security-Bcrypt-TLS | JWT session management with RBAC route guards and multi-layer financial validation | Nablus build | "JSON Web Token (JWT) management with automatic token refresh mechanisms" (Yaeesh & Salman 2026, System Features, para. 1) | [NOT STATED: bcrypt rounds, TLS version] | [CORROBORATION] CarePaws will implement its session-plus-RBAC security NFR on the same token pattern [Features 1, 2] |
| 4 | Requirements Analysis-ISO25010-Reliability-Availability | Cascading-delete plus unique-constraint integrity rules preventing orphaned records | Schema design | "deleting a pet will automatically delete all its medical_records, vaccinations, and appointments, preventing orphaned records" (Yaeesh & Salman 2026, Methods, para. 1) | [NOT STATED: availability %, n] | [CORROBORATION] CarePaws will enforce the same cascading-integrity rule for its records reliability NFR [Feature 2] |
Excluded: [2] candidates omitted (Stripe payments — quarantined scope; diagnostic-AI — quarantined scope).