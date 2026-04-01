---
name: meshagent-docs-maintainer
description: Maintain MeshAgent docs from code-first sources, using the migration artifacts, public-surface metadata, and source-backed examples.
---

# MeshAgent Docs Maintainer

Use this skill when the task is to update, expand, move, or create MeshAgent documentation and examples.

## Use This Skill When

- The task is to edit first-class MeshAgent docs.
- The task is to add or update examples under `meshagent-docs/examples`.
- The task is to regenerate snippets or CLI help after source changes.
- The task is to migrate content according to the docs migration artifacts.

## Source Of Truth

- Prefer the implementation and shipped examples over existing prose.
- Use `meshagent-sdk/meshagent-docs/public-surfaces.yaml` to decide whether a surface is current, transitional, or archive-only.
- Use `/Users/tulamasterman/code/meshagent-server/docs-migration/` artifacts to understand current coverage, gaps, and planned relocation.
- Use `meshagent-sdk/meshagent-docs/examples/catalog.yaml` to decide whether an example is canonical, archive-only, or non-canonical.

## Operating Rules

- Keep Room APIs grouped together.
- Keep the CLI as the primary teaching path unless the page is specifically about SDK authoring.
- Do not promote archive-only runtimes into first-class pages.
- Do not delete pages before the relocation matrix says what happens to them.
- Prefer source-backed snippets over pasted runnable examples.
- If a useful page is stale, rewrite it; do not discard it by default.

## Example Rules

- Add or edit the real source files first under `meshagent-docs/examples/`.
- Regenerate snippets after example changes.
- Update `examples/catalog.yaml` when adding canonical or archived examples.
- Keep examples concrete and runnable.
- If an example cannot be validated yet, do not present it as canonical.

## Required Checks Before Finishing

- Regenerate snippets when example sources changed.
- Regenerate CLI help when CLI docs sources changed.
- check `git diff --check`
- confirm docs changes still align with `public-surfaces.yaml`
- update migration artifacts when the work changes inventory, gaps, or relocation status

## Out Of Scope

- This skill does not choose the final IA by itself.
- This skill does not treat old runtime families as the recommended path for new users.
