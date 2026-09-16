# OctoAcme Project Management Docs

## Overview

OctoAcme follows a structured, iterative project management approach that balances flexibility with clear accountability. Our process emphasizes customer value, transparent communication, and continuous improvement.

### Core Principles
- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments frequently
- **Clear ownership**: Every project has named roles with explicit responsibilities
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Foster feedback and learning culture

## Project Management Process Summary

OctoAcme follows a structured project lifecycle designed to deliver customer value through iterative, data-informed execution. The process spans five phases: **Initiation** (validating business need and stakeholder alignment), **Planning** (breaking work into shippable increments with clear acceptance criteria), **Execution** (daily delivery with quality gates), **Release** (standardized deployment to production), and **Close & Retrospective** (capturing learnings). This lifecycle is grounded in core principles of customer-first prioritization, iterative delivery, clear ownership, data-driven decision-making, and psychological safety. Each project is led by a named Project Manager (PM) coordinating delivery and a Product Manager (PdM) defining outcomes—supported by developers, QA, and stakeholders—ensuring accountability and transparency at every stage.

OctoAcme operates with well-defined personas: **Developers** implement features and write tests while collaborating on design and risk identification; **Product Managers** own vision and prioritize the backlog based on customer research and metrics; and **Project Managers** coordinate schedules, manage risks, and facilitate cross-team communication. Day-to-day execution follows a predictable rhythm of daily 15-minute standups (focused on progress and blockers), weekly delivery syncs (showing updates and flagged risks), and demos at sprint/milestone end. Work moves through a GitHub Projects board (Backlog → Ready → In Progress → In Review → QA → Done) with small PRs (≤400 lines), linked issues, and at least one approval before merge. Communication is proactive: weekly PM-PdM alignment, twice-weekly team standups, monthly stakeholder updates, and structured risk escalation from team-level triage up through Product Lead to sponsors when needed.

Quality is embedded throughout OctoAcme's process via unit and integration tests, end-to-end smoke tests for critical flows, CI-automated security scanning, and manual QA for feature acceptance. Risk management is formalized through a Risk Register (tracking ID, description, impact, likelihood, owner, and mitigation) that is reviewed weekly and actively monitored. Communication templates standardize status reporting (progress, next steps, risks/blockers, decisions needed) and incident response (triage, actions, timeline, blameless retrospectives). Releases are governed by pre-release checklists (acceptance criteria met, CI/security scans passed, release notes drafted, rollback plans documented) and deployment verification, with clear rollback procedures if issues arise. Each project concludes with a retrospective (45–75 minutes) that captures what went well, improvement areas, and action items—which feed back into the backlog, creating a continuous improvement cycle that measures impact and celebrates incremental progress.

## Project Lifecycle

### 1. Initiation
Validate the business need, align stakeholders, and create a lightweight plan.
**Read**: [Project Initiation Guide](octoacme-project-initiation.md)

### 2. Planning
Break work into shippable increments, identify dependencies, and align timelines.
**Read**: [Project Planning](octoacme-project-planning.md)

### 3. Execution & Tracking
Manage day-to-day execution, track progress, and manage risks.
**Read**: [Execution & Tracking](octoacme-execution-and-tracking.md)

### 4. Release & Deployment
Standardize releases to production with confidence and minimal risk.
**Read**: [Release & Deployment Guide](octoacme-release-and-deployment.md)

### 5. Close & Retrospective
Capture learnings and convert them into continuous improvements.
**Read**: [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

## Documentation Index

### Getting Started
- [Project Management Overview](octoacme-project-management-overview.md) — High-level introduction, roles, and key artifacts
- [Roles & Personas](octoacme-roles-and-personas.md) — Definitions of key roles and responsibilities

### Process Guides
- [Project Initiation](octoacme-project-initiation.md) — Steps to validate and authorize work
- [Project Planning](octoacme-project-planning.md) — Creating actionable plans and backlogs
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Managing daily execution and progress
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Identifying and managing risks
- [Release & Deployment](octoacme-release-and-deployment.md) — Standardized release process
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capturing learnings

## Quick Navigation

**New to OctoAcme?** Start with [Project Management Overview](octoacme-project-management-overview.md) and [Roles & Personas](octoacme-roles-and-personas.md).

**Starting a new project?** Follow the [Project Initiation](octoacme-project-initiation.md) guide, then move to [Project Planning](octoacme-project-planning.md).

**Managing a project?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) for daily workflows and [Risk Management & Communication](octoacme-risks-and-communication.md) for stakeholder updates.

**Preparing to release?** See [Release & Deployment Guide](octoacme-release-and-deployment.md).

**Wrapping up?** Run a retrospective using [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md).
