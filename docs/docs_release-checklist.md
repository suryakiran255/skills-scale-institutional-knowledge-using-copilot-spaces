# Release & Deployment Checklist

Use this checklist for every release. Release Engineer and PM coordinate completion.

Pre-release
- [ ] All acceptance criteria met and PRs merged
- [ ] CI pipeline green for all required checks
- [ ] Security scans completed
- [ ] Release notes drafted and reviewed
- [ ] Rollback / mitigation plan documented and validated
- [ ] Stakeholders notified of release scope and timing

Deployment
- [ ] Deployment window scheduled (if applicable)
- [ ] Backup or snapshot created (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production via automated pipeline
- [ ] Monitor post-deploy metrics and logs

Post-release
- [ ] Verify production health and user flows
- [ ] Announce release to stakeholders and support
- [ ] Create follow-up items for any remaining issues