# Health & Exercise

[Dyadic Defaults](../README.md) · [All Plugins](../../README.md) · [Skills](https://github.com/HiLleywyn/dyadic-skills) · [Agents](https://github.com/HiLleywyn/dyadic-agents) · [Plugins](https://github.com/HiLleywyn/dyadic-plugins)

Public RxNorm drug references, FDA drug recalls and attributed wger exercise browsing. Medical research reuses Science.

**Version:** 1.0.0. **Native tool switch:** `health.*`.

[plugin.json](plugin.json) is an unmodified official catalog descriptor from Dyadic `26ea591af225ed48129a1968db78b3e8f335dc90`, `catalog/plugins/health`. Aliases: health, medicine, exercise, fitness.

## Capabilities declared by the source

- Drug name and identifier lookup
- US FDA drug recall records
- Public exercise categories and exercise details

## Permissions declared by the source

- Read-only public reference queries; never send patient details
- No clinical decisions, prescriptions, private routines or health-account access

This folder contains the Store descriptor, not the server implementation, provider sign-in or an executable plugin installer. The built-in runtime and account configuration must already provide the named switch. Publishing or downloading this folder does not turn it on. See [runtime compatibility](../../COMPATIBILITY.md).
