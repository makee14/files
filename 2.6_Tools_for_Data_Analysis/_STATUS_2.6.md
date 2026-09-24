# STATUS — 2.6 Tools for Data Analysis
> Extractor: `research_assistant_SECTION_EXTRACTOR_v7.md` | Depth default: standard | Updated: 2026-09-24

## Queue (source order — alphabetical)
- [x] DONE — `0_1_Introduction.md` — NOT USABLE
- [x] DONE — `1-s2.0-S3051308126000021-main.md` — HIGHLY USABLE
- [x] DONE — `1236-1251.md` — PARTIALLY USABLE
- [x] DONE — `15189-Article Text-39763-2-10-20260328.md` — HIGHLY USABLE
- [x] DONE — `15_beyer.k-chomiak-orsa.i-pietrzykowski.z.md` — NOT USABLE
- [x] DONE — `3305160.3305164.md` — PARTIALLY USABLE
- [x] DONE — `776.md` — PARTIALLY USABLE
- [x] DONE — `MG_2026_EurSafe26.md` — NOT USABLE
- [x] DONE — `Nablus-Vet-Care-Report.md` — NOT USABLE
- [x] DONE — `s13620-018-0123-3.md` — NOT USABLE
- [x] DONE — `The_DeLone_and_McLean_Model_of_Information_Systems.md` — NOT USABLE
- [x] DONE — `VenkateshThongXu-JAIS2016-OpenAccess (1).md` — NOT USABLE
- [x] DONE — `VetBot.md` — HIGHLY USABLE
- [x] DONE — `vol10-iss6-pg4336-4346-202606_pdf.md` — HIGHLY USABLE
- [x] DONE — `WSN-211-2026-132-151.md` — PARTIALLY USABLE

## Progress
- Done: 15 / 15 | Highly: 4 | Partially: 4 | Not Usable: 7

## Results Log (one row per completed source — from Task 2)
| Source | Verdict | Slots populated | Features mapped |
|---|---|---|---|
| 0_1_Introduction.md | NOT USABLE | none (redirect → 2.1) | — |
| 1-s2.0-S3051308126000021-main.md | HIGHLY USABLE | Golden-Thread, Cronbach-Alpha, Likert-Bounds | Feature 2 |
| 1236-1251.md | PARTIALLY USABLE | Golden-Thread | Features 1, 2, 6 |
| 15189-Article Text-39763-2-10-20260328.md | HIGHLY USABLE | Golden-Thread, Weighted-Mean, Likert-Bounds | Feature 2 |
| 15_beyer.k-chomiak-orsa.i-pietrzykowski.z.md | NOT USABLE | none (redirect → 2.4, 1.9.1) | — |
| 3305160.3305164.md | PARTIALLY USABLE | Likert seed (4.3 + gender split) | Feature 2 |
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
- Four pipeline sources now anchor 2.6: Morales et al. (2026) and VetCareSys both field the complete ISO-instrument → ordinal five-point Likert → weighted-mean → bounded-interpretation pipeline (Morales n=32 with eight ISO 25010 characteristics; VetCareSys n=16 with seven ISO 9126 characteristics and explicit 1.0–5.0 bands), Tukur et al. (2026) supplies the missing reliability leg (expert-reviewed questionnaire, pilot n=15, Cronbach alpha above 0.7 per domain, anchored five-point scales on n=152), and VetBot adds the AI-evaluation leg (RAGAS five-metric run on N=99 plus nine-criterion expert weighted means at 4.56 Strongly Agree plus SUS 79.61 Excellent). EliteVet corroborates objective-to-test traceability only (69/69 cases, UAT n=25) with no statistic; FurrySmart corroborates a 4.3 Agree acceptability reading with a gender-split table; Vetconnect and Care for Paws corroborate ranked-frequency and survey-plus-observation seeds only. Beyer, Giersberg, Nablus, and Golden carry zero qualifying mechanisms. No conflicts. Gaps: [Standard-Deviation-Formula], [Kendalls-W-Concordance], and [OWASP-Security-Checklist] remain empty across all 15 sources — must come from statistics/security sources added later, never invented.

## Section Verdict
- COMPLETE (for current inbox) — 15 of 15 inbox files judged; 8 usable sources (4 highly, 4 partially) with 17 grounded rows; ready for drafting 2.6 with statistics sources filling SD/W/OWASP.

## Next up
- None — queue empty for current inbox. Files added later become TODO on the next run.
