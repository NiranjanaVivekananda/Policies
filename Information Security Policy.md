# Information Security Policy

**Organization:** Replace with your organization name
**Document Owner:** Chief Information Security Officer (CISO)
**Classification:** Internal
**Version:** 1.0
**Effective Date:** 2026-08-27
**Next Review Date:** 2027-08-27
**Approved By:** [Executive Sponsor / Board of Directors]

---

## Document Control

| Version | Date | Author | Summary of Changes |
|---|---|---|---|
| 0.1 | 2026-07-01 | GRC Analyst | Initial draft |
| 1.0 | 2026-08-27 | GRC Analyst | Approved baseline version |

**Review cycle:** This policy is reviewed annually, and following any significant change to the organization's risk profile, technology estate, legal/regulatory obligations, or after a material security incident.

---

## 1. Purpose

This Information Security Policy defines XXX Technologies Ltd's ("the Company") commitment to protecting the confidentiality, integrity, and availability of its information assets, and those of its customers and partners. It establishes the framework of principles, roles, and controls through which information security is governed across the organization.

This policy is the top-level governance document within the Company's Information Security Management System (ISMS) and is supported by a set of subordinate policies and standards (e.g., Access Control Policy, Acceptable Use Policy, Incident Response Plan, Business Continuity Plan).

## 2. Scope

This policy applies to:

- All employees, contractors, temporary staff, interns, and third parties who access Company information systems or data.
- All information assets owned, leased, or managed by the Company, including data, software, hardware, network infrastructure, and cloud-hosted services.
- All locations from which Company systems are accessed, including offices, remote/home working environments, and third-party facilities.
- All formats of information — electronic, physical (paper), and verbal.

This policy does not override applicable law. Where local legal or regulatory requirements exceed the standards set out here, the stricter requirement applies.

## 3. Policy Statement

The Company is committed to preserving:

- **Confidentiality** — information is accessible only to those authorized to access it.
- **Integrity** — information and processing methods remain accurate, complete, and unaltered except by authorized action.
- **Availability** — authorized users have access to information and associated assets when required.

Information security is treated as a business risk management discipline, not solely a technical or IT function. Security decisions are risk-based, proportionate, and aligned with the Company's business objectives and legal, regulatory, and contractual obligations.

### 3.1 Objectives

- Protect the Company and its customers from harm arising from breaches of confidentiality, integrity, or availability.
- Maintain compliance with applicable legal, regulatory, and contractual obligations (e.g., UK GDPR, DPA 2018, customer security addenda).
- Support the Company's certification and audit commitments, including ISO/IEC 27001 and SOC 2 Type II.
- Embed a culture of security awareness and shared responsibility across all staff.
- Ensure the business can prevent, detect, respond to, and recover from information security incidents.

## 4. Governance and Roles & Responsibilities

| Role | Responsibility |
|---|---|
| **Board / Executive Leadership** | Ultimate accountability for information security risk; approves this policy and resources the ISMS. |
| **CISO / Head of Security** | Owns this policy; leads the ISMS; reports security posture and risk to leadership; chairs the risk committee. |
| **GRC / Compliance Function** | Maintains the risk register, control framework, audit program, and third-party risk assessment process; tracks remediation. |
| **IT / Engineering Leadership** | Implements and operates technical controls; owns system and infrastructure security configuration. |
| **People/HR Function** | Manages security aspects of the employee lifecycle (onboarding, role changes, offboarding, screening). |
| **Line Managers** | Ensure staff complete required training and follow policy within their teams. |
| **All Employees & Contractors** | Comply with this policy and subordinate standards; report suspected incidents or weaknesses promptly. |
| **Third Parties / Vendors** | Comply with contractual security requirements; cooperate with due diligence and assessment activities. |

Governance is exercised through a periodic (at minimum quarterly) security and risk review, chaired by the CISO, with reporting to executive leadership.

## 5. Risk Management

The Company maintains a formal information security risk management process, consistent with ISO/IEC 27001 Clause 6 and ISO/IEC 27005 guidance:

1. **Identification** — assets, threats, and vulnerabilities are identified and logged in the risk register.
2. **Assessment** — risks are evaluated for likelihood and impact using a defined risk matrix.
3. **Treatment** — risks are treated via mitigation, transfer, avoidance, or acceptance, with treatment plans owned and tracked to completion.
4. **Acceptance** — residual risk above the defined appetite requires documented sign-off from an authorized risk owner.
5. **Monitoring** — the risk register is reviewed at least quarterly and after significant change.

