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

## QA/Testing Lead

### Role Summary
QA/Testing Leads define the testing strategy, ensure quality standards are met, and own the acceptance validation process. They collaborate with developers and product managers to verify that features meet acceptance criteria and quality gates before release.

### Responsibilities
- Define test strategy and acceptance criteria interpretation
- Create and maintain test plans and test cases
- Lead acceptance testing and sign-off
- Identify quality risks and defects
- Track test coverage and quality metrics
- Participate in release readiness reviews

### Goals
- Ensure features meet acceptance criteria before release
- Reduce production defects and rework
- Maintain high quality standards and user confidence

### Interaction with Other Roles
- **Works closely with Developers**: reviews test coverage, identifies gaps, and conducts acceptance testing on completed features
- **Partners with Product Managers**: clarifies acceptance criteria and validates feature completeness against business requirements
- **Supports Project Managers**: provides quality metrics and release readiness sign-off for status reporting
- **Coordinates with DevOps/Release Engineer**: defines smoke test criteria and verifies production deployments

### Typical Communication
- QA planning in sprint kickoffs
- Defect reports and testing status in daily standups
- Release readiness checklist and sign-off

---

## Technical Architect / Tech Lead

### Role Summary
Technical Architects own the high-level technical design, system scalability, and architectural decisions. They provide technical guidance, review architectural choices, and ensure the solution meets non-functional requirements.

### Responsibilities
- Review and approve architectural proposals
- Guide design discussions and technical trade-offs
- Ensure scalability, performance, and security of design
- Identify technical risks and propose mitigations
- Mentor and support engineering teams
- Own integration points and dependencies

### Goals
- Deliver scalable, maintainable technical solutions
- Reduce technical debt and rework
- Ensure long-term system health and performance

### Interaction with Other Roles
- **Guides Developers**: provides architectural guidance and reviews implementation for alignment with technical standards
- **Informs Product Managers**: advises on technical feasibility and trade-offs for prioritization decisions
- **Partners with Project Managers**: identifies technical risks, dependencies, and integration points for planning
- **Collaborates with Security Champion**: ensures security architecture and design principles are embedded

### Typical Communication
- Technical design reviews and architecture decision records (ADRs)
- Code review comments on complex components
- Technical risk escalations

---

## Business Analyst

### Role Summary
Business Analysts bridge business requirements and technical implementation. They gather and clarify stakeholder needs, document requirements, and ensure the solution aligns with business objectives.

### Responsibilities
- Gather and analyze business requirements from stakeholders
- Document functional and non-functional requirements
- Create detailed requirement specifications and user stories
- Validate requirement clarity and completeness with stakeholders
- Support trade-off discussions between business needs and technical constraints
- Ensure traceability from requirements to deliverables

### Goals
- Translate complex business needs into clear, actionable requirements
- Reduce rework and scope creep through clear documentation
- Ensure solutions deliver measurable business value

### Interaction with Other Roles
- **Partners with Product Managers**: refines prioritization through detailed business impact analysis
- **Supports Developers**: clarifies requirements during implementation and answers detailed specification questions
- **Works with QA/Testing Lead**: ensures acceptance criteria align with original business requirements
- **Coordinates with Project Managers**: identifies scope, timeline, and resource implications of requirements

### Typical Communication
- Requirement specification documents and user stories
- Stakeholder interviews and workshops
- Requirements clarification in sprint planning and reviews

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters facilitate agile ceremonies, remove team impediments, and enable continuous improvement. They support the team in following agile practices and help drive organizational adoption of agile principles.

### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Remove blockers and impediments preventing team progress
- Coach team members on agile practices and self-organization
- Track team velocity and sprint metrics
- Support organizational adoption of agile methodologies
- Help resolve conflict and improve team dynamics

### Goals
- Enable high-performing, self-organizing teams
- Maximize team velocity and delivery predictability
- Foster continuous learning and improvement culture

### Interaction with Other Roles
- **Enables all team members**: removes impediments for developers, QA, architects, and analysts
- **Supports Project Managers**: provides sprint metrics and team capacity planning insights
- **Facilitates Product Manager engagement**: helps structure backlog refinement and prioritization ceremonies
- **Partners with Technical Architect**: assists in managing technical dependencies and architectural decisions

### Typical Communication
- Agile ceremony facilitation and notes
- Sprint metrics and retrospective action items
- Team health and impediment escalations

---

## Stakeholder / Executive Sponsor

