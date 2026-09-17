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

## Security / Compliance Lead

### Role Summary
The Security / Compliance Lead ensures that project work meets security, privacy, and regulatory requirements throughout the project lifecycle.

### Responsibilities
- Review architecture, dependencies, and data handling for security and compliance risks
- Define and track required controls, approvals, and policy checks
- Coordinate remediation for vulnerabilities and audit findings
- Partner with engineering and PM to incorporate risk mitigations into scope and timelines
- Support stakeholder communication around security milestones and issues

### Goals
- Reduce exposure to security and compliance risks
- Ensure work passes required review and approval gates
- Maintain trust and operational readiness for production environments

### Typical Communication
- Security review checkpoints and remediation planning
- Risk register updates and escalation to leadership when needed
- Coordination with engineering, PM, and compliance stakeholders

### Interaction with Existing Roles
- Works with Developers to validate secure coding and configuration practices
- Partner with Product Managers and Project Managers to assess risk trade-offs and release readiness
- Escalates high-risk issues to executive sponsors or leadership when business-impacting decisions are required

---

## QA / Testing Lead

### Role Summary
The QA / Testing Lead defines quality expectations, validates readiness, and helps ensure products meet acceptance criteria before release.

### Responsibilities
- Develop and maintain the quality strategy, test plans, and release gates
- Coordinate functional, regression, smoke, and acceptance testing
- Define metrics for quality, defect trends, and release readiness
- Partner with Developers and Product Managers on testability and acceptance criteria
- Support triage of defects and defect prioritization during delivery

### Goals
- Reduce defects reaching production
- Improve confidence in release quality and user experience
- Align quality checks with business expectations and delivery milestones

### Typical Communication
- Test plans, defect reviews, and release readiness checkpoints
- Weekly quality updates in project meetings
- Collaboration in sprint planning and retrospectives

### Interaction with Existing Roles
- Works closely with Developers to validate fixes and identify regressions
- Aligns with Product Managers on acceptance criteria and release decisions
- Keeps Project Managers informed of quality risks, blockers, and rollout readiness

---

## Data / Analytics Lead

### Role Summary
The Data / Analytics Lead turns project performance and user impact into measurable signals that support prioritization, validation, and improvement.

### Responsibilities
- Define success metrics, instrumentation, and reporting needs
- Monitor usage, adoption, error trends, and operational signals
- Work with Product Managers to evaluate whether the initiative is meeting goals
- Provide evidence for roadmap decisions, release impact, and optimization work
- Partner with engineering teams on data collection and reporting quality

### Goals
- Ensure decisions are informed by evidence and outcomes
- Make project impact measurable and understandable
- Improve transparency across stakeholders and leadership

### Typical Communication
- Weekly or milestone metrics reviews
- Dashboard updates and feature impact reporting
- Collaboration with PM, Product, and leadership for outcome validation

### Interaction with Existing Roles
- Supports Product Managers in evaluating success against objectives
- Provides Project Managers with measurable progress indicators and risk signals
- Supplies Developers with observability needs and product health data

---

## Technical Architect

### Role Summary
The Technical Architect guides platform decisions, system design, and technical standards so work remains scalable, maintainable, and aligned with broader strategy.

### Responsibilities
- Define reference architectures, design principles, and integration patterns
- Review major technical trade-offs and design decisions
- Identify dependencies, technical risks, and long-term maintainability concerns
- Align implementation choices with business goals, platform capabilities, and delivery constraints
- Support technical decision-making during planning and execution

### Goals
- Keep system design coherent and scalable
- Reduce rework caused by poor architectural choices
- Support delivery teams with practical technical direction

### Typical Communication
- Design reviews, architecture decision records, and technical planning sessions
- Risk discussions during sprint planning and milestone reviews
- Collaboration with leads across engineering, security, and product

### Interaction with Existing Roles
- Works with Developers to review technical approaches and implementation quality
- Advises Product Managers and Project Managers on feasibility, dependencies, and risk
- Coordinates with Security / Compliance Leads on control design and governance requirements

---

## Stakeholder Sponsor / Executive Sponsor

### Role Summary
The Stakeholder Sponsor or Executive Sponsor provides strategic sponsorship, approves priorities, and helps unblock organizational decisions that affect the project.

### Responsibilities
- Confirm business priorities, investment, and expected outcomes
- Align cross-functional teams and resolve escalated trade-offs
- Approve funding, risk tolerance, and major scope or timeline decisions
- Help remove organizational barriers and support stakeholder engagement
- Sponsor communication about progress and business impact to leadership

### Goals
- Ensure strategic alignment and executive visibility
- Support delivery teams with clear sponsorship and decision-making authority
- Improve project momentum and cross-team accountability

### Typical Communication
- Steering committee updates, milestone reviews, and escalation points
- Leadership briefings on progress, risks, and decision needs
- Coordination with PM and Product leadership

### Interaction with Existing Roles
- Provides direction to Project Managers and Product Managers on business priorities
- Reviews high-risk issues escalated by Security, QA, and project leads
- Supports alignment across stakeholders, sponsors, and delivery teams

---

## Support / Operations Representative

### Role Summary
The Support / Operations Representative ensures that new work is operationally viable, supportable, and ready for post-release ownership.

### Responsibilities
- Define runbooks, monitoring requirements, and support handoff processes
- Validate operational readiness, incident response, and service ownership
- Provide feedback on usability, reliability, and support burden during rollout
- Coordinate communications with support teams and end users during release windows
- Help identify operational risks that may not be visible during development

### Goals
- Improve service reliability and user support experience
- Reduce production surprises after deployment
- Ensure smooth ownership transitions from delivery to operations

### Typical Communication
- Release readiness reviews and operational handoff check-ins
- Incident follow-up and support escalation pathways
- Collaboration with PM, QA, and engineering leads

### Interaction with Existing Roles
- Works with Developers and QA to validate production-readiness and service expectations
- Supports Project Managers on release timing and final readiness checks
- Provides Product Managers with insights on customer support impacts and operational constraints

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- These expanded roles help teams clarify accountability, decision rights, and collaboration patterns across planning, execution, release, and support.

