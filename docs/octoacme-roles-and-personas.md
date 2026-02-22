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

## UX Designer

### Role Summary
UX Designers ensure the product delivers an excellent end-user experience driven by research and usability testing. They translate requirements and constraints into designs that are both accessible and delightful to use.

### Responsibilities
- Conduct user research, interviews, and usability tests
- Translate requirements and constraints into wireframes or prototypes
- Collaborate with Product and Developers on design decisions
- Ensure accessibility and design system compliance
- Maintain a shared design library and document design decisions

### Goals
- Deliver user experiences that are intuitive and inclusive
- Reduce rework by validating designs before development begins
- Ensure design artifacts are accessible to the full team

### Typical Communication
- Design reviews and critique sessions with Product and Engineering
- Shared design files (e.g., Figma) linked in sprint tickets
- Usability test findings summarized in project docs

### Interactions
- **Product Managers**: Partners closely to align on problem statements, user needs, and success metrics during Initiation and Planning. Shares research findings that inform backlog prioritization.
- **Project Managers**: Coordinates to ensure design milestones are reflected in the project plan and that design reviews are scheduled before development sprints begin.
- **Developers**: Works with developers during Execution to clarify interaction details, answer design questions, and review implemented UI for fidelity. Flags accessibility issues early to avoid last-minute rework.

---

## Security Lead

### Role Summary
Security Leads manage product security requirements and facilitate threat modeling throughout the project lifecycle. They act as the team's security advisor and ensure that security is built in, not bolted on.

### Responsibilities
- Conduct risk assessments and threat modeling exercises
- Review designs and code for security best practices
- Define and maintain security acceptance criteria and release gates
- Coordinate resolution of identified vulnerabilities
- Advise on compliance and regulatory requirements

### Goals
- Prevent security incidents through proactive design and review
- Ensure security requirements are captured and traceable
- Enable teams to ship confidently with clear security sign-off

### Typical Communication
- Threat model documents and security review findings shared with the team
- Participation in planning and release readiness reviews
- Ad-hoc consultation on security questions during development

### Interactions
- **Product Managers**: Engages during Initiation and Planning to identify security requirements and ensure they are prioritized alongside feature work. Supports PM in defining security gates as part of release criteria.
- **Project Managers**: Works with PM to schedule security reviews as formal checkpoints in the project timeline, particularly before release.
- **Developers**: Collaborates during Execution on secure implementation patterns, reviews pull requests for security concerns, and assists in remediating identified vulnerabilities.

---

## Business Analyst

### Role Summary
Business Analysts ensure project deliverables trace back to clear business needs. They document requirements for both technical and business stakeholders and bridge the gap between business intent and technical execution.

### Responsibilities
- Elicit and document business and technical requirements
- Clarify and maintain acceptance criteria with stakeholders and engineering
- Gather and synthesize stakeholder feedback
- Facilitate requirements reviews and workshops
- Identify scope gaps and flag conflicting requirements

### Goals
- Ensure every deliverable can be traced to a validated business need
- Reduce ambiguity in requirements before development begins
- Improve handoffs by producing clear, agreed-upon acceptance criteria

### Typical Communication
- Requirements documentation and user story refinement sessions
- Stakeholder workshops and feedback sessions
- Sign-off on acceptance criteria before sprint commitment

### Interactions
- **Product Managers**: Supports PdMs in requirements elicitation and refinement during Planning. Ensures business context and constraints are captured in user stories, reducing back-and-forth during development.
- **Project Managers**: Provides input on scope definition and flags requirement changes that may affect the project timeline or risk register.
- **Developers**: Acts as a liaison during Execution, answering questions about intent behind requirements and facilitating rapid clarification to unblock development.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [Role Collaboration Matrix](./octoacme-role-collaboration-matrix.md) for a cross-functional responsibility overview across lifecycle phases.
- See [Cross-Functional Handoff Checklist](./octoacme-cross-functional-handoff-checklist.md) for readiness criteria at key handoff points.

