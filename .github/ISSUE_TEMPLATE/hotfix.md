---
name: Hotfix
about: A high-priority fix that goes to customers before the next release
title: "Hotfix: "
labels: bug
type: Hotfix
---

## Problem

<!-- What is broken, at which customer, since which version? -->

## Fix

<!-- What changes? Link the pull request when it exists. -->

## Rollout

<!-- Which customers get the hotfix, in which order, and who tells them. -->

- [ ]
- [ ]

## After the fix

<!-- A hotfix goes first; the review and the approval follow directly afterwards. Tick these when done. -->

- [ ] Code review done afterwards by another developer.
- [ ] Approval recorded on the pull request.
- [ ] Checked at the customer that the fix works.

## Risk assessment

<!-- Name the affected components. Tick one risk box. For a high-risk change, add one line: what breaks when the fix is wrong, and how we roll back. -->

Affected systems or components:

- [ ] **Low risk**: one component, easy to revert, no change to authentication, stored data, network exposure or machine control.
- [ ] **High risk**: touches authentication, stored data, network exposure or machine control, or a fault can stop production at a customer.

Impact and rollback (high risk only):
