# 1.9.3 Synthesis — Nablus-Vet-Care-Report
> Source: `Sources/Nablus-Vet-Care-Report.md` | Date: 2026-09-24 | Depth: standard
> Verdict (Task 2): PARTIALLY USABLE
---
### Task 1 — Bibliographic Classification
- **Title**: Nablus Vet Care: A Unified Solution for Veterinary Operations, Client Services, and Business Management
- **Authors**: Baker Razi Wael Yaeesh, Yousef Faed Mahmoud Salman (supervised by Hanal Abuzant)
- **Year**: 2026
- **Recency**: PASS (2016–2026)
- **Outlet**: An-Najah National University, Faculty of Engineering, Dept. of Computer Engineering (graduation project)
- **DOI/URL**: [NOT FOUND]
- **Setting**: Foreign + "regions like Nablus, where clinics face additional challenges in accessing specialized expertise"
- **Design**: DSR Artifact (build only; all demo data synthetic via Faker; no human-subject evaluation)
- **APA7**: Yaeesh, B. R. W., & Salman, Y. F. M. (2026). *Nablus Vet Care: A unified solution for veterinary operations, client services, and business management* (Unpublished bachelor's project, An-Najah National University). [MISSING: pages]
- **Fit**: Feature-rich build with zero measured evaluation and deferred offline — feeds empirical, architectural, and geographical gaps.
### Task 2 — Verdict
- **Verdict**: PARTIALLY USABLE (3 mechanisms, 3 slots)
- **Bullets**:
  - Why + recency: PASS (Jan 2026); full stack documented but 100% synthetic data with no respondents.
  - Slots populated → Features: [Empirical-Gap] → Features 1–7; [Architectural-Gap] → Features 1, 2; [Geographical-Gap] → Features 1–7.
  - Missing: [Methodological-Gap] (no research design to critique); [CarePaws-Synthesis-Resolution] (author synthesis).
  - Panel use: deflects "feature list equals evidence" — synthetic-only demo with testing limits admitted.
  - Caveat: Stripe/diagnostic-AI quarantined; transfer gaps only.
### Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Synthesis-Empirical-Gap | Synthetic-only demonstration data with no human-subject evaluation | Faker-generated data | "are entirely synthetic, fictitious, and generated for simulation purposes only (100% Fake/Dummy Data)" (Yaeesh & Salman 2026, Notice, para. 1) | n=0 human subjects / [METRIC UNREPORTED] | [CORROBORATION] CarePaws will close this evidence gap with a counted human-subject ISO evaluation [Features 1–7] |
| 2 | Synthesis-Architectural-Gap | Offline capability explicitly deferred to future work | Stated limits | "expanding the mobile application's functionality to include offline capabilities" (Yaeesh & Salman 2026, Future Work, para. 1) | [METRIC UNREPORTED] | [CORROBORATION] CarePaws will close this resilience gap with offline queue plus local cache in its baseline build [Features 1, 2] |
| 3 | Synthesis-Geographical-Gap | Middle-Eastern regional tailoring distinct from Urdaneta single-site context | Nablus build | "particularly suited for the unique needs of the Middle Eastern region" (Yaeesh & Salman 2026, Abstract, para. 4) | [NOT STATED: n sites] | [CORROBORATION] CarePaws will close this site gap with its Pangasinan single-clinic study [Features 1–7] |
Excluded: [2] candidates omitted (Stripe — quarantined scope; diagnostic-AI — quarantined scope).