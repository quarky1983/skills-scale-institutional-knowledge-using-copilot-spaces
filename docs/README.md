# OctoAcme Project Management Docs

Welcome! This folder is the home for OctoAcme's program and process documentation. Use this README as your starting point: it summarizes how projects are run at OctoAcme and links to the detailed guidance you need.

## Overview of OctoAcme Project Management Processes

OctoAcme runs projects using a lightweight, repeatable lifecycle: **initiation → planning → execution → release → close/retro**. Work begins when a new idea or feature is ready for exploration. The team produces minimum initiation artifacts—a **Project One-pager** (problem, goal, success metrics), a stakeholder/communication plan, a high-level timeline with milestones, an initial risk list, and a rough view of resourcing. A decision gate ("approve to move into planning") confirms that success metrics are clear, stakeholders agree on priority, and the team has capacity. Planning then converts the approved initiative into a prioritized backlog of shippable increments, each carrying acceptance criteria, priority, estimates, an owner, and a **Definition of Done**.

Roles are explicitly defined to create clear ownership. The **Project Manager (PM)** coordinates delivery—schedule, risk, communication, and facilitation. The **Product Manager (PdM)** owns outcomes: problem framing, prioritization, and success measurement. **Developers** implement features and collaborate on design and testability. **QA/Testing** validates acceptance criteria and quality. **Stakeholders** provide input and approvals. This role clarity spans the full lifecycle and is supported by a project board workflow (**Backlog → Ready → In Progress → In Review → QA → Done**) that keeps delivery status visible to everyone.

Execution emphasizes consistent tracking and small-batch delivery. The team maintains a rhythm of **daily standups** (progress and blockers), a **weekly delivery sync** (updates and risk flags), and **end-of-sprint demos**. Risk is managed through a **risk register** (impact, likelihood, owner, mitigation, status) reviewed regularly, with clear escalation paths from team triage → PM escalation → leadership/sponsor escalation. Stakeholder communication is structured around regular status updates, a single source of truth for project health, and defined incident communication patterns when disruptions occur.

Quality assurance is built into daily development and the release process. OctoAcme favors **small PRs** with issue links and acceptance criteria in the description. Automated **tests, linting, and security scans** must pass in CI, and at least one peer approval is required before merge. Testing practices include **unit tests for new logic**, **integration tests where applicable**, and **end-to-end smoke tests for critical flows before release**, supplemented by **manual QA** for feature acceptance. Releases follow a standardized checklist: acceptance criteria met, CI/scans passing, release notes drafted, rollback plan confirmed, staging smoke tests complete, post-deploy verification done, and stakeholder announcements sent. Incidents trigger rollback and triage, followed by a **blameless retrospective** with tracked action items to drive continuous improvement.

## Process Docs

| Document | Description |
|---|---|
| [Project Management Overview](./octoacme-project-management-overview.md) | Principles, core roles, key artifacts, and the high-level lifecycle |
| [Project Initiation Guide](./octoacme-project-initiation.md) | How to start a project: one-pager, stakeholder plan, milestones, and the approval gate |
| [Project Planning](./octoacme-project-planning.md) | Backlog creation, Definition of Done, dependencies, and release planning |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Project board workflow, team cadence, and progress tracking practices |
| [Risk Management & Communication](./octoacme-risks-and-communication.md) | Risk register, escalation paths, and stakeholder communication strategies |
| [Release & Deployment](./octoacme-release-and-deployment.md) | Release checklist, deployment steps, and post-deploy verification |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Blameless retro format, action item tracking, and improvement loops |
| [Roles & Personas](./octoacme-roles-and-personas.md) | Detailed responsibilities and communication norms for each role |
