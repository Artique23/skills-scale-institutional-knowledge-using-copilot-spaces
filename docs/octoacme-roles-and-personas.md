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

## Quality Assurance (QA) / Testing

### Role Summary
QA Engineers validate that features meet acceptance criteria, identify defects, and ensure overall product quality before release. They collaborate closely with developers and product teams throughout the development lifecycle.

### Responsibilities
- Design and execute test plans and test cases
- Perform functional, regression, and exploratory testing
- Identify, document, and track defects
- Validate bug fixes and feature implementations
- Automate test scenarios where appropriate
- Verify acceptance criteria are met before release

### Goals
- Catch defects early in the development cycle
- Ensure high product quality and user experience
- Minimize production incidents and customer-reported bugs
- Improve test coverage and automation

### Typical Communication
- Daily standups and sprint planning
- Bug reports and test results documentation
- Sign-off on acceptance criteria and release readiness
- Collaborate with developers on reproducing and fixing issues

### Interaction with Other Roles
- **Developers**: Collaborate on test case design, bug reproduction, and fix validation
- **Product Manager**: Clarify acceptance criteria and validate feature completeness
- **Release Manager**: Provide testing sign-off and participate in release readiness reviews
- **Business Analyst**: Review requirements for testability and edge cases

---

## Release Manager

### Role Summary
Release Managers coordinate and execute software releases, ensuring smooth deployments with minimal risk. They manage release schedules, verify readiness, and coordinate communication across teams and stakeholders.

### Responsibilities
- Plan and schedule releases with stakeholders
- Verify release readiness (CI/CD green, security scans passed, approvals obtained)
- Execute deployment procedures and monitor rollout
- Maintain rollback plans and coordinate emergency responses
- Communicate release status to stakeholders and customers
- Track post-release metrics and coordinate hotfixes if needed
- Maintain release documentation and runbooks

### Goals
- Achieve zero-downtime deployments
- Minimize production incidents from releases
- Ensure clear communication and transparency during releases
- Continuously improve release processes and automation

### Typical Communication
- Release planning meetings with PM and engineering
- Pre-release status updates to stakeholders
- Deployment notifications and post-release summaries
- Incident communication during deployment issues

### Interaction with Other Roles
- **Developers**: Coordinate code freeze, review release candidate, validate deployment scripts
- **QA**: Confirm testing sign-off and coordinate smoke tests
- **Product Manager**: Align on release scope, timing, and feature flags
- **On-call/Support Engineer**: Brief on release changes and hand off monitoring responsibilities
- **Security Reviewer**: Ensure security scans passed and vulnerabilities addressed
- **Stakeholders**: Communicate release plans, timelines, and post-release status

### Escalation Path
- Level 1: Team-level rollback decision for deployment issues
- Level 2: Escalate to engineering leadership for critical incidents
- Level 3: Engage incident commander and stakeholders for customer-impacting outages

### Artifact Ownership
- **Release Notes**: Primary owner
- **Release Checklist**: Primary owner
- **Deployment Runbook**: Primary owner
- **Post-Release Report**: Primary owner

**Template**: See [docs/templates/release-manager-checklist.md](templates/release-manager-checklist.md)

---

## Scrum Master

### Role Summary
Scrum Masters facilitate agile processes, remove blockers, and coach teams to continuously improve delivery practices. They ensure the team follows Scrum ceremonies and principles while fostering a collaborative environment.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Remove impediments and blockers to team progress
- Coach team on agile practices and self-organization
- Track team velocity, burndown, and process metrics
- Shield team from external interruptions during sprints
- Drive continuous improvement through retrospectives
- Facilitate cross-team coordination when needed

### Goals
- Maximize team productivity and velocity
- Reduce cycle time and improve predictability
- Foster psychological safety and continuous learning
- Ensure transparent communication and alignment

### Typical Communication
- Daily facilitation of standups and ceremonies
- Blocker escalation to PM and leadership
- Retrospective summaries and action items
- Process improvement suggestions to the team

### Interaction with Other Roles
- **Developers**: Remove blockers, facilitate collaboration, coach on agile practices
- **Product Manager**: Ensure backlog is ready and prioritized, clarify sprint goals
- **Project Manager**: Coordinate on timelines, risks, and resource needs
- **QA**: Ensure testing is integrated into sprint workflow
- **Stakeholders**: Communicate sprint progress and manage expectations

