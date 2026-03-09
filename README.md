# ai-context

Portable, model-agnostic context profiles (YAML) for working across multiple AI models and modalities.

## How to use


These profiles are meant to be **pasted** into any stateless model to quickly align behavior.
### 1) Pick a manifest (recommended)
- `manifests/manifest_general.yaml` for everyday tasks
- `manifests/manifest_work.yaml` for work/ops-heavy tasks

Paste the manifest at the top of a new chat with a stateless model, then paste your task.

### 2) Or assemble manually (advanced)
Paste:
1. `core/00_global.yaml`
2. a role file from `roles/`
3. (optional) `core/99_handoff.yaml`
4. your task prompt

## Repo structure


- `projects/` project-specific constraints and defaults
- `core/` invariants (tone, rules, output contract)
- `roles/` task-role nuance (research/coding/ops/creative/vision/trainer-cap)
- `manifests/` pre-composed bundles to paste quickly
- `logs/` templates for tracking changes

## Versioning

Use Semantic Versioning (MAJOR.MINOR.PATCH).
- PATCH: wording/format tweaks
- MINOR: add rules/sections
- MAJOR: restructure philosophy or output contract

## Security

Do not put secrets, credentials, or sensitive personal logs in this repo.
Treat it like configuration, not a diary.

Last updated: 2026-01-21

## Projects
Project profiles live in `projects/` and are bundled via `manifests/manifest_<project_id>.yaml`.
