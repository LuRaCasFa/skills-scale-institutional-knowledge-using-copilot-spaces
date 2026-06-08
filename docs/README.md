# OctoAcme Project Management Docs

## Overview
Welcome to the OctoAcme project management documentation! Here you'll find complete, living guidance for how we plan, execute, and continuously improve projects using an iterative, stakeholder-aligned, and outcome-driven approach.

This documentation serves as the single source of truth for OctoAcme's project management processes, helping team members at all levels understand roles, workflows, and best practices.

## Project Management Processes Summary

OctoAcme's approach includes standardized initiation, planning, execution, risk management, release, and learning processes designed around these core principles:

- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments regularly
- **Clear ownership**: Each project has named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning across the team

### Process Lifecycle

```
Initiation → Planning → Execution & Tracking → Release & Deployment → Retrospective & Improvement
```

#### 1. **Initiation**
Validate problems, define scope, align stakeholders, and make a go/no-go decision for planning.
- Minimum deliverables: One-pager, stakeholder list, timeline, risk list, resource needs
- Key output: Project Charter with clear success metrics

#### 2. **Planning**
Turn approved ideas into actionable backlogs with clear estimates, milestones, dependencies, and Definition of Done.
- Break work into shippable increments with acceptance criteria
- Identify cross-team dependencies and integration points
- Create release plan and milestone map

#### 3. **Execution & Tracking**
Execute daily standups, manage project boards, follow PR conventions, maintain quality gates, and demo progress.
- Daily standups (15 min), weekly delivery syncs, regular demos
- Small PRs (≤400 lines), automated testing in CI, security scanning, peer review
- Unit tests, integration tests, and smoke tests before release

#### 4. **Risk & Communication**
Identify, assess, and mitigate risks; communicate status to stakeholders; escalate blockers efficiently.
- Maintain a Risk Register with ID, description, impact, likelihood, owner, mitigation
- Weekly status updates to stakeholders with progress, risks, and asks
- Three-level escalation: Team → PM → Product Lead → Sponsor

#### 5. **Release & Deployment**
Execute standardized checklists and playbooks for safe, observable, and transparent releases to PRE and PROD environments.
- Pre-release: all PRs merged, CI passing, security scans clean, release notes drafted
- Deployment: staging validation, production deploy, post-deploy verification
- Rollback playbook for critical issues; incident response and blameless retrospectives

#### 6. **Retrospective & Improvement**
Capture learnings after each sprint or milestone; convert feedback into actionable improvements.
- 45–75 min timeboxed sessions with team
- Structured: What went well → What to improve → Action items with owners and due dates
- Track improvements and measure impact

## Core Roles

| Role | Focus | Key Activities |
|------|-------|-----------------|
| **Project Manager (PM)** | Coordination & Delivery | Manages schedules, risks, dependencies, communications; removes blockers |
| **Product Manager (PdM)** | Outcomes & Prioritization | Defines success metrics, prioritizes backlog, validates with users |
| **Developers** | Implementation & Quality | Implement features, write tests, participate in design reviews, estimate work |
| **QA/Testing** | Quality Assurance | Validate acceptance criteria, automate tests, enforce quality gates |
| **Stakeholders** | Oversight & Approval | Provide inputs, approvals, business alignment, funding decisions |

See [Roles and Personas](./octoacme-roles-and-personas.md) for detailed responsibilities and communication patterns.

## Communication Cadence

- **Daily**: Standups (15 min) — progress, blockers, dependencies
- **Twice-weekly**: Delivery standups for extended teams
- **Weekly**: PM + PdM sync, risk register review, stakeholder updates
- **Monthly**: Executive stakeholder briefings and roadmap updates
- **Ad-hoc**: Escalations, decision gates, incident response

## Key Artifacts

- **Project Charter / One-pager**: Problem, goal, success metrics, stakeholders, timeline, risks, resources
- **Roadmap & Release Plan**: Milestones, dependencies, release schedule
- **Sprint/Iteration Backlog**: Prioritized, estimated, assigned work with acceptance criteria
- **Acceptance Criteria & Definition of Done**: Clear quality and completion standards
- **Risk Register**: Identified, assessed, and mitigated risks with owners and mitigation plans
- **Retrospective Notes & Action Items**: Learnings and process improvements with tracking

## Index of Docs

### Getting Started
- **[Project Management Overview](./octoacme-project-management-overview.md)**
  - High-level introduction to OctoAcme's approach, core roles, key artifacts, and lifecycle

### Phase-by-Phase Guidance
- **[Project Initiation Guide](./octoacme-project-initiation.md)**
  - How to validate ideas, align stakeholders, and decide whether to move into planning
  - Includes minimum deliverables, One-pager template, and decision gates

- **[Project Planning](./octoacme-project-planning.md)**
  - How to break work into shippable increments, estimate scope, identify dependencies
  - Includes backlog item template, sprint planning, and release planning guidance

- **[Execution & Tracking](./octoacme-execution-and-tracking.md)**
  - Daily standups, project board workflow, PR conventions, quality & testing standards
  - Includes reporting, metrics, blocker escalation, and execution checklist

- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)**
  - Pre-release requirements, deployment checklist, rollback and incident playbooks
  - Includes release notes template and deployment verification steps

### Cross-Cutting Guidance
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)**
  - Risk lifecycle and register management
  - Stakeholder communication templates, incident communication, and escalation paths

- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)**
  - How to run retrospectives, track improvements, and build a culture of learning
  - Action item template and guidance on measuring impact

### Reference
- **[Roles and Personas](./octoacme-roles-and-personas.md)**
  - Detailed definitions of typical roles, responsibilities, goals, and communication patterns
  - Used as persona prompts in exercises and team interactions

## How to Use These Docs

1. **New to OctoAcme?** Start with [Project Management Overview](./octoacme-project-management-overview.md)
2. **Starting a project?** Follow the phase sequence: Initiation → Planning → Execution → Release → Retrospective
3. **Joining mid-cycle?** Review the relevant phase doc and check your project's charter for context
4. **Need a template?** Check the relevant phase doc (e.g., One-pager, Backlog Item, Risk Register, Release Notes)
5. **Managing a blocker?** See [Risk Management & Communication](./octoacme-risks-and-communication.md) for escalation paths
6. **Preparing a release?** Use [Release & Deployment Guide](./octoacme-release-and-deployment.md) with checklists
7. **Running a retrospective?** Follow [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

## Contributing & Updating Docs

These are **living documents**. If you:
- Find an unclear section, add an example or clarification
- Discover a gap or new best practice, propose an update
- Complete a retrospective, capture action items related to process improvement

**Process**: Create an issue in the repo with the [Process Doc Update](../.github/ISSUE_TEMPLATE/) template, propose changes, and submit a PR for team review.

## Questions?

- **Process clarification**: Reach out to your Project Lead or PM
- **How to apply a template**: Ask in the project Slack channel or team sync
- **Suggesting an improvement**: Open an issue with the label `process-docs`

---

**Last Updated**: June 2026  
**Owner**: OctoAcme Project Management Team  
**Version**: 1.0
