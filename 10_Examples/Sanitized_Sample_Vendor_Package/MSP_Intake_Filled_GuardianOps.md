<!--
Document ID: TPRM-10-MSP-INTAKE
Title: Vendor Intake — GuardianOps MSP (Sanitized, Critical Tier)
Author/Owner: Badr Karim | Cybersecurity GRC Intern | Security Assurance | Risk-Based Controls | Compliance
LinkedIn: https://www.linkedin.com/in/badrkarim/
Version: 1.0
Effective Date: 2026-03-03
Review Cycle: Annual (or on major change)
Classification: Internal (Portfolio)
Approvers: Security (Owner) + Privacy + Legal (roles)
-->

# Vendor Intake Form — Filled (Sanitized Example)
Vendor: **GuardianOps MSP (Managed Service Provider)** *(sanitized example)*  
Tier: **Critical**  
Data: **Restricted / Confidential operational + identifiers**  
Access: **VPN + Privileged Admin + Remote Support Tools**

## Vendor profile
- Vendor name: GuardianOps MSP *(sanitized)*
- Service: Managed IT operations (endpoint patching, remote support, monitoring, incident response support)
- Business owner / sponsor: IT Operations (Role)
- Vendor security contact: security@guardianops.example *(placeholder)*
- Contract start/renewal: 2026-04-01 / 2027-04-01 *(planned)*

## Data & privacy
- Data classification: **Restricted / Confidential**
- Personal data involved (PII): **Yes (operational identifiers)**
  - Typical: employee names/emails in tickets, device identifiers, IPs, logs, admin activity records
- Sensitive data types: credentials/secrets exposure risk if access is not tightly controlled
- Processing purpose: IT operations support + endpoint management + remote troubleshooting
- Retention/deletion: Must be defined and contractually enforceable (Condition **C-03**)
- Deletion/return at termination: required with confirmation (Condition **C-03**)

## Access & connectivity
- Access type: **VPN + Privileged Admin**
  - Remote support tooling access to endpoints (agent-based)
  - Privileged access to admin consoles required (Critical driver)
- Privileged access required: **Yes**
- Integration points:
  - VPN access into management network segment
  - Remote management agent + ticketing integration
  - Log export into customer SIEM (required — EV-024)

## Cloud model
- Hybrid: vendor tools (SaaS) + customer environment access
- Region/residency: US preferred; subprocessor transparency required (EV-026)
- Encryption: required for all channels; key handling clarified in contract (C-03)

## Subprocessors / fourth parties
- Uses subprocessors: **Yes (common for MSP tooling)**
- Requirement: subprocessor list + flow-down + time-bound change notification (C-03)

## Assurance artifacts
- SOC 2 Type II: **Required for Critical** (EV-022) — currently **Pending**
- Pen test / security testing evidence: required (EV-027)
- Policies (IR, access control, background checks): required (EV-023, EV-025)

## Operational criticality
- Service criticality: **Critical**
- Outage/compromise impact: Direct impact to availability and security of internal environment.

## Inherent Risk Summary
- Inherent risk score: **86 (Critical)**
- Drivers:
  - Privileged access + remote tooling
  - Potential secrets exposure pathway
  - Broad operational visibility (logs/tickets/identifiers)
  - Subprocessor/toolchain risk
