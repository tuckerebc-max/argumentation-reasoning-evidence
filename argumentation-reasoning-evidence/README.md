# Argumentation, Reasoning, and Evidence

Standalone GitHub repository for the Main textbook skill `SKILL-ARG` and competency `COMP-ARG-REASONING`.

Upload this folder as the repository root. It includes `SKILL.md`, Codex UI metadata, competency and assessment codification, evaluator specification, output schema, handoff contract, argument ontology and quality guidance, provenance and authorship guidance, source manifest, shared schemas, fixtures, validation scripts, CI, release metadata, and checksums.

## Canonical design trace

`SPEC-ARG-001` · `ANRI-DOM-ARG-001` · `ARCH-ARG-001` · `CORP-ARG-001`

This package is finalized as a private draft. Toulmin and related schemes remain local diagnostics rather than a universal score. Human review remains required for current rules, rights, high-consequence claims, assessed work, and Public Argument Resolution transfer.

## Validate locally

```text
python scripts/validate_repository.py
python scripts/validate_repository.py --check
python scripts/evaluate_package.py
python scripts/build_release_manifest.py --check
```

The canonical textbook source files remain external and are mapped, not copied, in `catalog/source-manifest.json`.
