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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Suggested Personas

The following personas are recommended additions to improve clarity, accountability, and cross-functional collaboration in OctoAcme projects. Each includes a short description of responsibilities and how they typically interact with existing roles.

### Technical Lead / Architect
Role Summary
- Provides technical direction and architectural guidance for the project. Ensures the solution aligns with platform standards and long-term maintainability.

Responsibilities
- Define high-level architecture and key technical decisions
- Review and approve major design proposals and RFCs
- Help unblock developers on complex technical challenges
- Ensure alignment with platform and security standards

Interactions
- Works closely with Developers and Project Managers to translate timelines into feasible technical plans
- Advises Product Managers on technical trade-offs and impact on timelines
- Consults with DevOps/Platform Engineers on deployment and operational requirements


### QA Lead / Test Engineer
Role Summary
- Owns test strategy and quality standards for the project, ensuring acceptance criteria are validated and regressions are prevented.

Responsibilities
- Define test plans (unit, integration, e2e, regression)
- Maintain test automation and CI quality gates
- Coordinate manual QA efforts for feature acceptance
- Track and report test coverage and quality metrics

Interactions
- Collaborates with Developers to ensure testability and to pair on flaky test investigations
- Works with Project Managers to schedule QA cycles and gating criteria
- Provides feedback to Product Managers on readiness for release


### UX Designer / Researcher
Role Summary
- Owns user experience and usability aspects of the product, validates designs with research and ensures designs meet accessibility standards.

Responsibilities
- Create wireframes, mockups, and interaction designs
- Run user research and usability testing to validate assumptions
- Document UX acceptance criteria and accessibility requirements
- Hand off designs and assets to Developers with clear specs

Interactions
- Partners with Product Managers to validate problem statements and prioritize UX work
- Works with Developers and QA on implementation details and accessibility testing
- Presents designs during demos and incorporates stakeholder feedback


### DevOps / Platform Engineer
Role Summary
- Ensures the platform and pipelines are reliable, scalable, and secure. Owns deployment automation and operational tooling.

Responsibilities
- Maintain CI/CD pipelines and infrastructure-as-code
- Define deployment and rollback strategies
- Monitor platform health and respond to operational issues
- Implement observability (metrics, logs, tracing) for new features

Interactions
- Collaborates with Developers and Technical Leads on deployment requirements
- Works with Project Managers to schedule releases and coordinate rollout windows
- Engages with Security Engineers on hardening and compliance requirements


### Security Engineer
Role Summary
- Ensures the project meets security and compliance requirements and addresses security risks early in the lifecycle.

Responsibilities
- Conduct threat modeling and security reviews
- Run security scans and code reviews for vulnerabilities
- Define security acceptance criteria for features
- Coordinate incident response for security events

Interactions
- Advises Developers and Technical Leads on secure design
- Partners with DevOps/Platform Engineers for secure deployment/configuration
- Communicates risks and mitigations to Project Managers and Product Managers


### Data Analyst / Metrics Owner
Role Summary
- Defines the success metrics, instrumentation, and reporting needed to measure outcomes and guide product decisions.

Responsibilities
- Design and maintain event instrumentation and dashboards
- Validate tracking and data quality
- Analyze usage data to inform prioritization and measure success
- Provide regular reports to Product Managers and stakeholders

Interactions
- Works with Product Managers to define success metrics and experiments
- Collaborates with Developers to implement instrumentation
- Shares findings in demos and weekly status updates


### Release Manager
Role Summary
- Coordinates release activities, communicates timelines, and ensures all pre-release checklists are complete.

Responsibilities
- Maintain release calendar and coordinate cross-team cutovers
- Verify pre-release requirements (tests, security scans, release notes)
- Coordinate rollbacks and mitigation plans when needed
- Serve as the release point-of-contact for stakeholders

Interactions
- Works with Project Managers and DevOps to schedule and execute releases
- Communicates status to Product Managers, support, and stakeholders
- Coordinates with Support/Customer Success for release communications


### Support / Customer Success Liaison
Role Summary
- Represents customer and support interests during planning and ensures smooth handover at release.

Responsibilities
- Surface common customer issues and feature requests
- Prepare support runbooks and customer-facing documentation
- Coordinate post-release monitoring and feedback loops

Interactions
- Collaborates with Product Managers on prioritization based on customer impact
- Works with Developers and QA on reproducible steps for support cases
- Notifies Project Managers of customer-impacting incidents


### How adding these personas helps
- Clearer ownership: each critical area (security, release, QA, UX, platform, metrics) has a named responsibility, reducing ambiguity.
- Faster decision-making: defined interactions and responsibilities prevent back-and-forth and unblock teams sooner.
- Improved quality and outcomes: focused roles ensure test coverage, security posture, observability, and user validation are baked into delivery.
- Better stakeholder communication: Release Managers and Support liaisons provide predictable, customer-facing coordination.


---

## Example: minimal assignment per project
- Project Manager: overall delivery and risk
- Product Manager: outcomes and prioritization
- Technical Lead: architecture and technical direction
- Developers: build and tests
- QA Lead: release readiness and test strategy
- DevOps / Release Manager: deployments and operational readiness
- UX Designer: user validation and accessibility
- Data Analyst: metrics and instrumentation
- Support Liaison: customer handover and runbooks

