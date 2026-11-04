# Web Search

[Dyadic Defaults](../README.md) · [All Plugins](../../README.md) · [Skills](https://git.lley.cat/r/1a151e58-468a-45f1-a028-92c95690ad68?ref=store) · [Agents](https://git.lley.cat/r/dadd28be-7d91-432f-beb0-00d285e8f02b?ref=store) · [Plugins](https://git.lley.cat/r/ae86ea71-cb4d-4fc5-9ec1-803f8f303989?ref=store)

Search the web and cite sources before answering.

**Version:** 1.0.0. **Native tool switch:** `data.web_search`.

[plugin.json](plugin.json) is an unmodified official catalog descriptor from Dyadic `26ea591af225ed48129a1968db78b3e8f335dc90`, `catalog/plugins/web-search`. Aliases: web, internet.

## Capabilities declared by the source

- Searches the web when a question needs current or checkable facts
- Cites the pages it used, linked in the answer
- Reads past the first results when a question needs it

## Permissions declared by the source

- Sends the words of each search to Dyadic's search provider
- Uses credits for each search

This folder contains the Store descriptor, not the server implementation, provider sign-in or an executable plugin installer. The built-in runtime and account configuration must already provide the named switch. Publishing or downloading this folder does not turn it on. See [runtime compatibility](../../COMPATIBILITY.md).
