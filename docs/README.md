# OctoAcme Project Management Processes

## Overview

The OctoAcme project management framework is a comprehensive, customer-centric approach that guides teams through all phases of project delivery, from initial conception to continuous improvement. Built on five core principles—**customer-first delivery, iterative development, clear ownership, data-informed decisions, and psychological safety**—these processes ensure consistency, clarity, and excellence across all projects.

Our framework operates through a structured lifecycle that moves projects through distinct phases: **initiation, planning, execution, release, and retrospective**. Each phase is supported by defined deliverables, governance checkpoints, and clear communication cadences. Whether you're launching a new initiative, managing ongoing execution, or scaling processes across teams, these documentation resources provide guidance aligned with OctoAcme's proven practices.

### Key Principles

- **Customer-first**: Prioritize customer value and usability in every decision
- **Iterative delivery**: Deliver small, testable increments frequently
- **Clear ownership**: Every project has a named Project Manager and Product Lead
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and experimentation

### Core Roles

- **Project Manager (PM)**: Coordinates delivery, manages schedules, risks, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, and measures success
- **Developers**: Implement features, collaborate on design, and ensure code quality
- **QA/Testing**: Validates quality against acceptance criteria and requirements
- **Stakeholders**: Provide inputs, approvals, and business context

## Documentation Index

Navigate to the specific process documentation you need:

| Document | Purpose |
|----------|---------|
| [Project Management Overview](./octoacme-project-management-overview.md) | High-level introduction to OctoAcme's methodology, core roles, artifacts, and communication cadence |
| [Project Initiation](./octoacme-project-initiation.md) | Starting new projects—validating business need, defining success metrics, and creating a Project One-pager |
| [Project Planning](./octoacme-project-planning.md) | Planning phase—breaking work into shippable increments, estimating scope, and creating the release plan |
| [Roles and Personas](./octoacme-roles-and-personas.md) | Detailed descriptions of key roles (PM, PdM, Developers) and their responsibilities |
| [Execution and Tracking](./octoacme-execution-and-tracking.md) | Day-to-day execution—standups, PR workflows, quality assurance, and progress metrics |
| [Risks and Communication](./octoacme-risks-and-communication.md) | Risk management lifecycle and stakeholder communication strategies |
| [Release and Deployment](./octoacme-release-and-deployment.md) | Release planning and deployment procedures |
| [Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Post-project reviews and organizational learning |

## Project Lifecycle at a Glance

### 1. **Initiation**
Define the initial steps to validate and authorize work. Teams create a Project One-pager (problem statement, goals, success metrics) and align stakeholders around business need and priority.

### 2. **Planning**
Turn approved initiatives into actionable plans. Break work into shippable increments, identify dependencies and risks, estimate scope using story points or t-shirt sizing, and create a prioritized backlog with clear acceptance criteria.

### 3. **Execution**
Build, test, and deliver working increments. Teams follow a disciplined PR workflow with small, reviewable changes (≤400 lines), automated testing and linting in CI, and mandatory code review. Daily standups focus on progress and blockers; weekly delivery syncs track milestones and risks.

### 4. **Release**
Deploy to production and verify. Conduct end-to-end smoke testing, document release notes, and communicate status to stakeholders.

### 5. **Retrospective & Continuous Improvement**
Capture learnings and next steps. Conduct blameless retrospectives, document action items, and identify process improvements for the next cycle.

## Communication Cadence

OctoAcme maintains consistent, transparent communication across all projects:

- **Daily Standups** (15 min): Focus on progress, blockers, and dependencies
- **Twice-weekly Team Syncs**: Delivery updates and risk discussion
- **Weekly PM + PdM Sync**: Strategic alignment and priority adjustments
- **Weekly Delivery Sync**: Show progress, flag risks, and escalate blockers
- **Monthly Stakeholder Updates**: High-level status and business impact
- **Ad-hoc Escalations**: As needed for critical issues

## Quality and Testing

Quality is built into every phase of execution:

- **Unit Tests**: New logic covered by automated tests
- **Integration Tests**: Cross-component interactions validated
- **End-to-End Smoke Tests**: Critical user flows tested before release
- **Security Scanning**: Automated vulnerability scanning in CI
- **Manual QA**: Feature acceptance testing when needed
- **Code Review**: Mandatory peer review with at least one approval before merge

## Risk Management

Risks are identified, assessed, and actively managed throughout project execution:

- **Risk Register**: Maintain a centralized log (ID, description, impact, likelihood, owner, mitigation, status)
- **Weekly Review**: Update and discuss risks at team and stakeholder syncs
- **Escalation Paths**: Team-level → PM → Product Lead → Sponsor
- **Incident Communication**: Clear triage, actions, timeline, and blameless post-mortems

## Using These Docs

### For New Team Members
Start with [Project Management Overview](./octoacme-project-management-overview.md) for a high-level introduction, then read [Roles and Personas](./octoacme-roles-and-personas.md) to understand your role and responsibilities.

### For Project Leads
Follow the sequence: Initiation → Planning → Execution → Release → Retrospective. Use the checklists and templates in each guide.

### For Stakeholders
Review the [Communication](./octoacme-risks-and-communication.md) doc to understand how you'll receive updates and the escalation paths for issues.

### For Developers
Focus on [Execution and Tracking](./octoacme-execution-and-tracking.md) for PR workflows, testing practices, and daily standups.

### In Copilot Spaces
To use these docs as context in Copilot Spaces, add process-specific docs to the `.copilot/` directory in your project repository.

---

## Quick Links

- **Need to start a project?** → [Project Initiation](./octoacme-project-initiation.md)
- **Planning your sprint?** → [Project Planning](./octoacme-project-planning.md)
- **Executing and tracking?** → [Execution and Tracking](./octoacme-execution-and-tracking.md)
- **Managing risks?** → [Risks and Communication](./octoacme-risks-and-communication.md)
- **Deploying to production?** → [Release and Deployment](./octoacme-release-and-deployment.md)
- **Learning from past projects?** → [Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

---

**Last Updated**: September 2026  
**Maintained By**: OctoAcme Project Management Team
