# OctoAcme Project Management Docs

## Overview
Welcome to the OctoAcme project management documentation! Here you'll find complete, living guidance for how we plan, execute, and continuously improve projects using an iterative, stakeholder-aligned, and outcome-driven approach.

## Project Management Processes Summary

OctoAcme follows a structured, lifecycle-based approach to project management centered around five key phases: **Initiation, Planning, Execution, Release, and Retrospective**. The process prioritizes customer value through iterative delivery and data-informed decision-making. During initiation, teams validate business needs and establish success metrics via a lightweight Project One-pager, ensuring stakeholder alignment before proceeding. Planning transforms approved initiatives into actionable backlogs with clear acceptance criteria, dependencies, and release timelines. Execution is managed through daily standups, weekly syncs, and a project board with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done), while retrospectives capture learnings and drive continuous improvement after each sprint or milestone.

**Roles and Communication** are clearly defined to ensure accountability and alignment. The core team includes a Project Manager (who coordinates delivery and risk), a Product Manager (who defines outcomes and prioritizes), Developers (who implement features collaboratively), QA/Testing (who validate quality), and Stakeholders (who provide input and approvals). Communication flows through a structured cadence: daily standups for the delivery team, weekly syncs between PM and Product Lead, and monthly stakeholder updates. Risk escalation follows a three-level model—team triage, PM escalation to Product Lead, and sponsor-level escalation for business-impacting issues—ensuring transparency and rapid resolution of blockers.

**Quality Assurance and Release Management** are embedded throughout the lifecycle. Development follows small PR practices (≤400 lines), automated testing in CI, security scanning, and peer review requirements before merging. Pre-release verification includes acceptance criteria validation, passing CI checks, smoke testing, and documented rollback plans. The release process supports three types—patch, minor, and major—each with appropriate deployment checklists and post-deploy verification. Throughout execution, teams maintain a Risk Register tracking likelihood and impact, use weekly metrics and dashboards to monitor progress against success criteria, and conduct blameless post-incident retrospectives to continuously strengthen processes and reduce single-person dependency.

## Index of Docs

- [Project Management Overview](./octoacme-project-management-overview.md) — Introduction to OctoAcme's approach, core roles, key artifacts, and communication cadence.
- [Project Initiation Guide](./octoacme-project-initiation.md) — Validate business need, align stakeholders, and authorize work using a lightweight One-pager.
- [Project Planning](./octoacme-project-planning.md) — Break work into shippable increments, define dependencies, risks, and release timelines.
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Manage day-to-day delivery using standups, project boards, PR workflows, and quality gates.
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Identify, manage, and communicate risks; escalate efficiently; keep stakeholders informed.
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Standardized checklists and playbooks for safe, transparent, verifiable releases.
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and convert them into actionable improvements.
- [Roles and Personas](./octoacme-roles-and-personas.md) — Define typical roles (PM, PdM, Developers, QA, Stakeholders) and their responsibilities.

## How to Use These Docs

- **New to OctoAcme?** Start with [Project Management Overview](./octoacme-project-management-overview.md) for a quick introduction to our approach and roles.
- **Starting a new project?** Follow the sequence: Initiation → Planning → Execution → Release → Retrospective.
- **Joining a project mid-cycle?** Review the relevant phase docs and check your project's README or charter for context.
- **Continuous improvement?** Use the [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) guide to run sessions and track action items.

## Keeping Docs Current

These are **living documents**. As OctoAcme processes evolve, update the relevant docs, test changes in a pilot, and communicate updates to the team. Use pull requests and issues to propose changes and gather feedback.
