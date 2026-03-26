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

## QA / Testing

### Role Summary
QA and Testing team members ensure that software meets quality standards before release. They design and execute test plans, identify defects, and validate that acceptance criteria are met.

### Responsibilities
- Design and execute manual and automated test cases
- Report, triage, and track defects through resolution
- Validate that features meet defined acceptance criteria
- Collaborate with Developers on test environments and coverage
- Support regression and performance testing during release cycles

### Goals
- Prevent defects from reaching production
- Increase test coverage and reduce manual testing effort over time
- Ensure a consistent, high-quality user experience

### Typical Communication
- Sprint planning and backlog refinement for test scoping
- Defect reports and test result summaries
- Sign-off communications before deployment

---

## Scrum Master

### Role Summary
The Scrum Master is an agile facilitator and servant-leader who ensures the team follows Scrum practices, removes impediments, and continuously improves delivery processes. They act as a shield between the team and external distractions.

### Responsibilities
- Facilitate agile ceremonies: sprint planning, daily standups, sprint reviews, and retrospectives
- Identify and remove team impediments and blockers in a timely manner
- Coach team members on Scrum principles and agile best practices
- Track and report sprint velocity, capacity, and process health
- Foster a culture of continuous improvement and psychological safety

### Goals
- Maximize team flow and sprint predictability
- Reduce impediment resolution time
- Build a self-organizing, high-performing team

### Typical Communication
- Daily standups and retrospective facilitation
- Impediment logs and escalation paths
- Agile metrics and velocity reports shared with Project Manager and Product Manager

### Interactions with Other Roles
- **Project Manager:** Aligns on delivery timelines, escalates organizational blockers, and coordinates cross-team dependencies.
- **Product Manager:** Supports backlog refinement, ensures the team has clear priorities for each sprint, and protects sprint commitments.
- **Developers / QA:** Acts as a servant-leader to unblock work, coaches on process, and shields the team from unplanned interruptions.
- **Business Analyst:** Coordinates during backlog refinement to ensure user stories are well-defined before sprint planning.

---

## UX / UI Designer

### Role Summary
The UX/UI Designer owns the user experience and visual design of the product. They conduct user research, create wireframes and prototypes, and ensure the product meets usability and accessibility standards before and during implementation.

### Responsibilities
- Conduct user research, usability testing, and journey mapping
- Create wireframes, mockups, and interactive prototypes
- Define and maintain design systems, style guides, and component libraries
- Ensure accessibility (WCAG) and usability standards are met
- Review implemented features for design fidelity and provide feedback

### Goals
- Deliver intuitive, accessible, and visually consistent user experiences
- Reduce design-to-implementation rework through clear specifications
- Validate designs with real users before and after release

### Typical Communication
- Design reviews and critique sessions with Product Manager and Developers
- Prototype walkthroughs and usability testing readouts
- Design handoff via design tools (e.g., Figma) with annotated specs

### Interactions with Other Roles
- **Product Manager:** Collaborates to translate product requirements into user journeys and validates that designs meet business goals.
- **Developers:** Provides design assets, specifications, and implementation guidance; reviews built features for design accuracy.
- **Business Analyst:** Works together to align user flows with documented business requirements and acceptance criteria.
- **QA / Testing:** Supports usability and visual regression testing by providing design baselines and expected behaviors.

---

## Business Analyst

### Role Summary
The Business Analyst bridges business stakeholders and the technical team. They gather, clarify, and document requirements, ensuring that development work is grounded in well-defined, testable user stories and acceptance criteria.

### Responsibilities
- Elicit and document business requirements through stakeholder interviews and workshops
- Translate business needs into actionable user stories and acceptance criteria
- Maintain a requirements traceability matrix to track coverage
- Facilitate backlog refinement sessions with Product Manager and Developers
- Identify and resolve requirement ambiguities before development begins

### Goals
- Ensure all delivered features trace back to validated business requirements
- Reduce mid-sprint scope changes caused by unclear requirements
- Improve handoff quality between business stakeholders and engineering

### Typical Communication
- Backlog refinement and requirements workshops
- User story writeups, acceptance criteria documents, and process flow diagrams
- Regular check-ins with stakeholders to validate understanding

### Interactions with Other Roles
- **Product Manager:** Partners on backlog prioritization and ensures requirements align with the product vision and roadmap.
- **Project Manager:** Provides requirements status and flags scope risks that may impact timelines.
- **Developers:** Clarifies requirements during sprint planning and development; answers questions to unblock implementation.
- **QA / Testing:** Defines clear acceptance criteria that serve as the basis for test cases and sign-off conditions.
- **UX/UI Designer:** Aligns user flows and interface requirements with documented business processes.

---

## DevOps Engineer

### Role Summary
The DevOps Engineer automates deployment pipelines, manages infrastructure, and ensures system reliability. They bridge development and operations, enabling fast, safe, and repeatable software releases.

### Responsibilities
- Design, build, and maintain CI/CD pipelines and automation workflows
- Manage cloud infrastructure provisioning, configuration, and scaling
- Monitor system health, set up alerting, and lead incident response
- Establish and enforce security, compliance, and access control policies for infrastructure
- Support Developers with environment setup, tooling, and deployment guidance

### Goals
- Achieve fast, reliable, and repeatable deployment cycles
- Minimize mean time to recovery (MTTR) for production incidents
- Increase infrastructure reliability and observability

### Typical Communication
- Release planning sessions and deployment runbooks
- Incident reports, postmortems, and on-call escalation paths
- Infrastructure-as-code pull requests and architecture documentation

### Interactions with Other Roles
- **Developers:** Provides CI/CD tooling and environment support; reviews deployment readiness of application code.
- **QA / Testing:** Provisions and manages test and staging environments; supports automated test pipeline integration.
- **Project Manager:** Coordinates during release windows; communicates deployment risks and rollback plans.
- **Support Lead:** Shares system health data and incident timelines to support user-facing communication and triage.

---

## Support Lead

### Role Summary
The Support Lead manages user-facing support operations, triages incoming requests and bug reports, and closes the feedback loop between end users and the product team. They are the primary escalation point for post-release issues.

### Responsibilities
- Triage, prioritize, and route incoming support tickets and bug reports
- Maintain knowledge base articles, FAQs, and internal runbooks for support
- Aggregate user feedback and identify patterns for Product Manager review
- Coordinate with DevOps Engineer and Developers on incident resolution
- Communicate status updates and resolution timelines to affected users

### Goals
- Minimize user-reported issue resolution time
- Improve self-service support coverage through documentation
- Ensure user feedback informs the product roadmap

### Typical Communication
- Regular support metrics reports shared with Product Manager and Project Manager
- Escalation notifications to DevOps Engineer and Developers during incidents
- Knowledge base updates published after each major release

### Interactions with Other Roles
- **Product Manager:** Surfaces recurring user pain points and feature gaps to inform roadmap decisions.
- **Project Manager:** Reports on open support trends and escalates high-priority issues that require delivery team attention.
- **DevOps Engineer:** Coordinates on production incidents, shares user impact data, and aligns on resolution timelines.
- **Developers:** Routes reproducible bugs with clear reproduction steps; validates fixes before marking issues resolved.
- **QA / Testing:** Collaborates on regression coverage for frequently reported issues.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The full set of personas—including the six expanded roles above—reflects the cross-functional team structure used in real-world OctoAcme project delivery.

