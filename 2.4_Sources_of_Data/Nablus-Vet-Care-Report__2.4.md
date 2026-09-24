# 2.4 Sources of Data — Nablus-Vet-Care-Report
> Source: `Sources/Nablus-Vet-Care-Report.md` | Date: 2026-09-24 | Depth: standard
> Verdict (Task 2): PARTIALLY USABLE
---
### Task 1 — Bibliographic Classification
- **Title**: Nablus Vet Care: A Unified Solution for Veterinary Operations, Client Services, and Business Management
- **Authors**: Baker Razi Wael Yaeesh, Yousef Faed Mahmoud Salman (supervised by Hanal Abuzant)
- **Year**: 2026
- **Recency**: PASS (2016–2026)
- **Outlet**: An-Najah National University, Faculty of Engineering, Dept. of Computer Engineering (graduation project)
- **DOI/URL**: [NOT FOUND]
- **Setting**: Foreign + "regions like Nablus, where clinics face additional challenges in accessing specialized expertise"
- **Design**: DSR Artifact (five-role portal architecture; zero human subjects; 100% synthetic Faker data)
- **APA7**: Yaeesh, B. R. W., & Salman, Y. F. M. (2026). *Nablus Vet Care: A unified solution for veterinary operations, client services, and business management* (Unpublished bachelor's project, An-Najah National University). [MISSING: pages]
- **Fit**: Five-role architecture mapping cleanly to CarePaws strata, but zero respondents — role-design precedent with an explicit evaluation gap.
### Task 2 — Verdict
- **Verdict**: PARTIALLY USABLE (2 mechanisms, 2 slots)
- **Bullets**:
  - Why + recency: PASS (Jan 2026); Admin/Vet/Receptionist/Owner/Accountant portal split, but n=0 human subjects.
  - Slots populated → Features: [Stratum-Veterinarians] → Feature 2; [Stratum-Clinic-Staff] → Features 1, 6.
  - Missing: [Stratum-Pet-Owners] as counted respondents ([NOT STATED] as sample), [Stratum-IT-Experts-ISO25010], [Inclusion-Criteria], [Exclusion-Criteria].
  - Panel use: deflects "roles unarchitected" — five-portal RBAC split with workflow-mapped duties.
  - Caveat: transfer role architecture only; all evaluation counts from the methods plan.
### Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Sources of Data-Stratum-Veterinarians | Veterinarian portal role with consultation and record-update duties | Nablus build, n=0 subjects | "Veterinarians manage consultations, access appointment schedules, and update medical records" (Yaeesh & Salman 2026, Results, para. 1) | n=0 / [NOT STATED: respondents] | [CORROBORATION] CarePaws will define its veterinarian stratum with the same duty-mapped explicitness [Feature 2] |
| 2 | Sources of Data-Stratum-Clinic-Staff | Receptionist/accountant portal roles with scheduling and financial duties | Nablus build, n=0 subjects | "The architecture supports five distinct user roles—Admin, Veterinarian, Receptionist, Pet Owner, and Accountant—each with tailored interfaces" (Yaeesh & Salman 2026, Abstract, para. 3) | 5 roles; n=0 subjects | [CORROBORATION] CarePaws will define its staff strata with the same portal-mapped duties [Features 1, 6] |
Excluded: [1] candidate omitted (synthetic-data notice — limitation, no stratum).