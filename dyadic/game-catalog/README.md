# Game Catalog

[Dyadic Defaults](../README.md) · [All Plugins](../../README.md) · [Skills](https://github.com/HiLleywyn/dyadic-skills) · [Agents](https://github.com/HiLleywyn/dyadic-agents) · [Plugins](https://github.com/HiLleywyn/dyadic-plugins)

CheapShark deals and Steam metadata, requirements and regional prices. Separate from games to play.

**Version:** 1.0.0. **Native tool switch:** `games.catalog`.

[plugin.json](plugin.json) is an unmodified official catalog descriptor from Dyadic `26ea591af225ed48129a1968db78b3e8f335dc90`, `catalog/plugins/game-catalog`. Aliases: game-catalog.

## Capabilities declared by the source

- CheapShark deals and Steam metadata, requirements and regional prices. Separate from games to play.

## Permissions declared by the source

- Sends only the requested public catalog query to its provider
- Read-only metadata; no purchases, playback, account changes or automatic source fetching

This folder contains the Store descriptor, not the server implementation, provider sign-in or an executable plugin installer. The built-in runtime and account configuration must already provide the named switch. Publishing or downloading this folder does not turn it on. See [runtime compatibility](../../COMPATIBILITY.md).
