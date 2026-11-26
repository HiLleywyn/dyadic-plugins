# Flight Observations

[Dyadic Defaults](../README.md) · [All Plugins](../../README.md) · [Skills](https://github.com/HiLleywyn/dyadic-skills) · [Agents](https://github.com/HiLleywyn/dyadic-agents) · [Plugins](https://github.com/HiLleywyn/dyadic-plugins)

FlyItalyADSB aircraft observations near coordinates or by callsign, registration or ICAO hex. Community receiver coverage, not schedules or fares.

**Version:** 1.0.0. **Native tool switch:** `flights.*`.

[plugin.json](plugin.json) is an unmodified official catalog descriptor from Dyadic `26ea591af225ed48129a1968db78b3e8f335dc90`, `catalog/plugins/flights`. Aliases: flights, aircraft, FlyItalyADSB.

## Capabilities declared by the source

- Current aircraft observations
- Bounded nearby lookup with position age and units

## Permissions declared by the source

- Workspace-only public flight observations; CC BY-SA 4.0 attribution
- No API/feed redistribution, paid upgrade, continuous tracking or passenger data

This folder contains the Store descriptor, not the server implementation, provider sign-in or an executable plugin installer. The built-in runtime and account configuration must already provide the named switch. Publishing or downloading this folder does not turn it on. See [runtime compatibility](../../COMPATIBILITY.md).
