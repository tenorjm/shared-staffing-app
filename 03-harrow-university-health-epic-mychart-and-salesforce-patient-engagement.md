# Project opportunity: Harrow University Health — Epic MyChart and Salesforce Patient Engagement Integration

**Client:** Harrow University Health (fictional), academic medical center with a 950-bed flagship hospital, 3 community hospitals and 120 clinics, Nashville, Tennessee
**Engagement type:** Epic patient access optimization (Cadence, MyChart) and Salesforce Health Cloud patient engagement build, integrated through MuleSoft
**Platforms:** Epic and Salesforce (integrated via MuleSoft)
**Workstreams:** CRM (patient engagement, contact center, outreach); Patient record management (scheduling, patient portal)
**Start date:** 2027-02-01
**Duration:** 18 months (3 releases)
**Location / travel:** Hybrid, client site in Nashville 3 days per week; integration roles may be remote 4 days per week
**Partner sponsor:** (fictional) S. Feldman
**Status:** Signed SOW for Release 1, Releases 2-3 contingent; staffing due 2027-01-08

## Context

Harrow has been on Epic since 2015, but its central scheduling center runs on a separate CRM that agents toggle out of, and patients receive uncoordinated messages from MyChart, the CRM and three marketing tools. Third-next-available appointment for new patients is 41 days, and only 52% of active patients are on MyChart.

The engagement replaces the legacy CRM with Health Cloud and Service Cloud for the 300-seat access center, keeps Epic as the system of record for schedules and clinical data, and syncs patients, appointments and referrals through a MuleSoft layer using Epic's FHIR R4 and HL7v2 interfaces. Goals: MyChart activation to 70%, new-patient third-next-available to 21 days, and a 25% cut in agent handle time within 12 months.

## Roles to staff

Tailored from the standard staffing plan (staffing_plan.xlsx, 2026-10-23). Phase columns are planned FTE; Allocation is the plan's Avg FTE as a percentage. Skill proficiency is on a 1-5 scale.

