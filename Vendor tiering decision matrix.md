# Vendor Tiering Decision Matrix

**Companion to:** Third-Party Risk Management Policy, §5.1 (Risk Tiering)
**Purpose:** A repeatable, defensible way to assign a new vendor to Tier 1, 2, or 3 at intake,
so tiering doesn't rely on one reviewer's gut feel.

---

## Step 1 — Score the vendor

Score each factor 0–3 using the descriptions below, then sum the total.

| Factor | 0 (None) | 1 (Low) | 2 (Moderate) | 3 (High) |
|---|---|---|---|---|
| **Data sensitivity accessed** | No Company/customer data | Internal, non-confidential data | Confidential business data | Restricted data: customer PII, financial, health, or credentials |
| **Type of system access** | No system access | Read-only access to a non-production system | Access to a production system, or admin-level access to a non-production system | Admin/privileged access to a production system or core infrastructure |
| **Business criticality** | Service is discretionary; no operational impact if unavailable | Minor inconvenience if unavailable | Noticeable disruption to a business function if unavailable | Business-critical; extended outage would materially disrupt operations |
| **Data processor status** | Not a data processor; no personal data involved | Processes personal data incidentally, low volume | Processes personal data as a core part of the service | Processes personal data at scale, or special category data, as a data processor |

**Total score: ____ / 12**

## Step 2 — Map score to tier

| Total score | Tier |
|---|---|
| 9–12 | **Tier 1 – Critical** |
| 4–8 | **Tier 2 – Moderate** |
| 0–3 | **Tier 3 – Low** |

**Override rule:** regardless of total score, assign **Tier 1** automatically if *any single
factor* scores a 3. A vendor can be low-risk on three factors and still be critical because of
one — e.g. a free analytics tool that happens to get admin access to production infrastructure.

## Step 3 — Record the result

Log the vendor, its tier, and the scoring rationale in the Vendor Risk Register before
due diligence begins (Policy §5.2) and before contract execution (Policy §5.3).

---

## Decision flow (visual)

![Vendor tiering decision flowchart](vendor-tiering-flowchart.svg)

---

*Crosswalk: this matrix operationalises TPRM Policy §5.1 and the tiers referenced throughout
Appendix A (ISO/IEC 27001:2022 A.5.19; SOC 2 CC9.2).*

