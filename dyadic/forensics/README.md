# Forensics

[Dyadic Defaults](../README.md) · [All Plugins](../../README.md) · [Skills](https://github.com/HiLleywyn/dyadic-skills) · [Agents](https://github.com/HiLleywyn/dyadic-agents) · [Plugins](https://github.com/HiLleywyn/dyadic-plugins)

Investigate public sources, organize private cases and inspect evidence, relationships and timelines.

**Version:** 1.0.0. **Native tool switch:** `forensics.*`.

[plugin.json](plugin.json) is an unmodified official catalog descriptor from Dyadic `26ea591af225ed48129a1968db78b3e8f335dc90`, `catalog/plugins/forensics`. Aliases: forensics, investigation, evidence, public records, infrastructure research.

## Capabilities declared by the source

- Private append-only cases and attributable evidence
- Public records and passive infrastructure research
- Relationship graphs, timelines and heuristic analysis
- Versioned investigation workflows and downloadable reports

## Permissions declared by the source

- Case changes follow Workspace authorization and are private to the account
- Public collection is bounded; no private networks, logins or active browser probes
- Offline file analysis uses the existing read-only Code Sandbox

This folder contains the Store descriptor, not the server implementation, provider sign-in or an executable plugin installer. The built-in runtime and account configuration must already provide the named switch. Publishing or downloading this folder does not turn it on. See [runtime compatibility](../../COMPATIBILITY.md).
