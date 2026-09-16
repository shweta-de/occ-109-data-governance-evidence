# OCC-109(e) — Data Quality Assurance and Third-Party Controls

Completed controls for freshness, completeness, schema integrity, validation, monitoring, and vendor/source reliability.

| Linear item | Owner | Completed evidence |
| --- | --- | --- |
| [DE-2790 — Critical-model freshness checks](https://linear.app/bitgo/issue/DE-2790/extend-dbt-freshness-checks-to-all-critical-staging-models) | Prateek Patnaik | Freshness checks extended to critical staging models. |
| [DE-2610 — Staging lag SLA alerts](https://linear.app/bitgo/issue/DE-2610/alert-on-staging-lag-sla-breach-maxsrc-op-log-date-vs-now) | Shubham Shubham | Source-lag SLA monitoring and alerts. |
| [DE-2611 — Wallet-holdings lag alerts](https://linear.app/bitgo/issue/DE-2611/alert-on-wallet-holdings-lag-sla-breach) | Shubham Shubham | Wallet-holdings freshness/SLA monitoring. |
| [DE-2612 — Schema-drift framework](https://linear.app/bitgo/issue/DE-2612/implement-schema-drift-detection-framework-using-dbt-contracts) | Shubham Shubham | dbt-contract schema-drift detection and alerting. |
| [DE-2791 — Gold-layer dbt contracts](https://linear.app/bitgo/issue/DE-2791/implement-schema-drift-checks-using-dbt-contracts-for-gold-layer) | Shubham Shubham | Contract checks for critical marts. |
| [DE-2792 — Staging-layer dbt contracts](https://linear.app/bitgo/issue/DE-2792/implement-schema-drift-checks-using-dbt-contracts-for-stg-layer) | Shubham Shubham | Contract checks for critical staging tables. |
| [DE-2738 — Critical-model DQ checks](https://linear.app/bitgo/issue/DE-2738/extend-dbt-checks-to-all-critical-staging-models) | Prateek Patnaik | Not-null and uniqueness checks for critical models. |
| [DE-1232 — Decimal parsing tripwires](https://linear.app/bitgo/issue/DE-1232/add-dbt-source-test-tripwires-for-decimal-field-parsing) | Prateek Patnaik | Source checks for numeric schema changes that could produce null values. |
| [DE-2115 — Completeness service update](https://linear.app/bitgo/issue/DE-2115/update-the-data-completeness-service-to-point-to-the-new-models-and) | Prateek Patnaik | Completeness checks updated for current models and deletion handling. |
| [DE-2815 — APS pricing-table validation](https://linear.app/bitgo/issue/DE-2815/data-validation-sanity-check-data-gaps-in-sf-pricing-table) | Suresh Ravi | Pricing-table coverage and data-gap validation. |
| [DE-1834 — Tier-1 DSA/Billing tests](https://linear.app/bitgo/issue/DE-1834/identify-base-staging-tables-and-apply-dbt-data-quality-tests-for-tier) | Prateek Patnaik | DQ tests for high-impact DSA/Billing staging tables. |

These controls demonstrate how completeness, accuracy, timeliness, and schema reliability are monitored. Vendor-specific evidence should be attached from the relevant source/vendor issue when needed.
