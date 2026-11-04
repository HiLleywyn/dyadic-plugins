# OCR

[Dyadic Defaults](../README.md) · [All Plugins](../../README.md) · [Skills](https://git.lley.cat/r/1a151e58-468a-45f1-a028-92c95690ad68?ref=store) · [Agents](https://git.lley.cat/r/dadd28be-7d91-432f-beb0-00d285e8f02b?ref=store) · [Plugins](https://git.lley.cat/r/ae86ea71-cb4d-4fc5-9ec1-803f8f303989?ref=store)

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
