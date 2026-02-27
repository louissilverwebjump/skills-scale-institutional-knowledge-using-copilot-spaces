# OctoAcme Roles and Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## How These Roles Map to Common Ceremonies and Artifacts

The following table summarizes which roles participate in key agile ceremonies and own common artifacts. Use this as a quick reference when reviewing other OctoAcme process docs.

| Role | Sprint Planning | Daily Standup | Retrospective | Release Review | Key Artifacts |
|---|---|---|---|---|---|
| Project Manager | Facilitates | Optional | Facilitates | Attends | Project plan, risk register |
| Product Manager | Required | Optional | Attends | Attends | Roadmap, acceptance criteria |
| Developers | Required | Required | Required | Attends | Code, tests, technical docs |
| Scrum Master | Facilitates | Facilitates | Facilitates | Optional | Impediment log, team metrics |
| UX Designer/Researcher | Required | Optional | Attends | Attends | Wireframes, usability reports |
| Technical Writer | Optional | Optional | Optional | Attends | Process docs, user guides |
| Business Analyst | Required | Optional | Attends | Attends | Requirements, BRDs |
| Release Manager | Optional | Optional | Optional | Facilitates | Release checklist, runbook |
| QA/Testing | Required | Required | Required | Required | Test plans, defect reports |
| Stakeholders | Optional | — | Optional | Attends | Feedback, approvals |

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

## Scrum Master

### Role Summary
Scrum Masters facilitate the agile process, remove impediments, and help the team adopt continuous improvement practices. They act as a servant-leader, protecting the team's focus and fostering a healthy, high-performing environment.

### Responsibilities
- Coach team members on agile best practices and the Scrum framework
- Organize and facilitate standups, sprint planning, sprint reviews, and retrospectives
- Track and escalate impediments that block progress
- Shield the team from unplanned work and scope creep
- Monitor team health metrics and drive continuous improvement initiatives

### Goals
- Keep the team aligned, unblocked, and consistently delivering value
- Build a culture of transparency, inspection, and adaptation
- Improve predictability and reduce waste in the delivery process

### Typical Communication
- Daily facilitation of standups and async impediment updates
- Sprint ceremony facilitation notes and action items
- Team metrics dashboards (velocity, cycle time, burndown)

### Interactions
- **Project Managers**: Coordinates on timelines, dependencies, and escalation paths; the Scrum Master handles team-level process while the Project Manager owns broader delivery coordination.
- **Product Managers**: Aligns sprint goals with product priorities; ensures the backlog is refined and ready for planning.
- **Developers**: Serves as a coach and point of contact for process questions; removes blockers surfaced during standups.
- **QA/Testing**: Ensures testing activities are included in sprint planning and that quality gates are respected.
- **Stakeholders**: Communicates team capacity and shields the team from ad-hoc requests that bypass the backlog.

---

## UX Designer/Researcher

### Role Summary
UX Designers/Researchers design intuitive, user-centered experiences and conduct user research to inform product direction. They bridge the gap between user needs and engineering implementation.

### Responsibilities
- Plan and conduct user research sessions (interviews, surveys, usability tests)
- Create wireframes, mockups, and interactive prototypes
- Collaborate with Product Managers to translate research insights into acceptance criteria
- Facilitate design reviews and usability testing with real users
- Maintain a shared design system or component library where applicable

### Goals
- Deliver experiences that are intuitive, accessible, and aligned with user needs
- Reduce rework by validating design decisions early and often
- Increase confidence in product decisions through evidence-based research

### Typical Communication
- Design reviews and prototype walkthroughs with the team
- Research findings reports shared with Product Managers and Developers
- Annotated wireframes and design specs in shared collaboration tools

### Interactions
- **Project Managers**: Coordinates on design timelines and milestone deliverables to ensure design work is scheduled appropriately.
- **Product Managers**: Collaborates closely on requirements, user stories, and acceptance criteria to ensure design intent is captured.
- **Developers**: Partners on implementation feasibility, design handoffs, and verifying that the built product matches the intended experience.
- **QA/Testing**: Works with QA to define usability acceptance criteria and verify the user experience meets quality standards.
- **Stakeholders**: Presents research findings and design rationale to gain alignment and feedback before development begins.

---

## Technical Writer

### Role Summary
Technical Writers develop and maintain clear, accurate documentation for processes, APIs, and user-facing features. They ensure that institutional knowledge is accessible, well-organized, and up-to-date.

