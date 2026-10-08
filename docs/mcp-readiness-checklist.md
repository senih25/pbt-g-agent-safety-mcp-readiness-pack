# MCP Readiness Checklist

## Ownership and intent

- [ ] A named owner is accountable for the server and its listing.
- [ ] The user problem and supported client environments are stated plainly.
- [ ] The public description does not reveal private architecture or operational details.
- [ ] Every enabled tool has a documented user-facing purpose.

## Configuration hygiene

- [ ] Use distinct development and demonstration configuration; neither contains production credentials.
- [ ] Keep configuration under source control only after secret review.
- [ ] Prefer narrowly scoped variables and documented placeholders over copied credentials.
- [ ] Remove stale, duplicate, or undocumented server entries.
- [ ] Pin or review dependencies according to the team’s release policy.

## Tool surface

- [ ] Start with the smallest useful tool set.
- [ ] Separate read-only discovery from state-changing actions where practical.
- [ ] Identify actions requiring human approval or confirmation.
- [ ] Document expected inputs, outputs, and failure behavior at a high level.
- [ ] Avoid tool descriptions that invite unrestricted file, browser, or shell access.

## Release evidence

- [ ] Test with synthetic data in a clean profile or test workspace.
- [ ] Capture sanitized installation and rollback steps.
- [ ] Check public links, license, privacy, security contact, and support route.
- [ ] Obtain product/brand/legal approval for external claims.

**Result:** Record open items, owner, due date, and safe evidence reference. Do not attach secrets or raw logs.
