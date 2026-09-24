# STATUS — 2.6 Tools for Data Analysis
> Extractor: `research_assistant_SECTION_EXTRACTOR_v7.md` | Depth default: standard | Updated: 2026-09-25

## Queue (source order — alphabetical)
- [x] DONE — `0_1_Introduction.md` — NOT USABLE
- [x] DONE — `1-s2.0-S3051308126000021-main.md` — HIGHLY USABLE
- [x] DONE — `1236-1251.md` — PARTIALLY USABLE
- [x] DONE — `15189-Article Text-39763-2-10-20260328.md` — HIGHLY USABLE
- [x] DONE — `15_beyer.k-chomiak-orsa.i-pietrzykowski.z.md` — NOT USABLE
- [x] DONE — `169-175.docx` — PARTIALLY USABLE
- [x] DONE — `3305160.3305164.md` — PARTIALLY USABLE
- [x] DONE — `450-462.docx` — NOT USABLE
- [x] DONE — `776.md` — PARTIALLY USABLE
- [ ] TODO — `C-MALICDEM,+KIMBERLEY+P_Research+Article+Revised+3.md`
- [ ] TODO — `dataprivacy.md`
- [ ] TODO — `javma-javma.245.3.324.docx`
- [x] DONE — `MG_2026_EurSafe26.md` — NOT USABLE
- [x] DONE — `Nablus-Vet-Care-Report.md` — NOT USABLE
- [ ] TODO — `PDG_Practical_Compliance_Guide.docx`
- [ ] TODO — `s12917-016-0861-y.docx`
- [x] DONE — `s13620-018-0123-3.md` — NOT USABLE
- [ ] TODO — `s44356-025-00043-2.docx`
- [x] DONE — `The_DeLone_and_McLean_Model_of_Information_Systems.md` — NOT USABLE
- [x] DONE — `VenkateshThongXu-JAIS2016-OpenAccess (1).md` — NOT USABLE
- [x] DONE — `VetBot.md` — HIGHLY USABLE
- [ ] TODO — `Veterinary Clinical Pathol - 2025 - Neal - Artificial Intelligence in Veterinary Clinical Pathology An Introduction and.docx`
- [x] DONE — `vol10-iss6-pg4336-4346-202606_pdf.md` — HIGHLY USABLE
- [x] DONE — `WSN-211-2026-132-151.md` — PARTIALLY USABLE

## Progress
- Done: 17 / 24 | Highly: 4 | Partially: 5 | Not Usable: 8

## Results Log (one row per completed source — from Task 2)
| Source | Verdict | Slots populated | Features mapped |
|---|---|---|---|
| 0_1_Introduction.md | NOT USABLE | none (redirect → 2.1) | — |
| 1-s2.0-S3051308126000021-main.md | HIGHLY USABLE | Golden-Thread, Cronbach-Alpha, Likert-Bounds | Feature 2 |
| 1236-1251.md | PARTIALLY USABLE | Golden-Thread | Features 1, 2, 6 |
| 15189-Article Text-39763-2-10-20260328.md | HIGHLY USABLE | Golden-Thread, Weighted-Mean, Likert-Bounds | Feature 2 |
| 15_beyer.k-chomiak-orsa.i-pietrzykowski.z.md | NOT USABLE | none (redirect → 2.4, 1.9.1) | — |
| 169-175.docx | PARTIALLY USABLE | Golden-Thread, Likert-Verbal-Interpretation | Feature 2 |
| 3305160.3305164.md | PARTIALLY USABLE | Likert seed (4.3 + gender split) | Feature 2 |
| 450-462.docx | NOT USABLE | none (redirect → 2.5, 2.3) | — |
| 776.md | PARTIALLY USABLE | Golden-Thread seed (ranked frequencies) | Features 1, 2 |
| MG_2026_EurSafe26.md | NOT USABLE | none (redirect → 2.1, 1.9.1) | — |
| Nablus-Vet-Care-Report.md | NOT USABLE | none (redirect → 2.5, 2.2; Ch.5 data synthetic) | — |
| s13620-018-0123-3.md | NOT USABLE | none (redirect → 2.4, 2.3) | — |
| The_DeLone_and_McLean_Model_of_Information_Systems.md | NOT USABLE | none (redirect → 1.4) | — |
| VenkateshThongXu-JAIS2016-OpenAccess (1).md | NOT USABLE | none (redirect → 1.4, 2.1) | — |
| VetBot.md | HIGHLY USABLE | Golden-Thread, Weighted-Mean, Likert ×2 (RAGAS+SUS) | Features 4, 7 |
| vol10-iss6-pg4336-4346-202606_pdf.md | HIGHLY USABLE | Golden-Thread, Weighted-Mean, Likert-Bounds | Feature 2 |
| WSN-211-2026-132-151.md | PARTIALLY USABLE | Golden-Thread seed (survey+observation) | Features 1, 2 |

## Cross-source comparison
- Four pipeline sources now anchor 2.6: Morales et al. (2026) and VetCareSys both field the complete ISO-instrument → ordinal five-point Likert → weighted-mean → bounded-interpretation pipeline (Morales n=32 with eight ISO 25010 characteristics; VetCareSys n=16 with seven ISO 9126 characteristics and explicit 1.0–5.0 bands), Tukur et al. (2026) supplies the missing reliability leg (expert-reviewed questionnaire, pilot n=15, Cronbach alpha above 0.7 per domain, anchored five-point scales on n=152), and VetBot adds the AI-evaluation leg (RAGAS five-metric run on N=99 plus nine-criterion expert weighted means at 4.56 Strongly Agree plus SUS 79.61 Excellent). EliteVet corroborates objective-to-test traceability only (69/69 cases, UAT n=25) with no statistic; FurrySmart corroborates a 4.3 Agree acceptability reading with a gender-split table; Vetconnect and Care for Paws corroborate ranked-frequency and survey-plus-observation seeds only. Beyer, Giersberg, Nablus, Golden, and DVAS carry zero qualifying mechanisms. No conflicts. Gaps: [Standard-Deviation-Formula], [Kendalls-W-Concordance], and [OWASP-Security-Checklist] remain empty across the 17 judged sources; DVAS names STRIDE and supplies a project-specific security test checklist, but neither qualifies as OWASP.
- Current inbox reconciliation: 24 sources discovered; 17 judged and seven remain TODO. DVAS contributes no 2.6 slot: its n=31 user-acceptance results, custom STRIDE analysis, and four-scenario DVAS checklist lack the required formulas, scale bounds, reliability coefficient, Golden Thread map, or OWASP provenance.

## Section Verdict
- IN PROGRESS — 17 of 24 current inbox files judged; nine usable sources (4 highly, 5 partially) with 19 grounded rows; seven sources remain TODO. Cross-source comparison remains provisional until the current queue clears.

## Next up
- NEXT SECTION: 2.6 | NEXT SOURCE: `C-MALICDEM,+KIMBERLEY+P_Research+Article+Revised+3.md`
- Starter for new session (copy-paste):
```text
Read 00_SECTION_EXTRACTION_ORCHESTRATOR_PROMPT.md, then extractor v7, then do single job: TARGET 2.6 Tools for Data Analysis × SOURCE Sources/C-MALICDEM,+KIMBERLEY+P_Research+Article+Revised+3.md. Standard depth. See Outputs/2.6_Tools_for_Data_Analysis/_STATUS_2.6.md for queue.
```
