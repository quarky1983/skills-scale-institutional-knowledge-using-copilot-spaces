# OctoAcme Project Management Docs

Welcome! This folder is the home for OctoAcme's program and process documentation. Whether you are a new team member getting up to speed or a stakeholder looking for a specific process, this README is your starting point for understanding how projects are run at OctoAcme and where to find the detailed guidance you need.

## Overview of OctoAcme Project Management Processes

OctoAcme runs projects using a lightweight, repeatable lifecycle that moves from **initiation → planning → execution → release → close/retro**. Work begins when a new idea or feature is ready for exploration, producing minimum initiation artifacts: a **Project One-pager** (problem, goal, success metrics), a stakeholder/communication plan, a high-level timeline with milestones, an initial risk list, and a rough view of resourcing. A decision gate ("approve to move into planning") ensures success metrics are clear, stakeholders agree on priority, and the team has capacity before committing to detailed planning. Planning then converts the approved initiative into a prioritized backlog of shippable increments, each with acceptance criteria, priority, estimates, an owner, and a **Definition of Done**.

Roles are explicitly defined to create clear ownership and reduce ambiguity. The **Project Manager (PM)** coordinates delivery—schedule, risk, communication, and facilitation—while the **Product Manager (PdM)** owns outcomes: problem framing, prioritization, and success measurement. **Developers** implement features and collaborate on design and testability; **QA/Testing** validates acceptance criteria and quality; and **Stakeholders** provide input and approvals. This role clarity spans the full project lifecycle, from kickoff through retrospective, and is supported by a project board workflow (**Backlog → Ready → In Progress → In Review → QA → Done**) that makes delivery status visible to everyone.

Execution emphasizes consistent tracking and small-batch delivery. The team maintains a rhythm of **daily standups** for progress and blockers, a **weekly delivery sync** for updates and risk flags, and **end-of-sprint demos/reviews**. Risk management is handled through a **risk register** (impact, likelihood, owner, mitigation, status) reviewed regularly, with clear escalation paths from team triage to PM escalation to leadership/sponsor escalation when needed. Stakeholder communication is structured around regular updates, a single source of truth for project status, and specific incident communication patterns when disruptions occur.

Quality assurance is built into both day-to-day development and the release process. OctoAcme favors **small PRs**, requires issue links and acceptance criteria in PR descriptions, and mandates automated **tests, linting, and security scans in CI** before review, with at least one approval required. Testing practices include **unit tests for new logic**, **integration tests where applicable**, and **end-to-end smoke tests for critical flows before release**, supplemented by **manual QA** for feature acceptance. Releases follow a standardized checklist (acceptance criteria met, CI/scans passing, release notes, rollback plan, staging smoke tests, post-deploy verification, and stakeholder announcements). Incidents trigger rollback and triage followed by a **blameless retrospective** with tracked action items, driving continuous improvement across every project.

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
