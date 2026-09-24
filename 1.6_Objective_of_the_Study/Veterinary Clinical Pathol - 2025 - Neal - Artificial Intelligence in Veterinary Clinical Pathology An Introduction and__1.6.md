# 1.6 Objective of the Study — Veterinary Clinical Pathol - 2025 - Neal - Artificial Intelligence in Veterinary Clinical Pathology An Introduction and
> Source: `Sources/Veterinary Clinical Pathol - 2025 - Neal - Artificial Intelligence in Veterinary Clinical Pathology An Introduction and.docx` | Date: 2026-09-25 | Depth: standard
> Verdict (Task 2): HIGHLY USABLE
---
### Task 1 — Bibliographic Classification
- **Title**: Artificial Intelligence in Veterinary Clinical Pathology—An Introduction and Review
- **Authors**: Samuel V. Neal, Daniel G. Rudmann, Kara N. Corps
- **Year**: 2025
- **Recency**: PASS (2016–2026)
- **Outlet**: Veterinary Clinical Pathology, 54(Suppl. 2), S13–S29
- **DOI/URL**: https://doi.org/10.1111/vcp.70012
- **Setting**: Foreign — veterinary clinical pathology; Ohio State University, USA
- **Design**: Review (AI workflow, qualification, validation, and veterinary clinical-pathology application review)
- **APA7**: Neal, S. V., Rudmann, D. G., & Corps, K. N. (2025). Artificial intelligence in veterinary clinical pathology—An introduction and review. *Veterinary Clinical Pathology, 54*(Suppl. 2), S13–S29. https://doi.org/10.1111/vcp.70012
- **Fit**: Current veterinary-AI review that supplies objective-ready lifecycle verbs for intended-use definition, qualification, held-out testing, metric selection, acceptance criteria, and post-deployment monitoring.

### Task 2 — Verdict
- **Verdict**: HIGHLY USABLE (4 mechanisms, 3 slots)
- **Bullets**:
  - Why + recency: PASS (2025); the review explicitly describes intended-use definition, model qualification, held-out testing, performance evaluation, acceptance criteria, and monitoring across the AI lifecycle.
  - Slots populated → Features: [Phase3-Technical-Verification-Objective] → Feature 7; [Phase4-QUAN-Evaluation-Objective] → Feature 7; [Measurable-Metric-Threshold] → Feature 7.
  - Missing: [General-Objective-Action], [Phase1-QUAL-Requirements-Objective], and [Phase2-Agile-Engineering-Objective] are not stated as CarePaws study objectives; no CareParts/Urdaneta sample, sprint measure, or clinic-specific threshold is supplied.
  - Panel use: Deflects the attack that veterinary-AI objectives are untestable by pairing qualification and testing with named metrics and a gold-standard/non-inferiority acceptance pattern.
  - Transfer risk / caveat: This is a review of clinical-pathology AI, not a CarePaws artifact evaluation; transfer the lifecycle and validation pattern only, and preserve veterinary professional oversight and the non-diagnostic boundary for Feature 7.
- **Caveat**: The source is not evidence of an implemented CarePaws feature or of a Philippine clinic result.

### Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote ≤60w + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Objective of the Study-Phase3-Technical-Verification-Objective | Define intended use, qualification criteria, and monitoring responsibility before AI deployment | Veterinary clinical-pathology AI review; no CarePaws sample or artifact baseline | "The veterinary clinical pathologist must play an active role in defining the intended use, design, and qualification of these methods as well as the plan for monitoring their responsible application in practice." (Neal et al. 2025, Abstract, para. 1) | [NOT STATED: n, clinic threshold] | [CORROBORATION] CarePaws will define the intended use, qualification checks, and monitoring responsibility for its veterinary AI module [Feature 7] |
| 2 | Objective of the Study-Phase3-Technical-Verification-Objective | Qualify a method by testing whether it satisfies its defined intended use | AI-based veterinary diagnostic method; gold-standard comparison; n [NOT STATED] | "Qualification is the process of demonstrating whether a method (in this case, an AI-based method for enumerating and reporting BAL leukocytes) satisfies its intended use as defined by the veterinary pathologist." (Neal et al. 2025, §4, Fig. 5 caption) | Intended-use satisfaction = acceptance construct / [NOT STATED: target] | [CORROBORATION] CarePaws will verify that the AI explainer satisfies its defined educational purpose before deployment [Feature 7] |
| 3 | Objective of the Study-Phase4-QUAN-Evaluation-Objective | Train on one data partition and evaluate performance on held-out unseen data | Veterinary AI model-development workflow; training/testing split; n [NOT STATED] | "Once the data split is made, models are trained, or fit, using the training set, and tested on the testing set to evaluate model performance on novel or unseen data." (Neal et al. 2025, §3.1, para. 8) | Accuracy, precision, sensitivity, specificity, AUC, F1, balanced accuracy / [NOT STATED: target values] | [CORROBORATION] CarePaws will evaluate its AI outputs on held-out cases and report named quality metrics [Feature 7] |
| 4 | Objective of the Study-Measurable-Metric-Threshold | Predefine a gold-standard comparison and accept only when the AI method meets the criterion | AI-based BAL example; noninferiority design; X laboratory/report placeholders in source | "An example of acceptance criteria could be that the method of interest is noninferior to the identified gold standard, determined by comparing the two approaches using relevant statistical analyses." (Neal et al. 2025, §4, p. S22) | Non-inferiority criterion / [NOT STATED: CarePaws threshold] | [CORROBORATION] CarePaws will predefine an ISO-aligned acceptance criterion before evaluating the AI module [Feature 7] |
Excluded: [5] candidates omitted (image-classification examples, model-family descriptions, clinical diagnostic applications, and non-CarePaws performance results — technical background or out-of-scope outcomes, not objective mechanisms).