Risk assessments are also performed prior to onboarding new third-party vendors, adopting new technologies, and launching new products or significant system changes.

## 6. Asset Management

- All information assets (data, hardware, software, cloud services) are identified, classified, and assigned an owner.
- Information is classified according to a defined scheme (e.g., **Public / Internal / Confidential / Restricted**), and handling requirements are applied accordingly.
- An asset inventory is maintained and reviewed at least annually.
- Assets are securely sanitized or destroyed at end of life in line with data retention and disposal standards.

## 7. Access Control

- Access to systems and data is granted on the principle of **least privilege** and **need-to-know**.
- Access provisioning, review, and revocation follow a documented joiner-mover-leaver (JML) process.
- Privileged access is subject to additional controls, including approval, logging, and periodic access review (at minimum every 6 months).
- Multi-factor authentication (MFA) is required for remote access, administrative access, and access to systems processing confidential or restricted data.
- Shared/generic accounts are prohibited except where operationally justified, documented, and independently approved.

## 8. Human Resource Security

- Background screening is performed for roles with access to sensitive systems or data, proportionate to role risk and in line with local law.
- All personnel sign confidentiality/non-disclosure obligations as part of their contract.
- Security awareness training is mandatory at onboarding and at least annually thereafter, supplemented by periodic phishing simulation and targeted role-based training (e.g., for engineering, finance).
- A formal disciplinary process applies to confirmed policy violations.
- Access rights are revoked, and Company assets returned, promptly upon termination or role change, per the JML process.

## 9. Physical and Environmental Security

- Access to Company premises and secure areas (e.g., server/comms rooms) is restricted to authorized individuals and logged.
- Visitors are signed in, escorted, and not granted unsupervised access to secure areas.
- Equipment is protected against environmental threats (power loss, fire, flood) commensurate with the criticality of the asset.
- A clear desk and clear screen practice is expected in all offices.

## 10. Operations Security

- Change management: all changes to production systems follow a documented change control process, including testing and rollback planning.
- Malware protection is deployed and maintained on all endpoints and servers.
- Systems are patched in line with a defined vulnerability management SLA, prioritized by severity.
- Logging and monitoring are enabled on critical systems; logs are protected from tampering and retained per policy.
- Backups are performed on a defined schedule, encrypted, tested periodically for restorability, and stored with appropriate resilience (including offsite/logically separated copies).
- Capacity and performance are monitored to reduce availability risk.

## 11. Communications and Network Security

- Networks are segmented to separate environments of differing trust levels (e.g., production, corporate, guest).
- Data in transit over public networks is encrypted using industry-standard protocols.
- Firewalls and network access controls restrict traffic to what is explicitly required for business purposes.
- Remote access to internal systems requires MFA and an approved secure connection method (e.g., VPN, zero-trust access broker).

## 12. System Acquisition, Development, and Maintenance

- Security requirements are considered at the design stage of new systems and changes ("security by design").
- Development, testing, and production environments are logically separated.
- Code and configuration changes undergo review prior to deployment to production.
- Cryptographic controls are applied to protect data confidentiality and integrity, using approved algorithms and key management practices.
- Security testing (e.g., vulnerability scanning, and periodic penetration testing) is performed on internet-facing and business-critical systems.

## 13. Supplier and Third-Party Relationships

- Third parties that access, process, or store Company or customer data are subject to a documented due diligence and risk assessment process prior to onboarding (e.g., security questionnaire, evidence review, risk tiering).
- Security and data protection requirements are incorporated into contracts and, where applicable, Data Processing Agreements.
- Higher-risk vendors are subject to periodic reassessment, proportionate to the risk tier assigned.
- Material changes in a vendor's risk profile (e.g., a breach notification) trigger an off-cycle review.

## 14. Information Security Incident Management

- A documented Incident Response Plan defines detection, triage, containment, eradication, recovery, and post-incident review procedures.
- All staff are required to report suspected security incidents or weaknesses promptly through a defined channel.
- Incidents are logged, classified by severity, and tracked to closure.
- Where required by law, regulation, or contract, affected parties (including regulators and data subjects) are notified within mandated timeframes.
- Lessons learned from incidents are fed back into the risk register and control environment.

