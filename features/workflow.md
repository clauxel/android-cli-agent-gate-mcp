# Workflow

Android CLI Agent Gate is a hosted remote MCP for Android CLI agent build gate.

## Repeatable Flow

1. Open Android CLI Agent Gate and select the buyer plan.
2. Create or request a bearer token from the hosted product.
3. Add https://androidcliagentgate.clauxel.com/mcp to a compatible MCP client.
4. Run tools/list, then call check_android_cli_build with public-safe sample data.
5. Save the returned receipt or export for human review.

## Output Mindset

The useful artifact is not a marketing claim. It is evidence that a reviewer can inspect, export, and compare later.
