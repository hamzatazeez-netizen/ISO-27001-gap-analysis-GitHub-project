# Company Profile & Engagement Scope

## Company overview

**Meridian Trust Financial Services** is a fictional mid-size Canadian fintech
headquartered in Toronto, Ontario, offering digital lending and payment processing
services to small and medium-sized businesses across Canada. Founded in 2016, Meridian
Trust has grown to approximately 450 employees and processes payment and lending data
for roughly 60,000 SMB clients.

| Attribute | Detail |
|---|---|
| Industry | Financial services / fintech (lending & payments) |
| Employees | ~450 |
| Headquarters | Toronto, ON |
| Regulatory context | Provincially regulated lender; partners with two federally regulated banks for payment rails, bringing OSFI Guideline B-10 (third-party risk) expectations into scope indirectly |
| IT environment | Hybrid — AWS-hosted core platform, on-prem domain services at HQ, SaaS sprawl (HRIS, ticketing, CRM) |
| Key vendors | AWS (cloud infrastructure), a payment processor, a KYC/AML screening vendor, an HRIS provider |

## Why Meridian Trust is pursuing ISO 27001

Two of Meridian Trust's banking partners have started requiring ISO 27001 certification
(or a documented equivalent control set) as a condition of continued integration,
following updated third-party risk expectations from their own regulators. Meridian
Trust's leadership has committed to pursuing certification within 12 months and
commissioned an internal gap analysis as the first step.

## Engagement scope

This gap analysis is scoped to two Annex A control domains, selected because they
represent Meridian Trust's highest-exposure areas given its vendor-dependent
architecture and its need to demonstrate access governance to banking partners:

1. **Access Control** — A.5.15, A.5.16, A.5.17, A.5.18, A.8.2, A.8.3, A.8.4, A.8.5
2. **Supplier / Third-Party Relationships** — A.5.19, A.5.20, A.5.21, A.5.22, A.5.23

Out of scope for this phase: physical security controls, HR security (A.6.x), and the
remaining Annex A domains. These are noted as follow-on phases in the roadmap.

## Assessment approach

- **Method:** Document review (policies, vendor contracts, IAM configuration exports)
  plus structured interviews with the IT Manager, HR Ops lead, and the vendor holding
  the KYC/AML integration.
- **Standard reference:** ISO/IEC 27001:2022 Annex A, with ISO/IEC 27002:2022 used for
  implementation guidance interpretation.
- **Timeframe:** Point-in-time assessment, control state as of the assessment date.
- **Assessor:** Internal GRC analyst (this project's author), acting in an internal
  audit / readiness-assessment capacity — not a certification body audit.
