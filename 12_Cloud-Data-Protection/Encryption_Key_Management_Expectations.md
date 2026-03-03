<!--
Document ID: TPRM-12-KEYS
Title: Encryption & Key Management Expectations
Author/Owner: Badr Karim | Cybersecurity GRC Intern | Security Assurance | Risk-Based Controls | Compliance
LinkedIn: https://www.linkedin.com/in/badrkarim/
Version: 1.0
Effective Date: 2026-03-03
Review Cycle: Annual (or on major change)
Classification: Internal (Portfolio)
Note: Not legal advice. Templates are portfolio-grade and must be adapted to organizational context.
-->

# Encryption & Key Management Expectations (TPRM)

## Baseline
- Encryption in transit (TLS) required for UI/API.
- Encryption at rest required for stored customer data.
- Strong authentication (SSO/MFA) required for admin access.

## Key management expectations (practical)
- Key rotation practice documented (vendor-managed keys acceptable for many SaaS).
- Separation of duties for key access.
- Controlled access to encryption key material.

## Higher assurance (High/Critical, when feasible)
- Options such as BYOK/CMK noted if offered (not mandatory unless risk requires).
- Audit logging for key access operations.
- Incident handling includes crypto key exposure scenario response.
