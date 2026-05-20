# Evaluation Guide

Use this page to evaluate whether Android CLI Agent Gate fits a real workflow.

## What To Test

- Android CLI agent build gate
- Android CLI Agent Gate
- Android CLI Agent Gate documentation
- Android CLI Agent Gate remote MCP
- androidcliagentgate server card

## Expected Evidence

- Open Android CLI Agent Gate and select the buyer plan.
- Create or request a bearer token from the hosted product.
- Add https://androidcliagentgate.clauxel.com/mcp to a compatible MCP client.
- Run tools/list, then call check_android_cli_build with public-safe sample data.
- Save the returned receipt or export for human review.

## Risk Checks

- Do not put API keys, tokens, payment details, private logs, or customer records in public issues.
- Use public-safe sample data for examples and directory submissions.
- Treat generated receipts and scores as reviewer evidence, not as a substitute for accountable human approval.
- Validate release or migration gates against a staging workflow before production rollout.

## Buyer Path

Default plan: team.

- https://androidcliagentgate.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=androidcliagentgate_public_docs&utm_content=evaluation_checkout
