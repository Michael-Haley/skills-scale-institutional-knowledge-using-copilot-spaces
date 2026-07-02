# OctoAcme Project Management Process Docs

## Purpose

This directory contains the comprehensive project management processes used by OctoAcme to run cross-functional projects. These documents centralize institutional knowledge, accelerate onboarding, and ensure consistent, repeatable project execution across the team.

## OctoAcme PM Approach

OctoAcme follows a structured, five-phase project lifecycle designed to balance planning rigor with iterative delivery. At its core, OctoAcme projects are guided by these principles:

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and continuous learning

### Key Workflows & Communication

OctoAcme maintains consistent communication rhythms to keep teams aligned: daily standups (15 min), weekly delivery syncs, and monthly stakeholder updates. Work flows through project boards with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done), and pull requests follow strict conventions (≤400 lines, automated CI/CD, at least one approval). Quality is embedded throughout—unit and integration tests, end-to-end smoke tests, security scanning, and manual QA when needed—ensuring every delivery meets acceptance criteria and Definition of Done standards.

### Roles & Clear Ownership

OctoAcme defines clear personas to ensure accountability: **Developers** design, build, and test features; **Product Managers** own the vision and prioritize based on customer value; **Project Managers** coordinate delivery, manage risks, and communicate across stakeholders; and **Stakeholders** provide inputs and approvals. Risks are tracked in a formal Risk Register reviewed weekly, with escalation flowing from team-level triage → PM → Product Lead → Sponsor.

---

## Process Documentation

OctoAcme's project lifecycle is divided into five phases, each with dedicated guidance:

### 1. Project Initiation

📖 [**Project Initiation Guide**](./octoacme-project-initiation.md)

Define initial steps to validate and authorize work, align stakeholders, and create a lightweight plan. Includes the Project One-pager template and decision gate checklist.

### 2. Project Planning

📖 [**Project Planning**](./octoacme-project-planning.md)

Turn an approved initiative into an actionable plan and backlog for delivery. Covers backlog creation, estimation, Definition of Done, and risk management.

### 3. Execution & Tracking

📖 [**Execution & Tracking**](./octoacme-execution-and-tracking.md)

Guidance for managing day-to-day execution, team rhythm, quality standards, and blocker escalation.

### 4. Release & Deployment

📖 [**Release & Deployment Guide**](./octoacme-release-and-deployment.md)

Standardize how OctoAcme releases features to production. Covers release types, pre-release requirements, and rollback procedures.

### 5. Retrospective & Continuous Improvement

📖 [**Retrospective & Continuous Improvement**](./octoacme-retrospective-and-continuous-improvement.md)

Capture learnings and convert them into actionable improvements after sprints, releases, or milestones.

---

## Cross-Cutting Resources

### Organizational Knowledge

📖 [**Project Management Overview**](./octoacme-project-management-overview.md)

Concise introduction to how OctoAcme runs projects. Includes core roles, key artifacts, and communication cadence.

📖 [**Roles & Personas**](./octoacme-roles-and-personas.md)

Definitions of typical roles (Developers, Product Managers, Project Managers) and their responsibilities, used to frame scenarios and interactions across OctoAcme projects.

### Risk & Communication

📖 [**Risk Management & Communication**](./octoacme-risks-and-communication.md)

How to identify, manage, and communicate risks and dependencies. Includes risk register templates, stakeholder communication strategies, and escalation paths.

---

## How to Use These Docs

- **Getting Started**: Start with the [Project Management Overview](./octoacme-project-management-overview.md) for a high-level view
- **Starting a New Project**: Follow the [Initiation Guide](./octoacme-project-initiation.md) to validate and authorize work
- **Planning & Delivery**: Use [Project Planning](./octoacme-project-planning.md) and [Execution & Tracking](./octoacme-execution-and-tracking.md) during active work
- **Releasing**: Check the [Release & Deployment Guide](./octoacme-release-and-deployment.md) before going to production
- **In-Flight Issues**: See [Risk Management & Communication](./octoacme-risks-and-communication.md) for escalation paths and stakeholder templates
- **Learning & Improvement**: Use [Retrospectives](./octoacme-retrospective-and-continuous-improvement.md) to capture improvements

---

## Contributing

See the issue template [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose updates or additions to these processes.
