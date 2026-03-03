<!--
Document ID: TPRM-13-SMP-MSP
Title: Sample Risk Committee Brief — GuardianOps MSP (Critical Tier)
Author/Owner: Badr Karim | Cybersecurity GRC Intern | Security Assurance | Risk-Based Controls | Compliance
LinkedIn: https://www.linkedin.com/in/badrkarim/
Version: 1.0
Effective Date: 2026-03-03
Review Cycle: Annual (or on major change)
Classification: Internal (Portfolio)
Note: Not legal advice. Templates are portfolio-grade and must be adapted to organizational context.
-->

# Risk Committee Brief — GuardianOps MSP (Critical Tier)

## Decision requested
✅ Approve with Conditions (Critical-tier)

## Why leadership is needed
Vendor requires **VPN + privileged admin access**, creating pathways to material security impact.

## Business dependency
Managed IT operations support; interruption impacts operational continuity.

## Risk posture
- Inherent: 86 (Critical)
- Residual: ~21
- Top risks: privileged access misuse, remote tooling abuse, insufficient independent assurance.

## Must-close conditions
- C-04 Privileged/VPN hardening: JIT/JEA where feasible, session logging, allowlisting + posture + MFA (EV-020/021)
- C-05 Assurance artifact: SOC 2 Type II or equivalent (EV-022)

## Compensating controls (immediate)
- Customer-owned break-glass accounts, time-bound access only
- Segmented management network
- Mandatory SIEM log export + weekly review until closure

## Ask
Approve conditional to meet business need while enforcing strict time-bound closure of critical controls.
