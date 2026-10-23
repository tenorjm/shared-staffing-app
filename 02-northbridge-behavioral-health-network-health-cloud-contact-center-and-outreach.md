# Project opportunity: Northbridge Behavioral Health Network — Health Cloud Contact Center and Outreach

**Client:** Northbridge Behavioral Health Network (fictional), nonprofit behavioral health provider with 22 outpatient sites and a 24/7 crisis line, Columbus, Ohio
**Engagement type:** Salesforce Health Cloud implementation with Service Cloud Voice contact center and Marketing Cloud outreach
**Platforms:** Salesforce (Health Cloud, Service Cloud, Marketing Cloud, Experience Cloud)
**Workstreams:** CRM (contact center, referral management, outreach)
**Start date:** 2027-01-11
**Duration:** 7 months
**Location / travel:** Mostly remote; on site in Columbus 2 days every other week during design and UAT
**Partner sponsor:** (fictional) D. Lindqvist
**Status:** Verbal award, SOW in legal review, staffing due 2026-12-14

## Context

Northbridge takes about 9,000 intake and referral calls per month across a homegrown Access database, spreadsheets and a legacy phone system. Referrals from schools, courts and primary care arrive by fax and email, and 31% of referred clients never complete a first appointment.

The CEO wants a single Health Cloud view of each client's referral, intake status and care team, a Service Cloud Voice contact center for intake and crisis-line follow-up, and Marketing Cloud SMS reminders. The measurable goal is to raise referral-to-first-appointment completion from 69% to 80% and cut average intake call handle time from 14 to 9 minutes.

## Roles to staff

Tailored from the standard staffing plan (staffing_plan.xlsx, 2026-10-23). Phase columns are planned FTE; Allocation is the plan's Avg FTE as a percentage. Skill proficiency is on a 1-5 scale.

