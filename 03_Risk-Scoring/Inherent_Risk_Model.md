<!--
Author/Owner: Badr Karim | Cybersecurity GRC Intern | Security Assurance | Risk-Based Controls | Compliance
LinkedIn: https://www.linkedin.com/in/badrkarim/
Last updated: 2026-03-03
Classification: Internal (Portfolio)
-->

# Inherent Risk Model (0–100) — US Privacy + Cloud Data Protection

## Purpose
Score inherent risk based on **impact + exposure** before considering vendor control maturity.

## Scoring method
Each factor is scored 0–5, then weighted. Total = 0–100.

### Factors and weights
| Factor | Weight | What “5” means |
|---|---:|---|
| Data sensitivity & classification | 25 | Restricted data and/or large-scale PII |
| Access level | 20 | Privileged admin / VPN / production access |
| Business criticality | 15 | Outage causes material business impact |
| Privacy/regulatory exposure (US) | 15 | Consumer data + rights/retention obligations + contractual privacy exposure |
| Cloud architecture complexity | 10 | Multiple integrations, agents, deep access paths |
| Fourth-party/subprocessor risk | 10 | Subprocessors handle sensitive data or are not transparent |
| Incident history / public exposure | 5 | Prior incidents or weak disclosure posture |

### Tier thresholds
- 0–24: Low
- 25–44: Medium
- 45–69: High
- 70–100: Critical

## Scoring guide (quick)
- Data sensitivity: 0 (Public) → 5 (Restricted/PII at scale)
- Access: 0 (none) → 5 (privileged/network/code access)
- Privacy exposure: 0 (no personal data) → 5 (PII + retention + rights + service provider obligations)
- Cloud complexity: 0 (simple) → 5 (agents, deep integrations, privileged paths)
- Fourth-party risk: 0 (none) → 5 (multiple subprocessors, unclear controls)

## Output
1) Total score (0–100)
2) Tier (Low/Medium/High/Critical)
3) Required control baseline (from Standard) + evidence list
