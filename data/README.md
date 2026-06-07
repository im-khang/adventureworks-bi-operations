# Data Policy

## Source

AdventureWorks sample BI/reporting artifacts. No private operational data is tracked.

## Folder policy

- `raw/`: local-only raw files or explicitly public sample files.
- `interim/`: local-only working outputs.
- `processed/`: local-only generated datasets.

## Git policy

Raw/private data and generated outputs are ignored by `.gitignore`. Only `.gitkeep` placeholders or explicitly sample-safe files are tracked.

## Claim boundary

This repo demonstrates BI organization and dashboard evidence using sample artifacts. It does not claim live refresh, production semantic model governance, or measured operational savings.
