# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation! This README provides an overview and quick access to all core process docs that guide project planning, execution, and delivery.

## Project Management Process Summary

OctoAcme operates on a **customer-first, iterative delivery model** with clear ownership and data-driven decision-making. The organization follows a structured five-phase lifecycle: Initiation → Planning → Execution → Release → Close & Retrospective. Each project is guided by a **Project Manager (PM)** who coordinates delivery and a **Product Manager (PdM)** who owns outcomes and success metrics. This dual-role structure ensures both operational efficiency and customer value alignment. The approach emphasizes psychological safety, encouraging teams to surface blockers early and learn from outcomes through blameless retrospectives.

### Workflow & Execution Discipline

Projects begin with a lightweight **Project One-pager** that validates business need, identifies stakeholders, and defines measurable success criteria—serving as the decision gate to move into planning. Once approved, the team conducts a **kickoff meeting** to create a prioritized backlog with clear acceptance criteria, estimate scope using T-shirt sizing or story points, and define a **Definition of Done**. Execution follows an iterative sprint model with **daily standups** (15 min), **weekly delivery syncs**, and structured **pull request workflows** emphasizing small PRs (≤400 lines), automated CI/CD testing, and mandatory code reviews. The team tracks progress using **GitHub Projects** with columns (Backlog, Ready, In Progress, In Review, QA, Done) and manages risks and dependencies through a **Risk Register** updated weekly, with escalation paths from team-level → PM → Product Lead → Sponsor.

### Quality Assurance & Communication

Quality is embedded throughout the lifecycle via **unit tests** for new logic, **integration tests** where applicable, **end-to-end smoke tests** for critical flows, security scanning in CI, and manual QA for feature acceptance. Releases follow a standardized **pre-release checklist** including smoke tests on staging, passing security scans, and documented rollback plans. Communication is structured and transparent: **weekly status templates** capture progress, blockers, and decisions; **stakeholder updates** occur monthly or at milestones; and **incident communication** follows a triage-action-timeline format. After each sprint or milestone, the team conducts a **45–75 minute retrospective** to capture learnings, prioritize 2–3 action items, and continuously improve processes—ensuring accountability by tracking improvements in the backlog with clear owners and due dates.

---

## Core Process Docs

Quick links to all OctoAcme project management process documents:

- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, core roles, key artifacts, and lifecycle overview.

- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Steps to validate and authorize work, align stakeholders, and create a lightweight plan with a Project One-pager template.

- **[Project Planning](./octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and backlog, including backlog item templates, sprint planning, and risk management.

- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Guidance for managing day-to-day execution, team rhythm, workflows, quality gates, and blocker escalation.

- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — How to identify, assess, and mitigate risks; stakeholder communication templates; and escalation paths.

- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardize releases by release type, pre-release requirements, deployment checklist, and rollback procedures.

- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Structure for capturing learnings, running retrospectives, and converting action items into backlog improvements.

- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Definitions of core roles (Developers, Product Managers, Project Managers) and their responsibilities and goals.

---

## How to Use These Docs

- **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) for a high-level orientation.
- **Starting a new project?** Follow the [Initiation Guide](./octoacme-project-initiation.md) to validate and plan your work.
- **Managing execution?** Reference [Execution & Tracking](./octoacme-execution-and-tracking.md) and [Risk Management & Communication](./octoacme-risks-and-communication.md) for daily and weekly workflows.
- **Preparing to release?** Check the [Release & Deployment Guide](./octoacme-release-and-deployment.md) for pre-release and deployment steps.
- **Running retrospectives?** Use the [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) guide to capture and act on learnings.

Keep these docs updated as processes evolve. For process improvements or clarifications, open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
