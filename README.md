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

1. Read the relevant checklist as a reference for your own change or release review. Reproduction or adaptation requires the owner's permission until an approved license is published.
2. Use the synthetic example to rehearse a safe demonstration.
3. Record findings without secrets or private paths.
4. Resolve high-impact exposure decisions with the owner of the affected system.
5. Publish only material that passes the public-safe boundary in [SECURITY.md](SECURITY.md).

## Availability and permissions

This repository is publicly visible **for review only**. It is **not currently licensed as open source**. Public visibility does not grant permission to copy, modify, redistribute, or use its contents beyond evaluation; see [LICENSE.md](LICENSE.md). Permission for template reuse or redistribution requires an owner-approved license or separate authorization. This documentation pack does not include or license the private PBT-G implementation.

## Public-safe security boundary

Use fictional data. Do not add API keys, access tokens, cookies, private repository URLs, internal policies, customer data, or implementation details to issues, examples, screenshots, or listing submissions.

## Pilots and partners

For a scoped pilot or directory/partner discussion, contact the repository owner using the review channel described in [SECURITY.md](SECURITY.md).

> This repository contains public guidance only. It does not include PBT-G core source code or guarded-runtime implementation details.
