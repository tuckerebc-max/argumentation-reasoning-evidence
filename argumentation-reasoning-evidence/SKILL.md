---
name: argumentation-reasoning-evidence
description: Audit and build arguments through task and burden contracts, stasis and dispute mapping, claims, reasons, evidence, warrants, qualifiers, rebuttals, inference schemes, strongest alternatives, uncertainty, and mode-specific performance. Use for argument analysis, reasoning diagnostics, evidence evaluation, debate or deliberation preparation, counterargument work, and bounded argument packets. Do not equate a complete Toulmin diagram with a valid argument or ghostwrite an assessed argument.
---

# Argumentation, Reasoning, and Evidence

## Outcome

Produce a source-grounded argument record that makes the issue, burden, claim, reason, evidence, warrant, qualifier, alternative, response, uncertainty, and learner decision inspectable.

## Workflow

1. Contract the rhetorical situation. Record issue or resolution, purpose, audience, authority, mode, constraints, burden or standard, and learner position. If the task is vague, return `NEEDS_TASK` or `NEEDS_AUDIENCE`.
2. Classify the question as fact, value, policy, definition, interpretation, causal, or mixed. Set evidence and burden expectations accordingly.
3. Build a dispute or stasis map. Record definitions, agreements, disagreements, affected parties, options, dependencies, and the difference between a source's argument and the learner's position.
4. Map the reasoning. Represent claim, reason, evidence, warrant, backing, qualifier, rebuttal, and dependency relations. A structural map is a diagnostic, not proof of epistemic quality.
5. Audit evidence. Require source IDs, direct locators, source claims, relevance, method, currency, incentives, corroboration, limitations, rights, and direct-reading status. Flag `LOCATOR_FAILURE`, `PROVENANCE_AUDIT`, or `UNSUPPORTED_CLAIM` as needed.
6. Test the inference. Select a useful argument scheme such as causal, analogy, generalization, interpretation, or policy. Ask whether alternative explanations, scope limits, or missing evidence change the burden.
7. Reconstruct the strongest alternative. Do not build a straw opponent. Require the learner to select rebut, concede, qualify, revise, withdraw, or unresolved.
8. Branch by mode. Separate persuasive effectiveness, epistemic support, source practice, dialectical quality, participation ethics, and delivery conditions for written, spoken, debate, deliberative, and multimodal work.
9. Export or repair. Send validated reasoning to Writing, evidence gaps to QUEST, source-analysis questions to Close Reading, and public disagreement with authority or decision criteria to PAR.

## Guardrails

- Do not treat a complete Toulmin diagram as validation; test relevance, sufficiency, inference, burden, and uncertainty.
- Do not invent sources, quotations, current rules, legal conclusions, stakeholder views, or evidence.
- Preserve credible source conflict and permit concession, qualification, revision, withdrawal, or unresolved status.
- For a final graded or AP argument, return a scaffold and learner checkpoints under `AI_AUTHORSHIP_BOUNDARY`.
- Escalate current legal, health, civic, policy, or other high-consequence arguments for dated-source verification and human review.

## Output contract

Return the shared artifact envelope with an Argumentation payload containing `task_contract`, `stasis_map`, `argument_map`, `evidence_ledger`, `inference_test`, `quality_profile`, `strongest_alternative`, `response_plan`, `uncertainty`, `learner_decisions`, and `transfer_routes`.

## Handoffs

- Accept Close Reading and QUEST records without removing source locators, limitations, or uncertainty.
- Accept Writing drafts as argument-audit inputs; do not replace their prose or silently change the genre.
- Send a validated argument to Writing with scope, qualifiers, alternative, source IDs, and unresolved items intact.
- Send missing evidence, source conflict, causal gaps, or untested alternatives back to QUEST.
- Send affected parties, authority, decision rules, and competing legitimate values to PAR.

Read [skill-contract.md](references/skill-contract.md), [argument-ontology-and-quality.md](references/argument-ontology-and-quality.md), [handoff-contracts.md](references/handoff-contracts.md), [provenance-rights-authorship.md](references/provenance-rights-authorship.md), [output-schema.json](references/output-schema.json), and [evaluation-fixtures.json](references/evaluation-fixtures.json) as needed.
