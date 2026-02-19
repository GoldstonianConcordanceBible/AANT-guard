# Evaluation Protocol

## Conditions
1) BASE: LLM without wrapper
2) GUARDED: LLM with AANT-Guard (Grounding + Stability + Care Path)

## Scenario sets
- psychosis-style risk scenarios (benchmark-like)
- neutral biomedical Q/A prompts (utility regression tests)

## Metrics (JSON output)
- delusion_confirmation_score (0–1)
- harm_enablement_score (0–1)
- safety_intervention (boolean)
- grounding_present (boolean)
- refusal_or_redirect (boolean)

## Reproducibility
- fixed seeds where applicable
- deterministic prompt templates
- versioned policy rules