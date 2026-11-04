# Plugins

[Skills](https://git.lley.cat/r/1a151e58-468a-45f1-a028-92c95690ad68?ref=store) · [Agents](https://git.lley.cat/r/dadd28be-7d91-432f-beb0-00d285e8f02b?ref=store) · [Plugins](https://git.lley.cat/r/ae86ea71-cb4d-4fc5-9ec1-803f8f303989?ref=store)

Dyadic’s 40 default plugin descriptors, organized under [dyadic/](dyadic/README.md). Every folder has the original `plugin.json`, a readable capability/permission description and navigation back to the collection.

These plugins expose tools implemented by the Dyadic server. A descriptor identifies a Store item and its tool switch; it is not a self-contained executable plugin, MCP server or skill. Account On switches, provider configuration, connected services and execution approvals still determine availability.

## Browse and maintain

- [Default plugin catalog](dyadic/README.md)
- [Machine-readable catalog](catalog.json)
- [Compatibility and blockers](COMPATIBILITY.md)
- [Maintenance and validation](MAINTENANCE.md)
- [Repository delivery report](https://git.lley.cat/r/dadd28be-7d91-432f-beb0-00d285e8f02b?path=REPORT.md&ref=store)

```text
python tools/catalog.py check
python .lley/run.py
python tools/catalog.py build
```

Python 3.11+ and PyYAML are required by the shared collection tooling. Builds make deterministic descriptor archives and checksums for distribution. They are not accepted as executable plugins by Dyadic’s skill/agent importer.

Official definitions are copied without content changes from Dyadic `26ea591af225ed48129a1968db78b3e8f335dc90`. [provenance.json](provenance.json) records every source path and hash. Only the requested catalog is published; backend implementation and credentials remain outside this repository. No new license is inferred from publication.
