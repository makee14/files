# 1.2 Purpose and Description of the Study — Nablus-Vet-Care-Report
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
- **Fit**: Strong unified-system purpose analogue: names the intervention (web + mobile apps on one API/database), enumerates 9 objectives, and gates value across 5 roles (owners, vets, receptionists, pharmacists, admins).

### Task 2 — Verdict
- **Verdict**: HIGHLY USABLE (4 mechanisms, 4 slots)
- **Bullets (3–5)**:
  - Why this verdict + recency status: PASS (2026); 14-clinic fieldwork plus a built web/mobile system with 9 stated objectives and 5 RBAC roles; acceptance/load scores asserted without digits.
  - Slots populated → Features 1–7 mapping: [Primary-Intervention-Mechanism] → Features 1, 2, 4, 5, 6; [Function-Feature-1-7] → Features 1, 2, 3, 4, 5, 6; [Role-Gated-Value-Creation] → Features 1, 2, 4, 5, 6; [Metric-Change-Target] → Features 1, 2, 4, 5, 6.
  - Missing slots / metrics this source cannot cover: [System-Novelty] is thin (unified CRUD + RBAC is incremental); all numeric targets (load times, Lighthouse, questionnaire means) [NOT STATED].
  - Panel use (what attack this citation deflects): deflects "one system cannot cover clinical plus business ops" — this 14-clinic-grounded build unifies appointments, records, inventory, and financial reporting behind one API.
  - Transfer risk / caveat: all demo data declared 100% synthetic so only fieldwork + architecture transfer; pharmacy/in-house-pharmacy scope partially exceeds Features 1–7 and is capped at inventory/billing.

### Task 3 — Extraction Bank (1–4 rows max, min 1. Never pad.)
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote ≤60w + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Purpose and Description-Primary-Intervention-Mechanism | Unified web plus mobile system on a single backend/database replacing fragmented manual workflows | 14 Nablus clinics, paper baseline | "This project introduces Nablus Vet Care System, a centralized web and mobile application designed to unify all aspects of veterinary clinic management—medical, operational, and financial—into one integrated platform" (Yaeesh & Salman 2026, Ch. 1, para. 5) | 14 clinics / [NOT STATED: no pct gain] | [CORROBORATION] CarePaws will state the same unifying purpose: one web system for medical, operational, and billing workflows [Features 1, 2, 5, 6] |
| 2 | Purpose and Description-Function-Feature-1-7 | Objective set covering scheduling, EHR, vaccination tracking, client communication, inventory, and financial reporting | 9 objectives, Waterfall build | "develop an efficient appointment scheduling system that optimizes veterinarian time and reduces client waiting periods through automated reminders and real-time availability" (Yaeesh & Salman 2026, §1.3, Objective 1) | [NOT STATED: no waits, no throughput] | [CORROBORATION] CarePaws will mirror these objectives function-for-function across Features 1–6 with reminders and real-time availability [Features 1, 2, 3, 4, 5, 6] |
| 3 | Purpose and Description-Role-Gated-Value-Creation | Five-role RBAC gating owners, vets, receptionists, pharmacists, and admins behind one API/database | Same build, role-based access control | "Role-based access control (RBAC) governs permissions across five distinct user roles: pet owners, veterinarians, receptionists, pharmacists, and administrators" (Yaeesh & Salman 2026, §3.4.3, para. 6) | 5 roles / [NOT STATED: no permission timings] | [CORROBORATION] CarePaws will gate its three roles the same way: vet/administrator full authority, staff operational access, owner self-service [Features 1, 2, 4, 5, 6] |
| 4 | Purpose and Description-Metric-Change-Target | Multi-dimensional acceptance target (load, performance, accessibility, best practice, SEO, functional questionnaire) | Load/performance tests + Google Forms questionnaire, scores [NOT STATED] | "System validation confirmed the achievement of all nine project objectives, demonstrating improvements in operational efficiency and client satisfaction" (Yaeesh & Salman 2026, Abstract, para. 3) | [NOT STATED: no means, no timings, no n] | [CORROBORATION] CarePaws will set a matching multi-dimensional acceptance target: performance plus functional satisfaction measured post-build [Features 1, 2, 4, 5, 6] |
Excluded: [2] candidates omitted (100% synthetic demo outputs — declared fake, unusable as metrics; in-house pharmacy dispensing — scope beyond Features 1–7, capped at inventory/billing).