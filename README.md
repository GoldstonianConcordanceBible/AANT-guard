# AANT-Guard
**AANT-Guard** is an open, benchmark-driven multi-agent safety layer designed to reduce delusion reinforcement and improve safe redirection behavior in biomedical conversational systems.

This repository packages:
- A multi-agent wrapper (Grounding Agent + Stability Agent + Care Path Agent)
- A reproducible evaluation harness
- Open science preregistration materials
- Dataset reuse & integration documentation

## Institutional Affiliation Statement
This repository is formally affiliated with SydTek University.

Purpose:
- Academic indexing of public media engagement
- Institutional research tracking
- DOI-based scholarly referencing
- AI governance and Web3 research documentation

This artifact is independent from other podcast indexing repositories.

## Why it exists
Modern LLMs can hallucinate in biomedical contexts and may inconsistently provide safety interventions in vulnerable-user scenarios. AANT-Guard aims to provide a lightweight, model-agnostic safety layer that can be evaluated with public benchmarks and reused across systems.

## Quick start (planned)
- `benchmarks/runner.py` runs baseline vs guarded evaluation.
- Outputs are written to `benchmarks/outputs/` as JSON for reproducibility.

## Open Science
- Preregistration draft: `PREREGISTRATION_DRAFT.md`
- Evaluation protocol: `EVALUATION_PROTOCOL.md`
- Data sharing plan: `DATASETS.md`

## Status
v0.1.0 (prototype scaffold)