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
- **Product Owner**: Seeks clarification on requirements and acceptance criteria; provides effort estimates and technical feasibility input
- **Product Managers**: Contributes technical insights to product discussions and proposes technical solutions
- **Project Managers**: Reports on progress, blockers, and technical risks; participates in planning and estimation
- **QA Lead**: Collaborates on test strategy, writes automated tests, and fixes defects
- **Business Analyst**: Clarifies technical constraints and implementation approaches for business requirements
- **UX/UI Designer**: Implements designs and provides feedback on technical feasibility and performance
- **Change Manager**: Provides technical impact assessments for change requests

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
- **Product Owner**: Aligns on product vision and roadmap; delegates backlog management to Product Owner
- **Project Managers**: Coordinates on project scope, timelines, and resource allocation
- **Developers**: Engages on technical trade-offs and solution approaches
- **Business Analyst**: Leverages business analysis for market and customer insights
- **UX/UI Designer**: Reviews user research and design proposals to inform product decisions
- **Stakeholders**: Presents product strategy and gathers feedback on market needs

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
- **Product Owner**: Aligns on scope and backlog priorities; coordinates sprint planning and releases
- **Product Managers**: Synchronizes on roadmap, resource needs, and strategic priorities
- **Developers**: Tracks progress, removes blockers, and manages dependencies
- **QA Lead**: Coordinates testing schedules and ensures quality gates are met
- **Business Analyst**: Leverages requirements analysis for scope and risk management
- **Change Manager**: Coordinates change requests and assesses impact on project plans
- **UX/UI Designer**: Ensures design activities are integrated into project timelines
- **Stakeholders**: Provides status updates and manages expectations

---

## Product Owner

### Role Summary
Product Owners define and communicate the product vision, maintain the prioritized product backlog, and act as the primary liaison between stakeholders and the delivery team. They ensure the team builds the right features that deliver maximum value.

### Responsibilities
- Define and communicate the product vision and strategy
- Maintain and prioritize the product backlog
- Write clear user stories with acceptance criteria
- Make decisions on scope and trade-offs during development
- Act as the voice of the customer and key stakeholders
- Accept or reject completed work based on acceptance criteria
- Participate in sprint planning, reviews, and retrospectives

### Goals
- Maximize return on investment (ROI) for product development
- Ensure stakeholder needs are clearly represented
- Balance customer needs with business objectives
- Maintain a healthy, prioritized backlog

### Typical Communication
- Daily availability for team questions and clarifications
- Sprint planning and backlog refinement sessions
- Sprint reviews to demonstrate and accept completed work
- Regular stakeholder updates on product progress

### Interactions with Other Roles
- **Product Managers**: Aligns with PMs on overall product strategy and roadmap priorities; PM provides market insights and business case while Product Owner focuses on backlog execution
- **Project Managers**: Coordinates on scope, timeline, and resource planning; PjM manages delivery logistics while Product Owner manages feature priorities
- **Developers**: Clarifies requirements, answers questions, and provides timely feedback on implementation approaches
- **QA Lead**: Collaborates on acceptance criteria definition and validates that quality standards align with customer expectations
- **Business Analyst**: Works closely to refine requirements and ensure business logic is properly captured
- **UX/UI Designer**: Partners to ensure user stories incorporate usability and design requirements
- **Stakeholders**: Regularly communicates backlog priorities and gathers feedback on delivered features

---

## Quality Assurance Lead

### Role Summary
QA Leads ensure that deliverables meet agreed-upon quality standards through comprehensive testing strategies, test coordination, and quality metrics. They champion quality practices across the team and establish testing processes.

### Responsibilities
- Define and maintain the testing strategy and quality standards
- Coordinate testing efforts across manual and automated testing
- Review test coverage and identify gaps
- Participate in requirement reviews to ensure testability
- Lead defect triage and prioritization
- Report on quality metrics and testing progress
- Mentor team members on testing best practices
- Ensure test environments are properly configured

### Goals
- Deliver high-quality, defect-free software
- Achieve comprehensive test coverage across critical paths
- Reduce escaped defects to production
- Optimize testing efficiency through automation

### Typical Communication
- Daily standup participation and testing status updates
- Test plan reviews and sign-offs
- Defect reports and quality metrics dashboards
- Risk assessments related to quality and testing gaps

### Interactions with Other Roles
- **Product Owner**: Collaborates on acceptance criteria to ensure they are testable and comprehensive
- **Developers**: Partners on test automation, reviews code for testability, and coordinates bug fixes
- **Project Managers**: Reports on testing progress, risks, and resource needs; coordinates testing schedules
- **Business Analyst**: Validates that test scenarios cover all business requirements and edge cases
- **UX/UI Designer**: Ensures usability testing is incorporated and design specifications are verified
- **Change Manager**: Reviews change requests for quality impact and testing requirements
- **DevOps/Release Team**: Coordinates deployment validation, smoke testing, and production monitoring

