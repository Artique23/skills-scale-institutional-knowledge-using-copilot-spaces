# Release Manager Checklist

This checklist guides the Release Manager through pre-release preparation, deployment execution, and post-release verification to ensure a smooth and reliable release process.

---

## Pre-Release Checks

- [ ] **CI/CD Status**: Verify all CI builds are green for the release candidate
- [ ] **Security Scan**: Confirm security scanning (e.g., CodeQL, dependency checks) passed with no critical issues
- [ ] **Smoke Tests**: Run smoke tests on staging environment to validate critical paths
- [ ] **Release Notes**: Review and finalize release notes (features, bug fixes, known issues)
- [ ] **Rollback Plan**: Document and validate rollback procedure if deployment fails
- [ ] **Dependencies**: Confirm all external dependencies and integrations are compatible
- [ ] **Database Migrations**: Review migration scripts and ensure reversibility if needed
- [ ] **Feature Flags**: Verify feature flags are configured correctly for gradual rollout
- [ ] **Stakeholder Notification**: Send pre-deployment notice to stakeholders with deployment window

---

## Deployment Steps

- [ ] **Deployment Window**: Confirm maintenance window with stakeholders if applicable
- [ ] **Backup**: Take production backup (database, configurations) before deployment
- [ ] **Deploy to Production**: Execute deployment following the release runbook
- [ ] **Monitor Deployment**: Watch deployment logs and metrics for errors or anomalies
- [ ] **Deployment Verification**: Run automated deployment verification tests
- [ ] **Feature Flag Activation**: Enable new features via feature flags as planned

---

## Post-Release Verification

- [ ] **Smoke Tests (Production)**: Run critical smoke tests on production environment
- [ ] **Health Checks**: Verify all service health endpoints are responding correctly
- [ ] **Performance Monitoring**: Check dashboards for latency, error rates, and resource usage
- [ ] **User Validation**: Confirm key user flows are working as expected
- [ ] **Error Logs**: Review error logs for any unexpected issues
- [ ] **Rollback Decision**: If critical issues detected, execute rollback plan immediately

---

## Communication Steps

- [ ] **Release Announcement**: Notify stakeholders, customers, and support team of successful deployment
- [ ] **Documentation Update**: Update user-facing documentation and changelog
- [ ] **Support Team Briefing**: Brief support team on new features, changes, and known issues
- [ ] **Internal Announcement**: Share release summary with internal teams (Slack, email)
- [ ] **Post-Release Report**: Document deployment timeline, issues encountered, and resolutions

---

## Post-Release Monitoring (24-48 hours)

- [ ] **Metrics Tracking**: Monitor key success metrics defined in release goals
- [ ] **User Feedback**: Collect and triage user feedback and support tickets
- [ ] **Incident Response**: Address any production incidents with appropriate urgency
- [ ] **Follow-up Tasks**: Create tickets for any hotfixes or follow-up improvements identified

---

## Handoff

- [ ] **On-call Engineer**: Brief on-call/support engineer on the release and potential issues
- [ ] **Product Manager**: Share release metrics and initial user feedback with PM
- [ ] **Team Retrospective**: Schedule post-release retrospective to capture learnings
