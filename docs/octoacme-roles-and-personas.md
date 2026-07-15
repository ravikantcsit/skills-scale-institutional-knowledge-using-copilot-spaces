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
QA/Testing Leads ensure quality standards are met before release. They design test plans, coordinate testing activities, and validate that acceptance criteria are satisfied.

### Responsibilities
- Define and maintain test plans and test cases
- Coordinate manual and automated testing efforts
- Validate acceptance criteria are met before PR approval
- Identify and document defects with clear reproduction steps
- Participate in sprint planning to understand scope and test coverage needs
- Provide quality metrics and testing status updates

### Goals
- Ensure features meet acceptance criteria and quality standards
- Reduce production defects and regressions
- Enable faster, more confident releases

### Typical Communication
- Test plan reviews with product and development teams
- Defect tracking and PR review comments
- Quality metrics in weekly status reports

### Key Interactions
- Works with **Developers** to understand implementation and testability
- Collaborates with **Product Managers** on acceptance criteria validation
- Partners with **DevOps/Release Engineer** on smoke test and release validation

---

## Sponsor/Stakeholder

### Role Summary
Sponsors and Stakeholders provide business context, approve investments, and ensure the project aligns with organizational goals and customer needs. They may represent executive leadership, customers, or dependent teams.

### Responsibilities
- Provide business case and success criteria for projects
- Review and approve project charters and timelines
- Participate in key milestone reviews and gate decisions
- Provide feedback on requirements and design choices
- Escalate blockers and resource constraints
- Communicate project outcomes to broader organization

### Goals
- Ensure projects deliver measurable business value
- Maintain alignment across organizational priorities
- Reduce scope creep and delivery surprises

### Typical Communication
- Monthly stakeholder updates and milestone reviews
- Project charter and release announcement approvals
- Ad-hoc escalation paths for critical decisions

### Key Interactions
- Receives updates and escalations from **Project Manager**
- Reviews success metrics and outcomes from **Product Manager**
- Approves business-critical decisions with **Project Lead**

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate team processes, remove impediments, and help teams continuously improve their delivery practices.

### Responsibilities
- Facilitate daily standups, planning, and retrospectives
- Identify and help resolve team blockers and impediments
- Coach team on agile practices and continuous improvement
- Maintain sprint boards and burndown charts
- Escalate systemic impediments to project leadership
- Help the team self-organize and make decisions

### Goals
- Maximize team velocity and predictability
- Foster psychological safety and continuous learning
- Remove process friction and enable faster delivery

### Typical Communication
- Facilitation of ceremonies (standups, retros, demos)
- One-on-ones with team members
- Metrics and impediment tracking

### Key Interactions
- Works with all team members to identify and resolve blockers
- Partners with **Project Manager** on timeline and resource coordination
- Helps teams adopt best practices across **Developers**, **QA**, and other roles

---

## Designer / UX Lead

### Role Summary
Designers and UX Leads ensure features are usable, accessible, and aligned with user needs. They collaborate with product and engineering to create intuitive, delightful experiences.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Collaborate with product on requirements and user flows
- Partner with developers on implementation and accessibility
- Iterate on designs based on feedback and metrics
- Define design system and consistency standards

### Goals
- Deliver intuitive, accessible user experiences
- Reduce support burden through clear design
- Align product features with user needs and expectations

### Typical Communication
- Design reviews with product and engineering
- User research findings and usability test results
- Design specifications and accessibility checklists in PRs

### Key Interactions
- Collaborates with **Product Manager** on user requirements and prioritization
- Partners with **Developers** on implementation and technical feasibility
- Works with **QA/Testing Lead** on usability and accessibility validation

---

## DevOps / Release Engineer

### Role Summary
DevOps and Release Engineers ensure reliable, secure, and observable deployments to production. They own infrastructure, CI/CD pipelines, and incident response.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage deployment environments (staging, production)
- Ensure security and compliance in deployments
- Monitor system health, errors, and performance
- Coordinate with teams on deployment windows and rollbacks
- Implement infrastructure-as-code and observability
- Participate in incident response and post-mortems

### Goals
- Enable fast, reliable, and secure releases
- Minimize downtime and production incidents
- Provide visibility into system health and performance

### Typical Communication
- Deployment checklists and runbooks
- Incident response coordination
- Metrics and SLA reviews in status updates

### Key Interactions
- Coordinates with **Developers** on deployment readiness and CI/CD pipelines
- Works with **QA/Testing Lead** on smoke tests and release validation
- Keeps **Project Manager** informed on deployment status and incidents
- Escalates critical issues to **Sponsors/Stakeholders** when needed

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the **Key Interactions** sections to understand how roles collaborate across project phases.
