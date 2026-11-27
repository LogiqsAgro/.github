## Why

<!-- The problem or the goal, in one or two sentences. Link the issue: "Closes #123", or "Refs #123" when the issue stays open. -->

Closes #

## What changed

<!-- The change in short. Name the components. Add screenshots for a change in the user interface. -->

## How I tested it

<!-- Unit tests, an integration test, a test VM, a customer environment. Write "not needed" with the reason when no test applies. -->

## Risk assessment

<!-- Assess the risk from the diff. Name the affected components. Tick one risk box. For a high-risk change, add one line: what breaks when the change is wrong, and how we roll back. When the mark differs from the linked issue, update the issue. -->

Affected systems or components:

- [ ] **Low risk**: one component, easy to revert, no change to authentication, stored data, network exposure or machine control.
- [ ] **High risk**: touches authentication, stored data, network exposure or machine control, or a fault can stop production at a customer.

Impact and rollback (high risk only):

## Checklist before you request a review

- [ ] I did a self-review of the change.
- [ ] The risk mark in this pull request matches the diff and the linked issue.
- [ ] I added or updated the tests, and the build is green.
- [ ] I updated the documentation and the release notes where the change needs it.
