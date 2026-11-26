# Dyadic Plugins

[Skills](https://git.lley.cat/r/1a151e58-468a-45f1-a028-92c95690ad68?ref=main) · [Agents](https://git.lley.cat/r/dadd28be-7d91-432f-beb0-00d285e8f02b?ref=main) · [Plugins](https://git.lley.cat/r/ae86ea71-cb4d-4fc5-9ec1-803f8f303989?ref=main)

Dyadic’s 40 default plugin descriptors, organized under [dyadic/](dyadic/README.md). Every folder has the original `plugin.json`, a readable capability/permission description and navigation back to the collection.

These plugins expose tools implemented by the Dyadic server. A descriptor identifies a Store item and its tool switch; it is not a self-contained executable plugin, MCP server or skill. Account On switches, provider configuration, connected services and execution approvals still determine availability.

## Browse and maintain

- [Default plugin catalog](dyadic/README.md)
- [Machine-readable catalog](catalog.json)
- [Compatibility and blockers](COMPATIBILITY.md)
- [Maintenance and validation](MAINTENANCE.md)
- [Repository delivery report](https://git.lley.cat/r/dadd28be-7d91-432f-beb0-00d285e8f02b?path=REPORT.md&ref=main)

```text
python tools/catalog.py check
python .lley/run.py
python tools/catalog.py build
```

Python 3.11+ and PyYAML are required by the shared collection tooling. Builds make deterministic descriptor archives and checksums for distribution. They are not accepted as executable plugins by Dyadic’s skill/agent importer.

Official definitions are copied without content changes from Dyadic `26ea591af225ed48129a1968db78b3e8f335dc90`. [provenance.json](provenance.json) records every source path and hash. Only the requested catalog is published; backend implementation and credentials remain outside this repository. Project-authored material is licensed under MIT; bundled third-party notices remain in force.

## Source, mirrors and licensing

The [HiLleywyn/dyadic-plugins](https://github.com/HiLleywyn/dyadic-plugins) GitHub repository is canonical. [lley.cat](https://git.lley.cat/r/ae86ea71-cb4d-4fc5-9ec1-803f8f303989) is its synchronized mirror. Project-authored descriptors, documentation and tooling use [MIT](LICENSE), with upstream attribution retained where applicable.

## Capability descriptors, not a second runtime

Each `plugin.json` identifies the built-in capability exposed through Dyadic's tool registry. Its companion README explains what that capability does, the relevant account/tool switches and what configuration it requires. These descriptors help a developer inspect or maintain the catalog; they do not contain the backend implementation, a provider credential or an executable MCP service.

A plugin appearing in the catalog is distinct from its being enabled, configured, authorized and successfully executed. Connected services remain owned by the account that connected them. Network access, execution, external actions and provider spending retain the platform's actual policy and billing boundaries. An imported descriptor cannot bypass those checks.

## Inspect and reproduce

```sh
git clone https://github.com/HiLleywyn/dyadic-plugins.git
cd dyadic-plugins
python -m pip install PyYAML
python tools/catalog.py check
python .lley/run.py
python tools/catalog.py build
```

Use the [human directory](dyadic/README.md) for capability descriptions and [catalog.json](catalog.json) for a machine-readable inventory. [provenance.json](provenance.json) binds mirrored definitions to their source snapshot. The shared validator checks metadata, links and source integrity; the builder makes deterministic descriptor archives and checksums without starting services or executing tools.

For a runtime capability change, update the authoritative Dyadic tool/manifest owner and its contracts, then refresh this descriptor snapshot from the reviewed revision. Changing a README here cannot add a tool to the server. [Compatibility](COMPATIBILITY.md) records importer boundaries; [maintenance](MAINTENANCE.md) describes the verification and packaging sequence.

## Developing against Dyadic

Use [Dyadic Developers](https://dyadic.app/developers/) for actual API schemas, SDKs and integration guides. [Skills](https://github.com/HiLleywyn/dyadic-skills) supply reusable procedures; [agents](https://github.com/HiLleywyn/dyadic-agents) supply identities and delegated roles. [Matrix](https://dyadic.app/developers/matrix/) supplies durable orchestration, with [the engine source](https://github.com/HiLleywyn/dyadic-matrix) available for inspection. `lley.cat` is a synchronized mirror of this repository, and both GitHub Actions and `lley.cat` Actions validate pushes.
