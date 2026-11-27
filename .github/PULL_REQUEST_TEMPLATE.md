## Why

<!-- The problem or the goal, in one or two sentences. Link the issue: "Closes #123", or "Refs #123" when the issue stays open. -->

Closes #

## What changed

<!-- The change in short. Name the components. Add screenshots for a change in the user interface. -->

## How I tested it

<!-- Unit tests, an integration test, a test VM, a customer environment. Write "not needed" with the reason when no test applies. -->

## Risk assessment

<!-- Use one of the two options. Option 1: tick the box when the Risk assessment of the linked issue is filled in and matches the diff. Option 2: assess the risk here from the diff. Name the affected components. Tick one risk box. For a high-risk change, add one line: what breaks when the change is wrong, and how we roll back. When the mark differs from the linked issue, update the issue. -->

- [ ] The linked issue has its "Risk assessment" section filled in.

Or assess the risk here:

Affected systems or components:

- [ ] **Low risk**: one component, easy to revert, no change to authentication, stored data, network exposure or machine control.
- [ ] **High risk**: touches authentication, stored data, network exposure or machine control, or a fault can stop production at a customer.

Impact and rollback (high risk only):

## Checklist before you request a review

- [ ] I did a self-review of the change.
- [ ] The risk assessment, in this pull request or on the linked issue, matches the diff.
- [ ] I added or updated the tests, and the build is green.
- [ ] I updated the documentation and the release notes where the change needs it.
