# Project opportunity: Cedar Valley Regional Medical Center — Epic Clinical and Revenue Cycle Go-Live

**Client:** Cedar Valley Regional Medical Center (fictional), 180-bed community hospital with 14 outpatient clinics, Boise, Idaho
**Engagement type:** Epic implementation (EpicCare Inpatient, EpicCare Ambulatory, Prelude, Resolute Hospital Billing) replacing MEDITECH Expanse
**Platforms:** Epic
**Workstreams:** Patient record management; Billing & revenue cycle
**Start date:** 2026-12-07
**Duration:** 14 months (go-live at month 11, 3 months stabilization)
**Location / travel:** Hybrid, client site in Boise 2 weeks per month; on site daily for 6 weeks around go-live
**Partner sponsor:** (fictional) R. Okafor
**Status:** Signed SOW, staffing due 2026-11-20

## Context

Cedar Valley is leaving MEDITECH Expanse for Epic to align with the regional health system it joined in 2025. Clinicians currently chart in two systems, and nurses report 40+ minutes per shift lost to duplicate documentation. The CMIO wants inpatient and ambulatory documentation on a single EpicCare build before the next Joint Commission survey.

Revenue cycle is the CFO's priority: discharged-not-final-billed (DNFB) days average 9.4 and registration-related denials are 6% of claims. The target is DNFB under 5 days and registration denials under 2% within 90 days of go-live.

## Roles to staff

Tailored from the standard staffing plan (staffing_plan.xlsx, 2026-10-23). Phase columns are planned FTE; Allocation is the plan's Avg FTE as a percentage. Skill proficiency is on a 1-5 scale.

