# Third-Party Risk Management (TPRM) Vendor Assessment Project

## Overview
This project demonstrates a structured **Third-Party Risk Management (TPRM)** process used to evaluate, document, and assess the security, compliance, and operational risks of external vendors prior to onboarding.

This simulated assessment highlights how security findings, control gaps, and contractual responsibilities (CUECs) influence final risk decisions and vendor approval outcomes.

---

## Objectives
- Establish a consistent framework for assessing third-party security risk
- Identify security issues, control gaps, and compliance concerns early
- Evaluate vendor-provided evidence (SOC 2, penetration tests, security policies)
- Assess **Customer User Entity Controls (CUECs)** for reasonableness and feasibility
- Provide clear, actionable recommendations to stakeholders
- Reduce organizational risk exposure from third-party tools

---
## Common Issues & Associated Risks
- Outdated or missing SOC 2 reports
- Penetration tests with unresolved critical findings
- Lack of access management controls (SSO, MFA)
- Incomplete data retention and destruction policies
- Unreasonable or infeasible CUECs shifted to the customer
- Gaps in internal controls required to support vendor usage


---
## Vendor Clarification & Follow-Up Questions

- **Assurance & Audits**
  - Do you have a current SOC 2 report? If not, is an audit planned, and what is the expected timeline?
  - If findings were identified in your SOC 2, what remediation steps were taken and how is completion tracked?

- **Security Testing**
  - When was your most recent penetration test conducted?
  - Were any high or critical findings identified, and if so, have they been fully remediated?
  - Can you provide the full penetration test report, including findings and remediation details (not just a summary)?

- **Security Governance**
  - Do you maintain an up-to-date Information Security policy?
  - If policies are outdated or missing, what is the plan and timeline for updating them?

- **Data Handling**
  - How long is customer data retained?
  - What is your data retention and destruction process?
  - Can customers request deletion of their data, and how are those requests handled?

- **Access Management**
  - How is access to systems managed today?
  - Do you use Role-Based Access Control (RBAC)?
  - How frequently are user permissions reviewed?
  - Is Multi-Factor Authentication (MFA) enforced for privileged or all users?
  - If SSO is not currently supported, is it on the product roadmap?
 
---
## Evaluating Customer User Entity Controls (CUECs)

CUECs are evaluated based on **ownership, feasibility, and alignment with the shared responsibility model**. 
A control may be well-intentioned but still unreasonable if it places vendor obligations on the customer or is operationally infeasible.


### What Makes a CUEC Reasonable

A CUEC is generally reasonable when it:

- Falls within the customer’s control (users, access, data usage)
- Aligns with standard security practices (least privilege, MFA, logging, reviews)
- Supports governance, auditability, or compliance
- Can be met using existing or reasonably attainable controls

**Common examples**
- Managing user access and roles
- Disabling access upon termination
- Reviewing logs, reports, or exported data
- Preventing sensitive data from being entered into tools
- Maintaining documentation or inventories

---

### What Makes a CUEC Unreasonable

A CUEC is unreasonable when it:

- Shifts vendor-owned responsibilities to the customer
- Requires changes to the vendor’s infrastructure or product
- Depends on unsupported features
- Creates excessive operational or financial burden

---
## Required Remediation Actions

### Assurance & Testing
- Provide a current SOC 2 report by an agreed-upon date.
- Share a complete, up-to-date penetration test report (not just a summary).
- Provide clear evidence of remediation for any identified findings, including critical, medium, or minor issues.

### Policy & Governance
- Provide an updated Information Security policy.
- Provide a documented data retention and data destruction policy.

### Access Management
- Implement a formal access management process, including SSO and/or enforced MFA.
- Provide details on how user access is provisioned, reviewed, and revoked.

### Remediation Transparency
- Provide documentation outlining remediation plans, timelines, and validation for any unresolved findings.

---
## Methodology
1. **Vendor intake & use-case review**
2. **Evidence collection**
   - SOC 2 reports
   - Pen test documentation
   - Security policies
3. **Risk & gap identification**
4. **Vendor Q&A based on identified issues**
5. **CUEC analysis**
6. **Final recommendation with remediation requirements**

---

## Disclaimer
All vendor names and findings are simulated and used for **demonstration and educational purposes** only. This project is intended to showcase a TPRM assessment workflow and does not represent live production risk decisions.

---

## Author
Created as part of a hands-on security and risk management portfolio project focused on real-world vendor assessment and governance.
