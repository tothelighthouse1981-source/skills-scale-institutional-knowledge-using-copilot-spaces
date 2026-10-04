# OctoAcme Project Management Docs

This README is the central index for OctoAcme’s project management guidance. The approach is lightweight and structured: keep ownership clear, deliver customer value in small increments, use evidence to guide decisions, and make project status and decisions visible.

## Process overview

1. **Initiation** — Define the problem, goals, stakeholders, and success metrics; confirm alignment and a decision to proceed.
2. **Planning** — Prioritize and estimate the backlog, define scope and milestones, and identify dependencies and risks.
3. **Execution & Tracking** — Deliver iteratively, track work on the project board, review progress, and escalate blockers through the agreed path.
4. **Release & Deployment** — Validate readiness, deploy safely with verification and rollback plans, and communicate the release.
5. **Retrospective & Continuous Improvement** — Capture learnings after sprints, releases, milestones, or incidents; assign and track improvement actions.

## Approach and working practices

The Project Manager coordinates delivery, schedules, risks, and communication; the Product Manager defines outcomes, prioritizes work, and measures success. Developers build and test the work, QA validates acceptance criteria and quality, and stakeholders provide input and approvals. See [Roles and Personas](octoacme-roles-and-personas.md) for details.

Work moves from a prioritized backlog through **Ready, In Progress, In Review, QA, and Done**. Teams use clear acceptance criteria and a Definition of Done, small issue-linked pull requests, and iterative demos or reviews. The Project Manager and Product Manager align weekly; delivery teams hold daily standups and weekly delivery syncs; stakeholders receive regular, typically monthly or milestone-based, updates. Risks are reviewed weekly, and blockers are escalated from the team to the Project Manager, Product Lead, and sponsor as needed.

Quality is built into delivery: automated tests, linting, and security scans run in CI; pull requests receive review; and manual acceptance checks and smoke tests validate critical flows and releases. Releases require readiness checks, release notes, post-deployment verification, and a rollback or mitigation plan. Retrospective actions have owners and due dates and are tracked through the backlog or issues.

## Documentation

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution and Tracking](octoacme-execution-and-tracking.md)
- [Risks and Communication](octoacme-risks-and-communication.md)
- [Release and Deployment](octoacme-release-and-deployment.md)
- [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)
