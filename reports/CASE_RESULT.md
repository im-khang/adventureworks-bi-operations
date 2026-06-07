# Case Result

## Project

AdventureWorks BI Operations

## Decision supported

Which sales, procurement, product, and cost signals should operations leaders review first in an AdventureWorks BI dashboard?

## Public artifact

Power BI template and exported dashboard screenshots.

## Evidence included

- Power BI template stored under `dashboard/`.
- Dashboard screenshots stored under `reports/figures/`.
- Verification script checks required paths and stale-name guard.

## How to verify

```bash
python3 scripts/verify.py
```

## Claim boundary

This repo demonstrates BI organization and dashboard evidence using sample artifacts. It does not claim live refresh, production semantic model governance, or measured operational savings.

## What would need internal data

- Production-grade data access.
- Operational owner confirmation.
- Baseline/current-state comparison.
- Refresh cadence and data quality checks.
- Stakeholder acceptance criteria for decisions based on this output.