| # | Plan ref | Role | Pod | Level | Location | Must-have skills | Nice-to-have | Discovery and design | Build | Test | Deploy and hypercare | Allocation |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| R1 | 1 | Program manager leader | Shared | Senior Manager | Onshore | Healthcare program delivery (4+), multi-vendor governance (4+), Epic hospital go-live leadership for EpicCare and Resolute HB (4+) | MEDITECH-to-Epic conversion, PMP | 1 | 1 | 1 | 1 | 100% |
| R2 | 2 | Solution architect | Shared | Manager or Senior Manager | Onshore | End-to-end solution design (4+), Epic touchpoints across EpicCare Inpatient/Ambulatory/Prelude/Resolute HB (4+), discovery leadership (4+) | Epic Community Connect or shared-instance alignment with a parent health system | 1 | 1 | 0.5 | 0.5 | 75% |
| R3 | 4 | Integration architect (Epic interoperability) | Shared | Manager | Onshore | HL7 v2 interfaces (4+), FHIR (3+), Epic APIs and Bridges interface design (4+), middleware patterns (4+) | MEDITECH interface decommissioning, event-driven integration, Epic Bridges certification | 1 | 1 | 0.5 | 0.25 | 68.75% |
| R4 | 5 | Data architect | Shared | Senior Consultant or Manager | Onshore | Patient identity matching and MPI cleanup (4+), data migration strategy for MEDITECH Expanse to Epic (4+), analytics with Clarity/Caboodle for DNFB and denial KPIs (3+) | Epic Cogito certification, legacy data archiving | 0.5 | 1 | 0.5 | 0.25 | 56.25% |
| R5 | 7 | Epic application analyst | Billing & revenue cycle | Senior Consultant | Onshore | Epic Resolute Hospital Billing certification - current (5+), Epic Prelude certification - current (4+), registration-to-billing workflow build (4+) | Epic Cadence certification, real-time eligibility (270/271) setup | 1 | 1 | 0.5 | 0.5 | 75% |
| R6 | 9 | Business analyst, patient care | Patient record management | Consultant or Senior Consultant | Onshore | Care coordination and care plan requirements (3+), inpatient and ambulatory documentation workflows in EpicCare (3+), scheduling workflows (3+) | Nursing background, Joint Commission documentation standards | 1 | 1 | 0.5 | 0.25 | 68.75% |
| R7 | 10 | Business analyst, billing and revenue | Billing & revenue cycle | Senior Consultant | Onshore | Revenue cycle process design (4+), patient estimates and payments (3+), Epic billing touchpoints from Prelude to Resolute HB (4+) | DNFB reduction work, HFMA CRCR | 1 | 1 | 0.5 | 0.25 | 68.75% |
| R8 | adapted from 15 | Epic clinical lead, EpicCare Inpatient and Ambulatory | Patient record management | Senior Consultant | Onshore | EpicCare Inpatient and Ambulatory build leadership (4+), Epic Inpatient or Ambulatory certification - current (5+), care management and nursing workflow design (4+) | ClinDoc and Stork experience, RN background | 1 | 1 | 0.5 | 0.5 | 75% |
| R9 | adapted from 16 | Epic analyst, EpicCare Inpatient (ClinDoc) | Patient record management | Consultant | Offshore | EpicCare Inpatient ClinDoc build (3+), Epic Inpatient certification - current (4+), build and unit test in synthetic-data environments (3+) | Flowsheet and navigator build, Stork | 0 | 1 | 0.5 | 0 | 37.5% |
| R10 | adapted from 17 | Epic analyst, EpicCare Ambulatory | Patient record management | Consultant | Offshore | EpicCare Ambulatory build (3+), Epic Ambulatory certification - current (4+), clinic visit and scheduling workflow build (3+) | Specialty clinic content, Cadence exposure | 0 | 1 | 0.5 | 0 | 37.5% |
| R11 | adapted from 18 | Epic Resolute HB lead | Billing & revenue cycle | Senior Consultant | Onshore | Resolute Hospital Billing build leadership (4+), Epic Resolute HB certification - current (5+), charge capture and CDM reconciliation (4+), claims and payment integration (3+) | DNFB reduction work, claims scrubber configuration | 1 | 1 | 0.5 | 0.5 | 75% |
| R12 | adapted from 19 | Epic analyst, Resolute HB | Billing & revenue cycle | Consultant | Offshore | Resolute HB claim edit and workqueue build (3+), Epic Resolute HB certification - current (4+), payment posting configuration (3+) | 835 remittance automation, Prelude exposure | 0 | 1 | 0.5 | 0 | 37.5% |
| R13 | 20 | Integration developer, billing and revenue | Billing & revenue cycle | Consultant | Offshore | APIs and middleware (3+), FHIR resources with synthetic data only (3+), Epic Bridges billing interfaces such as 837/835 and 270/271 (3+) | Clearinghouse onboarding, Epic Bridges certification | 0 | 1 | 0.5 | 0 | 37.5% |
| R14 | 21 | Integration developer (FHIR/HL7, middleware) | Shared | Senior Consultant | Onshore | FHIR (3+), HL7 v2 (4+), middleware build (4+), Epic interface testing (4+) | Epic Bridges certification, MEDITECH interface experience | 0 | 1 | 1 | 0.5 | 62.5% |
| R15 | 22 | Data migration developer | Shared | Consultant | Onshore | ETL (4+), data loads and reconciliation (4+), identity matching (3+), MEDITECH Expanse extraction and Epic conversion loads (3+) | Chart abstraction and ADT conversion | 0 | 1 | 0.5 | 1 | 62.5% |
| R16 | 24 | Test lead | Shared | Senior Consultant | Onshore | Test strategy (4+), SIT and UAT management (4+), defect governance (4+), Epic integrated testing for EpicCare and Resolute HB (3+) | Epic go-live dress rehearsals, technical dress rehearsal | 0.5 | 1 | 1 | 0.5 | 75% |
| R17 | 26 | Test data and environment analyst | Shared | Consultant | Onshore | Synthetic and de-identified data (4+), environment readiness (3+), Epic test patient and test environment setup (3+) | Epic environment refresh coordination | 0 | 1 | 1 | 0.25 | 56.25% |
| R18 | 28 | Functional tester 1 | Shared | Analyst or Consultant | Offshore | Functional and regression testing (3+), synthetic data (3+), EpicCare and Resolute HB workflow testing (3+) | Epic integrated testing scripts | 0 | 0.5 | 1 | 0.25 | 43.75% |
| R19 | 29 | Functional tester 2 | Shared | Analyst or Consultant | Offshore | Functional and regression testing (3+), synthetic data (3+), EpicCare and Resolute HB workflow testing (3+) | Epic integrated testing scripts | 0 | 0.5 | 1 | 0.25 | 43.75% |
| R20 | 30 | OCM and training lead | Shared | Senior Consultant or Manager | Onshore | Clinical adoption (4+), training design (4+), communications (4+), Epic credentialed trainer program and go-live command center support (3+) | Epic Principal Trainer certification, at-the-elbow support planning | 0.5 | 0.25 | 0.5 | 1 | 56.25% |

**Totals (20 roles: 14 onshore, 6 offshore):** Discovery and design 9.5 FTE | Build 18.25 FTE | Test 13 FTE | Deploy and hypercare 7.75 FTE | Average 12.125 FTE. **Onshore:** Discovery and design 9.5, Build 13.25, Test 9, Deploy and hypercare 7.25 FTE (average 9.75). **Offshore:** Discovery and design 0, Build 5, Test 4, Deploy and hypercare 0.5 FTE (average 2.375).

## Removed from the standard plan

