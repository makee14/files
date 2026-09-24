# 1.9.1 Related Literature — Nablus-Vet-Care-Report
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
- **Design**: Review + DSR Artifact (Chapter 2 literature review grounding a multi-role build)
- **APA7**: Yaeesh, B. R. W., & Salman, Y. F. M. (2026). *Nablus Vet Care: A unified solution for veterinary operations, client services, and business management* (Unpublished bachelor's project). Department of Computer Engineering, An-Najah National University. [MISSING: DOI]
- **Fit**: Chapter 2 states genuine literature positions (platform spectrum, standards) — enterprise bloat vs SaaS digitization vs academic narrowness, plus IEEE/REST/JWT/HIPAA/GDPR standards — but its own system is a predecessor build excluded from debate rows.

### Task 2 — Verdict
- **Verdict**: PARTIALLY USABLE (2 mechanisms, 2 slots)
- **Bullets**:
  - Why + recency: PASS (January 2026); Chapter 2 debate positions and standards are stated with mechanisms.
  - Slots populated → Features: [Lit-Veterinary-Informatics-Debate] → Features 1, 2, 4; [Lit-Industry-Standards] → Feature 2.
  - Missing: [Lit-Regulatory-Statutes-RA10173-RA9268] ([NOT STATED] — HIPAA/GDPR cited are analogs, not substitutes); [Lit-Thematic-Construct] ([NOT STATED] — no named theory).
  - Panel use: deflects "why another clinic system" — a peer review that positions unified regionally-aware platforms against enterprise, SaaS, and academic alternatives.
  - Caveat: graduation-project review, low evidence weight; never cite its standards as Philippine compliance.

### Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Related Literature-Lit-Veterinary-Informatics-Debate | Platform-spectrum debate: enterprise bloat vs SaaS digitization vs narrow academic builds | Nablus-region review, paper-baseline clinics | "These projects frequently suffer from limited scope, lack of long-term maintenance, or an absence of a cohesive, production-ready architecture" (Yaeesh & Salman 2026, Literature Review, para. 4) | [NOT STATED: comparison counts] | [CORROBORATION] CarePaws will enter the debate the same way: unified clinic platform against fragmented alternatives [Features 1, 2, 4] |
| 2 | Related Literature-Lit-Industry-Standards | Standards stack position: IEEE design, RESTful APIs, JWT auth, HIPAA/GDPR data protection (analogs) | React/Node/PostgreSQL build, synthetic data | "The development followed IEEE software engineering standards for system design and maintained compliance with healthcare data protection protocols" (Yaeesh & Salman 2026, Standards, para. 1) | [NOT STATED: audit results] | [DEPARTURE] CarePaws will cite IEEE/REST/JWT as engineering standards where this source does, substituting RA 10173 for its HIPAA/GDPR analogs [Feature 2] |
Excluded: [2] candidates omitted (Socket.IO real-time claim and Qwen-AI authorship — own-build features for 1.9.2, not literature positions).
