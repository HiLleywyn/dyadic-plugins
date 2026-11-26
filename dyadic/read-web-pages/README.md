# Web Page Reader

[Dyadic Defaults](../README.md) · [All Plugins](../../README.md) · [Skills](https://github.com/HiLleywyn/dyadic-skills) · [Agents](https://github.com/HiLleywyn/dyadic-agents) · [Plugins](https://github.com/HiLleywyn/dyadic-plugins)

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
