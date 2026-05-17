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

## QA / Testing Engineers

### Role Summary
QA / Testing Engineers verify that delivered software meets acceptance criteria, quality standards, and non-functional requirements. They design test strategies, automate regression coverage, and provide the final quality sign-off before release.

### Responsibilities
- Define test plans and acceptance test scenarios from requirements
- Build and maintain automated test suites (unit-adjacent, integration, end-to-end)
- Perform exploratory and regression testing on candidate releases
- Triage defects and partner with Developers on root-cause analysis
- Sign off on release readiness against documented quality gates

### Goals
- Catch defects before they reach customers
- Shrink the manual-test burden through targeted automation
- Maintain a trusted, fast, low-flake regression suite

### Typical Communication
- Test plans and exit-criteria reports
- Defect reports linked to issues and PRs
- Release-readiness reviews

### Interactions with Existing Roles
- **Developers** — pair on reproducing defects and reviewing test coverage in PRs
- **Product Managers** — confirm acceptance criteria are testable and verify scenarios match intent
- **Project Managers** — surface quality risk early in the schedule and flag readiness blockers

---

## Engineering Managers / Tech Leads

### Role Summary
Engineering Managers and Tech Leads own technical direction and team health. They guide architecture decisions, balance capacity against commitments, mentor Developers, and act as the primary escalation path for technical risk.

### Responsibilities
- Set and maintain technical standards, architecture, and coding guidelines
- Plan team capacity and balance feature work against tech-debt and reliability
- Mentor Developers and run technical design reviews
- Approve major architectural changes and dependency choices
- Escalate technical risks to Project Managers and Executive Sponsors

### Goals
- Sustainable delivery pace without accumulating unmanaged tech debt
- Strong, growing engineering team with clear career paths
- Architectural decisions that age well

### Typical Communication
- Architecture decision records (ADRs) and design reviews
- 1:1s with Developers; team-health updates to leadership
- Technical-risk callouts in status reports

### Interactions with Existing Roles
- **Developers** — provide direction, unblock, and review significant designs
- **Product Managers** — negotiate scope vs. technical feasibility and sequencing
- **Project Managers** — own technical-risk entries in the risk register

---

## UX Designers

### Role Summary
UX Designers own the user-facing experience: research, interaction design, visual design, and accessibility. They partner with Product Managers on problem framing and with Developers on faithful implementation.

### Responsibilities
- Conduct user research and synthesize findings into design decisions
- Produce wireframes, prototypes, and high-fidelity designs
- Maintain the design system and accessibility (WCAG) standards
- Validate implemented UI against design intent
- Contribute to acceptance criteria for user-facing features

### Goals
- Designs that solve real user problems and are usable for everyone
- Consistent, accessible experience across the product
- Tight design-engineering feedback loops

### Typical Communication
- Prototypes, design specs, and Figma reviews
- Research readouts and usability findings
- Design QA notes on PRs

### Interactions with Existing Roles
- **Product Managers** — co-own problem definition and outcome metrics
- **Developers** — pair on implementation details, edge cases, and design QA
- **Project Managers** — surface design dependencies and research timelines

---

## DevOps / Site Reliability Engineers

### Role Summary
DevOps / SREs own the CI/CD pipeline, deployment infrastructure, observability, and incident response. They make safe, fast, reversible deployments the default and keep production reliable.

### Responsibilities
- Build and maintain CI/CD pipelines and deployment automation
- Operate observability (logs, metrics, traces) and alerting
- Lead incident response and post-incident reviews
- Define and track SLOs, error budgets, and reliability targets
- Partner with Developers on production-readiness reviews

### Goals
- Frequent, low-risk deployments with fast rollback
- Meet or exceed SLOs and stay within error budgets
- Reduce mean-time-to-detect and mean-time-to-recover

### Typical Communication
- Incident reports and post-mortems
- Deployment runbooks and on-call handoffs
- Reliability dashboards and SLO reviews

### Interactions with Existing Roles
- **Developers** — pair on instrumentation, deploy mechanics, and incident response
- **Project Managers** — coordinate release windows and surface reliability risk
- **Product Managers** — translate reliability targets into prioritization trade-offs

---

## Executive Sponsors

### Role Summary
Executive Sponsors hold funding authority, strategic alignment, and the final escalation path for a project. They are accountable for the business outcome and remove organizational blockers the team cannot resolve.

### Responsibilities
- Approve project initiation, scope, and budget
- Resolve cross-team conflicts and remove organizational blockers
- Receive scheduled status updates and ad-hoc escalations
- Approve material changes to scope, timeline, or budget
- Champion the project with executive peers and stakeholders

### Goals
- Project delivers the intended business outcome
- Strategic alignment between project and company priorities
- Sufficient resourcing and political cover for the team

### Typical Communication
- Steering committee reviews and monthly executive updates
- Escalation conversations with Project and Engineering Managers
- Go/no-go decisions at major milestones

### Interactions with Existing Roles
- **Project Managers** — receive escalations and approve scope/timeline changes
- **Product Managers** — confirm product direction matches strategic intent
- **Engineering Managers** — consulted on major technical-risk escalations

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

