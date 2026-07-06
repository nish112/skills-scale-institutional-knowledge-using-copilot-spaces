# OctoAcme Project Management Docs

This README gathers the OctoAcme program management process documents in one place and provides a short summary of the processes we follow. It is intended as a single entry point for teammates to quickly find the canonical process documents and understand the core workflows, roles, and quality practices used across OctoAcme projects.

## Overview

OctoAcme follows a clear, stage-gated lifecycle from initiation through planning, execution, release, and retrospective. Work begins with a Project One-pager that defines the problem, objectives, success metrics, stakeholders, and a high-level timeline to decide whether to move into planning. Planning produces a prioritized backlog with acceptance criteria, estimates, a Definition of Done, and a release/milestone map to ensure work is clear and actionable before execution.

During execution the delivery team uses a project board with columns such as Backlog, Ready, In Progress, In Review, QA, and Done. The pull request workflow emphasizes small, focused PRs, linked issues with acceptance criteria, and automated CI checks before review. Daily standups and weekly delivery syncs keep progress and blockers visible; demos at the end of sprints/milestones validate work against acceptance criteria and stakeholder expectations.

## Roles & Communication

Roles are explicit and distributed: Project Managers coordinate delivery, risk, schedules, and cross-team communication; Product Managers define vision, prioritize the backlog, and measure outcomes; Developers implement features and maintain tests; QA validates acceptance and quality; and Stakeholders provide inputs and approvals. Communication is structured: short daily standups, weekly PM+PdM alignment, a weekly delivery sync, and ad-hoc escalations following defined paths (team → PM → Product Lead → Sponsor). Use a single source of truth (project README or release doc) for status and stakeholder updates.

## Quality & Risk Practices

Quality is embedded into the workflow: unit and integration tests, CI-driven security scans, and end-to-end smoke checks for critical flows are required. Releases follow pre-release requirements (passing CI/security scans, release notes, rollback plan), a deployment checklist (staging smoke tests, automated production deploy where possible, post-deploy verification), and an incident playbook for rollbacks. Risk management is lightweight and continuous; maintain a risk register (ID, impact, likelihood, owner, mitigation) and review it regularly. Retrospectives turn learnings into prioritized action items with owners and due dates to drive continuous improvement.

## Links to process documents
- [Project Management Overview](docs/octoacme-project-management-overview.md) — concise intro to roles, principles, and lifecycle.
- [Project Initiation Guide](docs/octoacme-project-initiation.md) — one-pager, kickoff criteria, and initiation checklist.
- [Project Planning](docs/octoacme-project-planning.md) — backlog templates, planning activities, and risk/dependency handling.
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md) — day-to-day workflows, PR conventions, CI, and blocker escalation.
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md) — risk register, communication templates, and escalation paths.
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md) — deployment checklist, rollback playbook, and release notes template.
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md) — retrospective structure and action tracking.
- [Roles & Personas](docs/octoacme-roles-and-personas.md) — role summaries and responsibilities used across process docs.

## Suggested filename & location
- docs/README.md

## Notes
- Keep each summary short and link to the detailed doc for more information.
- Update this README whenever new process docs are added or existing ones are substantially changed.
