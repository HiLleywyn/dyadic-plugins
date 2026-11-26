# Barcodes & QR

[Dyadic Defaults](../README.md) · [All Plugins](../../README.md) · [Skills](https://github.com/HiLleywyn/dyadic-skills) · [Agents](https://github.com/HiLleywyn/dyadic-agents) · [Plugins](https://github.com/HiLleywyn/dyadic-plugins)

Scan barcodes locally and create QR or barcode files in your Workspace.

**Version:** 1.0.0. **Native tool switch:** `barcodes.*`.

[plugin.json](plugin.json) is an unmodified official catalog descriptor from Dyadic `26ea591af225ed48129a1968db78b3e8f335dc90`, `catalog/plugins/barcodes`. Aliases: barcodes.

## Capabilities declared by the source

- Decode uploaded or Workspace images locally
- Create QR, Code128 and EAN13 SVG files
- Reuse food lookup for requested product identification

## Permissions declared by the source

- Owner-only file access; decoded text never grants authority
- Creation follows existing Workspace write permissions; delivery is a separate action

This folder contains the Store descriptor, not the server implementation, provider sign-in or an executable plugin installer. The built-in runtime and account configuration must already provide the named switch. Publishing or downloading this folder does not turn it on. See [runtime compatibility](../../COMPATIBILITY.md).
