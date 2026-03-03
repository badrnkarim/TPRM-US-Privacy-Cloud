<!--
Document ID: TPRM-10-ANL-DDQ
Title: Due Diligence — DataPulse Analytics (Sanitized, High Tier)
Author/Owner: Badr Karim | Cybersecurity GRC Intern | Security Assurance | Risk-Based Controls | Compliance
LinkedIn: https://www.linkedin.com/in/badrkarim/
Version: 1.0
Effective Date: 2026-03-03
Review Cycle: Annual (or on major change)
Classification: Internal (Portfolio)
Note: Not legal advice. Templates are portfolio-grade and must be adapted to organizational context.
-->

# Vendor Due Diligence Questionnaire — Filled (High Tier, Sanitized Example)

Vendor: **DataPulse Analytics**  
Tier: **High**  
Scope: **Large-scale PII processing (data analytics)**  
Evidence references: EV-### in `06_Evidence/EV-INDEX.csv`

---

## A) Processing purpose + data scope (privacy-critical)
- Processing purpose must be contractually limited (no secondary use) — **EV-030 / C-06**
- Field-level minimization required: allowlist only; no free-text ingestion — **EV-031 / C-07**

## B) Retention + deletion (privacy-critical)
- Vendor provides retention configuration and deletion workflow — **EV-032**
- Condition: define retention schedule, deletion SLA, deletion confirmation, and deletion propagation to subprocessors — **EV-030 / C-06** and **EV-032 / C-07**

## C) DSAR / rights readiness (contractual support)
- Vendor must support contract-based deletion/export requests within defined SLAs — **EV-033 / C-06**
- Vendor must document how deletion affects backups/derived datasets — **EV-033 / C-06**

## D) Subprocessor governance
- Vendor must disclose subprocessors and provide time-bound change notification + flow-down obligations — **EV-037 / C-06**

## E) Cloud security safeguards
- Encryption in transit/at rest + access controls for ingestion endpoints — **EV-034 / EV-036**
- Logging available for admin/config + data ingestion endpoints; export on request — **EV-038**

## F) Incident response + breach readiness
- IR plan summary reviewed; notification SLA must be explicit in contract — **EV-035 / C-06**

## Assurance artifacts
- SOC 2 Type II summary/bridge letter evidence acceptable for High tier — **EV-034**
