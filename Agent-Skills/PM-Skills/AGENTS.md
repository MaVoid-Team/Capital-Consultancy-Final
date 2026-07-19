# AGENTS.md

## Purpose

- This subtree owns the PM-Skills area for `Agent-Skills/PM-Skills`.
- Keep this file current when responsibilities, contracts, or child docs change.

## Ownership

- Applies to every file under `Agent-Skills/PM-Skills` unless a deeper AGENTS.md overrides it.
- Parent instructions from the repository root remain binding.

## Local Contracts

- Keep this doc focused on durable contracts for this subtree.
- Preserve public interfaces, route names, data shapes, and documented workflows unless the task explicitly changes them.

## Work Guidance

- Read the nearest child AGENTS.md before editing nested areas listed below.
- Keep edits focused on the requested behavior and avoid speculative restructuring.
- Update this doc if the subtree gains a new durable boundary, workflow, or verification rule.

## Verification

- Run the smallest relevant check: `npm run lint`, `npm run build`.

## Child DOX Index

- [commands](commands/AGENTS.md) - the commands area.
- [skills](skills/AGENTS.md) - the skills area.
