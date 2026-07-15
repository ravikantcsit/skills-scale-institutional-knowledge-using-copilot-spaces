# OctoAcme Project Management Process Documentation

## Overview

OctoAcme follows a structured, lifecycle-based approach to project delivery that emphasizes customer value, iterative development, and clear accountability. This directory contains the comprehensive project management processes and guidance used by OctoAcme for running cross-functional projects.

Our methodology is built on core principles:
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle

OctoAcme follows a structured lifecycle with five key phases:

1. **Initiation** - Validate business need, align stakeholders, confirm go/no-go decision
2. **Planning** - Break work into shippable increments, identify dependencies and risks
3. **Execution** - Build, test, review, and iterate on deliverables with consistent team rhythm
4. **Release** - Deploy to production with quality assurance and verification
5. **Closeout & Retrospective** - Capture learnings and drive continuous improvements

## Project Management in Practice

**Execution** is coordinated through a consistent team rhythm and disciplined workflow practices. Daily standups (15 minutes) focus on progress and blockers, while weekly delivery syncs track status and flag risks. The team uses a project board with defined columns—Backlog, Ready, In Progress, In Review, QA, Done—to maintain visibility. Pull requests are kept small (≤400 lines when possible), include issue links and acceptance criteria, and require at least one approval and passing CI checks before merging. Quality is embedded throughout: unit tests, integration tests, end-to-end smoke tests, and security scanning happen in CI, with manual QA applied when needed for feature acceptance.

**Roles and Accountability** are clearly defined across the organization. Project Managers coordinate schedules and risks, Product Managers prioritize and measure outcomes, Developers implement and test, and QA/Testing validates acceptance criteria—each with explicit communication responsibilities. Stakeholder communication happens weekly through status updates and monthly briefings, while risks are tracked in a structured register with impact, likelihood, mitigation plans, and owners. Escalation follows three levels: team triage in standups, PM escalation to Product Lead, and sponsor involvement for business-critical issues.

**Continuous Improvement** is reinforced through retrospectives after each sprint or release. Retrospectives capture learnings and convert them into tracked action items, ensuring the team consistently refines its processes and delivery approach.

## Process Documents

### Foundational Guides
- [Project Management Overview](octoacme-project-management-overview.md) - Introduction to OctoAcme's approach, roles, and key artifacts
- [Roles & Personas](octoacme-roles-and-personas.md) - Definitions of core roles (PM, PdM, Developers, QA) and their responsibilities

### By Project Phase

**Initiation Phase**
- [Project Initiation Guide](octoacme-project-initiation.md) - Steps to validate work, align stakeholders, and create a project one-pager

**Planning Phase**
- [Project Planning](octoacme-project-planning.md) - Break work into backlog items, estimate scope, create release plans, and define acceptance criteria

**Execution Phase**
- [Execution & Tracking](octoacme-execution-and-tracking.md) - Day-to-day delivery, quality standards, team rhythm, blocker escalation, and success metrics

**Release Phase**
- [Release & Deployment Guide](octoacme-release-and-deployment.md) - Pre-release requirements, deployment checklists, and rollback procedures

**Continuous Improvement Phase**
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) - Running retrospectives, tracking improvements, and measuring impact

### Cross-Cutting Concerns
- [Risk Management & Communication](octoacme-risks-and-communication.md) - Identifying, tracking, and escalating risks; stakeholder communication templates; incident response

## Quick Navigation by Role

### Product Managers
Start here to understand how to define outcomes and prioritize delivery:
1. [Project Initiation Guide](octoacme-project-initiation.md) - Define the problem, success metrics, and stakeholder alignment
2. [Project Planning](octoacme-project-planning.md) - Create prioritized backlog with acceptance criteria
3. [Project Management Overview](octoacme-project-management-overview.md) - Understand roles and communication cadence

### Project Managers
Start here to coordinate delivery and manage risks:
1. [Project Management Overview](octoacme-project-management-overview.md) - Understand key roles, artifacts, and lifecycle
2. [Execution & Tracking](octoacme-execution-and-tracking.md) - Day-to-day execution, team rhythm, and escalation procedures
3. [Risk Management & Communication](octoacme-risks-and-communication.md) - Track risks and communicate with stakeholders
4. [Release & Deployment Guide](octoacme-release-and-deployment.md) - Plan and execute releases

### Developers
Start here to understand delivery standards and development practices:
1. [Execution & Tracking](octoacme-execution-and-tracking.md) - PR workflow, quality standards, and team rhythm
2. [Project Planning](octoacme-project-planning.md) - Understand backlog items and acceptance criteria
3. [Release & Deployment Guide](octoacme-release-and-deployment.md) - Pre-release requirements and deployment process

### QA/Testing
Start here to understand quality standards and acceptance criteria:
1. [Execution & Tracking](octoacme-execution-and-tracking.md) - Quality standards and testing requirements
2. [Project Planning](octoacme-project-planning.md) - Understand acceptance criteria and Definition of Done
3. [Release & Deployment Guide](octoacme-release-and-deployment.md) - Pre-release requirements and smoke tests

## How to Use These Docs

- **New team members**: Start with [Project Management Overview](octoacme-project-management-overview.md) for a concise introduction
- **Project kickoff**: Use the [Project Initiation Guide](octoacme-project-initiation.md) checklist
- **During execution**: Reference [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risk Management & Communication](octoacme-risks-and-communication.md)
- **Before release**: Review [Release & Deployment Guide](octoacme-release-and-deployment.md)
- **After sprint/release**: Follow [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- **Copilot Spaces**: Add process-specific docs to `.copilot/` if you want Copilot Spaces to use them as context for role-specific guidance

## Key Artifacts Across the Lifecycle

- **Project Charter / One-pager** - Defines problem, goals, success metrics, stakeholders
- **Roadmap and Release Plan** - Shows prioritized work across milestones
- **Sprint/Iteration Backlog** - Lists prioritized items with acceptance criteria
- **Risk Register** - Tracks risks with impact, likelihood, mitigation plans
- **Project Board** - Visualizes work status (Backlog, Ready, In Progress, In Review, QA, Done)
- **Retrospective Notes** - Captures learnings and action items

---

For questions or to propose improvements to these processes, please reach out to your Product Lead or Project Manager.
