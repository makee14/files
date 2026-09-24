# 1.5 Conceptual Framework — Veterinary Clinical Pathol - 2025 - Neal - Artificial Intelligence in Veterinary Clinical Pathology An Introduction and
> Source: `Sources/Veterinary Clinical Pathol - 2025 - Neal - Artificial Intelligence in Veterinary Clinical Pathology An Introduction and.docx` | Date: 2026-09-25 | Depth: standard
> Verdict (Task 2): HIGHLY USABLE
---

### Task 1 — Bibliographic Classification
- **Title**: Artificial Intelligence in Veterinary Clinical Pathology—An Introduction and Review
- **Authors**: Samuel V. Neal; Daniel G. Rudmann; Kara N. Corps
- **Year**: 2025
- **Recency**: PASS (2016–2026)
- **Outlet**: Veterinary Clinical Pathology, 54(Suppl. 2), S13–S29
- **DOI/URL**: https://doi.org/10.1111/vcp.70012
- **Setting**: Foreign + proof quote “Department of Veterinary Biosciences, College of Veterinary Medicine, Ohio State University, Columbus, Ohio, USA”
- **Design**: Review
- **APA7**: Neal, S. V., Rudmann, D. G., & Corps, K. N. (2025). Artificial intelligence in veterinary clinical pathology—An introduction and review. *Veterinary Clinical Pathology, 54*(Suppl. 2), S13–S29. https://doi.org/10.1111/vcp.70012
- **Fit**: The veterinary review supplies an iterative AI development cycle, explicit data-to-test causal logic, expert-controlled output gates, and qualification metrics for empirical outputs.

### Task 2 — Verdict
- **Verdict**: HIGHLY USABLE
- **Why**: PASS recency; the review provides four concrete mechanisms across three allowed slots, including an explicit build→evaluate→monitor→retrain workflow and clinician-controlled acceptance criteria.
- **Slots populated**: Process-Agile-DSR-Cycles; Process-Inside-The-Arrows-Causal-Logic; Output-Empirical-Usability-Baseline → Features 2 and 7.
- **Missing slots / metrics**: No ISO/IEC 25010 criterion, single-clinic baseline, RBAC permission matrix, or CarePaws acceptance threshold; cited veterinary examples are not evaluations of CarePaws.
- **Panel use**: Deflects attacks that AI outputs are unvalidated black boxes or that monitoring ends at deployment.
- **Transfer caveat**: The review concerns clinical pathology and diagnostic AI; only assistive summaries and non-diagnostic triage guardrails are transferable to Features 2 and 7.

### Task 3 — Extraction Bank

| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote ≤60w + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Conceptual Framework-Process-Agile-DSR-Cycles | An iterative AI lifecycle defines the problem, acquires and prepares data, trains and tests a model, then monitors real-world performance and retrains when results degrade. | Veterinary clinical-pathology AI workflow; narrative review; no CarePaws sample | “The algorithm(s) is then trained using the prepared training set. Model performance is then evaluated using the prepared testing data set. If the model is performing acceptably, the model can be deployed and monitored to ensure continued high performance on real-world data.” (Neal et al., 2025, Figure 3 caption) | Six development steps before training; real-world monitoring after deployment / [NOT STATED: retraining interval] | [CORROBORATION] CarePaws will iterate AI development through defined data preparation, held-out testing, clinician review, deployment monitoring, and evidence-triggered retraining [Feature 2] |
| 2 | Conceptual Framework-Process-Inside-The-Arrows-Causal-Logic | Separating training and unseen test data prevents learned training patterns from inflating model-performance metrics; cross-validation repeats held-out assessment across smaller datasets. | Machine-learning workflow; veterinary review; no sample | “After data exploration and preparation, the data set is typically split into training and testing sets. This is done so that models can be tested on data not used in training, ensuring that model performance metrics are not artificially inflated due to learned patterns specific to the training set.” (Neal et al., 2025, Supervised Model Development, para. 13) | Common split 80% training/20% testing; k-fold cross-validation | [DEPARTURE] CarePaws will evaluate AI changes on held-out clinic records and repeat validation across folds before accepting a model version [Feature 7] |
| 3 | Conceptual Framework-Output-Empirical-Usability-Baseline | Qualification begins with intended use, then defines a clinician-approved gold standard and statistically compares AI output with the reference method before implementation and continued monitoring. | AI-based BAL leukocyte enumeration example; veterinary clinical-pathology laboratory; illustrative thresholds | “After the intended use is defined, the veterinary pathologist needs to define acceptance criteria (“the gold standard”) for the method.” (Neal et al., 2025, Qualification and Validation, para. 7) | Example accepts AI method if non-inferior to manual method; [NOT STATED: actual threshold] | [DEPARTURE] CarePaws will define intended use and acceptance criteria for each assistive AI output, then verify performance against a veterinarian-approved reference before release [Feature 2] |
| 4 | Conceptual Framework-Process-Inside-The-Arrows-Causal-Logic | Expert supervision provides a human gate for rejecting unsafe outputs and feeding corrected cases back into training, testing, and version validation. | High-dimensional clinical AI; veterinary review; no deployment sample | “This lack of transparency emphasizes the need for supervision of the models by an expert (e.g., clinical pathologist) and the ability to reject an output and add new input (training) followed by testing and validation of model versions.” (Neal et al., 2025, Neural Networks, para. 7) | [NOT STATED: rejection rate; review time] | [CORROBORATION] CarePaws will retain veterinarian authority to reject AI outputs and route corrected cases into controlled retraining, testing, and version validation [Feature 7] |

Excluded: 3 candidates omitted (specific diagnostic-model accuracy figures outside the conceptual mechanism; centralized repositories and federated learning exceeded CarePaws scope).