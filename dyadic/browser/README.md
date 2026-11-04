# Browser

[Dyadic Defaults](../README.md) · [All Plugins](../../README.md) · [Skills](https://git.lley.cat/r/1a151e58-468a-45f1-a028-92c95690ad68?ref=store) · [Agents](https://git.lley.cat/r/dadd28be-7d91-432f-beb0-00d285e8f02b?ref=store) · [Plugins](https://git.lley.cat/r/ae86ea71-cb4d-4fc5-9ec1-803f8f303989?ref=store)

Use a real web browser: open pages, click, fill in forms and download files.

**Version:** 1.0.0. **Native tool switch:** `browser.*`.

[plugin.json](plugin.json) is an unmodified official catalog descriptor from Dyadic `26ea591af225ed48129a1968db78b3e8f335dc90`, `catalog/plugins/browser`. Aliases: web browser.

## Capabilities declared by the source

- Opens pages in a real browser, so sites that need scripts work, and reads each page as text
- Clicks, types, chooses options, scrolls, goes back and switches tabs, checking the page after each step
- Downloads files a page links to into your Workspace files, up to 20 MB each
- Shows the page it is on while it works, with a picture you can tap to enlarge, and Stop to end it

## Permissions declared by the source

- Off until you install it
- Asks you first before it submits a form, buys or pays, sends or posts, deletes, or types words that are not from your message or the page
- Never types passwords: signing in to sites is not supported
- Opens public web addresses only, in a fresh browser for each chat that keeps no cookies and closes after 5 idle minutes
- Costs about $0.0005 per step, because it reads each page as text; a screenshot looked at by the vision model costs about $0.001 more

This folder contains the Store descriptor, not the server implementation, provider sign-in or an executable plugin installer. The built-in runtime and account configuration must already provide the named switch. Publishing or downloading this folder does not turn it on. See [runtime compatibility](../../COMPATIBILITY.md).