## 15. Business Continuity and Disaster Recovery

- Business Impact Analysis identifies critical processes, systems, and recovery time/point objectives (RTO/RPO).
- Business Continuity and Disaster Recovery plans are documented, resourced, and tested at least annually.
- Backup and recovery procedures are aligned to defined RTO/RPO targets.

## 16. Compliance

- The Company identifies and maintains a register of applicable legal, regulatory, and contractual obligations relevant to information security and data protection (e.g., UK GDPR, DPA 2018, sector-specific requirements).
- Internal audits of the ISMS are conducted at least annually to verify control effectiveness.
- The Company supports external audits and certifications (e.g., ISO/IEC 27001 certification audits, SOC 2 Type II examinations) as part of its assurance program.
- Non-compliance with this policy may result in disciplinary action, and, for third parties, contractual remedies up to termination.

## 17. Policy Exceptions

Requests for exception to this policy must be submitted in writing to the CISO, documenting the business justification, compensating controls, and time-bound review date. Exceptions are logged in the risk register and re-reviewed at expiry.

## 18. Related Documents

- Acceptable Use Policy
- Access Control Policy
- Data Classification and Handling Standard
- Incident Response Plan
- Business Continuity Plan
- Third-Party Risk Management Policy
- Data Protection / Privacy Policy

---

## Appendix A — Framework Crosswalk

This policy is written to satisfy the requirements of ISO/IEC 27001:2022 Clause 5.2 (Policy) and to map onto the control domains of NIST CSF 2.0 and the SOC 2 Trust Services Criteria (Security/Common Criteria). This table is intended to demonstrate cross-framework coverage for audit and portfolio purposes — it is illustrative, not exhaustive.

| Policy Section | ISO/IEC 27001:2022 Annex A Reference | NIST CSF 2.0 Function | SOC 2 Trust Services Criteria |
|---|---|---|---|
| 4. Governance and Roles | A.5.1–A.5.4 (Policies, Roles, Segregation of Duties) | Govern (GV.OC, GV.RR) | CC1 – Control Environment |
| 5. Risk Management | A.5.7, A.6.1 (Threat Intelligence, Screening tie-in), ISO 27005 | Identify (ID.RA, ID.IM) | CC3 – Risk Assessment |
| 6. Asset Management | A.5.9–A.5.14 (Asset Inventory, Classification, Handling) | Identify (ID.AM) | CC6.1 |
| 7. Access Control | A.5.15–A.5.18, A.8.2–A.8.5 (Access Rights, Privileged Access, MFA) | Protect (PR.AA) | CC6.1, CC6.2, CC6.3 |
| 8. Human Resource Security | A.6.1–A.6.8 (Screening, Terms, Awareness, Disciplinary) | Protect (PR.AT) | CC1.4, CC1.5 |
| 9. Physical & Environmental Security | A.7.1–A.7.14 | Protect (PR.PS) | CC6.4 |
| 10. Operations Security | A.8.7–A.8.16 (Malware, Logging, Backup, Vulnerability Mgmt) | Protect (PR.DS, PR.PS), Detect (DE.CM) | CC7.1, CC7.2 |
| 11. Communications & Network Security | A.8.20–A.8.24 (Network Security, Encryption) | Protect (PR.DS, PR.IR) | CC6.6, CC6.7 |
| 12. System Acquisition & Development | A.8.25–A.8.34 (Secure Development Lifecycle) | Protect (PR.PS) | CC8.1 |
| 13. Supplier & Third-Party Relationships | A.5.19–A.5.23 (Supplier Security, Cloud Services) | Govern (GV.SC), Identify (ID.SC-equivalent) | CC9.2 |
| 14. Incident Management | A.5.24–A.5.28, A.6.8 | Detect (DE.AE), Respond (RS.MA, RS.CO) | CC7.3, CC7.4, CC7.5 |
| 15. Business Continuity & DR | A.5.29–A.5.30 | Recover (RC.RP, RC.CO) | A1.2, A1.3 (Availability) |
| 16. Compliance | A.5.31–A.5.37 | Govern (GV.OC, GV.RM) | CC1.1, CC2.3 |
