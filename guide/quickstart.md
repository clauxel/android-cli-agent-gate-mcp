# Quickstart

Android CLI Agent Gate is a hosted remote MCP for Android CLI agent build gate.

## Fast Path

1. Open Android CLI Agent Gate and select the buyer plan.
2. Create or request a bearer token from the hosted product.
3. Add https://androidcliagentgate.clauxel.com/mcp to a compatible MCP client.
4. Run tools/list, then call check_android_cli_build with public-safe sample data.
5. Save the returned receipt or export for human review.

## Useful Links

- https://androidcliagentgate.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=androidcliagentgate_public_docs&utm_content=quickstart_home
- https://androidcliagentgate.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=androidcliagentgate_public_docs&utm_content=quickstart_pricing
- https://androidcliagentgate.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=androidcliagentgate_public_docs&utm_content=quickstart_checkout

## MCP Endpoint

```text
https://androidcliagentgate.clauxel.com/mcp
```

Use bearer-token authentication for production calls. Keep the token in the MCP client's secret mechanism.
