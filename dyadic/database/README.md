# Database

[Dyadic Defaults](../README.md) · [All Plugins](../../README.md) · [Skills](https://git.lley.cat/r/1a151e58-468a-45f1-a028-92c95690ad68?ref=store) · [Agents](https://git.lley.cat/r/dadd28be-7d91-432f-beb0-00d285e8f02b?ref=store) · [Plugins](https://git.lley.cat/r/ae86ea71-cb4d-4fc5-9ec1-803f8f303989?ref=store)

Explore and query your PostgreSQL, MySQL and SQLite databases. Reads only, unless you allow changes, and every change asks you first.

**Version:** 1.0.0. **Native tool switch:** `database.*`.

[plugin.json](plugin.json) is an unmodified official catalog descriptor from Dyadic `26ea591af225ed48129a1968db78b3e8f335dc90`, `catalog/plugins/database`. Aliases: db.

## Capabilities declared by the source

- Lists a database's tables and views, their columns and types, and about how many rows each has
- Runs SQL for you, from lookups to totals and trends, and shows the result as a compact table
- Connects to PostgreSQL and MySQL servers, or to an SQLite file in your Workspace files
- Changes data (insert, update, delete, create a table) only on a connection where you allow changes

## Permissions declared by the source

- Off until you install it
- Reads in a read-only transaction the database itself enforces: at most 200 rows and 15 seconds a statement
- Changes only a connection you set to Allow changes, and asks you first every time, showing the exact SQL
- Scheduled runs only read: a change there is refused
- Reaches public database servers only, never your own network, private addresses or Dyadic's own database
- Keeps each password encrypted, uses it only to connect to that server, and never shows it to you or the AI again
- Opens SQLite files in your private, offline Code Sandbox
- Free: it costs nothing beyond the conversation

This folder contains the Store descriptor, not the server implementation, provider sign-in or an executable plugin installer. The built-in runtime and account configuration must already provide the named switch. Publishing or downloading this folder does not turn it on. See [runtime compatibility](../../COMPATIBILITY.md).
