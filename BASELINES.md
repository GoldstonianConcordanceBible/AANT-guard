# Baselines (Comparators)

To show AANT-Guard adds value beyond simple prompting, we evaluate:

## B0 — Base Model
No wrapper.

## B1 — Refusal-Only Guard
A single policy prompt that refuses high-risk content.

## B2 — Retrieval-Only Guard
Forces retrieval/citations for biomedical claims, but no vulnerability/risk logic.

## B3 — Single-Stage Risk Filter
A lightweight classifier (heuristic or model-based) triggers a safe template, without multi-role arbitration.

## AANT-Guard (Proposed)
Multi-role pipeline:
- Grounding Agent (retrieval/citations/uncertainty)
- Stability Agent (risk signals + override)
- Care Path Agent (safe redirect + support routing)

Primary claim: AANT-Guard outperforms B1–B3 on safety metrics while preserving utility.