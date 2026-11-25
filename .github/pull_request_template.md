## JIRA ticket

<!-- e.g. https://yourcompany.atlassian.net/browse/PROJ-123 -->

## Summary

<!-- What changed and why, in a few sentences. -->

## Checklist

- [ ] Tests added or updated, and passing locally
- [ ] Linting and type checks pass
- [ ] Docs / README updated if behaviour changed
- [ ] No secrets or credentials committed

## End-to-end tests

<!--
For central-system, api-ocpp, api-gateway and api-gireve: the "E2E declaration" check needs
exactly one of these labels. Remove this section in other repositories.
- `e2e: covered`: link the suite's PR or branch below. A suite branch with the same name as
  this PR's branch is used by the e2e check on this PR, so both can be tested before merging.
- `e2e: not needed`: fill in the `E2E:` line with why (refactor, docs, no behaviour change...).
How to test a change end to end: swish-charge/central-system-end-to-end-testing, docs/testing-changes.md
-->

- **Suite PR or branch:** <!-- https://github.com/swish-charge/central-system-end-to-end-testing/pull/<number> -->

E2E: <!-- why no end-to-end test is needed, with `e2e: not needed`; otherwise delete this line -->

## Handoff

<!--
Context for whoever (human or agent) picks this up next. Terse bullets, state not narrative.
Point to things (paths:lines, SHAs, tickets, error IDs) instead of pasting them.
Delete lines that don't apply; remove the whole section for trivial PRs.
-->

- **As of:** <!-- commit SHA this note describes -->
- **State:** <!-- done / in progress / blocked on ... -->
- **Decisions:** <!-- decision — because reason -->
- **Tried, failed:** <!-- approach → why it didn't work -->
- **Constraints:** <!-- what must not change, compatibility requirements -->
- **Open questions:** <!-- what the next person must decide or ask -->
- **Pointers:** <!-- key files, related PRs, tickets, error IDs -->
- **Verify:** <!-- command that proves the current state, e.g. `pytest tests/test_x.py` -->
