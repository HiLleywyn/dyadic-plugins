# Code Sandbox

[Dyadic Defaults](../README.md) · [All Plugins](../../README.md) · [Skills](https://git.lley.cat/r/1a151e58-468a-45f1-a028-92c95690ad68?ref=store) · [Agents](https://git.lley.cat/r/dadd28be-7d91-432f-beb0-00d285e8f02b?ref=store) · [Plugins](https://git.lley.cat/r/ae86ea71-cb4d-4fc5-9ec1-803f8f303989?ref=store)

Files and folders in your workspace, and an network-isolated sandbox to write and run code.

**Version:** 1.2.0. **Native tool switch:** `workspace.*`.

[plugin.json](plugin.json) is an unmodified official catalog descriptor from Dyadic `26ea591af225ed48129a1968db78b3e8f335dc90`, `catalog/plugins/code`. Aliases: sandbox.

## Capabilities declared by the source

- Creates, reads and changes files and folders in your workspace
- Runs Python and shell scripts in an network-isolated sandbox
- Clones public Git repositories to read
- Moves files between your Workspace files and its workspace: opens what you attach or receive, and sends you what it makes
- Unpacks and packs archives (ZIP, tar.gz, RAR, 7z and more) safely, in the sandbox: nothing leaves the folder and nothing runs

## Permissions declared by the source

- Works only in your own private workspace, with no network while code runs
- Asks before deleting files, and before changing them once it has read outside content

This folder contains the Store descriptor, not the server implementation, provider sign-in or an executable plugin installer. The built-in runtime and account configuration must already provide the named switch. Publishing or downloading this folder does not turn it on. See [runtime compatibility](../../COMPATIBILITY.md).
