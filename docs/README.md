# OctoAcme Project Management Docs

This directory centralizes all process documentation and key workflows for running projects at OctoAcme. Use it as your entry point for onboarding or to find detailed guidance for each stage of the project lifecycle.

## Project Management Process Summary

OctoAcme operates projects through a structured five-phase lifecycle that emphasizes customer value, iterative delivery, and clear ownership. The process begins with **Initiation**, where business needs are validated through a lightweight Project One-pager that captures the problem statement, success metrics, and stakeholder alignment. Once approved, teams move into **Planning**, where work is broken into shippable increments with prioritized backlogs, acceptance criteria, and a defined Definition of Done. The core **Execution & Tracking** phase involves daily standups (15 minutes), weekly delivery syncs, and a project board workflow with columns spanning Backlog through Done. Quality assurance is embedded throughout, with unit tests, integration tests, end-to-end smoke tests, and security scanning required before release. Teams then proceed to **Release & Deployment**, which includes pre-release requirements such as passing CI checks and documented rollback plans, followed by **Retrospectives & Continuous Improvement**, where learnings are captured and converted into actionable improvements.

The organizational structure centers on three core personas with distinct responsibilities. **Project Managers** coordinate delivery, manage timelines, risks, and cross-team communications, serving as the connective tissue between stakeholders and the delivery team. **Product Managers** define what should be built by owning the vision, prioritizing the backlog, and measuring outcomes through data-driven decisions. **Developers** implement features, write tests, conduct code reviews, and help identify technical risks. This clear ownership model is reinforced by the principle that each project has a named PM and Product Lead who align weekly on strategy and execution.

Communication cadence is a cornerstone of OctoAcme's approach, designed to maintain transparency and reduce surprises. Regular touchpoints include twice-weekly standups for delivery teams, weekly syncs between PM and Product Manager, and monthly stakeholder updates. Risk management is formalized through a Risk Register that tracks impact, likelihood, and mitigation strategies, with escalation paths moving from team-level triage through the PM, Product Lead, and ultimately to Sponsor level for business-impacting issues. Stakeholder communication templates standardize status updates (progress, next steps, risks, and decisions needed) and incident communications, ensuring consistent messaging across the organization. This structured approach to communication, combined with a single source of truth maintained in project repositories, enables OctoAcme to scale institutional knowledge while maintaining alignment across distributed teams.

## Process Documents

- [Project Management Overview](octoacme-project-management-overview.md) — Introduction to OctoAcme's approach, principles, core roles, and communication cadence
- [Project Initiation Guide](octoacme-project-initiation.md) — Steps to validate business needs, align stakeholders, and create an initial plan
- [Project Planning](octoacme-project-planning.md) — Breaking work into shippable increments, identifying dependencies, and defining milestones
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Day-to-day execution, team rhythm, quality assurance, and blocker escalation
- [Risks & Communication](octoacme-risks-and-communication.md) — Risk management, stakeholder communication, and escalation paths
- [Release & Deployment](octoacme-release-and-deployment.md) — Systematic, low-risk release process with checklists and rollback playbooks
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capturing learnings and converting them into actionable improvements
- [Roles & Personas](octoacme-roles-and-personas.md) — Detailed definitions of Project Managers, Product Managers, and Developers

## Quick Links

- **New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md)
- **Starting a new project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md)
- **Need to escalate a risk or blocker?** See [Risks & Communication](octoacme-risks-and-communication.md)
- **Preparing for a release?** Check the [Release & Deployment](octoacme-release-and-deployment.md) guide
- **Want to understand team roles?** Review [Roles & Personas](octoacme-roles-and-personas.md)

## How to Use These Docs

- Keep the Project Charter updated in your project repo
- Add process-specific docs to `.github/prompts` or `.github/instructions` if you want Copilot Spaces to use them as context
- Refer to the appropriate guide at each phase of your project
- Bring questions and feedback to your team's retrospectives to continuously improve these processes
