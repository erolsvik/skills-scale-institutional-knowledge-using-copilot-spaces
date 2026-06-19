# OctoAcme Project Management Docs

This README provides a comprehensive overview of OctoAcme project management processes and links to detailed process documents in the `docs/` folder. Use this as your central entry point for understanding how OctoAcme runs projects and how to navigate our project management guidance.

## OctoAcme Project Management Process Overview

OctoAcme employs a structured, lifecycle-based approach to project management that prioritizes customer value, iterative delivery, and clear ownership. The organization follows a five-phase project lifecycle:

1. **Initiation**: Validate business need and align stakeholders by creating a lightweight one-pager that confirms the problem statement, success metrics, and key stakeholders. This phase includes a decision gate to move forward only when success metrics are clear and stakeholder agreement is confirmed.

2. **Planning**: Break approved initiatives into shippable increments by creating a prioritized backlog with clear acceptance criteria, estimating scope, and defining milestones and a Definition of Done. Planning also includes identifying cross-team dependencies and building a risk register.

3. **Execution & Tracking**: Build, test, and iterate using a project board, small pull requests, and CI automation. The team maintains a regular cadence of daily standups, weekly syncs, and demos to track progress and manage blockers. Quality assurance is embedded through unit tests, integration tests, security scanning, and code reviews.

4. **Release & Deployment**: Deploy features to production with reduced risk through pre-release checklists, smoke tests, and documented rollback plans. Release types include patches (hotfixes), minor releases (incremental features), and major releases (significant functionality changes).

5. **Close & Retrospective**: Capture learnings and convert them into actionable improvements. After each sprint or milestone, the team runs a retrospective to identify what went well, what could improve, and generates prioritized action items for continuous improvement.

Three core roles drive execution throughout this lifecycle:
- **Project Manager**: Coordinates schedules, manages risks and dependencies, facilitates key meetings, and ensures consistent communication with stakeholders.
- **Product Manager**: Defines outcomes, prioritizes the backlog, validates solutions through research and metrics, and measures success.
- **Developers**: Implement features, collaborate on design and testing, participate in estimation and planning, and help identify technical risks.

Communication and risk management are central to OctoAcme's execution model. The team maintains a regular cadence of **daily standups** (15 minutes), **weekly PM-PdM syncs**, **twice-weekly team standups**, and **monthly stakeholder updates**. Risks are tracked in a Risk Register with impact, likelihood, mitigation plans, and status, with escalation flowing from team-level triage through the PM, Product Lead, and Sponsor as needed.

## Process Documents

### Core Reference
- **[Project Management Overview](octoacme-project-management-overview.md)** — Concise intro to OctoAcme roles, key artifacts, project lifecycle, and communication cadence. Start here for a quick orientation.

### Lifecycle Phases

- **[Project Initiation Guide](octoacme-project-initiation.md)** — One-pager template, initiation checklist, decision gate, and minimum deliverables for validating and authorizing new work.

- **[Project Planning](octoacme-project-planning.md)** — Backlog item templates, planning activities, sprint/iteration planning, risk & dependency management, and planning checklist.

- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Team rhythm (standups and demos), GitHub Projects workflow, pull request conventions, quality & testing practices, reporting & metrics, blocker escalation, and execution checklist.

- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Release types, pre-release requirements, deployment checklist, rollback & incident playbook, and release notes template.

- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Running retrospectives, tracking improvements, action item template, and building a continuous improvement culture.

### Cross-Cutting Concerns

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Risk register template, risk lifecycle, stakeholder communication strategies, communication templates (weekly status, incident communication), and escalation paths.

- **[Roles & Personas](octoacme-roles-and-personas.md)** — Detailed role definitions, responsibilities, goals, and typical communication patterns for Developers, Product Managers, and Project Managers.

## How to Use

1. **For new team members**: Start with the [Project Management Overview](octoacme-project-management-overview.md) for a quick orientation, then review the [Roles & Personas](octoacme-roles-and-personas.md) document to understand your role and how it fits into the broader organization.

2. **For new projects**: Follow the lifecycle in order—use the [Project Initiation Guide](octoacme-project-initiation.md) to validate your idea, then move through [Project Planning](octoacme-project-planning.md), [Execution & Tracking](octoacme-execution-and-tracking.md), and [Release & Deployment](octoacme-release-and-deployment.md).

3. **For specific questions**: Use the table of contents above to jump directly to the process document that covers your question (e.g., "How do I run a retrospective?" → see [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)).

4. **Keep it current**: Link to this README from project READMEs and onboarding materials. Update the overview and links whenever process docs change.

## Quick Reference: Key Artifacts

- **Project Charter / One-pager**: Defined problem, goal, success metrics, stakeholders, timeline
- **Backlog & Sprint Plan**: Prioritized work with acceptance criteria and estimates
- **Risk Register**: ID, description, impact, likelihood, owner, mitigation, status
- **Project Board**: Backlog → Ready → In Progress → In Review → QA → Done
- **Definition of Done**: Clear acceptance criteria, unit & integration tests, security scan passing, code review approval
- **Release Notes**: Name, date, summary, changes, migration steps, known issues
- **Retrospective Notes**: What went well, what to improve, action items with owners and due dates
