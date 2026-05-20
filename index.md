# Android CLI Agent Gate

Android CLI Agent Gate is a hosted remote MCP for Android CLI agent build gate.

This repository is a public documentation project for Android CLI Agent Gate. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://androidcliagentgate.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=androidcliagentgate_public_docs&utm_content=readme_home
- Pricing: https://androidcliagentgate.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=androidcliagentgate_public_docs&utm_content=readme_pricing
- Checkout: https://androidcliagentgate.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=androidcliagentgate_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://androidcliagentgate.clauxel.com/mcp
- Server card: https://androidcliagentgate.clauxel.com/server-card.json
- Registry name: `com.clauxel.androidcliagentgate/androidcliagentgate-mcp`
- Tools: `check_android_cli_build`, `suggest_android_fix`, `explain_permission_blocker`, `issue_build_gate_receipt`, `export_mobile_agent_log`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Security model](features/security-model.md)
6. [Public link reference](reference/links.md)

## Audience

developer platform teams, release owners, AI engineering leads, and delivery reviewers.

## Capabilities

- Streamable HTTP MCP endpoint
- Bearer-token access for production calls
- Structured tool-call output
- Receipt-oriented evidence export
- Public server card and registry metadata
- MCP tool: check_android_cli_build
- MCP tool: suggest_android_fix
- MCP tool: explain_permission_blocker
- MCP tool: issue_build_gate_receipt
- MCP tool: export_mobile_agent_log

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
