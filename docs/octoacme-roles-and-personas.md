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

## Release Manager / Release Coordinator

### Role Summary
The Release Manager or Release Coordinator owns release readiness and coordinates a controlled, predictable handoff from development to production.

### Responsibilities
- Plan release windows and coordinate release activities
- Define and validate release readiness criteria
- Track required approvals, deployments, and rollback plans
- Synchronize engineering, operations, product, quality, and support teams
- Communicate release status, changes, and incident follow-up

### Decision Authority
The Release Coordinator decides whether planned release activities are ready to proceed within the approved release plan and escalates unresolved go/no-go concerns to delivery and operational owners.

### Interactions with Existing Roles
- Works with Project Managers to align schedules, dependencies, risks, and status reporting.
- Partners with Product Managers on release scope, customer impact, and communication priorities.
- Coordinates Developers and QA teams on build readiness, test evidence, deployment steps, and rollback capability.
- Provides the Customer / Support Lead with release notes, known issues, and operational context.

---

## Security / Compliance Lead

### Role Summary
The Security / Compliance Lead ensures that security, privacy, and regulatory requirements are incorporated throughout project planning and delivery.

### Responsibilities
- Identify applicable security, privacy, and compliance requirements
- Review designs and delivery plans for control gaps and risk
- Coordinate assessments, evidence collection, and remediation
- Advise teams on policy interpretation and exception processes
- Communicate security and compliance status and escalations

### Decision Authority
The Security / Compliance Lead determines whether security and compliance evidence satisfies agreed requirements or needs escalation. This role advises on release risk but does not replace the accountable technical or delivery owner.

### Interactions with Existing Roles
- Works with Product Managers to incorporate requirements and communicate trade-offs.
- Advises Project Managers on risk, approval timelines, and dependencies.
- Reviews plans and implementations with Developers and the Release Coordinator.
- Coordinates unresolved concerns with stakeholders and, when necessary, executive or legal leadership.

---

## Customer / Support Lead

### Role Summary
The Customer / Support Lead represents customer-facing impact and operational readiness, bringing support feedback into delivery decisions.

### Responsibilities
- Assess likely customer impact and support requirements
- Communicate known issues, workarounds, and release information
- Gather recurring feedback, incidents, and support trends
- Coordinate support readiness, documentation, staffing, and escalation
- Share customer outcomes and feedback with delivery teams

### Decision Authority
The Customer / Support Lead owns the support readiness recommendation and determines when customer communication or operational preparation requires escalation. Release or product owners retain final decisions in their respective scopes.

### Interactions with Existing Roles
- Partners with Product Managers on customer needs, prioritization, and feedback.
- Gives Developers and QA teams context on real-world issues and acceptance concerns.
- Aligns with Project Managers on communications and support milestones.
- Receives release plans and known issues from the Release Coordinator.

---

## Data / Analytics Lead

### Role Summary
The Data / Analytics Lead defines how project outcomes will be measured and ensures that teams use reliable evidence for decisions.

### Responsibilities
- Translate project and product goals into measurable outcomes
- Define metrics, data sources, baselines, and reporting cadence
- Review data quality and measurement limitations
- Produce or guide implementation of dashboards and analyses
- Explain findings and help teams act on results

### Decision Authority
The Data / Analytics Lead owns metric definitions and data-quality recommendations within an agreed measurement plan. Metric changes that affect scope or success criteria are agreed with the Product Manager and relevant stakeholders.

### Interactions with Existing Roles
- Collaborates with Product Managers to define success metrics and interpret customer outcomes.
- Works with Developers to instrument features and validate event or data quality.
- Supports Project Managers with progress and outcome reporting.
- Uses release and support data to assess adoption or operational impact with the Release Manager and Customer / Support Lead.

---

## Technical Program Manager

### Role Summary
The Technical Program Manager coordinates complex, cross-team technical delivery, dependencies, risks, and integrated plans while preserving delivery ownership within each team.

### Responsibilities
- Map technical dependencies and critical paths across workstreams
- Maintain an integrated delivery plan and cross-team risk register
- Facilitate architecture, delivery, and dependency decisions
- Track milestones, blockers, decisions, and owners
- Escalate cross-team risks and resource conflicts to sponsors or delivery leadership

### Decision Authority
The Technical Program Manager coordinates decisions and escalates unresolved cross-team issues, but does not replace the Product Manager's scope authority or the Project Manager's delivery coordination for the applicable project.

### Interactions with Existing Roles
- Partners with Project Managers on integrated schedules, risks, dependencies, and reporting.
- Aligns with Product Managers on sequencing and cross-team product milestones.
- Works with Developers on technical dependencies and delivery constraints.
- Coordinates with Release, Security / Compliance, and Data leads when technical work spans release, assurance, or measurement concerns.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
