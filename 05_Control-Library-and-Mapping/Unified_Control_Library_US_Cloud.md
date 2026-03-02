<!--
Author/Owner: Badr Karim | Cybersecurity GRC Intern | Security Assurance | Risk-Based Controls | Compliance
LinkedIn: https://www.linkedin.com/in/badrkarim/
Last updated: 2026-03-03
Classification: Internal (Portfolio)
-->

# Unified Control Library — US Privacy + Cloud Data Protection (TPRM)

**Purpose:** A single control set used for vendor requirements, mapped at a high level to:
- NIST CSF 2.0 (GV/ID/PR/DE/RS/RC)
- ISO 27001/27002 (control intent areas)
- SOC 2 (Common Criteria intent)
- COBIT (governance/control objectives intent)
- ISO 37301 (compliance management intent)

> This library is written to be usable and reviewable. Exact numbering varies by organization; mapping here is intentional and defensible at the “intent” level.

## Control IDs (sample core set)
| ID | Control | Applies | NIST CSF 2.0 | Evidence examples |
|---|---|---|---|---|
| TPRM-US-CLD-001 | Data use limited to contracted purpose | PII vendors | GV/ID | DPA terms, policy statement |
| TPRM-US-CLD-002 | Data minimization and collection limits | PII vendors | GV/ID | data schema, intake mapping |
| TPRM-US-CLD-003 | Retention schedule + deletion process | PII vendors | GV/PR | retention policy, deletion logs |
| TPRM-US-CLD-004 | Consumer/contract rights support (delete/access/correct) | PII vendors | GV | process doc, ticket workflow |
| TPRM-US-CLD-005 | Subprocessor governance + change notification | High+ | GV | subprocessor list, flow-down terms |
| TPRM-US-CLD-006 | Encryption in transit | Medium+ | PR | architecture statement |
| TPRM-US-CLD-007 | Encryption at rest | Medium+ | PR | storage encryption statement |
| TPRM-US-CLD-008 | Strong authentication (SSO/MFA) | Medium+ | PR | SSO/MFA screenshots |
| TPRM-US-CLD-009 | Privileged access controls | High+ | PR/DE | PAM policy, access logs |
| TPRM-US-CLD-010 | Logging of access/admin/security events | Medium+ | DE | log retention config |
| TPRM-US-CLD-011 | Vulnerability management + patch SLAs | High+ | PR/DE | scan cadence, SLA doc |
| TPRM-US-CLD-012 | Incident response plan + notification | High+ | RS | IR plan, contact path |
| TPRM-US-CLD-013 | BC/DR plan + test evidence | High+ | RC | DR test summary |
| TPRM-US-CLD-014 | Secure SDLC (if software) | High+ | PR | SDLC policy, CI checks |
| TPRM-US-CLD-015 | Independent assurance evidence | Critical | GV | SOC2/ISO letter/summary |

## Tier baseline
- Low: 001–003 + confidentiality + incident contact
- Medium: add 006–010
- High: add 005 + 011–014
- Critical: add 015 + stronger evidence requirements
