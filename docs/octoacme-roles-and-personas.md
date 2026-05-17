# OctoAcme Personas & Role Framework

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises, and provides a framework for composing teams based on project scope and risk.

---

## Core Roles

### Developers

**Role Summary**  
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

**Responsibilities**
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

**Goals**
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

**Typical Communication**
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

**When to Engage**  
Present on all projects.

---

### Product Managers

**Role Summary**  
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

**Responsibilities**
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

**Goals**
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

**Typical Communication**
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

**When to Engage**  
Present on all projects; leads cross-functional prioritization and outcome measurement.

---

### Project Managers

**Role Summary**  
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

**Responsibilities**
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

**Goals**
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

**Typical Communication**
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

**When to Engage**  
Present on all projects; increases in engagement for cross-functional or high-risk initiatives.

---

## Extended Core Roles

The following roles provide specialized expertise critical for delivering high-quality, secure, and well-operationalized products. **Each project should explicitly decide which extended roles to engage based on scope and risk.**

---

### Technical Lead / Architect

**Role Summary**  
Provides technical direction and architectural guidance for the project. Ensures the solution aligns with platform standards and long-term maintainability.

**Responsibilities**
- Define high-level architecture and key technical decisions
- Review and approve major design proposals and RFCs
- Help unblock developers on complex technical challenges
- Ensure alignment with platform and security standards

**Interactions**
- Works closely with Developers and Project Managers to translate timelines into feasible technical plans
- Advises Product Managers on technical trade-offs and impact on timelines
- Consults with DevOps/Platform Engineers on deployment and operational requirements

**When to Engage**  
- Required for: platform architecture changes, significant technical debt, cross-service integrations, performance-critical features
- Recommended for: any project with 3+ developers or complex technical decisions

---

### QA Lead / Test Engineer

**Role Summary**  
Owns test strategy and quality standards for the project, ensuring acceptance criteria are validated and regressions are prevented.

**Responsibilities**
- Define test plans (unit, integration, e2e, regression)
- Maintain test automation and CI quality gates
- Coordinate manual QA efforts for feature acceptance
- Track and report test coverage and quality metrics

**Interactions**
- Collaborates with Developers to ensure testability and to pair on flaky test investigations
- Works with Project Managers to schedule QA cycles and gating criteria
- Provides feedback to Product Managers on readiness for release

**When to Engage**  
- Required for: customer-facing features, production systems, regulated environments
- Recommended for: any project where quality is a release gate

---

### UX Designer / Researcher

**Role Summary**  
Owns user experience and usability aspects of the product, validates designs with research and ensures designs meet accessibility standards.

**Responsibilities**
- Create wireframes, mockups, and interaction designs
- Run user research and usability testing to validate assumptions
- Document UX acceptance criteria and accessibility requirements
- Hand off designs and assets to Developers with clear specs

**Interactions**
- Partners with Product Managers to validate problem statements and prioritize UX work
- Works with Developers and QA on implementation details and accessibility testing
- Presents designs during demos and incorporates stakeholder feedback

**When to Engage**  
- Required for: user-facing features, significant UX changes, accessibility initiatives
- Recommended for: any feature where user experience is a success metric

---

### DevOps / Platform Engineer

**Role Summary**  
Ensures the platform and pipelines are reliable, scalable, and secure. Owns deployment automation and operational tooling.

**Responsibilities**
- Maintain CI/CD pipelines and infrastructure-as-code
- Define deployment and rollback strategies
- Monitor platform health and respond to operational issues
- Implement observability (metrics, logs, tracing) for new features

**Interactions**
- Collaborates with Developers and Technical Leads on deployment requirements
- Works with Project Managers to schedule releases and coordinate rollout windows
- Engages with Security Engineers on hardening and compliance requirements

**When to Engage**  
- Required for: new deployments, infrastructure changes, production releases
- Recommended for: any project affecting operational reliability

---

### Security Engineer

**Role Summary**  
Ensures the project meets security and compliance requirements and addresses security risks early in the lifecycle.

**Responsibilities**
- Conduct threat modeling and security reviews
- Run security scans and code reviews for vulnerabilities
- Define security acceptance criteria for features
- Coordinate incident response for security events

**Interactions**
- Advises Developers and Technical Leads on secure design
- Partners with DevOps/Platform Engineers for secure deployment/configuration
- Communicates risks and mitigations to Project Managers and Product Managers

**When to Engage**  
- Required for: features handling user data, authentication/authorization, compliance requirements, public-facing systems
- Recommended for: any project with moderate security risk

---

### Data Analyst / Metrics Owner

**Role Summary**  
Defines the success metrics, instrumentation, and reporting needed to measure outcomes and guide product decisions.

**Responsibilities**
- Design and maintain event instrumentation and dashboards
- Validate tracking and data quality
- Analyze usage data to inform prioritization and measure success
- Provide regular reports to Product Managers and stakeholders

**Interactions**
- Works with Product Managers to define success metrics and experiments
- Collaborates with Developers to implement instrumentation
- Shares findings in demos and weekly status updates

**When to Engage**  
- Required for: features with defined success metrics or experiments
- Recommended for: any project where measurement drives decisions

---

### Release Manager

**Role Summary**  
Coordinates release activities, communicates timelines, and ensures all pre-release checklists are complete.

