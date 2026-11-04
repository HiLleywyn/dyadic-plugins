# HTTP Request

[Dyadic Defaults](../README.md) · [All Plugins](../../README.md) · [Skills](https://git.lley.cat/r/1a151e58-468a-45f1-a028-92c95690ad68?ref=store) · [Agents](https://git.lley.cat/r/dadd28be-7d91-432f-beb0-00d285e8f02b?ref=store) · [Plugins](https://git.lley.cat/r/ae86ea71-cb4d-4fc5-9ec1-803f8f303989?ref=store)

Call web APIs, REST and GraphQL, with the sign-ins you save. Every change asks you first.

**Version:** 1.0.0. **Native tool switch:** `http.request`.

[plugin.json](plugin.json) is an unmodified official catalog descriptor from Dyadic `26ea591af225ed48129a1968db78b3e8f335dc90`, `catalog/plugins/http-request`. Aliases: none.

## Capabilities declared by the source

- Calls REST and GraphQL APIs: GET, POST, PUT, PATCH and DELETE, with query parameters, headers and a JSON body
- Uses connections you save here: an API's address and how it signs in (a token, a header, a username and password, or a key in the address)
- Reads the answer for you: the status, JSON laid out with long lists shortened, XML or text, and the headers about paging and rate limits
- Follows the API's next-page links on the same site

## Permissions declared by the source

- Off until you install it
- Reaches public HTTPS addresses only, never your own network, private addresses or Dyadic's own services
- Asks you first before every change (POST, PUT, PATCH, DELETE or a GraphQL mutation), showing the method, the full address and what it sends
- Keeps each saved sign-in encrypted, sends it only to that connection's site, and never shows it to you or the AI again
- Apps on your API keys get it only when a key may use your installed plugins, and then only to read: changes are refused
- Up to 30 requests a minute; each waits at most 20 seconds and reads at most 1 MB
- Free: it costs nothing beyond the conversation

This folder contains the Store descriptor, not the server implementation, provider sign-in or an executable plugin installer. The built-in runtime and account configuration must already provide the named switch. Publishing or downloading this folder does not turn it on. See [runtime compatibility](../../COMPATIBILITY.md).
