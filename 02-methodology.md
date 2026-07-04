# Methodology

## Maturity scale

Each in-scope control was scored against a 0–5 maturity scale (adapted from a
CMMI-style model commonly used in ISO 27001 readiness work):

| Score | Level | Description |
|---|---|---|
| 0 | Not Implemented | No control activity exists |
| 1 | Ad Hoc | Control performed inconsistently, undocumented, person-dependent |
| 2 | Repeatable | Control performed consistently but informally; no documented process |
| 3 | Defined | Control is documented, approved, and communicated |
| 4 | Managed | Control is measured, monitored, and has defined ownership |
| 5 | Optimized | Control is continuously improved using metrics and feedback loops |

**Target maturity** for this engagement was set at **Level 3 (Defined)** as the minimum
bar for ISO 27001 certification readiness, with select controls (privileged access,
cloud service security) targeted at **Level 4 (Managed)** given Meridian Trust's
regulatory exposure.

## Risk scoring model

For each control:

```
Maturity Gap = Target Maturity − Current Maturity
Impact Weight = 3 (High) | 2 (Medium) | 1 (Low)   — business impact if the gap is exploited/audited
Risk Score = Maturity Gap × Impact Weight
```

Risk Score is then translated into a **Risk Rating**:

| Risk Score | Rating |
|---|---|
| 9–15 | Critical |
| 6–8 | High |
| 3–5 | Medium |
| 0–2 | Low |

Business Impact ratings were assigned based on: (a) whether the control maps to a
banking-partner contractual requirement, (b) whether a gap would be a likely audit
finding under ISO 27002:2022 guidance, and (c) potential impact to customer data or
payment processing integrity if the control failed.

## Prioritization

Remediation items are sequenced primarily by Risk Rating (Critical first), with ties
broken by implementation effort (lower-effort items pulled forward within the same
rating band) so that the roadmap front-loads high-risk, low-effort wins.

## Limitations

This is a portfolio demonstration project. Evidence descriptions, interview findings,
and vendor names are illustrative rather than drawn from a live audit trail. The scoring
model and control structure, however, mirror the approach used in real ISO 27001
readiness assessments.
