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
QA/Testing Leads own the quality strategy, test planning, and acceptance validation. They collaborate with developers and product managers to ensure features meet acceptance criteria and quality standards before release.

### Responsibilities
- Define test strategy and test plan for each release
- Coordinate manual and automated testing efforts
- Validate acceptance criteria are met before sign-off
- Manage defect triage and quality metrics
- Advise on test automation investment and coverage
- Partner with developers on testability and test design

### Goals
- Ensure customer-facing features are reliable and meet acceptance criteria
- Reduce production defects through proactive testing
- Build maintainable, efficient test suites

### Typical Communication
- Weekly quality sync with PM and development lead
- Test plan reviews at sprint planning
- Daily defect triage on critical issues
- Quality metrics reporting in stakeholder updates

### Interaction with Other Roles
- Works closely with **Developers** to establish testability requirements and review test plans
- Collaborates with **Product Managers** to understand acceptance criteria and success metrics
- Coordinates with **Project Managers** to ensure quality gating in release timelines
- Partners with **Engineering Lead** on test automation strategy and quality standards

---

## Engineering Lead / Tech Lead

### Role Summary
Engineering Leads provide technical direction, architecture guidance, and code review oversight. They mentor developers, establish coding standards, and ensure solutions align with long-term technical strategy.

### Responsibilities
- Define technical approach and architecture for major features
- Review and approve technical design decisions
- Mentor junior developers and conduct code reviews
- Identify technical risks and propose mitigations
- Maintain code quality standards and technical debt management
- Collaborate with DevOps on deployability and scalability

### Goals
- Deliver scalable, maintainable, and performant solutions
- Foster a culture of technical excellence and continuous learning
- Balance velocity with long-term system health

### Typical Communication
- Technical design reviews with development team
- Weekly sync with PM and Project Manager on scope and technical risks
- Code review feedback on PRs
- Architecture documentation and decision logs

### Interaction with Other Roles
- Mentors and guides **Developers** on technical best practices and design patterns
- Partners with **Product Managers** to understand technical feasibility of feature requests
- Works with **QA/Testing Lead** on testability and test automation strategy
- Collaborates with **DevOps Engineer** to ensure architectural decisions support deployment and scalability
- Supports **Project Manager** in identifying and mitigating technical risks

---

## DevOps / Infrastructure Engineer

### Role Summary
DevOps Engineers manage deployment pipelines, infrastructure, observability, and system reliability. They enable teams to deploy safely and maintain production systems with confidence.

### Responsibilities
- Implement and maintain CI/CD pipelines
- Manage infrastructure and cloud resources
- Set up monitoring, logging, and alerting
- Support rollback and incident response
- Advise on security and compliance in deployments
- Collaborate with development on deployability and performance

### Goals
- Enable fast, safe, and reliable deployments
- Maintain high system availability and performance
- Reduce deployment-related incidents and manual overhead

### Typical Communication
- Pre-release deployment planning and readiness reviews
- On-call support for production issues
- Weekly infrastructure and reliability metrics reporting
- Post-incident retrospectives

### Interaction with Other Roles
- Works with **Developers** to ensure code is deployable and follows infrastructure conventions
- Partners with **Engineering Lead** on architecture decisions affecting deployment and scalability
- Collaborates with **Project Manager** on release scheduling and deployment readiness
- Supports **QA/Testing Lead** by providing staging environments and smoke test infrastructure
- Advises **Product Managers** on performance implications and infrastructure costs of features

---

## Design/UX Lead

### Role Summary
Design/UX Leads define user experience, design systems, and usability standards. They ensure that products are intuitive, accessible, and aligned with brand and business goals.

### Responsibilities
- Define user experience strategy and design patterns
- Create and maintain design systems and component libraries
- Conduct user research and usability testing
- Review designs and interface implementations for consistency and usability
- Establish accessibility and inclusive design standards
- Collaborate on feature specifications and acceptance criteria

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Maintain consistency across products and features
- Reduce support burden through excellent UX design

### Typical Communication
- Design reviews and feedback sessions with development team
- User research findings and usability testing results
- Design system documentation and component specifications
- Weekly sync with Product Managers on user needs and design priorities

### Interaction with Other Roles
- Partners with **Product Managers** to validate design decisions against user needs and business goals
- Collaborates with **Developers** on implementation of designs and component accessibility
- Works with **Engineering Lead** on performance and technical implications of design decisions
- Advises **QA/Testing Lead** on usability testing approach and acceptance criteria
- Supports **Project Manager** in user-facing feature planning and acceptance

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, strategic direction, and approval authority. They champion the project, secure resources, and ensure alignment with organizational goals.

### Responsibilities
- Define business objectives and strategic priorities
- Provide final approval for project charter and major scope changes
- Secure resources and budget for the project
- Escalate blockers and unresolved risks
- Communicate project progress to executive leadership
- Serve as tie-breaker on high-stakes decisions

### Goals
- Ensure projects deliver measurable business value
- Maintain strategic alignment across initiatives
- Minimize organizational risk and resource conflicts

### Typical Communication
- Monthly stakeholder updates and executive briefings
- Decision-gate approvals at project milestones
- Escalation channels for cross-team blockers
- Post-release reviews and lessons learned discussions

### Interaction with Other Roles
- Sets strategic context for **Product Managers** and receives prioritization recommendations
- Approves high-level plans and milestones from **Project Managers**
- Provides escalation path for risks identified by any team member
- Reviews business metrics and success outcomes with entire team
- Advocates for project team in organizational forums

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Recognize that team members may hold multiple personas (e.g., a developer may also serve as a Tech Lead) and adapt interactions accordingly.
