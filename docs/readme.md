# OctoAcme Project Management Docs

Welcome! This README summarizes OctoAcme's project management practices and links to key process documents in this folder. Use this as your starting point for understanding how projects are run, who's involved, and where to find detailed guides.

## Summary of OctoAcme Project Management Processes

### Overview & Lifecycle

OctoAcme follows a structured, five-phase project lifecycle designed to deliver value iteratively while maintaining clear ownership and stakeholder alignment. The process spans **Initiation** (validating business need and stakeholder buy-in), **Planning** (breaking work into shippable increments with clear acceptance criteria), **Execution** (day-to-day delivery with regular rhythm and quality gates), **Release** (standardized deployment with risk mitigation), and **Close & Retrospective** (capturing learnings for continuous improvement). This lifecycle is underpinned by core principles of customer-first thinking, iterative delivery, clear ownership, data-informed decisions, and psychological safety. Each project is led by a named Project Manager (PM) who coordinates delivery and communications, working closely with a Product Manager (PdM) who owns outcomes and success metrics.

### Key Roles, Workflows & Team Rhythm

OctoAcme organizes around four primary personas: **Product Managers** define what to build and prioritize the roadmap; **Project Managers** coordinate schedules, risks, and communications; **Developers** implement features, write tests, and collaborate on design; and **QA/Testing** validates quality and acceptance criteria. The team operates on a predictable rhythm: daily standups (15 minutes) focus on progress and blockers, weekly delivery syncs review progress and flagged risks, and demos/reviews occur at sprint or milestone end. Work flows through a GitHub Projects board with columns for Backlog, Ready, In Progress, In Review, QA, and Done. Pull requests follow lightweight conventions—kept under 400 lines when possible, linked to issues with clear acceptance criteria, run through automated testing and linting, and require at least one approval before merging.

### Quality Assurance & Risk Management

Quality is embedded throughout execution via unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows before release, and security scanning in CI pipelines. Manual QA validates feature acceptance when needed. Risk management is formalized through a Risk Register (tracking ID, description, impact, probability, owner, and mitigation), maintained and reviewed during weekly syncs. Blockers are escalated through three levels: team-level triage in standups, PM escalation to Product Leads and dependent teams, and sponsor-level escalation for business-impacting issues. This ensures visibility and rapid resolution.

### Communication & Continuous Improvement

Stakeholder communication operates on a consistent cadence: weekly syncs between PM and PdM, twice-weekly standups for delivery teams, and monthly stakeholder updates, with ad-hoc escalations as needed. OctoAcme uses standard templates for weekly status updates (progress, next steps, risks, decisions needed) and incident communication to ensure transparency. After each sprint, release, or milestone, retrospectives (45–75 minutes) capture what went well, what could improve, and generate 2–3 prioritized action items with clear owners and timelines. These improvements feed back into the project backlog, creating a cycle of continuous refinement that strengthens both the processes and the team's ability to deliver value consistently.

## Process Docs Index

Get detailed guidance on each area of the OctoAcme project lifecycle and operations:

- **[Project Management Overview](./octoacme-project-management-overview.md)** — Introduction to OctoAcme principles, roles, artifacts, and communication cadence.
- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Steps to validate and authorize new work, align stakeholders, and create a lightweight plan.
- **[Project Planning](./octoacme-project-planning.md)** — Turn approved initiatives into actionable plans, backlogs, and release timelines.
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Manage day-to-day delivery, team rhythm, quality assurance, and blocker escalation.
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks, dependencies, and stakeholder updates.
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardized process for releasing features to production safely and observably.
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements.
- **[Roles and Personas](./octoacme-roles-and-personas.md)** — Detailed definitions of Project Managers, Product Managers, Developers, and QA/Testing roles and responsibilities.

## Keep This README Up to Date

As OctoAcme's processes evolve, please maintain this README to reflect updates and new documentation. Use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template to propose changes.
