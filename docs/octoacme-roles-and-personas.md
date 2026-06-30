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

## UX / Design Lead

### Role Summary
The UX/Design Lead owns the end-to-end user experience, from early-stage research and wireframing through final design handoff. They ensure that features are usable, accessible, and aligned with customer needs.

### Responsibilities
- Conduct user research and translate findings into design requirements
- Create wireframes, prototypes, and final UI specifications
- Maintain the design system and accessibility standards
- Participate in planning to surface UX requirements early
- Review implemented features against approved designs before QA sign-off

### Goals
- Deliver intuitive, accessible experiences that meet user needs
- Reduce rework by surfacing design requirements before development begins
- Ensure design consistency across the product

### Typical Communication
- Design reviews and prototype walkthroughs with Developers and Product Managers
- Async feedback via design tools (e.g., Figma comments)
- Sprint planning and backlog refinement sessions

### Interactions with Existing Roles
- **Product Manager**: collaborates on requirements, validates designs against success metrics
- **Developers**: hands off specs, reviews implementations for design fidelity
- **QA/Testing**: provides acceptance criteria for visual and interaction quality
- **Project Manager**: flags design-related risks or scope changes during planning

---

## Tech Lead / Engineering Lead

### Role Summary
The Tech Lead provides technical direction for the delivery team. They translate product requirements into architectural decisions and ensure code quality, scalability, and maintainability across the codebase.

### Responsibilities
- Define and communicate technical architecture and design patterns
- Lead design reviews and set code quality standards
- Unblock developers on complex technical challenges
- Work with the PM to assess scope, estimate effort, and flag technical risks
- Own the Definition of Done from a technical quality perspective

### Goals
- Deliver technically sound, maintainable solutions
- Reduce technical debt and unplanned rework
- Ensure the team has clarity on implementation approach before each sprint

### Typical Communication
- Technical design docs and architecture decision records (ADRs)
- Code review comments and PR approvals
- Daily standups and sprint planning with the delivery team

### Interactions with Existing Roles
- **Project Manager**: co-owns scope trade-off decisions and effort estimates
- **Product Manager**: translates business requirements into technical feasibility assessments
- **Developers**: primary technical mentor and unblocking resource
- **Security & Compliance Officer**: collaborates on threat modeling and secure design patterns
- **DevOps/Platform Engineer**: aligns on infrastructure requirements and CI/CD standards

---

## Security & Compliance Officer

### Role Summary
The Security & Compliance Officer ensures that all project deliverables meet the organization's security, privacy, and regulatory requirements. They are a key gatekeeper in the release process.

### Responsibilities
- Define and review security requirements during project planning
- Conduct or coordinate threat modeling for significant features
- Review CI security scan results and resolve critical findings before release
- Approve pre-release security checklists and maintain the security incident runbook
- Act as the escalation point for security-related incidents and findings

### Goals
- Prevent security vulnerabilities from reaching production
- Ensure regulatory and compliance requirements are met consistently
- Enable fast, safe delivery by embedding security earlier in the lifecycle (shift-left)

### Typical Communication
- Security review sessions during planning and pre-release
- Incident notifications and triage coordination
- Async reviews of PRs with security-sensitive changes

### Interactions with Existing Roles
- **Tech Lead**: collaborates on secure architecture and code review standards
- **DevOps/Platform Engineer**: reviews CI security scan configuration and pipeline hardening
- **Project Manager**: escalation point for security-related blockers and risk register entries
- **Product Manager**: advises on compliance constraints that affect feature scope or timelines

---

## DevOps / Platform Engineer

### Role Summary
DevOps / Platform Engineers own the infrastructure, CI/CD pipelines, and deployment tooling that enable reliable, repeatable delivery. They ensure the team can ship quickly and safely.

### Responsibilities
- Build and maintain CI/CD pipelines (tests, linting, security scanning, deployment)
- Manage staging and production environments
- Support deployment windows, rollback procedures, and post-deploy verifications
- Set up and maintain observability tooling (dashboards, alerts, logging)
- Collaborate with Developers on environment configuration and infrastructure-as-code

### Goals
- Enable fast, safe, and automated deployments
- Maximize environment stability and uptime
- Reduce manual steps and human error in the release process

### Typical Communication
- Deployment planning and release coordination with PM and Tech Lead
- Incident response and on-call coordination
- Documentation of pipeline changes and infrastructure decisions

### Interactions with Existing Roles
- **Tech Lead**: aligns on infrastructure requirements and deployment architecture
- **Security & Compliance Officer**: implements security scanning and access controls in pipelines
- **Project Manager**: communicates deployment windows, environment risks, and release readiness
- **Developers**: supports local environment setup, unblocks CI/CD issues during sprints

---

## Customer Success / Support Representative

### Role Summary
The Customer Success / Support Representative acts as the voice of the customer within the project team. They surface real-world feedback, coordinate customer communication during releases, and help validate that shipped features meet user expectations.

### Responsibilities
- Relay customer-reported bugs, friction points, and feature requests to Product Managers
- Review release notes and customer-facing communications before deployment
- Coordinate customer communication and enablement during major or breaking releases
- Participate in retrospectives to share post-release customer impact observations
- Contribute to acceptance criteria validation from a customer experience perspective

### Goals
- Ensure customers are informed, prepared, and successful after each release
- Close the feedback loop between the field and the product team
- Reduce support escalations through proactive communication and documentation

### Typical Communication
- Release communication reviews with PM and Product Manager
- Retrospective input on customer impact
- Async coordination on support tickets linked to active features

### Interactions with Existing Roles
- **Product Manager**: primary partner for surfacing customer feedback and validating priorities
- **Project Manager**: receives release schedule and communication timelines
- **UX/Design Lead**: shares usability feedback from customer interactions
- **QA/Testing**: flags customer-reported defects for triage and prioritization

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
