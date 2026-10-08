# Demo Script

## Goal

Demonstrate the public-safe value of the readiness pack without exposing real credentials, private repositories, customer data, internal paths, or PBT-G core internals.

## Narrative

A developer team is preparing to publish an MCP-enabled AI agent integration. The integration exposes browser, terminal, file, and workflow tools. Before publishing, they use this pack to review whether the setup is safe enough for a public demo or marketplace listing.

## Demo flow

1. Open the synthetic configuration file.
2. Identify broad tool exposure.
3. Check whether terminal/browser actions have clear user approval boundaries.
4. Review secret-risk fields and public screenshot rules.
5. Convert findings into a public-safe marketplace description.
6. End with an approval gate: publish only after owner review.

## Talk track

"This pack does not inspect private systems. It gives teams a structured way to review MCP and agent exposure before they publish. The output is a safer launch checklist, not a security guarantee."

## Success criteria

- no real secrets shown
- no private repo opened
- no real customer data used
- risky items are described as classes, not values
- output is safe to attach to a partner email
