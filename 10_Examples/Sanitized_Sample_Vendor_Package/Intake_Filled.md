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

# Intake — AcmeCRM (Sanitized Example)
Vendor type: **SaaS CRM**  
Tier: **High**  
Data: **PII (Confidential)**  
Access: **SSO + API** (+ CRM admin role)

## Summary
AcmeCRM is used for lead/contact/account lifecycle and customer engagement tracking. Risk drivers: PII, admin capability inside SaaS, API integration, subprocessors.

## Key requirements
- DPA/privacy clauses for purpose limitation, retention/deletion, subprocessors, breach notification (Condition C-01)
- API governance hardening (Condition C-02)
