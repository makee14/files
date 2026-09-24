# 1.7 Scope and Delimitation — Nablus-Vet-Care-Report
> Source: `Sources/Nablus-Vet-Care-Report.md` | Date: 2026-09-24 | Depth: standard
> Verdict (Task 2): HIGHLY USABLE
---
### Task 1 — Bibliographic Classification
- **Title**: Nablus Vet Care: A Unified Solution for Veterinary Operations, Client Services, and Business Management
- **Authors**: Baker Razi Wael Yaeesh, Yousef Faed Mahmoud Salman (supervised by Dr. Hanal Abuzant)
- **Year**: 2026
- **Recency**: PASS (2016–2026)
- **Outlet**: An-Najah National University, Faculty of Engineering, Department of Computer Engineering (Software Graduation Project)
- **DOI/URL**: [NOT FOUND]
- **Setting**: Foreign + "Veterinary clinics in Nablus and similar regions predominantly rely on manual, paper-based systems"
- **Design**: DSR Artifact (multi-role web/mobile build, 5 portals, React/Node/PostgreSQL)
- **APA7**: Yaeesh, B. R. W., & Salman, Y. F. M. (2026). *Nablus Vet Care: A unified solution for veterinary operations, client services, and business management* (Unpublished bachelor's project). Department of Computer Engineering, An-Najah National University. [MISSING: DOI]
- **Fit**: Only source with a dedicated Scope and Limitations section plus testing/deployment bounds — the structural model for writing CarePaws 1.7.

### Task 2 — Verdict
- **Verdict**: HIGHLY USABLE (4 mechanisms, 4 slots)
- **Bullets**:
  - Why + recency: PASS (January 2026); dedicated §1.5 plus §3.2 constraints state role, medical, testing, and scale bounds.
  - Slots populated → Features: [Population-Boundary] → Features 1, 2, 4; [System-Feature-Boundary] → Features 1–7; [Temporal-Pilot-Boundary] → Features 1, 2; [Deliberate-Exclusion-Justification] → Features 2, 5, 6, 7.
  - Missing: none of the four slots is empty; CarePaws-specific values (site, n, dates) still come from the study plan.
  - Panel use: deflects every scope attack — named exclusions (equipment, inventory, insurance), named test limits, named scale ceiling.
  - Caveat: all demo data synthetic (Faker); transfer the bounding structure, not the data.

### Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Scope and Delimitation-Population-Boundary | Clinic-level scope with five named role portals and single-site deployment ceiling | One-clinic design, Nablus region | "The system implements a multi-tier architecture with role-based access control, supporting five distinct user roles: Administrators, Veterinarians, Receptionists, Pet Owners, and Accountants" (Yaeesh & Salman 2026, System Overview, para. 1) | 5 roles; 1 clinic / [NOT STATED: pilot n] | [CORROBORATION] CarePaws will bound its population the same way: named roles with single-site ceiling [Features 1, 2, 4] |
| 2 | Scope and Delimitation-System-Feature-Boundary | Feature scope bounded at named core plus explicit out-of-scope operations | Full-stack build, paper-baseline clinics | "It does not handle inventory management for medical supplies, pharmacy dispensary operations, or pet boarding/hotel services" (Yaeesh & Salman 2026, Scope and Limitations, para. 3) | [NOT STATED: no feature counts] | [CORROBORATION] CarePaws will bound its feature scope the same way: named inclusions with named exclusions [Features 5, 6] |
| 3 | Scope and Delimitation-Deliberate-Exclusion-Justification | AI and equipment boundaries drawn with vet-judgment retention and no device integration | AI-assisted design, synthetic demo data | "The system provides AI-assisted decision support but does not replace professional veterinary judgment, conduct physical diagnoses, or manage in-clinic medical equipment integration" (Yaeesh & Salman 2026, Scope and Limitations, para. 2) | 100% synthetic data / [NOT STATED: accuracy metrics] | [CORROBORATION] CarePaws will justify its AI exclusion the same way: assistive-only role with retained vet authority [Features 2, 7] |
| 4 | Scope and Delimitation-Temporal-Pilot-Boundary | Testing and scale window bounded to core web/Android with single-branch ceiling | Resource-constrained academic build | "The current implementation is designed as a clinic-level solution and does not natively support multi-branch franchise management" (Yaeesh & Salman 2026, Scope and Limitations, para. 5) | Web + Android tested; iOS/cross-browser limited / [NOT STATED: test dates] | [CORROBORATION] CarePaws will bound its pilot window the same way: named platforms tested with named scale ceiling [Features 1, 2] |
Excluded: [1] candidate omitted (QuickBooks/insurance non-integration — second exclusion example, same slot, weaker quote).
