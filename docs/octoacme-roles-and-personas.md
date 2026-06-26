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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Personas (proposed additions)

To improve clarity, accountability, and cross-team coordination, add the following personas. Each entry includes a short Role Summary, Responsibilities, and Interactions with existing roles.

### Technical Program Manager (TPM)
Role summary: Coordinates complex technical projects across multiple teams to ensure delivery of cross-cutting initiatives.

Responsibilities:
- Manage cross-team schedules, milestones, and end-to-end risk tracking
- Drive dependency resolution and coordinate integration points
- Maintain project artifacts (integration plans, dependency logs) and coordinate post-release reviews

Interactions:
- Works closely with PM (delivery coordination) and PdM (scope alignment)
- Liaises with Engineering Managers and SRE for technical readiness
- Elevates cross-team blockers to Product Lead or sponsor as needed

### Delivery Lead
Role summary: Day-to-day owner for a release or program increment, focused on removing impediments and keeping work flowing.

Responsibilities:
- Facilitate planning, standups, and delivery-focused ceremonies
- Track sprint goals, readiness criteria, and release checklists
- Ensure quality gates (testing, security, performance) are met before release

Interactions:
- Collaborates with PM for schedule and stakeholder comms
- Works with PdM to confirm scope and acceptance criteria
- Coordinates with Developers, QA, SRE, and Security for release readiness

### Engineering Manager (EM)
Role summary: People and technical leadership for an engineering team, responsible for delivery capacity and technical decisions.

Responsibilities:
- Support team health, career growth, and technical direction
- Resolve resource trade-offs and help unblock engineering work
- Coordinate design and architecture reviews and approve technical approach

Interactions:
- Partners with PM/PdM on resourcing and capacity planning
- Works with Developers on technical design and implementation
- Coordinates with TPMs/Delivery Leads on cross-team dependencies and scheduling

### UX Researcher / Designer
Role summary: Owns user research, product discovery, and design to ensure usable outcomes.

Responsibilities:
- Conduct user research and usability testing
- Provide design assets and UX acceptance criteria
- Validate solutions against user needs and accessibility standards

Interactions:
- Works with PdM during discovery and prioritization
- Provides artifacts and acceptance criteria to Developers and QA
- Shares user insights with PM and stakeholders for decision-making

### Data Analyst / Insights Owner
Role summary: Ensures success metrics are measurable and provides data for prioritization and post-release evaluation.

Responsibilities:
- Define instrumentation needs, dashboards, and success metrics
- Analyze experiments and provide insights to the team
- Validate data quality and provide queries/dashboards for stakeholders

Interactions:
- Collaborates with PdM on metric definitions and success criteria
- Works with Developers on instrumentation and telemetry
- Provides reporting and context to PM and leadership

### Site Reliability Engineer (SRE) / Platform Engineer
Role summary: Ensures operational readiness, reliability, and observability of services.

Responsibilities:
- Define SLOs, runbooks, and monitoring requirements
- Support deployment automation, incident response, and performance tuning
- Review production readiness and capacity planning

Interactions:
- Works with Developers on operability and observability requirements
- Coordinates with PM and Delivery Lead on release readiness and post-deploy monitoring
- Partners with Security for incident handling and forensics

### Security / Compliance Owner
Role summary: Ensures product and project meet security, privacy, and regulatory compliance requirements.

Responsibilities:
- Conduct security reviews, threat modeling, and compliance checks
- Define remediation priorities and security acceptance criteria
- Maintain compliance artifacts and audit readiness documentation

Interactions:
- Collaborates with Developers, EMs, and PMs to address findings
- Escalates significant security risks to Product Lead and Security leadership
- Works with QA on penetration and security testing as required

### Business Analyst (BA) / Subject Matter Expert
Role summary: Bridges domain knowledge and requirements between stakeholders and the delivery team.

Responsibilities:
- Translate business and regulatory requirements into clear acceptance criteria
- Validate edge cases, workflows, and compliance requirements
- Support stakeholder interviews and requirement clarification

Interactions:
- Works with PdM on requirements and prioritization
- Supports Developers and QA with domain clarifications
- Coordinates with PM on stakeholder communication and approvals

---

## How these additions improve outcomes
- Clearer ownership reduces ambiguity and accelerates decision-making.
- Explicit interactions and handoffs reduce missed integration work and late discovery of dependencies.
- Better onboarding: new teammates can quickly understand who to contact for specific concerns (security, data, operations).
- Improved release quality through explicit readiness gates (SRE, Security, Data, QA).

(If these additions are approved, consider adding short templates for each persona to standardize their responsibilities and contacts — see the role-responsibilities template in docs/process-templates/.)
