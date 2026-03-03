<!--
Document ID: TPRM-13-VRS-CRM
Title: Sample Vendor Risk Summary — AcmeCRM (Closure Demonstration)
Author/Owner: Badr Karim | Cybersecurity GRC Intern | Security Assurance | Risk-Based Controls | Compliance
LinkedIn: https://www.linkedin.com/in/badrkarim/
Version: 1.0
Effective Date: 2026-03-03
Review Cycle: Annual (or on major change)
Classification: Internal (Portfolio)
Note: Not legal advice. Portfolio-grade templates must be adapted to organizational context.
-->

# Vendor Risk Summary (One Page) — AcmeCRM (Sanitized)

## Vendor + decision request
- Vendor: AcmeCRM (SaaS CRM)
- Service: CRM for sales/customer success operations
- Tier: High
- Decision requested: **Approve (post-closure)**
- Business Owner: Sales Ops (role)
- GRC Owner: Badr Karim
- Go-live / renewal date: Portfolio scenario

## Business value
Supports revenue pipeline execution and customer lifecycle operations.

## Data + access scope
- Data classification: Confidential
- PII involved: Yes
- Access paths: SSO + API (+ app admin)
- Subprocessors: Yes (disclosed/contracted)

## Risk snapshot
- Inherent: 58 (High)
- Control maturity (post-closure): 85/100 (closure of contract + API governance)
- Evidence confidence: 0.90
- Residual risk: low enough for approval (closure demonstrated via EV-010 + EV-011)

## Top risks + mitigation
1) Secondary use / privacy misalignment  
   - Impact: privacy/regulatory exposure  
   - Mitigation: executed privacy annex (EV-010)
2) Retention/deletion enforceability  
   - Impact: inability to confirm deletion at termination  
   - Mitigation: contract clauses + deletion confirmation terms (EV-010)
3) API token governance weakness  
   - Impact: expanded data exposure via integration path  
   - Mitigation: allowlisting + rotation + least scopes + deprovisioning controls (EV-011)

## Evidence status
- EV-INDEX updated: Yes
- Key evidence: EV-010 (Accepted), EV-011 (Accepted)

## Recommendation
Approve. Remaining risk is managed through enforceable terms and validated governance controls.
