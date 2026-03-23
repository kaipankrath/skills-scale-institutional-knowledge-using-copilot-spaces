# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily stand-ups (15 min) — **facilitated by Scrum Master** — focus on progress, blockers, dependencies
- Weekly delivery sync — **facilitated by Project Manager** — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone — **facilitated by Scrum Master** with Product Manager as audience lead

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup — **Scrum Master** owns resolution tracking
- Level 2: PM escalates to Product Lead and dependent teams — **Project Manager** owns escalation
- Level 3: Sponsor-level escalation for business-impacting issues — **Project Manager + Stakeholder Champion**

## Feedback Loops
- **QA**: QA findings are logged as issues and triaged in the next standup; Scrum Master tracks closure.
- **UX**: UX Designer reviews implementations before sprint review; feedback captured in PRs or design notes.
- **Security**: Security scanning results reviewed by Security Lead; critical findings block the release and are escalated to Project Manager immediately.

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
