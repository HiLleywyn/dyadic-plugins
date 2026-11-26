# Image Analysis

[Dyadic Defaults](../README.md) · [All Plugins](../../README.md) · [Skills](https://github.com/HiLleywyn/dyadic-skills) · [Agents](https://github.com/HiLleywyn/dyadic-agents) · [Plugins](https://github.com/HiLleywyn/dyadic-plugins)

Look at an image and describe it, or answer a question about it.

**Version:** 1.0.0. **Native tool switch:** `vision.describe_image`.

[plugin.json](plugin.json) is an unmodified official catalog descriptor from Dyadic `26ea591af225ed48129a1968db78b3e8f335dc90`, `catalog/plugins/image-analysis`. Aliases: none.

## Capabilities declared by the source

- Describes a photo, chart, diagram or screenshot
- Answers a specific question about what an image shows
- Works on images you attach, images in your workspace and public image links

## Permissions declared by the source

- Sends the image, and your question, to the vision model
- Uses credits for each image

This folder contains the Store descriptor, not the server implementation, provider sign-in or an executable plugin installer. The built-in runtime and account configuration must already provide the named switch. Publishing or downloading this folder does not turn it on. See [runtime compatibility](../../COMPATIBILITY.md).
