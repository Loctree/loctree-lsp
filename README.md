# Loctree LSP 0.15.1

This repository is the public home of the Loctree language server.

The language server brings Loctree structural intelligence into editor integrations. Issues and pull requests are welcome here.

## Build

```bash
cargo check --workspace
```

## License

BUSL-1.1. See `LICENSE` and `NOTICE.md`.

## Snapshot Notes

- Target repo: `Loctree/loctree-lsp`
- Dependency mode: `crates.io registry`
- Engine crates (loctree, loctree-ast, report-leptos) are consumed from crates.io at the pinned release version; no vendored sources in this mirror.
