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

## Agile Coach

### Role Summary
Agile Coaches help teams adopt and improve agile practices, facilitate ceremonies, and foster a culture of continuous improvement. They act as change agents, removing impediments and coaching team members on agile principles.

### Responsibilities
- Facilitate sprint planning, retrospectives, and other agile ceremonies
- Coach teams on agile best practices and principles
- Identify and help remove organizational impediments
- Foster collaboration and self-organization within teams
- Mentor Project Managers and team leads on servant leadership
- Track and improve team health metrics and maturity

### Goals
- Increase team velocity and predictability
- Build self-organizing, high-performing teams
- Improve transparency and collaboration across the organization
- Drive continuous improvement through retrospectives and feedback loops

### Typical Communication
- Daily standup facilitation and observation
- Regular 1-on-1 coaching sessions with team members
- Monthly agile maturity assessments and improvement plans
- Cross-team collaboration on scaling practices

### Interactions with Other Roles
- **Project Managers**: Coaches PMs on servant leadership and agile facilitation techniques
- **Developers**: Provides guidance on engineering practices like pair programming and TDD
- **Product Managers**: Helps refine backlog management and stakeholder engagement approaches

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business stakeholders and technical teams. They elicit, analyze, and document business requirements, ensuring that solutions deliver expected business value.

### Responsibilities
- Elicit and document business requirements and use cases
- Create process flows, data models, and functional specifications
- Facilitate requirements workshops with stakeholders
- Validate that delivered features meet business needs
- Identify opportunities for process improvement and optimization
- Support UAT (User Acceptance Testing) planning and execution

### Goals
- Ensure clear, complete, and testable requirements
- Minimize rework due to requirement misunderstandings
- Maximize business value delivered per release
- Maintain alignment between technical solutions and business objectives

### Typical Communication
- Requirements workshops and stakeholder interviews
- Detailed functional specifications and user stories
- Traceability matrices linking requirements to deliverables
- UAT plans and acceptance documentation

### Interactions with Other Roles
- **Product Managers**: Collaborates on defining acceptance criteria and success metrics
- **Developers**: Clarifies requirements and answers questions during implementation
- **QA Lead**: Ensures test scenarios cover all business requirements
- **Stakeholders**: Primary liaison for gathering and validating requirements

---

## QA Lead

### Role Summary
QA Leads own the quality strategy for projects, ensuring comprehensive test coverage and maintaining quality standards. They manage QA resources, define testing approaches, and serve as the quality gatekeeper before releases.

### Responsibilities
- Define test strategy and approach for each project phase
- Create and maintain test plans and test case libraries
- Lead manual and automated testing efforts
- Coordinate UAT with business stakeholders
- Track defects and quality metrics (defect density, escape rate)
- Ensure Definition of Done includes appropriate quality gates
- Participate in release go/no-go decisions

### Goals
- Deliver high-quality releases with minimal production defects
- Maintain comprehensive test coverage for critical paths
- Reduce manual testing time through automation
- Build quality awareness and ownership across the team

### Typical Communication
- Daily updates on test progress and blocker issues
- Weekly quality metrics reports and defect trends
- Test plan reviews with Project Managers and developers
- Go/no-go recommendations for release decisions

### Interactions with Other Roles
- **Developers**: Collaborates on test automation strategy and reviews test cases
- **Business Analyst**: Validates test scenarios against business requirements
- **Release Manager**: Coordinates release testing and sign-off procedures
- **Project Managers**: Reports on quality risks and testing progress

---

## Release Manager

### Role Summary
Release Managers coordinate and execute production releases, ensuring smooth deployments with minimal disruption. They manage release schedules, coordinate across teams, and handle rollback procedures when needed.

### Responsibilities
- Create and maintain release schedules and deployment runbooks
- Coordinate cross-team dependencies for releases
- Execute deployment procedures and smoke tests
- Manage feature flags and gradual rollouts
- Monitor post-deployment metrics and alerts
- Coordinate rollback procedures if issues arise
- Document release notes and communicate to stakeholders

### Goals
- Achieve zero-downtime deployments
- Minimize deployment-related incidents and rollbacks
- Improve deployment frequency and lead time
- Maintain clear communication during release windows

### Typical Communication
- Pre-release checklists and readiness reviews
- Release announcements and status updates
- Post-deployment summaries and metrics
- Incident communications during release issues

### Interactions with Other Roles
- **Developers**: Reviews deployment procedures and coordinates code freezes
- **QA Lead**: Ensures all testing is complete before release approval
- **Project Managers**: Aligns release schedule with project milestones
- **Change Manager**: Coordinates organizational change activities related to releases

---

## Change Manager

### Role Summary
Change Managers plan and execute organizational change initiatives, ensuring smooth adoption of new processes, tools, or systems. They focus on people-side change management including communication, training, and stakeholder engagement.

### Responsibilities
- Assess change impact and stakeholder readiness
- Develop change management strategies and plans
- Create communication plans and materials
- Design and deliver training programs
- Identify and engage change champions and influencers
- Measure adoption rates and address resistance
- Gather feedback and adjust change strategies accordingly

### Goals
- Maximize user adoption of new systems and processes
- Minimize productivity loss during transitions
- Build organizational change capability
- Ensure sustainable change that sticks beyond go-live

### Typical Communication
- Stakeholder impact assessments and readiness reports
- Change communication newsletters and announcements
- Training schedules and materials
- Adoption metrics and post-implementation reviews

### Interactions with Other Roles
- **Project Managers**: Integrates change activities into project plans and timelines
- **Product Managers**: Aligns user adoption strategies with product rollout
- **Release Manager**: Coordinates change communications with release schedules
- **Business Analyst**: Leverages requirements analysis for impact assessments

---

## UX Designer

### Role Summary
UX Designers create intuitive, user-centered experiences by conducting research, designing interfaces, and validating designs with users. They ensure products are not only functional but delightful to use.

### Responsibilities
- Conduct user research and usability testing
- Create user personas, journey maps, and wireframes
- Design high-fidelity mockups and interactive prototypes
- Establish and maintain design systems and style guides
- Collaborate with developers on implementation feasibility
- Validate designs through user testing and iterate based on feedback
- Ensure accessibility and inclusive design standards

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and support tickets
- Improve user satisfaction and engagement metrics
- Build consistent experiences across products

### Typical Communication
- Design presentations and prototype walkthroughs
- User research findings and recommendations
- Design critique sessions with cross-functional teams
- Usability test reports and iteration plans

### Interactions with Other Roles
- **Product Managers**: Collaborates on feature prioritization based on user needs
- **Developers**: Works closely on design implementation and technical constraints
- **Business Analyst**: Incorporates business requirements into user flows
- **QA Lead**: Provides input on usability testing scenarios

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

