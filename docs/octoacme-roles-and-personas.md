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

## Scrum Master

### Role Summary
Scrum Masters facilitate agile ceremonies, remove impediments, and ensure the team follows agreed-upon processes. They work closely with Project Managers and Product Managers to surface delivery risks and foster a culture of continuous improvement.

### Responsibilities
- Facilitate agile ceremonies (sprint planning, daily standups, retrospectives, demos)
- Remove blockers and impediments for the delivery team
- Coach the team on agile principles and best practices
- Shield the team from external distractions during sprints
- Track and communicate team velocity and health metrics
- Escalate risks and dependencies to Project Manager and Product Manager

### Goals
- Maximize team productivity and flow
- Foster a self-organizing, high-performing team
- Ensure consistent delivery cadence
- Drive continuous process improvement

### Typical Communication
- Daily standups and sprint ceremonies
- Regular syncs with Project Manager on delivery risks
- Coaching sessions with team members
- Retrospective facilitation and action item tracking

### Collaboration with Other Roles
| Role | Collaboration Points |
|------|---------------------|
| Project Manager | Coordinate on schedules, dependencies, and risk escalation |
| Product Manager | Align on sprint goals and backlog priorities |
| Developers | Remove blockers, facilitate technical discussions |
| QA Lead | Coordinate testing timelines within sprint cycles |

---

## UX Designer

### Role Summary
UX Designers focus on user experience design, collaborating with Product Managers for requirements and Developers for implementation. They provide wireframes, prototypes, and usability feedback throughout the product lifecycle.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Define interaction patterns and design standards
- Collaborate with Product Managers on user stories and acceptance criteria
- Review implementation with Developers for design fidelity
- Advocate for accessibility and inclusive design

### Goals
- Deliver intuitive, delightful user experiences
- Ensure designs are accessible and meet usability standards
- Reduce friction and improve user task completion rates
- Maintain design consistency across products

### Typical Communication
- Design reviews with Product Manager and stakeholders
- Handoff sessions with Developers (specs, assets, interactions)
- User research readouts and usability test findings
- Weekly design critiques within the design team

### Collaboration with Other Roles
| Role | Collaboration Points |
|------|---------------------|
| Product Manager | Align on requirements, validate designs against user needs |
| Developers | Handoff design specs, review implementation |
| Business Analyst | Understand business requirements and user workflows |
| QA Lead | Validate UI implementation against design specs |

---

## Business Analyst

### Role Summary
Business Analysts gather requirements, document business logic, and support both Product Managers and Stakeholders in clarifying goals and deliverables. They bridge gaps between technical and non-technical roles.

### Responsibilities
- Elicit and document business requirements and use cases
- Create process flows, data models, and specifications
- Facilitate requirements workshops and stakeholder interviews
- Translate business needs into actionable user stories
- Support acceptance testing and validate deliverables against requirements
- Maintain traceability between business goals and implementation

### Goals
- Ensure requirements are clear, complete, and testable
- Reduce ambiguity and rework through thorough analysis
- Bridge communication gaps between business and technical teams
- Deliver documentation that supports implementation and testing

### Typical Communication
- Requirements workshops with stakeholders
- Specification reviews with Product Manager and Developers
- User acceptance testing coordination with QA Lead
- Business process documentation updates

### Collaboration with Other Roles
| Role | Collaboration Points |
|------|---------------------|
| Product Manager | Translate product vision into detailed requirements |
| Developers | Clarify requirements, answer implementation questions |
| Stakeholders | Elicit needs, validate requirements, manage expectations |
| QA Lead | Define test scenarios and acceptance criteria |

---

## QA Lead

### Role Summary
QA Leads own the test strategy and coordinate with Developers and Project Managers to ensure quality standards are understood and met. They drive testing activities across the project lifecycle.

### Responsibilities
- Define and maintain the overall test strategy and QA processes
- Coordinate manual and automated testing activities
- Review and approve test plans and test cases
- Identify and track defects, prioritize fixes with Project Manager
- Ensure acceptance criteria and Definition of Done are testable
- Report on quality metrics and release readiness

### Goals
- Deliver high-quality, defect-free releases
- Ensure comprehensive test coverage across features
- Reduce regression risks through automated testing
- Maintain clear quality gates for releases

### Typical Communication
- Test planning sessions with Developers and Business Analysts
- Defect triage and prioritization with Project Manager
- Quality status reports in weekly delivery syncs
- Release readiness sign-off meetings

### Collaboration with Other Roles
| Role | Collaboration Points |
|------|---------------------|
| Developers | Define testability requirements, coordinate defect fixes |
| Project Manager | Prioritize defects, report on quality status |
| Business Analyst | Validate acceptance criteria, review test scenarios |
| UX Designer | Verify UI implementation against design specifications |

---

## Role Interaction Matrix

This matrix shows key interaction points between roles during project delivery:

| Interaction | Primary Roles | Key Handoffs |
|-------------|---------------|--------------|
| Requirements Gathering | Business Analyst, Product Manager, Stakeholders | Business requirements → User stories |
| Design Review | UX Designer, Product Manager, Business Analyst | Wireframes → Design specs |
| Sprint Planning | Scrum Master, Product Manager, Developers, QA Lead | Prioritized backlog → Sprint commitment |
| Implementation | Developers, UX Designer, Business Analyst | Design specs + Requirements → Working code |
| Testing | QA Lead, Developers, Business Analyst | Code → Test results → Defect reports |
| Release | Project Manager, QA Lead, Developers | Quality sign-off → Production deployment |
| Retrospective | Scrum Master, All Roles | Learnings → Action items |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

