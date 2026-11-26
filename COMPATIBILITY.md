# Dyadic Compatibility

[Plugins](README.md) · [Agent import limits](https://github.com/HiLleywyn/dyadic-agents/blob/main/COMPATIBILITY.md)

The 40 folders are descriptors for tools that already exist in the Dyadic server. Each `plugin.json` maps to a built-in tool switch; Dyadic's Store loads its own copy from `catalog/plugins/` at startup.

- **Not installable code.** Dyadic's package importer accepts skills and agents. It cannot install a provider backend or executable plugin from these manifests, and the built archives are distribution bundles only.
- **No catalog sync.** A push here does not change Dyadic's Store, enable a plugin or update installed account copies. Runtime changes start in the Dyadic repository.
- **Availability is per account.** A plugin's tools still depend on its account switch, any provider or connector setup, and the platform's approval and billing policy.

`tools/verify_dyadic.py` in [dyadic-agents](https://github.com/HiLleywyn/dyadic-agents) can compare these descriptors with the switches a Dyadic checkout surfaces.
