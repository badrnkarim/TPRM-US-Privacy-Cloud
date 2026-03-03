<!--
Document ID: TPRM-12-LOG
Title: Logging Requirements (Vendor Assurance)
Author/Owner: Badr Karim | Cybersecurity GRC Intern | Security Assurance | Risk-Based Controls | Compliance
LinkedIn: https://www.linkedin.com/in/badrkarim/
Version: 1.0
Effective Date: 2026-03-03
Review Cycle: Annual (or on major change)
Classification: Internal (Portfolio)
Note: Not legal advice. Templates are portfolio-grade and must be adapted to organizational context.
-->

# Logging Requirements (Vendor Assurance)

## Required log types (High/Critical)
- Authentication events (SSO/MFA, failures)
- Privileged/admin actions (role changes, configuration changes)
- API activity (token creation/usage, scope changes where possible)
- Security events (alerts, detections)
- Data access events where available (especially Restricted)

## Retention
- Minimum retention aligned to investigation needs (define by tier).
- Ability to export logs on request (CSV/JSON/SIEM formats).

## Access & integrity
- Logs accessible to customer admins or exportable via support.
- Evidence of tamper resistance/integrity controls where supported.

## Incident support
- Ability to preserve logs for forensic review.
- Response timeline for log export requests.