### Role Summary
Stakeholders and Executive Sponsors provide business context, strategic direction, and resource approval. They prioritize initiatives against organizational strategy and ensure executive alignment and support.

### Responsibilities
- Define strategic business objectives and success metrics
- Provide resource approval and budget authorization
- Validate business case and ROI assumptions
- Escalate and resolve high-level blockers
- Communicate project status to executive leadership
- Make go/no-go decisions at major milestones

### Goals
- Ensure initiatives align with organizational strategy
- Maximize return on investment and business impact
- Maintain executive visibility and stakeholder alignment

### Interaction with Other Roles
- **Engages with Project Managers**: receives status updates and resolves executive-level escalations
- **Partners with Product Managers**: validates business objectives, success metrics, and prioritization
- **Provides direction to all teams**: sets strategic context and decision-making authority
- **Reviews with QA/Testing Lead**: approves release decisions and post-launch metrics

### Typical Communication
- Executive briefings and status reports
- Quarterly business reviews and milestone approvals
- Strategic planning sessions

---

## Customer / User Representative

### Role Summary
Customer or User Representatives provide direct customer perspective and validate that solutions meet real user needs and expectations. They bridge the gap between the organization and end users.

### Responsibilities
- Represent customer needs and pain points
- Validate feature designs and solutions against user expectations
- Participate in user testing and feedback sessions
- Clarify user workflows and use cases
- Escalate critical customer issues and feedback
- Champion user experience and usability

### Goals
- Ensure solutions meet real customer needs
- Reduce customer dissatisfaction and churn
- Drive adoption and user satisfaction

### Interaction with Other Roles
- **Advises Product Managers**: provides customer feedback for prioritization and roadmap planning
- **Reviews with Developers and QA**: validates implementation against user requirements and expectations
- **Provides input to Business Analysts**: clarifies user workflows and use cases for requirement documentation
- **Supports Customer Success teams**: bridges communication between product organization and customer support

### Typical Communication
- User acceptance testing and feedback sessions
- Customer issue reports and feature requests
- Usability testing participation and feedback

---

## DevOps / Release Engineer

### Role Summary
DevOps Engineers and Release Engineers manage deployments, infrastructure, and operational readiness. They ensure reliable, efficient delivery pipelines and infrastructure that supports production systems.

### Responsibilities
- Design and maintain CI/CD pipelines and infrastructure
- Manage deployment processes and rollback procedures
- Monitor system performance and reliability metrics
- Configure and manage infrastructure as code
- Conduct pre-release verification and smoke testing
- Support incident response and post-incident analysis

### Goals
- Ensure reliable, repeatable deployments
- Minimize deployment risk and downtime
- Maintain system performance, security, and scalability

### Interaction with Other Roles
- **Partners with Developers**: ensures CI/CD pipeline supports development workflow and testing requirements
- **Works with QA/Testing Lead**: coordinates smoke testing and deployment verification procedures
- **Supports Project Managers**: provides deployment readiness status and risk assessments
- **Collaborates with Technical Architect**: implements architectural requirements and non-functional design principles
- **Coordinates with Security Champion**: implements security controls and compliance in infrastructure

### Typical Communication
- Deployment checklists and release notes
- Infrastructure and pipeline documentation
- Incident response and post-mortem reports

---

## Security Champion

### Role Summary
Security Champions embed security best practices and compliance throughout the project lifecycle. They identify security risks, guide secure design and implementation, and ensure compliance with organizational security policies.

### Responsibilities
- Define security requirements and acceptance criteria
- Review design and code for security vulnerabilities
- Conduct threat modeling and security risk assessments
- Ensure compliance with security policies and standards
- Provide security training and guidance to team members
- Escalate critical security issues and incidents

### Goals
- Deliver secure, compliant solutions
- Reduce security vulnerabilities and breach risk
- Build security awareness and practices across the team

### Interaction with Other Roles
- **Guides Developers**: reviews code and provides security best practices guidance
- **Advises Technical Architect**: ensures secure architecture and design principles are embedded
- **Informs Product Managers**: advises on security-related prioritization and compliance requirements
- **Partners with DevOps/Release Engineer**: implements security controls and verifies production security posture
- **Supports Project Managers**: identifies security risks for risk registers and escalations

### Typical Communication
- Security design reviews and threat models
- Vulnerability reports and remediation tracking
- Security incident response and post-incident analysis

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When planning projects, ensure all relevant personas are identified and their responsibilities clearly assigned.
- Use interaction patterns between personas to identify communication touchpoints and dependency management needs.
