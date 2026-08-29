# Vendor / Third-Party Risk Management Policy

**Organization:**(placeholder — replace with your organization name)*
**Document Owner:** Chief Information Security Officer (CISO)
**Classification:** Internal
**Version:** 1.0
**Effective Date:** 2026-08-29
**Next Review Date:** 2027-08-29
**Approved By:** [Executive Sponsor / Board of Directors]

---

## Document Control

| Version | Date | Author | Summary of Changes |
|---|---|---|---|
| 0.1 | 2026-08-15 | GRC Analyst | Initial draft |
| 1.0 | 2026-08-29 | GRC Analyst | Approved baseline version |

**Review cycle:** Reviewed annually, and following any significant change to the vendor risk landscape or relevant legal/regulatory requirements.

---

## 1. Purpose

This policy defines how NovaGrid Technologies Ltd ("the Company") identifies, assesses, monitors, and manages information security and privacy risk arising from vendors, suppliers, and other third parties that access, process, store, or transmit Company or customer data, or that provide services supporting Company operations.

## 2. Scope

This policy applies to all third parties engaged by the Company, including:

- Software-as-a-Service (SaaS) and cloud infrastructure providers.
- Outsourced service providers (e.g., payroll, customer support, development).
- Subcontractors and downstream vendors (fourth parties) engaged by a primary vendor.
- Any third party granted access to Company systems, facilities, or data.

It does not apply to purely public, non-contractual information sources with no data or system access.

## 3. Policy Statement

The Company will not engage a third party that creates unacceptable information security or privacy risk. Third-party risk is managed proportionately to the sensitivity of data involved, the criticality of the service, and the level of system access granted — applying greater scrutiny to higher-risk relationships and lighter-touch review to low-risk ones.

## 4. Roles & Responsibilities

| Role | Responsibility |
|---|---|
| **CISO / GRC Function** | Owns the third-party risk process; defines risk tiering criteria; approves higher-risk engagements; maintains the vendor risk register. |
| **Business/Engagement Owner** | Initiates vendor engagement requests; provides business context; ensures ongoing vendor performance and compliance. |
| **Procurement/Legal** | Ensures security and data protection terms are incorporated into contracts and Data Processing Agreements (DPAs). |
| **Vendor** | Completes due diligence questionnaires accurately; notifies the Company of material changes to its risk profile (e.g., breaches, subcontracting changes) within agreed timeframes. |

## 5. Third-Party Risk Lifecycle

### 5.1 Risk Tiering

New vendors are tiered at intake based on factors including: data sensitivity accessed, type of system access, criticality to business operations, and whether the vendor is a data processor under applicable data protection law. Typical tiers:

| Tier | Description | Example |
|---|---|---|
| **Tier 1 – Critical** | Access to Confidential/Restricted data, or business-critical service | Cloud hosting provider, HR/payroll system |
| **Tier 2 – Moderate** | Limited data access or moderate operational reliance | Marketing analytics tool |
| **Tier 3 – Low** | No data access, low operational impact | Office supplies vendor |

### 5.2 Due Diligence (Pre-Engagement)

- Tier 1 and Tier 2 vendors complete a security questionnaire (e.g., SIG Lite or SIG Core, scaled to tier) prior to onboarding.
- Evidence review may include: SOC 2 Type II report, ISO 27001 certificate, penetration test summary, or equivalent assurance artifacts.
- Identified gaps are logged, risk-assessed, and either remediated by the vendor, accepted with sign-off, or result in the engagement not proceeding.
- Findings and risk tier are documented in the vendor risk register prior to contract execution.

### 5.3 Contracting

- Contracts with Tier 1 and Tier 2 vendors include security and data protection requirements proportionate to risk (e.g., breach notification timelines, right-to-audit, data return/deletion on termination).
- A Data Processing Agreement (DPA) is executed with any vendor that processes personal data on the Company's behalf.

### 5.4 Ongoing Monitoring & Reassessment

- Tier 1 vendors are reassessed at least annually; Tier 2 vendors periodically (e.g., every 18–24 months); Tier 3 vendors on an ad hoc basis.
- Reassessment includes requesting updated assurance evidence (e.g., current SOC 2 report) and re-confirming the risk tier is still accurate.
- Material adverse events (e.g., a vendor breach notification, a critical vulnerability disclosure, an M&A event affecting the vendor) trigger an off-cycle reassessment.

### 5.5 Offboarding

- On contract termination, the Company confirms return or secure destruction of Company/customer data held by the vendor, and revokes any system access granted to the vendor.

## 6. Escalation & Reporting

Unresolved critical or high findings from vendor assessments are escalated to the CISO and, where risk appetite is exceeded, to executive leadership for a formal risk acceptance decision. The vendor risk register is reviewed at least quarterly as part of the Company's broader risk governance process.

## 7. Related Documents

- Information Security Policy
- Data Protection / Privacy Policy
- Incident Response Plan

---

## Appendix A — Framework Crosswalk

| Policy Section | ISO/IEC 27001:2022 Annex A Reference | SOC 2 Trust Services Criteria |
|---|---|---|
| 5.1 Risk Tiering | A.5.19 (Information Security in Supplier Relationships) | CC9.2 |
| 5.2 Due Diligence | A.5.20 (Addressing Security Within Supplier Agreements), A.5.21 (ICT Supply Chain) | CC9.2 |
| 5.3 Contracting | A.5.20, A.5.22 (Monitoring, Review and Change Management of Supplier Services) | CC9.2 |
| 5.4 Ongoing Monitoring & Reassessment | A.5.22 | CC9.2, CC3.2 |
| 5.5 Offboarding | A.5.20, A.5.11 (Return of Assets) | CC9.2, CC6.5 |
| 6. Escalation & Reporting | A.5.4 (Management Responsibilities), A.5.35 (Independent Review) | CC3.2, CC9.2 |


