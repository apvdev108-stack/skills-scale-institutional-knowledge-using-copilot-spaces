---
name: Issue Template - Add Personas Integration
about: Template for creating the personas and roles integration issue
title: "[Process Doc Update]: Integrating Additional Personas and Roles into Project Management Documentation"
labels: ["documentation", "process improvement"]
---

## Which process document do you want to update?
octoacme-roles-and-personas.md

## Summary of New Content

**Promote the "Additional Suggested Personas" section into integrated core guidance.** 

Formalize eight specialized roles (Technical Lead/Architect, QA Lead/Test Engineer, UX Designer/Researcher, DevOps/Platform Engineer, Security Engineer, Data Analyst/Metrics Owner, Release Manager, and Support/Customer Success Liaison) as standard reference points for cross-functional project teams.

Add a new **"Role Engagement Model"** section that specifies:
- **Minimal team** (for small, contained projects)
- **Standard team** (for typical cross-functional features)  
- **Extended team** (for platform-level, high-risk, or enterprise initiatives)

## Why is this update needed?

**Identified Gaps:**
1. Current core roles (PM, PdM, Developers, QA, Stakeholders) provide a foundation, but specialized expertise areas lack formal guidance
2. Teams often struggle to know *when* and *how* to engage security, UX, platform, metrics, or release specialists
3. As OctoAcme scales, accountability for critical concerns (security posture, QA strategy, user validation, deployment reliability) becomes increasingly important

**Benefits:**
- **Clarity & Accountability**: Explicit ownership reduces ambiguity and prevents critical areas from falling through cracks
- **Improved Outcomes**: Cross-functional projects with clear role assignment deliver higher quality, better user experience, and lower operational risk
- **Faster Onboarding**: New team members understand the full spectrum of roles and when to engage each
- **Scalability**: Provides a framework for projects of different sizes to engage the right level of expertise

**Team Feedback & Alignment:**
- Extended roles are already referenced in delivery practices but lack formal integration
- Emerging best practices (security-by-design, observability, accessibility) require specialized ownership
- OctoAcme's maturing process benefits from explicit role clarity

## Suggested Content

### Changes to `docs/octoacme-roles-and-personas.md`

**1. Rename and elevate the section:**
- Current: "Additional Suggested Personas"
- New: "Extended Core Roles" (positioned immediately after core roles, not as a separate appendix)

**2. Add new subsection: "Role Engagement Model"**

```markdown
## Role Engagement Model

Choose the team composition based on project scope and risk profile:

### Minimal Team (Small, low-risk projects)
- Project Manager
- Product Manager
- Developers (1–3)
- QA Lead

Use for: Internal tools, bug fixes, small feature improvements with no cross-team dependencies.

### Standard Team (Typical cross-functional features)
- Project Manager
- Product Manager
- Technical Lead / Architect
- Developers (3–8)
- QA Lead / Test Engineer
- DevOps / Release Manager
- Data Analyst / Metrics Owner

Use for: Customer-facing features, platform improvements, new integrations, typical release cadence.

### Extended Team (Platform-level, high-risk, or enterprise initiatives)
- All Standard Team roles, plus:
- Security Engineer
- UX Designer / Researcher
- Support / Customer Success Liaison

Use for: Major feature launches, security/compliance initiatives, platform architecture changes, high customer impact, compliance requirements.
```

**3. Update role descriptions to emphasize interaction:**
- Add a subsection under each extended role: **"When to Engage"**
- Example for Security Engineer: "Engage at planning phase for any feature handling user data, authentication, or regulatory requirements."

## Acceptance Criteria

- ✅ Content aligns with existing process docs and current best practices reflected in OctoAcme delivery
- ✅ Update improves clarity and closes the gap between core and extended roles with actionable guidance
- ✅ New "Role Engagement Model" provides clear decision framework for team composition
- ✅ Interaction patterns with existing roles are explicit and actionable
- ✅ Document ready for use in project planning and team scaling scenarios

---

## Related Context
This issue addresses the integration of the "Additional Suggested Personas" section that already exists in the document, promoting it from recommendations to formalized guidance with clear engagement criteria for different project scales.
