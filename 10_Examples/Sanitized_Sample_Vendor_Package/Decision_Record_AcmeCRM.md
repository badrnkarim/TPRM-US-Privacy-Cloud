<!--
Document ID: TPRM-10-ACME
Title: Sanitized Sample Vendor Package — AcmeCRM (High Tier)
Author/Owner: Badr Karim | Cybersecurity GRC Intern | Security Assurance | Risk-Based Controls | Compliance
LinkedIn: https://www.linkedin.com/in/badrkarim/
Version: 1.0
Effective Date: 2026-03-03
Review Cycle: Annual (or on major change)
Classification: Internal (Portfolio)
Approvers: Security (Owner) + Privacy + Legal (roles)
-->

# Decision Record — Approve with Conditions
Decision: ✅ **Approve with Conditions**

## Conditions
**C-01 (DPA/Privacy Annex):** purpose limitation, retention/deletion SLA + confirmation, subprocessor flow-down + change notification, time-bound breach notification.  
**C-02 (API Governance):** allowlisting where supported, token rotation ≤ 90 days, least-privileged scopes, SCIM/automated deprovisioning (or documented alternative).

## Compensating controls (until closure)
- Minimum API scopes + dedicated integration account
- Weekly admin/API log review during remediation window
