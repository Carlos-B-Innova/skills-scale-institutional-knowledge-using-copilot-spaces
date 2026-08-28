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

### Interactions with Other Roles
- Collaborate with **Quality Assurance / Testing Lead** on test automation and acceptance validation
- Receive technical guidance from **Technical Lead / Architect** on design decisions
- Report to **Scrum Master / Agile Coach** on blockers and progress
- Implement requirements from **Product Managers** and accept feedback from **Project Managers**

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
- Partner with **Stakeholder / Sponsor** to align on business objectives and success metrics
- Collaborate with **Technical Lead / Architect** on feasibility and trade-offs
- Work with **Project Managers** to prioritize and schedule work
- Coordinate with **Quality Assurance / Testing Lead** on acceptance criteria validation

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
- Report status and escalate blockers to **Stakeholder / Sponsor**
- Facilitate planning and execution with **Scrum Master / Agile Coach**
- Coordinate with **Technical Lead / Architect** on technical milestones and dependencies
- Support **Quality Assurance / Testing Lead** on release readiness and QA scheduling

---

## Quality Assurance / Testing Lead

### Role Summary
Quality Assurance and Testing Leads define and execute testing strategies to validate that features meet acceptance criteria and quality standards before release.

### Responsibilities
- Define test plans and QA approach for each project or milestone
- Develop and maintain acceptance test cases aligned with acceptance criteria
- Execute manual and automated testing, coordinate with developers on test automation
- Validate that Definition of Done is met before PR approval
- Identify and document quality issues and regressions
- Participate in release readiness reviews and smoke testing
- Report quality metrics and testing coverage to the team

### Goals
- Ensure features meet acceptance criteria before merge
- Catch regressions and quality issues early
- Support fast, confident releases
- Maintain high test coverage and observability

### Typical Communication
- Sprint planning and backlog refinement
- Quality review gates in PR process
- Incident and triage discussions
- Release readiness sign-off

### Interactions with Other Roles
- Work with **Developers** to design automated tests and validate test coverage
- Review acceptance criteria with **Product Managers** to ensure test alignment
- Participate in release decisions with **Project Managers** and **Security / Compliance Officer**
- Report quality status to **Scrum Master / Agile Coach** and project stakeholders

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, strategic direction, and approvals for projects. They ensure work aligns with organizational priorities and success metrics.

### Responsibilities
- Provide business problem statement and success metrics
- Approve project charter and resource allocation
- Review and approve release decisions and timelines
- Communicate project status to broader business
- Remove business-level blockers and secure dependencies
- Validate that delivered solution meets business objectives

### Goals
- Ensure project delivers business value and ROI
- Align team priorities with organizational strategy
- Minimize business risk and regulatory/compliance issues
- Drive adoption and business outcomes post-release

### Typical Communication
- Project initiation and charter review
- Monthly stakeholder status updates
- Release approval and announcement
- Quarterly or milestone business impact reviews

### Interactions with Other Roles
- Partner with **Product Managers** to define business outcomes and success criteria
- Receive status reports from **Project Managers** and escalations on business-impacting issues
- Approve releases with input from **Security / Compliance Officer** on regulatory requirements
- Participate in retrospectives and provide strategic feedback to the delivery team

---

## Technical Lead / Architect

### Role Summary
Technical Leads provide technical direction, review architecture decisions, and guide the team on technical risks and trade-offs.

### Responsibilities
- Provide technical guidance on design and implementation approaches
- Review technical proposals and design docs
- Identify technical risks and propose mitigation strategies
- Collaborate on scope and trade-off decisions
- Mentor developers and support technical skill development
- Ensure code quality and architectural consistency
- Support capacity planning based on technical complexity

### Goals
- Deliver scalable, maintainable technical solutions
- Minimize technical debt and architectural risk
- Support team skill development and knowledge sharing
- Reduce rework and unplanned technical work

### Typical Communication
- Design reviews and technical discussions
- Estimation and planning conversations
- Code reviews and architecture guidance
- Risk register and incident response

### Interactions with Other Roles
- Guide **Developers** on architecture and design decisions
- Work with **Product Managers** to evaluate technical feasibility and trade-offs
- Inform **Project Managers** on technical risks and capacity constraints
- Support **Quality Assurance / Testing Lead** on test strategy and automation approaches

---

## Security / Compliance Officer

### Role Summary
Security and Compliance Officers ensure that projects meet security and compliance requirements and are released safely to production.

### Responsibilities
- Define security requirements for features and projects
- Review release readiness for security scanning and compliance
- Coordinate incident response for security issues
- Ensure data privacy and regulatory requirements are met
- Validate that security best practices are followed in code and deployment
- Maintain security incident runbooks and escalation paths

### Goals
- Prevent security vulnerabilities and breaches
- Ensure regulatory and compliance adherence
- Reduce incident severity and response time
- Build secure-by-default culture

### Typical Communication
- Planning and threat assessment discussions
- Release readiness sign-off
- Security incident response and triage
- Post-incident retrospectives

### Interactions with Other Roles
- Partner with **Technical Lead / Architect** on security requirements and design
- Collaborate with **Quality Assurance / Testing Lead** on security testing and validation
- Approve releases with **Project Managers** and communicate risk to **Stakeholder / Sponsor**
- Support **Developers** with security guidance and best practices

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate team processes, remove blockers, and coach the team on agile practices and continuous improvement.

### Responsibilities
- Facilitate sprint ceremonies (planning, standup, review, retrospective)
- Track and remove team blockers and impediments
- Coach team on agile practices and process adherence
- Maintain sprint board and backlog hygiene
- Support retrospective follow-up and action item tracking
- Report team health metrics and process improvements
- Coordinate with PM and PdM on sprint planning

### Goals
- Keep team focused and unblocked
- Continuous process improvement and team velocity
- Foster psychological safety and team engagement
- Reduce sprint disruption and unplanned work

### Typical Communication
- Daily standups and sprint ceremonies
- Backlog refinement and planning sessions
- Retrospectives and action item tracking
- Team health and process improvement discussions

### Interactions with Other Roles
- Work with all team members to identify and remove blockers
- Facilitate communication between **Developers**, **Product Managers**, and **Project Managers**
- Support **Technical Lead / Architect** in providing technical guidance
- Coordinate with **Quality Assurance / Testing Lead** on process improvements and test coverage goals

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Understand role interactions to identify potential communication gaps or single points of failure.
- Map personas to team members and clarify responsibilities across your projects.
