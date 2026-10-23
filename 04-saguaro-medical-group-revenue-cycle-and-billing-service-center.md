# Project opportunity: Saguaro Medical Group — Revenue Cycle and Billing Service Center

**Client:** Saguaro Medical Group (fictional), 420-provider multi-specialty physician group with 38 clinics and 4 ambulatory surgery centers, Phoenix, Arizona
**Engagement type:** Epic Resolute Professional Billing optimization and Salesforce Service Cloud billing service center, integrated through MuleSoft
**Platforms:** Epic and Salesforce (integrated via MuleSoft)
**Workstreams:** Billing & revenue cycle (charge capture, claims, denials, collections); CRM (contact center)
**Start date:** 2027-03-15
**Duration:** 10 months
**Location / travel:** Hybrid, client site in Phoenix (Scottsdale admin office) 2 days per week
**Partner sponsor:** (fictional) M. Castellanos
**Status:** Shortlisted in RFP, orals on 2027-01-20; staffing plan due with orals deck 2027-01-13

## Context

Saguaro moved to Epic in 2022 but kept a minimal Resolute Professional Billing build. Initial denial rate is 11.8%, A/R over 90 days is 24% of total A/R, and charge lag averages 6 days. Patient billing calls go to an outsourced vendor with no access to account history, and first-call resolution is 48%.

The group wants a denials and charge-capture optimization in Epic plus an in-house billing service center on Service Cloud that shows Epic guarantor balances, payment plans and claim status in a single agent console. Targets: denial rate under 6%, A/R over 90 days under 15%, charge lag under 3 days, and first-call resolution above 75% within 6 months of service center launch.

## Roles to staff

Tailored from the standard staffing plan (staffing_plan.xlsx, 2026-10-23). Phase columns are planned FTE; Allocation is the plan's Avg FTE as a percentage. Skill proficiency is on a 1-5 scale.

