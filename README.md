# National Health Authority agent plugins

Agent plugins from the National Health Authority for building on India's digital health networks: ABDM integration skills and the NHCX claims integration, each with its documentation MCP server.

## Install

Claude Code:

```bash
claude plugin marketplace add nha-in/agent-plugins
claude plugin install abdm-integrators-assistant@nha
claude plugin install nhcx@nha
```

Codex:

```bash
codex plugin marketplace add nha-in/agent-plugins
```

Then install a plugin from Codex's plugin directory.

## Plugins

| Plugin | Version | What it is for |
| --- | --- | --- |
| `abdm-integrators-assistant` | 0.5.0 | Build and debug an ABDM integration. |
| `nhcx` | 1.0.0 | Build the provider side of an NHCX claims integration into a hospital information system. |

Documentation: https://docs.abdm.gov.in

This repository is generated from the ABDM Developer Portal and published as it is. Changes made here are overwritten on the next publish; report issues through the portal.
