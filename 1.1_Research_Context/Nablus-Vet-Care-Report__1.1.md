# 1.1 Research Context — Nablus-Vet-Care-Report
> Source: `Sources/Nablus-Vet-Care-Report.md` | Date: 2026-09-24 | Depth: standard
> Verdict (Task 2): HIGHLY USABLE
---
### Task 1 — Bibliographic Classification
- **Title**: Nablus Vet Care: A Unified Solution for Veterinary Operations, Client Services, and Business Management
- **Authors**: Baker Razi Wael Yaeesh, Yousef Faed Mahmoud Salman (supervised by Dr. Hanal Abuzant)
- **Year**: 2026
- **Recency**: PASS (2016–2026)
- **Outlet**: Software Graduation Project, Department of Computer Engineering, An-Najah National University [MISSING: DOI/URL]
- **DOI/URL**: [MISSING: DOI/URL]
- **Setting**: Foreign (Palestine) + proof: "During the field visits, the authors surveyed 14 clinics" in "Nablus, Palestine" with the Palestinian Ministry of Agriculture registry
- **Design**: DSR Artifact (Waterfall; field visits to 14 clinics + semi-structured interviews + systems review; load/performance tests with scores [NOT STATED])
- **APA7**: Yaeesh, B. R. W., & Salman, Y. F. M. (2026). *Nablus Vet Care: A unified solution for veterinary operations, client services, and business management* (Unpublished bachelor's graduation project, supervised by H. Abuzant). Department of Computer Engineering, An-Najah National University. [MISSING: DOI/URL]
- **Fit**: Strong fieldwork-grounded 1.1 corroboration: 14-clinic survey documenting single-vet overload, memory-based routines, phone-only booking, and absent reminders — then a unified web/mobile build answering them.

### Task 2 — Verdict
- **Verdict**: HIGHLY USABLE (3 mechanisms, 3 slots)
- **Bullets (3–5)**:
  - Why this verdict + recency status: PASS (2026); 14-clinic fieldwork with three quoted context mechanisms; performance claims assert "high scores" without digits.
  - Slots populated → Features 1–7 mapping: [Macro-Digital-Transformation] → Features 1, 2, 4; [Micro-Clinical-Breaking-Points] → Features 1, 3, 4; [Meso-Rural-Provincial-Constraints] → Features 1, 2.
  - Missing slots / metrics this source cannot cover: [Manual-Ledger-Vulnerabilities] as a named slot is thin here (covered instead by memory-notebook routines under Meso); [Statutory-Imperatives-RA10173-RA9268] absent; no wait-time, loss-count, or Lighthouse digits (all [NOT STATED]).
  - Panel use (what attack this citation deflects): deflects "one vet can manage everything by memory" — 14 clinics show informal memory routines producing fragmentation, waste, and invisible performance.
  - Transfer risk / caveat: all system-demo data are declared 100% synthetic, so only the fieldwork observations (not screenshots or test outputs) transfer; Palestinian setting, not Philippine.

### Task 3 — Extraction Bank (1–4 rows max, min 1. Never pad.)
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote ≤60w + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Research Context-Macro-Digital-Transformation | Unified web/mobile system replacing manual paper workflows across records, appointments, and billing | 14 Nablus clinics, manual paper baseline | "many clinics still rely on manual, paper-based workflows for managing records, appointments, and billing, increasing the risk of errors, inefficiencies, and poor client communication" (Yaeesh & Salman 2026, Ch. 1, para. 5) | 14 clinics surveyed / [NOT STATED: no error counts] | [CORROBORATION] CarePaws will unify the same three paper workflows — records, scheduling, billing — into one auditable system [Features 1, 2, 6] |
| 2 | Research Context-Micro-Clinical-Breaking-Points | Phone-or-in-person booking within limited hours plus inconsistent or absent vaccination reminders plus fragmented history access | Same 14 clinics, phone/manual baseline | "appointments must typically be booked by phone or in person during limited clinic hours, vaccination reminders are inconsistent or entirely absent, and access to their pets' medical history is fragmented or unavailable" (Yaeesh & Salman 2026, Ch. 1, para. 9) | [NOT STATED: no booking volume, no reminder coverage pct] | [CORROBORATION] CarePaws will add self-booking, automated vaccination reminders with certificates, and owner-visible histories [Features 1, 3, 4] |
| 3 | Research Context-Meso-Rural-Provincial-Constraints | Single-veterinarian owner-clinician-manager model with memory/notebook routines producing fragmentation and waste | Same 14 clinics, single-vet baseline | "the overwhelming majority of clinics operate under a single-veterinarian model, where one veterinarian serves as the owner, primary clinician, and business manager" (Yaeesh & Salman 2026, Ch. 1, para. 3) | 14 clinics / [NOT STATED: no hours, no revenue figures] | [PROVINCIAL] CarePaws will design for the same one-vet-does-everything reality at PetCare, offloading scheduling, reminders, and stock/invoice chores to staff-safe automation [Features 1, 4, 5, 6] |
Excluded: [2] candidates omitted (synthetic screenshot/test outputs — declared 100% fake, unusable as evidence; $70k–150k capital figures — investment context, not a 1.1 slot mechanism).