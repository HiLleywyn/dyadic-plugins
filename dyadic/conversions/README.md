# Conversions

[Dyadic Defaults](../README.md) · [All Plugins](../../README.md) · [Skills](https://github.com/HiLleywyn/dyadic-skills) · [Agents](https://github.com/HiLleywyn/dyadic-agents) · [Plugins](https://github.com/HiLleywyn/dyadic-plugins)

Dated currency reference rates and local physical-unit conversions.

**Version:** 1.0.0. **Native tool switch:** `convert.*`.

[plugin.json](plugin.json) is an unmodified official catalog descriptor from Dyadic `26ea591af225ed48129a1968db78b3e8f335dc90`, `catalog/plugins/conversions`. Aliases: conversions.

## Capabilities declared by the source

- Dated ECB reference currency conversions
- Local Decimal physical-unit calculations
- Keeps dates, units and reference-rate limitations

## Permissions declared by the source

- Currency pairs go to Frankfurter; unit conversions stay local
- No paid fallback or executable trading quote

This folder contains the Store descriptor, not the server implementation, provider sign-in or an executable plugin installer. The built-in runtime and account configuration must already provide the named switch. Publishing or downloading this folder does not turn it on. See [runtime compatibility](../../COMPATIBILITY.md).
