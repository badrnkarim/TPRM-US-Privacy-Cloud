<!--
Document ID: TPRM-10-MSP-DEC
Title: Decision Record — GuardianOps MSP (Critical Tier)
Author/Owner: Badr Karim | Cybersecurity GRC Intern | Security Assurance | Risk-Based Controls | Compliance
LinkedIn: https://www.linkedin.com/in/badrkarim/
Version: 1.0
Effective Date: 2026-03-03
Review Cycle: Annual (or on major change)
Classification: Internal (Portfolio)
Approvers: Security (Owner) + Privacy + Legal (roles)
-->

# Decision Record — GuardianOps MSP (Sanitized)

Vendor: **GuardianOps MSP**  
Tier: **Critical**  
Access: **VPN + Privileged Admin**  
Decision Date: 2026-03-03

## Summary
- Inherent Risk: 86 (Critical)
- Control Maturity: 70/100
- Evidence Confidence: 0.80
- Residual Risk: ~21

## Decision
✅ **Approve with Conditions (Critical-tier conditional approval)**  
**Executive/Risk Committee sign-off required in a real organization.** (Portfolio simulation)

### Why conditional (not full approval)
- MSP privileged access creates high impact pathways.
- Assurance artifacts and privileged access hardening must be completed to reduce residual risk.

## Conditions (2 items — strict)
### C-04 — Privileged Access + VPN Hardening (Critical requirement)
Implement and evidence:
- JIT/JEA privileged access (or documented least-privilege alternative)
- Session logging/recording for privileged actions where supported
- VPN access restrictions: allowlisting + device posture checks + MFA
Evidence: **EV-020 + EV-021**  
Due: **2026-04-17**

### C-05 — Independent Assurance Artifact (Critical requirement)
Provide SOC 2 Type II (preferred) or equivalent independent assurance evidence acceptable to Security/Legal.
Evidence: **EV-022**  
Due: **2026-04-17**

## Compensating controls (until closure)
- Separate “break-glass” privileged accounts owned by customer; vendor gets time-bound access only
- Dedicated management network segment; no lateral movement
- Mandatory log export to customer SIEM; weekly review during remediation window
- Ticket-based approval for privileged sessions

## Monitoring
- Continuous monitoring + annual reassessment
- Immediate reassessment on incident, toolchain/subprocessor change, or access scope change
