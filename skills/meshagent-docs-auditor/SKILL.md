---
name: meshagent-docs-auditor
description: Audit MeshAgent docs against code, examples, public-surface metadata, and migration artifacts without mutating the docs.
---

# MeshAgent Docs Auditor

Use this skill when the task is to inspect, map, or report on docs coverage and drift without editing files.

## Use This Skill When

- The task is to audit what is documented versus what exists in code.
- The task is to label docs as current, stale, archive, duplicate, or thin.
- The task is to identify gaps before a docs migration wave.
- The task is to check whether examples are source-backed and cataloged.

## Inputs

- `meshagent-sdk/meshagent-docs/public-surfaces.yaml`
- `meshagent-sdk/meshagent-docs/examples/catalog.yaml`
- `/Users/tulamasterman/code/meshagent-server/docs-migration/`
- current docs pages under `meshagent-sdk/meshagent-docs/`
- current public code surfaces in `meshagent-sdk/`, `meshagent-studio/`, and `powerboards/`

## Audit Questions

- Is the code surface current, transitional, or archive-only?
- Does a first-class docs page already exist for it?
- Is the existing page current, stale, thin, or archive-only?
- Does the page use real example sources?
- Is the example catalog entry present and accurate?
- Does the relocation matrix already describe what should happen to the page?

## Operating Rules

- Prefer deterministic repo facts over assumptions.
- Distinguish missing docs from intentionally archived docs.
- Treat generated CLI help as reference material, not as the information architecture.
- Keep Room APIs grouped in audit recommendations.
- Flag pages that should be preserved even if they are currently unpublished.

## Expected Output

- codebase map updates
- docs inventory updates
- coverage gap updates
- relocation recommendations
- example catalog drift findings
- public-surface drift findings
