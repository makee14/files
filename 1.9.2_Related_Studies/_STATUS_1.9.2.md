# STATUS — 1.9.2 Related Studies
> Extractor: `research_assistant_SECTION_EXTRACTOR_v7.md` | Depth default: standard | Updated: 2026-09-24

## Queue (source order — alphabetical)
- [x] DONE — `0_1_Introduction.md` — NOT USABLE
- [x] DONE — `1-s2.0-S3051308126000021-main.md` — PARTIALLY USABLE
- [x] DONE — `1236-1251.md` — HIGHLY USABLE
- [x] DONE — `15189-Article Text-39763-2-10-20260328.md` — HIGHLY USABLE
- [x] DONE — `15_beyer.k-chomiak-orsa.i-pietrzykowski.z.md` — PARTIALLY USABLE
- [x] DONE — `MG_2026_EurSafe26.md` — NOT USABLE
- [x] DONE — `Nablus-Vet-Care-Report.md` — HIGHLY USABLE
- [x] DONE — `s13620-018-0123-3.md` — PARTIALLY USABLE
- [x] DONE — `The_DeLone_and_McLean_Model_of_Information_Systems.md` — NOT USABLE
- [x] DONE — `VenkateshThongXu-JAIS2016-OpenAccess (1).md` — NOT USABLE
- [x] DONE — `vol10-iss6-pg4336-4346-202606_pdf.md` — HIGHLY USABLE
- [x] DONE — `3305160.3305164.md` — HIGHLY USABLE
- [x] DONE — `776.md` — PARTIALLY USABLE
- [x] DONE — `VetBot.md` — HIGHLY USABLE
- [x] DONE — `WSN-211-2026-132-151.md` — HIGHLY USABLE

## Progress
- Done: 15 / 15 | Highly: 7 | Partially: 4 | Not Usable: 4

## Results Log (one row per completed source — from Task 2)
| Source | Verdict | Slots populated | Features mapped |
|---|---|---|---|
| 0_1_Introduction.md | NOT USABLE | none (concept-only → 2.1) | — |
| 1-s2.0-S3051308126000021-main.md | PARTIALLY USABLE | Metric-Outcomes, Arch-Flaws | Features 1, 2 |
| 1236-1251.md | HIGHLY USABLE | Architecture ×2, Metric-Outcomes, Arch-Flaws | Features 1, 2, 6 |
| 15189-Article Text-39763-2-10-20260328.md | HIGHLY USABLE | Architecture, Metric-Outcomes ×2, Connectivity | Features 1, 2, 4 |
| 15_beyer.k-chomiak-orsa.i-pietrzykowski.z.md | PARTIALLY USABLE | Metric-Outcomes, Architecture | Features 1, 2, 4 |
| MG_2026_EurSafe26.md | NOT USABLE | none (ethics deliberation → 1.9.1/1.9.3) | — |
| Nablus-Vet-Care-Report.md | HIGHLY USABLE | Architecture ×2, Connectivity, Arch-Flaws | Features 1, 2, 4, 6 |
| s13620-018-0123-3.md | PARTIALLY USABLE | Metric-Outcomes (demand context) | Feature 7 |
| The_DeLone_and_McLean_Model_of_Information_Systems.md | NOT USABLE | none (concept-only → 1.4) | — |
| VenkateshThongXu-JAIS2016-OpenAccess (1).md | NOT USABLE | none (concept-only → 1.4) | — |
| vol10-iss6-pg4336-4346-202606_pdf.md | HIGHLY USABLE | Architecture, Metric-Outcomes, Arch-Flaws | Features 1, 2, 4, 6 |
| 3305160.3305164.md | HIGHLY USABLE | Architecture ×2, Metric-Outcomes, Arch-Flaws | Features 1, 2, 7 |
| 776.md | PARTIALLY USABLE | Architecture, Metric-Outcomes, Arch-Flaws (design-only, no build) | Features 1, 4 |
| VetBot.md | HIGHLY USABLE | Architecture, Metric-Outcomes ×2, Arch-Flaws | Features 1, 2, 4 |
| WSN-211-2026-132-151.md | HIGHLY USABLE | Architecture ×2, Metric-Outcomes, Arch-Flaws | Features 1, 2, 4 |

## Cross-source comparison
- Seven empirical builds now converge: Morales (three-tier + n=32 ISO), VetCareSys (web modules + n=16 Excellent means), EliteVet (PHP/MySQL + 69 Pass cases), Nablus (React/Node/PostgreSQL + JWT/RBAC), FurrySmart/Buot (Spiral MIS + PowerBI segmentation + n=45 total 4.3, Quezon City), VetBot (Flutter/Django/PostgreSQL/ChromaDB/Gemini 3 Flash + N=99 RAGAS + 9-vet 4.56 + 32-owner SUS 79.61, La Union), Care-for-Paws/Ganiron (web + mobile + NFC + N=60 FURPS web 4.72/mobile 4.71, Manila). No conflicts; all agree paper/walk-in baselines fail on retrieval/scheduling. Vetconnect/De Guzman (n=50 requirements means, design-only) corroborates demand without a build. Tukur (78.3% manual, n=152) and Beyer (30% queue waits, n=102) corroborate the baseline problem without builds. Giersberg (n=21 deliberation) and the three theory texts contribute nothing. Gap update: [Connectivity-Assumptions] now has VetBot (online-LLM) and Ganiron (NFC-compatible) witnesses plus prior VetCareSys/Nablus rows; [Hardware-Offline-Fallbacks] remains empty everywhere (Ganiron explicitly defers beyond NFC; VetBot has no offline path). No SUS outside VetBot; no latency-ms in any source.

## Section Verdict
- COMPLETE — 15 of 15 judged; 11 usable sources (7 highly, 4 partially) with 39 grounded rows; ready for drafting 1.9.2 from the seven builds, with Vetconnect/Tukur/Beyer/Golden as contrast witnesses.

## Next up
- None — queue empty for current inbox. Files added later become TODO on the next run.
