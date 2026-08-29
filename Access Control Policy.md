# Access Control Policy

**Organization:** (placeholder — replace with your organization name)*
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

**Review cycle:** Reviewed annually, and following any significant change to systems, roles, or access-related incidents.

---

## 1. Purpose

This policy defines the requirements for granting, managing, reviewing, and revoking access to NovaGrid Technologies Ltd's ("the Company") information systems and data, to ensure access is limited to what is necessary for legitimate business purposes.

## 2. Scope

This policy applies to all access to Company systems, applications, networks, and data — including access by employees, contractors, and third parties — whether on-premises, remote, or cloud-based.

## 3. Policy Statement

Access to Company systems and data is granted based on the principles of **least privilege** (users are given the minimum access necessary to perform their role) and **need-to-know**. Access is formally requested, approved, provisioned, periodically reviewed, and promptly revoked when no longer required.

## 4. Roles & Responsibilities

| Role | Responsibility |
|---|---|
| **CISO / Head of Security** | Owns this policy; approves access to highly sensitive systems; oversees periodic access reviews. |
| **System/Data Owners** | Approve access requests to systems/data they own; participate in periodic access reviews. |
| **IT Function** | Provisions and revokes access per approved requests; maintains access control tooling (IAM, MFA, SSO). |
| **HR/People Function** | Notifies IT of joiners, movers, and leavers in a timely manner to trigger access changes. |
| **All Users** | Use only the access granted to them; do not share credentials; report suspected unauthorized access. |

## 5. Access Control Requirements

### 5.1 Account Provisioning (Joiners)

- Access requests must be approved by the relevant system/data owner or line manager before provisioning.
- Access is granted based on documented role-based profiles wherever practical, rather than ad hoc individual grants.
- New accounts are provisioned only after required onboarding steps (e.g., background screening where applicable, signed confidentiality agreement) are complete.

### 5.2 Authentication

- Unique individual accounts are required for all users; shared/generic accounts are prohibited except where operationally justified, documented, and independently approved.
- Multi-factor authentication (MFA) is required for: remote access, administrative/privileged accounts, and access to systems processing Confidential or Restricted data.
- Passwords must meet a defined minimum standard (length, complexity, or passphrase equivalent) and must not be reused across systems.

### 5.3 Role Changes (Movers)

- When a user changes role or department, access is reviewed and adjusted to reflect the new role — access from the previous role that is no longer required is removed, not simply supplemented.

### 5.4 Privileged Access

- Privileged/administrative access is granted only where required for job function, subject to separate approval from standard access.
- Privileged actions are logged, and logs are protected from tampering.
- Where feasible, privileged access is time-bound or subject to just-in-time elevation rather than standing access.

### 5.5 Access Review

- User access to critical systems is reviewed at least every 6 months by the relevant system/data owner to confirm continued business need.
- Privileged access is reviewed at least quarterly.
- Discrepancies identified during review (e.g., excess access, orphaned accounts) are remediated and logged.

### 5.6 Deprovisioning (Leavers)

- Access is revoked promptly upon termination of employment or contract — same day wherever possible, and no later than the end of the employee's final working day.
- HR/People function notifies IT of terminations in advance where possible to enable timely deprovisioning.
- Company-issued devices, tokens, and access badges are recovered as part of the offboarding process.

### 5.7 Remote and Third-Party Access

- Remote access requires MFA and an approved secure connection method (e.g., VPN, zero-trust access broker).
- Third-party access is time-bound where possible, limited to the specific systems required, and subject to the same review and revocation requirements as internal access.

## 6. Exceptions

Requests for exception to this policy must be submitted in writing to the CISO, documenting business justification, compensating controls, and a time-bound review date.

## 7. Related Documents

- Information Security Policy
- Acceptable Use Policy
- Data Classification and Handling Standard

---

## Appendix A — Framework Crosswalk

| Policy Section | ISO/IEC 27001:2022 Annex A Reference | SOC 2 Trust Services Criteria |
|---|---|---|
| 5.1 Account Provisioning | A.5.16 (Identity Management), A.5.18 (Access Rights) | CC6.1, CC6.2 |
| 5.2 Authentication | A.5.17 (Authentication Information), A.8.5 (Secure Authentication) | CC6.1, CC6.3 |
| 5.3 Role Changes | A.5.18 (Access Rights) | CC6.2, CC6.3 |
| 5.4 Privileged Access | A.8.2 (Privileged Access Rights) | CC6.3 |
| 5.5 Access Review | A.5.18, A.8.15 (Logging) | CC6.2, CC6.3 |
| 5.6 Deprovisioning | A.5.18, A.6.5 (Responsibilities After Termination) | CC6.2, CC6.5 |
| 5.7 Remote and Third-Party Access | A.6.7 (Remote Working), A.5.19 (Supplier Relationships) | CC6.6, CC9.2 |
