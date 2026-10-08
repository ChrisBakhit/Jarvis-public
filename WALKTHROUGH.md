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

## Homelab ideas — October 2026

A public homelab showcase in October 2026 suggested the boundaries below. They are inspiration for someone reading this edition. They are not accepted features, and they do not authorize an install. The showcase's hardware, names, addresses, and photos stay out of this repository.

- Budget an always-on household host by idle power and memory. Describe short spikes, such as photo ingest, media transcode, and document conversion, separately from idle.
- Keep experiments in a separate environment from that always-on host.
- Treat local-first automation, its radios, and its history as existing capability areas. A container or an appliance is a deployment choice.
- Keep scanned papers, photo libraries, and file sync as separate stores. A self-hosted replacement for a cloud service stays inside the store it already belongs to.
- Keep untrusted cameras on an isolated network, with footage stored locally.
- Give a named subset of outbound workloads one restricted route. When that route drops, those workloads stop.
- Publish a local service only through an explicit choice: an outbound tunnel, or a local name that stays inside the network. Firewall policy stays its own decision.
- Count a backup when a restore matches the source. A second view of the same repository is the same backup.
- Keep monitoring thinner than the system it watches.
- Split services into an explicit always-on set and a set that starts for a task and then stops.
- When the always-on host is also the network path between other machines, record that dependency and what happens when the host is down.
- Keep a household password store separate from the assistant's credential broker.
- Record a trial of two tools as one evaluation. The survivor is still a single candidate.

## When this page should change

Update this path when a reviewed export actually lands: name the manifest, say which seams replaced personal configuration, and keep [HANDOFF.md](HANDOFF.md) honest about what is still not accepted. Until that export exists, the useful review is the boundary in `HANDOFF.md`, not a search for missing source.
