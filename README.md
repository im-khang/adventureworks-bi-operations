# AdventureWorks BI Operations

Which sales, procurement, product, and cost signals should operations leaders review first in an AdventureWorks BI dashboard?

## Business question

Which sales, procurement, product, and cost signals should operations leaders review first in an AdventureWorks BI dashboard?

## Reviewer guide

1. `dashboard/AdventrureWorks_report.pbit` — Power BI template artifact.
2. `reports/figures/Cost_Analysis.png` — cost analysis screenshot.
3. `reports/figures/Procurement_Overview.png` — procurement overview screenshot.
4. `docs/evaluation.md` and `reports/results.md` — verification notes.

## Data source

AdventureWorks sample BI/reporting artifacts. No private operational data is tracked.

## Repository structure

```text
README.md
LICENSE
.gitignore
requirements.txt
data/
  raw/          # source/sample input files or local-only raw data
  interim/      # local-only transformed working files
  processed/    # local-only generated datasets
notebooks/      # ordered analysis notebooks/scripts
src/            # reusable project code
dashboard/      # BI/dashboard files or dashboard export code
docs/           # documentation and evaluation notes
reports/        # human-readable findings and figures
references/     # source notes, papers, dictionaries, original materials
scripts/        # verification or utility scripts
```

## Setup

```bash
python -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

## Run / verify

```bash
python3 scripts/verify.py
```

## Public outputs

- Dashboard or public artifact: `Power BI template and exported dashboard screenshots.`
- Findings and evidence notes: `reports/`
- Evaluation notes: `docs/`
- Supporting references: `references/`

## Claim boundary

This repo demonstrates BI organization and dashboard evidence using sample artifacts. It does not claim live refresh, production semantic model governance, or measured operational savings.

## Data and security policy

- Credentials, environment files, local raw data, generated working data, databases, archives, and scratch outputs are ignored by `.gitignore`.
- Public repo keeps only shareable code, sample-safe artifacts, documentation, dashboard files, and evidence summaries.
- Claims stay bounded by available data and documented assumptions.
