# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Roles

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Specialized/Supporting Roles

### Scrum Master

#### Role Summary
Scrum Masters remove impediments and coach teams on agile best practices. They facilitate ceremonies and foster a culture of continuous improvement and psychological safety.

#### Responsibilities
- Remove team blockers and impediments
- Facilitate agile ceremonies (standup, planning, retrospectives, reviews)
- Coach team members on agile practices and mindsets
- Monitor team health and engagement
- Drive continuous improvement initiatives
- Protect team focus from external distractions

#### Goals
- Maximize team productivity and velocity
- Foster psychological safety and open communication
- Continuously improve team processes and outcomes

#### Interacts With
- **Project Manager (PM)**: Shares impediment status, escalates blockers; PM handles cross-team dependencies while SM handles internal team flow
- **Developers**: Removes obstacles, facilitates technical discussions, coaches on best practices
- **Product Managers**: Ensures backlog clarity and prioritization support agile delivery

#### Typical Communication
- Daily standups and sprint ceremonies
- Retro action item tracking and follow-up
- One-on-ones with team members
- Impediment logs and health dashboards

---

### UX Designer

#### Role Summary
UX Designers conduct user research, design intuitive workflows, and ensure solutions meet usability and accessibility standards. They advocate for the user throughout the product lifecycle.

#### Responsibilities
- Lead user research and discovery activities
- Design wireframes, mockups, and interaction flows
- Conduct usability testing and incorporate feedback
- Ensure WCAG accessibility compliance
- Collaborate on design systems and component libraries
- Document design decisions and rationale

#### Goals
- Deliver user-centric, intuitive experiences
- Reduce support burden through better design
- Build products that users love and recommend

#### Interacts With
- **Product Manager**: Partners on requirements, success metrics, and user research insights
- **Developers**: Hands off designs with clear specifications; supports implementation questions and edge cases
- **QA/Testing**: Validates design acceptance criteria and user experience
- **Project Manager**: Provides design timelines and dependency information for scheduling

#### Typical Communication
- Design presentations and walkthroughs
- Design specification documents
- Figma or design tool collaboration
- Design review sessions with stakeholders

---

### Technical Writer

#### Role Summary
Technical Writers create and maintain clear, accurate documentation for users and internal teams. They ensure processes, features, and systems are well-documented and accessible.

#### Responsibilities
- Create and maintain user-facing documentation
- Write release notes and change logs
- Document internal processes and runbooks
- Maintain API documentation and guides
- Ensure documentation is current, accurate, and accessible
- Collaborate with teams to extract and structure information

#### Goals
- Reduce support tickets through clear documentation
- Accelerate onboarding for new users and team members
- Preserve institutional knowledge in searchable formats

#### Interacts With
- **Developers**: Source of truth for feature details, technical specs, and code examples
- **Product Manager**: Understands feature intent, use cases, and success metrics to contextualize documentation
- **QA/Testing**: Validates documentation accuracy; provides edge cases and known issues
- **Project Manager**: Included in release planning to ensure docs ship with features

#### Typical Communication
- Documentation reviews and edits
- Kickoff meetings to understand features
- Release note drafts and approvals
- Documentation roadmap and prioritization

---

### DevOps Engineer

#### Role Summary
DevOps Engineers design, build, and maintain infrastructure, CI/CD pipelines, and deployment automation. They ensure systems are scalable, reliable, and observable.

#### Responsibilities
- Design and manage cloud infrastructure and environments
- Build and maintain CI/CD pipelines and automation
- Implement monitoring, alerting, and observability
- Manage deployments and rollback procedures
- Ensure security and compliance in infrastructure
- Support incident response and post-mortem actions
- Optimize costs and performance

#### Goals
- Enable rapid, safe deployments
- Minimize downtime and mean time to recovery (MTTR)
- Maintain system reliability and performance

#### Interacts With
- **Developers**: Provides build/deploy tooling, troubleshoots integration issues, supports local development setup
- **QA/Testing**: Provisions test environments, supports performance testing, manages test data
- **Project Manager**: Involved in release planning, deployment windows, and rollback readiness
- **Technical Writer**: Documents deployment procedures and operational runbooks

#### Typical Communication
- Deployment planning and coordination
- Infrastructure design reviews
- Incident response and post-mortems
- CI/CD pipeline improvements and status updates

---

## How These Personas Are Used

- Use these persona definitions to frame scenarios and sample interactions in exercises
- Each persona can be referenced in process documents to clarify responsibilities and handoffs
- Customize role assignments based on team size and structure (e.g., one person may hold multiple roles)
- Refer back to this document when creating checklists, templates, or project communication plans

---

## Cross-Functional Collaboration Matrix

| Core Interaction | Primary Roles | Key Touchpoints |
|---|---|---|
| **Planning** | PM + PdM + Dev + Scrum Master | Backlog prioritization, estimation, sprint planning |
| **Design & Spec** | PdM + UX Designer + Dev | Acceptance criteria, wireframes, design specs |
| **Implementation** | Dev + Scrum Master + Tech Writer | Code reviews, documentation, impediment removal |
| **Testing** | QA + Dev + UX Designer | Acceptance criteria validation, usability testing |
| **Release** | Project Manager + DevOps + Tech Writer + Developers | Deployment coordination, release notes, runbooks |
| **Communication** | Project Manager + Technical Writer | Status updates, release announcements, runbooks |
| **Continuous Improvement** | Scrum Master + Entire Team | Retros, action items, process refinements |
