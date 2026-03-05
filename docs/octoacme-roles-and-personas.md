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

## UX/UI Designer

### Role Summary
UX/UI Designers craft user experiences and interfaces that are intuitive, accessible, and aligned with product goals. They bridge user needs and technical implementation, ensuring delivered features are usable and meet design standards.

### Responsibilities
- Collaborate with Product Managers to clarify user journeys, personas, and design requirements
- Produce wireframes, prototypes, and user flows for review and iteration
- Participate in usability reviews and incorporate feedback from users and stakeholders
- Define and maintain a shared design system or component library
- Validate that implemented UIs match approved designs

### Goals
- Deliver designs that meet user needs and improve product usability
- Reduce ambiguity for developers through clear, well-documented design specs
- Ensure accessibility and consistency across all product surfaces

### Typical Communication
- Design reviews and feedback sessions with Product Managers and Developers
- Handoff documentation (e.g., Figma links, annotated specs) shared at sprint start
- Async updates in project channels when designs change or are finalised

### Interactions with Other Roles
- **Product Managers (PdM):** Receive product requirements and user research; collaborate on feature scope and acceptance criteria
- **Developers:** Hand off design specs; answer implementation questions; review delivered UIs against designs
- **QA Lead:** Align on UI acceptance criteria so visual and UX defects are caught during testing
- **Business Analyst:** Incorporate business process flows into UX designs

---

## QA Lead / QA Engineer

### Role Summary
QA Leads define the quality assurance strategy, coordinate testing activities, and ensure that all deliverables meet agreed acceptance criteria before release. QA Engineers execute test plans, report defects, and support continuous quality improvement.

### Responsibilities
- Develop and maintain test plans, test cases, and test data strategies
- Coordinate manual and automated testing activities across sprints
- Report, triage, and track defects to resolution
- Define and maintain the Definition of Done for quality gates
- Validate release readiness and sign off on deployment go/no-go decisions

### Goals
- Prevent defects from reaching production
- Improve test coverage and reduce regression risk
- Provide the team with timely, actionable quality signals

### Typical Communication
- Sprint ceremonies (planning, reviews) to clarify acceptance criteria
- Defect reports and test result summaries shared with the team
- Go/no-go status communicated to Project Manager and Release Manager ahead of releases

### Interactions with Other Roles
- **Developers:** Collaborate on test coverage, review fixes for regressions, and clarify acceptance criteria
- **Project Managers (PM):** Report testing progress and flag quality risks that may affect timelines
- **Product Managers (PdM):** Align on acceptance criteria and validate that delivered features meet product intent
- **Release Manager:** Provide test sign-off as part of release readiness; escalate blocking defects
- **UX/UI Designer:** Validate delivered UI against design specifications to catch visual defects

---

## Release Manager

### Role Summary
Release Managers oversee release planning, deployment coordination, and change management. They ensure that every release is well-communicated, thoroughly verified, and can be safely rolled back if needed.

### Responsibilities
- Define and maintain the release schedule and deployment windows
- Coordinate pre-release readiness across development, QA, and operations teams
- Ensure release notes, runbooks, and rollback plans are documented and reviewed
- Communicate release timelines and post-release status to stakeholders and support teams
- Own and execute rollback or incident response plans when deployments encounter issues

### Goals
- Deliver reliable, predictable releases with minimal disruption
- Maintain clear audit trails and communication records for every deployment
- Reduce release risk through standardised processes and checklists

### Typical Communication
- Release readiness reviews with QA Lead, Developers, and Project Manager ahead of each deployment
- Release announcements and post-release summaries to stakeholders and Support Lead
- Incident notifications and post-mortems when releases cause issues

### Interactions with Other Roles
- **Project Managers (PM):** Align release schedule with project milestones and resource availability
- **Developers:** Confirm deployment artefacts are ready, run pre-production smoke tests
- **QA Lead:** Receive test sign-off; act on blocking defects before proceeding with deployment
- **Support Lead:** Brief on upcoming changes so support teams are prepared for user impact
- **Product Managers (PdM):** Confirm feature flags, staged rollout plans, and stakeholder communication

---

## Support Lead

### Role Summary
Support Leads represent the customer support function in the project lifecycle. They ensure teams are ready to handle user issues after launch and feed customer insights back into the product and project process.

### Responsibilities
- Review release plans and documentation to assess support impact
- Prepare support runbooks, FAQs, and training materials ahead of launches
- Manage escalation channels for support issues post-launch
- Gather and relay user or customer feedback to Product Managers and QA
- Coordinate incident communication when production issues affect customers

### Goals
- Minimise customer impact from new releases and incidents
- Ensure support teams have the information and tools they need before go-live
- Turn customer feedback into actionable product insights

### Typical Communication
- Pre-release briefings from Release Manager and Project Manager
- Post-launch status updates and feedback summaries shared with Product Manager
- Incident updates coordinated with Release Manager and Project Manager during outages

### Interactions with Other Roles
- **Release Manager:** Receive advance notice of deployments and participate in go/no-go decisions
- **Project Managers (PM):** Raise support readiness risks that may affect release timing
- **Product Managers (PdM):** Share customer feedback and surface support-driven feature requests
- **QA Lead:** Collaborate on known issues lists and workaround documentation for support use

---

## Business Analyst

### Role Summary
Business Analysts translate business needs into clear, actionable requirements. They bridge the gap between stakeholders and the delivery team, ensuring solutions address real business problems and measurable outcomes.

### Responsibilities
- Gather, document, and validate business and process requirements from stakeholders
- Produce requirements artefacts (user stories, process maps, use cases) for the team
- Support Product Managers in backlog prioritisation based on business value
- Validate that delivered solutions meet original requirements and business goals
- Identify and document process gaps or improvement opportunities

### Goals
- Ensure requirements are complete, unambiguous, and traceable
- Reduce rework caused by misunderstood or missing requirements
- Support alignment between business stakeholders and the delivery team

### Typical Communication
- Requirements workshops and stakeholder interviews to gather and validate needs
- Requirements documentation and user stories shared with Product Managers and Developers
- Validation sign-off with stakeholders at sprint reviews or milestones

### Interactions with Other Roles
- **Product Managers (PdM):** Collaborate on backlog refinement and requirement prioritisation; align on acceptance criteria
- **Project Managers (PM):** Share requirement dependencies and risks that could affect scope or timeline
- **Developers:** Clarify requirements and answer questions during implementation
- **UX/UI Designer:** Provide business process context to inform UX flows and interface decisions
- **Stakeholders:** Serve as the primary liaison for requirements gathering and solution validation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [Cross-functional RACI & Handoffs Checklist](octoacme-cross-functional-raci-and-handoffs.md) for a concise view of who owns what at each stage of the project lifecycle.

