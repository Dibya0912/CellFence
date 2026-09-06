# CellFence package ownership

CellFence is published as focused npm packages. Use the package that matches
the integration point you need:

| Package | Owns |
| --- | --- |
| `cellfence` | Command-line interface and local repository checks |
| `@cellfence/engine` | Core manifest and governance evaluation |
| `@cellfence/schema` | Shared manifest and result schemas |
| `@cellfence/plugin-api` | Public API for writing plugins |
| `@cellfence/github-action` | GitHub Actions integration |
| `@cellfence/mcp-proxy` | MCP proxy integration |
| `@cellfence/trace` | Trace capture and replay utilities |
| `@cellfence/github-action-baseline-gate` | Baseline gate for GitHub Actions |
| `@cellfence/reporter-economy-matrix` | Economy matrix reporting |

Use the package README for installation and API details. Packages with names
starting with `plugin-` provide optional governance checks, while packages
starting with `adapter-` provide integration adapters.
