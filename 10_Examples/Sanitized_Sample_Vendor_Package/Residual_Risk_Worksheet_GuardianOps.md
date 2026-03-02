<!--
Document ID: TPRM-10-MSP-RRW
Title: Residual Risk Worksheet — GuardianOps MSP (Critical Tier)
Author/Owner: Badr Karim | Cybersecurity GRC Intern | Security Assurance | Risk-Based Controls | Compliance
LinkedIn: https://www.linkedin.com/in/badrkarim/
Version: 1.0
Effective Date: 2026-03-03
Review Cycle: Annual (or on major change)
Classification: Internal (Portfolio)
Approvers: Security (Owner) + Privacy + Legal (roles)
-->

# Residual Risk Worksheet — GuardianOps MSP (Sanitized)

## Inherent risk
- Inherent Risk Score: **86 (Critical)**

## Control maturity (Critical-tier baseline)
Key control groups:
- Privileged access controls (JIT/JEA, session logging): **Pending hardening** (EV-020/EV-021)
- Logging & SIEM export: acceptable (EV-024)
- IR readiness + notification posture: acceptable but contract SLA must be explicit (EV-023 / C-03)
- Subprocessor governance: requires contract flow-down and notice window (EV-026 / C-03)
- Independent testing & vuln mgmt: acceptable (EV-027)
- BC/DR: acceptable (EV-028)
- SOC 2 Type II assurance: **Pending** (EV-022)

**Control Maturity:** 70/100 (due to pending privileged-access hardening + assurance artifact)

## Evidence confidence
Evidence is partial for Critical tier until SOC2 is received and access hardening is validated.  
**Evidence Confidence:** 0.80

## Residual risk calculation
ResidualRisk = InherentRisk × (1 − ControlMaturity) × EvidenceConfidence  
= 86 × (1 − 0.70) × 0.80  
= 86 × 0.30 × 0.80 ≈ **21**

## Outcome
Residual risk ~21 supports **Conditional Approval** for business-critical need, with strict conditions and compensating controls.
