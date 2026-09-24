# 1.5 Conceptual Framework — Nablus-Vet-Care-Report
> Source: `Sources/Nablus-Vet-Care-Report.md` | Date: 2026-09-24 | Depth: standard
> Verdict (Task 2): HIGHLY USABLE
---
### Task 1 — Bibliographic Classification
- **Title**: Nablus Vet Care: A Unified Solution for Veterinary Operations, Client Services, and Business Management
- **Authors**: Baker Razi Wael Yaeesh, Yousef Faed Mahmoud Salman (Supervisor: Dr. Hanal Abuzant)
- **Year**: 2026
- **Recency**: PASS (2016–2026)
- **Outlet**: Department of Computer Engineering, Faculty of Engineering, An-Najah National University (undergraduate graduation project report)
- **DOI/URL**: [NOT FOUND]
- **Setting**: Foreign + "Nablus Vet Care" system title with An-Najah National University authorship (Title page)
- **Design**: DSR Artifact (Agile build with synthetic/Faker demo data; no human-subject evaluation)
- **APA7**: Yaeesh, B. R. W., & Salman, Y. F. M. (2026). *Nablus Vet Care: A unified solution for veterinary operations, client services, and business management* (Unpublished undergraduate project report). Department of Computer Engineering, An-Najah National University. [MISSING: DOI]
- **Fit**: Strongest RBAC-plus-Agile process source: three-role least-privilege matrix, conflict-detecting scheduling, two-week sprints, and a unit-to-UAT testing pyramid — all demo data synthetic.

### Task 2 — Verdict
- **Verdict**: HIGHLY USABLE (4 mechanisms, 2 slots)
- **Bullets**:
  - Why + recency: PASS (2026); least-privilege clinical matrix, no-delete rule, conflict detection, two-week sprints, Jest/Postman/Cypress pyramid.
  - Slots populated → Features: [Process-RBAC-Engineering] → Features 1, 2, 4, 6; [Process-Agile-DSR-Cycles] → Features 1–7.
  - Missing: [Input-ISO25010-Standards], [Input-Clinic-Baselines], [Process-Inside-The-Arrows-Causal-Logic], [Output-Empirical-Usability-Baseline] (no human evaluation; all data 100% synthetic).
  - Panel use: deflects "RBAC is asserted, not shown" — a vet system with view-but-not-modify clinical integrity plus conflict detection.
  - Caveat: transfer architecture only; no metric may be cited as an evaluation result.

### Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Conceptual Framework-Process-RBAC-Engineering | Least-privilege clinical matrix with a no-delete rule | Nablus build, synthetic demo data | "Receptionists can view but not modify medical records, maintaining clinical data integrity while supporting front-desk operations. They cannot delete any medical records" (Yaeesh & Salman 2026, §4.2, para. 3) | [NOT STATED: permission matrix] | [CORROBORATION] CarePaws will enforce view-but-not-modify plus no-delete clinical integrity for reception roles [Feature 2] |
| 2 | Conceptual Framework-Process-RBAC-Engineering | Conflict-detecting appointment scheduling with duration and type controls | Nablus receptionist portal, synthetic data | "Conflict detection and resolution for scheduling optimization" (Yaeesh & Salman 2026, §4.5, Appointment list) | Slots 8:00 AM–6:30 PM; durations 15–120 min / [NOT STATED: conflict rate] | [CORROBORATION] CarePaws will engineer its scheduling lane with conflict detection plus duration controls [Feature 1] |
| 3 | Conceptual Framework-Process-Agile-DSR-Cycles | Two-week sprint cycles with per-iteration deliverables | Nablus build, Agile methodology | "We adopted agile development methodology for its flexibility and iterative nature, with two-week sprint cycles and defined deliverables for each iteration" (Yaeesh & Salman 2026, §3.2, para. 1) | Two-week sprints / [NOT STATED: velocity] | [CORROBORATION] CarePaws will run its process arrow as two-week Agile sprints with defined deliverables [Features 1–7] |
| 4 | Conceptual Framework-Process-Agile-DSR-Cycles | Four-level testing pyramid from unit through user acceptance | Nablus build, Jest/Postman/Cypress stack | "The testing strategy embraced a comprehensive approach spanning unit testing, integration testing, system testing, and user acceptance testing" (Yaeesh & Salman 2026, §3.3, para. 1) | [NOT STATED: pass rates — synthetic data only] | [CORROBORATION] CarePaws will verify each process increment through unit-to-acceptance testing levels [Features 1–7] |
Excluded: [1] candidate omitted (Qwen-AI diagnostics/BI stack — non-diagnostic boundary; Feature 7 explainer only).
