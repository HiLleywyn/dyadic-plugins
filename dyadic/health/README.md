# Health & Exercise

[Dyadic Defaults](../README.md) · [All Plugins](../../README.md) · [Skills](https://git.lley.cat/r/1a151e58-468a-45f1-a028-92c95690ad68?ref=store) · [Agents](https://git.lley.cat/r/dadd28be-7d91-432f-beb0-00d285e8f02b?ref=store) · [Plugins](https://git.lley.cat/r/ae86ea71-cb4d-4fc5-9ec1-803f8f303989?ref=store)

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
