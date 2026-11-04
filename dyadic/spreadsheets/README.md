# Spreadsheets

[Dyadic Defaults](../README.md) · [All Plugins](../../README.md) · [Skills](https://git.lley.cat/r/1a151e58-468a-45f1-a028-92c95690ad68?ref=store) · [Agents](https://git.lley.cat/r/dadd28be-7d91-432f-beb0-00d285e8f02b?ref=store) · [Plugins](https://git.lley.cat/r/ae86ea71-cb4d-4fc5-9ec1-803f8f303989?ref=store)

Make and edit Excel and CSV files, with formulas, tables and charts.

**Version:** 1.0.0. **Native tool switch:** `spreadsheets.*`.

[plugin.json](plugin.json) is an unmodified official catalog descriptor from Dyadic `26ea591af225ed48129a1968db78b3e8f335dc90`, `catalog/plugins/spreadsheets`. Aliases: spreadsheet, Excel.

## Capabilities declared by the source

- Reads Excel workbooks and CSV files, formulas included
- Makes workbooks with formulas, number formats, tables and frozen headers
- Draws native Excel charts: column, bar, line, area, pie and scatter
- Adds rows, cells, sheets and charts to an existing workbook and keeps what it has

## Permissions declared by the source

- Reads files in your workspace and files you attach
- Makes and changes files in your offline sandbox, with no network
- Asks before changing files once it has read outside content

This folder contains the Store descriptor, not the server implementation, provider sign-in or an executable plugin installer. The built-in runtime and account configuration must already provide the named switch. Publishing or downloading this folder does not turn it on. See [runtime compatibility](../../COMPATIBILITY.md).
