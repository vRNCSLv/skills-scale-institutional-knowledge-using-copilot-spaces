# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation. This directory contains comprehensive guidance for running successful projects at OctoAcme, from initiation through retrospective.

## Quick Overview

OctoAcme uses a structured, iterative approach to project management based on these core principles:

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Core Roles

Our project teams include:

- **Project Manager (PM)**: Coordinates delivery, schedules, manages risks, and facilitates communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, and measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs, requirements, and approvals

For detailed role descriptions and responsibilities, see [Roles & Personas](#8-roles--personas).

## Project Lifecycle

Every OctoAcme project follows this structured lifecycle:

```
1. Initiation → 2. Planning → 3. Execution → 4. Release → 5. Retrospective
```

### Stage Overview

- **Initiation**: Validate business need, align stakeholders, create a Project One-pager
- **Planning**: Break work into shippable increments, identify dependencies, establish timelines
- **Execution**: Build, test, review, and iterate with daily standups and regular demos
- **Release**: Deploy to production with safety checks and rollback procedures
- **Retrospective**: Capture learnings and convert them into actionable improvements

## Documentation Guide

### [1. Project Management Overview](./octoacme-project-management-overview.md)

A concise introduction to OctoAcme's project management approach, core roles, key artifacts, and communication cadence.

**Key topics:**
- Principles and lifecycle overview
- Core roles and responsibilities
- Key artifacts and deliverables
- Communication cadence

---

### [2. Project Initiation](./octoacme-project-initiation.md)

Guidance for validating and authorizing new work, aligning stakeholders, and creating a lightweight plan.

**Key topics:**
- When to initiate a project
- Project One-pager template
- Minimum deliverables
- Go/no-go decision gate

---

### [3. Project Planning](./octoacme-project-planning.md)

How to turn an approved initiative into an actionable plan and backlog for delivery.

**Key topics:**
- Backlog creation and prioritization
- Scope estimation (T-shirt sizing, story points)
- Definition of Done
- Risk and dependency management
- Release planning and milestones

---

### [4. Execution & Tracking](./octoacme-execution-and-tracking.md)

Guidance for managing day-to-day execution, team rituals, and quality standards.

**Key topics:**
- Daily standups and weekly syncs
- Pull request workflows and code review practices
- Quality and testing standards
- Metrics and reporting
- Blocker escalation process

---

### [5. Risk Management & Communication](./octoacme-risks-and-communication.md)

How to identify, assess, and monitor risks, plus communication templates and escalation paths.

**Key topics:**
- Risk register and assessment
- Risk lifecycle (identify, assess, mitigate, monitor)
- Stakeholder communication strategies
- Communication templates (status updates, incidents)
- Escalation paths and procedures

---

### [6. Release & Deployment](./octoacme-release-and-deployment.md)

Standardized release processes covering release types, pre-release requirements, and deployment safety.

**Key topics:**
- Release types (patch, minor, major)
- Pre-release checklist and requirements
- Deployment and post-deploy verification
- Rollback and incident playbook
- Release notes template

---

### [7. Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

How to capture learnings after sprints or milestones and convert them into actionable improvements.

**Key topics:**
- Retrospective structure and timing
- What went well / could improve
- Action item tracking and follow-up
- Continuous improvement culture

---

### [8. Roles & Personas](./octoacme-roles-and-personas.md)

Definitions of core roles and their responsibilities within OctoAcme projects.

**Key topics:**
- Developer responsibilities and goals
- Product Manager responsibilities and goals
- Project Manager responsibilities and goals
- How personas are used in exercises and guidance

---

## Quick Reference

### Key Artifacts Across the Lifecycle

| Artifact | Stage | Owner | Purpose |
|----------|-------|-------|---------|
| Project One-pager | Initiation | PdM / PM | Define problem, goals, success metrics |
| Backlog & Acceptance Criteria | Planning | PdM | Specify what to build and acceptance standards |
| Sprint / Iteration Plan | Planning & Execution | PM / Team | Organize work into deliverable chunks |
| Risk Register | Planning, Execution, Release | PM | Track and mitigate risks |
| Pull Requests & Code Review | Execution | Developers | Maintain quality and knowledge sharing |
| Status Updates | Execution | PM | Keep stakeholders informed |
| Release Notes | Release | PM / PdM | Communicate changes and migration steps |
| Retrospective Notes | Retrospective | PM | Capture learnings and action items |

### Communication Cadence

- **Daily**: Standups (15 min) — progress, blockers, dependencies
- **Weekly**: PM + PdM sync — alignment and planning
- **Twice weekly**: Team standups (or as agreed)
- **Monthly**: Stakeholder updates — high-level progress
- **Ad-hoc**: Escalations and incident communications

### When to Escalate

Follow this escalation path for issues that block progress:

1. **Team-level**: Triage in daily standup
2. **PM-level**: PM escalates to Product Lead and dependent teams
3. **Sponsor-level**: For business-impacting issues

---

## How to Use These Docs

1. **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) to understand our approach.
2. **Starting a new project?** Follow the path: [Initiation](./octoacme-project-initiation.md) → [Planning](./octoacme-project-planning.md) → [Execution](./octoacme-execution-and-tracking.md).
3. **Looking for a specific process?** Use the [Documentation Guide](#documentation-guide) above to find the relevant doc.
4. **Need role clarity?** Check [Roles & Personas](./octoacme-roles-and-personas.md) for responsibilities and goals.

### Using These Docs in Copilot Spaces

- Keep these docs in your Copilot Space as a knowledge base for project management guidance
- Reference specific docs when creating issues or pull requests for process improvements
- Use the templates and checklists as starting points for your project artifacts
- Update docs collaboratively as your team refines processes

---

## Contributing to These Docs

Have a process improvement or clarification to suggest? 

1. Open an issue using the **[Add/Update Process Docs template](./../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)**
2. Describe the update needed and rationale
3. Include suggested content if you have it
4. Engage stakeholders for feedback
5. Submit a pull request with your changes

---

## Document Versions

All documents are maintained in this repository and versioned with the code. See commit history for changes and rationale.

Last updated: October 2026
