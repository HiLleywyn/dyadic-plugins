# GitHub

[Dyadic Defaults](../README.md) · [All Plugins](../../README.md) · [Skills](https://git.lley.cat/r/1a151e58-468a-45f1-a028-92c95690ad68?ref=store) · [Agents](https://git.lley.cat/r/dadd28be-7d91-432f-beb0-00d285e8f02b?ref=store) · [Plugins](https://git.lley.cat/r/ae86ea71-cb4d-4fc5-9ec1-803f8f303989?ref=store)

Read and change your GitHub repositories: push code from your Workspace, create repositories and branches, open and merge pull requests, and manage issues. Every change asks you first.

**Version:** 1.1.0. **Native tool switch:** `github.*`.

[plugin.json](plugin.json) is an unmodified official catalog descriptor from Dyadic `26ea591af225ed48129a1968db78b3e8f335dc90`, `catalog/plugins/github`. Aliases: none.

## Capabilities declared by the source

- Searches code, issues, pull requests and repositories with GitHub's own search syntax
- Reads a repository's facts, a file at any branch, tag or commit, a folder, an issue with its comments, a pull request with its files and diff, and recent commits
- Clones your repositories into the Workspace, private ones too
- Pushes many files as one commit, from a Workspace folder or written out, to an existing or new branch
- Creates repositories and branches, opens and merges pull requests
- Creates, closes, reopens and comments on issues, and adds labels

## Permissions declared by the source

- Off until you install it
- Reaches api.github.com only
- Signs in with a personal access token you paste here; GitHub is asked who it belongs to before it is kept
- Keeps the token encrypted and never shows it to you or the AI again
- Without a token it reads public repositories only, within GitHub's 60 requests an hour
- Asks you first before every change, showing the repository, what it will do and the full text or diff; scheduled runs only read
- Only your own chats and schedules use it; apps on your API keys don't
- Free: it costs nothing beyond the conversation

This folder contains the Store descriptor, not the server implementation, provider sign-in or an executable plugin installer. The built-in runtime and account configuration must already provide the named switch. Publishing or downloading this folder does not turn it on. See [runtime compatibility](../../COMPATIBILITY.md).
