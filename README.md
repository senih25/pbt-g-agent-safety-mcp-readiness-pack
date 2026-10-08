# PBT-G Agent Safety & MCP Readiness Pack

A public-safe set of checklists, setup guidance, and synthetic examples for teams that expose MCP servers and agent tools to browser, terminal, and local-workflow capabilities.

## Who it is for

Developers, maintainers, platform teams, and partner programs preparing an MCP integration, agent extension, repository, or marketplace listing.

## What it checks

- MCP configuration hygiene and least-privilege tool exposure
- Browser and terminal workflow review prompts
- Public-repository secret-risk checks
- IDE/client setup validation for VS Code, Cursor, Claude Desktop, and Copilot-oriented workflows
- Extension, marketplace, and partner-documentation readiness

## What it does not do

This pack is not a security certification, penetration test, compliance opinion, managed monitoring service, or substitute for an organization’s security review. It does not inspect private repositories, collect secrets, or provide a guarantee that a configuration is safe.

## Use concept

1. Copy the relevant checklist into a change or release review.
2. Use the synthetic example to rehearse a safe demonstration.
3. Record findings without secrets or private paths.
4. Resolve high-impact exposure decisions with the owner of the affected system.
5. Publish only material that passes the public-safe boundary in [SECURITY.md](SECURITY.md).

## Public-safe security boundary

Use fictional data. Do not add API keys, access tokens, cookies, private repository URLs, internal policies, customer data, or implementation details to issues, examples, screenshots, or listing submissions.

## Pilots and partners

For a scoped pilot or directory/partner discussion, use the placeholder contact in [SECURITY.md](SECURITY.md) after the repository owner has replaced it with an approved channel.

> This repository contains public guidance only. It does not include PBT-G core source code or guarded-runtime implementation details.
