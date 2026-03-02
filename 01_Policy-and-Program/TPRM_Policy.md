<!--
Author/Owner: Badr Karim | Cybersecurity GRC Intern | Security Assurance | Risk-Based Controls | Compliance
LinkedIn: https://www.linkedin.com/in/badrkarim/
Last updated: 2026-03-03
Classification: Internal (Portfolio)
-->

# Third-Party Risk Management (TPRM) Policy — US Privacy + Cloud Data Protection

**Owner:** Security GRC (with Privacy + Legal oversight)  
**Applies to:** All third parties that store/process/transmit Northbridge Cloud data or receive system access  
**Objective:** Ensure third-party services do not create unacceptable risk to confidentiality, integrity, availability, or privacy obligations.

## 1) Scope
In scope:
- SaaS vendors, IaaS/PaaS providers, MSPs, security vendors, data processors, consultants with data exposure
- Subprocessors/fourth parties for High/Critical vendors (disclosure required)
Out of scope (managed separately):
- Commodity suppliers with no data/access (low operational risk only)

## 2) Risk tiers (based on inherent risk score)
- **Critical:** material impact + privileged access / restricted data / high regulatory exposure
- **High:** significant impact + sensitive data or elevated access
- **Medium:** limited sensitive data or limited access
- **Low:** minimal data, no privileged access, low impact

## 3) Minimum gating requirements
- **All vendors:** confidentiality obligations + security contact + incident notification commitment
- **Medium+ vendors:** MFA/SSO, encryption at rest/in transit, logging, vulnerability management
- **High/Critical vendors:** documented security program, incident response plan, BC/DR, subprocessor controls, evidence artifacts, contract security/privacy clauses

## 4) US privacy alignment (CIPP/US-aligned expectations)
For vendors handling personal data:
- data use limitation (purpose-bound processing)
- data minimization and retention controls
- rights readiness support (deletion, access, correction where applicable)
- service provider/processor terms and subprocessor governance
- breach response readiness and notification obligations

## 5) Approvals
- **Low/Medium:** Security GRC + vendor owner
- **High:** Security GRC + Privacy + Legal + business owner
- **Critical:** Risk Committee (Security + Privacy + Legal + leadership) approval required

## 6) Exceptions
Exceptions are allowed only with:
- written risk acceptance + compensating controls + expiration date
- tracked remediation plan when applicable

## 7) Review cadence
- Critical: annual reassessment + continuous monitoring
- High: annual
- Medium: every 24 months
- Low: every 36 months or on major change
