# OctoAcme Project Management Docs

Welcome to OctoAcme's project management documentation. This folder contains comprehensive guides for running projects from initiation through closure.

## Overview

OctoAcme is built on a structured, iterative project management approach that prioritizes **customer value**, **clear ownership**, **data-informed decisions**, and **psychological safety**. Our project lifecycle is organized into five distinct phases, with cross-cutting themes for risk management and communication throughout.

### Core Principles

- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments and learn from each cycle
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and blameless retrospectives

## Project Lifecycle

OctoAcme follows a five-phase project lifecycle:

### 📋 Phase 1: Project Initiation
**Goal**: Validate business need and get stakeholder alignment

- Document: [Project Initiation Guide](./octoacme-project-initiation.md)
- Key deliverables: One-pager, stakeholder list, initial risk assessment, go/no-go decision
- When to use: Whenever a new project idea or feature proposal is ready to be explored
- Key activities:
  - Confirm business need and measurable outcome
  - Identify stakeholders & champions
  - Define success criteria and initial timeline
  - Assess resource needs

### 📐 Phase 2: Project Planning
**Goal**: Break work into shippable increments and create an actionable backlog

- Document: [Project Planning](./octoacme-project-planning.md)
- Key deliverables: Prioritized backlog, Definition of Done, release plan, risk register
- Key activities:
  - Kickoff meeting with stakeholders and delivery team
  - Create prioritized backlog with acceptance criteria
  - Estimate scope using T-shirt sizing or story points
  - Identify dependencies and integration points
  - Create release plan and milestone map

### ⚙️ Phase 3: Execution & Tracking
**Goal**: Manage day-to-day delivery and track progress toward milestones

- Document: [Execution & Tracking](./octoacme-execution-and-tracking.md)
- Key artifacts: GitHub Projects board, sprint backlog, PR descriptions
- Key activities:
  - Daily standups (15 min) — focus on progress, blockers, dependencies
  - Weekly delivery syncs — show progress, updates, and flagged risks
  - Small, focused PRs with linked issues and acceptance criteria
  - Automated testing, linting, and security scanning in CI
  - Regular demos and reviews at sprint/milestone boundaries

### 🚀 Phase 4: Release & Deployment
**Goal**: Standardize release process and reduce production risk

- Document: [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- Key artifacts: Release notes, rollback plan, deployment checklist
- Release types: Patch, Minor, Major
- Key pre-release requirements:
  - All acceptance criteria met and PRs merged
  - Passing CI and security scans
  - Release notes drafted
  - Smoke tests prepared
  - Rollback/mitigation plan documented

### 🔄 Phase 5: Retrospective & Continuous Improvement
**Goal**: Capture learnings and convert to actionable improvements

- Document: [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- When: After each sprint, release, or important milestone
- Key activities:
  - What went well / what could improve
  - Prioritize 2–3 action items to avoid overload
  - Track improvements and measure impact
  - Update process docs with validated improvements

## Cross-Cutting Themes

### Risk Management & Communication
**Document**: [Risk Management & Communication](./octoacme-risks-and-communication.md)

Identify, track, and communicate risks throughout the project lifecycle:
- Maintain a risk register with ID, description, impact, likelihood, owner, and mitigation
- Follow escalation paths: Team-level → PM → Product Lead → Sponsor
- Provide regular stakeholder updates using standardized templates
- Follow incident communication protocols for security and production issues

### Roles & Personas
**Document**: [Roles and Personas](./octoacme-roles-and-personas.md)

Understand responsibilities and communication patterns for key roles:
- **Developers**: Implement features, write tests, participate in design reviews
- **Product Managers**: Define what to build, prioritize backlog, measure outcomes
- **Project Managers**: Coordinate delivery, manage risks, facilitate communication
- **QA/Testing**: Validate quality and acceptance criteria

### Project Management Overview
**Document**: [Project Management Overview](./octoacme-project-management-overview.md)

High-level introduction to OctoAcme principles, roles, artifacts, and communication cadence.

## Quick Reference: How to Use These Docs

**Getting started with a new project?**
→ Start with [Project Initiation Guide](./octoacme-project-initiation.md)

**Planning your next sprint or release?**
→ Reference [Project Planning](./octoacme-project-planning.md) and [Execution & Tracking](./octoacme-execution-and-tracking.md)

**Managing or tracking risks?**
→ See [Risk Management & Communication](./octoacme-risks-and-communication.md)

**Preparing a release or deployment?**
→ Use [Release & Deployment Guide](./octoacme-release-and-deployment.md)

**Running a retrospective or capturing learnings?**
→ Follow [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

**Understanding team roles?**
→ Review [Roles and Personas](./octoacme-roles-and-personas.md)

## Key Artifacts by Phase

| Phase | Key Artifacts |
|-------|---------------|
| **Initiation** | Project One-pager, Stakeholder list, Initial risk list |
| **Planning** | Backlog with acceptance criteria, Definition of Done, Release plan, Risk register |
| **Execution** | Sprint backlog, PR descriptions, Risk updates, Weekly status reports |
| **Release** | Release notes, Deployment checklist, Rollback plan |
| **Retrospective** | Retro notes, Action items, Process improvements |

## Communication Cadence

- **Daily**: Team standups (15 min) — progress, blockers, dependencies
- **Weekly**: PM + PdM sync, delivery team standups
- **Weekly**: Risk register review and status updates
- **Milestone-based**: Stakeholder updates and demos
- **Monthly**: Full stakeholder status review
- **Ad-hoc**: Escalations and incident communication

## Getting Help

- Unsure which phase your project is in? Check the [Project Management Overview](./octoacme-project-management-overview.md) for the high-level lifecycle
- Need a specific template or checklist? Look for the "Checklist" section in each phase document
- Questions about roles or responsibilities? See [Roles and Personas](./octoacme-roles-and-personas.md)

---

**Last updated**: June 2026 | **Maintained by**: OctoAcme Project Management Team
