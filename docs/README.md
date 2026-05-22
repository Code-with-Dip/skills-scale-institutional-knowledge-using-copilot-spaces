# OctoAcme Project Management Docs

Welcome! This README provides an entry point to all project management process documentation for OctoAcme.

## Project Management Processes (Summary)

OctoAcme follows an **iterative, customer-focused delivery model** with clear roles and artifacts throughout the project lifecycle. Here's how we execute projects:

### Core Lifecycle

OctoAcme runs projects through five distinct phases:

1. **Initiation** — Validate business need, define success metrics, align stakeholders, and create a lightweight Project One-pager. Move to planning only when success criteria are clear and stakeholder buy-in is confirmed.

2. **Planning** — Break approved initiatives into shippable increments with prioritized backlogs, acceptance criteria, and clear ownership. Define the Definition of Done and map dependencies and integration points.

3. **Execution** — Build, test, and review work in daily standups (15 min), weekly delivery syncs, and end-of-sprint demos. Use GitHub Projects for workflow management (Backlog → Ready → In Progress → In Review → QA → Done). Enforce small PRs (≤400 lines), automated testing/linting in CI, and code reviews before merge.

4. **Release** — Deploy to production following pre-release requirements (acceptance criteria met, CI/security scans pass, smoke tests prepared). Use staging-first deployments with post-deploy verification and rollback playbooks for incidents.

5. **Continuous Improvement** — Capture learnings through retrospectives after sprints, releases, or milestones. Convert action items into tracked improvements with clear owners and success criteria.

### Key Characteristics

- **Clear ownership**: Each project has a named Project Manager (coordinates delivery) and Product Lead (defines outcomes)
- **Risk management**: Maintain a Risk Register with ID, description, impact, likelihood, owner, and mitigation plan. Escalate through three levels: team-level → PM → sponsor
- **Quality embedded**: Unit tests, integration tests, end-to-end smoke tests, security scanning in CI, and manual QA when needed—not just final-gate testing
- **Structured communication**: Daily standups, weekly PM + Product Manager syncs, twice-weekly team standups, monthly stakeholder updates, and consistent status templates
- **Data-informed decisions**: Track velocity, burndown, and success metrics; use dashboards for key signals; measure impact of improvements
- **Psychological safety**: Encourage feedback, learning, and blameless retrospectives to drive continuous culture

### Core Roles

- **Project Manager** — Coordinates delivery, manages schedules, risks, and communications
- **Product Manager** — Defines outcomes, prioritizes backlog, measures success
- **Developers** — Implement features, collaborate on design and testability
- **QA/Testing** — Validates quality and acceptance criteria
- **Stakeholders** — Provide inputs, approvals, and business context

---

## Docs Index

Navigate to the documentation that matches your current project phase or area of interest:

- **[Project Management Overview](octoacme-project-management-overview.md)** — Start here for a concise introduction to OctoAcme's approach, core roles, key artifacts, and high-level lifecycle.

- **[Project Initiation Guide](octoacme-project-initiation.md)** — Learn how to validate business need, align stakeholders, and create a lightweight plan. Use this when a new project idea or feature proposal is ready to be explored.

- **[Project Planning](octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and backlog. Covers kickoff, backlog creation, dependency mapping, and release planning.

- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Manage day-to-day execution, track progress, and maintain quality. Includes team rhythm, PR workflows, testing standards, and blocker escalation.

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify, assess, and mitigate risks. Maintain stakeholder communication and follow escalation paths.

- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardize how OctoAcme releases features to production. Covers pre-release requirements, deployment checklists, and rollback procedures.

- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings after sprints, releases, or milestones. Convert action items into tracked improvements.

- **[Roles & Personas](octoacme-roles-and-personas.md)** — Understand the responsibilities and communication patterns of Developers, Product Managers, Project Managers, and other key roles.

---

## How to Use These Docs

- **New team members**: Start with the [Project Management Overview](octoacme-project-management-overview.md), then explore the phase-specific guides as needed.
- **Active projects**: Keep your Project Charter updated in the project repository. Link back to these docs for reference and consistency.
- **Continuous improvement**: When updating OctoAcme processes, use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template to propose changes collaboratively.

---

*Update this index as new process docs are added to keep everyone synchronized.*
