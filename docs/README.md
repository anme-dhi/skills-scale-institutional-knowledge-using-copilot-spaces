# OctoAcme Project Management Docs

## Overview

OctoAcme's project management approach follows a lightweight, end-to-end lifecycle: **Initiation → Planning → Execution → Release → Close/Retrospective**. Work begins with a **Project One-pager/Charter** that clarifies the problem, SMART objective, success metrics, key stakeholders, rough milestones, initial risks, and resourcing needs. A decision gate confirms stakeholder alignment, priority, and team availability before moving into detailed planning, ensuring the team only invests deeply once outcomes and ownership are clear. Once approved, planning turns the initiative into an actionable backlog by running a kickoff, defining a **Definition of Done**, breaking work into shippable increments, estimating scope, and mapping milestones and releases. Backlog items include clear acceptance criteria, ownership, and links to relevant docs. Risks and dependencies are captured in a **Risk Register** (with impact/likelihood, owner, mitigation, and status) and reviewed continuously, with explicit escalation paths from team triage up through PM/Product Lead and, if needed, sponsor-level escalation.

Day-to-day execution relies on a consistent team rhythm and visible workflow management. OctoAcme uses a project board (e.g., GitHub Projects) with columns **Backlog → Ready → In Progress → In Review → QA → Done**, supported by **daily standups** for blockers/dependencies and a **weekly delivery sync** for progress and risk review, plus demos at the end of sprints or milestones. Roles are clearly defined: the **Project Manager (PM)** coordinates delivery, timelines, risks, and communications; the **Product Manager (PdM)** defines outcomes and prioritizes the backlog; **Developers** implement and test while collaborating on design and estimation; **QA/Testing** validates acceptance criteria; and **Stakeholders** provide input and approvals. Communication is structured around stakeholder groups, weekly and milestone-driven updates, a single source of truth for project status, standardized status templates, and a clear escalation ladder (team → PM → Product Lead → Sponsor) for unresolved blockers.

Quality and release practices emphasize small, reviewable changes and strong validation before production. PRs are kept **small (≤ ~400 lines when possible)**, include a linked issue and acceptance criteria, and require at least one approval before merging. OctoAcme expects appropriate **unit and integration testing**, **end-to-end smoke tests for critical flows**, and **security scanning in CI**, with manual QA where needed for feature acceptance. Releases follow a pre-release checklist that includes acceptance sign-off, passing CI/security checks, release notes, and a rollback/mitigation plan. Deployments proceed to staging first, then production, followed by post-deploy verification and stakeholder announcements. Learning is captured via structured **retrospectives** that produce a small number of owned, trackable improvement actions (each with an owner, due date, and success criteria) reviewed in the weekly PM sync and tracked in the backlog or issue tracker.

## Docs Index

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, core roles, key artifacts, and high-level lifecycle |
| [Project Initiation Guide](octoacme-project-initiation.md) | One-pager/Charter template, decision gate, and initiation checklist |
| [Project Planning](octoacme-project-planning.md) | Kickoff, backlog setup, Definition of Done, milestones, and release plan |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Board workflow, team rhythms, standup format, and blocker escalation |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk Register, communication cadences, status templates, and escalation paths |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Pre-release checklist, staging/production process, rollback, and release notes |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retro format, action-item tracking, and continuous improvement cycle |
| [Roles and Personas](octoacme-roles-and-personas.md) | Detailed responsibilities and goals for PM, PdM, Developers, QA, and Stakeholders |

For questions or feedback, [create an issue](../../../issues).
