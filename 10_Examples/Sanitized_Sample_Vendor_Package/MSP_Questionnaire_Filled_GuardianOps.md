<!--
Document ID: TPRM-10-MSP-DDQ
Title: Due Diligence — GuardianOps MSP (Sanitized, Critical Tier)
Author/Owner: Badr Karim | Cybersecurity GRC Intern | Security Assurance | Risk-Based Controls | Compliance
LinkedIn: https://www.linkedin.com/in/badrkarim/
Version: 1.0
Effective Date: 2026-03-03
Review Cycle: Annual (or on major change)
Classification: Internal (Portfolio)
Approvers: Security (Owner) + Privacy + Legal (roles)
-->

# Vendor Due Diligence Questionnaire — Filled (Critical Tier, Sanitized Example)

Vendor: **GuardianOps MSP**  
Tier: **Critical**  
Scope: **VPN + privileged admin + remote tooling**

Evidence references: EV-### in `06_Evidence/EV-INDEX.csv`

---

## A) Governance + accountability
- Security governance documented; roles and escalation path established (**EV-023**).
- Background screening + security training controls required (**EV-025**).

## B) US privacy & data handling (service provider expectations)
- Purpose limitation and restricted processing must be contractually enforced (**EV-010 / C-03** style requirements).
- Retention + deletion/return commitments required with verifiable confirmation (**C-03**).
- Subprocessor transparency + flow-down + change notification required (**EV-026 / C-03**).

## C) Access control (Critical drivers)
- Privileged access must be **JIT/JEA** where feasible, with session logging (**EV-020 / C-04**).
- VPN access must be restricted by allowlisting, device posture, and MFA (**EV-021 / C-04**).
- Remote tooling must support session recording/command logging where possible (**EV-020 / EV-024**).

## D) Logging + monitoring
- Customer must receive exportable admin/support logs for SIEM ingestion (**EV-024**).
- Log retention and integrity controls documented (**EV-024**).

## E) Incident response + breach readiness
- IR plan exists with time-bound notification commitments in contract (**EV-023 / C-03**).

## F) Security testing + vulnerability management
- Independent testing evidence required (pen test / VA summaries) (**EV-027**).
- Patch SLAs and escalation for critical findings required (**EV-027**).

## G) Resilience
- BC/DR controls and test evidence required given operational criticality (**EV-028**).

## H) Assurance artifacts (Critical requirement)
- SOC 2 Type II (or equivalent) required to reach “Approved” status for Critical tier (**EV-022 / C-05**).
