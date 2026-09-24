# 2.5 System Requirements — Nablus-Vet-Care-Report
> Source: `Sources/Nablus-Vet-Care-Report.md` | Date: 2026-09-24 | Depth: standard
> Verdict (Task 2): HIGHLY USABLE
---
### Task 1 — Bibliographic Classification
- **Title**: Nablus Vet Care: A Unified Solution for Veterinary Operations, Client Services, and Business Management
- **Authors**: Baker Razi Wael Yaeesh, Yousef Faed Mahmoud Salman (supervised by Hanal Abuzant)
- **Year**: 2026
- **Recency**: PASS (2016–2026)
- **Outlet**: An-Najah National University, Faculty of Engineering, Department of Computer Engineering (Software Graduation Project)
- **DOI/URL**: [NOT FOUND]
- **Setting**: Foreign + "ensuring cultural and linguistic appropriateness for its target market" in "the Nablus region" with "full multi-language (EN/AR/HE) and RTL support"
- **Design**: DSR Artifact (full-stack React/Node/PostgreSQL build with client-side, server-side, and database architecture)
- **APA7**: Yaeesh, B. R. W., & Salman, Y. F. M. (2026). *Nablus Vet Care: A unified solution for veterinary operations, client services, and business management* (Software Graduation Project, Department of Computer Engineering, An-Najah National University). [MISSING: DOI]
- **Fit**: The richest versionless stack in the inbox — named frontend, backend, database, tooling, security, and schema mechanisms across three slots; only hardware specs and versions are missing.

### Task 2 — Verdict
- **Verdict**: HIGHLY USABLE (4 mechanisms, 3 slots)
- **Bullets**:
  - Why this verdict + recency status: PASS (January 2026); four grounded mechanisms covering both runtime halves, topology, and storage.
  - Slots populated → Features: [Software-Runtime-Engine] → Features 1, 2, 4, 5, 6, 7; [System-Architecture-MultiTier-Topology] → Features 1, 2, 4, 5, 6; [Database-Storage-Spec] → Feature 2.
  - Missing slots / metrics this source cannot cover: [Hardware-Dev-vs-Client-Spec] ([NOT STATED]); all product versions, server sizing, latency ([NOT STATED]).
  - Panel use: deflects "no full-stack precedent" — a five-role vet-clinic build on React, Node/Express, Socket.IO, and PostgreSQL.
  - Caveat: names are versionless and Stripe/WebRTC exceed the CarePaws boundary (non-banking-gateway Features 1–7) — transfer the stack pattern only, never the payment-gateway module.

### Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | System Requirements-Software-Runtime-Engine | React 18 plus TypeScript web front end with React Native mobile and Tailwind styling | Nablus graduation build, n [NOT STATED] | "For frontend development, we utilized React 18 with TypeScript for web interfaces and React Native for mobile applications, with styling implemented through Tailwind CSS" (Yaeesh & Salman 2026, Methodology, Tools, para. 1) | [NOT STATED: versions beyond React 18, OS, hardware, latency] | [CORROBORATION] CarePaws will name its own versioned frontend trio following this web-plus-mobile-plus-styling pattern [Features 1, 2, 4] |
| 2 | System Requirements-Software-Runtime-Engine | Node.js plus Express RESTful API backend with Socket.IO real-time channel and Firebase push notifications | Nablus build, RESTful API conventions | "Backend services were built using Node.js with Express.js to establish a RESTful API architecture managing application data and business logic" (Yaeesh & Salman 2026, Methodology, Tools, para. 1) | [NOT STATED: Node version, server specs, throughput, latency] | [CORROBORATION] CarePaws will specify its own versioned API backend with the same REST-plus-realtime pattern [Features 1, 4] |
| 3 | System Requirements-System-Architecture-MultiTier-Topology | Multi-tier role-gated architecture with five customized portals over one integrated data platform | Nablus build; Administrators, Veterinarians, Receptionists, Pet Owners, Accountants | "The system implements a multi-tier architecture with role-based access control, supporting five distinct user roles: Administrators, Veterinarians, Receptionists, Pet Owners, and Accountants" (Yaeesh & Salman 2026, System Features, Overview, para. 1) | 5 roles / [NOT STATED: tier count, server specs, latency] | [CORROBORATION] CarePaws will structure its own three-role multi-tier system on the same role-gated portal pattern [Features 1, 2, 4] |
| 4 | System Requirements-Database-Storage-Spec | Relational PostgreSQL store with consistent cross-platform schemas, cascading deletes, unique constraints, and generated price columns | Nablus build, web plus mobile clients | "PostgreSQL was employed for relational database design, maintaining consistent data schemas across web and mobile platforms" (Yaeesh & Salman 2026, Methodology, Tools, para. 1) | [NOT STATED: PostgreSQL version, storage size, backup, encryption] | [CORROBORATION] CarePaws will specify its versioned relational schema with the same consistency-plus-integrity logic [Feature 2] |
Excluded: [2] candidates omitted (JWT/OAuth login prose — security content for 2.3, not a spec; Stripe/WebRTC modules — out-of-boundary gateway/voice scope, quarantined under Features 1–7).
