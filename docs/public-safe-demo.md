# Public-Safe Demo Scenario

## Scenario

A developer maintains several MCP server entries for a fictional project named **Sample Inventory Lab**. They want to prepare a public listing without sharing production configuration.

## Demo flow

1. Show a synthetic configuration with three clearly labeled servers: read-only documentation search, fixture-file lookup, and a disabled example of a state-changing tool.
2. Use the MCP readiness checklist to identify an overbroad description and an unnecessary tool category.
3. Use the tool-exposure review to classify the fixture lookup as read-only and the disabled action as approval-required.
4. Use the secret-risk checklist to confirm that placeholders replace tokens, internal paths, and account names.
5. Show the partner-pitch summary and explain that the resulting artifacts are documentation and review prompts, not a security certification.

## Safety rules

Use only the files in `demo/` and `examples/`. Do not open production profiles, private repositories, real accounts, or live secrets. Do not send messages, publish listings, or execute destructive commands.

## Expected outcome

The viewer sees a repeatable review process that narrows an agent’s exposed tool surface and produces marketplace-safe documentation using fictional data.
