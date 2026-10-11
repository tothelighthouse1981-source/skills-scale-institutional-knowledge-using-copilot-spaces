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

## QA / Testing Lead

### Role Summary
The QA / Testing Lead defines and coordinates the quality assurance strategy, ensuring work meets acceptance criteria and quality standards before release.

### Responsibilities
- Define test plans and testing coverage aligned with feature requirements
- Design and maintain test cases and automation
- Coordinate manual and automated testing
- Identify, document, and triage defects with clear reproduction steps
- Validate acceptance criteria and report release readiness

### Collaboration with Other Roles
- Works with Product Managers to clarify acceptance criteria and edge cases
- Partners with Developers to plan testability, automate checks, and resolve defects
- Coordinates with Release Managers on smoke tests and release readiness
- Shares quality risks and progress with Project Managers

### Goals
- Deliver high-quality, reliable software
- Reduce defects escaping to production
- Enable confident releases through effective test coverage and automation

### Typical Communication
- Sprint planning and backlog refinement
- Test plans, defect reports, and daily quality updates
- Acceptance and release readiness reviews

---

## Design / UX Lead

### Role Summary
The Design / UX Lead ensures solutions are user-centered, usable, accessible, and aligned with the product vision.

### Responsibilities
- Conduct user research and validate problem statements
- Create wireframes, prototypes, and design specifications
- Define and maintain design systems and component standards
- Lead design reviews and incorporate feedback
- Ensure accessibility and usability standards are considered
- Support user testing and validation activities

### Collaboration with Other Roles
- Partners with Product Managers and Stakeholders to understand user needs and business goals
- Hands off clear designs and specifications to Developers and reviews implementation
- Works with QA / Testing Leads to include usability and accessibility in validation
- Coordinates design decisions and dependencies with Project Managers

### Goals
- Maximize user satisfaction and product usability
- Reduce design-related rework during development
- Maintain a consistent, accessible user experience

### Typical Communication
- Product planning and requirements discussions
- Design critiques, prototypes, and design specifications
- Development handoffs and user testing sessions

---

## Scrum Master / Team Lead

### Role Summary
The Scrum Master / Team Lead facilitates team health, removes impediments, and helps the team execute efficiently within its agreed process.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Identify blockers and help coordinate their resolution
- Coach the team on process adherence and continuous improvement
- Maintain clear team communication and meeting rhythms
- Escalate capacity or process issues to the appropriate leadership
- Foster psychological safety and team collaboration

### Collaboration with Other Roles
- Works with Developers and other delivery roles to surface blockers and improve team practices
- Coordinates team execution with Project Managers while keeping facilitation distinct from project planning and status ownership
- Aligns priorities and delivery expectations with Product Managers
- Escalates organizational impediments through Project Managers or Sponsors as appropriate

### Goals
- Support predictable, sustainable team delivery
- Remove organizational friction and blockers
- Build a healthy, collaborative team culture

### Typical Communication
- Daily standups and sprint ceremonies
- Blocker and dependency coordination
- Retrospectives, coaching, and continuous improvement discussions

---

## Stakeholder / Sponsor

### Role Summary
The Stakeholder / Sponsor provides business context, approvals, and resources for a project, advocates for its value, and ensures alignment with organizational priorities.

### Responsibilities
- Clarify business needs and expected outcomes
- Provide timely decisions, approvals, and priority guidance
- Confirm or help secure budget and resource support
- Participate in initiation, planning, and key milestone reviews
- Communicate project value and impact to the broader organization
- Help escalate organizational blockers

### Collaboration with Other Roles
- Partners with Product Managers to align business outcomes, product priorities, and success measures
- Provides Project Managers with decisions, resource direction, and timely escalation support
- Consults Developers and Design / UX Leads through Product Managers to understand options and trade-offs
- Receives progress, risks, and decisions needed through agreed stakeholder updates

### Goals
- Ensure projects deliver meaningful business value
- Maintain alignment with organizational strategy
- Enable timely decisions and remove organizational barriers

### Typical Communication
- Project initiation and planning discussions
- Milestone reviews and decision requests
- Regular stakeholder updates on progress, risks, and outcomes

---

## Security Lead

### Role Summary
The Security Lead helps ensure security best practices are incorporated into the project and coordinates the assessment and mitigation of security risks.

### Responsibilities
- Define security requirements and advise on security acceptance criteria
- Review designs and implementation for security concerns
- Coordinate security testing, scans, and threat modeling as appropriate
- Track security risks and recommended mitigations
- Advise on relevant compliance and regulatory requirements
- Coordinate security incident response with the appropriate security on-call

### Collaboration with Other Roles
- Advises Developers and Design / UX Leads on secure design and implementation
- Works with Project Managers to record, assess, and communicate security risks
- Coordinates security validation and release readiness with QA / Testing and Release Managers
- Escalates significant security risks or incidents through established channels and informs affected Stakeholders as appropriate

### Goals
- Protect user data and system integrity
- Reduce security vulnerabilities and incidents
- Support compliance with applicable security requirements

### Typical Communication
- Design and code reviews
- Security risk assessments and mitigation tracking
- Release security checks and incident triage

---

## Release Manager / DevOps Engineer

### Role Summary
The Release Manager / DevOps Engineer manages deployment pipelines and coordinates reliable, repeatable releases and post-deployment verification.

### Responsibilities
- Maintain and improve CI/CD pipelines and deployment automation
- Plan and coordinate deployments with the delivery team
- Monitor deployment health and coordinate post-deploy verification
- Maintain rollback and release incident procedures
- Document release processes and deployment outcomes
- Coordinate infrastructure and operations dependencies

### Collaboration with Other Roles
- Coordinates release timing and communications with Project Managers and Stakeholders
- Works with Developers to maintain build and deployment pipelines
- Aligns smoke tests and release readiness with QA / Testing Leads
- Confirms security checks and mitigations with Security Leads before release
- Coordinates post-deployment issue response with Developers and the team lead

### Goals
- Enable fast, reliable, low-risk deployments
- Reduce manual deployment errors and downtime
- Improve release repeatability and team confidence

### Typical Communication
- Release planning and deployment coordination
- Deployment status, post-deploy verification, and rollback updates
- CI/CD improvements and incident coordination

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
