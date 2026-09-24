# 1.3 Company Profile — 15_beyer.k-chomiak-orsa.i-pietrzykowski.z
> Source: `Sources/15_beyer.k-chomiak-orsa.i-pietrzykowski.z.md` | Date: 2026-09-24 | Depth: standard
> Verdict (Task 2): PARTIALLY USABLE
---
### Task 1 — Bibliographic Classification
- **Title**: Digital Transformation and Business Process Improvement in Veterinary Clinics
- **Authors**: Karolina Beyer, Iwona Chomiak-Orsa, Zbigniew Pietrzykowski, Dominik Rozkrut
- **Year**: 2025
- **Recency**: PASS (2016–2026)
- **Outlet**: 28th European Conference on Artificial Intelligence (ECAI 2025), Intelligent Management Workshop [MISSING: publisher, pages]
- **DOI/URL**: DOI 10.18276/978-83-8419-028-9-15
- **Setting**: Foreign (Poland) + proof: "a study conducted from December 2024 to May 2025 on a sample of 100 clients and 60 employees of veterinary clinics in Poland"
- **Design**: Mixed-Methods survey + interviews (60 clinic employees + 100 clients)
- **APA7**: Beyer, K., Chomiak-Orsa, I., Pietrzykowski, Z., & Rozkrut, D. (2025). Digital transformation and business process improvement in veterinary clinics. In *Proceedings of the 28th European Conference on Artificial Intelligence (ECAI 2025), Intelligent Management Workshop*. https://doi.org/10.18276/978-83-8419-028-9-15 [MISSING: editors, publisher, page range]
- **Fit**: Multi-site barrier/skill profile with no named company: quantifies paper persistence, legacy drag, and staff skill gaps that PetCare's own vulnerability audit can mirror as a pattern, not as facts.

### Task 2 — Verdict
- **Verdict**: PARTIALLY USABLE (2 mechanisms, 2 slots)
- **Bullets (3–5)**:
  - Why this verdict + recency status: PASS (2025); n=160 with two quoted audit-pattern mechanisms, but zero PetCare-specific facts.
  - Slots populated → Features 1–7 mapping: [Technology-Baseline] → Feature 2; [Vulnerability-Audit] → Features 1, 2.
  - Missing slots / metrics this source cannot cover: [Operational-Profile] (no site) and [Org-Staff-Roles] (no headcount/roster) absent; PetCare's own audit must come from fieldwork.
  - Panel use (what attack this citation deflects): deflects "paper is marginal" — 74% paper use plus 60% legacy drag across 160 respondents shows paper is the norm to audit against.
  - Transfer risk / caveat: Polish multi-vet pattern only; do not present 74%/60% as PetCare's own figures.

### Task 3 — Extraction Bank (1–4 rows max, min 1. Never pad.)
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote ≤60w + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Company Profile-Technology-Baseline | Paper records and vaccination books as the dominant documentation baseline with rare full electronics | n=100 clients + 60 staff, Polish clinics | "Historical data documents (e.g., paper-based medical records, vaccination books) were used by 74% of the respondents" (Beyer et al. 2025, §3.1, para. 2) | 74% paper / [NOT STATED: PetCare inventory] | [DEPARTURE] CarePaws will audit PetCare's own paper tools against this 74%-paper norm, then digitize histories and vaccination books [Features 2, 3] |
| 2 | Company Profile-Vulnerability-Audit | Legacy-system plus missing-integration plus skill-gap vulnerability pattern blocking improvement | Same sample, legacy baseline | "Legacy systems were identified as a challenge in as many as 60% of responses. The lack of integrated IT systems (33%) and paper-based medical records (28%) indicate a need for digitization" (Beyer et al. 2025, §3.2, para. 4) | 60% / 33% / 28%; 57% lacking AI skills / [NOT STATED: PetCare audit] | [DEPARTURE] CarePaws will run PetCare's own audit on the same three axes — fragmentation, paper dependence, staff readiness — before build [Features 1, 2] |
Excluded: [2] candidates omitted (no named site — cannot populate Operational-Profile; no roster — cannot populate Org-Staff-Roles).