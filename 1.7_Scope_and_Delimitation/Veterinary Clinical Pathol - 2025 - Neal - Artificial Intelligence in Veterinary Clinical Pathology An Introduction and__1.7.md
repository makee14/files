# 1.7 Scope and Delimitation — Veterinary Clinical Pathol - 2025 - Neal - Artificial Intelligence in Veterinary Clinical Pathology An Introduction and
> Source: `Sources/Veterinary Clinical Pathol - 2025 - Neal - Artificial Intelligence in Veterinary Clinical Pathology An Introduction and.docx` | Date: 2026-09-25 | Depth: standard
> Verdict (Task 2): HIGHLY USABLE
---

## Task 1 — Bibliographic Classification
- **Title**: Artificial Intelligence in Veterinary Clinical Pathology—An Introduction and Review
- **Authors**: Samuel V. Neal; Daniel G. Rudmann; Kara N. Corps
- **Year**: 2025
- **Recency**: PASS (2016–2026)
- **Outlet**: Veterinary Clinical Pathology, 54(Suppl. 2), S13–S29
- **DOI/URL**: https://doi.org/10.1111/vcp.70012
- **Setting**: Foreign — Ohio State University, Columbus, Ohio, USA; Moderna Inc., Cambridge, Massachusetts, USA
- **Design**: Review
- **APA7**: Neal, S. V., Rudmann, D. G., & Corps, K. N. (2025). Artificial intelligence in veterinary clinical pathology—An introduction and review. *Veterinary Clinical Pathology, 54*(Suppl. 2), S13–S29. https://doi.org/10.1111/vcp.70012
- **Fit**: Supplies explicit intended-use, human-oversight, model-monitoring, and non-generalizability boundaries relevant to delimiting CarePaws’ AI-assisted scope.

## Task 2 — Verdict
- **Verdict**: HIGHLY USABLE
- **Recency passes; three grounded mechanisms populate three allowed slots.
- **Slots populated**: Population-Boundary, System-Feature-Boundary, Deliberate-Exclusion-Justification → Features 1–7 boundary.
- **Missing**: No CarePaws clinic, canine/feline sample, pilot dates, or formal feature inventory.
- **Panel use**: Defends an assistive, veterinarian-supervised, narrowly intended-use boundary and rejects claims that an AI module may replace professional judgment or generalize beyond its validated setting.
- **Caveat**: This is a review of veterinary clinical pathology AI, not a CarePaws implementation study; transfers are explicit scope-control extrapolations.

## Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote ≤60w + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Scope and Delimitation-System-Feature-Boundary | AI scope is bounded by an explicitly defined intended use, design, qualification, and monitoring plan | Review of veterinary clinical pathology AI; deployment context | “The veterinary clinical pathologist must play an active role in defining the intended use, design, and qualification of these methods as well as the plan for monitoring their responsible application in practice.” (Neal et al. 2025, Abstract) | [NOT STATED] | [DEPARTURE] CarePaws will define and monitor the AI module only as an assistive, non-diagnostic Feature 7 function within the veterinarian’s authority [Feature 7] |
| 2 | Scope and Delimitation-Deliberate-Exclusion-Justification | AI models are restricted to augmentation, with professional oversight retained and model drift/rare-disease misses acknowledged | Veterinary clinical pathology; post-deployment lifecycle | “AI models should be designed to augment, not replace, veterinary clinical pathologists... once models are deployed, they must be monitored for degradation in performance due to variations in the environment, termed model drift.” (Neal et al. 2025, Conclusions, para. 1) | [NOT STATED] | [DEPARTURE] CarePaws will exclude autonomous diagnosis, treatment selection, and unmonitored model claims, retaining veterinarian review and formal-vet-consultation escalation [Feature 7] |
| 3 | Scope and Delimitation-Population-Boundary | Small, single-institution proof-of-concept studies are treated as insufficiently generalizable without expansion | Veterinary clinical pathology applications; review evidence | “Many of the studies discussed below are single institutional studies with relatively small sample sizes. These represent important proof of concepts but likely require significant expansion to generalize well.” (Neal et al. 2025, Section 5—AI Applications Relevant to Veterinary Clinical Pathology) | Single-institution studies; relatively small samples | [DEPARTURE] CarePaws will delimit its evaluation to one Urdaneta clinic and its authorized companion-animal population, and exclude cross-site generalization claims [Feature 2] |

Excluded: 7 candidates omitted (ML definitions, algorithm taxonomy, laboratory validation details, model-performance examples without scope mechanisms, human-pathology applications without veterinary transfer, and generic AI benefits).
