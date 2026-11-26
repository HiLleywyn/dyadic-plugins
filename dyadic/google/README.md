# Google Workspace

[Dyadic Defaults](../README.md) · [All Plugins](../../README.md) · [Skills](https://github.com/HiLleywyn/dyadic-skills) · [Agents](https://github.com/HiLleywyn/dyadic-agents) · [Plugins](https://github.com/HiLleywyn/dyadic-plugins)

Drive, Gmail, Calendar, Docs and Sheets as your Google account, at the level you allow each. Sending email, calendar changes and edits ask you first.

**Version:** 1.0.0. **Native tool switch:** `google.*`.

[plugin.json](plugin.json) is an unmodified official catalog descriptor from Dyadic `26ea591af225ed48129a1968db78b3e8f335dc90`, `catalog/plugins/google`. Aliases: google, gmail, drive, calendar, docs, sheets.

## Capabilities declared by the source

- Searches and reads your Drive (Google Docs, Sheets and Slides as text), uploads text files, makes folders, and moves, renames or trashes files
- Searches and reads your Gmail, saves drafts, and sends email (replies stay in their thread)
- Reads your Google Calendar, finds when you're free, and creates, changes or cancels events (guests are told)
- Reads, creates and edits Google Docs, and reads, creates and updates Google Sheets
- Works in your scheduled runs too: reading and drafting, never sending or changing

## Permissions declared by the source

- Off until you install it and connect your Google account here
- You choose each service's level (off, read, or read and change); Google's screen asks for exactly that, and you can lower a level at any time
- Keeps Google's tokens encrypted on Dyadic, refreshes them itself, and never shows them to you, the AI or anyone's apps
- Asks you first before sending an email, any calendar change, any change in Drive, and edits to existing Docs or Sheets, showing all of it
- Drafts and brand-new Docs or Sheets don't ask: they change nothing that exists
- Only your own chats and schedules use it; apps on your API keys don't
- Uninstalling or disconnecting revokes Dyadic's access at Google
- Free: it costs nothing beyond the conversation

This folder contains the Store descriptor, not the server implementation, provider sign-in or an executable plugin installer. The built-in runtime and account configuration must already provide the named switch. Publishing or downloading this folder does not turn it on. See [runtime compatibility](../../COMPATIBILITY.md).
