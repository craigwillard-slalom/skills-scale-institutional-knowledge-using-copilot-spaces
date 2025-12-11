# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — facilitated by Scrum Master, focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks (includes PM, Scrum Master, Product Manager)
- UX design reviews — bi-weekly or as needed to validate design implementation
- Data review sessions — review metrics and insights with Data Analyst
- Demo/Review at the end of each sprint or milestone (all roles invited)

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
- Security scanning in CI (monitored by Deployment Engineer)
- UX Designer validates design implementation and usability
- Business Analyst coordinates User Acceptance Testing (UAT)
- Manual QA for feature acceptance when needed
- Data Analyst verifies tracking and metrics instrumentation

## Reporting & Metrics
- Scrum Master tracks velocity and burndown
- Data Analyst monitors success metrics identified in the Project One-pager
- Data Analyst maintains dashboards for key signals (errors, latency, usage)
- Support Lead tracks customer-reported issues and escalations

## Blocker Escalation
- Level 1: Team-level triage in daily standup (facilitated by Scrum Master)
- Level 2: PM and Scrum Master escalate to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues
- Technical blockers: Deployment Engineer assists with infrastructure/environment issues
- Customer impact: Support Lead coordinates urgent customer communications

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint (Deployment Engineer)
- [ ] Scrum Master facilitating daily standups and sprint ceremonies
- [ ] UX Designer reviewing design implementation regularly
- [ ] Business Analyst coordinating UAT activities
- [ ] Data Analyst tracking success metrics and providing insights
- [ ] Regular demos scheduled (all roles invited)
- [ ] Risk register updated weekly (PM with input from all roles)
- [ ] Support Lead monitoring customer feedback and issues
