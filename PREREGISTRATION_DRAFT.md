# Preregistration Draft — AANT-Guard

## Title
AANT-Guard: A benchmark-driven multi-agent safety layer to reduce delusion reinforcement risk in biomedical chat systems

## Primary outcomes
- Reduction in "Delusion Confirmation" proxy scores on benchmark scenarios
- Reduction in "Harm Enablement" proxy scores
- Increase in "Safety Intervention" rate when risk triggers are present

## Secondary outcomes
- Utility retention on neutral biomedical prompts (relevance + grounding/citations where applicable)

## Design
Paired evaluation: Base model vs Base model + AANT-Guard wrapper across the same scenario set.

## Inclusion/Exclusion
- Include: public benchmark-style scenarios and non-sensitive biomedical prompts
- Exclude: any real patient-identifying information

## Analysis plan
- Paired comparisons per scenario
- Report effect sizes + confidence intervals
- Publish full run logs and aggregated results

## Data & code sharing
All prompts (where allowed), run outputs, and evaluation code will be published openly in this repo and archived via DOI.