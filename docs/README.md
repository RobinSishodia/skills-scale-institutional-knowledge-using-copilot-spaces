# OctoAcme Project Management Docs

## Overview

OctoAcme follows an iterative, customer-first approach to project management that emphasizes clear ownership, data-driven decisions, and psychological safety. Our processes are designed to deliver measurable business outcomes through organized phases—from validating initial ideas, to planning and execution, through release and continuous improvement.

**Key Principles:**
- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments rather than large, risky releases
- **Clear ownership**: Each project has named Project Manager (PM) and Product Manager (PdM) roles
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and transparency

## Project Lifecycle Overview

OctoAcme's project management follows a five-phase lifecycle:

1. **Initiation** — Validate the business need, define measurable outcomes, and align stakeholders on go/no-go decisions
2. **Planning** — Break work into shippable increments, establish acceptance criteria, estimate scope, and manage dependencies
3. **Execution & Tracking** — Build, test, and review work through sprint cycles; maintain daily standups and weekly syncs
4. **Release & Deployment** — Prepare for production with pre-release checks, smoke tests, and rollback planning
5. **Retrospective & Continuous Improvement** — Capture learnings and convert them into actionable improvements

Throughout all phases, risk management and stakeholder communication ensure transparency and early escalation of blockers.

## Core Roles

OctoAcme projects operate with clearly defined roles:

- **Project Manager (PM)**: Coordinates delivery, manages schedules, risks, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, and measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide input, approvals, and strategic guidance

## Process Documents

### Getting Started
- **[Project Management Overview](octoacme-project-management-overview.md)** — Core principles, lifecycle, roles, and artifacts
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Detailed definitions of Project Manager, Product Manager, Developer, and QA responsibilities

### Project Phases
1. **[Initiation](octoacme-project-initiation.md)** — Validate the problem, align stakeholders, create a one-pager, confirm go/no-go decision
2. **[Planning](octoacme-project-planning.md)** — Break work into shippable increments, estimate scope, define Definition of Done, manage dependencies
3. **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Daily standups, sprint planning, quality standards, progress tracking, blocker escalation
4. **[Release & Deployment](octoacme-release-and-deployment.md)** — Pre-release requirements, deployment checklist, rollback playbooks, release notes
5. **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Structure retrospectives, track action items, measure impact of improvements

### Cross-Cutting Concerns
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Risk registers, lifecycle management, stakeholder communication templates, escalation paths

## Quality & Testing Strategy

Quality is built into every phase:

- **Unit tests** for new logic
- **Integration tests** where applicable
- **End-to-end smoke tests** for critical flows before release
- **Security scanning** in CI
- **Manual QA** for feature acceptance when needed
- **Pull request standards**: Small PRs (≤ 400 lines), with issue links and acceptance criteria; require review and approval before merge

## Communication Cadence

- **Daily standups** (15 min) — Progress, blockers, dependencies
- **Weekly syncs** — PM and PdM alignment; delivery team standups
- **Weekly or milestone-based stakeholder updates** — Status, risks, decisions
- **Ad-hoc escalations** — For blockers and critical issues

## Quick Navigation

**If you're starting a new project:**
→ Begin with [Project Initiation](octoacme-project-initiation.md) and [Project Management Overview](octoacme-project-management-overview.md)

**If you're planning an upcoming sprint:**
→ See [Planning](octoacme-project-planning.md) and [Execution & Tracking](octoacme-execution-and-tracking.md)

**If you're managing a risk, blocker, or incident:**
→ Reference [Risk Management & Communication](octoacme-risks-and-communication.md)

**If you're preparing a release:**
→ Follow [Release & Deployment](octoacme-release-and-deployment.md)

**If you're reflecting on team learnings:**
→ Use [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

**If you want to understand roles and responsibilities:**
→ Review [Roles & Personas](octoacme-roles-and-personas.md)

## How to Use These Docs

- **Keep the Project Charter updated** in your project repository
- **Reference the appropriate phase guide** as your project progresses
- **Use checklists and templates** as starting points for your team
- **Add process-specific customizations** to align with your organizational needs
- **Share links to relevant docs** in project kickoffs, planning sessions, and team communications

---

*These documents are maintained as part of OctoAcme's institutional knowledge initiative, ensuring all team members have equal access to processes, decisions, and rationale.*
