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

## QA Lead

### Role Summary
QA Leads oversee the testing strategy and ensure quality standards are met across all deliverables. They coordinate manual and automated testing efforts, establish quality gates, and validate that acceptance criteria are fulfilled before releases.

### Responsibilities
- Define and maintain overall testing strategy and test plans
- Coordinate manual testing, regression testing, and exploratory testing
- Ensure comprehensive test coverage of acceptance criteria
- Establish and enforce quality gates in the delivery workflow
- Identify and track defects through resolution
- Report on quality metrics and test execution status

### Goals
- Prevent defects from reaching production
- Maintain high test coverage and quality standards
- Reduce time-to-detect for issues and bugs
- Enable confidence in release readiness

### Typical Communication
- Daily coordination with Developers on bug fixes and testing needs
- Weekly quality reports to Project Managers and Product Managers
- Test plan reviews and sign-off meetings before releases
- Defect triage sessions with engineering team

### Interactions with Other Roles
- **Developers:** Collaborate on test cases, report bugs, verify fixes, and review testability of code
- **Product Managers:** Validate acceptance criteria clarity, prioritize testing scope, and provide quality feedback on features
- **Project Managers:** Report on testing progress, quality gates status, and risks related to quality or test coverage
- **DevOps Engineers:** Coordinate test environment setup, automated test integration in CI/CD, and deployment validation
- **UX/UI Designers:** Perform usability testing and validate that UI meets design specifications

---

## UX/UI Designer

### Role Summary
UX/UI Designers create user-centered designs and interfaces that balance usability, accessibility, and business goals. They translate user needs and product requirements into wireframes, prototypes, and production-ready design assets.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Design accessible and responsive user interfaces
- Maintain design systems and component libraries
- Advocate for user needs and accessibility standards
- Collaborate on design reviews and feedback sessions

### Goals
- Deliver intuitive and delightful user experiences
- Ensure consistency across product interfaces
- Meet accessibility standards (e.g., WCAG)
- Reduce user friction and support adoption

### Typical Communication
- Design critique sessions with stakeholders and team
- Handoff meetings with Developers to review design specs
- User research findings and usability test results
- Regular check-ins with Product Managers on requirements

### Interactions with Other Roles
- **Product Managers:** Collaborate on user stories, requirements, and feature priorities; validate designs meet business goals
- **Developers:** Provide design assets, specifications, and component documentation; review implementation for design fidelity
- **QA Lead:** Participate in usability testing and validate that UI meets design and accessibility requirements
- **Technical Writers:** Ensure UI terminology is consistent with documentation and help text
- **Project Managers:** Communicate design timeline, dependencies, and scope changes

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain the infrastructure, automation, and tooling that enable reliable and efficient software delivery. They manage CI/CD pipelines, infrastructure-as-code, monitoring, and deployment processes.

### Responsibilities
- Design and maintain CI/CD pipelines and automation
- Manage infrastructure-as-code and cloud resources
- Implement deployment strategies (blue-green, canary, rollback)
- Monitor system health, performance, and reliability
- Ensure security best practices in infrastructure and deployments
- Automate repetitive tasks and improve developer experience

### Goals
- Minimize deployment time and manual intervention
- Maximize system reliability and uptime
- Enable fast feedback loops for developers
- Maintain secure and compliant infrastructure

### Typical Communication
- Daily coordination with Developers on build/deployment issues
- Weekly infrastructure and release pipeline reviews with Project Managers
- Incident response and post-mortem discussions
- Security and compliance check-ins with stakeholders

### Interactions with Other Roles
- **Developers:** Support with build tooling, deployment automation, environment troubleshooting, and CI/CD optimization
- **QA Lead:** Provide test environments, integrate automated tests in pipelines, and support deployment validation
- **Project Managers:** Advise on release pipeline risks, deployment windows, and infrastructure capacity planning
- **Product Managers:** Ensure monitoring and observability support feature success metrics and rollout strategies
- **Technical Writers:** Provide deployment documentation and runbooks for operations and support teams

---

## Technical Writer

### Role Summary
Technical Writers create and maintain clear, accurate, and accessible documentation for internal teams, end users, and stakeholders. They ensure knowledge is captured, versioned, and discoverable throughout the project lifecycle.

### Responsibilities
- Write and update user guides, API docs, and onboarding materials
- Maintain project documentation and process guides
- Create and refine release notes and changelog entries
- Ensure documentation clarity, consistency, and version control
- Collaborate with teams to capture tribal knowledge
- Support knowledge-sharing and documentation best practices

### Goals
- Make complex information understandable and accessible
- Reduce onboarding time for new team members
- Ensure documentation stays current with product changes
- Enable self-service support for users and stakeholders

### Typical Communication
- Regular sync with Developers and Project Managers on doc updates
- Review sessions for release notes and technical content
- Feedback loops with users to improve documentation clarity
- Coordination with QA and Product on acceptance criteria wording

### Interactions with Other Roles
- **Developers:** Gather technical details, review code comments and API specs, document features and architecture
- **Product Managers:** Translate product requirements and user stories into end-user documentation
- **Project Managers:** Maintain project status docs, process guides, and meeting notes; ensure docs are release-ready
- **QA Lead:** Document test procedures, known issues, and troubleshooting guides
- **UX/UI Designers:** Ensure consistency between UI text, help content, and documentation; align on terminology
- **DevOps Engineers:** Document deployment procedures, infrastructure setup, and operational runbooks

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

