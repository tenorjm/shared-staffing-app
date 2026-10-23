# Project opportunity: Prairie Star Children's Health — Epic Pediatric Access and MyChart Proxy Program

**Client:** Prairie Star Children's Health (fictional), pediatric health system with a 260-bed children's hospital and 30 specialty and primary care clinics, Kansas City, Missouri
**Engagement type:** Epic patient access and patient portal optimization (Cadence, Prelude, MyChart, Resolute Hospital Billing front-end)
**Platforms:** Epic
**Workstreams:** Patient record management (scheduling, patient portal); Billing & revenue cycle (registration)
**Start date:** 2027-04-19
**Duration:** 6 months
**Location / travel:** Remote with on-site weeks in Kansas City for discovery (weeks 1-2) and go-live (month 5)
**Partner sponsor:** (fictional) A. Brennan
**Status:** Early discovery, proposal due 2027-02-26

## Context

Prairie Star's MyChart proxy setup is manual: parents and guardians request access on paper, and adolescent confidentiality rules (ages 12-17) are applied inconsistently. Only 38% of pediatric patients have an active proxy, and the call center fields roughly 2,500 proxy-access calls a month.

Registration errors on guarantor and coverage, often divorced parents or Medicaid-to-commercial changes, drive 7% of hospital billing claim denials. The goal is to reach 65% active MyChart proxy coverage, cut proxy-related calls by half, and reduce registration-related denials to below 3% by the end of the engagement.

## Roles to staff

Tailored from the standard staffing plan (staffing_plan.xlsx, 2026-10-23). Phase columns are planned FTE; Allocation is the plan's Avg FTE as a percentage. Skill proficiency is on a 1-5 scale.

