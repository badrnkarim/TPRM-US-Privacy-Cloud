<!--
Document ID: TPRM-10-ANL-RRW
Title: Residual Risk Worksheet — DataPulse Analytics (High Tier)
Author/Owner: Badr Karim | Cybersecurity GRC Intern | Security Assurance | Risk-Based Controls | Compliance
LinkedIn: https://www.linkedin.com/in/badrkarim/
Version: 1.0
Effective Date: 2026-03-03
Review Cycle: Annual (or on major change)
Classification: Internal (Portfolio)
Note: Not legal advice. Templates are portfolio-grade and must be adapted to organizational context.
-->

# Residual Risk Worksheet — DataPulse Analytics (Sanitized)

## Inherent risk
Inherent Risk Score: **67 (High)**

## Control maturity (High-tier baseline)
- Purpose limitation + no secondary use: pending contract execution (EV-030) → 65
- Minimization (field allowlist): defined but must be enforced/validated (EV-031) → 70
- Retention + deletion + confirmation: workflow exists, SLA pending (EV-032) → 65
- DSAR readiness: process defined, SLA + subprocessor propagation pending (EV-033) → 65
- Subprocessor governance: list present; notice window pending (EV-037) → 65
- Security safeguards + assurance: SOC2 summary + controls (EV-034/036/038) → 80
- IR readiness: present; notification SLA pending in contract (EV-035) → 70

Overall Control Maturity (judgement): **74/100**

## Evidence confidence
Evidence is strong for security posture; privacy commitments depend on contract clauses and proof of deletion propagation.  
Evidence Confidence: **0.85**

## Residual risk calculation
ResidualRisk = 67 × (1 − 0.74) × 0.85  
= 67 × 0.26 × 0.85 ≈ **15**

## Outcome
Residual risk ~15 supports **Approve with Conditions** (C-06, C-07).
