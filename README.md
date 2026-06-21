# DIKWP-TRIZ SemanticForge Studio V2

A standalone, offline-first prototype for moving inventive problem solving from a concept-only space into a purpose-driven semantic space.

## Core workflow

Concept problem statement → Semantic problem ledger → Purpose Contract → Contradiction graph → DIKWP 5×5 transformation router → TRIZ principle routing → Resource and ideality map → Solution Cards → Experiment plan → Risk and evidence ledger → Patent disclosure sketch → Innovation Passport.

## Quick start

Open `index.html` in a modern browser. No server, database, API key, model endpoint, or network is required.

Optional CLI:

```bash
python run_demo.py examples/sample_innovation_problem.json --out outputs
```

## What this package implements

- exact 25-cell DIKWP × DIKWP candidate-principle matrix reported in the 2026 Electronics paper
- 40 TRIZ inventive principles with operator-level interpretations
- concept-space versus semantic-space problem modeling
- Purpose Contract with hard and soft constraints
- technical, physical, semantic, and purpose contradictions
- 3-No simulation: incompleteness, inconsistency, and imprecision
- solution cards with assumptions, evidence, risk, and kill conditions
- minimum viable experiment plans
- semantic checks: existence/expressibility, contextual uniqueness, and compositional trace consistency
- non-legal patent disclosure sketch
- Innovation Passport and audit export

## Important boundary

This system supports innovation workshops and ideation. It is not:

- engineering certification
- safety approval
- patentability, novelty, infringement, or freedom-to-operate opinion
- clinical or medical validation
- a substitute for domain experts, safety reviewers, regulatory professionals, or patent counsel

The 25 transformation-to-principle mappings are design-time heuristic priors. They are not proved optimal or complete and must be validated through expert review and experiments.

## Suggested Chinese name

DIKWP-TRIZ从概念空间到语义空间的目的驱动创新工作台
