# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management process documentation. These guides help our teams run consistent, iterative, and customer-focused projects.

## Core Principles
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle
OctoAcme projects follow five phases:
1. **Initiation** - Validate need, align stakeholders, create lightweight plan
2. **Planning** - Break work into shippable increments, identify risks and dependencies
3. **Execution** - Build, test, review, and iterate
4. **Release** - Deploy, verify, and announce
5. **Close & Retrospective** - Capture learnings and next steps

## OctoAcme Project Management Processes Overview

OctoAcme operates a structured, lifecycle-based project management approach designed to balance customer value, iterative delivery, and clear ownership. The methodology encompasses five core phases—Initiation (validating business need and aligning stakeholders), Planning (breaking work into shippable increments with defined acceptance criteria), Execution (building, testing, and iterating with daily standups and weekly syncs), Release (deploying to production with pre-flight checks and rollback plans), and Close & Retrospective (capturing learnings and continuous improvement). This phased approach ensures that projects move through a decision gate at each stage—particularly after initiation, where success metrics must be clear and stakeholder alignment confirmed before proceeding to detailed planning. The methodology emphasizes small, testable increments and data-informed decisions, positioning product value and usability as primary drivers.

Organizational roles and responsibilities are clearly defined to enable efficient coordination. The **Project Manager** owns schedules, risks, and communications; the **Product Manager** defines outcomes, prioritizes the backlog, and measures success; **Developers** implement features while collaborating on design and testability; and **QA/Testing** validates quality against acceptance criteria. This distributed ownership model is reinforced by a structured communication cadence: daily standups (15 minutes) for progress and blockers, weekly PM-PdM alignment, twice-weekly delivery team standups, and monthly stakeholder updates. Cross-team dependencies and risks are surfaced early through a Risk Register (tracking ID, description, impact, likelihood, mitigation, and status) and escalated through a three-level hierarchy—from team triage to PM escalation to sponsor-level involvement—ensuring visibility and swift resolution of blockers.

Quality and delivery practices are embedded throughout the execution phase to reduce risk and ensure consistent outcomes. Teams use GitHub Projects-style boards with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done), maintain pull request discipline (≤400 lines when possible with automated CI testing and linting), and require at least one approval before merging. Testing expectations include unit tests for new logic, integration and end-to-end smoke tests for critical flows, and security scanning in CI. Each project maintains a Definition of Done, standardized acceptance criteria, and velocity/burndown metrics to track progress against success criteria defined in the Project One-pager. Pre-release checks—including passing CI, drafted release notes, and prepared rollback plans—gate deployment, while post-deployment verification and incident playbooks mitigate production risk.

Finally, OctoAcme institutionalizes learning and continuous improvement through retrospectives held after each sprint or milestone, structured around "what went well," "what could improve," and prioritized action items. Improvements are tracked in the project backlog with clear owners and timelines, and their impact is measured to create a culture of iterative refinement. This commitment to psychological safety, evidence-based decisions, and captured institutional knowledge—stored in versioned documentation and accessible via Copilot Spaces—reduces single-person dependency risk and accelerates onboarding of new team members into a consistent, repeatable execution model.

## Documentation Index

### Getting Started
- [OctoAcme Project Management Overview](./octoacme-project-management-overview.md) - Introduction to roles, principles, and artifacts
- [OctoAcme Roles & Personas](./octoacme-roles-and-personas.md) - Role definitions for Developers, Product Managers, and Project Managers

### By Project Phase
- [Project Initiation Guide](./octoacme-project-initiation.md) - Steps to validate and authorize work
- [Project Planning](./octoacme-project-planning.md) - Turn approved initiatives into actionable plans
- [Execution & Tracking](./octoacme-execution-and-tracking.md) - Day-to-day delivery management
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) - Standardized release processes
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) - Capturing learnings

### Cross-Cutting Concerns
- [Risk Management & Communication](./octoacme-risks-and-communication.md) - Managing risks, dependencies, and stakeholder updates

## Quick Start for New Team Members
1. Start with [OctoAcme Project Management Overview](./octoacme-project-management-overview.md) for a high-level understanding
2. Review [Roles & Personas](./octoacme-roles-and-personas.md) to understand your role
3. Jump to the phase-specific guide for your current project stage
4. Reference cross-cutting docs (Risk Management, Communication) as needed

## Questions?
Reach out to your Project Manager or Product Lead for guidance on applying these processes to your project.
