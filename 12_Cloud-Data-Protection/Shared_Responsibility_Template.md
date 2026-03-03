<!--
Document ID: TPRM-12-SRM
Title: Shared Responsibility Model Template (Cloud Vendor)
Author/Owner: Badr Karim | Cybersecurity GRC Intern | Security Assurance | Risk-Based Controls | Compliance
LinkedIn: https://www.linkedin.com/in/badrkarim/
Version: 1.0
Effective Date: 2026-03-03
Review Cycle: Annual (or on major change)
Classification: Internal (Portfolio)
Note: Not legal advice. Templates are portfolio-grade and must be adapted to organizational context.
-->

# Shared Responsibility Model (Template)

## Service model
- SaaS / PaaS / IaaS / MSP hybrid:
- Data stored/processed:
- Access paths (SSO/API/admin/VPN/support):

## Vendor responsibilities
- Platform security (patching, infra controls, tenant isolation)
- Encryption at rest/in transit (where applicable)
- Vulnerability management and testing
- Incident response and notification

## Customer responsibilities
- Identity governance (SSO configuration, role assignments)
- API token governance (scopes, rotation)
- Logging ingestion and monitoring
- Data minimization and retention settings (where configurable)

## Shared controls (must be clear)
- Privileged access handling
- Incident coordination and evidence preservation
- Subprocessor governance
