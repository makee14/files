# STATUS — 2.4 Sources of Data
> Extractor: `research_assistant_SECTION_EXTRACTOR_v7.md` | Depth default: standard | Updated: 2026-09-25

## Queue (fresh-reconciled source order — alphabetical)
- [x] DONE — `0_1_Introduction.md` — NOT USABLE
- [x] DONE — `1236-1251.md` — PARTIALLY USABLE
- [x] DONE — `15_beyer.k-chomiak-orsa.i-pietrzykowski.z.md` — PARTIALLY USABLE
- [x] DONE — `15189-Article Text-39763-2-10-20260328.md` — HIGHLY USABLE
- [x] DONE — `169-175.docx` — HIGHLY USABLE
- [x] DONE — `1-s2.0-S3051308126000021-main.md` — PARTIALLY USABLE
- [x] DONE — `3305160.3305164.md` — PARTIALLY USABLE
- [x] DONE — `450-462.docx` — HIGHLY USABLE
- [x] DONE — `776.md` — PARTIALLY USABLE
- [ ] TODO — `C-MALICDEM,+KIMBERLEY+P_Research+Article+Revised+3.md`
- [ ] TODO — `dataprivacy.md`
- [ ] TODO — `javma-javma.245.3.324.docx`
- [x] DONE — `MG_2026_EurSafe26.md` — PARTIALLY USABLE
- [x] DONE — `Nablus-Vet-Care-Report.md` — PARTIALLY USABLE
- [ ] TODO — `PDG_Practical_Compliance_Guide.docx`
- [ ] TODO — `s12917-016-0861-y.docx`
- [x] DONE — `s13620-018-0123-3.md` — HIGHLY USABLE
- [ ] TODO — `s44356-025-00043-2.docx`
- [x] DONE — `The_DeLone_and_McLean_Model_of_Information_Systems.md` — NOT USABLE
- [x] DONE — `VenkateshThongXu-JAIS2016-OpenAccess (1).md` — NOT USABLE
- [x] DONE — `VetBot.md` — HIGHLY USABLE
- [ ] TODO — `Veterinary Clinical Pathol - 2025 - Neal - Artificial Intelligence in Veterinary Clinical Pathology An Introduction and.docx`
- [x] DONE — `vol10-iss6-pg4336-4346-202606_pdf.md` — HIGHLY USABLE
- [x] DONE — `WSN-211-2026-132-151.md` — HIGHLY USABLE

## Progress
- Done: 17 / 24 | Highly: 7 | Partially: 7 | Not Usable: 3

## Results Log (one row per completed source — from Task 2)
| Source | Verdict | Slots populated | Features mapped |
|---|---|---|---|
| 0_1_Introduction.md | NOT USABLE | none (redirect → 2.1) | — |
| 1-s2.0-S3051308126000021-main.md | PARTIALLY USABLE | Veterinarians, Exclusion | Features 1, 2 |
| 1236-1251.md | PARTIALLY USABLE | Clinic-Staff, Pet-Owners (roles, uncounted) | Feature 1 |
| 15189-Article Text-39763-2-10-20260328.md | HIGHLY USABLE | Veterinarians, Clinic-Staff, Pet-Owners (1/2/3/10) | Features 1, 2, 4 |
| 15_beyer.k-chomiak-orsa.i-pietrzykowski.z.md | PARTIALLY USABLE | Pet-Owners (n=102), Clinic-Staff (3 clinics) | Features 1, 4 |
| 169-175.docx | HIGHLY USABLE | Clinic-Staff, Veterinarians, Inclusion-Criteria | Features 1, 2, 4 |
| 3305160.3305164.md | PARTIALLY USABLE | Population seed, Triangulation seed | Features 1, 2, 5 |
| 450-462.docx | HIGHLY USABLE | Veterinarians, Clinic-Staff, Pet-Owners (role pathways; pooled UAT n=31) | Features 1, 2 |
| 776.md | PARTIALLY USABLE | Survey seed, Population seed (top-3 shortlist) | Features 1, 2, 4 |
| MG_2026_EurSafe26.md | PARTIALLY USABLE | Veterinarians (sectoral mix, n=21) | Feature 7 |
| Nablus-Vet-Care-Report.md | PARTIALLY USABLE | Veterinarians, Clinic-Staff (5-role architecture, n=0) | Features 1, 2, 6 |
| s13620-018-0123-3.md | HIGHLY USABLE | Veterinarians (n=38), Clinic-Staff (n=69 + routing) | Feature 7 |
| The_DeLone_and_McLean_Model_of_Information_Systems.md | NOT USABLE | none (redirect → 1.4) | — |
| VenkateshThongXu-JAIS2016-OpenAccess (1).md | NOT USABLE | none (redirect → 1.4) | — |
| VetBot.md | HIGHLY USABLE | Interview, Survey (Likert+SUS), Population (3/9/32) | Features 1, 2, 4, 7 |
| vol10-iss6-pg4336-4346-202606_pdf.md | HIGHLY USABLE | Staff, Owners, IT-Experts, Inclusion | Features 1, 2, 4 |
| WSN-211-2026-132-151.md | HIGHLY USABLE | Survey, Population (admin/staff/owners), Triangulation | Features 1, 2, 4 |

## Cross-source comparison
- Veterinarian stratum triangulated: Tukur (90.1%, n=152) + VetCareSys (2 vets) + Golden (38 PVPs) + Nablus (duty-mapped portal) + Morales (counted) + VetBot (3 purposive interviews + 9 licensed Likert evaluators) + Care for Paws (organization administrators). Staff triangulated: VetCareSys (3+1) + Golden (69 VNs + routing) + EliteVet (admin/doctor matrices) + Nablus (receptionist/accountant portals) + Care for Paws (staff respondents). Owners triangulated: VetCareSys (10) + Beyer (102 IDIs) + Morales + VetBot (32 SUS owners) + Vetconnect (respondent top-3 shortlist) + FurrySmart (respondent opinions) + Care for Paws (adopters/owners). No conflicts. Honest gaps: [Stratum-IT-Experts-ISO25010] still only from Morales (n=2) — all 4 new sources lack IT experts; [Inclusion-Criteria] only from Morales; full criterion rules must come from the methods plan.
- 169-175 adds a Malaysian staff-interview mechanism, a veterinarian user test, and a mixed staff/customer/student UX survey (n=102). It corroborates staff and veterinarian data collection but does not explicitly identify customers/students as pet owners and supplies no IT-expert or exclusion stratum.
- 450-462 adds doctor, helpdesk-staff, and pet-owner role pathways with a pooled UAT cohort (n=31). The three role-specific respondent counts and participant composition remain [NOT STATED], so the total must not be assigned to any stratum; it supplies no IT-expert, inclusion, or exclusion stratum.

## Section Verdict
- IN PROGRESS — 17 of 24 current-inbox sources judged; 14 usable (7 highly, 7 partially) with 36 grounded rows; 7 sources remain.

## Next up
- NEXT SECTION: 2.4 Sources of Data | NEXT SOURCE: `C-MALICDEM,+KIMBERLEY+P_Research+Article+Revised+3.md`
- Starter for new session (copy-paste):
```text
Read C:\Users\Administrator\Desktop\RESEARCH-OUTPUT\00_SECTION_EXTRACTION_ORCHESTRATOR_PROMPT.md, then extractor v7, then do single job: TARGET 2.4 Sources of Data × SOURCE C-MALICDEM,+KIMBERLEY+P_Research+Article+Revised+3.md. Standard depth. See Outputs/2.4_Sources_of_Data/_STATUS_2.4.md for queue.
```