| # | Plan ref | Role | Pod | Level | Location | Must-have skills | Nice-to-have | Discovery and design | Build | Test | Deploy and hypercare | Allocation |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| R1 | 1 | Program manager leader | Shared | Senior Manager | Onshore | Healthcare program delivery (4+), multi-vendor governance including transition from the outsourced billing vendor (4+), Epic and Salesforce programs (4+), revenue cycle transformation (4+) | HFMA CRCR, physician group experience | 1 | 1 | 1 | 1 | 100% |
| R2 | 2 | Solution architect | Shared | Manager or Senior Manager | Onshore | End-to-end solution design (4+), Service Cloud agent console design (4+), Epic touchpoints for Resolute PB guarantor and claim data (4+), discovery leadership (4+) | Health Cloud, Salesforce Application Architect | 1 | 1 | 0.5 | 0.5 | 75% |
| R3 | 4 | Integration architect (Epic interoperability) | Shared | Manager | Onshore | FHIR (3+), HL7 v2 (3+), Epic APIs and web services (4+), MuleSoft middleware patterns (4+), event-driven integration (3+) | MuleSoft Certified Integration Architect, Epic Bridges certification | 1 | 1 | 0.5 | 0.25 | 68.75% |
| R4 | 6 | Security architect | Shared | Senior Consultant | Onshore | PHI access model with HIPAA minimum-necessary design (4+), Shield and encryption (4+), field-level security (4+), audit (4+), PCI DSS scope reduction and payment tokenization (4+) | PCI QSA engagement experience | 0.5 | 0.25 | 0.25 | 0.25 | 31.25% |
| R5 | 7 | Epic application analyst | Billing & revenue cycle | Senior Consultant | Onshore | Epic Resolute Professional Billing certification - current (5+), claim edits and denial workqueue design (4+), charge router configuration (4+) | Epic Claims and Remittance certification, ASC billing, Cadence or MyChart certification | 1 | 1 | 0.5 | 0.5 | 75% |
| R6 | 8 | Business analyst, CRM | CRM | Consultant or Senior Consultant | Onshore | Requirements and user stories (3+), patient billing service processes and contact center KPIs (4+), Service Cloud case management (3+) | First-call resolution improvement programs | 1 | 1 | 0.5 | 0.25 | 68.75% |
| R7 | 10 | Business analyst, billing and revenue | Billing & revenue cycle | Senior Consultant | Onshore | Revenue cycle (4+), patient estimates and payments and payment plans (4+), Epic billing touchpoints in Resolute PB A/R and denials (4+) | CPT/ICD-10 coding knowledge, HFMA CRCR | 1 | 1 | 0.5 | 0.25 | 68.75% |
| R8 | 11 | UX designer | Shared | Senior Consultant | Onshore | Staff experience design for the billing agent console (4+), accessibility (3+), Service Cloud console UX (3+) | Patient billing statement and self-service design | 1 | 0.5 | 0 | 0 | 37.5% |
| R9 | 12 | Dev lead, CRM | CRM | Senior Consultant | Onshore | Salesforce development lead (4+), Service Cloud console and case management (4+), Omni-Channel (3+) | Health Cloud, Service Cloud Voice | 1 | 1 | 0.5 | 0.5 | 75% |
| R10 | 13 | Salesforce developer, CRM 1 | CRM | Consultant | Offshore | Apex (4+), LWC (4+), Flow (4+), Service Cloud console components (3+) | Health Cloud, Salesforce Platform Developer I | 0 | 1 | 0.5 | 0 | 37.5% |
| R11 | 14 | Salesforce developer, CRM 2 | CRM | Consultant | Offshore | Apex (3+), LWC (3+), Flow (4+), Service Cloud Knowledge and Omni-Channel (3+) | Experience Cloud patient billing self-service | 0 | 1 | 0.5 | 0 | 37.5% |
| R12 | 18 | Dev lead, billing and revenue | Billing & revenue cycle | Senior Consultant | Onshore | Salesforce development lead (4+), integration-heavy build with MuleSoft and Epic (4+), payments with PCI-compliant tokenized card capture (4+) | Payment gateway integration, Salesforce Platform Developer II | 1 | 1 | 0.5 | 0.5 | 75% |
| R13 | adapted from 19 | Epic analyst, Resolute PB charge capture and denials | Billing & revenue cycle | Consultant | Offshore | Epic charge router and charge review workqueues (3+), Epic Resolute PB certification - current (4+), denial workqueue build (3+), CPT/ICD-10 coding knowledge (3+) | CPC certification, Epic OpTime charging | 0 | 1 | 0.5 | 0 | 37.5% |
| R14 | 20 | Integration developer, billing and revenue | Billing & revenue cycle | Consultant | Offshore | APIs (4+), MuleSoft middleware (4+), FHIR resources with synthetic data only (3+), Epic guarantor balance and claim status web services (3+) | MuleSoft Certified Developer Level 1, PCI-compliant payment integration | 0 | 1 | 0.5 | 0 | 37.5% |
| R15 | 21 | Integration developer (FHIR/HL7, middleware) | Shared | Senior Consultant | Onshore | FHIR (3+), HL7 v2 (3+), MuleSoft middleware build (4+), Epic interface testing (4+) | Epic Bridges certification | 0 | 1 | 1 | 0.5 | 62.5% |
| R16 | 23 | DevOps / release engineer | Shared | Senior Consultant | Offshore | CI/CD for Salesforce and MuleSoft (4+), source control (4+), environment strategy (4+), release management (4+) | Copado or Gearset | 0.25 | 1 | 1 | 1 | 81.25% |
| R17 | 24 | Test lead | Shared | Senior Consultant | Onshore | Test strategy (4+), SIT and UAT management (4+), defect governance (4+), Epic Resolute PB and Service Cloud end-to-end testing (3+) | Revenue cycle parallel testing | 0.5 | 1 | 1 | 0.5 | 75% |
| R18 | 25 | Test automation engineer | Shared | Senior Consultant | Offshore | Salesforce test automation (4+), regression suites (4+), Service Cloud console automation (3+) | Provar or Copado Robotic Testing | 0 | 1 | 1 | 0.25 | 56.25% |
| R19 | 26 | Test data and environment analyst | Shared | Consultant | Onshore | Synthetic and de-identified data (4+), environment readiness (3+), synthetic guarantor accounts and PCI test card data (3+) | Epic test guarantor creation | 0 | 1 | 1 | 0.25 | 56.25% |
| R20 | 27 | Integration tester (Epic to Salesforce) | Shared | Consultant | Onshore | End-to-end interface testing with PHI-bound data (4+), Epic Resolute PB to Service Cloud flows via MuleSoft (3+) | Clarity SQL validation | 0 | 0.5 | 1 | 0.5 | 50% |
| R21 | 28 | Functional tester 1 | Shared | Analyst or Consultant | Offshore | Functional and regression testing (3+), synthetic data (3+), Service Cloud console and Epic billing workqueue testing (3+) | Claim scrubber edit testing | 0 | 0.5 | 1 | 0.25 | 43.75% |
| R22 | 29 | Functional tester 2 | Shared | Analyst or Consultant | Offshore | Functional and regression testing (3+), synthetic data (3+), Service Cloud console and Epic billing workqueue testing (3+) | Claim scrubber edit testing | 0 | 0.5 | 1 | 0.25 | 43.75% |
| R23 | 30 | OCM and training lead | Shared | Senior Consultant or Manager | Onshore | Adoption for billing office and service center staff (4+), training design (4+), communications (4+) | Insourcing a contact center from an outsourced vendor | 0.5 | 0.25 | 0.5 | 1 | 56.25% |

