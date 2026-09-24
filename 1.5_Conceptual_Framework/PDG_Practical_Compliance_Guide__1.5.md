# 1.5 Conceptual Framework — PDG_Practical_Compliance_Guide
> Source: `Sources/PDG_Practical_Compliance_Guide.docx` | Date: 2026-09-25 | Depth: standard
> Verdict (Task 2): HIGHLY USABLE
---

### Task 1 — Bibliographic Classification
- **Title**: Practical Compliance Guide: Implementing Data Privacy and Cybersecurity Measures in Philippine Organizations
- **Authors**: Philippine Data Guardians (PDG)
- **Year**: [NOT FOUND]
- **Recency**: PASS (the guide records 2024 enforcement actions; exact publication year is [NOT STATED])
- **Outlet**: Philippine Data Guardians
- **DOI/URL**: phdataguardians.org
- **Setting**: Local (Philippines) + proof quote “Data privacy and cybersecurity compliance is no longer optional in the Philippines.”
- **Design**: Review
- **APA7**: Philippine Data Guardians. (n.d.). *Practical compliance guide: Implementing data privacy and cybersecurity measures in Philippine organizations*. https://phdataguardians.org [MISSING: publication date]
- **Fit**: The guide supplies an input data-inventory mechanism, access-control requirements, a predeployment PIA sequence, and a continuous-improvement cycle for the section’s inside-the-arrows logic.

### Task 2 — Verdict
- **Verdict**: HIGHLY USABLE
- **Why**: The practical guide provides at least four concrete mechanisms across two allowed slots; its content is demonstrably current through cited 2024 actions, although it is guidance rather than empirical validation.
- **Slots populated**: Input-Clinic-Baselines; Process-RBAC-Engineering; Process-Inside-The-Arrows-Causal-Logic → Features 2 and 4, with the control process applicable across Features 1–7.
- **Missing slots / metrics**: No ISO/IEC 25010 criteria, Agile/DSR sprint cycle, or user-level usability measure; the examples are compliance scenarios rather than evaluated deployments.
- **Panel use**: Deflects claims that privacy controls are merely paperwork or that role gating, predeployment risk review, and continuous monitoring lack an implementable Philippine process.
- **Transfer caveat**: The guide is non-official awareness guidance and disclaims legal advice; the DPO and government-specific registration examples must not be represented as CarePaws requirements without verification.

### Task 3 — Extraction Bank

| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote ≤60w + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Conceptual Framework-Input-Clinic-Baselines | A data-inventory register maps data type, source, storage, retention, access, and third-party sharing, then supplies the baseline for PIA, policy, and breach-response artifacts. | Philippine organizations; practical scenarios; no study sample | “Identify every type of personal data your organization collects, from whom it is collected, where it is stored, how long it is kept, who can access it, and whether it is shared with third parties.” (Philippine Data Guardians, Step 01, para. 1) | Review annually and when a new system, platform, or processing activity is introduced / [NOT STATED: clinic sample] | [DEPARTURE] CarePaws will maintain a clinic data inventory covering records, owners, access, retention, and disclosures before feature deployment [Feature 2] |
| 2 | Conceptual Framework-Process-RBAC-Engineering | Access-control lists, minimum-access role rules, MFA, credential policy, and audit logging form an operational access-control layer. | Philippine government-agency checklist plus general organizational guidance; no deployment evaluation | “Role-based access controls are implemented — minimum access principle enforced” (Philippine Data Guardians, §5.2 Government Agency Compliance Checklist, item 11) | MFA on all government portals and email systems / [NOT STATED: clinic effect size] | [STATUTORY/PROVINCIAL] CarePaws will enforce minimum-access roles, MFA, credential controls, and audit logging for protected clinic data [Feature 2] |
| 3 | Conceptual Framework-Process-Inside-The-Arrows-Causal-Logic | A predeployment PIA converts mapped data flows into assessed privacy risks, mitigations, approvals, and implemented controls before go-live. | New or changed systems involving personal data; Philippine organizations; no study sample | “PIA process: (1) Describe the data flow; (2) Identify privacy risks; (3) Assess likelihood and severity of each risk; (4) Define mitigation measures; (5) Document findings and approvals; (6) Implement mitigations before going live.” (Philippine Data Guardians, Step 06, item 3) | [NOT STATED: PIA effect size] | [DEPARTURE] CarePaws will gate each feature deployment on a documented PIA that maps data flow, assesses risk, and verifies mitigations [Feature 2] |
| 4 | Conceptual Framework-Process-Inside-The-Arrows-Causal-Logic | A Plan-Do-Check-Act loop turns compliance gaps into implemented measures, audit evidence, policy revisions, and training changes. | Philippine organizations; continuous-improvement guidance; no study sample | “Adopt a Plan-Do-Check-Act cycle: 1. Plan assess current compliance status against NPC requirements and identify gaps 1. Do implement the required measures, train staff, and document everything 2. Check conduct internal audits, review breach logs, and assess staff training effectiveness 3. Act address gaps identified in the audit, update policies, and improve training content” (Philippine Data Guardians, §8.3, para. 1) | Monthly DPO review; quarterly training; bi-annual PIA review; annual audit | [DEPARTURE] CarePaws will audit privacy controls, address identified gaps, and revise policies and training through a documented continuous-improvement loop [Feature 4] |

Excluded: 2 candidates omitted (generic DPO duties without an inside-arrow mechanism; advisory legal context outside the six section slots).