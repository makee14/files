# 1.2 Purpose and Description of the Study — Veterinary Clinical Pathol - 2025 - Neal - Artificial Intelligence in Veterinary Clinical Pathology An Introduction and
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
- **Setting**: Foreign (United States) + proof: “Ohio State University, Columbus, Ohio, USA” and “Cambridge, Massachusetts, USA”
- **Design**: Review (narrative educational review; no original validation dataset)
- **APA7**: Neal, S. V., Rudmann, D. G., & Corps, K. N. (2025). Artificial intelligence in veterinary clinical pathology—An introduction and review. *Veterinary Clinical Pathology, 54*(Suppl. 2), S13–S29. https://doi.org/10.1111/vcp.70012
- **Fit**: Directly supports the bounded AI-assisted clinical-summary lifecycle, veterinarian authority, qualification criteria, and post-deployment monitoring for Feature 2.

### Task 2 — Verdict
- **Verdict**: HIGHLY USABLE (4 mechanisms, 4 slots)
- **Bullets (3–5)**:
  - **Why this verdict + recency status**: PASS (2025). The review provides a four-mechanism AI lifecycle: define intended use, train/test against expert-labelled data, retain expert oversight, and monitor deployed performance against an acceptance criterion.
  - **Slots populated → Features 1–7 mapping**: [Primary-Intervention-Mechanism], [Function-Feature-1-7], [Role-Gated-Value-Creation], and [Metric-Change-Target] → Feature 2. No diagnostic-AI or pathology capability is transferred.
  - **Missing slots / metrics this source cannot cover**: [System-Novelty] is not established for CarePaws, and a CarePaws-specific noninferiority margin, latency, sample size, or local baseline is [NOT STATED].
  - **Panel use**: deflects “AI summary is an uncontrolled black box” with intended-use definition, test-set evaluation, expert rejection authority, and continuous monitoring.
  - **Transfer risk / caveat**: Most cited models diagnose laboratory or image-based disease; those capabilities, metrics, and datasets are outside Features 1–7. Only the assistive summary, expert gate, and validation pattern transfer to Feature 2.
- **Transfer boundary**: CarePaws will not inherit pathology diagnosis, image analysis, autonomous classification, or a source-specific performance threshold; the veterinarian remains the sole clinical decision-maker.

### Task 3 — Extraction Bank (1–4 rows max, min 1. Never pad.)

| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote ≤60w + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Purpose and Description-Primary-Intervention-Mechanism | An AI workflow defines the problem, collects and prepares data, selects an algorithm, and reserves independent training and testing sets | Narrative review of veterinary clinical-pathology AI; no original sample | “At the outset of ML model development, several steps are required, including (1) defining the problem to be addressed, (2) collection of necessary data, (3) exploration of the data, (4) selection of the initial algorithm(s) to be trained, (5) preparation of the data, and (6) splitting of the data into training and testing sets.” (Neal et al. 2025, Figure 3 caption) | [NOT STATED: CarePaws n, effect size, latency] | [CORROBORATION] CarePaws will define, train, test, and monitor the AI-assisted clinical summary within the digital health record [Feature 2] |
| 2 | Purpose and Description-Function-Feature-1-7 | AI produces a preliminary result while final interpretation remains with a clinical expert | Veterinary clinical-pathology use case; automated blood-smear evaluation | “Such a use case could be part of a wider set of AI models that collectively perform automated blood smear evaluation and provide preliminary results to the clinician while the sample awaits final clinical pathologist review.” (Neal et al. 2025, §3.1, para. 1) | Preliminary/final review stages; outcome effect [NOT STATED] | [DEPARTURE] CarePaws will restrict AI assistance to a preliminary, non-diagnostic summary while the attending veterinarian retains sole authority [Feature 2] |
| 3 | Purpose and Description-Role-Gated-Value-Creation | The clinical expert governs intended use, design, qualification, monitoring, and rejection of AI output | Veterinary clinical-pathology AI governance | “The veterinary pathologist must play an active role in defining the intended use, design, and qualification of these methods as well as the plan for monitoring their responsible application in practice.” (Neal et al. 2025, Abstract, para. 1) | [NOT STATED: rejection rate or override time] | [CORROBORATION] CarePaws will keep the veterinarian as sole clinical decision-maker and allow rejection or correction of every AI-assisted summary [Feature 2] |
| 4 | Purpose and Description-Metric-Change-Target | Qualification compares AI output with a clinician-defined gold standard using a predeclared noninferiority criterion | BAL leukocyte-enumeration example; laboratory and report placeholders | “An example could be ‘the automated AI-based BAL method will be non-inferior to the manual clinical pathology method at X laboratory as documented in X report.’” (Neal et al. 2025, §4, para. 3) | Noninferiority criterion; threshold, laboratory, and report [NOT STATED] | [CORROBORATION] CarePaws will predeclare a clinician-reviewed gold standard and an acceptance metric for the Feature 2 AI summary [Feature 2] |

Excluded: [4] candidates omitted (pathology diagnostic accuracy, image-classification datasets, an 80/20 split, and model-specific sensitivity/specificity were quarantined as diagnostic-AI or non-transferable thresholds).