**Responsibilities**
- Maintain release calendar and coordinate cross-team cutovers
- Verify pre-release requirements (tests, security scans, release notes)
- Coordinate rollbacks and mitigation plans when needed
- Serve as the release point-of-contact for stakeholders

**Interactions**
- Works with Project Managers and DevOps to schedule and execute releases
- Communicates status to Product Managers, support, and stakeholders
- Coordinates with Support/Customer Success for release communications

**When to Engage**  
- Required for: coordinated multi-team releases, high-risk deployments
- Recommended for: any release involving stakeholder notifications

---

### Support / Customer Success Liaison

**Role Summary**  
Represents customer and support interests during planning and ensures smooth handover at release.

**Responsibilities**
- Surface common customer issues and feature requests
- Prepare support runbooks and customer-facing documentation
- Coordinate post-release monitoring and feedback loops

**Interactions**
- Collaborates with Product Managers on prioritization based on customer impact
- Works with Developers and QA on reproducible steps for support cases
- Notifies Project Managers of customer-impacting incidents

**When to Engage**  
- Required for: customer-facing releases, high-impact features
- Recommended for: any feature affecting customer operations

---

## Role Engagement Model

Use this framework to compose your team based on project scope, risk, and complexity.

### Minimal Team
**For small, low-risk projects or rapid prototypes**

Core members:
- Project Manager
- Product Manager
- Developers (1–3)
- QA Lead (or shared QA responsibility)

Use for:
- Internal tools and utilities
- Bug fixes and small improvements
- Prototypes with no cross-team dependencies
- Well-contained scope with minimal new infrastructure

---

### Standard Team
**For typical cross-functional features and platform improvements**

Core members:
- Project Manager
- Product Manager
- Technical Lead / Architect
- Developers (3–8)
- QA Lead / Test Engineer
- DevOps / Release Manager
- Data Analyst / Metrics Owner

Extended members (as needed):
- UX Designer / Researcher (if UX changes)
- Security Engineer (if data or auth-related)
- Support Liaison (if customer-facing)

Use for:
- Customer-facing features
- Platform improvements affecting multiple teams
- New integrations or services
- Features with defined success metrics
- Typical feature release cadence

**Planning Guidance:**
- Assign Technical Lead early (planning phase)
- Engage QA Lead in sprint planning for test strategy
- Include DevOps/Release Manager for deployment planning
- Coordinate with Data Analyst for instrumentation and success metrics

---

### Extended Team
**For platform-level work, high-risk initiatives, or enterprise projects**

All Standard Team roles, plus:
- Security Engineer (core)
- UX Designer / Researcher (core)
- Support / Customer Success Liaison (core)

Use for:
- Major feature launches with customer impact
- Security, compliance, or privacy initiatives
- Platform architecture changes
- Cross-team or cross-org dependencies
- Features affecting operational reliability or user trust
- Regulated or enterprise-grade systems

**Planning Guidance:**
- Conduct Security review in planning; integrate Security Engineer early
- Run UX research; incorporate findings into acceptance criteria
- Plan Support handover and runbook creation in advance
- Schedule extended stakeholder engagement and approvals
- Anticipate longer review cycles for high-risk approval gates

---

## Decision Tree: Choosing Your Team

1. **Is this a contained internal change with no new infrastructure?**
   - Yes → Minimal Team
   - No → Continue

2. **Does this involve customer data, authentication, or compliance?**
   - Yes → Include Security Engineer → Consider Extended Team
   - No → Continue

3. **Is this a user-facing feature or significant UX change?**
   - Yes → Include UX Designer → Consider Extended Team
   - No → Continue

4. **Does this require platform/infrastructure changes or multi-team coordination?**
   - Yes → Include Technical Lead & DevOps → Standard Team or Extended
   - No → Continue

5. **Is this a release or feature with high customer visibility or impact?**
   - Yes → Include Release Manager & Support Liaison → Standard Team or Extended
   - No → Standard Team (minimum)

---

## How These Roles Work Together

**Planning Phase:**
- PM/PdM: Define scope and success metrics
- Technical Lead: Assess technical feasibility and architecture
- Project Manager: Create timeline and identify dependencies
- All specialists: Provide estimates and risk input for their domains

**Execution Phase:**
- Developers & Technical Lead: Implement and review
- QA/Security/UX: Validate against acceptance criteria and standards
- Data Analyst: Ensure instrumentation is in place
- Project Manager: Track progress and manage blockers

**Release Phase:**
- Release Manager: Coordinates handoff and deployment
- QA Lead: Verifies release readiness
- Support/Success Liaison: Prepares customer communication and runbooks
- DevOps: Executes deployment and monitoring
- All: Monitor post-release and respond to issues

---

## Minimal Assignment Per Project Example

Every project should have at least:
- **Project Manager**: overall delivery and risk
- **Product Manager**: outcomes and prioritization
- **Developers**: build and tests
- **QA Lead**: release readiness and test strategy

Then add specialists based on the Decision Tree above.

---

## How These Personas Are Used

- Use these role definitions to frame scenarios and sample interactions in exercises and planning
- Reference this document during project kickoffs to explicitly assign roles and clarify responsibilities
- Use the Decision Tree and Engagement Model to guide team composition discussions
- Each role can be used as a persona prompt for Copilot Spaces to shape role-specific guidance
