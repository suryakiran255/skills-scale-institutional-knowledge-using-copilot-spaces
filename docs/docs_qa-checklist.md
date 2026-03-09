# QA Checklist

Use this checklist for each sprint/release to ensure test coverage and acceptance criteria are met.

Pre-merge / PR
- [ ] Acceptance criteria present in issue and PR
- [ ] Unit tests added for new logic
- [ ] Integration tests for cross-boundary behavior (if applicable)
- [ ] Linting and static analysis pass
- [ ] Test data and environment notes included for reviewers

Pre-release / staging
- [ ] Automated regression suite executed and green
- [ ] Critical path smoke tests passed
- [ ] Manual acceptance testing completed for UI/UX and edge-cases
- [ ] Known issues documented and communicated
- [ ] QA sign-off recorded in release readiness

Post-release
- [ ] Post-deploy verification completed
- [ ] Any production issues triaged and linked to action items
- [ ] Test coverage gaps identified and backlog items created