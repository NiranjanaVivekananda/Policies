# Tier 2/3 Vendor Due Diligence Checklist

**Companion to:** Third-Party Risk Management Policy, §5.2 (Due Diligence)
**Purpose:** A simplified, SIG Lite/Core-style checklist for vendors that do not warrant a full
Tier 1 assessment. Use this instead of a full SIG for Tier 2 vendors, and as an optional
lightweight check for higher-risk Tier 3 vendors.
**How to use:** Send the relevant sections to the vendor (or complete from public evidence, e.g.
a Trust Center page) and record the outcome, with tier and findings, in the Vendor Risk Register.

---

## Scope guidance

| Tier | Sections to complete | Evidence expected |
|---|---|---|
| **Tier 2 – Moderate** | All sections below | Self-attestation + one assurance artifact (SOC 2, ISO 27001 cert, or pen test summary) if available |
| **Tier 3 – Low** | Sections 1, 2, and 6 only | Self-attestation is sufficient |

---

## 1. Company & Engagement Overview

- [ ] Legal entity name and registered address confirmed
- [ ] Point of contact for security/privacy matters identified
- [ ] Description of service being provided
- [ ] Subcontractors or fourth parties involved in service delivery disclosed
- [ ] Countries/regions where data will be stored or processed disclosed

## 2. Data Handling

- [ ] Types of Company/customer data the vendor will access, store, or transmit (specify: PII, financial, health, confidential business data, none)
- [ ] Data retention period and deletion process described
- [ ] Data encrypted in transit (Y/N, method)
- [ ] Data encrypted at rest (Y/N, method)
- [ ] Vendor acts as a data processor under applicable data protection law (Y/N)
- [ ] Data Processing Agreement (DPA) required and executed (Y/N) — required if above is Y

## 3. Access Control & Authentication

- [ ] Multi-factor authentication (MFA) enforced for administrative/privileged access
- [ ] Role-based access control (RBAC) or least-privilege model in place
- [ ] User access reviewed on a defined periodic basis
- [ ] Access is revoked within a defined timeframe of role change or termination

## 4. Security Program & Assurance

- [ ] Written information security policy in place
- [ ] Independent assurance available (select one or more): SOC 2 Type II report / ISO 27001 certificate / recent penetration test summary / none
- [ ] Vulnerability management / patching process described
- [ ] Security awareness training provided to vendor staff

## 5. Incident & Breach Notification

- [ ] Documented incident response process in place
- [ ] Contractual breach notification timeframe to the Company specified (e.g., within 72 hours of confirmed breach)
- [ ] History of material security incidents in the past 24 months disclosed

## 6. Business Continuity & Termination

- [ ] Business continuity / disaster recovery plan exists
- [ ] Process for returning or securely destroying Company data upon contract termination confirmed
- [ ] Process for revoking vendor access to Company systems upon termination confirmed

---

## Outcome

| Field | Entry |
|---|---|
| Overall outcome | ☐ Proceed — no material gaps ☐ Proceed with conditions ☐ Do not proceed |
| Gaps identified | *(free text — carry into Vendor Risk Register "Findings / Gaps Identified" column)* |
| Assessed by | |
| Date | |
| Next reassessment due | *(Tier 2: 18–24 months; Tier 3: ad hoc)* |

---

*Crosswalk: this checklist operationalises TPRM Policy §5.2 and supports the evidence referenced
in Appendix A against ISO/IEC 27001:2022 A.5.20 and A.5.21, and SOC 2 CC9.2.*
