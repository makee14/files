# 1.6 Objective of the Study — Nablus-Vet-Care-Report
> Source: `Sources/Nablus-Vet-Care-Report.md` | Date: 2026-09-24 | Depth: standard
> Verdict (Task 2): PARTIALLY USABLE
---
### Task 1 — Bibliographic Classification
- **Title**: Nablus Vet Care: A Unified Solution for Veterinary Operations, Client Services, and Business Management
- **Authors**: Baker Razi Wael Yaeesh, Yousef Faed Mahmoud Salman (Supervisor: Dr. Hanal Abuzant)
- **Year**: 2026
- **Recency**: PASS (2016–2026)
- **Outlet**: Department of Computer Engineering, Faculty of Engineering, An-Najah National University (undergraduate graduation project report)
- **DOI/URL**: [NOT FOUND]
- **Setting**: Foreign + "Nablus Vet Care" system title with An-Najah National University authorship (Title page)
- **Design**: DSR Artifact (Agile build with synthetic/Faker demo data; no human-subject evaluation)
- **APA7**: Yaeesh, B. R. W., & Salman, Y. F. M. (2026). *Nablus Vet Care: A unified solution for veterinary operations, client services, and business management* (Unpublished undergraduate project report). Department of Computer Engineering, An-Najah National University. [MISSING: DOI]
- **Fit**: Build-process precedent for two phased verbs (Agile delivery, four-level verification) — but no elicitation, evaluation, or threshold content, and all demo data is synthetic.

### Task 2 — Verdict
- **Verdict**: PARTIALLY USABLE (2 mechanisms, 2 slots)
- **Bullets**:
  - Why + recency: PASS (2026); two-week Agile delivery verb plus unit-to-UAT verification pyramid.
  - Slots populated → Features: [Phase2-Agile-Engineering-Objective] → Features 1–7; [Phase3-Technical-Verification-Objective] → Features 1–7.
  - Missing: [General-Objective-Action], [Phase1-QUAL-Requirements-Objective], [Phase4-QUAN-Evaluation-Objective], [Measurable-Metric-Threshold] (all [NOT STATED]; no human evaluation).
  - Panel use: deflects "Phase 3 is a single test" — a vet system verified across four testing levels with named tools.
  - Caveat: transfer process pattern only; no metric may be cited as an evaluation result (100% synthetic data).

### Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Objective of the Study-Phase2-Agile-Engineering-Objective | Iterative Agile delivery in fixed sprint cycles | Nablus build, synthetic demo data | "We adopted agile development methodology for its flexibility and iterative nature, with two-week sprint cycles and defined deliverables for each iteration" (Yaeesh & Salman 2026, §3.2, para. 1) | Two-week sprints / [NOT STATED: velocity, burndown] | [CORROBORATION] CarePaws will phrase its Phase 2 objective as iterative Agile delivery in fixed sprint cycles [Features 1–7] |
| 2 | Objective of the Study-Phase3-Technical-Verification-Objective | Four-level verification from unit through user acceptance | Nablus build, Jest/Postman/Cypress stack | "The testing strategy embraced a comprehensive approach spanning unit testing, integration testing, system testing, and user acceptance testing" (Yaeesh & Salman 2026, §3.3, para. 1) | [NOT STATED: pass rates — synthetic data only] | [CORROBORATION] CarePaws will phrase its Phase 3 objective as four-level verification from unit through acceptance [Features 1–7] |
Excluded: [1] candidate omitted (synthetic Faker demo metrics — fabricated illustration data, unusable as thresholds).