| # | Plan ref | Role | Pod | Level | Location | Must-have skills | Nice-to-have | Discovery and design | Build | Test | Deploy and hypercare | Allocation |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| R1 | 1 | Program manager leader | Shared | Senior Manager | Onshore | Healthcare program delivery (4+), multi-vendor governance (3+), Epic optimization programs for Cadence/Prelude/MyChart (4+) | Pediatric health system experience, Lean/Six Sigma | 1 | 1 | 1 | 1 | 100% |
| R2 | 2 | Solution architect | Shared | Manager or Senior Manager | Onshore | End-to-end solution design (4+), Epic touchpoints across Cadence/Prelude/MyChart/Resolute HB (4+), discovery leadership (4+) | Adolescent confidentiality and minor-consent design | 1 | 1 | 0.5 | 0.5 | 75% |
| R3 | 7 | Epic application analyst | Billing & revenue cycle | Senior Consultant | Onshore | Epic Prelude or Cadence certification - current (4+), Epic Resolute HB certification - current (4+), Prelude guarantor and coverage workflows (4+) | Epic MyChart certification, Medicaid eligibility workflows | 1 | 1 | 0.5 | 0.5 | 75% |
| R4 | 9 | Business analyst, patient care | Patient record management | Consultant or Senior Consultant | Onshore | Care coordination (3+), scheduling workflows in Cadence (4+), MyChart proxy and adolescent access workflows (3+) | Pediatric confidentiality policy design, family advisory council facilitation | 1 | 1 | 0.5 | 0.25 | 68.75% |
| R5 | 10 | Business analyst, billing and revenue | Billing & revenue cycle | Senior Consultant | Onshore | Revenue cycle (4+), patient estimates and payments (3+), Epic billing touchpoints from Prelude registration to Resolute HB front-end edits (4+) | Pediatric Medicaid managed care billing | 1 | 1 | 0.5 | 0.25 | 68.75% |
| R6 | adapted from 15 | Epic MyChart lead, proxy and adolescent access | Patient record management | Senior Consultant | Onshore | MyChart proxy and adolescent access build (4+), Epic MyChart certification - current (5+), patient portal workflow leadership (4+) | MyChart Bedside, pediatric confidentiality policy design | 1 | 1 | 0.5 | 0.5 | 75% |
| R7 | adapted from 16 | Epic analyst, MyChart | Patient record management | Consultant | Offshore | MyChart build (3+), Epic MyChart certification - current (4+), MyChart proxy request and activation configuration (3+) | MyChart ticket scheduling | 0 | 1 | 0.5 | 0 | 37.5% |
| R8 | adapted from 17 | Epic analyst, Cadence | Patient record management | Consultant | Offshore | Cadence scheduling build (3+), Epic Cadence certification - current (4+), pediatric scheduling templates and decision trees (3+) | Specialty clinic scheduling | 0 | 1 | 0.5 | 0 | 37.5% |
| R9 | adapted from 18 | Epic Resolute HB lead, front-end edits and denials | Billing & revenue cycle | Senior Consultant | Onshore | Resolute Hospital Billing front-end edits and denials analysis (4+), Epic Resolute HB certification - current (5+), registration-to-claim integration (3+) | Pediatric Medicaid managed care billing | 1 | 1 | 0.5 | 0.5 | 75% |
| R10 | adapted from 19 | Epic analyst, Prelude | Billing & revenue cycle | Consultant | Offshore | Prelude guarantor and coverage build (3+), Epic Prelude certification - current (4+), registration quality workqueues (3+) | Real-time eligibility (270/271) setup | 0 | 1 | 0.5 | 0 | 37.5% |
| R11 | 24 | Test lead | Shared | Senior Consultant | Onshore | Test strategy (4+), SIT and UAT management (4+), defect governance (4+), Epic MyChart and Prelude integrated testing (3+) | Epic upgrade regression coordination | 0.5 | 1 | 1 | 0.5 | 75% |
| R12 | 26 | Test data and environment analyst | Shared | Consultant | Onshore | Synthetic and de-identified data (4+), environment readiness (3+), synthetic pediatric patients with guardian and proxy scenarios (3+) | Epic test patient creation | 0 | 1 | 1 | 0.25 | 56.25% |
| R13 | 28 | Functional tester 1 | Shared | Analyst or Consultant | Offshore | Functional and regression testing (3+), synthetic data (3+), MyChart proxy and registration workflow testing (3+) | Adolescent confidentiality test scenarios | 0 | 0.5 | 1 | 0.25 | 43.75% |
| R14 | 30 | OCM and training lead | Shared | Senior Consultant or Manager | Onshore | Clinical adoption (4+), training design (4+), communications to families and call center staff (4+) | Family advisory council facilitation, tip sheet design | 0.5 | 0.25 | 0.5 | 1 | 56.25% |

**Totals (14 roles: 10 onshore, 4 offshore):** Discovery and design 8 FTE | Build 12.75 FTE | Test 9 FTE | Deploy and hypercare 5.5 FTE | Average 8.8125 FTE. **Onshore:** Discovery and design 8, Build 9.25, Test 6.5, Deploy and hypercare 5.25 FTE (average 7.25). **Offshore:** Discovery and design 0, Build 3.5, Test 2.5, Deploy and hypercare 0.25 FTE (average 1.5625).

## Removed from the standard plan

