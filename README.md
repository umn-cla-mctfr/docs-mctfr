# docs-mctfr

Central documentation hub for MCTFR research data and supported applications.

## Workspace Context

This repository owns curated, cross-repository documentation and is checked out at
`repos/docs-mctfr` in
[`mctfr-app-stack`](https://github.com/umn-cla-mctfr/mctfr-app-stack). Its source
repositories are sibling checkouts under `repos/`; see
[`docs/source-integration.md`](docs/source-integration.md) for ownership and provenance
guidance. The documentation site can also be developed from a standalone clone.

## Local development

```bash
pip install mkdocs mkdocs-material
mkdocs serve
```

## Build

```bash
mkdocs build
```
