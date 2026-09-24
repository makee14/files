# 1.8 Definition of Terms — Nablus-Vet-Care-Report
> Source: `Sources/Nablus-Vet-Care-Report.md` | Date: 2026-09-24 | Depth: standard
> Verdict (Task 2): PARTIALLY USABLE
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
- **Fit**: Defines two operationalizable pairs — RBAC portal (concept vs five-role implementation) and AI diagnostic assistance (concept vs assistant behavior) — both glossable for CarePaws access and AI terms.

### Task 2 — Verdict
- **Verdict**: PARTIALLY USABLE (2 term pairs)
- **Bullets**:
  - Why + recency: PASS (January 2026); both terms carry stated functional meaning plus implemented behavior.
  - Slots populated → Features: [Term-Conceptual-Definition] + [Term-Operational-Definition] for "role-based access" and "AI-assisted diagnosis" → Features 2, 7.
  - Missing: the other 8 locked terms (all [NOT STATED]).
  - Panel use: anchors "RBAC" to five named portals and "AI" to assistive support that does not replace judgment.
  - Caveat: graduation-project build with synthetic data; transfer the definition structure, not the evidence weight.

### Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Definition of Terms-Term-Conceptual-Definition | Role-based access control: multi-tier architecture limiting each role to its appropriate functions | Five-role design, Nablus clinics | "The system implements a multi-tier architecture with role-based access control, supporting five distinct user roles: Administrators, Veterinarians, Receptionists, Pet Owners, and Accountants" (Yaeesh & Salman 2026, System Overview, para. 1) | 5 roles / [NOT STATED: permission counts] | [CORROBORATION] CarePaws will define RBAC conceptually as multi-tier access limiting each role to its functions [Feature 2] |
| 2 | Definition of Terms-Term-Operational-Definition | Role-based access control: in CarePaws, two-step login redirecting each user to its role portal | Email/password plus JWT refresh design | "users first authenticate with email and password credentials, then are automatically redirected to their role-specific portal endpoint" (Yaeesh & Salman 2026, Authentication, para. 1) | [NOT STATED: login metrics] | [CORROBORATION] CarePaws will define RBAC operationally as credential login with automatic role-portal redirect [Feature 2] |
| 3 | Definition of Terms-Term-Conceptual-Definition | AI-assisted diagnosis: decision support aiding evidence-based care without replacing judgment | AI-enhanced ecosystem, synthetic demo data | "The system provides AI-assisted decision support but does not replace professional veterinary judgment, conduct physical diagnoses, or manage in-clinic medical equipment integration" (Yaeesh & Salman 2026, Scope and Limitations, para. 2) | 100% synthetic data / [NOT STATED: accuracy metrics] | [CORROBORATION] CarePaws will define AI assistance conceptually as decision support that never replaces vet judgment [Feature 7] |
| 4 | Definition of Terms-Term-Operational-Definition | AI-assisted diagnosis: in CarePaws, assistants giving diagnosis support plus symptom analysis to vets | Qwen-powered assistants, professional and owner versions | "Provides professional medical consultation including diagnosis support, treatment recommendations, and detailed symptom analysis for veterinary professionals" (Yaeesh & Salman 2026, AI Features, para. 2) | [NOT STATED: consultation counts] | [DEPARTURE] CarePaws will define AI assistance operationally as explainer guidance only, narrowing this diagnostic wording to non-diagnostic triage [Feature 7] |
Excluded: [1] candidate omitted (Stripe payment processing — feature description, not a locked term).
