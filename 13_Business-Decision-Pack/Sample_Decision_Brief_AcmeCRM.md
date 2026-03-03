<!--
Document ID: TPRM-13-SMP-CRM
Title: Sample Executive Decision Brief — AcmeCRM (High Tier)
Author/Owner: Badr Karim | Cybersecurity GRC Intern | Security Assurance | Risk-Based Controls | Compliance
LinkedIn: https://www.linkedin.com/in/badrkarim/
Version: 1.0
Effective Date: 2026-03-03
Review Cycle: Annual (or on major change)
Classification: Internal (Portfolio)
Note: Not legal advice. Templates are portfolio-grade and must be adapted to organizational context.
-->

# Executive Decision Brief — AcmeCRM (High Tier)

## Decision requested
✅ Approve with Conditions

## Business value
CRM supports revenue pipeline execution and customer lifecycle operations.

## Data + access
- Data: PII (Confidential)
- Access: SSO + API + CRM admin role
- Subprocessors: Yes

## Risk summary
- Inherent: 58 (High)
- Residual: ~11
- Key risks: secondary use risk if contract weak; retention/deletion enforceability; API governance hardening.

## Conditions
- C-01 Contract/DPA clauses: purpose limitation, deletion/return SLA + confirmation, subprocessor flow-down + notice window, time-bound breach notification (EV-010)
- C-02 API governance: allowlisting where supported, token rotation ≤90d, least scopes, deprovisioning (EV-011)

## Recommendation
Conditional approval is defensible because baseline security posture is acceptable, and conditions close the remaining privacy + governance gaps.
