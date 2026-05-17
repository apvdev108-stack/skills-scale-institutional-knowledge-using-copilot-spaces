# Team Composition Checklist

## Purpose
Provides a practical checklist to help project leads select and validate the right team composition for their project based on scope, risk, and complexity.

## When to Use
During project **initiation** and **planning** phases:
1. **Initial Assessment** (Initiation): Identify which roles are needed
2. **Team Validation** (Planning): Confirm all critical expertise areas are covered

---

## Quick Reference: Role Engagement Criteria

| Role | Minimal | Standard | Extended | When Required |
|------|---------|----------|----------|---------------|
| Project Manager | ✓ | ✓ | ✓ | Always |
| Product Manager | ✓ | ✓ | ✓ | Always |
| Developers | ✓ | ✓ | ✓ | Always |
| QA Lead | ✓ | ✓ | ✓ | Always (shared for Minimal) |
| Technical Lead | - | ✓ | ✓ | 3+ devs or complex tech |
| DevOps / Release Manager | - | ✓ | ✓ | New deployments, prod release |
| Data Analyst | - | ✓ | ✓ | Success metrics or experiments |
| UX Designer | - | (✓) | ✓ | User-facing features |
| Security Engineer | - | (✓) | ✓ | Data, auth, compliance |
| Support Liaison | - | (✓) | ✓ | Customer-facing releases |

**Legend:** ✓ = Required | (✓) = Recommended | - = Not typically needed

---

## Pre-Planning Checklist: "Am I Engaging the Right Roles?"

Use this checklist during **initiation** to assess which team composition fits your project.

### Scope & Complexity Assessment
- [ ] **Project Type**: Identify project type
  - [ ] Internal tool / infrastructure
  - [ ] Feature / product improvement
  - [ ] Platform architecture change
  - [ ] Security / compliance initiative
  
- [ ] **Team Size**: Estimated number of developers
  - [ ] 1–2 developers
  - [ ] 3–5 developers
  - [ ] 6+ developers or cross-team

- [ ] **Release Impact**: Who is affected?
  - [ ] Internal team only
  - [ ] Single team/product
  - [ ] Multiple teams or org-wide
  - [ ] External customers or public

### Risk & Specialty Engagement

- [ ] **Security & Data**: Does this project involve any of the following?
  - [ ] Customer or user data
  - [ ] Authentication / authorization
  - [ ] Compliance requirements (e.g., GDPR, SOC 2)
  - [ ] Public-facing systems
  - **Action**: If yes to any → Engage Security Engineer

- [ ] **User Experience**: Does this project involve any of the following?
  - [ ] User-facing changes
  - [ ] Significant UX changes
  - [ ] Accessibility requirements
  - [ ] First-time user setup or onboarding
  - **Action**: If yes to any → Engage UX Designer

- [ ] **Infrastructure & Operations**: Does this project involve any of the following?
  - [ ] New deployment targets or environments
  - [ ] CI/CD pipeline changes
  - [ ] Observability or monitoring
  - [ ] Scaling or performance improvements
  - **Action**: If yes to any → Engage DevOps / Platform Engineer

- [ ] **Technical Complexity**: Does this project involve any of the following?
  - [ ] Significant architectural decisions
  - [ ] Cross-service integrations
  - [ ] Performance-critical features
  - [ ] Technical debt or refactoring
  - **Action**: If yes to any → Engage Technical Lead

- [ ] **Customer Impact & Release**: Does this project involve any of the following?
  - [ ] Customer-facing release
  - [ ] Multi-team coordination
  - [ ] High-visibility announcement
  - [ ] Rollback or rollout planning
  - **Action**: If yes to any → Engage Release Manager & Support Liaison

- [ ] **Success Measurement**: Does this project involve any of the following?
  - [ ] Defined success metrics
  - [ ] A/B testing or experiments
  - [ ] Usage tracking or analytics
  - [ ] Business outcome measurement
  - **Action**: If yes to any → Engage Data Analyst

### Team Composition Decision

Based on your assessment above, select the appropriate engagement model:

- [ ] **Minimal Team**: Internal, small-scope, low-risk → 4–5 people (PM, PdM, Devs, QA)
- [ ] **Standard Team**: Cross-functional feature or platform improvement → 8–10 people
- [ ] **Extended Team**: Platform-level, high-risk, or customer-facing → 12–15+ people

**Next Step**: Share the team composition decision with stakeholders for approval during initiation gate.

---

## Post-Planning Validation Checklist: "Did I Cover All Critical Expertise Areas?"

Use this checklist at the **end of planning** to validate that your team has the expertise needed to succeed.

### Technical & Architecture
- [ ] Technical Lead identified and understands:
  - [ ] High-level architecture and design decisions
  - [ ] Integration points with other systems
  - [ ] Technical risks and mitigations
  - [ ] Long-term maintainability implications

### Quality & Testing
- [ ] QA Lead has defined:
  - [ ] Test strategy (unit, integration, e2e, regression)
  - [ ] Acceptance criteria and test cases
  - [ ] Regression test coverage
  - [ ] Release gate / readiness criteria

### Security & Compliance
- [ ] Security Engineer (if engaged) has:
  - [ ] Conducted threat modeling
  - [ ] Identified security acceptance criteria
  - [ ] Reviewed design for vulnerabilities
  - [ ] Planned security scanning in CI

### Operations & Deployment
- [ ] DevOps / Release Manager has:
  - [ ] Defined deployment strategy and timeline
  - [ ] Planned for rollback and mitigation
  - [ ] Reviewed monitoring and observability
  - [ ] Coordinated with infrastructure team

### User Experience
- [ ] UX Designer (if engaged) has:
  - [ ] Validated designs with research or user testing
  - [ ] Documented accessibility requirements
  - [ ] Handed off clear specs to development
  - [ ] Planned for post-launch UX validation

### Customer Readiness
- [ ] Support/Success Liaison (if engaged) has:
  - [ ] Prepared support runbooks
  - [ ] Planned customer communication
  - [ ] Coordinated with support team
  - [ ] Identified training needs

### Metrics & Success
- [ ] Data Analyst (if engaged) has:
  - [ ] Defined success metrics
  - [ ] Planned instrumentation
  - [ ] Set up dashboards and reporting
  - [ ] Defined measurement frequency

### Cross-Functional Alignment
- [ ] All roles have clarity on:
  - [ ] Project goals and success criteria
  - [ ] Timeline and milestones
  - [ ] Dependencies and blockers
  - [ ] Escalation paths and decision owners
  - [ ] Communication cadence

**Validation Result:**
- [ ] All critical areas covered → Ready to proceed to execution
- [ ] Gaps identified → Adjust team composition or timeline before execution starts

---

## Role Selection Decision Tree

**Use this quick reference to make the final team composition decision:**
