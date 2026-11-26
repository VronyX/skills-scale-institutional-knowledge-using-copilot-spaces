# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

Projects may assign a persona to a dedicated person or share responsibilities across existing roles. Define accountable owners during planning so handoffs, decisions, and escalations remain clear.

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
The Release Manager or Release Coordinator owns release planning, readiness, and go/no-go coordination. This persona is accountable for turning approved scope into a controlled, observable release.

### Responsibilities
- Build and maintain the release plan and deployment checklist
- Coordinate release scope and timing with Product and Project Management
- Confirm implementation, test, rollback, and communication readiness
- Facilitate the go/no-go decision and document the outcome
- Coordinate deployment execution and post-release verification

### Goals
- Reduce release failures and unplanned production changes
- Make readiness and release decisions visible and timely
- Provide predictable stakeholder and support communications

### Interactions with Existing Roles
- Work with Product Managers to confirm scope, timing, release notes, and migration implications.
- Partner with Project Managers on schedules, risks, dependencies, and escalation.
- Confirm with Developers that code, configuration, rollback, and observability are ready.
- Coordinate release validation and acceptance evidence with QA/Testing.
- Prepare stakeholders and operational teams for the release.

### Typical Communication
- Release readiness reviews and go/no-go meetings
- Deployment runbooks and rollback plans
- Release status updates and post-deploy verification reports

---

## Scrum Master / Delivery Facilitator

### Role Summary
The Scrum Master or Delivery Facilitator enables an effective team cadence, facilitates ceremonies and improvement practices, and helps the team remove impediments.

### Responsibilities
- Facilitate planning, standups, reviews, and retrospectives
- Coach the team on agreed working agreements and continuous improvement
- Identify and remove team-level impediments
- Connect delivery dependencies to broader planning and escalation channels
- Track follow-up actions for process improvements

### Goals
- Improve team flow, focus, and predictability
- Reduce preventable meetings and recurring blockers
- Turn retrospective insights into measurable improvements

### Interactions with Existing Roles
- Partner with Project Managers on planning, dependencies, capacity, and reporting.
- Help Product Managers keep backlog discussions focused and ready for delivery.
- Facilitate clear technical and cross-team escalation with Developers.
- Include QA/Testing early when defining ready work and acceptance criteria.

### Typical Communication
- Team ceremonies and facilitation notes
- Impediment and action logs
- Weekly delivery and dependency updates

---

## UX/Design Lead

### Role Summary
The UX/Design Lead represents customer and usability needs, translating research and requirements into coherent, testable experiences.

### Responsibilities
- Translate customer needs and product requirements into user flows and designs
- Validate concepts through research, prototypes, or usability testing
- Maintain design standards and accessibility expectations
- Collaborate on implementation feasibility and design quality
- Help define acceptance criteria that cover user experience

### Goals
- Deliver usable, accessible, and consistent experiences
- Reduce late-stage design rework
- Improve customer outcomes through evidence-informed design decisions

### Interactions with Existing Roles
- Collaborate with Product Managers on user needs, requirements, and success measures.
- Pair with Developers on feasibility, interaction details, and implementation review.
- Work with QA/Testing to establish usability and accessibility acceptance checks.
- Surface unresolved customer or design risks to Project Managers and Product leadership.

### Typical Communication
- Design reviews and research readouts
- Prototypes, flow diagrams, and design specifications
- Acceptance criteria and usability feedback

---

## Data/Analytics Lead

### Role Summary
The Data/Analytics Lead defines how project outcomes will be measured, validated, and reported so delivery decisions remain evidence-based.

### Responsibilities
- Define success metrics and reporting requirements
- Design or review instrumentation and event definitions
- Validate data quality and analytical assumptions
- Produce delivery, adoption, and outcome insights
- Recommend measurement changes based on observed results

### Goals
- Ensure decisions are supported by trustworthy metrics
- Improve instrumentation completeness before launch
- Reduce ambiguity about whether project outcomes are achieved

### Interactions with Existing Roles
- Align success measures and hypotheses with Product Managers.
- Partner with Developers on event schemas, instrumentation, and observability.
- Give Project Managers delivery insights and data-quality risks for reporting.
- Define measurement evidence and acceptance checks with QA/Testing.

### Typical Communication
- Metrics and instrumentation plans
- Dashboards and experiment or launch analyses
- Weekly delivery and outcome reviews

---

## Security Lead

### Role Summary
The Security Lead establishes security requirements, reviews threat mitigations, and coordinates security validation across delivery and release activities.

### Responsibilities
- Identify security requirements and relevant threat scenarios
- Review designs and implementations for security risks
- Coordinate security testing and remediation with QA/Testing
- Advise Developers on secure design and implementation practices
- Escalate material risks and exceptions to Project and Product leadership

### Goals
- Reduce security risk in delivered solutions
- Detect and remediate vulnerabilities before exposure
- Make security decisions, exceptions, and ownership explicit

### Interactions with Existing Roles
- Advise Product Managers on security constraints and trade-offs.
- Work with Developers on threat mitigations, secure implementation, and remediation.
- Coordinate security scans, tests, and findings with QA/Testing.
- Provide risk updates to Project Managers and escalate unresolved or business-impacting issues through the project escalation path.
- Confirm security readiness before go/no-go decisions with the Release Manager or Coordinator.

### Typical Communication
- Threat models and security review records
- Vulnerability findings and remediation plans
- Security incidents and exception escalation

---

## Customer Success or Support Lead

### Role Summary
The Customer Success or Support Lead represents customer-facing needs and operational readiness, ensuring users and support teams are prepared for changes.

### Responsibilities
- Gather customer feedback and recurring support concerns
- Assess operational readiness and support coverage
- Prepare support documentation, training, and escalation routes
- Coordinate customer communications and known-issue guidance
- Bring customer insights into prioritization and retrospectives

### Goals
- Improve customer readiness and satisfaction
- Reduce avoidable support demand and unresolved escalations
- Ensure customer feedback influences product improvements

### Interactions with Existing Roles
- Share customer needs and operational risks with Product Managers.
- Coordinate support materials and launch readiness with the Release Manager or Delivery Lead.
- Help Developers and QA/Testing understand real-world scenarios and known issues.
- Give Project Managers a view of readiness, stakeholder concerns, and support impacts.
- Contribute evidence and follow-through actions to retrospectives.

### Typical Communication
- Customer advisory sessions and support readouts
- Release readiness and known-issue communications
- Retrospective feedback and prioritized support actions

---

## Collaboration and Escalation Map

- **Scope and outcomes:** Product Manager is accountable for what to build and success measures; UX, Data/Analytics, Security, and Customer Success contribute requirements and evidence.
- **Delivery coordination:** Project Manager owns schedules, dependencies, risks, and stakeholder reporting; the Delivery Facilitator supports team flow and impediment removal.
- **Implementation:** Developers own implementation and technical quality; they coordinate feasibility and readiness with UX, Data/Analytics, Security, QA/Testing, and the Release Coordinator.
- **Release decision:** the Release Coordinator assembles readiness evidence and facilitates go/no-go; QA/Testing verifies acceptance, Security validates applicable risks, and the Project or Product Lead makes or delegates final business approval.
- **Escalation:** team-level impediments go through standups or the Delivery Facilitator, delivery and cross-team risks go to the Project Manager, and product or business-impact decisions go to the Product Manager and Sponsor/leadership as appropriate.

Not every persona is required on every project. Teams should assign a primary owner, combine roles only when capacity and accountability remain clear, and document role assignments in the project plan or one-pager.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