| # | Plan ref | Role | Pod | Level | Location | Must-have skills | Nice-to-have | Discovery and design | Build | Test | Deploy and hypercare | Allocation |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| R1 | 1 | Program manager leader | Shared | Senior Manager | Onshore | Healthcare program delivery (4+), multi-vendor governance across Salesforce and Amazon Connect (4+), Salesforce Health Cloud and Service Cloud program delivery (4+) | Behavioral health or nonprofit client experience, Agile/SAFe certification | 1 | 1 | 1 | 1 | 100% |
| R2 | 2 | Solution architect | Shared | Manager or Senior Manager | Onshore | End-to-end solution design (4+), Health Cloud data model and care plans (4+), discovery leadership (4+), Service Cloud Voice and Marketing Cloud solution design (3+), Health Cloud sharing and scale (3+) | Salesforce Health Cloud Accredited Professional, Salesforce Application Architect, 42 CFR Part 2 consent design | 1 | 1 | 0.5 | 0.5 | 75% |
| R3 | 6 | Security architect | Shared | Senior Consultant | Onshore | PHI access model (4+), Shield Platform Encryption and Event Monitoring (4+), field-level security and sharing (4+), audit (3+), 42 CFR Part 2 consent and record-sharing design (4+) | Salesforce Sharing and Visibility Architect certification | 0.5 | 0.25 | 0.25 | 0.25 | 31.25% |
| R4 | 8 | Business analyst, CRM | CRM | Consultant or Senior Consultant | Onshore | Requirements and user stories (3+), patient engagement and service processes (4+), behavioral health intake and referral workflows in Health Cloud (3+) | Crisis-line or 988 workflows, school and court referral processes | 1 | 1 | 0.5 | 0.25 | 68.75% |
| R5 | 11 | UX designer | Shared | Senior Consultant | Onshore | Patient and staff experience design (4+), accessibility to WCAG 2.1 AA (4+), Experience Cloud referral portal and intake agent console UX (3+) | Trauma-informed design, SMS content design | 1 | 0.5 | 0 | 0 | 37.5% |
| R6 | 12 | Dev lead, CRM | CRM | Senior Consultant | Onshore | Salesforce development lead (4+), Health Cloud (4+), Service Cloud with Service Cloud Voice (Amazon Connect) and Omni-Channel (4+) | Salesforce Platform Developer II, OmniStudio, CTI migration | 1 | 1 | 0.5 | 0.5 | 75% |
| R7 | 13 | Salesforce developer, CRM 1 | CRM | Consultant | Offshore | Apex (4+), LWC (4+), Flow (4+), Health Cloud referral and care team build (3+) | Salesforce Platform Developer I, OmniStudio FlexCards and OmniScripts | 0 | 1 | 0.5 | 0 | 37.5% |
| R8 | 14 | Salesforce developer, CRM 2 | CRM | Consultant | Offshore | Apex (3+), LWC (3+), Flow (4+), Experience Cloud referral portal build (3+), Marketing Cloud Journey Builder and MobileConnect SMS (3+) | Salesforce Marketing Cloud Email Specialist, healthcare SMS consent and opt-out handling | 0 | 1 | 0.5 | 0 | 37.5% |
| R9 | 22 | Data migration developer | Shared | Consultant | Onshore | ETL (3+), data loads with Data Loader (4+), reconciliation (3+), identity matching and de-duplication across the Access database and spreadsheets (3+) | Health Cloud person account migration | 0 | 1 | 0.5 | 1 | 62.5% |
| R10 | 23 | DevOps / release engineer | Shared | Senior Consultant | Offshore | CI/CD (4+), source control (4+), environment strategy for Salesforce sandboxes (4+), release management (4+) | Copado or Gearset, Marketing Cloud package deployment | 0.25 | 1 | 1 | 1 | 81.25% |
| R11 | 24 | Test lead | Shared | Senior Consultant | Onshore | Test strategy (4+), SIT and UAT management (4+), defect governance (4+), Service Cloud Voice call-flow and cutover testing (3+) | Contact center go-live testing | 0.5 | 1 | 1 | 0.5 | 75% |
| R12 | 25 | Test automation engineer | Shared | Senior Consultant | Offshore | Salesforce test automation (4+), regression suites (4+), Health Cloud and Service Cloud console automation (3+) | Provar or Copado Robotic Testing | 0 | 1 | 1 | 0.25 | 56.25% |
| R13 | 26 | Test data and environment analyst | Shared | Consultant | Onshore | Synthetic and de-identified data (4+), environment readiness (3+), Salesforce sandbox seeding with synthetic behavioral health records (3+) | Synthetic 42 CFR Part 2 test scenarios | 0 | 1 | 1 | 0.25 | 56.25% |
| R14 | 28 | Functional tester 1 | Shared | Analyst or Consultant | Offshore | Functional and regression testing (3+), synthetic data (3+), Service Cloud and Experience Cloud functional testing (3+) | Marketing Cloud journey testing | 0 | 0.5 | 1 | 0.25 | 43.75% |
| R15 | 30 | OCM and training lead | Shared | Senior Consultant or Manager | Onshore | Clinical adoption for intake and crisis-line staff (4+), training design (4+), communications (4+) | Contact center go-live support, nonprofit change management | 0.5 | 0.25 | 0.5 | 1 | 56.25% |

**Totals (15 roles: 10 onshore, 5 offshore):** Discovery and design 6.75 FTE | Build 12.5 FTE | Test 9.75 FTE | Deploy and hypercare 6.75 FTE | Average 8.9375 FTE. **Onshore:** Discovery and design 6.5, Build 8, Test 5.75, Deploy and hypercare 5.25 FTE (average 6.375). **Offshore:** Discovery and design 0.25, Build 4.5, Test 4, Deploy and hypercare 1.5 FTE (average 2.5625).

## Removed from the standard plan

