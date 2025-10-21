# OctoAcme Project Management Framework

## Introduction

The OctoAcme project management framework provides a standardized, lightweight approach to delivering cross-functional projects that create customer and business value. This README serves as your entry point to understanding how OctoAcme runs projects—from initial concept through delivery and continuous improvement.

Our framework ensures teams can quickly align on goals, manage risks effectively, and deliver incrementally with clear ownership and accountability.

## Guiding Principles

- **Customer-first**: Prioritize customer value and usability in every decision
- **Iterative delivery**: Deliver small, testable increments rather than big-bang releases
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and blameless retrospectives

## Project Lifecycle Overview

Our projects follow a structured lifecycle with clear gates and deliverables:

1. **Initiation**: Validate business need, define success metrics, identify stakeholders, and create the Project One-pager. Decision gate: approve to move into planning. → [Detailed guide](./octoacme-project-initiation.md)

2. **Planning**: Break work into shippable increments, estimate scope, define Definition of Done, identify dependencies, and create a release plan. → [Detailed guide](./octoacme-project-planning.md)

3. **Execution & Tracking**: Manage day-to-day delivery using the project board, conduct daily standups, run CI tests, and track progress toward milestones. → [Detailed guide](./octoacme-execution-and-tracking.md)

4. **Release & Deployment**: Deploy to production following pre-release requirements, run smoke tests, and communicate releases to stakeholders. → [Detailed guide](./octoacme-release-and-deployment.md)

5. **Retrospective & Continuous Improvement**: Capture learnings, identify action items with owners, and feed improvements back into the backlog. → [Detailed guide](./octoacme-retrospective-and-continuous-improvement.md)

For a high-level overview, see the [Project Management Overview](./octoacme-project-management-overview.md).

## Key Roles & Personas

Clear roles ensure accountability and effective collaboration:

- **Project Manager (PM)**: Coordinates delivery, schedules, risk management, and cross-team communication
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, and measures success
- **Developers**: Implement features, write tests, participate in design reviews, and help estimate work
- **QA/Testing**: Validate quality, acceptance criteria, and run manual testing when needed
- **Stakeholders**: Provide inputs, approvals, and feedback throughout the project lifecycle

→ [Detailed roles and responsibilities](./octoacme-roles-and-personas.md)

## Core Workflows & Project Board

**Project Board Columns**: Backlog → Ready → In Progress → In Review → QA → Done

**Pull Request Policy**:
- Keep PRs small (≤ ~400 lines of code when possible)
- Include issue link and acceptance criteria in PR description
- CI must pass: automated tests, linting, and security scans
- Require at least one approval before merging

**Escalation Path**:
- **Level 1**: Team-level triage in daily standup
- **Level 2**: PM escalates to Product Lead and dependent teams
- **Level 3**: Sponsor-level escalation for business-impacting issues

**Risk Register**: Maintain a simple table tracking ID, description, impact, likelihood, owner, mitigation plan, and status. Review weekly. → [Risk management details](./octoacme-risks-and-communication.md)

## Quality Assurance & Testing

Quality is built in throughout development:

- **Unit tests**: For all new logic and critical paths
- **Integration tests**: Where components interact with external systems
- **End-to-end smoke tests**: Run before each release to validate critical user flows
- **Security scanning**: Automated in CI pipeline
- **Manual QA**: Performed when acceptance criteria require human validation
- **Definition of Done**: Documented per project to ensure consistency

All acceptance criteria must be met before marking work as "Done."

## Communication & Reporting

**Regular Cadence**:
- **Daily or twice-weekly standups**: 15-minute focus on progress, blockers, and dependencies
- **Weekly PM/PdM sync**: Alignment on priorities, roadmap, and risk
- **Milestone demos/reviews**: At the end of each sprint or milestone
- **Monthly stakeholder updates**: High-level status and upcoming milestones

**Weekly Status Template**:
- Progress this week
- Next steps
- Risks & blockers
- Ask / decisions needed

**Incident Communication**:
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

→ [Communication guidelines](./octoacme-risks-and-communication.md)

## Continuous Improvement

Retrospectives are held after each sprint, release, or major milestone. Structure:
- What went well
- What could be improved
- Action items (with owner and due date)
- Follow-up on previous action items

Action items are added to the project backlog or issues with clear owners and timelines. The PM reviews outstanding actions in weekly syncs to ensure accountability.

→ [Retrospective guide](./octoacme-retrospective-and-continuous-improvement.md)

## Quick Start for New Team Members

If you're new to an OctoAcme project:

1. **Read the Project One-pager**: Understand the problem, goals, and success metrics
2. **Review the project board**: Familiarize yourself with current work and priorities
3. **Check the Risk Register**: Understand active risks and mitigations
4. **Join the daily standup**: Introduce yourself and learn about current blockers
5. **Confirm the Definition of Done**: Ensure you understand quality expectations

## Related Documentation

- [OctoAcme Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)

## Related Issue

This documentation was created in response to [Issue #2](https://github.com/arsen-markiv-eleks/skills-scale-institutional-knowledge-using-copilot-spaces/issues/2) to provide a comprehensive overview and entry point for the OctoAcme project management documentation.
