# OctoAcme Project Management Docs

This folder contains the full set of process documents for OctoAcme's project management practices. Use this README as your starting point to discover and navigate all documentation.

## Overview

OctoAcme follows a structured, lifecycle-based approach to project management that spans five phases: **Initiation, Planning, Execution, Release, and Retrospective**. Every project begins with a lightweight one-pager that captures the problem statement, SMART objectives, success metrics, and stakeholder alignment before any planning work begins. Work is only approved to move forward once success metrics are clear, stakeholders agree on priority, and team availability is confirmed. This gate-based approach ensures that effort is never invested in poorly-defined initiatives, reducing waste and improving predictability across the portfolio.

The core team structure includes four key personas: the **Project Manager (PM)**, who coordinates delivery, schedules, risks, and communications; the **Product Manager (PdM)**, who owns the product vision and prioritizes the backlog; **Developers**, who implement and test features while contributing to design and risk identification; and **QA/Testing** roles that validate acceptance criteria. Planning activities translate approved initiatives into prioritized, estimated backlogs with a clear Definition of Done, a release plan, and a risk register that tracks impact, likelihood, owner, and mitigation strategy for each identified risk. Dependencies across teams are surfaced on the project board and escalated during weekly syncs.

Day-to-day execution and communication follows a disciplined team rhythm: 15-minute daily standups to surface blockers, weekly delivery syncs for progress and risk reviews, and sprint-end demos. Pull requests are kept small (≤400 lines where possible), must link to their originating issue with acceptance criteria, and require passing CI checks (including automated tests, linting, and security scanning) before review. Blocker escalation follows a three-level path — from team triage, to PM escalation to the Product Lead, to sponsor-level escalation for business-impacting issues. Stakeholders receive regular weekly or milestone-based status updates using a consistent template covering progress, next steps, risks, and decisions needed.

Quality assurance and continuous improvement are built into every stage of the lifecycle. Unit, integration, and end-to-end smoke tests are required for critical flows, with manual QA used for feature acceptance when needed. After each sprint, release, or incident, the team holds a structured retrospective (45–75 minutes) covering what went well, what could be improved, and 2–3 prioritized action items with clear owners and due dates. Those action items feed back into the project backlog and are reviewed in the weekly PM sync, creating a closed feedback loop that systematically converts team learnings into measurable process improvements over time.

---

## Process Documents

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Introduction to OctoAcme's approach, roles, key artifacts, and lifecycle |
| [Project Initiation](octoacme-project-initiation.md) | Steps to validate and authorize work, align stakeholders, and create a lightweight plan |
| [Project Planning](octoacme-project-planning.md) | Turning an approved initiative into an actionable plan and backlog |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Managing day-to-day execution and tracking progress toward milestones |
| [Risks & Communication](octoacme-risks-and-communication.md) | Identifying, managing, and communicating risks and dependencies |
| [Release & Deployment](octoacme-release-and-deployment.md) | Standardizing how OctoAcme releases features to production |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capturing learnings and converting them into actionable improvements |
| [Roles & Personas](octoacme-roles-and-personas.md) | Typical roles and responsibilities used across OctoAcme projects |
