# OctoAcme Project Management Docs

## About
This folder contains OctoAcme’s program-level project management guidance — concise, practical artifacts that help teams start, plan, deliver, and learn from cross-functional work. Use this README as the primary entry point for project charters, workflows, escalation paths, release guidance, and role definitions.

## Project lifecycle & key workflows
OctoAcme follows a clear lifecycle: Initiation → Planning → Execution → Release → Retrospective. Projects start with a Project One-pager to validate objectives and success metrics before moving into planning. Planning decomposes approved work into shippable increments, captures dependencies and risks in a Risk Register, and produces a prioritized backlog and release plan. Execution is tracked on a project board with a canonical workflow (Backlog → Ready → In Progress → In Review → QA → Done), enforced pull-request practices, CI gating, and short iterations to improve feedback velocity. Releases follow a checklist with pre-release smoke tests, rollback plans, and stakeholder announcements to reduce risk.

## Personas & responsibilities
Roles are explicit so ownership and handoffs are clear. Project Managers (PMs) coordinate delivery, schedules, risk registers, and stakeholder communications. Product Managers (PdMs) define outcomes, prioritize the backlog, and measure success. Developers implement and test changes, and QA validates acceptance criteria. These roles meet regularly through agreed cadences to keep progress aligned and visible: daily standups for the delivery team, weekly delivery syncs, PM+PdM alignment meetings, and monthly stakeholder updates.

## Communication & quality assurance
Communication is templated and discoverable: weekly status templates, incident summaries, and a single source of truth (project README or release doc) ensure clear stakeholder updates. QA is layered: automated unit, integration, and security checks run in CI, end-to-end smoke tests run before releases, and targeted manual acceptance testing is used when necessary. Retrospectives capture learnings and convert them into tracked action items to continuously improve processes and outcomes.

## Process documents
- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md)
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](docs/octoacme-roles-and-personas.md)
