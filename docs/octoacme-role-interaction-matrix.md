# OctoAcme — Role Interaction Matrix

## Purpose
Provide a lightweight RACI-style reference showing which roles are **R**esponsible, **A**ccountable, **C**onsulted, or **I**nformed for key project activities.

> **Legend:** R = Responsible (does the work) · A = Accountable (owns the outcome) · C = Consulted (input required) · I = Informed (kept in the loop)

---

## Matrix

| Activity | Developer | Product Manager | Project Manager | Scrum Master | UX Designer | Security Lead | Stakeholder Champion | Release Manager |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Initiation** | | | | | | | | |
| Define problem statement & success metrics | C | A/R | C | | | | C | |
| Build stakeholder list & communication plan | | C | A/R | | | | R | |
| Initial risk identification | C | C | A/R | | | C | | |
| **Planning** | | | | | | | | |
| Backlog creation & prioritization | C | A/R | C | C | C | | | |
| Estimation facilitation | R | C | C | A/R | | | | |
| Definition of Done | R | A | C | R | C | C | | |
| Release calendar / milestone map | | C | C | | | | | A/R |
| UX review of user-facing stories | C | C | | | A/R | | | |
| Security review of sensitive features | C | | C | | | A/R | | |
| **Execution & Tracking** | | | | | | | | |
| Daily standup facilitation | I | I | I | A/R | I | I | | |
| Weekly delivery sync facilitation | I | C | A/R | C | I | I | I | |
| Blocker triage & resolution | R | C | C | A/R | | | | |
| QA feedback loop | A/R | C | I | C | C | | | |
| UX implementation review | | C | I | | A/R | | | |
| Security scan review | | | I | | | A/R | | |
| Risk register updates | | | A/R | C | | C (security risks) | | C (release risks) |
| **Release & Deployment** | | | | | | | | |
| Release readiness assessment | C | C | C | | | C | | A/R |
| Go/no-go decision | | C | A | | | C | C | R |
| Release notes | | C | | | | | | A/R |
| Deployment execution | A/R | | I | | | | | C |
| Post-deploy verification | A/R | | I | | | I | | C |
| Stakeholder release announcement | | C | C | | | | R | C |
| Incident triage & rollback | A/R | I | C | | | C | I | A/R |
| **Retrospectives** | | | | | | | | |
| Retrospective facilitation | | | | A/R | | | | |
| Action item tracking | C | C | C | A/R | | | | |
| Process risk escalation | | | C | A/R | | | | |

---

## Notes
- This matrix is a guide, not a rigid contract. Adjust per project size and team structure.
- Where two roles share A/R, they collaborate closely with one designated as the primary contact.
- For a full role description, see [`octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md).