### Escalation Path
- Level 1: Team-level blocker resolution in standup
- Level 2: Escalate to PM or engineering lead for cross-team dependencies
- Level 3: Escalate to leadership for organizational impediments

### Artifact Ownership
- **Sprint Backlog**: Co-owner with team
- **Sprint Goal**: Facilitates definition with Product Owner
- **Retrospective Action Items**: Primary owner
- **Team Velocity Metrics**: Primary owner

**Template**: See [docs/templates/scrum-master-checklist.md](templates/scrum-master-checklist.md)

---

## UX Designer

### Role Summary
UX Designers create user-centered designs that balance user needs, business goals, and technical constraints. They conduct research, design interfaces, and collaborate with developers to ensure design intent is implemented correctly.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Define user flows and interaction patterns
- Ensure accessibility and inclusive design practices
- Maintain design system and component libraries
- Collaborate with developers on implementation and design QA
- Iterate on designs based on user feedback and data

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and increase task completion rates
- Ensure design consistency across the product
- Validate designs through research and testing

### Typical Communication
- Design reviews and critique sessions
- Developer handoff meetings with annotated mockups
- User research findings and recommendations
- Design system updates and component documentation

### Interaction with Other Roles
- **Developers**: Provide detailed design handoff, clarify interaction details, conduct design QA
- **Product Manager**: Collaborate on feature definition, validate solutions with user research
- **Business Analyst**: Review requirements for user experience implications
- **QA**: Define visual and interaction acceptance criteria
- **Stakeholders**: Present design concepts and gather feedback

### Escalation Path
- Level 1: Resolve design questions with developers directly
- Level 2: Escalate to Product Manager for scope or priority decisions
- Level 3: Escalate to design leadership for design system or standards questions

### Artifact Ownership
- **UX Specifications**: Primary owner
- **Wireframes and Mockups**: Primary owner
- **User Flows**: Primary owner
- **Design System Components**: Primary owner
- **Accessibility Guidelines**: Primary owner

**Template**: See [docs/templates/ux-handoff.md](templates/ux-handoff.md)

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business stakeholders and technical teams by gathering, analyzing, and documenting detailed requirements. They ensure that features deliver business value and meet stakeholder needs.

### Responsibilities
- Gather and analyze business requirements from stakeholders
- Document detailed functional and non-functional requirements
- Define acceptance criteria and edge cases
- Create process flows and data models
- Facilitate requirement reviews with stakeholders and developers
- Validate delivered features against requirements
- Identify opportunities for process improvement

### Goals
- Ensure clear, complete, and testable requirements
- Minimize rework due to unclear or missing requirements
- Maximize business value delivered by features
- Improve stakeholder satisfaction and alignment

### Typical Communication
- Requirement gathering sessions with stakeholders
- Requirement review meetings with developers and QA
- Detailed requirement documentation and specifications
- User story refinement and backlog grooming

### Interaction with Other Roles
- **Product Manager**: Collaborate on product vision and prioritization
- **Developers**: Clarify requirements, answer technical questions, validate feasibility
- **QA**: Define testable acceptance criteria and validation approach
- **UX Designer**: Align on user flows and interaction requirements
- **Stakeholders**: Gather requirements, manage expectations, demonstrate solutions

### Escalation Path
- Level 1: Clarify requirement questions with stakeholders directly
- Level 2: Escalate to Product Manager for priority or scope conflicts
- Level 3: Escalate to business sponsor for strategic decisions

### Artifact Ownership
- **Detailed Requirements**: Primary owner
- **Acceptance Criteria**: Primary owner (shared with Product Manager)
- **Business Process Flows**: Primary owner
- **Data Requirements**: Primary owner
- **Use Cases**: Primary owner

**Template**: See [docs/templates/business-analyst-reqs.md](templates/business-analyst-reqs.md)

---

## On-call / Support Engineer

### Role Summary
On-call and Support Engineers provide technical support for production systems, respond to incidents, and ensure system reliability. They act as the first line of defense for production issues and customer-impacting incidents.

