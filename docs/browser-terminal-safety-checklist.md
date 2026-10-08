# Browser-Terminal Agent Workflow Safety Checklist

## Before enabling a workflow

- [ ] Define the exact user goal and the permitted browser, terminal, file, and network scopes.
- [ ] Prefer observation and preview steps before actions that change state.
- [ ] Separate routine read operations from writes, uploads, sends, publishes, deletions, and account changes.
- [ ] Identify user approvals required for external, destructive, financial, credential, or privacy-impacting actions.

## During a workflow

- [ ] Keep actions tied to the stated task and named target.
- [ ] Display meaningful errors rather than silently broadening scope or continuing after a failed control.
- [ ] Use synthetic or test data for demos and validation.
- [ ] Keep logs and screenshots sanitized and access-controlled.

## After a workflow

- [ ] State what changed, what did not change, and any pending human action.
- [ ] Preserve only minimal, sanitized evidence needed for review.
- [ ] Revoke temporary test access and remove temporary synthetic fixtures when no longer needed.
- [ ] Reassess tool scope after a change in client, integration, target environment, or user role.

This is a planning checklist, not a substitute for system-specific security engineering or access-control design.
