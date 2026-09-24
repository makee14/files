# 1.9.1 Related Literature — Veterinary Clinical Pathol - 2025 - Neal - Artificial Intelligence in Veterinary Clinical Pathology An Introduction and
> Source: `Sources/Veterinary Clinical Pathol - 2025 - Neal - Artificial Intelligence in Veterinary Clinical Pathology An Introduction and.docx` | Date: 2026-09-25 | Depth: standard
> Verdict (Task 2): HIGHLY USABLE
---
### Task 1 — Bibliographic Classification
- **Title**: Artificial Intelligence in Veterinary Clinical Pathology—An Introduction and Review
- **Authors**: Samuel V. Neal, Daniel G. Rudmann, Kara N. Corps
- **Year**: 2025
- **Recency**: PASS (2016–2026)
- **Outlet**: *Veterinary Clinical Pathology*
- **DOI/URL**: https://doi.org/10.1111/vcp.70012
- **Setting**: Foreign (United States) + proof "Department of Veterinary Biosciences, College of Veterinary Medicine, Ohio State University, Columbus, Ohio, USA"
- **Design**: Review
- **APA7**: Neal, S. V., Rudmann, D. G., & Corps, K. N. (2025). Artificial intelligence in veterinary clinical pathology—An introduction and review. *Veterinary Clinical Pathology*. https://doi.org/10.1111/vcp.70012
- **Fit**: Reviews veterinary AI qualification, human oversight, failure modes, performance monitoring, and quality-system references that bound an assistive clinical AI role.

### Task 2 — Verdict
- **Verdict**: HIGHLY USABLE (4 mechanisms, 3 slots)
- **Bullets**:
  - Why + recency: PASS (2025); the review states qualification and integration requirements and discusses veterinary AI failure modes.
  - Slots populated → Features: [Lit-Veterinary-Informatics-Debate] → Features 2, 7; [Lit-Industry-Standards] → Features 2, 7; [Lit-Thematic-Construct] → Features 2, 7.
  - Missing: [Lit-Regulatory-Statutes-RA10173-RA9268] is not addressed; the source does not establish Philippine law.
  - Panel use: supports a non-diagnostic, veterinarian-supervised AI boundary and requires qualification evidence, audit trails, and post-deployment monitoring.
  - Caveat: the review is focused on clinical pathology; diagnostic AI examples are not interchangeable with CarePaws' locked educational symptom explainer.
  
### Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote ≤60w + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Related Literature-Lit-Veterinary-Informatics-Debate | Veterinary AI requires professional involvement in intended use, design, qualification, and responsible monitoring | Veterinary clinical pathology; review; no intervention sample | "The veterinary clinical pathologist must play an active role in defining the intended use, design, and qualification of these methods as well as the plan for monitoring their responsible application in practice." (Neal et al. 2025, Abstract) | [NOT STATED: review sample] | [CORROBORATION] CarePaws will keep symptom guidance educational and require veterinarian review rather than autonomous diagnosis [Features 2, 7] |
| 2 | Related Literature-Lit-Industry-Standards | AI qualification starts with intended use, acceptance criteria or gold standard, evaluation, implementation, and continuous performance monitoring | AI method qualification workflow; veterinary laboratory context; acceptance criteria example | "Qualification is the process of demonstrating whether a method ... satisfies its intended use." (Neal et al. 2025, Figure 5, AI method qualification workflow) | [NOT STATED: target metric] | [CORROBORATION] CarePaws will define intended-use and acceptance criteria for its explainer before evaluation and continue monitoring after release [Feature 7] |
| 3 | Related Literature-Lit-Thematic-Construct | Model drift and hallucination are distinct AI risks requiring monitoring against changing data and grounded outputs | AI review; model-performance and output-grounding concepts; no veterinary deployment n | "Model drift Degradation of model performance due to changes in the data" (Neal et al. 2025, Table 1) | [NOT STATED: drift rate] | [CONTRADICTION] CarePaws will monitor explainer behavior against changing clinical language and prevent unsupported outputs from being presented as veterinary conclusions [Feature 7] |
| 4 | Related Literature-Lit-Industry-Standards | Software-based veterinary AI can use ISO/IEC 27001 information-security guidance and ISO 13485:2016 quality-management practice as reference controls | Veterinary diagnostic laboratory; review of quality and validation principles; no implementation sample | "The industry benchmarks associated with computer systems validation ... and information security (see ISO 27001) are useful reference guidelines for a software based solution such as an AI-based method." (Neal et al. 2025, §4, para. 3) | ISO 27001; ISO 13485:2016 / [NOT STATED: audit result] | [CORROBORATION] CarePaws will treat information-security and quality-management controls as implementation references while keeping the locked feature scope [Features 2, 7] |
Excluded: [4] candidates omitted (individual diagnostic-model accuracy results, algorithm taxonomy, and pathology-specific applications outside the locked educational explainer boundary).
