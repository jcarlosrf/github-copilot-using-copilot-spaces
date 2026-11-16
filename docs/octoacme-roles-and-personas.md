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

## UX/UI Designers or User Researchers

### Role Summary
UX/UI Designers or User Researchers bring user needs, usability insights, and product goals into experience decisions. They help ensure solutions are usable, accessible, and aligned with intended customer value.

### Responsibilities
- Gather user feedback, research, and usability insights
- Translate customer problems into user flows, design concepts, and experience requirements
- Collaborate with Product Managers to shape problem framing and success criteria
- Identify accessibility, usability, and edge-case considerations
- Work with Developers and QA/Testing to make designs feasible and testable

### Goals
- Improve usability and customer satisfaction
- Reduce rework caused by unclear or unvalidated requirements
- Ensure user needs are considered throughout design and delivery

### Typical Communication
- Discovery and requirements workshops
- Design reviews and user research readouts
- Design handoffs and acceptance-criteria discussions

### Interaction with Existing Roles
- Partners with Product Managers to connect customer insights to product outcomes and priorities
- Works with Developers to assess feasibility and clarify design intent
- Collaborates with QA/Testing to validate user flows, accessibility, and acceptance criteria
- Shares relevant findings with Project Managers to inform scope, dependencies, and planning

---

## Technical Leads or Architects

### Role Summary
Technical Leads or Architects guide technical direction, system design, and implementation quality. They help teams make informed technical decisions while balancing delivery needs, maintainability, and risk.

### Responsibilities
- Guide architecture, technical patterns, and integration decisions
- Review technical trade-offs for reliability, scalability, and maintainability
- Support Developers with design reviews and technical guidance
- Identify technical risks, constraints, and dependencies
- Communicate technical implications of scope and delivery choices

### Goals
- Enable robust, maintainable technical solutions
- Reduce integration issues and avoidable technical risk
- Improve implementation quality and delivery predictability

### Typical Communication
- Technical design and architecture reviews
- Planning and dependency discussions
- Technical risk updates and implementation guidance

### Interaction with Existing Roles
- Works with Developers on implementation choices, reviews, and technical quality
- Collaborates with Product Managers on feasibility and technical trade-offs affecting outcomes
- Informs Project Managers about technical risks, dependencies, and schedule implications
- Coordinates with QA/Testing on testability and technical validation needs

---

## Delivery or Release Managers

### Role Summary
Delivery or Release Managers coordinate readiness and operational flow from development through deployment. They make release timing, dependencies, and readiness visible to the team.

### Responsibilities
- Coordinate release schedules, milestones, and readiness reviews
- Track cross-team dependencies, blockers, and release risks
- Support deployment, rollback, and release communication planning
- Coordinate validation and readiness activities with QA/Testing and operations
- Keep stakeholders informed about release status and changes

### Goals
- Improve release predictability and readiness
- Reduce deployment surprises and coordination gaps
- Ensure teams and stakeholders understand launch timing and responsibilities

### Typical Communication
- Release readiness checkpoints
- Milestone, dependency, and deployment updates
- Launch coordination with delivery teams and stakeholders

### Interaction with Existing Roles
- Partners with Project Managers on schedules, dependencies, risks, and status communication
- Coordinates with Developers and QA/Testing on release criteria, validation, and deployment readiness
- Aligns with Product Managers on feature readiness and launch expectations
- Works with Customer Support or Operations representatives on handoff and operational readiness

---

## Security or Privacy Leads

### Role Summary
Security or Privacy Leads help teams identify and address security, privacy, and data-protection concerns throughout project delivery.

### Responsibilities
- Advise on security and privacy requirements, risks, and controls
- Review designs and data flows for potential exposure or compliance concerns
- Support threat modeling, security reviews, and mitigation planning
- Identify when risks require escalation or specialist review
- Coordinate security and privacy validation with QA/Testing

### Goals
- Reduce security and privacy risks
- Protect customer data and trust
- Address relevant controls and review needs early in delivery

### Typical Communication
- Design and risk reviews
- Security or privacy findings and remediation updates
- Release readiness and escalation discussions for material risks

### Interaction with Existing Roles
- Advises Developers on secure implementation and privacy-aware design
- Works with Product Managers to clarify requirements and customer or regulatory implications
- Partners with Project Managers to track risk, dependencies, and escalation
- Collaborates with QA/Testing on validation and evidence for required controls

---

## Customer Support or Operations Representatives

### Role Summary
Customer Support or Operations Representatives bring customer-facing and service-operational perspectives into planning, release readiness, and ongoing delivery.

### Responsibilities
- Share customer issues, support trends, and operational feedback
- Identify support, monitoring, documentation, and service-readiness needs
- Help plan customer communications, support coverage, and launch handoffs
- Provide feedback on incident response and post-release service impact

### Goals
- Improve customer experience and service continuity
- Reduce post-release support friction and operational surprises
- Ensure delivered solutions can be supported effectively

### Typical Communication
- Support and operational readiness reviews
- Launch and handoff planning
- Customer-impact feedback and incident follow-up

### Interaction with Existing Roles
- Shares customer insights and support needs with Product Managers to inform priorities and outcomes
- Coordinates with Project Managers on launch planning, handoffs, and stakeholder communication
- Works with Developers and QA/Testing to surface operational requirements and validate readiness
- Partners with Delivery or Release Managers on support coverage and launch coordination

---

## Role Interaction Model

These personas describe responsibilities, not necessarily separate positions. Depending on project size and context, one person may cover multiple roles. Teams should make ownership and handoffs explicit during planning, especially where responsibilities overlap.

- Product Manager and UX/UI Designer or User Researcher: connect customer needs, product outcomes, and experience quality
- Project Manager and Delivery or Release Manager: coordinate plans, dependencies, delivery status, and release readiness
- Developers and Technical Lead or Architect: design, build, and validate solutions with appropriate technical guidance
- Developers, Security or Privacy Lead, and QA/Testing: address security and privacy requirements through implementation and validation
- Product Manager, Project Manager, and Customer Support or Operations Representative: align customer impact, launch readiness, and operational handoff

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- For small teams, multiple responsibilities may be combined in a single person without changing the intent of the role model.
