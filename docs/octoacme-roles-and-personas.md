# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Additional / Cross-functional Personas (proposed additions)

These roles clarify ownership for cross-cutting concerns that affect delivery, release, security, UX, and data-driven decisions. Add the following entries to improve clarity and accountability.

### Delivery Lead
- Responsibilities: Oversee day-to-day delivery cadence, remove impediments, ensure backlog hygiene, coordinate cross-team delivery across multiple projects.
- Interaction with existing roles: Works closely with the Project Manager to translate roadmap and milestones into sprint-level execution. Coordinates with Engineering Managers and QA to align sprint commitments and capacity. Escalates scheduling conflicts to the PM or Product Lead.

### Engineering Manager
- Responsibilities: People management, career development, technical roadmap alignment, capacity planning, and technical risk identification.
- Interaction with existing roles: Coordinates resource allocation with Project Managers and Product Managers. Partners with Developers on technical designs and trade-offs. Works with Delivery Lead to balance team capacity across concurrent initiatives.

### Release Engineer
- Responsibilities: Owns release pipelines, deployment automation, rollback plans, release validation scripts, and release runbooks.
- Interaction with existing roles: Collaborates with Developers, QA, and SRE/Operations to automate releases, define pre/post-deploy checks, and reduce manual steps. Works with PM to schedule release windows and with Product Lead to validate release readiness.

### Security/Ops Liaison
- Responsibilities: Ensures security and compliance checks are integrated into CI/CD and delivery workflows, coordinates incident response and post-incident steps.
- Interaction with existing roles: Works with Release Engineer and Developers to add automated scans and gating. Escalates security risks to Product Lead and Security on-call and advises the PM on mitigation timelines.

### UX Researcher / Designer
- Responsibilities: Plans and runs user research, defines UX acceptance criteria, creates design specs and usability validations.
- Interaction with existing roles: Partners with Product Managers to define user needs and acceptance criteria; collaborates with Developers to ensure designs are implementable; participates in reviews and demos to validate experience quality.

### Data Analyst
- Responsibilities: Defines success metrics, builds dashboards and telemetry, validates experiment and metric instrumentation, and produces post-release impact analyses.
- Interaction with existing roles: Works with Product Managers to operationalize success metrics and with Developers to ensure correct instrumentation. Provides PMs and stakeholders with data needed for decisions.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When adding a new persona, include: one-paragraph summary, responsibilities list, and a short "Interaction with other roles" note (see checklist).

---
