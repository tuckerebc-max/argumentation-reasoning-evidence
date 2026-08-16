# Argumentation package contract

**Registry ID:** `SKILL-ARG`  
**Package version:** `0.1.0`  
**Source domain:** `DOM-ARG`  
**Current status:** `READY_WITH_CONDITIONS`

## Required inputs

Supply an issue or resolution, purpose, audience, authority where relevant, mode, constraints, burden or standard, source/evidence records, and learner position or decision boundary. A vague task stops at `NEEDS_TASK` or `NEEDS_AUDIENCE`.

## Core payload

The package produces `task_contract`, `stasis_map`, `argument_map`, `evidence_ledger`, `inference_test`, `quality_profile`, `strongest_alternative`, `response_plan`, `uncertainty`, `learner_decisions`, and `transfer_routes` inside the shared artifact envelope.

## Quality conditions

The argument map is a diagnostic. Quality requires relevant and sufficient evidence, a defensible warrant, appropriate burden, tested inference, credible alternative, visible uncertainty, source provenance, and an accountable learner response.

## Canonical source paths

See `catalog/source-manifest.json` for the portable mapping to the prompt, corpus crosswalk, competency design specification, technical specification, and textbook architecture. The source validation IDs are `TST-ARG-001` through `TST-ARG-016`, plus `TST-INT-006` and `TST-INT-007`.
