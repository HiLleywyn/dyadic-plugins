# Food & Nutrition

[Dyadic Defaults](../README.md) · [All Plugins](../../README.md) · [Skills](https://github.com/HiLleywyn/dyadic-skills) · [Agents](https://github.com/HiLleywyn/dyadic-agents) · [Plugins](https://github.com/HiLleywyn/dyadic-plugins)

Look up food labels, barcodes, nutrients and recipes.

**Version:** 1.0.0. **Native tool switch:** `food.*`.

[plugin.json](plugin.json) is an unmodified official catalog descriptor from Dyadic `26ea591af225ed48129a1968db78b3e8f335dc90`, `catalog/plugins/food`. Aliases: food.

## Capabilities declared by the source

- Packaged-food labels and barcode lookup
- USDA nutrients when a free key is configured
- Recipes when a production supporter key is configured

## Permissions declared by the source

- Sends requested food names or barcode digits to the selected catalog
- Incomplete labels cannot guarantee allergy safety; catalog licenses remain separate

This folder contains the Store descriptor, not the server implementation, provider sign-in or an executable plugin installer. The built-in runtime and account configuration must already provide the named switch. Publishing or downloading this folder does not turn it on. See [runtime compatibility](../../COMPATIBILITY.md).
