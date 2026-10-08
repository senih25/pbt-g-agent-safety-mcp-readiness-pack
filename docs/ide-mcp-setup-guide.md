# IDE and Desktop MCP Setup Validation Guide

This guide validates configuration shape and tool boundaries; it does not require a production server or real credentials.

## Common preparation

1. Work in a disposable test workspace with synthetic files.
2. Keep the server definition minimal and use placeholder environment values only.
3. Name the server clearly and document its intended tool categories.
4. Start with a harmless read-only test such as listing a synthetic fixture.
5. Confirm failures are visible and do not silently fall back to broader access.

## VS Code and Copilot-oriented workflows

- Confirm the MCP configuration is in the intended workspace or user scope.
- Ensure tool descriptions distinguish read-only from state-changing behavior.
- Test that a synthetic prompt cannot redirect the workflow to unrelated files or accounts.
- Record the client version and sanitized setup steps for support.

## Cursor

- Use an isolated project and clearly label the test server.
- Review the enabled tool list before invoking it.
- Validate only synthetic, reversible interactions.

## Claude Desktop

- Use a separate test configuration and placeholder values.
- Confirm the server starts and reports errors without emitting sensitive data.
- Verify the tool inventory matches the documented minimum surface.

## Completion record

Capture client, date, config owner, tested synthetic scenario, enabled tool categories, result, and follow-up actions. Do not paste configuration values that contain sensitive information.