---

## Business Analyst

### Role Summary
Business Analysts bridge business needs and technical solutions by eliciting, analyzing, and documenting requirements. They facilitate communication between stakeholders and technical teams to ensure solutions meet business objectives.

### Responsibilities
- Elicit and document business requirements and processes
- Analyze and model business workflows and data flows
- Translate business needs into clear, actionable requirements
- Facilitate requirement workshops and stakeholder interviews
- Create process diagrams, user flows, and requirement specifications
- Support User Acceptance Testing (UAT) coordination
- Identify opportunities for process improvement
- Maintain traceability between business needs and solutions

### Goals
- Ensure technical solutions align with business objectives
- Reduce requirement ambiguity and rework
- Facilitate effective communication between business and technical teams
- Support data-driven decision making

### Typical Communication
- Requirement specification documents and user stories
- Process flow diagrams and business cases
- Stakeholder workshops and interviews
- Clarification sessions with development team

### Interactions with Other Roles
- **Product Owner**: Assists in refining user stories and acceptance criteria; ensures business context is clear
- **Product Managers**: Provides detailed analysis to support product decisions and feature prioritization
- **Developers**: Translates business requirements into technical specifications; answers domain questions
- **Project Managers**: Contributes to scope definition, estimation, and risk identification
- **QA Lead**: Ensures test scenarios cover all business requirements and validates acceptance criteria
- **UX/UI Designer**: Provides business context for design decisions and validates workflows
- **Stakeholders**: Primary interface for gathering requirements and validating solutions
- **Change Manager**: Analyzes impact of changes on business processes and requirements

---

## Change Manager

### Role Summary
Change Managers oversee the change control process, evaluating change requests for impact, coordinating approvals, and ensuring smooth implementation of approved changes. They maintain change logs and communicate changes to all affected parties.

### Responsibilities
- Review and assess change requests for impact and urgency
- Coordinate Change Advisory Board (CAB) meetings when needed
- Document and track all changes in the change log
- Evaluate risks and dependencies of proposed changes
- Ensure proper approval processes are followed
- Communicate approved changes to all stakeholders
- Monitor change implementation and post-change validation
- Maintain change documentation and metrics

### Goals
- Minimize disruption from changes while enabling agility
- Ensure all changes are properly reviewed and approved
- Maintain clear audit trail of all changes
- Reduce failed changes and rollbacks

### Typical Communication
- Change request notifications and status updates
- Change advisory board meeting summaries
- Impact assessment reports
- Post-implementation reviews

### Interactions with Other Roles
- **Project Managers**: Coordinates on change impact to project timelines and resources
- **Product Owner**: Reviews scope changes and reprioritization requests
- **Developers**: Gathers technical impact assessments and implementation plans
- **QA Lead**: Ensures changes include appropriate testing and validation
- **Business Analyst**: Analyzes business impact and requirement changes
- **Stakeholders**: Communicates change impacts and gathers approval
- **DevOps/Release Team**: Coordinates change deployment windows and rollback plans

---

## UX/UI Designer

### Role Summary
UX/UI Designers focus on creating intuitive, user-centered interfaces and experiences. They conduct user research, create design specifications, and collaborate with product and engineering teams to ensure usability and accessibility standards are met.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Design user interfaces that meet accessibility standards
- Develop and maintain design systems and style guides
- Collaborate on user stories and acceptance criteria
- Validate implementations against design specifications
- Gather and incorporate user feedback
- Ensure consistency across product experiences

### Goals
- Create intuitive, accessible user experiences
- Reduce user friction and improve task completion rates
- Maintain design consistency across the product
- Advocate for user needs throughout development

### Typical Communication
- Design presentations and walkthroughs
- User research findings and personas
- Design specifications and prototypes
- Usability test results and recommendations

### Interactions with Other Roles
- **Product Owner**: Collaborates on feature definitions ensuring user needs are central to backlog items
- **Product Managers**: Provides user insights to inform product strategy and prioritization
- **Developers**: Works closely during implementation to ensure design feasibility and fidelity
- **QA Lead**: Coordinates on usability testing and validates that implementations meet design specs
- **Business Analyst**: Collaborates on user workflows and ensures business processes are user-friendly
- **Stakeholders**: Presents designs for feedback and validates that solutions meet user expectations
- **Accessibility Specialist**: Ensures designs meet accessibility standards and guidelines

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- These expanded roles provide clearer accountability and help teams understand handoffs and collaboration points.

