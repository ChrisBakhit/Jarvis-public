# Public reading path

Start here if you are not the owner. This repository is the public destination for JARVIS. It explains what the project is willing to say in public. It does not contain a runtime you can install.

## Read in this order

1. This file.
2. [README.md](README.md) — what this repository is for.
3. [HANDOFF.md](HANDOFF.md) — current limits and the rules for any later source export.

That is the whole public tree today.

## What you can understand from here

JARVIS is a home and workshop assistant with two editions:

- **This public edition** is for reusable documentation and, later, reviewed source that another person could run without the owner's house, accounts, or devices.
- **The private edition** is [ChrisBakhit/Jarvis](https://github.com/ChrisBakhit/Jarvis). It holds the owner's catalog and operational handoff. You do not need it to understand the public boundary, and its contents are not part of this repository.

A future public feature is supposed to arrive as an explicit file list, with personal endpoints replaced by documented configuration seams and synthetic fixtures. Third-party notices stay attached to third-party code. Local tests, an installed runtime, rendered or audio results, and physical checks are separate claims. A green local test would not mean a house feature works.

## What is intentionally absent

- No application, Home Assistant component, credentials, or device configuration.
- No private snapshot, maintenance receipts, or personal handoff.
- No feature implementations. An incomplete placeholder catalog exists only in the private repository. It has not been copied here because ownership, provenance, and license review are unfinished.
- No redistribution license. Do not treat these files as MIT or as cleared to copy into another project.

## If you were sent the private repository

The private `main` branch is a fail-closed placeholder catalog. The private branch `handoff/2026-10-07-takeover` is an operational handoff for the owner. Neither branch is a public release, and neither should be republished here.

## When this page should change

Update this path when a reviewed export actually lands: name the manifest, say which seams replaced personal configuration, and keep [HANDOFF.md](HANDOFF.md) honest about what is still not accepted. Until that export exists, the useful review is the boundary in `HANDOFF.md`, not a search for missing source.
