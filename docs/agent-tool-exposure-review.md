# Agent Tool Exposure Review

Use this review before an agent can call browser, terminal, file, network, or administrative tools.

## Per-tool questions

| Question | Review prompt |
|---|---|
| Necessity | What user outcome requires this tool? Can a smaller read-only tool meet it? |
| Scope | Which resources, domains, directories, or environments should be in scope? |
| Impact | Could the action create, change, delete, send, publish, or disclose data? |
| Input | Can untrusted text influence arguments or destinations? |
| Oversight | What requires a user confirmation, preview, or separate approval? |
| Evidence | How will a sanitized result and failure be communicated? |

## Decision checklist

- [ ] Allow only the minimum capability needed for the documented workflow.
- [ ] Define explicit resource boundaries rather than broad machine or account access.
- [ ] Treat browser navigation, terminal commands, uploads, and outbound messages as different risk classes.
- [ ] Use synthetic fixtures for demonstrations and support reproduction.
- [ ] Provide an owner and a disable/rollback path.
- [ ] Re-review the tool surface after material changes, new integrations, or new client environments.

## Escalate for human review

Credentials, private repositories, production accounts, financial actions, legal/compliance claims, destructive actions, data exports, publishing, and third-party account linking require a separate owner decision.
