# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner _(assign to the role most accountable — see `octoacme-roles-and-personas.md`)_
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution — all roles contribute; PM consolidates
- Assess: estimate impact and likelihood — Tech Lead assesses technical risks; Security & Compliance Officer assesses security/compliance risks
- Mitigate: reduced via actions and contingency plans — DevOps/Platform Engineer owns infrastructure mitigations
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Customer Success/Support Representative coordinates external customer-facing communications
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

## Communication Templates

### Weekly Status Template
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

### Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- Technical blockers: Team-level -> Tech Lead -> PM -> Product Lead
- Security incidents: Immediately notify Security & Compliance Officer; follow the security incident runbook and notify Security on-call
- Customer-impacting issues: PM + Customer Success/Support Rep coordinate external communication concurrently with technical triage
