# AGENTS.md

## Purpose

- This subtree owns reusable UI components for `src/components`.
- Keep this file current when responsibilities, contracts, or child docs change.

## Ownership

- Applies to every file under `src/components` unless a deeper AGENTS.md overrides it.
- Parent instructions from the repository root remain binding.

## Local Contracts

- Key local files: Footer.jsx, HalftoneImage.css, HalftoneImage.jsx, Icons.jsx, Layout.jsx, LazySection.jsx, LoadingScreen.css, LoadingScreen.jsx, Navbar.css, Navbar.jsx.
- Preserve public interfaces, route names, data shapes, and documented workflows unless the task explicitly changes them.

## Work Guidance

- Read the nearest child AGENTS.md before editing nested areas listed below.
- Keep edits focused on the requested behavior and avoid speculative restructuring.
- Update this doc if the subtree gains a new durable boundary, workflow, or verification rule.

## Verification

- Run the smallest relevant check: `npm run lint`, `npm run build`.

## Child DOX Index

- No child AGENTS.md files yet.
