# Public Repository Secret-Risk Checklist

Run this before creating a public repository, issue, release, marketplace listing, demo video, or screenshot.

## Inspect without exposing

- [ ] Review tracked files, documentation, examples, build output, screenshots, and CI configuration.
- [ ] Exclude `.env` files, key/certificate formats, credential stores, browser profiles, cookies, token files, and private configuration from public review artifacts.
- [ ] Replace identifiers, hostnames, account names, and internal paths with fictional placeholders where they are not needed.
- [ ] Confirm examples use obvious non-secret values such as `EXAMPLE_TOKEN_DO_NOT_USE`.

## Source and artifacts

- [ ] Do not copy private source, policy internals, raw logs, or unpublished mechanisms into this pack.
- [ ] Verify generated bundles, archives, and screenshots separately from source files.
- [ ] Check that release attachments and package metadata contain only approved public material.
- [ ] Keep provenance and internal test artifacts outside the public repository unless specifically cleared.

## Publication decision

- [ ] A second reviewer confirms the material is public-safe.
- [ ] The owner approves the license, contact information, claims, and target destination.
- [ ] There is a removal and incident-contact plan if an exposure is discovered.

If a possible secret is found, stop publication, restrict further sharing, rotate or revoke through the owning team’s process, and create a sanitized incident record.
