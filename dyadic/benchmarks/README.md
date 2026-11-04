# AI Benchmarks

[Dyadic Defaults](../README.md) · [All Plugins](../../README.md) · [Skills](https://git.lley.cat/r/1a151e58-468a-45f1-a028-92c95690ad68?ref=store) · [Agents](https://git.lley.cat/r/dadd28be-7d91-432f-beb0-00d285e8f02b?ref=store) · [Plugins](https://git.lley.cat/r/ae86ea71-cb4d-4fc5-9ec1-803f8f303989?ref=store)

Compare published model benchmark evidence from OpenRouter and BenchLM, with source dates and uncertainty.

**Version:** 1.0.0. **Native tool switch:** `benchmarks.*`.

[plugin.json](plugin.json) is an unmodified official catalog descriptor from Dyadic `26ea591af225ed48129a1968db78b3e8f335dc90`, `catalog/plugins/benchmarks`. Aliases: benchmarks, model rankings, BenchLM, OpenRouter benchmarks.

## Capabilities declared by the source

- Read OpenRouter evaluations and source-specific scores
- Inspect BenchLM rankings, model identities and read allowance
- Preserve provenance, methodology, evidence labels and missing data

## Permissions declared by the source

- Read-only requests to fixed provider endpoints using dedicated server credentials
- Private queries and internal analysis; source reuse terms remain applicable
- No paid evaluations, model configuration changes or inference-key fallback

This folder contains the Store descriptor, not the server implementation, provider sign-in or an executable plugin installer. The built-in runtime and account configuration must already provide the named switch. Publishing or downloading this folder does not turn it on. See [runtime compatibility](../../COMPATIBILITY.md).
