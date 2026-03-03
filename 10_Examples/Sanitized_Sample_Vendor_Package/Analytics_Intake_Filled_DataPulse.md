<!--
Document ID: TPRM-10-ANL-INTAKE
Title: Vendor Intake — DataPulse Analytics (Sanitized, High Tier)
Author/Owner: Badr Karim | Cybersecurity GRC Intern | Security Assurance | Risk-Based Controls | Compliance
LinkedIn: https://www.linkedin.com/in/badrkarim/
Version: 1.0
Effective Date: 2026-03-03
Review Cycle: Annual (or on major change)
Classification: Internal (Portfolio)
Note: Not legal advice. Templates are portfolio-grade and must be adapted to organizational context.
-->

# Vendor Intake Form — Filled (Sanitized Example)

Vendor: **DataPulse Analytics (Data Analytics / Data Processor)** *(sanitized example)*  
Tier: **High**  
Data: **Large-scale PII (Confidential/Restricted)**  
Access: **API + Batch File Transfer** (no VPN/privileged internal access)

## Vendor profile
- Vendor name: DataPulse Analytics *(sanitized)*
- Service description: Analytics platform used to process customer engagement and product usage events to generate performance insights and segmentation.
- Business owner/sponsor: Growth Analytics (Role)
- Vendor security contact: security@datapulse.example *(placeholder)*
- Contract start/renewal: 2026-04-01 / 2027-04-01 *(planned)*

## Data & privacy
- Data classification: **Confidential/Restricted**
- PII involved: **Yes (large-scale)**
  - Typical fields: customer identifiers (email/ID), device identifiers, usage events, region/state, account identifiers.
- Sensitive data: No PCI/PHI; but scale + identifiers create elevated privacy exposure.
- Processing purpose: analytics and performance reporting limited to contracted purpose (Condition **C-06**).
- Data minimization requirement: only required fields; no free-text ingestion; field allowlist enforced (Condition **C-07**).
- Retention requirement: defined schedule + verifiable deletion (Condition **C-07**).
- Deletion/return at termination: required with confirmation; must propagate to subprocessors (Condition **C-06**).

## Access & connectivity
- Access type: **API + batch file transfer**
  - Inbound: event files pushed to vendor bucket / SFTP / HTTPS upload (sanitized design)
  - Outbound: aggregate analytics exports
- Privileged access required: **No** (no VPN/admin access to customer infrastructure)
- Integration points:
  - API keys/tokens for ingestion endpoints
  - Scheduled exports (reports only, no raw PII export unless required)

## Cloud model
- Vendor-hosted SaaS
- Data residency preference: **US-only**
- Encryption expectations: TLS in transit + encryption at rest required
- Key management: vendor-managed acceptable with evidence; contract must define safeguards (EV-034)

## Subprocessors / fourth parties
- Uses subprocessors: **Yes**
- Requirement for High tier: list + flow-down + time-bound change notification (Condition **C-06**)

## Assurance artifacts
- SOC 2 Type II: Yes (summary/bridge letter under NDA) — EV-034
- Security policies summary: Yes (sanitized index) — EV-036
- IR plan summary: Yes — EV-035

## Operational criticality
- Service criticality: Medium/High (business impact but not production availability)
- Primary risk driver: privacy exposure from scale of PII processing

## Inherent Risk Summary
- Inherent risk score: **67 (High)**
- Drivers:
  - Large-scale PII processing
  - Retention + deletion + rights readiness obligations
  - Subprocessors/toolchain risk
