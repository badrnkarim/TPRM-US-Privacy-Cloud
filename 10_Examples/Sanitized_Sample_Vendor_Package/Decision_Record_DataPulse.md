<!--
Document ID: TPRM-10-ANL-DEC
Title: Decision Record — DataPulse Analytics (High Tier)
Author/Owner: Badr Karim | Cybersecurity GRC Intern | Security Assurance | Risk-Based Controls | Compliance
LinkedIn: https://www.linkedin.com/in/badrkarim/
Version: 1.0
Effective Date: 2026-03-03
Review Cycle: Annual (or on major change)
Classification: Internal (Portfolio)
Note: Not legal advice. Templates are portfolio-grade and must be adapted to organizational context.
-->

# Decision Record — DataPulse Analytics (Sanitized)

Vendor: DataPulse Analytics  
Tier: High  
Data: Confidential/Restricted PII at scale  
Access: API + batch file transfer  
Decision Date: 2026-03-03

## Summary
- Inherent Risk: 67 (High)
- Control Maturity: 74/100
- Evidence Confidence: 0.85
- Residual Risk: ~15

## Decision
✅ **Approve with Conditions**

Rationale:
- Security posture acceptable with assurance evidence.
- Privacy controls require explicit contractual commitments and operational proof for retention/deletion and DSAR propagation.

## Conditions (2)
### C-06 — Execute Privacy Annex for Purpose + DSAR + Subprocessors + Breach SLA
Contract/DPA must explicitly enforce:
- purpose limitation / no secondary use
- DSAR support obligations + response SLAs
- subprocessor flow-down + time-bound change notification
- time-bound incident/breach notification commitment
**Due:** 2026-04-17  
**Evidence:** EV-030 executed; EV-033 DSAR workflow confirmed; EV-037 notice window confirmed

### C-07 — Retention/Minimization Controls + Verifiable Deletion
Implement and evidence:
- field allowlist/minimization enforced for ingestion
- retention schedule configured
- deletion confirmation method + deletion propagation to subprocessors
**Due:** 2026-04-17  
**Evidence:** EV-031 validated; EV-032 deletion + retention proof

## Compensating controls (until closure)
- ingest only minimal fields (temporary allowlist)
- restrict exports to aggregated data only
- monthly review of retention configuration and deletion logs (as available)

## Monitoring
Annual reassessment (High tier) or earlier on data scope increase, new subprocessors, incident, or major integration change.
