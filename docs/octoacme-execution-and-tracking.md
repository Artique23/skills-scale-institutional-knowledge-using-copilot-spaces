# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- **Daily standups (15 min)** — focus on progress, blockers, dependencies
  - *Facilitated by*: Scrum Master (or Project Manager in non-Scrum teams)
  - *Participants*: Developers, QA, Product Manager (as needed)
- **Weekly delivery sync** — show progress, updates, and flagged risks
  - *Facilitated by*: Project Manager
  - *Participants*: Team leads, stakeholders
- **Demo/Review at the end of each sprint or milestone**
  - *Facilitated by*: Scrum Master (or Project Manager)
  - *Participants*: Team, Product Manager, stakeholders

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- **Level 1**: Team-level triage in daily standup
  - *Facilitated by*: Scrum Master
  - *Action*: Team collaborates to resolve blockers directly
- **Level 2**: PM escalates to Product Lead and dependent teams
  - *When*: Blockers require cross-team coordination or resource allocation
  - *Involves*: Project Manager, Product Manager, engineering leads
- **Level 3**: Sponsor-level escalation for business-impacting issues
  - *When*: Critical blockers affecting release dates or business outcomes
  - *Involves*: Executive sponsor, stakeholders, leadership team

### Deployment & Incident Escalation
For deployment and production incidents, escalation follows a specific path:
- **Level 1**: On-call Engineer troubleshoots and attempts resolution
- **Level 2**: Release Manager coordinates with development team for code-level issues or deployment failures
- **Level 3**: Declare major incident; engage incident commander and stakeholders for customer-impacting outages

For ceremony facilitation details, see [docs/templates/scrum-master-checklist.md](templates/scrum-master-checklist.md).  
For release coordination, see [docs/templates/release-manager-checklist.md](templates/release-manager-checklist.md).

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
