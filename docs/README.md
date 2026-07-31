# OctoAcme Project Management Docs

This README collects and links OctoAcme's project management process documents and provides a concise overview so contributors and stakeholders can quickly find the right guidance. Keep this file as the single source of truth for process links and a short summary of how we run projects.

OctoAcme runs projects with a principle-driven lifecycle that emphasizes customer value, iterative delivery, and clear ownership. Projects move through initiation, planning, execution & tracking, release & deployment, and close/retrospective stages. Key artifacts include a Project One‑pager, roadmap and release plan, sprint backlog, acceptance criteria and Definition of Done, a Risk Register, and retrospective action items to drive continuous improvement.

Planning and execution focus on small, shippable increments. Planning turns approved initiatives into a prioritized, estimated backlog with clear acceptance criteria and a documented Definition of Done. Execution uses a project board workflow (Backlog → Ready → In Progress → In Review → QA → Done), a disciplined PR process with CI and required approvals, and weekly tracking of risks and blockers. Releases follow pre‑release checks, staging smoke tests, an automated production pipeline when possible, and a rollback/incident playbook.

Quality and communication are built into the cadence: daily standups and sprint demos, weekly PM+PdM syncs, and monthly stakeholder updates. QA practices include unit/integration tests, smoke checks, manual QA when needed, and security scanning in CI. Retrospectives after sprints, releases, and incidents generate prioritized action items tracked in the backlog to improve the process continuously.

## Process summary (short)

- Initiation: validate the problem, define success metrics, identify stakeholders, produce a Project One‑pager.
- Planning: create a prioritized, estimated backlog; define Definition of Done; map release milestones.
- Execution & Tracking: use project boards and PR workflows; run CI and QA; track velocity, blockers, and escalations.
- Risks & Communication: maintain a Risk Register; assess, mitigate and monitor risks; follow stakeholder communication cadence.
- Release & Deployment: meet pre‑release gates, run staging smoke tests, deploy via pipelines and follow rollback/playbook for incidents.
- Retrospectives & Improvement: conduct retrospectives, create action items, and track improvements in the backlog.
- Roles & Personas: clear ownership — Product Manager (PdM), Project Manager (PM), Developers, QA, and Stakeholders.

## Links to docs

- docs/octoacme-project-management-overview.md — Project Management Overview
- docs/octoacme-project-initiation.md — Project Initiation Guide
- docs/octoacme-project-planning.md — Project Planning
- docs/octoacme-execution-and-tracking.md — Execution & Tracking
- docs/octoacme-risks-and-communication.md — Risk Management & Communication
- docs/octoacme-release-and-deployment.md — Release & Deployment Guide
- docs/octoacme-retrospective-and-continuous-improvement.md — Retrospective & Continuous Improvement
- docs/octoacme-roles-and-personas.md — Roles & Personas

## Acceptance criteria

- README added to docs/ with working relative links to each file
- Includes a brief project management processes summary aligned with existing docs
- Reviewed by PM or repo owner before merge
