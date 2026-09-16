# OCC-109 Data Governance — Completed Evidence Summary

This document maps completed Data Engineering work to the five OCC-109 evidence asks. It intentionally excludes Linear issues that are Todo, Backlog, In Review, On Hold, Canceled, or Duplicate.

Detailed section packets:

- [109(a) — Data quality governance](109-a-data-quality-governance/)
- [109(b) — Data as a First-Class Citizen](109-b-data-first-class-citizen/)
- [109(c) — Data inventory](109-c-data-inventory/)
- [109(d) — Access management](109-d-access-management/)
- [109(e) — Data quality assurance](109-e-data-quality-assurance/)

Each section folder also contains public-safe quick-reference cards for the completed Linear issues cited below. The cards include status, owner, project, completion metadata, a concise outcome, and the authoritative Linear link.

## (a) Data-quality governance documentation, dashboards, and issue logs

| Completed control | Owner | Linear evidence |
| --- | --- | --- |
| Data-quality improvement proposal and prioritization | Eric Li | [DE-2550](https://linear.app/bitgo/issue/DE-2550/develop-data-quality-improvement-proposal) |
| Data Trust Checklist covering schema contracts, tests, staging gates, lineage, and alerts | Suresh Ravi | [DE-658](https://linear.app/bitgo/issue/DE-658/publish-data-trust-checklist-for-all-new-modelspipelines-schema) |
| Data Trust Framework handover with identified issues, root causes, observability baselines, and KPIs | Suresh Ravi | [DE-1746](https://linear.app/bitgo/issue/DE-1746/data-trust-framework-project-handover-documentation) |
| DQ checks documented in the Snowflake onboarding guide | Suresh Ravi | [DE-2243](https://linear.app/bitgo/issue/DE-2243/document-data-quality-dq-checks-in-snowflake-data-onboarding-guide) |
| Monitoring inventory tagged by layer and status | Suresh Ravi | [DE-640](https://linear.app/bitgo/issue/DE-640/tag-each-link-by-layer-l1l2l3-and-status-active-stale-missing) |
| Central monitoring inventory with gaps annotated | Suresh Ravi | [DE-641](https://linear.app/bitgo/issue/DE-641/publish-single-confluence-page-with-inventory-gap-annotations) |

## (b) Data as a First-Class Citizen — plan, issues, impact, and remediation

| Completed evidence | Owner | Linear evidence |
| --- | --- | --- |
| Data-quality improvement proposal: industry benchmark, known gaps, impact, and prioritization | Eric Li | [DE-2550](https://linear.app/bitgo/issue/DE-2550/develop-data-quality-improvement-proposal) |
| Data Trust Framework handover and issue inventory | Suresh Ravi | [DE-1746](https://linear.app/bitgo/issue/DE-1746/data-trust-framework-project-handover-documentation) |
| Tier-1 DSA/Billing staging inventory and DQ tests | Prateek Patnaik | [DE-1834](https://linear.app/bitgo/issue/DE-1834/identify-base-staging-tables-and-apply-dbt-data-quality-tests-for-tier) |
| DAS reconciliation roadmap | Suresh Ravi | [DE-2986](https://linear.app/bitgo/issue/DE-2986/create-roadmap-for-proper-das-data-reconciliation) |
| Missing USD values in OCC transfer CSV investigated/remediated | Ben Hu | [DE-3046](https://linear.app/bitgo/issue/DE-3046/investigate-missing-usd-values-in-occ-transfer-csv) |
| Duplicate fiat-account rows remediated | Xintong Li | [DE-2950](https://linear.app/bitgo/issue/DE-2950/fix-duplicate-rows-in-dim-fiat-accounts-accounts) |
| Balance-reconciliation control for audit requirements | Suresh Ravi | [DE-511](https://linear.app/bitgo/issue/DE-511/pwc-audit-compliance-for-balance-recon) |

## (c) Data inventory and categorization

| Completed evidence | Owner | Linear evidence |
| --- | --- | --- |
| Pipeline catalog covering DAGs, dbt models, stored procedures, owners, and alerts | Suresh Ravi | [DE-1368](https://linear.app/bitgo/issue/DE-1368/build-a-pipeline-catalog-dags-modelsdag-procs-with-owners-and-alerts) |
| Monitoring inventory categorized by L1/L2/L3 and active/stale/missing status | Suresh Ravi | [DE-640](https://linear.app/bitgo/issue/DE-640/tag-each-link-by-layer-l1l2l3-and-status-active-stale-missing) |
| Central inventory published with monitoring gaps | Suresh Ravi | [DE-641](https://linear.app/bitgo/issue/DE-641/publish-single-confluence-page-with-inventory-gap-annotations) |
| Snowflake table availability documented for staging/test environments | Brandon Anderson | [DE-1526](https://linear.app/bitgo/issue/DE-1526/de-ask-snowflake-tables-available-in-stagingtest-environments) |
| Data-pipeline ownership catalog updated with current squad owners | Suresh Ravi | [DE-2241](https://linear.app/bitgo/issue/DE-2241/update-stale-owners-in-data-pipeline-ownership-catalog-with-squad-owners) |

## (d) Access management and access-review evidence

| Completed evidence | Owner | Linear evidence |
| --- | --- | --- |
| Enterprise and wallet scoping in access tokens reviewed | Xintong Li | [DE-832](https://linear.app/bitgo/issue/DE-832/review-tdd-enterprise-and-wallet-scoping-in-access-tokens) |
| Snowflake Trust Center roles granted to DATA_ADMIN | Ben Hu | [DE-1761](https://linear.app/bitgo/issue/DE-1761/grant-snowflake-trust-center-access-to-data-admin) |
| Snowflake Trust Center viewer role added under DATA | Ben Hu | [DE-1776](https://linear.app/bitgo/issue/DE-1776/add-trust-center-viewer-under-data-snowflake-role) |
| Analytics access to staging.linear in Snowflake provided | Anant Gupta | [DE-982](https://linear.app/bitgo/issue/DE-982/provide-analytics-access-to-staginglinear-in-snowflake) |

**Evidence gap:** the completed Linear set does not include a dedicated issue proving periodic access reviews for every critical system; those records must be attached from the relevant IAM, Snowflake, Cloudflare, or access-review systems if required by OCC-109.

## (e) Data-quality assurance and third-party/vendor controls

| Completed control | Owner | Linear evidence |
| --- | --- | --- |
| Freshness checks for critical staging models | Prateek Patnaik | [DE-2790](https://linear.app/bitgo/issue/DE-2790/extend-dbt-freshness-checks-to-all-critical-staging-models) |
| Staging lag SLA alerts | Shubham Shubham | [DE-2610](https://linear.app/bitgo/issue/DE-2610/alert-on-staging-lag-sla-breach-maxsrc-op-log-date-vs-now) |
| Wallet-holdings lag SLA alerts | Shubham Shubham | [DE-2611](https://linear.app/bitgo/issue/DE-2611/alert-on-wallet-holdings-lag-sla-breach) |
| Schema-drift detection framework using dbt contracts | Shubham Shubham | [DE-2612](https://linear.app/bitgo/issue/DE-2612/implement-schema-drift-detection-framework-using-dbt-contracts) |
| dbt contracts for critical gold-layer models | Shubham Shubham | [DE-2791](https://linear.app/bitgo/issue/DE-2791/implement-schema-drift-checks-using-dbt-contracts-for-gold-layer) |
| dbt contracts for critical staging models | Shubham Shubham | [DE-2792](https://linear.app/bitgo/issue/DE-2792/implement-schema-drift-checks-using-dbt-contracts-for-stg-layer) |
| Not-null and uniqueness checks for critical models | Prateek Patnaik | [DE-2738](https://linear.app/bitgo/issue/DE-2738/extend-dbt-checks-to-all-critical-staging-models) |
| Tier-1 DSA/Billing data-quality tests | Prateek Patnaik | [DE-1834](https://linear.app/bitgo/issue/DE-1834/identify-base-staging-tables-and-apply-dbt-data-quality-tests-for-tier) |
| Decimal-field parsing tripwires for source/vendor schema changes | Prateek Patnaik | [DE-1232](https://linear.app/bitgo/issue/DE-1232/add-dbt-source-test-tripwires-for-decimal-field-parsing) |
| Data-completeness service updated for current models and deletion handling | Prateek Patnaik | [DE-2115](https://linear.app/bitgo/issue/DE-2115/update-the-data-completeness-service-to-point-to-the-new-models-and) |
| APS pricing-table data-gap validation | Suresh Ravi | [DE-2815](https://linear.app/bitgo/issue/DE-2815/data-validation-sanity-check-data-gaps-in-sf-pricing-table) |

## Scope note

These Linear records demonstrate completed controls and remediation work. They do not by themselves prove that every OCC-109 requirement is fully satisfied; the final package should attach the linked documents, dashboards, CI results, access-review exports, and issue logs referenced by each control.
