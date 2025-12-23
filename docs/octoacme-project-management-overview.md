# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles
- **Project Manager (PM)**: coordinates delivery, schedules, risk, communications.
- **Product Manager (PdM)**: defines outcomes, prioritizes backlog, and measures success.
- **Developers**: implement features, collaborate on design and testability.
- **QA/Testing**: validate quality and acceptance criteria.
- **Stakeholders**: provide inputs and approvals.

### Extended Roles
In addition to core roles, OctoAcme teams may include specialized personas that perform essential functions:

- **Release Manager**: coordinates release planning, deployment execution, and rollback procedures. Ensures smooth releases with clear communication.
- **Scrum Master**: facilitates agile ceremonies (standups, planning, retrospectives), removes blockers, and drives continuous improvement.
- **UX Designer**: creates user-centered designs, conducts research, and provides detailed handoffs to developers with mockups and interaction specs.
- **Business Analyst**: gathers and documents detailed requirements, defines acceptance criteria, and bridges stakeholder needs with technical implementation.
- **On-call / Support Engineer**: monitors production systems, responds to incidents, and provides technical support to ensure reliability.
- **Security Reviewer**: assesses code and infrastructure for vulnerabilities, ensures compliance, and guides secure development practices.

For detailed persona descriptions including responsibilities, goals, interactions, and escalation paths, see [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md).

## Key Artifacts
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

### Artifact Ownership
The following table maps key artifacts to their primary owners, contributors, and approvers:

| Artifact | Primary Owner | Contributors | Approvers |
|----------|--------------|--------------|-----------|
| Project Charter / One-pager | Project Manager | Product Manager, Stakeholders | Executive Sponsor |
| Product Roadmap | Product Manager | Stakeholders, Engineering Lead | Executive Sponsor |
| Release Plan & Notes | Release Manager | Product Manager, Developers | Product Manager |
| Sprint Backlog | Scrum Master, Team | Product Manager | Product Manager |
| Acceptance Criteria | Product Manager, Business Analyst | UX Designer, QA | Product Manager |
| Detailed Requirements | Business Analyst | Product Manager, UX Designer | Product Manager, Stakeholders |
| UX Specifications | UX Designer | Business Analyst | Product Manager |
| Test Plans | QA | Developers, Business Analyst | QA Lead |
| Deployment Runbook | Release Manager | Developers, On-call Engineer | Engineering Lead |
| Risk Register | Project Manager | Team | Project Manager, Stakeholders |
| Retrospective Action Items | Scrum Master | Team | Team |
| Security Review Reports | Security Reviewer | Developers | Security Lead |

For role-specific templates and checklists, see [docs/templates/](templates/).

## Lifecycle (high-level)
1. Initiation: problem statement, stakeholders, high-level timeline.
2. Planning: scope, resources, milestones, dependencies.
3. Execution: build, test, review, iterate.
4. Release: deploy, verify, announce.
5. Close & Retrospective: capture learnings and next steps.

## Communication Cadence
- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
