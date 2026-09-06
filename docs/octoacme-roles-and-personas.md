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

## Release Managers

### Role Summary
Release Managers coordinate release readiness across teams so changes move to production with clear approvals, communication, and rollback preparation.

### Primary Responsibilities
- Maintain the release checklist, timeline, and go/no-go readiness criteria
- Confirm testing, documentation, release notes, and rollout plans are complete
- Coordinate deployment windows, change communication, and post-release verification
- Ensure rollback and incident-response contacts are defined before launch

### Interactions with Existing Roles
- Work with Project Managers to align release milestones and escalation timing
- Partner with Product Managers on release scope, customer-facing messaging, and timing trade-offs
- Coordinate with Developers and QA/Testing on build readiness, defect status, and smoke-test coverage
- Notify Stakeholders and Support teams about release timing, risks, and outcomes

### Decision Rights and Escalation
- Can recommend a go/no-go decision based on readiness criteria and unresolved risks
- Escalates release blockers, failed checks, or rollback decisions through the PM, Product Lead, and Sponsor path when business impact is material

### Lifecycle Contributions
- **Initiation:** identify release constraints, target windows, and dependency assumptions
- **Planning:** define release checkpoints, environments, and approval needs
- **Execution:** track readiness, verify exit criteria, and coordinate cutover preparation
- **Release:** lead deployment coordination, stakeholder updates, and post-deploy validation
- **Retrospective:** capture release lessons, recurring failure modes, and process improvements

### Goals
- Reduce release risk and confusion
- Improve deployment predictability and communication quality
- Shorten time to recover when releases encounter issues

### Typical Communication
- Release readiness reviews and go/no-go updates
- Deployment checklists, release notes, and stakeholder announcements
- Post-release summaries and rollback coordination if needed

---

## Business Analysts

### Role Summary
Business Analysts turn business needs into clear requirements, workflows, and acceptance criteria that help delivery teams build the right solution.

### Primary Responsibilities
- Clarify requirements, scope boundaries, business rules, and process impacts
- Break high-level requests into detailed user stories or functional requirements
- Support acceptance criteria, traceability, and dependency identification
- Surface assumptions, open questions, and downstream operational impacts

### Interactions with Existing Roles
- Work with Product Managers to refine problem statements, priorities, and success measures
- Partner with Project Managers to expose scope risks, dependencies, and stakeholder decisions
- Collaborate with Developers and QA/Testing to clarify expected behavior and edge cases
- Gather input from Stakeholders, Support, and Operations to ensure requirements reflect real workflows

### Decision Rights and Escalation
- Owns clarification of documented requirements and recommends scope interpretation when ambiguity exists
- Escalates unresolved requirement conflicts or missing stakeholder decisions to Product and Project leadership

### Lifecycle Contributions
- **Initiation:** help define the business problem, stakeholders, constraints, and desired outcomes
- **Planning:** translate needs into backlog-ready requirements, acceptance criteria, and dependency notes
- **Execution:** answer delivery questions, refine stories, and validate that implemented behavior matches intent
- **Release:** confirm business-facing documentation, training inputs, and known-process impacts
- **Retrospective:** identify requirement gaps, handoff issues, and opportunities to improve discovery

### Goals
- Reduce ambiguity before development starts
- Improve alignment between business intent and delivered behavior
- Lower rework caused by misunderstood requirements

### Typical Communication
- Requirement workshops, backlog refinement, and acceptance-criteria reviews
- Decision logs for open questions and scope clarifications
- Stakeholder interviews and process walkthroughs

---

## Technical Leads / Solution Architects

### Role Summary
Technical Leads or Solution Architects guide the overall technical approach so delivery decisions align with platform standards, scalability needs, and long-term maintainability.

### Primary Responsibilities
- Define solution direction, major design decisions, and key technical trade-offs
- Identify cross-system dependencies, architectural risks, and non-functional requirements
- Support estimation with technical discovery and implementation sequencing
- Guide developers through design reviews, integration patterns, and quality expectations

### Interactions with Existing Roles
- Advise Product Managers on feasibility, sequencing, and technical trade-offs tied to business outcomes
- Partner with Project Managers on dependency planning, risk visibility, and escalation timing
- Mentor Developers and collaborate with QA/Testing on test strategy for critical flows and integrations
- Coordinate with Operations and Support on observability, supportability, and deployment constraints

