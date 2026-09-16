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

## Stakeholder/Client Representative

### Role Summary
External or internal client representatives provide business context, requirements, and approval authority for project deliverables. They serve as the voice of the customer throughout the project lifecycle and ensure alignment with business objectives.

### Responsibilities
- Communicate business requirements and success criteria
- Provide timely approvals for project gates and deliverables
- Serve as the escalation point for business-impacting decisions
- Participate in requirements validation and acceptance testing
- Represent stakeholder interests during planning and execution
- Communicate project status and outcomes to broader business leadership

### Interactions with Other Personas
- **Project Manager**: Weekly status reviews, change requests, escalations
- **Product Manager**: Requirements clarification, scope validation, prioritization trade-offs
- **Quality Assurance Lead**: Acceptance criteria definition, sign-off on testing results
- **Technical Architect**: Technical feasibility discussions and solution design reviews

### Goals
- Ensure project delivery meets business needs and success criteria
- Minimize scope creep through clear requirements and early alignment
- Enable informed decision-making on priorities and trade-offs
- Maintain stakeholder confidence through transparent communication

### Typical Communication
- Weekly status meetings and stakeholder reviews
- Written approval gates and sign-offs
- Project steering committee participation
- Ad-hoc escalation and decision requests

### Authority & Decision Rights
- Scope changes → Approval required
- Timeline adjustments → Approval required
- Resource allocation (business side) → Approval required
- Acceptance of deliverables → Final authority

---

## Quality Assurance Lead

### Role Summary
Quality Assurance Leads oversee testing strategies, validate acceptance criteria, and establish quality gates before release. They ensure that deliverables meet defined standards and organizational quality expectations.

### Responsibilities
- Define testing strategies and test plans aligned with project scope
- Validate acceptance criteria and ensure clarity with Product and Project Managers
- Oversee test execution and identify defects and quality issues
- Establish and manage quality gates for each release
- Document test results and quality metrics
- Coordinate with Developers on defect resolution and retesting
- Communicate quality risks and readiness assessments to stakeholders

### Interactions with Other Personas
- **Developers**: Defect reporting, test case clarification, quality expectations
- **Product Manager**: Acceptance criteria validation, scope and quality trade-offs
- **Project Manager**: Quality schedule planning, gate readiness reporting
- **Stakeholder/Client Representative**: Quality sign-off, acceptance testing participation
- **Technical Architect**: Technical test strategy alignment, infrastructure requirements for testing

### Goals
- Deliver high-quality products that meet acceptance criteria
- Identify defects early to reduce downstream rework
- Maintain consistent quality standards across releases
- Minimize critical issues escaping to production

### Typical Communication
- Test plan and strategy reviews with stakeholders
- Daily defect logs and quality status reports
- Quality metrics dashboards and trend analysis
- Release readiness assessments and gate reviews

### Authority & Decision Rights
- Test strategy and scope → Defines standards
- Quality gate decisions → Final authority to block/approve release
- Defect prioritization → Recommends priority based on severity
- Acceptance testing sign-off → Required approval

---

## Technical Architect

### Role Summary
Technical Architects guide technical decisions, conduct system design reviews, and ensure alignment with organizational infrastructure standards and best practices. They provide technical leadership and reduce architectural risks.

### Responsibilities
- Lead system design discussions and architectural reviews
- Evaluate technology choices and recommend optimal solutions
- Ensure alignment with organizational infrastructure and standards
- Identify and mitigate technical risks and dependencies
- Document technical decisions and rationale (ADRs)
- Support Developers with technical guidance and mentoring
- Validate scalability, security, and performance requirements

### Interactions with Other Personas
- **Developers**: Technical guidance, design reviews, mentoring
- **Product Manager**: Technical feasibility assessment, trade-offs on requirements
- **Project Manager**: Technical risk identification, schedule and dependency impact
- **Quality Assurance Lead**: Non-functional requirements (performance, security, scalability)
- **Stakeholder/Client Representative**: Technical feasibility discussions, solution architecture presentations

### Goals
- Deliver technically sound, scalable solutions
- Reduce technical debt and architectural risks
- Ensure consistency with organizational standards
- Enable sustainable, long-term product evolution

### Typical Communication
- Architecture design reviews and technical proposals
- Technical risk registers and mitigation plans
- Architecture Decision Records (ADRs)
- Technical mentoring and design guidance sessions

### Authority & Decision Rights
- Technology selection → Recommends with rationale
- Architectural approach → Final authority on design alignment
- Technical standards compliance → Enforces organizational standards
- Technical risk escalation → Authority to escalate and block if critical

---

## Change Management Coordinator

### Role Summary
Change Management Coordinators manage organizational change, guide stakeholder communication during transitions, and develop adoption strategies for new processes and tools. They ensure successful transitions and minimize disruption.

### Responsibilities
- Develop change management and communication plans
- Identify and engage key stakeholders in the change process
- Create training materials and adoption guidance
- Manage change communications throughout the project lifecycle
- Monitor adoption metrics and address resistance
- Support team transitions to new processes and tools
- Coordinate with Learning & Development on training delivery

### Interactions with Other Personas
- **Project Manager**: Change schedule and milestones, stakeholder impact planning
- **Stakeholder/Client Representative**: Executive communication, adoption commitment
- **Product Manager**: Feature messaging, user adoption strategy
- **Learning & Development Specialist**: Training content and delivery coordination
- **Developers**: Process and tool adoption guidance, documentation clarity

### Goals
- Ensure smooth transitions with minimal disruption
- Maximize stakeholder adoption and engagement
- Reduce resistance and increase buy-in for changes
- Measure and demonstrate change effectiveness

### Typical Communication
- Change readiness assessments and communications plans
- Stakeholder update newsletters and bulletins
- Adoption metrics and feedback reports
- Training and support coordination meetings

### Authority & Decision Rights
- Change communication approach → Determines strategy
- Training and adoption programs → Recommends content and approach
- Stakeholder engagement → Authority on engagement strategy
- Adoption metrics → Defines success measures

---

## Learning & Development Specialist

### Role Summary
Learning & Development Specialists are responsible for creating training materials, documentation, and knowledge transfer resources for new processes and tools. They ensure teams have the knowledge and support needed for successful adoption.

### Responsibilities
- Create comprehensive training materials and guides
- Develop documentation for new processes and tools
- Design and deliver training sessions and workshops
- Create job aids and reference materials
- Assess learning effectiveness and adjust content
- Build knowledge repositories and self-service resources
- Support ongoing learning and continuous improvement

### Interactions with Other Personas
- **Change Management Coordinator**: Training delivery coordination, adoption messaging
- **Project Manager**: Training schedule and resource planning
- **Stakeholder/Client Representative**: Training availability and accessibility for stakeholders
- **Developers**: Technical documentation and process guidance
- **Product Manager**: Feature documentation and user guidance

### Goals
- Ensure team readiness and competency with new processes/tools
- Reduce learning curve and time to proficiency
- Enable self-service support through clear documentation
- Foster continuous learning culture

### Typical Communication
- Training material and documentation reviews
- Learning effectiveness reports and feedback
- Knowledge repository updates and maintenance
- Training schedule and resource coordination

### Authority & Decision Rights
- Training content and approach → Determines instructional strategy
- Documentation standards → Defines organizational documentation guidelines
- Competency validation → Assesses readiness through assessments

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the interaction patterns between personas to design realistic multi-stakeholder scenarios and decision-making workflows.
