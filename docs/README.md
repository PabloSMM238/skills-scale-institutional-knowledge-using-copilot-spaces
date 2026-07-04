# OctoAcme Project Management Docs

This README is the central landing page for OctoAcme's project management process documentation. It provides a concise overview of our lifecycle and links to the full documents in the docs/ folder so new teammates and stakeholders can quickly find the guidance they need.

OctoAcme runs projects through a stage-gated lifecycle: Initiation (validate the problem, create a one-pager, confirm stakeholders), Planning (break work into shippable increments, estimate, identify dependencies and risks), Execution & Tracking (deliver iteratively using a project board, daily standups, weekly syncs, and PR/CI best practices), Release & Deployment (pre-release checks, staging smoke tests, rollback plans), and Retrospective & Continuous Improvement (timeboxed retros, prioritized action items, and measurement of improvement impact). Projects move from stage to stage when success criteria, stakeholder alignment, and resource availability are clear.

Workflows emphasize small, reviewable changes and visibility. Use the project board with columns Backlog → Ready → In Progress → In Review → QA → Done. Follow the Pull Request conventions: small PRs, link the related issue and acceptance criteria, run CI (tests, linting, security scans), and require reviews/approvals before merging. Blocker escalation is tiered so business-impacting issues are handled promptly: team triage → PM → Product Lead / dependent teams → Sponsor.

Roles and communication are explicit. Core personas include Project Manager (delivery coordination, schedule, risk tracking), Product Manager (outcomes, prioritization, metrics), Developers (implementation, tests), QA/Testing (validation of acceptance), and Stakeholders (approvals, inputs). Regular cadence items include PM+PdM weekly alignment, delivery team standups, weekly delivery syncs, demos at the end of sprints, and monthly stakeholder updates. Quality gates include unit and integration tests, end-to-end smoke tests for critical flows, CI security scanning, manual QA where required, and an incident/rollback playbook to minimize production risk.

## Documents

- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md)
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](docs/octoacme-roles-and-personas.md)

## How to use

- Add or update additional process docs in docs/ and link them here.
- Keep the Project One-pager and key artifacts in the project repo so they remain the single source of truth.
- To make these docs available to Copilot Spaces, add process-specific context into `.copilot/` as needed.
