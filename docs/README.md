# OctoAcme Project Management Docs

## Overview

OctoAcme uses a customer-first, iterative project management approach with clear ownership, measurable outcomes, and continuous improvement. The process covers the full lifecycle: initiating and authorizing work, planning scope and delivery, executing and tracking progress, managing risks and communication, releasing and deploying safely, and capturing lessons through retrospectives. Core roles include Project Managers, Product Managers, Developers, QA/Testing, and stakeholders.

## Documentation

- [Project Management Overview](octoacme-project-management-overview.md) — Principles, roles, lifecycle, artifacts, and communication cadence.
- [Project Initiation](octoacme-project-initiation.md) — Business need, stakeholders, success criteria, risks, resources, and the decision gate for planning.
- [Project Planning](octoacme-project-planning.md) — Backlog creation, prioritization, estimation, Definition of Done, dependencies, risks, and release planning.
- [Execution and Tracking](octoacme-execution-and-tracking.md) — Team rhythm, project-board workflow, pull requests, quality practices, metrics, and blocker escalation.
- [Risk Management and Communication](octoacme-risks-and-communication.md) — Risk register, risk lifecycle, stakeholder updates, incident communication, and escalation paths.
- [Release and Deployment](octoacme-release-and-deployment.md) — Release types, pre-release requirements, deployment checklist, rollback, incident response, and release notes.
- [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Retrospective structure, action-item tracking, and improvement practices.
- [Roles and Personas](octoacme-roles-and-personas.md) — Responsibilities, goals, and communication patterns for key project roles.

## Project Management Process Summary

Projects begin by validating the business need and defining measurable outcomes, stakeholders, a timeline, risks, dependencies, and resource needs. Once approved, planning breaks the work into prioritized backlog items with acceptance criteria, estimates, owners, a Definition of Done, and a release plan.

During execution, the team uses a project board with stages such as Backlog, Ready, In Progress, In Review, QA, and Done. Standups focus on progress, blockers, and dependencies, while weekly delivery or PM/Product Manager syncs review progress and risks. Pull requests should be small where possible, link to the relevant issue, include acceptance criteria, and receive the required approval. Quality is reinforced through unit, integration, and smoke tests, CI checks for tests and linting, security scanning, and manual QA when needed.

Project Managers coordinate delivery, schedules, risks, dependencies, documentation, and stakeholder communication. Product Managers define outcomes, prioritize the backlog, and measure success. Developers implement and test solutions, QA/Testing validates quality and acceptance criteria, and stakeholders provide input and approvals. Risks are recorded with impact, likelihood, owner, mitigation, and status, with clear escalation from the team to the PM, Product Lead, and sponsor.

Before release, acceptance criteria must be met, CI and security checks must pass, release notes and rollback plans must be prepared, and smoke tests must be ready. Deployments include staging validation, production verification, and stakeholder notification. After each sprint, release, milestone, or incident, retrospectives capture lessons learned and create owned, time-bound improvement actions that are tracked in the backlog or issues.

## How to Use These Documents

Start with the [Project Management Overview](octoacme-project-management-overview.md), then use the lifecycle-specific guides as the project progresses. Keep project-specific plans, risks, decisions, status updates, release information, and retrospective actions current in the repository or project workspace.
