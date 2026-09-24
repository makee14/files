# 2.6 Tools for Data Analysis — VetBot
> Source: `Sources/VetBot.md` | Date: 2026-09-24 | Depth: standard
> Verdict (Task 2): HIGHLY USABLE
---
### Task 1 — Bibliographic Classification
- **Title**: VetBot: An AI-Driven Veterinary Chatbot for Canine and Feline Care Guidance
- **Authors**: Edward Andrew P. Alverde, James Robert F. Dangbis, Voke Michael Oghenekaro, Paul Emmanuelle Quimpo, Johnny F. Verzola
- **Year**: [MISSING: year not stated in extracted text]
- **Recency**: UNCLASSIFIED (year unstated; FAIL rule applies only to verified pre-2016)
- **Outlet**: [MISSING: outlet not stated in extracted text; Lorma Colleges capstone manuscript]
- **DOI/URL**: [MISSING: DOI not stated in extracted text]
- **Setting**: Local (Philippines) + "College of Computer Studies and Engineering, Lorma Colleges" plus "In provincial settings such as La Union, Philippines"
- **Design**: Mixed evaluation (RAGAS N=99 automated run; 9 licensed veterinarians on five-point Likert across nine criteria; 32 pet owners on SUS)
- **APA7**: Alverde, E. A. P., Dangbis, J. R. F., Oghenekaro, V. M., Quimpo, P. E., & Verzola, J. F. ([MISSING: year]). VetBot: An AI-driven veterinary chatbot for canine and feline care guidance. Lorma Colleges. [MISSING: outlet, DOI]
- **Fit**: Only source pairing a five-metric RAGAS evaluation with a nine-criterion weighted-mean Likert panel plus SUS — the richest 2.6 instrument-plus-metric precedent in the batch.
### Task 2 — Verdict
- **Verdict**: HIGHLY USABLE (4 mechanisms, 3 slots)
- **Bullets**:
  - Why + recency: UNCLASSIFIED (year unstated); RAGAS five-metric run plus expert weighted means plus SUS 79.61.
  - Slots populated → Features: [Golden-Thread-Objective-Alignment] → Feature 7; [Weighted-Mean-Formula] → Feature 7; [Likert-Scale-Verbal-Interpretation] → Features 4, 7.
  - Missing: [Standard-Deviation-Formula], [Kendalls-W-Concordance], [Cronbachs-Alpha-Reliability], [OWASP-Security-Checklist] (all [NOT STATED]).
  - Panel use: deflects "AI evaluation unmeasured" — RAGAS grounding plus Strongly Agree expert means plus Excellent SUS in one pipeline.
  - Caveat: transfer the instrument-plus-metric pattern; RAGAS tuning thresholds are Feature 7 engineering detail for later chapters.
### Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Tools for Data Analysis-Golden-Thread-Objective-Alignment | Five-metric RAGAS instrument aligning retrieval-generation objectives to faithfulness, relevancy, precision, recall, and correctness | N=99 clinical test queries, La Union | "The RAG pipeline was evaluated with the RAGAS framework on 99 clinical test queries." (Alverde et al., Abstract, para. 3) | N=99; faithfulness 0.889, relevancy 0.906, precision 0.753, recall 0.691, correctness 0.517 / [NOT STATED: SD, alpha] | [TEMPLATE] CarePaws will align its Feature 7 explainer objective to the same multi-metric evaluation instrument [Feature 7] |
| 2 | Tools for Data Analysis-Weighted-Mean-Formula | Nine-criterion expert weighted-mean computation across six urgency scenarios | N=9 licensed veterinarians, La Union | "For each scenario, evaluators rated VetBot's output across nine criteria using a 5-point Likert scale." (Alverde et al., Expert Evaluation, para. 1) | Overall mean 4.56, n=9 / [NOT STATED: SD formula, alpha] | [TEMPLATE] CarePaws will compute expert weighted means on the same five-point, multi-criterion pipeline [Feature 7] |
| 3 | Tools for Data Analysis-Likert-Scale-Verbal-Interpretation | Strongly Agree interpretation of the 4.56 overall expert mean with criterion-level bounds | N=9 licensed veterinarians, six scenarios | "the overall weighted mean across all nine criteria was 4.56, which falls within the Strongly Agree range" (Alverde et al., Expert Evaluation, Table 2, para. 1) | 4.56 Strongly Agree; triage utility 4.67 / [NOT STATED: band bounds, SD] | [TEMPLATE] CarePaws will interpret its expert Likert means against the same Strongly Agree banding [Feature 7] |
| 4 | Tools for Data Analysis-Likert-Scale-Verbal-Interpretation | SUS usability outcome interpreting 79.61 as Grade A- Excellent | n=32 pet owners, La Union | "Thirty-two (32) pet owners completed the System Usability Scale (SUS), producing a score of 79.61" (Alverde et al., Abstract, para. 3) | SUS 79.61, Grade A-, Excellent, n=32 / [NOT STATED: SD, alpha] | [CORROBORATION] CarePaws will interpret its owner SUS scores against the same Excellent-graded reading [Features 4, 7] |
Excluded: [1] candidate omitted (correctness-wording caveat — interpretive note, not a separate analysis tool).