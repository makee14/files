# 1.9.2 Related Studies — Nablus-Vet-Care-Report
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
- **Design**: DSR Artifact (multi-tier build + role portals; all demo data synthetic via Faker; no human-subject evaluation)
- **APA7**: Yaeesh, B. R. W., & Salman, Y. F. M. (2026). *Nablus Vet Care: A unified solution for veterinary operations, client services, and business management* (Unpublished bachelor's project, An-Najah National University). [MISSING: pages]
- **Fit**: Richest architecture in the batch: full stack, PostgreSQL schema, JWT/RBAC, Socket.io/Firebase — with offline explicitly deferred.
### Task 2 — Verdict
- **Verdict**: HIGHLY USABLE (4 mechanisms, 4 slots)
- **Bullets**:
  - Why + recency: PASS (Jan 2026); React 18 + Node/Express + PostgreSQL + JWT/RBAC + Socket.io/Firebase with schema-level integrity rules.
  - Slots populated → Features: [Empirical-System-Architecture] → Features 1, 2, 4, 6; [Acknowledged-Architectural-Flaws] → Features 1, 2; [Connectivity-Assumptions] → Feature 4.
  - Missing: [Quantitative-Metric-Outcomes] (no ISO means/SUS/latency — synthetic data only); [Hardware-Offline-Fallbacks] absent by admission.
  - Panel use: deflects "architecture unspecified" — named tiers plus RBAC plus cascading-delete integrity, with limits admitted.
  - Caveat: Stripe payments and diagnostic-AI content quarantined; transfer architecture + RBAC + scheduling patterns only.
### Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Related Studies-Empirical-System-Architecture | React + Node/Express + PostgreSQL multi-tier stack with REST and real-time channels | Nablus build, paper baseline | "Built on a modern technology stack utilizing React 18 with TypeScript for web, React Native for mobile applications, and Node.js with Express for backend services" (Yaeesh & Salman 2026, Abstract, para. 3) | [NOT STATED: n, latency, versions beyond React 18] | [CORROBORATION] CarePaws will document an equivalently explicit tiered stack for Features 1–7 [Features 1, 2, 4, 6] |
| 2 | Related Studies-Empirical-System-Architecture | JWT plus five-role RBAC gating every portal endpoint | Nablus build | "Role-based access control (RBAC) with granular permission management" (Yaeesh & Salman 2026, System Features, para. 2) | 5 roles; [NOT STATED: encryption, test counts] | [CORROBORATION] CarePaws will enforce the same RBAC-gated portal separation for vet, staff, and owner roles [Features 1, 2, 4] |
| 3 | Related Studies-Connectivity-Assumptions | Socket.io plus Firebase push as the real-time notification channel | Nablus build | "real-time features through Socket.io and Firebase push notifications" (Yaeesh & Salman 2026, Abstract, para. 3) | [NOT STATED: delivery rates, latency] | [CORROBORATION] CarePaws will implement push/SMS reminders on the same real-time pattern [Feature 4] |
| 4 | Related Studies-Acknowledged-Architectural-Flaws | Offline capability deferred to future work with testing limited to web and Android | Stated limits | "expanding the mobile application's functionality to include offline capabilities" (Yaeesh & Salman 2026, Future Work, para. 1) | [NOT STATED: failure rates] | [CONTRADICTION] CarePaws will build the offline queue this predecessor deferred for brownout-prone operation [Features 1, 2] |
Excluded: [2] candidates omitted (Stripe payments — quarantined scope; diagnostic-AI support — quarantined non-diagnostic boundary).