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

## QA/Testing Lead

### Role Summary
QA/Testing Leads drive quality assurance strategy and own acceptance testing across the project. They partner with developers and product managers to define testability requirements and validate that features meet acceptance criteria before release.

### Responsibilities
- Define test plans aligned with acceptance criteria
- Execute acceptance criteria verification and sign-off
- Manage test coverage and identify gaps
- Identify and escalate quality blockers
- Mentor developers on testing best practices

### Goals
- Ensure features meet quality standards before release
- Catch defects early and reduce production incidents
- Maintain and improve test automation coverage
- Enable faster, more confident releases

### Typical Communication
- Sprint planning and acceptance criteria reviews
- Test plans and quality reports
- Collaboration with developers on test design
- Quality metrics and risk escalation to the Project Manager

### Interactions
- With Developers: Reviews test design, collaborates on test automation strategy, and identifies testability risks.
- With Product Managers: Clarifies acceptance criteria and validates feature completeness.
- With Project Managers: Escalates quality risks that may affect release plans or milestones.

---

## Scrum Master / Iteration Lead

### Role Summary
Scrum Masters facilitate agile ceremonies and remove team impediments to maintain flow and velocity. They coach the team on agile practices and help shield delivery teams from distractions that reduce focus.

### Responsibilities
- Facilitate daily standups, planning, and retrospectives
- Support sprint or iteration backlog health and prioritization
- Identify and surface team blockers promptly
- Coach team members on agile practices
- Protect team focus and capacity

### Goals
- Maintain consistent team velocity
- Keep communication flowing across disciplines
- Remove organizational friction that slows delivery
- Foster a culture of continuous improvement

### Typical Communication
- Daily standups and sprint ceremonies
- Blocker updates and escalation tracking
- Retrospective facilitation and action item tracking
- Team health and velocity metrics

### Interactions
- With Project Managers: Partners on sprint planning and escalates schedule-impacting blockers.
- With Developers: Removes impediments, facilitates knowledge sharing, and protects focus time.
- With Product Managers: Ensures backlog is ready for planning and communicates sprint capacity constraints.

---

## Technical Architect

### Role Summary
Technical Architects provide technical direction and strategy, mitigating architectural risks and ensuring solutions are scalable, maintainable, and secure. They advise on technology choices and help prevent costly rework.

### Responsibilities
- Design technical approaches for complex features and systems
- Review critical pull requests and technical designs
- Identify and flag technical debt and architectural risks
- Advise on technology selections and trade-offs
- Mentor developers on architectural patterns and best practices

### Goals
- Ensure scalable, maintainable, and secure architecture
- Prevent costly rework from poor design decisions
- Reduce technical debt accumulation
- Enable team confidence in technical direction

### Typical Communication
- Technical design reviews and architecture discussions
- Code review feedback on critical PRs
- Risk assessments and technical trade-off analysis
- Technical documentation and decision records

### Interactions
- With Developers: Collaborates on design, reviews critical code, and mentors on best practices.
- With Project and Product Managers: Advises on technical trade-offs and resource implications.
- With Security/Compliance Lead: Reviews designs for security and compliance considerations.
- With Project Managers: Escalates architectural risks that affect schedule or quality.

---

## Sponsor / Stakeholder Representative

### Role Summary
Sponsors represent business and stakeholder interests, provide strategic direction, and make go/no-go decisions. They allocate resources, approve scope changes, and ensure project alignment with business strategy.

### Responsibilities
- Approve project scope, changes, and trade-offs
- Allocate budget and resources for the project
- Make go/no-go decisions at key milestones
- Remove organizational blockers and escalations
- Provide executive visibility and steering

### Goals
- Ensure the project delivers measurable business value
- Make timely strategic decisions
- Maintain executive alignment and visibility
- Enable unblocked progress

### Typical Communication
- Milestone reviews and gate decisions
- Executive status updates and risk escalations
- Scope change approvals and trade-off discussions
- Stakeholder communication and announcements

### Interactions
- With Project Managers: Receives status updates and makes decisions on risks and scope changes.
- With Product Managers: Aligns on business priorities and success metrics.
- With leadership and teams: Escalates organizational blockers and provides resource allocation decisions.

---

## Support / Operations Representative

### Role Summary
Support and Operations Representatives ensure operational readiness and successful customer adoption. They define operational requirements, plan deployment support, and identify production risks early.

### Responsibilities
- Define operational and support requirements
- Plan rollout strategy and support materials such as runbooks and FAQs
- Identify production-readiness risks
- Collaborate on user documentation and training
- Ensure smooth deployment and customer onboarding

### Goals
- Ensure smooth deployment and minimal downtime transitions
- Reduce post-release support burden and escalations
- Enable fast customer adoption and success
- Maintain operational stability and customer satisfaction

### Typical Communication
- Feature reviews for operational impact
- Deployment planning and support readiness checks
- Runbook and documentation collaboration
- Post-deployment verification and incident coordination

### Interactions
- With Developers: Collaborates on operational concerns such as monitoring, logging, and graceful degradation.
- With Product Managers: Advises on user experience and adoption barriers.
- With Project Managers: Coordinates deployment timing, support readiness, and post-release verification.
- With Security/Compliance Lead: Ensures operational practices meet compliance requirements.

---

## Security/Compliance Lead

### Role Summary
Security and Compliance Leads ensure that solutions meet security and regulatory requirements. They review designs for vulnerabilities, define compliance requirements, and embed security into development practices.

### Responsibilities
- Review designs and architectures for security risks
- Define security and compliance requirements
- Review code for vulnerabilities and secure coding practices
- Plan secure deployment and access controls
- Maintain compliance posture and audit readiness

### Goals
- Prevent security incidents and data breaches
- Maintain compliance with regulatory and organizational standards
- Embed security into development culture
- Enable confident, secure deployments

### Typical Communication
- Security design reviews and threat assessments
- Code review feedback and vulnerability remediation
- Compliance requirement definitions and audit reports
- Security incident coordination and remediation

### Interactions
- With Technical Architects: Partners on design review for security and compliance.
- With Developers: Collaborates on secure coding, reviews PRs, and advises on vulnerability fixes.
- With Project Managers: Escalates security risks that affect release decisions.
- With Support/Operations: Ensures secure deployment, access controls, and monitoring.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