### Responsibilities
- Monitor production systems and respond to alerts
- Triage and resolve production incidents
- Escalate complex issues to development teams
- Document incident resolutions and root causes
- Participate in on-call rotation
- Support customers with technical issues
- Contribute to runbooks and incident response procedures

### Goals
- Minimize mean time to resolution (MTTR) for incidents
- Maintain high system uptime and reliability
- Provide excellent customer support experience
- Continuously improve incident response processes

### Typical Communication
- Incident reports and status updates
- Post-incident reviews and root cause analysis
- On-call handoff notes and escalation alerts
- Customer support tickets and responses

### Interaction with Other Roles
- **Developers**: Escalate complex bugs, collaborate on incident resolution
- **Release Manager**: Coordinate during deployments, report post-release issues
- **Product Manager**: Report patterns in customer issues and feature requests
- **QA**: Report production bugs and edge cases found in the field
- **Stakeholders**: Communicate incident status and impact

### Escalation Path
- Level 1: On-call engineer troubleshoots and resolves standard issues
- Level 2: Escalate to development team for code-level issues
- Level 3: Declare major incident and engage incident commander for critical outages

### Artifact Ownership
- **Incident Reports**: Primary owner
- **Runbooks**: Co-owner with developers
- **Support Ticket Documentation**: Primary owner
- **Post-Incident Reviews**: Co-owner with engineering

---

## Security Reviewer

### Role Summary
Security Reviewers assess code, infrastructure, and processes to identify security vulnerabilities and ensure compliance with security standards. They provide guidance on secure development practices and validate security controls.

### Responsibilities
- Review code for security vulnerabilities (SAST, DAST)
- Conduct security threat modeling for new features
- Review and approve security-sensitive changes
- Ensure compliance with security policies and standards
- Guide developers on secure coding practices
- Track and prioritize security findings
- Coordinate security incident response

### Goals
- Prevent security vulnerabilities from reaching production
- Ensure compliance with security standards (e.g., OWASP, SOC 2)
- Minimize security technical debt
- Foster a security-aware development culture

### Typical Communication
- Security review findings and recommendations
- Threat modeling sessions with architects and developers
- Security compliance status reports
- Security training and awareness communications

### Interaction with Other Roles
- **Developers**: Review code for security issues, provide remediation guidance
- **Release Manager**: Verify security scans passed before release
- **QA**: Collaborate on security test cases and penetration testing
- **Product Manager**: Advise on security implications of features
- **Compliance/Legal**: Ensure regulatory compliance for data handling

### Escalation Path
- Level 1: Developer remediates security findings
- Level 2: Escalate to security team lead for complex vulnerabilities
- Level 3: Escalate to CISO for critical vulnerabilities or compliance issues

### Artifact Ownership
- **Security Review Reports**: Primary owner
- **Threat Models**: Primary owner
- **Security Scan Results**: Primary owner
- **Security Compliance Documentation**: Co-owner with compliance team

---

## Artifact Ownership Mapping

This table clarifies who owns specific project artifacts and deliverables:

| Artifact | Primary Owner | Contributors | Approvers |
|----------|--------------|--------------|-----------|
| **Release Notes** | Release Manager | Product Manager, Developers | Product Manager |
| **Acceptance Criteria** | Product Manager, Business Analyst | UX Designer, QA | Product Manager |
| **UX Specifications** | UX Designer | Business Analyst | Product Manager |
| **Detailed Requirements** | Business Analyst | Product Manager, UX Designer | Product Manager, Stakeholders |
| **Design Mockups** | UX Designer | Product Manager | Product Manager, Stakeholders |
| **Sprint Backlog** | Scrum Master, Team | Product Manager | Product Manager |
| **Test Plans** | QA | Developers, Business Analyst | QA Lead |
| **Deployment Runbook** | Release Manager | Developers, On-call Engineer | Engineering Lead |
| **Incident Reports** | On-call Engineer | Developers | Engineering Lead |
| **Security Review Reports** | Security Reviewer | Developers | Security Lead |
| **Retrospective Action Items** | Scrum Master | Team | Team |
| **Product Roadmap** | Product Manager | Stakeholders, Engineering Lead | Executive Sponsor |
| **Risk Register** | Project Manager | Team | Project Manager, Stakeholders |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

