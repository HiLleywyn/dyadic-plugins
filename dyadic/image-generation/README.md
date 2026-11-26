# Image Generation

[Dyadic Defaults](../README.md) · [All Plugins](../../README.md) · [Skills](https://github.com/HiLleywyn/dyadic-skills) · [Agents](https://github.com/HiLleywyn/dyadic-agents) · [Plugins](https://github.com/HiLleywyn/dyadic-plugins)

Create images from a description or a reference upload.

**Version:** 1.0.0. **Native tool switch:** `image.generate`.

[plugin.json](plugin.json) is an unmodified official catalog descriptor from Dyadic `26ea591af225ed48129a1968db78b3e8f335dc90`, `catalog/plugins/image-generation`. Aliases: image generator.

## Capabilities declared by the source

- Makes images from a description
- Changes an image you upload or one it made
- Saves every image to your Images library

## Permissions declared by the source

- Sends the description, and any reference image, to the image model
- Uses credits for each image

This folder contains the Store descriptor, not the server implementation, provider sign-in or an executable plugin installer. The built-in runtime and account configuration must already provide the named switch. Publishing or downloading this folder does not turn it on. See [runtime compatibility](../../COMPATIBILITY.md).
