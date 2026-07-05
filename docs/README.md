# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation hub. This folder contains guidance for running cross-functional projects using OctoAcme's proven processes and best practices.

## Quick Start

New to OctoAcme? Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand our core principles, roles, and key artifacts.

## Project Management Overview

OctoAcme operates a structured, lifecycle-based project management approach that emphasizes customer value, iterative delivery, and clear ownership. The process flows through five key phases: **Initiation**, where business needs are validated and stakeholders aligned around a Project One-pager; **Planning**, where work is broken into shippable increments with defined acceptance criteria and risk identification; **Execution**, where daily standups and weekly syncs track progress against a GitHub Projects board; **Release**, where standardized deployment checklists and rollback plans minimize production risk; and **Retrospectives**, where learnings drive continuous improvement. This structured lifecycle ensures that every project moves through clear decision gates before progressing to the next phase, with success metrics and stakeholder alignment established early.

The organization operates with clearly defined roles that foster cross-functional collaboration. Project Managers coordinate delivery, manage schedules, risks, and communications to keep teams aligned and on track. Product Managers own the product vision, prioritize the backlog, and measure outcomes through data-driven decisions. Developers implement features while maintaining high code quality through tests and design reviews. QA/Testing validates quality against acceptance criteria. This distributed ownership model encourages ownership and accountability while keeping communication channels clear and purposeful.

Communication flows through a consistent cadence: daily standups (15 minutes focused on blockers and dependencies), weekly delivery syncs between teams, and monthly stakeholder updates. Risk management is embedded throughout—risks are captured in a register during planning, assessed by impact and likelihood, and monitored weekly. Escalation follows a clear path from team-level to PM to Product Lead to Sponsor, ensuring issues surface early without creating bottlenecks. Quality and testing are built into execution from day one, with small pull requests (≤400 lines), automated CI testing and linting, and at least one approval required before merging.

## Documentation by Project Phase

### 1. Initiation
- [Project Initiation Guide](octoacme-project-initiation.md) — Validate business need, align stakeholders, and decide go/no-go for planning

### 2. Planning
- [Project Planning](octoacme-project-planning.md) — Break work into shippable increments, manage dependencies and risks, align timelines

### 3. Execution & Tracking
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Manage day-to-day execution, track progress, run quality gates, escalate blockers

### 4. Release & Deployment
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Standardize releases, manage rollbacks, and maintain observability

### 5. Retrospective & Continuous Improvement
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings, track action items, improve processes

## Cross-Cutting Concerns

- [Risk Management & Communication](octoacme-risks-and-communication.md) — Identify risks, manage dependencies, and keep stakeholders informed
- [OctoAcme Personas](octoacme-roles-and-personas.md) — Understand core roles, responsibilities, and communication patterns

## Core Principles

OctoAcme projects are guided by:
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named PM and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Key Artifacts

Every OctoAcme project maintains:
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Communication Cadence

- **Weekly sync** between PM + PdM
- **Twice-weekly standups** for delivery team (or as agreed)
- **Monthly stakeholder updates**
- **Ad-hoc escalations** as needed

## How to Use These Docs

- Keep the Project Charter updated in your project repo
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context
- Reference specific sections during project kickoff and planning phases
- Use the checklists in each document to ensure completeness at each phase
