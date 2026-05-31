# OctoAcme Project Management Docs

This folder documents OctoAcme's lightweight but structured project management model across the full delivery lifecycle: **initiation, planning, execution, release, and retrospective improvement**. Work starts with a one-pager that defines the problem, goal, success metrics, stakeholders, timeline, risks, and resource needs. After approval, planning converts that intent into a prioritized backlog with acceptance criteria, estimates, dependencies, milestones, and a clear Definition of Done.

Delivery depends on clear cross-functional ownership. **Project Managers** coordinate timelines, risks, meetings, documentation, and stakeholder communication. **Product Managers** define outcomes, prioritize work, and measure impact. **Developers** implement and test features while surfacing technical risks, and **QA/testing contributors** validate acceptance criteria and quality. Stakeholders provide input, approvals, and alignment throughout.

Execution is run through visible workflows and regular team rhythms. Teams track work on boards (Backlog, Ready, In Progress, In Review, QA, Done), use standups to resolve blockers and dependencies, and maintain weekly delivery/PM-Product syncs. Communication is milestone-based, with status updates and a shared source of truth (project README or release docs). Risks are maintained in a simple register and escalated from team triage to sponsor-level escalation when business impact requires it.

Quality is built into every stage instead of treated as a final gate. OctoAcme expects unit tests for new logic, integration tests when needed, end-to-end smoke tests for critical flows, and security scanning in CI. Pull requests should be small, linked to issues and acceptance criteria, pass checks before review, and meet approval policy before merge. Before release, teams verify acceptance criteria, CI/scans, rollback readiness, and smoke test preparation. After each sprint, release, or incident, retrospectives capture improvements and track action items.

## Document map

- [Project management overview](./octoacme-project-management-overview.md)
- [Project initiation guide](./octoacme-project-initiation.md)
- [Project planning](./octoacme-project-planning.md)
- [Execution and tracking](./octoacme-execution-and-tracking.md)
- [Risk management and communication](./octoacme-risks-and-communication.md)
- [Release and deployment](./octoacme-release-and-deployment.md)
- [Retrospective and continuous improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and personas](./octoacme-roles-and-personas.md)
