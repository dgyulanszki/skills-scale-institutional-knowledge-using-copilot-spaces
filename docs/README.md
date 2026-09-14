# OctoAcme Project Management Docs

## Overview

OctoAcme follows a structured, iterative project management approach that balances flexibility with clear accountability. Our process emphasizes customer value, transparent communication, and continuous improvement. These docs serve as the central hub for all project management processes and guidance used across OctoAcme teams.

## Core Principles

- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments frequently
- **Clear ownership**: Every project has named roles with explicit responsibilities
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Foster feedback and learning culture

## Project Management Process Summary

OctoAcme operates through a five-phase project lifecycle designed to deliver customer value through structured, data-informed execution:

### 1. **Initiation**
Validate the business need, align stakeholders, and create a lightweight plan. This phase focuses on confirming the problem statement, identifying key stakeholders, defining success metrics, and securing go/no-go approval to move into detailed planning.

### 2. **Planning**
Break work into shippable increments, identify dependencies, estimate scope, and align timelines. Teams create prioritized backlogs with clear acceptance criteria, define the Definition of Done, and establish a release plan with milestones.

### 3. **Execution & Tracking**
Manage day-to-day execution through daily standups, weekly syncs, and progress tracking on project boards. The team follows small PR workflows (≤400 lines), requires automated CI/security checks, and maintains quality through unit tests, integration tests, and manual QA. Risk escalation is managed in three levels: team triage, PM escalation to Product Lead, and sponsor-level escalation for business-impacting issues.

### 4. **Release & Deployment**
Standardize releases to production with confidence and minimal risk. Pre-release requirements include passing CI/security scans, drafted release notes, and documented rollback plans. Deployments are verified with smoke tests, and incidents trigger blameless retrospectives.

### 5. **Close & Retrospective**
Capture learnings and convert them into continuous improvements. Teams conduct 45–75 minute retrospectives to discuss what went well, areas for improvement, and prioritize 2–3 action items with clear owners and success criteria.

### Key Execution Rhythm

- **Daily standups** (15 min) — focus on progress, blockers, dependencies
- **Weekly delivery sync** — show progress, updates, and flagged risks
- **Weekly PM-PdM alignment** — coordinate delivery and product priorities
- **Monthly stakeholder updates** — communicate status to sponsors and key stakeholders
- **Sprint/milestone demos** — showcase completed work and gather feedback

### Core Roles

- **Project Manager (PM)**: Coordinates delivery, manages schedules, risks, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, and measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs, approvals, and strategic guidance

## Project Lifecycle Overview

```
Initiation → Planning → Execution & Tracking → Release & Deployment → Close & Retrospective
    ↓          ↓             ↓                       ↓                     ↓
Problem    Backlog       Daily standups        Deploy to prod        Learnings
Validated  & timeline    & tracking            & verification        & action items
```

## Documentation Index

### Getting Started
- [Project Management Overview](octoacme-project-management-overview.md) — High-level introduction, roles, and key artifacts
- [Roles & Personas](octoacme-roles-and-personas.md) — Definitions of key roles and responsibilities

### Process Guides by Phase

**Initiation**
- [Project Initiation Guide](octoacme-project-initiation.md) — Steps to validate and authorize work, align stakeholders, and create a lightweight plan

**Planning**
- [Project Planning](octoacme-project-planning.md) — Creating actionable plans, backlogs, and release timelines

**Execution & Tracking**
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Managing day-to-day execution, standups, and progress tracking
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Identifying, managing, and communicating risks and dependencies

**Release & Deployment**
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Standardized release processes and deployment checklists

**Close & Retrospective**
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Running retrospectives and capturing learnings

## Quick Navigation

**New to OctoAcme?**
Start with [Project Management Overview](octoacme-project-management-overview.md) and [Roles & Personas](octoacme-roles-and-personas.md) to understand our approach and key responsibilities.

**Starting a new project?**
Follow the [Project Initiation Guide](octoacme-project-initiation.md) to validate your project and secure alignment, then move to [Project Planning](octoacme-project-planning.md) to create your actionable backlog and timeline.

**Managing an active project?**
Reference [Execution & Tracking](octoacme-execution-and-tracking.md) for daily workflows and standups, and [Risk Management & Communication](octoacme-risks-and-communication.md) for stakeholder updates and escalation guidance.

**Preparing to release?**
See [Release & Deployment Guide](octoacme-release-and-deployment.md) for pre-release checklists, deployment procedures, and rollback plans.

**Wrapping up a project?**
Run a retrospective using [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) to capture learnings and prioritize improvements for the next cycle.

## Key Artifacts

Every OctoAcme project maintains these core artifacts:

- **Project Charter / One-pager** — Problem, goal, success metrics, stakeholders, timeline, risks, and resources
- **Roadmap and Release Plan** — Milestones, releases, and delivery timeline
- **Sprint/Iteration Backlog** — Prioritized work items with acceptance criteria and estimates
- **Definition of Done** — Shared understanding of when work is complete
- **Risk Register** — Identified risks with impact, likelihood, owner, and mitigation plans
- **Retrospective Notes & Action Items** — Learnings and improvements for next cycle

## Communication Guidelines

### Weekly Status Template
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

### Escalation Path
- **Level 1**: Team-level triage in daily standup
- **Level 2**: PM escalates to Product Lead and dependent teams
- **Level 3**: Sponsor-level escalation for business-impacting issues

---

**Questions or feedback?** Open an issue or submit a pull request to improve these docs. See `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` for guidance on suggesting updates.
