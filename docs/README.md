# OctoAcme Project Management Docs

This directory contains OctoAcme's program and project management process documents. These docs capture how we plan, execute, communicate, and learn from work across cross-functional projects. They are intended to make onboarding easier, provide a single source of truth for delivery practices, and support consistent execution.

## Quick summary
OctoAcme uses a structured, iterative approach anchored on customer-first principles, clear roles, and data-informed decisions. Projects move through a lifecycle of initiation → planning → execution → release → retrospective. Risk management, stakeholder communication, and quality assurance are embedded throughout the lifecycle. Core roles include Product Manager, Project Manager, Developers, QA, and Stakeholders.

## Brief overview of OctoAcme project management processes
- Initiation: Capture the business problem, define success metrics, identify stakeholders, and produce a Project One-pager to decide whether to move into planning.
- Planning: Run a kickoff, create a prioritized backlog with acceptance criteria, estimate work, identify dependencies and risks, and produce a release plan and Definition of Done.
- Execution & Tracking: Use a project board and small pull requests, run CI and tests, track velocity and burndown, hold regular team rhythm (standups, weekly syncs, demos), and escalate blockers as needed.
- Release & Deployment: Follow pre-release checks (CI, security scans, release notes, rollback plan), run staging smoke tests, deploy via automated pipeline when possible, and run post-deploy verification.
- Retrospective & Continuous Improvement: Run blameless retrospectives after sprints/releases/incidents, capture action items with owners and due dates, and add improvements to the backlog.

## Documents in this folder
- [Project Management Overview](./octoacme-project-management-overview.md) — High-level principles, lifecycle, roles, and key artifacts.
- [Project Initiation Guide](./octoacme-project-initiation.md) — One-pager, initiation checklist and decision gate.
- [Project Planning](./octoacme-project-planning.md) — Backlog, estimation, dependencies, and planning checklist.
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Team rhythm, PR workflow, testing and execution checklist.
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Risk register, stakeholder comms, and escalation paths.
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Release types, pre-release checks, and rollback playbook.
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Retrospective structure and tracking improvements.
- [Roles and Personas](./octoacme-roles-and-personas.md) — Role descriptions and responsibilities used across the docs.

## How to use these docs
- Start with the Project Management Overview for context.
- For a new initiative follow the Project Initiation Guide, then move into Project Planning.
- Keep the Project One-pager, Risk Register, and Release notes in the project repo (docs/ or .copilot/) so Copilot Spaces can use them as context.
- Link to relevant process docs from project READMEs and the project board.

## Contribution guidance
- Use the issue template "Add Content to Project Management Process Docs" in .github/ISSUE_TEMPLATE/ to propose updates.
- When submitting changes: include a short rationale, suggested content, and acceptance criteria (see the issue template).
- Label updates as `documentation` and `process improvement` where appropriate.

## Acceptance criteria
- Content aligns with existing process docs in docs/
- README improves discoverability and onboarding
- README is linked to issue #2 for traceability

## Related
- Issue: https://github.com/Artique23/skills-scale-institutional-knowledge-using-copilot-spaces/issues/2
