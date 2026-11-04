# Knowledge Search

[Dyadic Defaults](../README.md) · [All Plugins](../../README.md) · [Skills](https://git.lley.cat/r/1a151e58-468a-45f1-a028-92c95690ad68?ref=store) · [Agents](https://git.lley.cat/r/dadd28be-7d91-432f-beb0-00d285e8f02b?ref=store) · [Plugins](https://git.lley.cat/r/ae86ea71-cb4d-4fc5-9ec1-803f8f303989?ref=store)

Search your files, chats, projects and memory, and cite them.

**Version:** 1.0.0. **Native tool switch:** `knowledge.search`.

[plugin.json](plugin.json) is an unmodified official catalog descriptor from Dyadic `26ea591af225ed48129a1968db78b3e8f335dc90`, `catalog/plugins/knowledge-search`. Aliases: knowledge base.

## Capabilities declared by the source

- Finds the passages in your files, past chats, projects and memory that answer a question
- Says where each one came from: the file, the chat and its date, the project or your memory
- Keeps to this chat's project or library when you ask

## Permissions declared by the source

- Searches only your own Workspace, and only the memory the chat uses
- Indexed in Dyadic at no cost and never sent to another service for it
- Shares your 500 MB search index with your vector stores

This folder contains the Store descriptor, not the server implementation, provider sign-in or an executable plugin installer. The built-in runtime and account configuration must already provide the named switch. Publishing or downloading this folder does not turn it on. See [runtime compatibility](../../COMPATIBILITY.md).
