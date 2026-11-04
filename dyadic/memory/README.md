# Memory

[Dyadic Defaults](../README.md) · [All Plugins](../../README.md) · [Skills](https://git.lley.cat/r/1a151e58-468a-45f1-a028-92c95690ad68?ref=store) · [Agents](https://git.lley.cat/r/dadd28be-7d91-432f-beb0-00d285e8f02b?ref=store) · [Plugins](https://git.lley.cat/r/ae86ea71-cb4d-4fc5-9ec1-803f8f303989?ref=store)

Learn lasting preferences, remember what you ask, and find, change or forget it later.

**Version:** 1.1.0. **Native tool switch:** `memory.*`.

[plugin.json](plugin.json) is an unmodified official catalog descriptor from Dyadic `26ea591af225ed48129a1968db78b3e8f335dc90`, `catalog/plugins/memory`. Aliases: memories.

## Capabilities declared by the source

- Remembers a preference or fact when you ask it to
- Learns grounded, non-sensitive preferences from your own messages when automatic learning is on
- Finds what it remembers, and changes or forgets it when you say
- Uses a project's or library's own memory in its chats when it has one

## Permissions declared by the source

- Automatic learning saves only new, non-sensitive preferences grounded in your current message; other changes ask or need approval
- Nothing from a temporary chat is remembered
- Agents with memory off don't use it
- Use Saved Memories and Learn Automatically can be switched off in Settings > Memory

This folder contains the Store descriptor, not the server implementation, provider sign-in or an executable plugin installer. The built-in runtime and account configuration must already provide the named switch. Publishing or downloading this folder does not turn it on. See [runtime compatibility](../../COMPATIBILITY.md).