- 3. Technical architect (Salesforce) — Salesforce-specific role; Prairie Star is an Epic-only optimization.
- 4. Integration architect (Epic interoperability) — No new interfaces in scope; the work is build optimization inside the existing Epic instance.
- 5. Data architect — No data migration, identity matching or Data Cloud scope.
- 6. Security architect — Built around Salesforce Shield, encryption and field-level security; MyChart proxy and adolescent access rules are built by the MyChart lead (R6) with the client privacy officer.
- 8. Business analyst, CRM — CRM workstream is not in this project.
- 11. UX designer — MyChart screens are vendor-controlled; family-facing content is covered by the MyChart lead (R6) and OCM and training lead (R14).
- 12. Dev lead, CRM — CRM workstream is not in this project.
- 13. Salesforce developer, CRM 1 — CRM workstream is not in this project.
- 14. Salesforce developer, CRM 2 — CRM workstream is not in this project.
- 20. Integration developer, billing and revenue — No interface build in scope; the Billing & revenue cycle work is Prelude registration and Resolute HB front-end edits.
- 21. Integration developer (FHIR/HL7, middleware) — No new interfaces or middleware build; Prairie Star is an Epic-only optimization.
- 22. Data migration developer — No data migration in scope.
- 23. DevOps / release engineer — Salesforce-style CI/CD does not apply; Epic build migration is run by the client's Epic team.
- 25. Test automation engineer — Salesforce-specific role (Salesforce test automation); Prairie Star is an Epic-only optimization.
- 27. Integration tester (Epic to Salesforce) — Epic-to-Salesforce role; there is no Salesforce in scope.
- 29. Functional tester 2 — Six-month optimization with a small build team; one functional tester is enough.

## Client-provided roles

| Role | Notes |
|---|---|
| Executive sponsor | Decision authority and escalation |
| Product owner, one per pod (2) | Backlog ownership and acceptance for Patient record management and Billing & revenue cycle |
| Clinical informaticist or clinical SME | Clinical workflow validation, including adolescent medicine input on 12-17 confidentiality rules |
| Client Epic analysts and Epic integration team | Work alongside the Epic application analyst (R3) and Epic build roles; own build migrations and the fall Epic upgrade |
| Compliance and privacy officer | Sign-off on PHI access model and data handling, including approval of Missouri and Kansas minor-consent rules before build migration |

## Constraints

- Adolescent confidentiality: any proxy access change for patients aged 12-17 must follow Missouri and Kansas minor-consent rules and be approved by the client's privacy officer before build migration.
- All Epic roles must hold current certifications at start; with a 6-month engagement there is no time for Epic certification training.
- Prairie Star has a go-live freeze for its fall Epic upgrade starting 2027-09-20; MyChart changes must be in production by 2027-09-13.
- Proposal is pre-SOW; the partner wants the team sized to 5 roles or fewer to keep the bid under the client's budget.
- Standard plan offshore rule: offshore roles (R7, R8, R10, R13) work only with synthetic or de-identified data; onshore is required for any role that touches production PHI, runs client workshops, or owns Epic integration testing.

## Plan conflicts

1. **Team sized to 5 roles or fewer.** The tailored plan has 14 roles. **Recommended resolution:** Bid a 5-role core and leave the rest out of the proposal. The core is R1 Program manager leader (staffed at Manager as the engagement manager), R6 Epic MyChart lead, R3 Epic application analyst (covering Cadence and Prelude), R9 Epic Resolute HB lead (staffed at Consultant, 75%) and R14 OCM and training lead. The BA, test and offshore build work (R2, R4, R5, R7, R8, R10, R11, R12, R13) is absorbed by these roles and the client's Epic analysts. Show the full 14-role plan only as a scale-up option if the SOW scope grows.
2. **All Epic roles hold current certifications.** Every Epic build role in the table (R3, R6, R7, R8, R9, R10) needs current certification at start, and the plan's Risks sheet flags certified Epic analysts as the hardest roles to fill, especially offshore. **Recommended resolution:** Propose only currently certified people, and confirm certificates before the proposal date. Under the 5-role core in conflict 1, the offshore adapted roles are not bid. If they are added later, staff them onshore when no certified offshore candidate exists.
3. **Fall upgrade freeze (MyChart changes in production by 2027-09-13) vs plan phase lengths.** The plan assumes about 10 weeks of discovery and 6 build sprints. From a 2027-04-19 start, that puts build exit near late September, after the MyChart deadline and before any test phase. **Recommended resolution:** Compress discovery to the 2 on-site weeks plus 2 remote weeks, run 4 two-week build sprints, and finish SIT/UAT by late August. MyChart proxy changes then go live by 2027-09-13, with hypercare during the freeze limited to monitoring and non-build fixes.