### Decision Rights and Escalation
- Owns technical direction for the agreed solution and recommends standards, patterns, and exception handling
- Escalates material architecture risks, security concerns, or dependency conflicts when they threaten delivery or operability

### Lifecycle Contributions
- **Initiation:** assess feasibility, major constraints, and likely integration complexity
- **Planning:** shape architecture, sequencing, and technical milestones
- **Execution:** review implementation choices, unblock complex decisions, and monitor technical risk
- **Release:** verify operational readiness, performance considerations, and rollback implications
- **Retrospective:** review technical debt, architecture fit, and improvement opportunities

### Goals
- Keep the solution maintainable, secure, and scalable
- Reduce technical rework and late-stage design churn
- Make implementation trade-offs explicit and well understood

### Typical Communication
- Design reviews, architecture notes, and technical risk discussions
- Dependency and integration planning sessions
- Cross-functional reviews for major technical decisions

---

## Operations / Support Leads

### Role Summary
Operations or Support Leads prepare the business and technical support model for launch, incident response, and steady-state service ownership.

### Primary Responsibilities
- Define monitoring, alerting, support handoff, and runbook readiness for new changes
- Prepare support teams with known issues, escalation paths, and customer-impact guidance
- Validate operational tasks such as access, maintenance windows, or environment readiness
- Track post-release health signals and coordinate incident response with engineering when needed

### Interactions with Existing Roles
- Work with Project Managers and Release Managers on rollout timing, readiness checkpoints, and communications
- Partner with Technical Leads and Developers on observability, supportability, and operational constraints
- Coordinate with QA/Testing on smoke-test expectations and production verification steps
- Keep Product Managers and Stakeholders informed about support readiness, incidents, and customer-impact themes

### Decision Rights and Escalation
- Can recommend delaying a release when support readiness, monitoring, or operational safeguards are incomplete
- Escalates production incidents, support trends, and service risks through incident and sponsor communication paths as appropriate

### Lifecycle Contributions
- **Initiation:** identify service, support, and operational impacts early
- **Planning:** define runbooks, on-call expectations, monitoring, and support dependencies
- **Execution:** review readiness artifacts and confirm support workflows for new capabilities
- **Release:** monitor rollout health, manage incident handoff, and coordinate customer-impact communications
- **Retrospective:** contribute support metrics, incident learnings, and operational improvement actions

### Goals
- Improve production readiness and service stability
- Reduce support friction during and after releases
- Speed up detection, triage, and recovery from incidents

### Typical Communication
- Runbook reviews, support readiness checklists, and incident updates
- Post-release health reports and customer-impact summaries
- Cross-functional coordination with engineering, product, and stakeholders

---

## Risk Owners

### Role Summary
Risk Owners are named individuals accountable for monitoring a specific risk, driving mitigations, and escalating when trigger conditions or contingency thresholds are met.

### Primary Responsibilities
- Maintain the status, mitigation actions, and trigger conditions for assigned risks
- Coordinate with affected teams to reduce likelihood or impact
- Keep the risk register current with evidence, dates, and contingency plans
- Raise decisions quickly when mitigation is blocked or a risk materializes

### Interactions with Existing Roles
- Work with Project Managers to keep risk reviews current and visible
- Support Product Managers with impact framing and decision trade-offs when risks affect scope, timing, or value
- Partner with Technical Leads, Developers, QA/Testing, or Operations depending on the source of the risk
- Inform Stakeholders when exposure changes materially or leadership action is required

### Decision Rights and Escalation
- Owns day-to-day management of the assigned risk and can recommend mitigation priorities or contingency activation
- Escalates through the documented PM -> Product Lead -> Sponsor path when exposure exceeds agreed thresholds, and uses the security or incident path for specialized events

### Lifecycle Contributions
- **Initiation:** highlight major uncertainties, assumptions, and dependency exposure
- **Planning:** document mitigations, owners, thresholds, and review cadence
- **Execution:** monitor changes in exposure, drive mitigation tasks, and surface blockers
- **Release:** confirm high-priority risks are acceptable, mitigated, or covered by contingency plans
- **Retrospective:** assess which mitigations worked and update future risk practices

### Goals
- Make risk ownership explicit and actionable
- Reduce surprise escalations and unmanaged dependencies
- Improve team confidence in mitigation and contingency planning

### Typical Communication
- Weekly risk reviews and mitigation updates
- Escalation notes tied to thresholds, blockers, or contingency activation
- Decision logs for accepted, transferred, or mitigated risks

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
