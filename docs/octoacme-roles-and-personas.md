# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Scrum Master

### Role Summary
Facilitates agile ceremonies, removes impediments, and coaches the team on process improvements.

### Responsibilities
- Run standups, sprint planning, sprint reviews, and retrospectives
- Identify and resolve team blockers promptly
- Foster continuous improvement and a healthy team culture
- Shield the team from external distractions during sprints

### Goals
- Maintain a sustainable, predictable delivery cadence
- Reduce lead time and eliminate recurring blockers
- Improve team self-organization and collaboration

### Typical Communication
- Daily standups and ceremony facilitation notes
- Impediment log and resolution updates
- Retrospective action items and follow-ups

### Interactions with Existing Roles
- **Developers**: Day-to-day support; unblocks technical or process impediments.
- **Product Manager**: Helps maintain backlog health and clarifies priorities before planning.
- **Project Manager**: Coordinates on schedule risks, dependencies, and escalation; complements (not duplicates) PM activities.
- *Lifecycle fit*: Active throughout **Planning → Execution**; drives retrospectives at the close of each sprint or milestone.

---

## UX Designer

### Role Summary
Designs user flows, wireframes, and prototypes to ensure the product meets usability standards and user needs.

### Responsibilities
- Plan and conduct user research, interviews, and usability tests
- Deliver wireframes, prototypes, and design specifications
- Collaborate with Product Managers on requirements and acceptance criteria
- Partner with Developers to ensure faithful implementation
- Participate in design reviews and provide sign-off on UI changes

### Goals
- Deliver intuitive, accessible user experiences
- Reduce rework caused by late-stage usability issues
- Create and maintain a shared design system or pattern library

### Typical Communication
- Design reviews and handoff documentation (e.g., Figma links in PRs)
- Usability test reports and research summaries
- Sprint review demos focused on UX quality

### Interactions with Existing Roles
- **Product Manager**: Translates product requirements into user flows and validates designs against success metrics.
- **Developers**: Provides design specs; reviews implementations for fidelity; flags issues before release.
- **Project Manager**: Flags UX-related risks or scope changes that could affect timelines.
- *Lifecycle fit*: Engaged from **Initiation** (early research) through **Execution** (design/build cycles) and **Release** (UX sign-off).

---

## Security Lead

### Role Summary
Oversees security practices throughout the software development lifecycle (SDLC), ensuring the product is built and shipped securely.

### Responsibilities
- Conduct security risk assessments and recommend mitigations
- Review code, architecture, and deployments for vulnerabilities
- Enforce compliance with internal and external security standards
- Define and maintain the security incident runbook
- Approve security-sensitive releases as part of the go/no-go process

### Goals
- Prevent security vulnerabilities from reaching production
- Ensure rapid containment and resolution of security incidents
- Build a security-aware engineering culture

### Typical Communication
- Security review findings and remediation tracking
- Threat model documents for significant features
- Incident reports and post-mortems

### Interactions with Existing Roles
- **Developers**: Reviews code and provides remediation guidance; advises on secure coding practices.
- **Project Manager**: Escalation point for security risks that affect timelines or scope.
- **Release Manager**: Required sign-off on go/no-go decisions; validates that security scans have passed.
- *Lifecycle fit*: Consulted during **Planning** (threat modelling), active in **Execution** (security scans, code review), and a gate at **Release**.

---

## Stakeholder Champion

### Role Summary
Represents stakeholder interests in ongoing project discussions and major decisions, ensuring their feedback is heard and addressed.

### Responsibilities
- Gather, synthesize, and communicate feedback from relevant stakeholders
- Track open stakeholder concerns and follow up on resolutions
- Coordinate stakeholder review sessions and sign-offs
- Escalate unresolved stakeholder blockers to the Project or Product Manager

### Goals
- Ensure no key stakeholder perspective is missed
- Reduce last-minute change requests by involving stakeholders early
- Maintain trust and transparency with external or senior stakeholders

### Typical Communication
- Stakeholder meeting notes and action items
- Summary updates embedded in weekly status reports
- Escalation notes when concerns are unresolved

### Interactions with Existing Roles
- **Product Manager**: Provides stakeholder input that shapes prioritization decisions.
- **Project Manager**: Coordinates on the stakeholder communication plan; joint owner of stakeholder list.
- **Developers**: Bridges stakeholder feedback to technical requirements when needed.
- *Lifecycle fit*: Introduced at **Initiation** (stakeholder mapping), active through **Execution** (feedback loops), and critical at **Release** (stakeholder acceptance).

---

## Release Manager

### Role Summary
Coordinates the scheduling, communication, and execution of software releases to ensure predictable and low-risk deployments.

### Responsibilities
- Maintain the release calendar and deployment checklists
- Facilitate go/no-go decisions with required approvers (PM, QA, Security Lead)
- Communicate release timelines and outcomes to the team and stakeholders
- Own the release notes process and ensure they are accurate before publication
- Coordinate rollback decisions and post-release incident triage

### Goals
- Achieve zero-surprise releases with clear communication
- Reduce time-to-recovery when release issues occur
- Maintain an auditable release history

### Typical Communication
- Release readiness reports and go/no-go meeting outcomes
- Release notes distributed to stakeholders and support
- Post-release retrospective notes

### Interactions with Existing Roles
- **Project Manager**: Aligns release schedule with overall project milestones and stakeholder commitments.
- **Developers**: Confirms all PRs are merged, CI is green, and deployment steps are documented.
- **Security Lead**: Validates security scan results before approving release.
- **Stakeholder Champion**: Coordinates stakeholder communication and acceptance ahead of release.
- *Lifecycle fit*: Engaged during **Planning** (release calendar), leads **Release & Deployment**, and contributes to **Retrospectives**.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

