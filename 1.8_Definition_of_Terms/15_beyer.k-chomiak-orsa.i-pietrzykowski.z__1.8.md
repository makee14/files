# 1.8 Definition of Terms — 15_beyer.k-chomiak-orsa.i-pietrzykowski.z
> Source: `Sources/15_beyer.k-chomiak-orsa.i-pietrzykowski.z.md` | Date: 2026-09-24 | Depth: standard
> Verdict (Task 2): PARTIALLY USABLE
---
### Task 1 — Bibliographic Classification
- **Title**: Digital Transformation and Business Process Improvement in Veterinary Clinics
- **Authors**: Karolina Beyer, Iwona Chomiak-Orsa, Zbigniew Pietrzykowski, Dominik Rozkrut
- **Year**: 2025
- **Recency**: PASS (2016–2026)
- **Outlet**: 28th European Conference on Artificial Intelligence (ECAI 2025), Intelligent Management Workshop
- **DOI/URL**: 10.18276/978-83-8419-028-9-15
- **Setting**: Foreign + "analysis of three veterinary clinics in Szczecin" + "102 in-depth interviews (IDI) conducted"
- **Design**: Qualitative Case (102 pet-owner IDIs + 3-clinic observation/interviews)
- **APA7**: Beyer, K., Chomiak-Orsa, I., Pietrzykowski, Z., & Rozkrut, D. (2025). Digital transformation and business process improvement in veterinary clinics. In *28th European Conference on Artificial Intelligence (ECAI 2025), Intelligent Management Workshop*. https://doi.org/10.18276/978-83-8419-028-9-15
- **Fit**: Defines two operationalizable pairs — animal treatment facility (statutory concept vs equipped-premises operation) and appointment scheduling (concept vs online/reminder operation) — both glossable for CarePaws scope terms.

### Task 2 — Verdict
- **Verdict**: PARTIALLY USABLE (2 term pairs)
- **Bullets**:
  - Why + recency: PASS (2025); both terms carry a stated definition plus an observable operational form.
  - Slots populated → Features: [Term-Conceptual-Definition] + [Term-Operational-Definition] for "veterinary facility" and "appointment scheduling" → Features 1, 7.
  - Missing: the other 8 locked terms (all [NOT STATED]).
  - Panel use: anchors "clinic" to a statutory definition and "scheduling" to online/reminder behavior, not adjectives.
  - Caveat: Polish statute, not RA 9268; transfer the definition structure, not the jurisdiction.

### Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Definition of Terms-Term-Conceptual-Definition | Animal treatment facility: statutory establishment for veterinary services with matched premises and equipment | Polish Animal Treatment Facilities Act, Art. 1.1 | "an animal health establishment is an establishment dedicated to the provision of veterinary medicine services, equipped with assets such as premises, apparatus and appropriate equipment" (Beyer et al. 2025, Background, para. 3) | [NOT STATED: facility counts] | [STATUTORY/PROVINCIAL] CarePaws will define the clinic conceptually as a statutory service establishment with matched premises and equipment [Feature 7] |
| 2 | Definition of Terms-Term-Operational-Definition | Animal treatment facility: in CarePaws, classified unit by size and service nature served only by authorised vets | Same statute, Art. 2.2 and 4.1 | "It should be emphasised that veterinary services may only be provided by authorised veterinarians (Article 2.2 of the Animal Health Establishment Act)" (Beyer et al. 2025, Background, para. 3) | Approx. 7,500 Polish units / [NOT STATED: clinic staffing] | [STATUTORY/PROVINCIAL] CarePaws will define the clinic operationally as a classified unit served only by authorised veterinarians [Feature 7] |
| 3 | Definition of Terms-Term-Conceptual-Definition | Appointment scheduling: advance booking of visits through digital or traditional channels | Three Szczecin clinics, mixed channels | "All three clinics require appointments to be made in advance, utilizing a mix of digital and traditional communication methods" (Beyer et al. 2025, Case Study, para. 1) | 3 clinics / [NOT STATED: booking volumes] | [CORROBORATION] CarePaws will define scheduling conceptually as advance booking through named channels [Feature 1] |
| 4 | Definition of Terms-Term-Operational-Definition | Appointment scheduling: in CarePaws, online booking with vaccination reminders and telemedicine options | 102 pet-owner IDIs, 17-question guide | "to arrange appointments online, receive reminders for vaccinations or regular check-ups, and access telemedicine consultations" (Beyer et al. 2025, Results, para. 3) | 12% online booking; 63.4% no reminders / [NOT STATED: clinic rates] | [CORROBORATION] CarePaws will define scheduling operationally as online booking with vaccination reminders [Feature 1] |
Excluded: [1] candidate omitted (BPMN mapping — method term for 2.2, not a 1.8 locked term).
