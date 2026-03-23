# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

**Risk register is maintained by the Project Manager.** Contributors:
- **Security Lead**: owns security-related risks; must review and update security risk entries at least every sprint.
- **Scrum Master**: flags process or team-health risks during retrospectives.
- **Release Manager**: flags deployment and release risks.
- All team members are encouraged to raise new risks at any time.

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level -> Scrum Master -> PM -> Product Lead -> Sponsor
- For security incidents: **Security Lead** is notified immediately → follows the security incident runbook → escalates to PM and Sponsor if business impact is confirmed → post-incident review conducted by Security Lead and Project Manager