| # | Plan ref | Role | Pod | Level | Location | Must-have skills | Nice-to-have | Discovery and design | Build | Test | Deploy and hypercare | Allocation |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| R1 | 1 | Program manager leader | Shared | Senior Manager | Onshore | Healthcare program delivery (5+), multi-vendor governance across Epic and Salesforce and MuleSoft (4+), Epic and Salesforce programs (4+) | Academic medical center experience, PMP | 1 | 1 | 1 | 1 | 100% |
| R2 | 2 | Solution architect | Shared | Manager or Senior Manager | Onshore | End-to-end solution design (4+), Health Cloud and Service Cloud (4+), Epic touchpoints for Cadence and MyChart over FHIR R4 (4+), discovery leadership (4+) | Salesforce Application Architect, prior Epic-to-Salesforce integration delivery | 1 | 1 | 0.5 | 0.5 | 75% |
| R3 | 3 | Technical architect (Salesforce) | Shared | Manager | Onshore | Salesforce platform architecture (4+), Health Cloud data model (4+), sharing (4+), scale for a 300-seat Service Cloud access center (4+) | Data Cloud, Service Cloud Voice | 1 | 1 | 0.5 | 0.5 | 75% |
| R4 | 4 | Integration architect (Epic interoperability) | Shared | Manager | Onshore | FHIR R4 (4+), HL7 v2 (4+), Epic APIs (4+), MuleSoft Anypoint middleware patterns (5+), event-driven integration (3+) | MuleSoft Certified Integration Architect, Epic Bridges certification | 1 | 1 | 0.5 | 0.25 | 68.75% |
| R5 | 5 | Data architect | Shared | Senior Consultant or Manager | Onshore | Patient identity matching across Epic and Health Cloud (4+), data migration strategy from the legacy CRM (4+), Data Cloud identity resolution (3+), analytics (3+) | Salesforce Data Cloud Consultant certification | 0.5 | 1 | 0.5 | 0.25 | 56.25% |
| R6 | 6 | Security architect | Shared | Senior Consultant | Onshore | PHI access model (4+), Shield Platform Encryption and Event Monitoring (4+), field-level security (4+), audit (4+) | HITRUST assessments, Salesforce Sharing and Visibility Architect | 0.5 | 0.25 | 0.25 | 0.25 | 31.25% |
| R7 | 8 | Business analyst, CRM | CRM | Consultant or Senior Consultant | Onshore | Requirements and user stories (3+), patient engagement and access-center service processes (4+), Service Cloud and Marketing Cloud outreach processes (3+) | Central scheduling center redesign | 1 | 1 | 0.5 | 0.25 | 68.75% |
| R8 | 9 | Business analyst, patient care | Patient record management | Consultant or Senior Consultant | Onshore | Care coordination (3+), scheduling workflows including Cadence decision trees and referrals (4+), MyChart patient portal and activation workflows (3+) | Academic medical center access-center experience | 1 | 1 | 0.5 | 0.25 | 68.75% |
| R9 | 11 | UX designer | Shared | Senior Consultant | Onshore | Patient and staff experience design (4+), accessibility (4+), Service Cloud agent console and MyChart activation journey design (3+) | Omnichannel patient messaging design | 1 | 0.5 | 0 | 0 | 37.5% |
| R10 | 12 | Dev lead, CRM | CRM | Senior Consultant | Onshore | Salesforce development lead (4+), Health Cloud (4+), Service Cloud and Omni-Channel (4+) | Service Cloud Voice, Salesforce Platform Developer II | 1 | 1 | 0.5 | 0.5 | 75% |
| R11 | 13 | Salesforce developer, CRM 1 | CRM | Consultant | Offshore | Apex (4+), LWC (4+), Flow (4+), Health Cloud (3+) | Salesforce Platform Developer I, Data Cloud | 0 | 1 | 0.5 | 0 | 37.5% |
| R12 | 14 | Salesforce developer, CRM 2 | CRM | Consultant | Offshore | Apex (3+), LWC (3+), Flow (4+), Marketing Cloud Journey Builder and AMPscript (3+) | Experience Cloud, MyChart activation campaigns | 0 | 1 | 0.5 | 0 | 37.5% |
| R13 | adapted from 15 | Epic Cadence/MyChart lead | Patient record management | Senior Consultant | Onshore | Cadence template and decision tree build (4+), MyChart open scheduling and activation workflows (4+), Epic Cadence and MyChart certifications - current (5+) | MyChart ticket scheduling, Fast Pass setup | 1 | 1 | 0.5 | 0.5 | 75% |
| R14 | adapted from 16 | Epic analyst, Cadence | Patient record management | Consultant | Offshore | Cadence scheduling build (3+), Epic Cadence certification - current (4+), referral and appointment data exposed through Epic FHIR R4 (3+) | Referral workqueues, Epic Interconnect | 0 | 1 | 0.5 | 0 | 37.5% |
| R15 | adapted from 17 | Epic analyst, MyChart | Patient record management | Consultant | Offshore | MyChart build (3+), Epic MyChart certification - current (4+), MyChart scheduling and activation configuration (3+) | MyChart ticket scheduling, Fast Pass | 0 | 1 | 0.5 | 0 | 37.5% |
| R16 | 21 | Integration developer (FHIR/HL7, middleware) | Shared | Senior Consultant | Onshore | FHIR R4 (4+), HL7 v2 (4+), MuleSoft middleware build with DataWeave (4+), Epic interface testing (4+) | MuleSoft Certified Developer Level 1, Epic Interconnect, Epic Bridges | 0 | 1 | 1 | 0.5 | 62.5% |
| R17 | 22 | Data migration developer | Shared | Consultant | Onshore | ETL (4+), data loads (4+), reconciliation (3+), identity matching from the legacy CRM to Health Cloud (3+) | Salesforce Bulk API, Data Cloud ingestion | 0 | 1 | 0.5 | 1 | 62.5% |
| R18 | 23 | DevOps / release engineer | Shared | Senior Consultant | Offshore | CI/CD for Salesforce and MuleSoft (4+), source control (4+), environment strategy (4+), release management across 3 releases (4+) | Copado or Gearset, MuleSoft CloudHub deployment | 0.25 | 1 | 1 | 1 | 81.25% |
| R19 | 24 | Test lead | Shared | Senior Consultant | Onshore | Test strategy (4+), SIT and UAT management (4+), defect governance (4+), Epic-to-Salesforce end-to-end test planning (3+) | Multi-release regression planning | 0.5 | 1 | 1 | 0.5 | 75% |
| R20 | 25 | Test automation engineer | Shared | Senior Consultant | Offshore | Salesforce test automation (4+), regression suites (4+), MuleSoft API test automation (3+) | Provar or Copado Robotic Testing | 0 | 1 | 1 | 0.25 | 56.25% |
| R21 | 26 | Test data and environment analyst | Shared | Consultant | Onshore | Synthetic and de-identified data (4+), environment readiness (4+), aligned Epic and Salesforce test environments (3+) | Epic test patient creation | 0 | 1 | 1 | 0.25 | 56.25% |
| R22 | 27 | Integration tester (Epic to Salesforce) | Shared | Consultant | Onshore | End-to-end interface testing with PHI-bound data (4+), Epic Cadence/MyChart to Salesforce flows via MuleSoft (3+), SQL data validation against Clarity (3+) | Prior Epic-to-Salesforce integration delivery | 0 | 0.5 | 1 | 0.5 | 50% |
| R23 | 28 | Functional tester 1 | Shared | Analyst or Consultant | Offshore | Functional and regression testing (3+), synthetic data (3+), Service Cloud console and MyChart workflow testing (3+) | Marketing Cloud journey testing | 0 | 0.5 | 1 | 0.25 | 43.75% |
| R24 | 29 | Functional tester 2 | Shared | Analyst or Consultant | Offshore | Functional and regression testing (3+), synthetic data (3+), Service Cloud console and MyChart workflow testing (3+) | Marketing Cloud journey testing | 0 | 0.5 | 1 | 0.25 | 43.75% |
| R25 | 30 | OCM and training lead | Shared | Senior Consultant or Manager | Onshore | Clinical adoption (4+), training design for a 300-seat access center (4+), communications (4+) | MyChart activation campaigns, contact center change management | 0.5 | 0.25 | 0.5 | 1 | 56.25% |

