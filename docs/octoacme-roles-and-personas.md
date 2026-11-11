# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. A person may hold more than one role, and teams may share specialist roles, depending on project size and needs. The roles below clarify ownership and collaboration; they do not prescribe mandatory staffing.

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

## UX/UI Designer or User Researcher

### Role Summary
This role researches user needs and designs and validates usable, accessible experiences. Depending on the team, design and research may be separate specialties.

### Responsibilities
- Plan and conduct user research, and share findings with the team
- Create interaction flows, prototypes, and visual designs as needed
- Validate usability and accessibility with users and agreed standards
- Document design decisions and experience requirements

### Collaboration and decision boundaries
- Partners with the Product Manager to connect research findings to user needs, priorities, and acceptance criteria; the Product Manager remains accountable for product priorities.
- Works with Developers and the Tech Lead to assess feasibility and resolve implementation questions while preserving essential user outcomes.
- Works with QA/Testing to identify usability, accessibility, and experience checks for validation.
- Shares research and design implications with the Project Manager so plans, dependencies, and stakeholder updates reflect the work.

---

## Tech Lead or Architect

### Role Summary
The Tech Lead or Architect guides technical design and integration so the solution is maintainable, reliable, and aligned with agreed technical constraints. This role may be held by a senior developer.

### Responsibilities
- Facilitate technical design and document important decisions
- Identify technical risks, integration points, and dependencies
- Guide engineering standards and review implementation approaches
- Advise on technical estimates, sequencing, and testability

### Collaboration and decision boundaries
- Works with Developers and QA/Testing to make designs implementable and verifiable, and supports technical problem-solving.
- Coordinates with the Project Manager on engineering dependencies, delivery risks, and estimates.
- Explains technical options and trade-offs to the Product Manager, who owns product priority decisions; escalates material scope or schedule impacts through the Project Manager.
- Consults Security/Privacy and Operations/Site Reliability contributors on relevant design and operational concerns. Technical decisions follow the team's agreed governance and escalation path.

---

## Business Analyst or Requirements Lead

### Role Summary
This role clarifies business processes and translates stakeholder needs into requirements that the delivery team can understand and validate.

### Responsibilities
- Elicit and document workflows, business rules, and requirements
- Identify gaps, assumptions, and conflicting requests
- Help make acceptance criteria clear, testable, and traceable
- Maintain links between stakeholder needs, backlog items, and validation

### Collaboration and decision boundaries
- Works with stakeholders and the Product Manager to clarify needs and resolve ambiguity; the Product Manager remains responsible for product scope and prioritization.
- Partners with Developers and QA/Testing to confirm requirements are feasible and testable, and to resolve interpretation questions.
- Coordinates with the Project Manager when requirement changes affect dependencies, milestones, risks, or communications.

---

## Security or Privacy Lead

### Role Summary
This role advises the team on security, privacy, and applicable compliance considerations throughout delivery. It may be a specialist or a designated contact who connects the project to security and privacy teams.

### Responsibilities
- Identify relevant security and privacy requirements, risks, and review needs
- Advise on threat assessment, data handling, and appropriate controls
- Help define security and privacy validation activities and release considerations
- Escalate significant concerns through established security, privacy, and incident channels

### Collaboration and decision boundaries
- Works with the Tech Lead and Developers to integrate appropriate controls into design and implementation, and with QA/Testing to plan relevant verification.
- Coordinates with the Project Manager to track risks, reviews, dependencies, and escalation; consults the Product Manager on user or scope trade-offs without replacing product ownership.
- Advises stakeholders and Operations/Site Reliability contributors as needed. Formal approvals and incident response remain with the designated organizational authorities and runbooks.

---

## Operations, Site Reliability, or Support Representative

### Role Summary
This role helps ensure the service can be deployed, operated, monitored, and supported effectively. The role may be represented by an operations or support contact rather than a dedicated project team member.

### Responsibilities
- Advise on operability, reliability, monitoring, and support readiness
- Identify operational dependencies and deployment or recovery considerations
- Help define runbooks, alerts, and post-release verification needs
- Share support feedback and production signals with the delivery team

### Collaboration and decision boundaries
- Partners with Developers and the Tech Lead on reliability, deployment design, and observability, and with QA/Testing on operational and release checks.
- Coordinates with the Project Manager on readiness, operational dependencies, and risks, and with the Product Manager on prioritizing user-impacting operational feedback.
- Works with stakeholders and the Change Management/Communications Lead on support expectations and release communications. Operational approval and incident actions follow the organization's established ownership and runbooks.

---

## Change Management or Communications Lead

### Role Summary
This role plans communications, training, and adoption support so affected audiences understand and can use a project’s changes.

### Responsibilities
- Identify audiences, communication needs, and adoption impacts
- Prepare communication, training, and enablement materials
- Coordinate timing and channels for launch and milestone updates
- Gather adoption feedback and share it with the project team

### Collaboration and decision boundaries
- Works with the Project Manager to align communications with delivery milestones, risks, and stakeholder updates.
- Partners with the Product Manager to explain product value, changes, and intended user outcomes; checks technical details with Developers and the Tech Lead.
- Coordinates support readiness and FAQs with Operations/Site Reliability or Support, and consults stakeholders and the UX/UI Designer or User Researcher about audience needs.
- Communications do not replace formal decisions or approvals owned by the Product Manager, Project Manager, or designated stakeholders.

---

## Role coordination and handoffs

- The Product Manager owns product outcomes and backlog priority; the Project Manager coordinates the delivery plan, dependencies, risks, and project communications. Specialist roles advise and deliver within those accountabilities rather than silently taking them over.
- Make decisions, owners, dependencies, and handoffs visible in the backlog, project board, risk register, or decision log as appropriate. Raise unresolved scope, schedule, quality, security, or operational concerns through the established team-to-PM-to-Product Lead-to-Sponsor escalation path; security incidents follow the security incident runbook.
- Tailor role coverage to the initiative. Combine or share roles when appropriate, while explicitly assigning responsibility for each needed activity so that no handoff is left implicit.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
