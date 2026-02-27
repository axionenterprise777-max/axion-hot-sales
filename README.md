# Axion Hot Sales

## Public Snapshot

This repository publishes a public-ready application snapshot focused on runnable source, UI assets, and deploy-safe code only.

Version tag target: `v1.0.0`

## Included

- Sanitized source code and public assets.
- Build metadata needed to understand the project structure.
- A generated README designed for public handoff.

## Excluded

- Environment files and secret-bearing configuration.
- Internal notes, operational documents, and workspace-only reports.
- Local caches, dependencies, generated build folders, and private backups.

## Repository Layout

- ``public``
- ``src``
- ``.gitignore``
- ``package-lock.json``
- ``package.json``

## Quick Start

- ``npm run start``: npx serve . -p 3000
- ``npm run dev``: npx serve . -p 3000 -l
- ``npm run build``: echo 'Build complete'

## Release Policy

- Public releases are tagged with semantic versioning when package metadata is available.
- This repository is intended to expose professional, shareable source snapshots without internal workspace context.

## Notes

- Generated from the SANDBOX workspace using a sanitization pipeline.
- Public-facing content was intentionally reduced to avoid leaking internal details.
- Screenshots already indexed for this project: **2** real captures in the central `portfolio` repository.

