# OCR

[Dyadic Defaults](../README.md) · [All Plugins](../../README.md) · [Skills](https://github.com/HiLleywyn/dyadic-skills) · [Agents](https://github.com/HiLleywyn/dyadic-agents) · [Plugins](https://github.com/HiLleywyn/dyadic-plugins)

Read the text in scans, screenshots, receipts and photos of documents.

**Version:** 1.0.0. **Native tool switch:** `vision.read_text`.

[plugin.json](plugin.json) is an unmodified official catalog descriptor from Dyadic `26ea591af225ed48129a1968db78b3e8f335dc90`, `catalog/plugins/ocr`. Aliases: none.

## Capabilities declared by the source

- Reads scanned PDFs page by page, and screenshots, receipts, forms and diagrams
- Keeps tables, lists and form fields as they are laid out
- Makes scanned PDFs in your Workspace files searchable once it has read them
- Remembers what it read, so reading a page again is free

## Permissions declared by the source

- Sends each page or image to the vision model
- Uses credits for each new page, about a quarter of a cent, and only when you ask

This folder contains the Store descriptor, not the server implementation, provider sign-in or an executable plugin installer. The built-in runtime and account configuration must already provide the named switch. Publishing or downloading this folder does not turn it on. See [runtime compatibility](../../COMPATIBILITY.md).
