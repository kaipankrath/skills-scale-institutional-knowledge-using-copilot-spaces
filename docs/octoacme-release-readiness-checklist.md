# OctoAcme — Release Readiness Checklist

## Purpose
Provide a comprehensive, role-aligned checklist to confirm that a release is ready to proceed to production.

---

## How to Use
1. Open this checklist for each release candidate.
2. Each owner completes and signs off on their section.
3. The Release Manager collates all sign-offs before calling the go/no-go meeting.
4. A release does **not** proceed until all **Required** items are checked.

---

## 1. Product & Scope (Owner: Product Manager)
- [ ] All acceptance criteria for in-scope items are met
- [ ] Out-of-scope items are deferred and tracked as follow-up issues
- [ ] Product Manager has reviewed and approved the release scope

## 2. Engineering & Quality (Owner: Developers / Tech Lead)
- [ ] All feature branches merged to the release branch
- [ ] CI pipeline is green (build, unit tests, integration tests)
- [ ] No unresolved critical or high-severity bugs in scope
- [ ] Smoke tests documented and ready to run
- [ ] Smoke tests passing in staging environment
- [ ] Feature flags configured correctly for this release

## 3. UX Sign-off (Owner: UX Designer)
- [ ] All user-facing changes reviewed against design specifications
- [ ] Accessibility checks completed for new UI components
- [ ] UX Designer has approved visual and interaction quality

## 4. Security Sign-off (Owner: Security Lead)
- [ ] Security scans (SAST/DAST/dependency) have run and passed, or findings are documented with accepted risk
- [ ] No unresolved high or critical security findings blocking release
- [ ] Secrets and credentials are not hardcoded; secret rotation completed if needed
- [ ] Security Lead has signed off on the release

## 5. Release Artifacts (Owner: Release Manager)
- [ ] Release notes drafted, reviewed, and approved by Product Manager
- [ ] Release version / tag created in source control
- [ ] Deployment runbook is up-to-date and accessible
- [ ] Rollback / mitigation plan documented
- [ ] Stakeholders notified of release window and expected outcomes

## 6. Infrastructure & Operations (Owner: Developers / DevOps)
- [ ] Deployment window scheduled (if required)
- [ ] Backup or snapshot taken (if applicable)
- [ ] Monitoring and alerting configured for new features
- [ ] Support team briefed on new features and known issues

## 7. Stakeholder Acceptance (Owner: Stakeholder Champion)
- [ ] Key stakeholders have reviewed and accepted the release scope
- [ ] Outstanding stakeholder concerns are resolved or deferred with agreement
- [ ] Communication plan for the release announcement is ready

---

## Go / No-Go Sign-offs

| Role | Approved? | Name | Date |
|---|:---:|---|---|
| Product Manager | ☐ | | |
| Project Manager | ☐ | | |
| Security Lead | ☐ | | |
| Release Manager | ☐ | | |

> **Go** = all Required items checked and all sign-offs obtained.
> **No-Go** = document the blocking reason and set a resolution target date.

---

## Post-Release Verification
- [ ] Deployment completed without errors
- [ ] Post-deploy smoke tests passed in production
- [ ] Key metrics and dashboards checked (errors, latency, usage)
- [ ] Release announcement sent to stakeholders and support team
- [ ] Any post-release incidents captured in the incident log

---

*For role definitions, see [`octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md).*

*For the deployment checklist, see [`octoacme-release-and-deployment.md`](octoacme-release-and-deployment.md).*
