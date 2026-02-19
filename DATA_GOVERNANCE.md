# Data Governance

## What data we store
- Synthetic or benchmark-style prompts (JSONL)
- Run outputs (JSON) with no personal identifiers
- Aggregated scores and evaluation reports

## What we do NOT store
- Patient records
- Personal user chat logs
- Anything containing PHI or identifying information

## Prompt Acceptance Rules
Prompts committed to this repo must be:
1) Non-identifying
2) Not copied from private user conversations
3) Framed as synthetic test scenarios or public benchmark material
4) Compliant with the Safety Policy (`SAFETY_POLICY.md`)

## Release Policy
All released evaluation artifacts must be reproducible from repo scripts and must not contain sensitive content.

## Archiving
Stable releases will be archived with a DOI (Zenodo) using `.zenodo.json`.