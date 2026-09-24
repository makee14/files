# 1.9.1 Related Literature — PDG_Practical_Compliance_Guide
> Source: `Sources/PDG_Practical_Compliance_Guide.docx` | Date: 2026-09-25 | Depth: standard
> Verdict (Task 2): HIGHLY USABLE
---
### Task 1 — Bibliographic Classification
- **Title**: Philippine Data Guardians Practical Compliance Guide: Implementing Data Privacy and Cybersecurity Measures in Philippine Organizations
- **Authors**: Philippine Data Guardians (PDG)
- **Year**: [NOT FOUND]
- **Recency**: PASS (contemporary guidance cites NPC Circulars 2023-06 and 2024-02; publication date [NOT STATED])
- **Outlet**: Philippine Data Guardians
- **DOI/URL**: [NOT FOUND]
- **Setting**: Local (Philippines) + proof "For: Government Agencies | SMEs | Community Organizations"
- **Design**: Review (practical compliance guide)
- **APA7**: Philippine Data Guardians. (n.d.). *Philippine Data Guardians practical compliance guide: Implementing data privacy and cybersecurity measures in Philippine organizations*. Philippine Data Guardians. [MISSING: publication date]
- **Fit**: Converts Philippine privacy and cybersecurity requirements into implementable controls for organizational systems, including data mapping, access control, security layers, breach response, and recurring compliance review.

### Task 2 — Verdict
- **Verdict**: HIGHLY USABLE (3 mechanisms, 2 slots)
- **Bullets**:
  - Why + recency: PASS for contemporary compliance guidance; the text cites NPC Circular 2023-06, NPC Circular 16-03, and NPC Circular 2024-02, but its publication date is [NOT FOUND].
  - Slots populated → Features: [Lit-Industry-Standards] → Features 2, 4, 7; [Lit-Regulatory-Statutes-RA10173-RA9268] → Features 2, 4.
  - Missing: [Lit-Veterinary-Informatics-Debate] and [Lit-Thematic-Construct] are [NOT STATED]; RA 9268 and veterinary-specific literature are not discussed.
  - Panel use: supports the claim that privacy compliance requires operational controls and evidence, not only a written policy.
  - Caveat: this is a secondary practical guide, not a substitute for the official statute or NPC circular text.
  
### Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote ≤60w + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Related Literature-Lit-Industry-Standards | Security controls are organized across physical, organizational, and technical dimensions | Philippine organizations; baseline structure stated in guide; no evaluation sample | "Under NPC Circular 2023-06, organizations must implement security measures across three dimensions: Physical security ... Organizational security ... Technical security" (PDG, §3.4 Data Security Measures, p. 6) | 3 dimensions; [NOT STATED: implementation rate] | [CORROBORATION] CarePaws will specify physical, organizational, and technical safeguards for owner and clinical data [Features 2, 4] |
| 2 | Related Literature-Lit-Regulatory-Statutes-RA10173-RA9268 | Data mapping creates a living inventory of data flows, purposes, retention, access, and third-party sharing | Philippine organizations; data-mapping exercise; no organization sample | "Identify every type of personal data your organization collects, from whom it is collected, where it is stored, how long it is kept, who can access it, and whether it is shared with third parties." (PDG, Step 01 Conduct Data Mapping, p. 15) | Annual update; [NOT STATED: organization count] | [STATUTORY/PROVINCIAL] CarePaws will maintain a data inventory for owner, appointment, clinical, vaccination, inventory, and billing records [Features 1, 2, 3, 5, 6] |
| 3 | Related Literature-Lit-Industry-Standards | Breach preparedness requires a maintained breach log, assigned response roles, and a notification workflow | Philippine organizations; qualifying serious-harm breach; no incident sample | "Maintain a Breach Log All organizations, regardless of size" and "Mandatory Within 72 hours of discovery" (PDG, Core Compliance Requirements — Quick Reference Table, p. 3) | 72 hours; [NOT STATED: breach frequency] | [CORROBORATION] CarePaws will define breach logging, escalation roles, and the 72-hour notification decision path before deployment [Features 2, 4] |
Excluded: [6] candidates omitted (general DPO training, registration mechanics, password examples, common mistakes, vendor templates, and scenario narratives that duplicate the retained mechanisms or lack an independent mechanism).
