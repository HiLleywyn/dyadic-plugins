# Scheduler

[Dyadic Defaults](../README.md) · [All Plugins](../../README.md) · [Skills](https://github.com/HiLleywyn/dyadic-skills) · [Agents](https://github.com/HiLleywyn/dyadic-agents) · [Plugins](https://github.com/HiLleywyn/dyadic-plugins)

Have an agent do something on a schedule, like every Tuesday or every hour, and tell you when something happens.

**Version:** 1.0.0. **Native tool switch:** `schedule.*`.

[plugin.json](plugin.json) is an unmodified official catalog descriptor from Dyadic `26ea591af225ed48129a1968db78b3e8f335dc90`, `catalog/plugins/scheduler`. Aliases: none.

## Capabilities declared by the source

- Sets up a schedule from a chat: "every weekday at 9, summarize my unread files" or "check this page every hour and tell me if the price drops below $50"
- Runs hourly at a minute, daily at a time, weekly on the days you choose, or monthly on a day, in your time zone
- Posts each run's result in the schedule's own chat, so you can read back and ask follow-ups
- Notifies you under the bell when a run finishes or when the agent has something to tell you, and by email if you ask
- Lists every schedule on the Scheduled page, to pause, resume, run now, edit or delete

## Permissions declared by the source

- Off until you install it
- Asks you first before it sets up a schedule, showing when it runs, the next three times and what it will do
- Runs with nobody watching, so anything that needs your approval is refused: a browser submitting a form, an HTTP change, a memory change you didn't ask for
- Each run uses your credits like a message you send; a schedule pauses after 3 failed runs in a row, or when your credits run out, and tells you why
- Up to 10 active schedules, at most once an hour each; a run missed while Dyadic was down runs once
- Emails only your verified address, at most 20 a day, each with a link to turn email off
- Free: notifications and emails cost nothing beyond the runs themselves

This folder contains the Store descriptor, not the server implementation, provider sign-in or an executable plugin installer. The built-in runtime and account configuration must already provide the named switch. Publishing or downloading this folder does not turn it on. See [runtime compatibility](../../COMPATIBILITY.md).
