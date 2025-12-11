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

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- PM coordinates with Support Lead for customer-facing communications
- Business Analyst facilitates requirements clarification with business stakeholders
- Data Analyst provides metrics and insights to leadership
- UX Designer shares research findings and design decisions with relevant stakeholders
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:
- Key metrics and insights (from Data Analyst)

Incident Communication (coordinated by Support Lead and Deployment Engineer):
- Triage summary
- Customer impact assessment
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled (facilitated by Scrum Master)

## Escalation Paths
- Team-level (Scrum Master facilitates) -> PM -> Product Lead -> Sponsor
- Technical/Infrastructure issues: Deployment Engineer coordinates with platform teams
- Customer escalations: Support Lead -> Product Manager -> Executive sponsor
- Requirements conflicts: Business Analyst facilitates with PM and Product Manager
- For security incidents, follow the security incident runbook and notify Security on-call (Deployment Engineer coordinates)
