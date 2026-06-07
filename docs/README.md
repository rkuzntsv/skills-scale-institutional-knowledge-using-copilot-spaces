# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation hub. This folder contains comprehensive guides on how OctoAcme structures and executes projects, from initiation through retrospective and continuous improvement.

## Overview of Project Management Processes

OctoAcme follows a structured, iterative approach to project management that emphasizes customer value, clear ownership, and continuous learning. Our methodology is built on five core principles: **customer-first prioritization**, **iterative delivery** of small testable increments, **clear ownership** with named Project Managers and Product Leads, **data-informed decision-making**, and **psychological safety** to encourage feedback and learning.

### Core Workflows

**Project Lifecycle**: OctoAcme projects progress through five phases—**Initiation** (establishing problem statements and stakeholders), **Planning** (defining scope, resources, and dependencies), **Execution** (building, testing, and iterating), **Release** (deployment and verification), and **Close & Retrospective** (capturing learnings). Throughout this lifecycle, teams maintain key artifacts including project charters, roadmaps, sprint backlogs, acceptance criteria, risk registers, and retrospective notes.

**Execution Model**: Daily standups focus on progress and blockers, weekly delivery syncs track milestone progress, and sprint demos showcase completed work. Development follows a pull request workflow emphasizing small PRs (≤400 lines), automated testing and linting in CI, and at least one approval before merging.

### Key Roles and Personas

OctoAcme defines three primary roles with clear accountability:

- **Product Managers** define what should be built, prioritize the backlog, and measure customer impact through data and user research.
- **Project Managers** coordinate delivery, manage schedules and risks, facilitate planning meetings, and maintain stakeholder alignment through regular status reporting.
- **Developers** implement features, write tests, participate in code reviews, and identify technical risks.

Additional roles include QA/Testing professionals who validate quality against acceptance criteria, and Stakeholders who provide inputs and approvals.

### Communication and Quality Assurance

**Communication Cadence**: Weekly syncs between PM and Product Manager, twice-weekly standups for the delivery team, monthly stakeholder updates, and ad-hoc escalations. Status updates follow a consistent template covering progress, next steps, risks, and decisions needed.

**Quality Practices**: Quality is embedded throughout execution via a Definition of Done that includes unit tests, integration tests, end-to-end smoke tests for critical flows, and security scanning in CI. Success is measured through velocity tracking, burndown monitoring, and dashboard metrics tracking errors, latency, and usage.

---

## Documentation Index

### Getting Started
- **[Project Management Overview](./octoacme-project-management-overview.md)** — Concise introduction to OctoAcme's approach, principles, core roles, key artifacts, and communication cadence.

### Project Phases

- **[Project Initiation](./octoacme-project-initiation.md)** — How to define the problem, identify stakeholders, and establish high-level timelines for new projects.

- **[Project Planning](./octoacme-project-planning.md)** — Breaking work into shippable increments, creating prioritized backlogs with acceptance criteria, estimating scope, defining Definition of Done, and identifying dependencies.

- **[Execution and Tracking](./octoacme-execution-and-tracking.md)** — Managing day-to-day execution through daily standups, weekly syncs, PR workflows, quality gates, and progress tracking.

- **[Risks and Communication](./octoacme-risks-and-communication.md)** — Identifying, assessing, and mitigating risks; maintaining a risk register; managing stakeholder communication; and escalation paths.

- **[Release and Deployment](./octoacme-release-and-deployment.md)** — Preparing for release, deployment procedures, verification steps, and stakeholder announcements.

- **[Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capturing learnings, identifying improvements, and planning next steps after project completion.

### Reference
- **[Roles and Personas](./octoacme-roles-and-personas.md)** — Detailed descriptions of personas used across OctoAcme projects, including responsibilities, goals, and typical communication patterns for Developers, Product Managers, and Project Managers.

---

## Quick Reference: Key Artifacts

- **Project Charter / One-pager** — Defines problem, solution, success metrics, stakeholders, and timeline
- **Roadmap and Release Plan** — Long-term vision and milestone-based delivery schedule
- **Sprint/Iteration Backlog** — Prioritized list of work items with acceptance criteria
- **Definition of Done (DoD)** — Shared understanding of when work is complete
- **Risk Register** — Tracked risks with impact, likelihood, owner, and mitigation plans
- **Retrospective Notes** — Learnings and action items for continuous improvement

---

## How to Use These Docs

1. **New to OctoAcme?** Start with [Project Management Overview](./octoacme-project-management-overview.md) for a high-level introduction.

2. **Starting a new project?** Follow the [Project Initiation](./octoacme-project-initiation.md) and [Project Planning](./octoacme-project-planning.md) guides.

3. **In the thick of delivery?** Reference [Execution and Tracking](./octoacme-execution-and-tracking.md) and [Risks and Communication](./octoacme-risks-and-communication.md).

4. **Need to understand roles?** See [Roles and Personas](./octoacme-roles-and-personas.md) for detailed persona definitions and responsibilities.

5. **Integrating with Copilot Spaces?** Add process-specific docs to `.copilot/` if you want Copilot to use them as context when providing guidance.

---

## Questions or Feedback?

These docs evolve with OctoAcme's practices. If you find gaps, unclear sections, or want to propose improvements, please open an issue or submit a pull request to keep our documentation current and useful.
