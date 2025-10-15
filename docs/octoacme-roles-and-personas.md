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

### Interactions with Other Roles
- **Product Managers**: Collaborate on feature definition, provide technical feasibility input, and clarify acceptance criteria. Participate in backlog refinement.
- **Project Managers**: Provide effort estimates, flag technical risks, and report progress on assigned work. Escalate blockers that impact delivery.
- **Scrum Master**: Partner on process improvements, raise impediments, and participate in retrospectives for continuous improvement.
- **UX Designer**: Implement designs with attention to detail, provide technical constraints feedback, and collaborate on interaction patterns.
- **Release Manager**: Prepare code for deployment, support release validation, and participate in hotfix processes when needed.
- **Business Analyst**: Clarify business logic and requirements, support estimation with technical complexity analysis.


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

### Interactions with Other Roles
- **Project Managers**: Align on delivery timelines, trade-offs, and resource allocation. PM executes delivery plan; PdM defines what to build and why.
- **Developers**: Collaborate on technical feasibility, prioritization trade-offs, and solution validation through demos and metrics.
- **Scrum Master**: Partner on backlog health, ensure stories are ready for sprint planning, and respond to prioritization questions.
- **UX Designer**: Define user problems and success criteria together, validate design solutions, and prioritize design work alongside feature development.
- **Business Analyst**: Review detailed requirements, validate business cases, and ensure metrics align with strategic objectives.


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

### Interactions with Other Roles
- **Product Managers**: Weekly syncs on roadmap alignment, priority changes, and scope decisions. Translate product vision into executable delivery plans.
- **Developers**: Coordinate on estimates, resource allocation, and delivery commitments. Track progress and escalate delivery risks.
- **Scrum Master**: Partner on team process and delivery coordination. PM handles external dependencies; Scrum Master focuses on team effectiveness.
- **UX Designer**: Ensure design work is scheduled appropriately in project plans and coordinate design reviews with stakeholders.
- **Release Manager**: Align on release schedules, coordinate release communications, and manage deployment dependencies across projects.
- **Business Analyst**: Leverage detailed requirements for planning accuracy, incorporate impact analysis into risk management.


---

## Scrum Master

### Role Summary
Scrum Masters facilitate Agile ceremonies, remove impediments, and coach the team in Scrum practices. They ensure the team follows agreed processes and continuously improves delivery effectiveness.

### Responsibilities
- Facilitate daily standups, sprint planning, retrospectives, and demos
- Remove blockers and impediments that prevent team progress
- Shield the team from external disruptions and context-switching
- Coach team members on Agile principles and collaborative practices
- Track and visualize team metrics (velocity, cycle time, burndown)
- Collaborate with Project Managers on delivery coordination

### Goals
- Maximize team velocity and flow efficiency
- Foster self-organization and continuous improvement
- Ensure transparency through visible metrics and artifacts
- Create psychological safety for experimentation and learning

### Typical Communication
- Daily standup facilitation and blocker resolution
- Weekly metrics reviews with PM and team
- Retrospective summaries and action tracking
- Cross-team coordination on dependencies

### Interactions with Other Roles
- **Project Managers**: Partner on timeline planning, risk management, and stakeholder communication. Scrum Master focuses on team health and process; PM focuses on delivery coordination and external dependencies.
- **Product Managers**: Ensure backlog items are ready with clear acceptance criteria before sprint planning. Coordinate on prioritization changes mid-sprint.
- **Developers**: Remove blockers, facilitate collaboration, and coach on Agile engineering practices.

---

## UX Designer

### Role Summary
UX Designers research user needs, design intuitive interfaces, and validate solutions through prototyping and usability testing. They ensure products are accessible, usable, and delightful.

### Responsibilities
- Conduct user research and synthesize insights into design requirements
- Create wireframes, prototypes, and high-fidelity mockups
- Define information architecture and interaction patterns
- Validate designs through usability testing and feedback sessions
- Maintain design systems and accessibility standards
- Collaborate with developers on implementation and design QA

### Goals
- Deliver user-centered designs that solve real problems
- Reduce friction and improve user satisfaction metrics
- Ensure design consistency and accessibility compliance
- Balance user needs with technical and business constraints

### Typical Communication
- Design reviews and critiques with Product and Engineering
- User research findings and usability test reports
- Design handoff sessions and implementation support
- Accessibility and design system documentation

### Interactions with Other Roles
- **Product Managers**: Collaborate on problem definition, user research planning, and validation of solution concepts. Translate requirements into concrete design solutions.
- **Developers**: Work closely during implementation to ensure design fidelity, provide design assets, and validate UI components meet design standards.
- **QA/Testing**: Partner on usability testing and accessibility validation. Define acceptance criteria for user experience quality.

---

## Release Manager

### Role Summary
Release Managers coordinate and execute software releases, ensuring deployments are safe, well-communicated, and properly documented. They manage release schedules and coordinate cross-team dependencies.

### Responsibilities
- Create and maintain release schedules and deployment plans
- Coordinate release readiness reviews and go/no-go decisions
- Manage deployment execution and rollback procedures
- Track and communicate release status to stakeholders
- Maintain release documentation and runbooks
- Coordinate hotfix and emergency release processes

### Goals
- Deliver reliable, zero-downtime releases
- Minimize deployment risks through planning and automation
- Ensure clear communication before, during, and after releases
- Maintain release velocity while preserving stability

### Typical Communication
- Release calendars and deployment windows
- Pre-release readiness checklists and approvals
- Real-time deployment status updates
- Post-release reports and retrospectives

### Interactions with Other Roles
- **Project Managers**: Coordinate on release timing, dependencies, and stakeholder communication. PM owns project delivery; Release Manager owns deployment execution.
- **Developers**: Ensure code is release-ready, coordinate feature flags, and manage deployment validations. Partner on rollback procedures.
- **QA/Testing**: Validate release candidates through final QA gates. Coordinate on smoke tests and post-deployment validation.

---

## Business Analyst

### Role Summary
Business Analysts bridge business needs and technical solutions by gathering requirements, modeling processes, and ensuring delivered solutions meet business objectives. They analyze data to inform decisions and validate outcomes.

### Responsibilities
- Elicit and document detailed business requirements
- Model current and future-state business processes
- Define success metrics and acceptance criteria
- Analyze data to identify trends, opportunities, and risks
- Facilitate stakeholder workshops and requirements reviews
- Validate solutions against business objectives

### Goals
- Ensure technical solutions deliver measurable business value
- Reduce ambiguity through clear, testable requirements
- Enable data-driven decision making
- Bridge communication gaps between business and technical teams

### Typical Communication
- Requirements documents and user stories
- Process flow diagrams and data models
- Stakeholder workshop facilitation
- Business case analysis and ROI reports

### Interactions with Other Roles
- **Product Managers**: Partner on translating business strategy into concrete requirements. BA focuses on detailed requirements and process analysis; PM focuses on prioritization and vision.
- **Developers**: Provide detailed requirements, clarify business logic, and validate implementation against business rules. Support estimation with complexity analysis.
- **Project Managers**: Supply requirements documentation, impact analysis, and change assessments. Support planning with effort estimates and dependency mapping.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

