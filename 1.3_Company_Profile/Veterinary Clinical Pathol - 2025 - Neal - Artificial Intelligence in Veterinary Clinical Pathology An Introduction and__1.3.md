# 1.3 Company Profile — Veterinary Clinical Pathol - 2025 - Neal - Artificial Intelligence in Veterinary Clinical Pathology An Introduction and
> Source: `Sources/Veterinary Clinical Pathol - 2025 - Neal - Artificial Intelligence in Veterinary Clinical Pathology An Introduction and.docx` | Date: 2026-09-25 | Depth: standard
> Verdict (Task 2): PARTIALLY USABLE
---
### Task 1 — Bibliographic Classification
- **Title**: Artificial Intelligence in Veterinary Clinical Pathology—An Introduction and Review
- **Authors**: Samuel V. Neal, Daniel G. Rudmann, Kara N. Corps
- **Year**: 2025
- **Recency**: PASS (2016–2026)
- **Outlet**: Veterinary Clinical Pathology, 54(Suppl. 2), S13–S29
- **DOI/URL**: https://doi.org/10.1111/vcp.70012
- **Setting**: Foreign (United States) + proof quote: "Department of Veterinary Biosciences, College of Veterinary Medicine, Ohio State University, Columbus, Ohio, USA"
- **Design**: Review (AI concepts, qualification, validation, and applications)
- **APA7**: Neal, S. V., Rudmann, D. G., & Corps, K. N. (2025). Artificial intelligence in veterinary clinical pathology—An introduction and review. *Veterinary Clinical Pathology, 54*(Suppl. 2), S13–S29. https://doi.org/10.1111/vcp.70012
- **Fit**: A current veterinary review provides limited technology, data-quality, and professional-oversight mechanisms for 1.3, but it is not a clinic profile and its diagnostic-pathology focus must not be imported into CarePaws.

### Task 2 — Verdict
- **Verdict**: PARTIALLY USABLE (3 transferable mechanisms across 3 slots; review rather than company evidence)
- **Bullets**:
  - Recency status: PASS (2025); the article is a current veterinary review, but it reports no PetCare site, equipment inventory, throughput, or local incident sample.
  - Slots populated → Features 1–7 mapping: [Technology-Baseline] → Feature 2; [Vulnerability-Audit] → Feature 2; [Org-Staff-Roles] → Features 2 and 4.
  - Missing slots / metrics this source cannot cover: [Operational-Profile] is not populated; PetCare hardware, network, appointment volume, patient volume, headcount, paper-friction counts, and recovery metrics are [NOT STATED].
  - Panel use: deflects “digital veterinary records can be assumed complete and self-validating”; the review identifies incomplete records, clerical mistakes, model-data variation, and the need for professional oversight.
  - Transfer risk / caveat: clinical pathology, whole-slide images, diagnostic models, and pathologist-specific AI are outside Features 1–7; retain only record-quality and accountable-review principles for Feature 2.

### Task 3 — Extraction Bank (1–4 rows max, min 1. Never pad.)
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote ≤60w + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Company Profile-Technology-Baseline | Veterinary clinical work is increasingly digitalized through electronic health records and whole-slide-image systems, creating a technology context in which clinical data must be managed | 2025 veterinary clinical-pathology review; academic and diagnostic-laboratory context; n=[NOT STATED] | "as veterinary clinical pathology is digitalized and electronic health records (EHRs) and whole-slide images (WSIs) proliferate" (Neal et al. 2025, Introduction, para. 1) | Digital artifacts: EHRs and WSIs; source sample: [NOT STATED] | [DEPARTURE] CarePaws will document its own digital-record baseline and use only the authorized digital health record, not pathology imaging or diagnostic-AI functions [Feature 2] |
| 2 | Company Profile-Vulnerability-Audit | Incomplete records and clerical mistakes can create missing values even in curated veterinary data, requiring data preparation and quality control | Veterinary clinical-pathology review; multi-source data examples; n=[NOT STATED] | "Missing values are also frequently encountered even in highly curated data sets due to ... incomplete records or clerical mistakes." (Neal et al. 2025, §3.1 Supervised Model Development, para. 1) | Missing-data causes: 3 named classes; missing-value rate: [NOT STATED] | [CORROBORATION] CarePaws will include completeness checks, clerical-error controls, and recoverable entry procedures for digital health records [Feature 2] |
| 3 | Company Profile-Org-Staff-Roles | A clinical professional defines intended use, participates in qualification and validation, and oversees monitoring so AI output is not accepted without expert review | Veterinary diagnostic-laboratory review; pathologist oversight model; n=[NOT STATED] | "The veterinary clinical pathologist must play an active role in defining the intended use, design, and qualification of these methods as well as the plan for monitoring their responsible application in practice." (Neal et al. 2025, Abstract, para. 1) | Oversight activities: 4 stated responsibilities; monitoring threshold: [NOT STATED] | [CORROBORATION] CarePaws will preserve veterinarian authority over clinical records and require accountable review of any educational symptom-explainer output [Features 2, 7] |
Excluded: [9] candidates omitted (pathology-specific AI, whole-slide imaging, cytology classifiers, diagnostic endpoints, multimodal disease prediction, model training pipelines, laboratory instruments, research repositories, and human-pathology applications).
