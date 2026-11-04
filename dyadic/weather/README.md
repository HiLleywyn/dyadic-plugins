# Weather

[Dyadic Defaults](../README.md) · [All Plugins](../../README.md) · [Skills](https://git.lley.cat/r/1a151e58-468a-45f1-a028-92c95690ad68?ref=store) · [Agents](https://git.lley.cat/r/dadd28be-7d91-432f-beb0-00d285e8f02b?ref=store) · [Plugins](https://git.lley.cat/r/ae86ea71-cb4d-4fc5-9ec1-803f8f303989?ref=store)

Forecasts, official alerts and specialized weather data, with source attribution.

**Version:** 1.0.0. **Native tool switch:** `weather.*`.

[plugin.json](plugin.json) is an unmodified official catalog descriptor from Dyadic `26ea591af225ed48129a1968db78b3e8f335dc90`, `catalog/plugins/weather`. Aliases: weather.

## Capabilities declared by the source

- Forecasts reuse NWS, MET Norway and DWD
- Recent US station observations and active alerts
- Licensed global history, model forecasts, marine waves and air quality when configured

## Permissions declared by the source

- Sends requested locations to weather providers
- Advanced Open-Meteo products require a licensed key and explicit operator enablement

This folder contains the Store descriptor, not the server implementation, provider sign-in or an executable plugin installer. The built-in runtime and account configuration must already provide the named switch. Publishing or downloading this folder does not turn it on. See [runtime compatibility](../../COMPATIBILITY.md).
