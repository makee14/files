# 1.9.3 Synthesis of the State-of-the-Art — Veterinary Clinical Pathol - 2025 - Neal - Artificial Intelligence in Veterinary Clinical Pathology An Introduction and
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
- **Setting**: Foreign — “Department of Veterinary Biosciences, College of Veterinary Medicine, Ohio State University, Columbus, Ohio, USA” (Neal et al., 2025, author affiliation)
- **Design**: Review (AI concepts, qualification, validation, and veterinary applications)
- **APA7**: Neal, S. V., Rudmann, D. G., & Corps, K. N. (2025). Artificial intelligence in veterinary clinical pathology—An introduction and review. *Veterinary Clinical Pathology, 54*(Suppl. 2), S13–S29. https://doi.org/10.1111/vcp.70012
- **Fit**: This recent veterinary review identifies data-source generalizability, centralized-data, validation, model-monitoring, and small-study limitations that support the four synthesis-gap dimensions.
### Task 2 — Verdict
- **Verdict**: HIGHLY USABLE (4 mechanisms across 4 gap slots)
- **Bullets**:
  - Why this verdict + recency status: PASS (2025); the review supplies explicit mechanisms for data variation, limited centralized databases, veterinary qualification/validation, and post-deployment drift monitoring.
  - Slots populated → Features: [Methodological-Gap] → Features 2, 7; [Geographical-Gap] → Features 1, 2, 4; [Architectural-Gap] → Features 2, 4; [Empirical-Gap] → Features 2, 7; [CarePaws-Synthesis-Resolution] → Features 2, 7.
  - Missing slots / metrics this source cannot cover: no Philippine/Urdaneta validation and no CarePaws latency, availability, or usability measurement; the review is not a controlled deployment study.
  - Panel use: deflects “high reported model accuracy proves an AI clinical feature is ready” by separating proof-of-concept results from generalizability, qualification, drift monitoring, and veterinary oversight.
  - Transfer risk / caveat: This is a clinical-pathology review, not a CarePaws requirements study; diagnostic AI claims are not transferred, and the veterinarian remains clinical authority.
### Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote ≤60w + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Synthesis-Methodological-Gap | Generalizability-method gap: single-institution data may be insufficient, and subtle source differences can degrade performance unless represented during development. | Veterinary clinical-pathology review; no primary validation sample. | “If generalizability is desired, it is important to incorporate data from a variety of sources that reflect the variability expected by the model once in use.” (Neal et al., 2025, §3.1, p. 15) | n=[NOT STATED]; cross-source performance and external-validation metrics not reported | [DEPARTURE] CarePaws will validate AI-assisted summaries and owner explanations across staff, owner, canine/feline, and local-clinic data strata [Features 2, 7] |
| 2 | Synthesis-Architectural-Gap | Data-infrastructure gap: veterinary AI depends on centralized databases, interoperable preparation, and monitoring, but these capabilities remain developing. | Veterinary clinical pathology; EHRs, whole-slide images, specialist reports, and laboratory data. | “These include a lack of centralized databases, the need for improved slide scanning capabilities, and the variation across veterinary medicine” (Neal et al., 2025, §6 Conclusions, p. 25) | Database coverage, scan capability, and monitoring results [NOT STATED] | [DEPARTURE] CarePaws will use structured record fields, resilient local storage, and monitored quality checks for AI-assisted clinical summaries [Features 2, 4] |

| 3 | Synthesis-Empirical-Gap | Evidence-scale gap: many veterinary AI studies remain single-institutional, small-sample proof-of-concepts that require expansion before generalization. | Veterinary clinical-pathology applications; review of veterinary and human studies. | “Many of the studies discussed below are single institutional studies with relatively small sample sizes. These represent important proof of concepts but likely require significant expansion to generalize.” (Neal et al., 2025, §5, p. 23) | Small single-site samples; cited applications use differing sensitivity/specificity and error metrics | [CONTRADICTION] CarePaws will report external task results, error types, and local user outcomes instead of treating a proof-of-concept accuracy score as deployment evidence [Features 2, 7] |
| 4 | Synthesis-CarePaws-Synthesis-Resolution | Lifecycle-resolution mechanism: AI should augment rather than replace veterinary professionals, with intended use, qualification, oversight, and continuous monitoring across development, deployment, and drift. | Veterinary clinical-pathology review; clinician-in-the-loop principle. | “AI models should be designed to augment, not replace, veterinary clinical pathologists” and must be monitored for degradation due to model drift. (Neal et al., 2025, §6 Conclusions, p. 25) | Drift threshold, monitoring cadence, and escalation threshold [NOT STATED] | [CORROBORATION] CarePaws will keep the veterinarian as clinical decision authority, disclose the explainer’s educational limits, and monitor summary quality and owner-facing safety signals [Features 2, 7] |
Excluded: 5 candidates omitted (algorithm taxonomy, general AI definitions, model architectures, and individual cited metrics did not add a distinct target-gap mechanism).
### Usability Gate — Task 2 based
- Verdict: **HIGHLY USABLE**
- Why: This 2025 veterinary review contributes distinct methodological, infrastructure, empirical, and clinician-oversight mechanisms, while leaving Philippine deployment evidence to later validation.
- Slots filled: [Methodological-Gap], [Geographical-Gap], [Architectural-Gap], [Empirical-Gap], [CarePaws-Synthesis-Resolution] → Features: 1, 2, 4, 7
- Missing for this section: no unresolved 1.9.3 slot; Philippine/Urdaneta validation and CarePaws-specific metrics remain future work.
- Keep for draft? **YES** — use for the state-of-the-art gap synthesis and as a boundary against diagnostic-AI scope creep.
- Panel use: deflects “reported accuracy establishes safe clinical AI” by requiring external validation, local monitoring, and professional oversight.
