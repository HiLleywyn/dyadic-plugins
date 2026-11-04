# Web Page Reader

[Dyadic Defaults](../README.md) · [All Plugins](../../README.md) · [Skills](https://git.lley.cat/r/1a151e58-468a-45f1-a028-92c95690ad68?ref=store) · [Agents](https://git.lley.cat/r/dadd28be-7d91-432f-beb0-00d285e8f02b?ref=store) · [Plugins](https://git.lley.cat/r/ae86ea71-cb4d-4fc5-9ec1-803f8f303989?ref=store)

Open and read a link you share.

**Version:** 1.0.0. **Native tool switch:** `data.web_fetch`.

[plugin.json](plugin.json) is an unmodified official catalog descriptor from Dyadic `26ea591af225ed48129a1968db78b3e8f335dc90`, `catalog/plugins/read-web-pages`. Aliases: page reader.

## Capabilities declared by the source

- Opens a link you give and reads the page
- Follows links from search results to the source itself

## Permissions declared by the source

- Fetches public pages over HTTPS from Dyadic's servers
- After reading outside content, only opens links from you or from earlier results

This folder contains the Store descriptor, not the server implementation, provider sign-in or an executable plugin installer. The built-in runtime and account configuration must already provide the named switch. Publishing or downloading this folder does not turn it on. See [runtime compatibility](../../COMPATIBILITY.md).
