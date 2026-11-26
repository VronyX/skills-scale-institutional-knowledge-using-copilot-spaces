# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. These personas help clarify ownership, collaboration, and communication throughout the project management lifecycle.

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

### Interactions with Other Roles
- Product Managers: Clarify requirements, discuss technical trade-offs, and provide estimates.
- Project Managers: Share progress, identify blockers, and communicate delivery risks.
- QA/Testing Leads: Collaborate on test coverage, defect investigation, and quality improvements.
- Technical Leads: Follow technical standards and collaborate on architectural decisions.
- DevOps/Release Engineers: Coordinate CI/CD integration, deployment requirements, and environment issues.

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

### Interactions with Other Roles
- Developers: Communicate product requirements and clarify expected outcomes.
- Project Managers: Align priorities with project timelines and delivery plans.
- Stakeholders/Sponsors: Gather business needs, communicate product outcomes, and align expectations.
- QA/Testing Leads: Define acceptance criteria and validate that features meet user expectations.
- Business and Security Leads: Consider business requirements, security, and compliance constraints.

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

### Interactions with Other Roles
- Product Managers: Coordinate scope, priorities, and delivery expectations.
- Developers: Monitor progress, dependencies, and technical blockers.
- Stakeholders/Sponsors: Provide project updates and escalate significant risks.
- Scrum Masters: Align project-level coordination with team-level Agile practices.
- QA/Testing Leads and DevOps Engineers: Coordinate quality gates and release readiness.

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads define and coordinate quality assurance strategies to ensure deliverables meet functional requirements, acceptance criteria, and quality standards.

### Key Responsibilities
- Define test strategies, test plans, and testing approaches.
- Coordinate manual and automated testing activities.
- Review acceptance criteria and prepare test scenarios.
- Track, prioritize, and communicate defects.
- Validate that fixes meet expected quality standards.
- Provide quality assessments during release readiness reviews.

### Goals
- Prevent defects from reaching production.
- Establish consistent and repeatable testing practices.
- Ensure deliverables meet acceptance criteria.
- Promote a quality-first culture across the team.

### Typical Communication
- Test plans and test execution reports.
- Defect tracking and triage meetings.
- Sprint planning and release readiness discussions.
- Quality metrics and test coverage reports.

### Interactions with Other Roles
- Developers: Collaborate on test coverage, reproduce defects, and verify fixes.
- Product Managers: Clarify acceptance criteria and validate expected product behavior.
- Project Managers: Report quality risks and communicate testing progress.
- DevOps/Release Engineers: Coordinate test environments and automated testing pipelines.
- Stakeholders/Sponsors: Communicate quality status and significant release risks when necessary.

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors represent business interests and provide direction, resources, and support for project initiatives. Sponsors typically have decision-making authority over project funding, priorities, or major scope changes, while stakeholders provide relevant input and feedback.

### Key Responsibilities
- Define and communicate business needs and expected outcomes.
- Provide project sponsorship, resources, and organizational support.
- Review project progress and major milestones.
- Make or support decisions on significant scope, budget, and priority changes.
- Provide feedback and approvals at agreed decision points.
- Help resolve organizational dependencies and escalations.

### Goals
- Ensure projects deliver expected business value.
- Maintain alignment between project outcomes and organizational strategy.
- Support timely decisions and remove organizational obstacles.
- Ensure appropriate stakeholder engagement.

### Typical Communication
- Project kickoff and milestone reviews.
- Executive status reports and progress updates.
- Scope, budget, and priority decision meetings.
- Escalation discussions and approval requests.

### Interactions with Other Roles
- Project Managers: Receive status updates, review risks, and support decisions on scope and resources.
- Product Managers: Align business objectives, product priorities, and expected outcomes.
- Developers: Provide business context through product and project representatives when needed.
- Security/Compliance Leads: Review significant compliance risks and required organizational controls.
- QA/Testing Leads: Review quality status and acceptance outcomes at major milestones.

---

## Security/Compliance Lead

