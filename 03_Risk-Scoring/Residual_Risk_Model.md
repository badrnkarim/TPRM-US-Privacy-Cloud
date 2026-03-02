# Residual Risk Model — Control Maturity + Evidence Confidence

## Purpose
Convert inherent risk into residual risk based on:
- **Control maturity** (does the vendor meet the required controls?)
- **Evidence confidence** (is proof strong, current, and consistent?)

## Step 1 — Control maturity score (0–100)
Evaluate required controls by tier and rate maturity:
- 0–39: weak / gaps
- 40–69: partial / compensating controls needed
- 70–89: strong / minor gaps
- 90–100: robust / well-evidenced

## Step 2 — Evidence confidence factor (0.7–1.0)
- 1.0 = third-party assurance (SOC2 Type II / ISO cert) + current evidence
- 0.85 = strong internal evidence, consistent and current
- 0.7 = screenshots only / outdated / incomplete

## Step 3 — Residual risk calculation (simple, defensible)
ResidualRisk = InherentRisk × (1 - (ControlMaturity/100)) × EvidenceConfidence

## Decision mapping (general)
- Residual < 10: Approve
- 10–25: Approve with conditions (remediation deadlines)
- > 25: Reject or require executive exception + compensating controls