**Totals (25 roles: 17 onshore, 8 offshore):** Discovery and design 11.25 FTE | Build 21.5 FTE | Test 16.25 FTE | Deploy and hypercare 9.75 FTE | Average 14.6875 FTE. **Onshore:** Discovery and design 11, Build 14.5, Test 10.25, Deploy and hypercare 8 FTE (average 10.9375). **Offshore:** Discovery and design 0.25, Build 7, Test 6, Deploy and hypercare 1.75 FTE (average 3.75).

Adapted roles: on Harrow, Patient record management (scheduling and patient portal) runs in Epic, which stays the system of record for schedules. So the plan's Salesforce patient care roles (rows 15-17) are adapted to their Epic Cadence/MyChart equivalents at the same level, location and FTE. Salesforce scope sits in the CRM pod.

Epic-to-Salesforce references: propose R2, R4, R16 and R22 as the named roles with prior Epic-to-Salesforce integration delivery (at least three required by the CIO).

## Removed from the standard plan

- 7. Epic application analyst — Billing & revenue cycle workstream is not in this project. Its Cadence and MyChart skills are covered by the adapted Epic roles R13-R15.
- 10. Business analyst, billing and revenue — Billing & revenue cycle workstream is not in this project.
- 18. Dev lead, billing and revenue — Billing & revenue cycle workstream is not in this project.
- 19. Salesforce developer, billing and revenue — Billing & revenue cycle workstream is not in this project.
- 20. Integration developer, billing and revenue — Billing & revenue cycle workstream is not in this project.

## Client-provided roles

| Role | Notes |
|---|---|
| Executive sponsor | Decision authority and escalation (CIO) |
| Product owner, one per pod (2) | Backlog ownership and acceptance for CRM and Patient record management |
| Clinical informaticist or clinical SME | Clinical workflow validation for scheduling decision trees, referral rules and MyChart open scheduling |
| Client Epic analysts and Epic integration team | Work alongside the adapted Epic roles (R13-R15) and the integration architect (R4); own Epic build migrations and the May 2027 upgrade |
| Compliance and privacy officer | Sign-off on PHI access model and data handling, including Shield, event monitoring and BAA addenda |

## Constraints

- Harrow's Epic upgrade freeze runs 2027-05-01 to 2027-05-31; no Epic build migrations or interface changes during that window, which Release 1 planning must absorb.
- All Salesforce orgs holding PHI must use Shield Platform Encryption and event monitoring; Harrow requires a signed BAA addendum and HIPAA attestation for every team member.
- R3 must hold current Epic certifications at start; Harrow will not sponsor certification and Epic training lead time is 4-6 months.
- At least three roles must have delivered an Epic-to-Salesforce integration before; the CIO asked for named references.
- Standard plan offshore rule: offshore roles (R11, R12, R14, R15, R18, R20, R23, R24) work only with synthetic or de-identified data; onshore is required for any role that touches production PHI, runs client workshops, or owns Epic integration testing.

## Plan conflicts

1. **Epic upgrade freeze (2027-05-01 to 2027-05-31) vs plan Build phase.** With about 10 weeks of discovery from 2027-02-01, Release 1 build starts mid-April. The plan has the Epic build roles (R13, R14, R15) and integration roles (R4, R16) at full Build FTE through May. **Recommended resolution:** In May, Epic roles build and unit test only in the Epic build environment, with no migrations, and integration roles build MuleSoft flows against mocked Epic FHIR/HL7 endpoints. Migrations and interface changes resume in June, after the upgrade regression. Plan Salesforce-side CRM build first in the Release 1 sprint order.
2. **Epic certification.** R3 in the constraint is the original Epic Cadence / MyChart Lead, which is R13 in this table. The adapted Epic analysts R14 and R15 also need current Cadence and MyChart certification. Harrow will not sponsor certification, lead time is 4-6 months, and certified offshore Epic analysts are scarce. **Recommended resolution:** Require current certifications for R13, R14 and R15 at start. If certified offshore candidates are not available, staff R14 and/or R15 onshore at the same level and FTE (on site in Nashville 3 days per week). Do not propose uncertified Epic staff.