### Role Summary
Security/Compliance Leads ensure that project deliverables follow security policies, regulatory requirements, and organizational compliance standards. They identify security risks and guide teams in implementing appropriate controls.

### Key Responsibilities
- Define and communicate security and compliance requirements.
- Review security risks and recommend mitigation strategies.
- Coordinate security assessments, vulnerability scanning, and compliance checks.
- Support incident response and security-related investigations.
- Review relevant release readiness requirements.
- Maintain security and compliance documentation.

### Goals
- Protect organizational data and systems.
- Reduce security vulnerabilities and compliance risks.
- Ensure security requirements are addressed throughout delivery.
- Promote secure development and operational practices.

### Typical Communication
- Security assessment and vulnerability reports.
- Risk reviews and compliance checklists.
- Security incident reports and response coordination.
- Release readiness and security approval discussions.

### Interactions with Other Roles
- Developers: Provide secure coding guidance and coordinate remediation of vulnerabilities.
- Project Managers: Communicate security risks, dependencies, and mitigation plans.
- Product Managers: Ensure product requirements consider privacy, security, and compliance needs.
- DevOps/Release Engineers: Coordinate infrastructure security, access controls, and deployment safeguards.
- Stakeholders/Sponsors: Escalate significant security risks and communicate compliance concerns.

---

## DevOps/Release Engineer

### Role Summary
DevOps/Release Engineers manage infrastructure, automation, deployment pipelines, and release processes. They help teams deliver software reliably while maintaining system stability, availability, and security.

### Key Responsibilities
- Build and maintain CI/CD pipelines and deployment automation.
- Manage development, testing, staging, and production environments.
- Maintain infrastructure configuration and deployment procedures.
- Monitor system health, availability, and operational performance.
- Coordinate release activities, deployment verification, and rollback procedures.
- Support incident investigation and operational improvements.

### Goals
- Enable reliable and repeatable software deployments.
- Reduce manual deployment effort and operational errors.
- Maintain system availability and observability.
- Improve collaboration between development and operations teams.

### Typical Communication
- Deployment plans and release notes.
- CI/CD pipeline status and infrastructure documentation.
- Operational monitoring and incident reports.
- Release coordination and readiness meetings.

### Interactions with Other Roles
- Developers: Coordinate application build, integration, and deployment requirements.
- QA/Testing Leads: Provide stable test environments and support automated testing.
- Security/Compliance Leads: Implement infrastructure security controls and address vulnerabilities.
- Project Managers: Communicate deployment schedules, dependencies, and release risks.
- Product Managers: Align release timing with product priorities and readiness.

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters/Agile Coaches support teams in applying Agile principles and practices effectively. They facilitate team ceremonies, help remove blockers, and encourage continuous improvement.

### Key Responsibilities
- Facilitate Agile ceremonies such as sprint planning, daily standups, reviews, and retrospectives.
- Help identify and remove impediments affecting team progress.
- Coach team members on Agile principles and practices.
- Encourage collaboration, transparency, and continuous improvement.
- Support effective backlog refinement and sprint execution.
- Help teams identify process improvements and track follow-up actions.

### Goals
- Improve team collaboration and delivery effectiveness.
- Help teams maintain a sustainable pace of work.
- Reduce blockers and unnecessary process friction.
- Encourage continuous learning and improvement.

### Typical Communication
- Daily standups and sprint planning sessions.
- Retrospective notes and improvement action items.
- Team facilitation and coaching discussions.
- Blocker and impediment tracking.

### Interactions with Other Roles
- Developers: Facilitate collaboration, remove blockers, and support effective sprint execution.
- Product Managers: Coordinate backlog refinement and help clarify priorities.
- Project Managers: Align Agile team activities with broader project timelines and dependencies.
- QA/Testing Leads: Encourage quality practices throughout the sprint.
- Stakeholders/Sponsors: Facilitate appropriate engagement during reviews and feedback sessions.

---

## How these personas are used in the exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- These roles may be assigned to different individuals or shared by team members
