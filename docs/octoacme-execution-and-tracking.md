# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review (owned by DevOps/Platform Engineer)
  - Require at least one approval before merging — Tech Lead approves architecture-impacting changes; UX/Design Lead approves UI changes
  - Security & Compliance Officer reviews PRs touching authentication, data handling, or third-party integrations

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI (configured and maintained by DevOps/Platform Engineer; findings triaged with Security & Compliance Officer)
- Manual QA for feature acceptance when needed
- UX/Design Lead signs off on visual and interaction quality before marking a feature Done

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage) — DevOps/Platform Engineer owns observability setup

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues
- Security blockers: escalate directly to Security & Compliance Officer, then follow the security incident runbook if needed

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests, lint, and security scanning (DevOps/Platform Engineer)
- [ ] Observability dashboards set up for key signals
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
- [ ] UX/Design Lead included in sprint reviews for user-facing features