- 3. Technical architect (Salesforce) — Single Salesforce org on one platform; the solution architect (R2) covers the Health Cloud data model, sharing and scale with the security architect (R3), avoiding a second Manager-level architect on a capped nonprofit budget.
- 4. Integration architect (Epic interoperability) — Epic-specific role; Northbridge is Salesforce-only with no Epic or HL7/FHIR interfaces.
- 5. Data architect — Migration is one Access database plus spreadsheets; strategy and identity matching are covered by the solution architect (R2) and data migration developer (R9). Data Cloud is not in scope.
- 7. Epic application analyst — Epic-specific role, and its Billing & revenue cycle workstream is not in this project.
- 9. Business analyst, patient care — Patient record management workstream is not in this project.
- 10. Business analyst, billing and revenue — Billing & revenue cycle workstream is not in this project.
- 15. Dev lead, patient care — Patient record management workstream is not in this project.
- 16. Salesforce developer, patient care 1 — Patient record management workstream is not in this project.
- 17. Salesforce developer, patient care 2 — Patient record management workstream is not in this project.
- 18. Dev lead, billing and revenue — Billing & revenue cycle workstream is not in this project.
- 19. Salesforce developer, billing and revenue — Billing & revenue cycle workstream is not in this project.
- 20. Integration developer, billing and revenue — Billing & revenue cycle workstream is not in this project.
- 21. Integration developer (FHIR/HL7, middleware) — Plan role is FHIR/HL7 and Epic interface work; there is no Epic in scope. Service Cloud Voice and Marketing Cloud use native connectors built by the CRM pod.
- 27. Integration tester (Epic to Salesforce) — Epic-to-Salesforce role; there is no Epic in scope.
- 29. Functional tester 2 — One CRM pod with three developers; one functional tester plus the automation engineer (R12) covers regression for a 7-month project.

## Client-provided roles

| Role | Notes |
|---|---|
| Executive sponsor | Decision authority and escalation (CEO office) |
| Product owner, one per pod (1) | Backlog ownership and acceptance for the CRM pod (contact center, referral management, outreach) |
| Clinical informaticist or clinical SME | Clinical workflow validation for intake, crisis-line follow-up and referral triage |
| Compliance and privacy officer | Sign-off on PHI access model and data handling, including 42 CFR Part 2 consent and record-sharing design before build |

## Constraints

- Substance use disorder records are protected under 42 CFR Part 2 as well as HIPAA; consent and record-sharing design must be signed off by Northbridge's privacy officer before build.
- No production PHI is loaded into any sandbox; test data must be synthetic or de-identified.
- The crisis-line cutover cannot happen on a weekend or holiday and must have a same-day rollback to the legacy phone system.
- Nonprofit budget is capped; the partner will not approve any role above Manager.
- Standard plan offshore rule: offshore roles (R7, R8, R10, R12, R14) work only with synthetic or de-identified data; onshore is required for any role that touches production PHI, runs client workshops, or owns Epic integration testing.

## Plan conflicts

1. **No role above Manager.** The plan's Program manager leader (R1) is Senior Manager, and the Solution architect (R2) is Manager or Senior Manager. **Recommended resolution:** Staff R1 at Manager, as an engagement manager with Salesforce Health Cloud program delivery experience, and staff R2 at Manager only. No other role in the table is above Manager.
2. **No production PHI in any sandbox vs plan migration approach.** The data migration developer (R9) normally rehearses loads in a full-copy sandbox with production extracts. **Recommended resolution:** Run all migration rehearsals in sandboxes with de-identified extracts or synthetic data built by R13. Load real client records only into production at cutover, with onshore R9 doing the load and the privacy officer signing off the reconciliation approach.
3. **Crisis-line cutover (weekday only, same-day rollback) vs plan deploy staffing.** The DevOps / release engineer (R10) is offshore, and the CRM developers (R7, R8) are at 0 FTE in Deploy and hypercare. **Recommended resolution:** Make the onshore dev lead (R6) the owner of the cutover and rollback runbook, with the test lead (R11) running a rehearsed rollback test before cutover. R10 works a US-hours shift during cutover week and deploys metadata only, with no access to production data.
