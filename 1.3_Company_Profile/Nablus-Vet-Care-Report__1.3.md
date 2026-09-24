# 1.3 Company Profile — Nablus-Vet-Care-Report
> Source: `Sources/Nablus-Vet-Care-Report.md` | Date: 2026-09-24 | Depth: standard
> Verdict (Task 2): HIGHLY USABLE
---
### Task 1 — Bibliographic Classification
- **Title**: Nablus Vet Care: A Unified Solution for Veterinary Operations, Client Services, and Business Management
- **Authors**: Baker Razi Wael Yaeesh, Yousef Faed Mahmoud Salman (supervised by Dr. Hanal Abuzant)
- **Year**: 2026
- **Recency**: PASS (2016–2026)
- **Outlet**: Software Graduation Project, Department of Computer Engineering, An-Najah National University [MISSING: DOI/URL]
- **DOI/URL**: [MISSING: DOI/URL]
- **Setting**: Foreign (Palestine) + proof: "During the field visits, the authors surveyed 14 clinics" in "Nablus, Palestine"
- **Design**: DSR Artifact (Waterfall; 14-clinic fieldwork + interviews; React/React Native + Node/Express + PostgreSQL; load/performance tests with scores [NOT STATED])
- **APA7**: Yaeesh, B. R. W., & Salman, Y. F. M. (2026). *Nablus Vet Care: A unified solution for veterinary operations, client services, and business management* (Unpublished bachelor's graduation project, supervised by H. Abuzant). Department of Computer Engineering, An-Najah National University. [MISSING: DOI/URL]
- **Fit**: Strongest fieldwork profiling pattern for 1.3: 14-clinic operational model (single-vet owner-clinician-manager), register-plus-leadership baseline, and a 5-role RBAC roster — the exact audit shape PetCare needs, as analogy only.

### Task 2 — Verdict
- **Verdict**: HIGHLY USABLE (3 mechanisms, 3 slots)
- **Bullets (3–5)**:
  - Why this verdict + recency status: PASS (2026); 14-clinic fieldwork with three quoted profiling mechanisms across operational, baseline, and role slots.
  - Slots populated → Features 1–7 mapping: [Operational-Profile] → Features 1, 2, 5, 6; [Technology-Baseline] → Feature 2; [Org-Staff-Roles] → Features 1, 2, 4, 5, 6.
  - Missing slots / metrics this source cannot cover: [Vulnerability-Audit] as a named PetCare audit is absent; PetCare's own throughput, headcount, and hardware are all [NOT STATED] and must come from fieldwork.
  - Panel use (what attack this citation deflects): deflects "small clinics need no profiling" — 14 clinics show the one-vet-does-everything model with memory routines is precisely what must be profiled before digitizing.
  - Transfer risk / caveat: analogue only; demo data declared 100% synthetic so only fieldwork observations transfer; pharmacy role capped at inventory/billing scope.

### Task 3 — Extraction Bank (1–4 rows max, min 1. Never pad.)
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote ≤60w + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Company Profile-Operational-Profile | Single-veterinarian owner-clinician-manager model across the overwhelming majority of surveyed clinics | 14 Nablus clinics, single-vet baseline | "the overwhelming majority of clinics operate under a single-veterinarian model, where one veterinarian serves as the owner, primary clinician, and business manager" (Yaeesh & Salman 2026, Ch. 1, para. 3) | 14 clinics / [NOT STATED: PetCare visits, revenue] | [DEPARTURE] CarePaws will profile PetCare against this model: who owns, who clinics, who manages, and where overload concentrates [Features 1, 2, 5, 6] |
| 2 | Company Profile-Technology-Baseline | Ministry registry plus clinic-leader verification as the pre-digital record baseline, displaced by PostgreSQL ACID storage | Same 14 clinics, registry/manual baseline | "We selected PostgreSQL as our database management system for its reliability, advanced features, and robust support for complex queries" (Yaeesh & Salman 2026, §3.4.3, para. 2) | [NOT STATED: no PetCare hardware, no data volumes] | [DEPARTURE] CarePaws will inventory PetCare's own registers, notebooks, and hardware the same way before specifying ACID storage [Feature 2] |
| 3 | Company Profile-Org-Staff-Roles | Five-role RBAC roster covering owners, veterinarians, receptionists, pharmacists, and administrators | Same build, role-based access control | "Role-based access control (RBAC) governs permissions across five distinct user roles: pet owners, veterinarians, receptionists, pharmacists, and administrators" (Yaeesh & Salman 2026, §3.4.3, para. 6) | 5 roles / [NOT STATED: PetCare headcount] | [CORROBORATION] CarePaws will roster PetCare the same way, collapsed to three roles: vet/administrator, staff, owner [Features 1, 2, 4, 5, 6] |
Excluded: [2] candidates omitted (100% synthetic demo rows — declared fake, unusable as profile facts; $70k–150k capital figures — investment context, not a 1.3 slot).