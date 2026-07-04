# Remediation Roadmap

Controls are sequenced by risk rating (Critical → High → Medium → Low), with
low-effort items pulled forward within a rating band to front-load quick wins.
Target dates assume a start date of **2026-07-04**.

## Phase 1 — Days 0–60: Contain the highest risk items

| Control | Item | Owner | Target |
|---|---|---|---|
| A.8.2 | Stand up a PAM solution; reduce standing AWS admin accounts; enable privileged session logging | IT Manager | Day 60 |
| A.5.17 | Deploy secrets management (Azure Key Vault); rotate exposed service-account credentials | IT Manager | Day 45 |
| A.8.4 | Revoke former contractor GitHub access immediately; add revocation step to offboarding checklist | Engineering Lead | Day 30 |
| A.8.5 | Enable MFA on core platform admin console or apply compensating controls | IT Manager | Day 28 |

**Rationale:** these four items are either already-exploitable exposures (shared
credentials, active former-contractor access) or the assessment's sole Critical
finding. All are addressable without new organizational process — tooling and
configuration changes only.

## Phase 2 — Days 60–120: Formalize policy and process

| Control | Item | Owner | Target |
|---|---|---|---|
| A.5.19 | Build vendor risk tiering model + security due diligence questionnaire | GRC Analyst | Day 90 |
| A.5.15 | Draft and approve Access Control Policy; move provisioning into ticketing workflow | IT Manager | Day 90 |
| A.5.18 | Implement quarterly access recertification process | IT Manager | Day 100 |
| A.5.20 | Develop Information Security Exhibit for vendor contracts; begin retrofitting Tier 1 vendors | GRC Analyst + Legal | Day 120 |
| A.5.23 | Document Cloud Security Policy; select and begin CSPM tool rollout | IT Manager | Day 105 |

**Rationale:** these require policy drafting, cross-functional sign-off, and in
some cases legal/vendor negotiation, so they are scheduled after the Phase 1
tooling fixes are underway.

## Phase 3 — Days 120–180: Operationalize ongoing monitoring

| Control | Item | Owner | Target |
|---|---|---|---|
| A.5.22 | Launch annual vendor security review cycle (SOC 2 review + risk-tier reassessment) | GRC Analyst | Day 150 |
| A.5.21 | Require sub-processor disclosure from key vendors; add to vendor assessment cycle | GRC Analyst | Day 165 |
| A.8.3 | Document formal access control matrix | IT Manager | Day 130 |
| A.5.16 | Add JML procedure to the annual policy review calendar | HR Ops Lead | Day 135 |

**Rationale:** these are lower-risk items that primarily need to be embedded
into a recurring cadence rather than urgently fixed — appropriate to close out
the program once the higher-risk items are resolved.

## Post-remediation

At the end of Phase 3, re-run the gap analysis matrix (`assessment/ISO27001-Gap-Analysis-Matrix.xlsx`)
against updated current-state maturity to confirm all 13 controls have reached
their target maturity level before scheduling a Stage 1 certification audit.