**Totals (23 roles: 15 onshore, 8 offshore):** Discovery and design 10.75 FTE | Build 19.5 FTE | Test 15.25 FTE | Deploy and hypercare 8.5 FTE | Average 13.5 FTE. **Onshore:** Discovery and design 10.5, Build 12.5, Test 9.25, Deploy and hypercare 6.75 FTE (average 9.75). **Offshore:** Discovery and design 0.25, Build 7, Test 6, Deploy and hypercare 1.75 FTE (average 3.75).

Adapted role: on Saguaro, most Billing & revenue cycle build is Epic Resolute PB optimization (charge capture, claim edits, denials). So the plan's Salesforce billing developer (row 19) is adapted to an Epic Resolute PB analyst at the same level, location and FTE. Salesforce payment work stays with the billing dev lead (R12) and the CRM developers.

## Removed from the standard plan

- 3. Technical architect (Salesforce) — Single Service Cloud console for a billing service center, not a large Health Cloud build; Salesforce architecture is covered by the solution architect (R2) and CRM dev lead (R9). It would also be a further Manager-level role against the partner's cap.
- 5. Data architect — No data migration or identity-matching scope: Epic stays the system of record and Service Cloud reads guarantor data live through MuleSoft. Data Cloud is not in scope.
- 9. Business analyst, patient care — Patient record management workstream is not in this project.
- 15. Dev lead, patient care — Patient record management workstream is not in this project.
- 16. Salesforce developer, patient care 1 — Patient record management workstream is not in this project.
- 17. Salesforce developer, patient care 2 — Patient record management workstream is not in this project.
- 22. Data migration developer — No legacy data to migrate; the outsourced vendor's call history is not being converted.

## Client-provided roles

| Role | Notes |
|---|---|
| Executive sponsor | Decision authority and escalation (revenue cycle leadership) |
| Product owner, one per pod (2) | Backlog ownership and acceptance for Billing & revenue cycle and CRM (billing service center) |
| Client Epic analysts and Epic integration team | Work alongside the Epic application analyst (R5) and Epic PB analyst (R13); own Epic build migrations and web service enablement |
| Compliance and privacy officer | Sign-off on PHI access model and data handling, including HIPAA minimum-necessary access and PCI DSS scope |

## Constraints

- R2 must hold a current Epic Resolute PB certification at start; Saguaro is an Epic customer but will not sponsor certification for vendor staff.
- Service center agents will see PHI and payment data in Salesforce; the design must meet HIPAA minimum-necessary access and PCI DSS for card payments, with no card numbers stored in Salesforce.
- No changes to Epic billing build during the Epic year-end CPT code update window, 2027-12-15 to 2028-01-10.
- Proposal is competitive and price-sensitive; the partner wants a blended rate with no more than one Manager-level role.
- Standard plan offshore rule: offshore roles (R10, R11, R13, R14, R16, R18, R21, R22) work only with synthetic or de-identified data; onshore is required for any role that touches production PHI, runs client workshops, or owns Epic integration testing.

## Plan conflicts

1. **No more than one Manager-level role.** The tailored plan has four roles at or able to be at Manager level: Program manager leader R1 (Senior Manager), Solution architect R2 (Manager or Senior Manager), Integration architect R3 (Manager) and OCM and training lead R23 (Senior Consultant or Manager). **Recommended resolution:** Keep R1 as the single Manager-level role, staffed at Manager to protect the blended rate. Staff R2 and R3 at Senior Consultant with prior Epic-MuleSoft-Salesforce delivery, and R23 at Senior Consultant. If the orals deck needs Manager-level architecture, ask the partner for an explicit exception for R2 only.
2. **Epic year-end CPT window (2027-12-15 to 2028-01-10) vs plan deploy and hypercare.** The 10-month engagement ends about 2028-01-14, so the plan's Deploy and hypercare phase for the Epic application analyst (R5, 0.5 FTE) and billing BA (R7, 0.25 FTE) falls inside the window when no Epic billing build changes are allowed. **Recommended resolution:** Move Epic Resolute PB optimization go-live to no later than 2027-12-01 so a short stabilization window closes before 2027-12-15. During the window, Epic roles do monitoring and denial-trend reporting only, with no build migrations. The Service Cloud service center deploy is not affected.
3. **Epic certification.** The constraint's R2 is the original Resolute PB Lead, which is the Epic application analyst R5 in this table. The adapted Epic PB analyst R13 also needs current Resolute PB certification to build. Saguaro will not sponsor certification, and the plan's Risks sheet flags the Epic analyst as the hardest role to fill. **Recommended resolution:** Confirm current Resolute PB certification for R5 and R13 before the orals deck. If no certified offshore candidate exists for R13, staff it onshore at the same level and FTE.
