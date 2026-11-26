# Your Computer

[Dyadic Defaults](../README.md) · [All Plugins](../../README.md) · [Skills](https://github.com/HiLleywyn/dyadic-skills) · [Agents](https://github.com/HiLleywyn/dyadic-agents) · [Plugins](https://github.com/HiLleywyn/dyadic-plugins)

Let Iris run commands on your own computer through the Dyadic Runner and send you files from it: build and start Docker containers, deploy, use your tools. Pair it with one command and a code; it asks you first unless you allow it.

**Version:** 2.3.0. **Native tool switch:** `machine.*`.

[plugin.json](plugin.json) is an unmodified official catalog descriptor from Dyadic `26ea591af225ed48129a1968db78b3e8f335dc90`, `catalog/plugins/computer`. Aliases: computer, machine, runner, pc, laptop, server.

## Capabilities declared by the source

- Runs commands on your computer in its own shell (PowerShell on Windows, bash on macOS and Linux): builds, tests, docker compose up, deploys, WSL
- Sends you files from your computer, and saves files from a chat on it (your home folder, or the folder you started it in), up to 20 MB
- Works with what's already there: your files, Docker, git and tools, inside the folder you started it in
- Several computers, each for the Code projects you choose; pause one, or unpair it, at any time

## Permissions declared by the source

- Off until you install it and pair a computer: one command on it (nothing else to install on Windows; Python 3 on macOS and Linux), then a code or QR code you confirm with your passkey
- Once paired, it runs in the background and starts when you sign in, for your account only and never as administrator; stop it there with the command it shows, or pause or unpair it here
- The runner connects out to Dyadic: no ports to open on your computer. Its key never leaves your computer; Dyadic keeps only its hash
- Only the Code projects you choose can use a computer; commands start inside the folder you started the runner in
- Asks you first before every command and every file it sends, showing the computer and exactly what it will do
- Each computer has its own Permissions: run commands, send files or save files without asking, always allow plain commands like docker ps, or Never Ask; allowing more takes your passkey
- Saved files never replace one unless asked, never go where something starts at sign-in, in a profile or .ssh, are marked as downloaded, and are never run
- A chat that has read outside content (web pages, emails, other people's files) always asks first
- Pause a computer to stop new commands (the pairing stays), or unpair it to stop its key; a command is never sent twice
- Scheduled runs never run commands on your computer
- Free: it costs nothing beyond the conversation

This folder contains the Store descriptor, not the server implementation, provider sign-in or an executable plugin installer. The built-in runtime and account configuration must already provide the named switch. Publishing or downloading this folder does not turn it on. See [runtime compatibility](../../COMPATIBILITY.md).
