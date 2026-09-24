# 1.9.1 Related Literature — dataprivacy
> Source: `Sources/dataprivacy.md` | Date: 2026-09-25 | Depth: standard
> Verdict (Task 2): PARTIALLY USABLE
---
### Task 1 — Bibliographic Classification
- **Title**: Republic Act No. 10173 — Data Privacy Act of 2012
- **Authors**: Congress of the Philippines
- **Year**: 2012
- **Recency**: PASS (current statutory text; not an empirical claim)
- **Outlet**: Republic Act of the Philippines
- **DOI/URL**: [NOT FOUND]
- **Setting**: Local (Philippines) + proof "Republic of the Philippines Congress of the Philippines Metro Manila Fifteenth Congress Second Regular Session"
- **Design**: UNCLASSIFIED (statute)
- **APA7**: Republic Act No. 10173. (2012). *An Act Protecting Individual Personal Information in Information and Communications Systems in the Government and the Private Sector...*. Congress of the Philippines. [MISSING: official publication URL]
- **Fit**: Directly supplies Philippine statutory requirements for personal-information protection, lawful processing, security safeguards, breach response, and data-subject rights.

### Task 2 — Verdict
- **Verdict**: PARTIALLY USABLE (4 mechanisms, 1 slot)
- **Bullets**:
  - Why + recency: PASS as a current primary statutory text; the source states binding requirements rather than empirical findings.
  - Slots populated → Features: [Lit-Regulatory-Statutes-RA10173-RA9268] → Features 2, 4, 7.
  - Missing: [Lit-Veterinary-Informatics-Debate], [Lit-Industry-Standards], and [Lit-Thematic-Construct] are [NOT STATED]; RA 9268 is not reproduced in this source.
  - Panel use: grounds the privacy and security obligations that an AI-assisted veterinary workflow must disclose and operationalize.
  - Caveat: the statute governs personal information; veterinary records may also contain animal and owner data, so application to each field remains a transfer judgment.

### Task 3 — Extraction Bank
| # | Slot | Finding (mechanism + noun) | Condition (n, setting, baseline) | Quote ≤60w + Locator | Metric or [NOT STATED] | Use in TARGET |
|---|---|---|---|---|---|---|
| 1 | Related Literature-Lit-Regulatory-Statutes-RA10173-RA9268 | Consent is a specific, informed, documented condition for collecting and processing personal information | Philippine government and private-sector information and communications systems; statutory text | "Consent of the data subject refers to any freely given, specific, informed indication of will, whereby the data subject agrees to the collection and processing of personal information" (Republic Act No. 10173, Sec. 3(b)) | [NOT STATED] | [STATUTORY/PROVINCIAL] CarePaws will provide a documented consent path before processing identifiable pet-owner information in its client and clinical workflows [Features 2, 4] |
| 2 | Related Literature-Lit-Regulatory-Statutes-RA10173-RA9268 | Lawful processing requires a statutory basis, including contract, legal obligation, vital interests, or legitimate interests subject to rights limits | Philippine personal-information controller; no organizational baseline stated | "The processing of personal information shall be permitted only if not otherwise prohibited by law, and when at least one of the following conditions exists" (Republic Act No. 10173, Sec. 12) | [NOT STATED] | [STATUTORY/PROVINCIAL] CarePaws will document the lawful basis for each owner-information processing activity rather than infer permission from account creation [Features 2, 4, 7] |
| 3 | Related Literature-Lit-Regulatory-Statutes-RA10173-RA9268 | Security controls must be proportionate to data nature, processing risk, organizational complexity, best practices, and implementation cost | Personal-information controller; reasonable and appropriate organizational, physical, and technical measures | "The determination of the appropriate level of security under this section must take into account the nature of the personal information to be protected, the risks represented by the processing" (Republic Act No. 10173, Sec. 20(c)) | [NOT STATED] | [STATUTORY/PROVINCIAL] CarePaws will select access, network, monitoring, and incident controls according to the sensitivity and processing risk of each record class [Feature 2] |
| 4 | Related Literature-Lit-Regulatory-Statutes-RA10173-RA9268 | Suspected acquisition of sensitive information requires prompt notification to the Commission and affected data subjects when serious-harm risk is likely | Personal-information controller; breach circumstances and risk threshold stated by statute | "The personal information controller shall promptly notify the Commission and affected data subjects when sensitive personal information ... is reasonably believed to have been acquired by an unauthorized person" (Republic Act No. 10173, Sec. 20(f)) | [NOT STATED] | [STATUTORY/PROVINCIAL] CarePaws will define a breach-notification path for suspected unauthorized access to owner or clinical data [Features 2, 4] |
Excluded: [5] candidates omitted (definitions without a transfer mechanism, government-only access rules, criminal penalties, appropriations, and repealer provisions outside the target literature mechanism).
