<!--
Document ID: TPRM-10-ANL-ROPA
Title: RoPA-lite — DataPulse Analytics (Sanitized)
Author/Owner: Badr Karim | Cybersecurity GRC Intern | Security Assurance | Risk-Based Controls | Compliance
LinkedIn: https://www.linkedin.com/in/badrkarim/
Version: 1.0
Effective Date: 2026-03-03
Review Cycle: Annual (or on major change)
Classification: Internal (Portfolio)
Note: Not legal advice. Templates are portfolio-grade and must be adapted to organizational context.
-->

# RoPA-lite (Vendor Processing Record) — Filled (Sanitized Example)

## Vendor + service
- Vendor: DataPulse Analytics
- Service: Data analytics platform (event processing + aggregated insights)
- Subprocessors: Yes (EV-037)

## Processing purpose
- Purpose: analytics and reporting for business performance insights
- Processing activities: ingest → transform → aggregate → report

## Data categories
- Classification: Confidential/Restricted
- Personal data: customer identifiers (email/ID), device identifiers, account IDs
- Sensitive: no PCI/PHI; scale elevates privacy risk

## Data flows
- Source: internal event pipeline / product telemetry
- Destination: vendor SaaS analytics environment
- Transfers: US-only preferred; cross-border must be disclosed and approved (EV-037)

## Retention + deletion
- Retention schedule: must be contract-defined (C-07)
- Deletion method: workflow + confirmation + subprocessor propagation (C-06)

## Security measures (high-level)
- Auth: scoped API tokens; least privilege
- Encryption: TLS + at-rest encryption
- Logging: ingestion + admin logs exportable (EV-038)
- IR readiness: EV-035

## Rights support (contractual)
- Export: aggregate reports; raw export only if contract requires
- Deletion: supported with SLA + confirmation (C-06)
