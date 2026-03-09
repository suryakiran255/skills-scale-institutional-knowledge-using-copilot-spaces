# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.
It also adds additional personas to improve clarity, accountability, and handoffs across the delivery lifecycle.

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

## QA Lead (new)

### Role Summary
The QA Lead owns test strategy and verification for a project or release, coordinating test design, automation priorities, and acceptance criteria validation.

### Responsibilities
- Design and maintain the test strategy (unit, integration, regression, e2e)
- Define acceptance-test criteria for features and releases
- Coordinate manual testing and review automated test coverage
- Triage, track, and escalate defects found during testing
- Maintain test environments and test data hygiene
- Feed quality metrics back to the team and stakeholders

### Interaction with existing roles
- Developers: partner to clarify acceptance criteria and triage defects
- Product Manager: validate acceptance criteria and confirm user acceptance tests
- Project Manager: align test timelines with project milestones and release windows
- Release Engineer: coordinate staging verification and smoke tests prior to deployment

### Typical Communication
- Test status in weekly delivery syncs
- QA sign-off comments in PRs and release readiness checklists

---

## Release Engineer (new)

### Role Summary
The Release Engineer owns the release and deployment pipeline, ensuring safe, reproducible, and observable deployments.

### Responsibilities
- Manage and improve CI/CD pipelines and deployment automation
- Maintain release schedules and gating criteria
- Produce and maintain rollback/mitigation plans and runbooks
- Ensure release notes and migration steps are documented
- Coordinate deployment windows and post-deploy verification
- Support incident triage for deployment-related issues

### Interaction with existing roles
- Developers: work to ensure artifacts are buildable and deployable; confirm migration steps
- QA Lead: ensure smoke tests and gating checks run in pipeline
- Project Manager: align release timing and stakeholder notifications
- Product Manager & Stakeholder Liaison: communicate release scope and timing

### Typical Communication
- Release status updates in release channel and weekly syncs
- Release notes and deployment runbooks attached to release artifacts

---

## Stakeholder Liaison (new)

### Role Summary
A dedicated contact who manages communications, expectations, and feedback for external business stakeholders or cross-functional partners.

### Responsibilities
- Consolidate stakeholder feedback and surface prioritized inputs
- Communicate project status, risks, and decisions to external stakeholders
- Organize stakeholder review sessions and approvals
- Escalate stakeholder concerns into the project lifecycle when required

### Interaction with existing roles
- Product Manager: translates stakeholder needs into product requirements and acceptance criteria
- Project Manager: coordinates status reporting, risk communication, and stakeholder approvals
- Release Engineer: ensures stakeholders are informed of release timing and impacts

### Typical Communication
- Stakeholder reports, meeting summaries, and decision logs

---

## Technical Writer (new)

### Role Summary
Creates and maintains documentation that supports development, onboarding, releases, and operational procedures.

### Responsibilities
- Draft and maintain technical documentation, runbooks, and user-facing docs
- Ensure process artifacts (decision logs, READMEs, release notes) are clear and versioned
- Work with Developers, QA, and PMs to translate technical decisions into accessible docs
- Maintain documentation templates and documentation cadence

### Interaction with existing roles
- Developers & QA Lead: gather technical details and testing outcomes for docs
- Project Manager: ensure documentation aligns with project artifacts and timelines
- Release Engineer: produce and verify release notes and deployment instructions

### Typical Communication
- Documentation reviews during planning and before release
- Maintained docs in docs/ and .copilot/ where relevant

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---