### Responsibilities
- Author and maintain internal documentation (process docs, runbooks, decision logs) and external content (user guides, API references, README files)
- Coordinate with subject matter experts (SMEs) to gather accurate information
- Review and standardize documentation contributions from other team members
- Maintain the structure and quality of the knowledge base (e.g., the `docs/` directory)
- Identify and close documentation gaps identified during audits or retrospectives

### Goals
- Ensure every team member and stakeholder can find accurate, up-to-date information quickly
- Reduce onboarding time by providing clear reference materials
- Lower support burden by proactively documenting common questions and edge cases

### Typical Communication
- Async collaboration with SMEs via comments and review cycles on documentation PRs
- Documentation status updates during sprint reviews or retrospectives
- Change logs and versioning notes for major documentation updates

### Interactions
- **Project Managers**: Coordinates on which process documents need to be created or updated each sprint; ensures project decisions are captured in the knowledge base.
- **Product Managers**: Collaborates to document product requirements, release notes, and user-facing feature descriptions accurately.
- **Developers**: Works closely with developers to document technical designs, API contracts, and codebase conventions.
- **QA/Testing**: Documents test plans, quality processes, and known issues to support team and end-user understanding.
- **Stakeholders**: Ensures stakeholder-facing content (reports, guides, release notes) is clear, accurate, and appropriately scoped.

---

## Business Analyst

### Role Summary
Business Analysts analyze organizational needs, translate ambiguous requirements into actionable specifications, and ensure that project deliverables align with business objectives. They act as a bridge between stakeholders and the delivery team.

### Responsibilities
- Gather, document, and validate functional and non-functional requirements
- Facilitate requirements workshops and stakeholder interviews
- Define and refine user stories, use cases, and acceptance criteria
- Assist in identifying and measuring success metrics and KPIs
- Analyze business processes and recommend improvements that align with project goals

### Goals
- Ensure project deliverables are traceable back to clearly defined business needs
- Reduce rework caused by misunderstood or incomplete requirements
- Support data-driven decision-making with well-defined success criteria

### Typical Communication
- Requirements documentation and business requirement documents (BRDs)
- Facilitation of stakeholder workshops and requirement walkthroughs
- Regular syncs with Product Managers and Project Managers to review scope changes

### Interactions
- **Project Managers**: Aligns on scope, schedule impact of requirement changes, and risk implications of open decisions.
- **Product Managers**: Partners closely on defining and prioritizing requirements; validates that product features map to documented business needs.
- **Developers**: Clarifies requirements during sprint planning and answers implementation questions to reduce ambiguity.
- **QA/Testing**: Provides requirements documentation and acceptance criteria to support test plan development.
- **Stakeholders**: Acts as the primary point of contact for requirements gathering; validates deliverables against stakeholder expectations.

---

## Release Manager

### Role Summary
Release Managers coordinate release planning, manage deployment execution, and communicate status with stakeholders to ensure reliable, low-risk delivery. They own the end-to-end release process and serve as the single point of contact for release-related decisions.

### Responsibilities
- Maintain and execute the release checklist and deployment runbook
- Facilitate go/no-go decisions with relevant team leads
- Communicate release status, timelines, and post-deployment outcomes to stakeholders
- Coordinate scheduling with Developers, QA, and infrastructure teams to align on readiness
- Organize and action post-release reviews and incident retrospectives

### Goals
- Deliver releases on schedule with minimal incidents or rollbacks
- Ensure clear communication and accountability throughout the release lifecycle
- Continuously improve the release process through post-release reviews

### Typical Communication
- Release status updates distributed to stakeholders before, during, and after each release
- Go/no-go meeting facilitation with documented decisions and sign-offs
- Post-release review reports shared with the broader team

### Interactions
- **Project Managers**: Coordinates on release timelines and dependencies to ensure delivery commitments are met.
- **Product Managers**: Aligns on release scope, feature flags, and stakeholder communication content.
- **Developers**: Confirms deployment readiness, coordinates rollback plans, and tracks open issues that may affect release go/no-go.
- **QA/Testing**: Validates that quality gates have been met before authorizing a release; coordinates final sign-off in the go/no-go process.
- **Stakeholders**: Communicates release timelines, expected impact, and post-deployment outcomes; manages expectations around scheduled maintenance windows.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The expanded set of roles (Scrum Master, UX Designer/Researcher, Technical Writer, Business Analyst, Release Manager) covers cross-functional responsibilities commonly found in modern software delivery teams.
- Refer to the ceremonies/artifacts mapping table at the top of this document when designing multi-role scenarios.