- 3. Technical architect (Salesforce) — Salesforce-specific role; Cedar Valley is an Epic-only implementation. No Salesforce org or Health Cloud data model in scope.
- 6. Security architect — Built around Salesforce Shield, encryption and field-level security; Epic user security (templates and security classes) is configured by the Epic analysts with the client's Epic security coordinator.
- 8. Business analyst, CRM — CRM workstream is not in this project.
- 11. UX designer — Epic screens are vendor-controlled; clinician workflow design is covered by the patient care BA (R6) and Epic clinical lead (R8).
- 12. Dev lead, CRM — CRM workstream is not in this project.
- 13. Salesforce developer, CRM 1 — CRM workstream is not in this project.
- 14. Salesforce developer, CRM 2 — CRM workstream is not in this project.
- 23. DevOps / release engineer — Salesforce-style CI/CD does not apply; Epic build migration (Data Courier) and environment management are run by the client's Epic technical team.
- 25. Test automation engineer — Salesforce-specific role; Cedar Valley is an Epic-only implementation. Plan role is Salesforce test automation.
- 27. Integration tester (Epic to Salesforce) — Epic-to-Salesforce role; there is no Salesforce in scope. Onshore Epic interface testing is owned by the integration developer (R14) under the test lead (R16).

## Client-provided roles

| Role | Notes |
|---|---|
| Executive sponsor | Decision authority and escalation (CMIO for clinical, CFO for revenue cycle) |
| Product owner, one per pod (2) | Backlog ownership and acceptance for Patient record management and Billing & revenue cycle |
| Clinical informaticist or clinical SME | Clinical workflow validation for inpatient nursing and ambulatory documentation |
| Client Epic analysts and Epic integration team | Work alongside the Epic application analyst (R5) and Epic build roles; own Data Courier migrations and Epic security |
| Compliance and privacy officer | Sign-off on PHI access model and data handling, including MEDITECH conversion extracts |

## Constraints

- R2, R3, R4 and R5 must hold current Epic certifications at start; the client cannot sponsor new certifications, and Epic's certification lead time would push past the build window.
- Go-live freeze runs from month 10 to month 12: no time off or roll-offs approved for any role during that window.
- PHI access is limited to client-issued laptops over the client VPN; all staff complete Cedar Valley HIPAA training before receiving Epic environment access.
- Fixed-fee budget; the partner wants no more than two Senior Consultants on the team.
- Standard plan offshore rule: offshore roles (R9, R10, R12, R13, R18, R19) work only with synthetic or de-identified data; onshore is required for any role that touches production PHI, runs client workshops, or owns Epic integration testing.

## Plan conflicts

1. **Senior Consultant cap.** The partner allows no more than two Senior Consultants, but the tailored plan has six Senior Consultant roles (R5, R7, R8, R11, R14, R16) and three roles whose range includes Senior Consultant (R4, R6, R20). **Recommended resolution:** Keep the two certified build leads as the only Senior Consultants: R8 Epic clinical lead and R11 Epic Resolute HB lead. Staff R5, R7, R14 and R6 at Consultant (with current certifications where required), R16 at Consultant with prior Epic integrated-testing lead experience, and R4 and R20 at Manager. If a Consultant-level test lead is judged too risky for a hospital go-live, get the partner's written exception before the staffing deadline rather than over-staffing silently.
2. **Epic certification rule.** The constraint names R2-R5 from the original role list (Clinical Documentation Lead, Ambulatory Analyst, Patient Access Analyst, Hospital Billing Lead). In this table those duties sit with R8, R10, R5 and R11, and the adapted Epic build roles R9 and R12 need current certifications too. The client cannot sponsor certification, and the plan's Risks sheet calls the Epic application analyst the hardest role to fill. **Recommended resolution:** Apply the current-certification requirement to R5, R8, R9, R10, R11 and R12 and confirm certificates before proposing names. If certified offshore candidates for R9, R10 or R12 cannot be found, staff them onshore at the same level and FTE (higher cost) instead of proposing uncertified staff.
3. **Go-live freeze (months 10-12) vs plan roll-offs.** Plan FTE drops to 0 in Deploy and hypercare for R9, R10, R12 and R13, so those roles would roll off inside the freeze window. **Recommended resolution:** Fix their roll-off dates before month 10, after test exit. If test runs into month 10, keep them at 0.25 FTE through month 12 for defect fixes. Reductions in allocation are fine during the freeze; roll-offs are not.
4. **PHI access via client-issued laptops and VPN vs offshore Epic build roles (R9, R10, R12, R13, R18, R19).** Epic build environments are reached only through the client VPN on client laptops. **Recommended resolution:** Limit offshore roles to Epic build and test environments with synthetic or de-identified patients, on client-issued laptops over the client VPN after Cedar Valley HIPAA training. If the client will not ship laptops outside the US, move those roles onshore at the same level and FTE.
