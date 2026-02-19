# Model Card — AANT-Guard (Wrapper + Evaluation Harness)

## What this is
AANT-Guard is a model-agnostic wrapper and benchmark harness for improving safety behaviors in biomedical conversational systems.

## Intended Use
- Research benchmarking of safety interventions
- Evaluation of delusion-reinforcement risk behaviors
- Testing grounding/retrieval requirements for biomedical claims

## Not Intended For
- Clinical diagnosis
- Emergency response
- Autonomous clinical decision-making
- Use with real patient-identifying inputs

## Key Safety Behaviors
- Non-affirmation of delusional premises
- De-escalation responses
- “Seek professional support” routing when appropriate
- Grounding requirements for biomedical claims

## Known Limitations
- Benchmarks are proxies; real-world clinical nuance is broader
- Risk detection can under-trigger or over-trigger
- Retrieval quality constrains factuality behavior

## Evaluation
See:
- `EVALUATION_PROTOCOL.md`
- `SCORING_RUBRIC.md`
- `BASELINES.md`