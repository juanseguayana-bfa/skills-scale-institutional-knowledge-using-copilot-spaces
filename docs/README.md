# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation hub. This README serves as your starting point for understanding how OctoAcme plans, executes, and continuously improves its projects.

---

## About OctoAcme's Approach

OctoAcme operates a structured, lifecycle-based project management approach grounded in clear ownership, iterative delivery, and data-informed decision-making. Our core principles are:

- **Customer-first** – prioritize customer value and usability in every decision.
- **Iterative delivery** – ship small, testable increments rather than large, infrequent releases.
- **Clear ownership** – every project has a named Project Manager (PM) and Product Lead accountable for outcomes.
- **Data-informed decisions** – measure impact and iterate based on evidence.
- **Psychological safety** – encourage open feedback and continuous learning at every level.

---

## Project Management Process Overview

OctoAcme projects move through five lifecycle phases, each with defined entry criteria, activities, and decision gates:

1. **Initiation** – Validate the business need and align stakeholders. Key output: a lightweight One-pager / Project Charter that captures the problem statement, success metrics, and high-level timeline.
2. **Planning** – Define scope, resources, and milestones. Break work into shippable increments, populate the prioritized backlog, and identify risks and dependencies early.
3. **Execution & Tracking** – Deliver features in iterative sprints. Teams run twice-weekly standups, maintain a Definition of Done, follow a structured PR workflow (≤ 400-line PRs, automated CI, at least one approval), and continuously monitor risks.
4. **Release & Deployment** – Execute pre-flight checks, run smoke tests, deploy through the standard release pipeline, and communicate rollout status to stakeholders. Rollback plans are prepared before every release.
5. **Close & Retrospective** – Capture learnings in a structured retro, convert action items into backlog tickets, and measure the impact of improvements over time.

Cross-cutting the full lifecycle, communication is managed through a regular cadence: weekly PM–PdM syncs, twice-weekly team standups, and monthly stakeholder updates, with a clear three-level escalation path (team → PM → Product Lead → Sponsor) for risks and blockers.

---

## Documentation Index

### 📋 Overview & Foundations

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, core roles, key artifacts, lifecycle summary, and communication cadence |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed responsibilities and goals for each role |
| [Role Alignment and Handoffs](octoacme-role-alignment-and-handoffs.md) | RACI-lite template plus kickoff/release handoff checklists for clearer accountability |

### 🚀 Lifecycle Phases

| Phase | Document |
|---|---|
| Initiation | [Project Initiation](octoacme-project-initiation.md) |
| Planning | [Project Planning](octoacme-project-planning.md) |
| Execution & Tracking | [Execution and Tracking](octoacme-execution-and-tracking.md) |
| Release & Deployment | [Release and Deployment](octoacme-release-and-deployment.md) |
| Close & Retrospective | [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) |

### ⚠️ Risks & Communication

| Document | Description |
|---|---|
| [Risks and Communication](octoacme-risks-and-communication.md) | Risk identification, assessment, monitoring, escalation paths, and communication templates |

---

## Quick Reference: Core Roles

| Role | Responsibilities |
|---|---|
| **Project Manager (PM)** | Coordinates delivery schedules, manages risks and dependencies, facilitates meetings, and ensures consistent status reporting |
| **Product Manager (PdM)** | Owns product vision, prioritizes the backlog, defines success metrics, and aligns stakeholders on trade-offs |
| **Developers** | Implement features, write tests and docs, participate in design and code reviews, and help identify technical risks |

For full role definitions and persona guidance, see [Roles & Personas](octoacme-roles-and-personas.md).
