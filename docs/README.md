# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation library. This README provides a roadmap to help you find the guidance you need, whether you're starting a new project, managing risks, or running a retrospective.

## Quick Start

New to OctoAcme? Start here:
- **[Project Management Overview](./octoacme-project-management-overview.md)** — Understand our principles, roles, and lifecycle
- **[Roles and Personas](./octoacme-roles-and-personas.md)** — Learn your role and responsibilities

## OctoAcme Project Management Overview

OctoAcme follows a structured, lifecycle-based approach to project management grounded in five core principles: customer-first delivery, iterative increments, clear ownership, data-informed decisions, and psychological safety. The organization operates projects across five key phases—**Initiation, Planning, Execution, Release, and Close & Retrospective**—each with defined deliverables and decision gates. 

Projects begin with lightweight validation through a **Project One-pager** that confirms business need, identifies stakeholders, and establishes success metrics. Once approved, the team moves into planning where work is broken into shippable increments, prioritized with acceptance criteria, and organized into a release roadmap. This structured handoff ensures alignment before execution begins and reduces mid-project scope creep.

**Execution at OctoAcme** emphasizes rapid feedback and transparency through a consistent team rhythm: daily standups (15 min), weekly delivery syncs, and sprint-based reviews. The organization uses **GitHub Projects** for workflow visibility with columns spanning Backlog → Ready → In Progress → In Review → QA → Done. Pull requests follow a discipline of small, reviewable changes (≤400 lines), automated CI testing and linting, and mandatory peer approval before merge. Quality is enforced through unit tests, integration tests, smoke tests for critical flows, security scanning, and manual QA acceptance when needed. Risk management is continuous—teams maintain a living Risk Register tracking impact and likelihood, escalate blockers through three levels (team triage → PM → Product Lead → Sponsor), and update status weekly.

**Communication and role clarity** are central to OctoAcme's success. Three core roles drive each project: Project Managers coordinate schedules, risks, and stakeholder alignment; Product Managers own vision, prioritization, and success metrics; and Developers implement features while identifying technical risks. A predictable cadence—weekly PM-PdM syncs, twice-weekly team standups, and monthly stakeholder updates—ensures no surprises. **Release management is deliberate and risk-aware**: teams complete pre-release checklists, deploy to staging first, run smoke tests, then move to production with post-deploy verification and stakeholder announcements.

Finally, **OctoAcme institutionalizes learning** through mandatory retrospectives after each sprint, release, or incident. These sessions capture what went well, identify improvements, and generate 2–3 actionable items with clear owners and due dates. By pairing this lightweight governance with comprehensive documentation, OctoAcme ensures that processes remain accessible, versioned, and collaboratively maintained—reducing onboarding time and single-person dependency across teams.

## By Project Phase

### 1. Initiation
- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Validate ideas, align stakeholders, define success criteria
  - When to use this phase
  - Minimum deliverables (Project One-pager, stakeholder list, timeline, risks, resources)
  - Decision gate for moving to planning

### 2. Planning
- **[Project Planning](./octoacme-project-planning.md)** — Create actionable plans, estimate scope, and define milestones
  - Break work into shippable increments
  - Create prioritized backlog with acceptance criteria
  - Identify dependencies and integration points
  - Define Definition of Done

### 3. Execution & Tracking
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Manage day-to-day work, track progress, and resolve blockers
  - Team rhythm (standups, syncs, demos)
  - GitHub Projects workflow and PR conventions
  - Quality and testing standards
  - Blocker escalation paths

- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Identify risks, communicate status, and escalate issues
  - Risk Register maintenance
  - Risk lifecycle (identify, assess, mitigate, monitor)
  - Stakeholder communication templates
  - Escalation paths

### 4. Release
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Prepare, deploy, and verify production releases
  - Release types (patch, minor, major)
  - Pre-release requirements and deployment checklist
  - Rollback and incident playbook
  - Release notes template

### 5. Continuous Improvement
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and drive improvements
  - When to hold retrospectives
  - Retrospective structure (what went well, improvements, action items)
  - Tracking and measuring improvements
  - Building continuous improvement culture

## OctoAcme Principles

Our approach is built on:

- **Customer-first** — Prioritize customer value and usability
- **Iterative delivery** — Deliver small, testable increments
- **Clear ownership** — Named PMs and Product Leads own accountability
- **Data-informed** — Measure impact and iterate based on evidence
- **Psychological safety** — Encourage feedback and learning

## Key Roles

- **Project Manager (PM)** — Coordinates delivery, schedules, risks, and communications
- **Product Manager (PdM)** — Defines outcomes, prioritizes backlog, measures success
- **Developers** — Implement features, collaborate on design and testing
- **QA/Testing** — Validate quality and acceptance criteria
- **Stakeholders** — Provide inputs and approvals

See **[Roles and Personas](./octoacme-roles-and-personas.md)** for detailed descriptions of responsibilities and typical communication patterns.

## Project Lifecycle Overview

```
Initiation → Planning → Execution → Release → Close & Retrospective
    ↓           ↓           ↓          ↓              ↓
Problem &   Scope &     Build,      Deploy,      Learnings &
Alignment   Timeline    Test &      Verify &     Improvements
                        Iterate     Announce
```

1. **Initiation** — Problem statement, stakeholders, high-level timeline
2. **Planning** — Scope, resources, milestones, dependencies
3. **Execution** — Build, test, review, iterate with continuous risk management
4. **Release** — Deploy, verify, announce to stakeholders
5. **Close & Retrospective** — Capture learnings, plan improvements, celebrate wins

## Communication Cadence

- **Daily** — Team standups (15 min) focused on progress, blockers, dependencies
- **Weekly** — Delivery sync (show progress, updates, flagged risks) and PM-PdM alignment
- **Twice-weekly** — Team standups (or as agreed by team)
- **Monthly** — Stakeholder updates and status reporting
- **Ad-hoc** — Escalations and incident communication as needed

## Key Artifacts

- **Project Charter / One-pager** — Business need, goals, success metrics, team, timeline
- **Roadmap and Release Plan** — Phased delivery and milestone mapping
- **Sprint/Iteration Backlog** — Prioritized work with acceptance criteria
- **Definition of Done** — Team standards for "done" and ready to release
- **Risk Register** — Active tracking of identified risks and mitigations
- **Retrospective notes** — Learnings and action items for continuous improvement

## Need Help?

If you can't find what you're looking for, check:
- The table of contents above
- The **[Roles and Personas](./octoacme-roles-and-personas.md)** guide for role-specific workflows
- The **[Project Management Overview](./octoacme-project-management-overview.md)** for high-level principles
- Your project PM or Product Lead for context-specific guidance

---

**Last Updated:** June 2026  
**Maintained by:** OctoAcme Project Management Team
