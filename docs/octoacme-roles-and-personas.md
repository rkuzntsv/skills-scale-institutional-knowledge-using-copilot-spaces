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

## Release Manager

### Role Summary
Release Managers own the planning, coordination, and execution of releases to production. They work closely with developers, QA, and product managers to ensure smooth, low-risk deployments and clear communication with stakeholders.

### Responsibilities
- Plan and schedule releases aligned with business priorities
- Coordinate with Developers and QA to ensure readiness
- Manage release notes, deployment checklists, and rollback plans
- Communicate release status and changes to stakeholders and support teams
- Monitor post-deployment health and coordinate incident response if needed
- Track release metrics and capture lessons learned

### Goals
- Execute reliable, predictable releases with minimal production incidents
- Reduce deployment risk and time-to-production
- Ensure clear stakeholder communication and alignment
- Maintain deployment documentation and best practices

### Typical Communication
- Release planning meetings with Product Managers and Developers
- Deployment day coordination with DevOps and QA
- Post-release stakeholder announcements
- Release retrospectives and process improvements

### Interaction with Other Roles
- **Developers**: Validate code readiness, coordinate deployment windows
- **QA Lead**: Confirm acceptance criteria met, coordinate testing sign-off
- **DevOps Engineer**: Execute deployment and monitor infrastructure health
- **Product Manager**: Align on release scope and timeline
- **Project Manager**: Track release schedule and dependencies

---

## UX Designer

### Role Summary
UX Designers are responsible for creating intuitive, accessible user experiences. They collaborate with Product Managers and Developers to validate design solutions and ensure usability across all customer touchpoints.

### Responsibilities
- Conduct user research and usability testing
- Design wireframes, prototypes, and user interfaces
- Ensure accessibility and usability standards are met
- Iterate on designs based on user feedback and metrics
- Document design decisions and design systems
- Collaborate on design reviews with the team

### Goals
- Deliver user-centric, accessible interfaces
- Reduce user friction and increase adoption
- Build cohesive, consistent product experiences
- Enable developers to implement designs efficiently

### Typical Communication
- Design reviews and feedback sessions with Developers
- Usability testing findings and recommendations
- Design documentation and system updates
- Collaboration with Product Managers on customer insights

### Interaction with Other Roles
- **Product Manager**: Align on user needs and design priorities
- **Developers**: Ensure implementability and design fidelity
- **QA Lead**: Validate design acceptance criteria
- **Support Representative**: Incorporate user feedback and common issues

---

## QA Lead

### Role Summary
QA Leads oversee the quality strategy, test coverage, and acceptance validation for features. They work closely with Developers, Release Managers, and Designers to ensure products meet quality standards before release.

### Responsibilities
- Define quality standards and acceptance criteria
- Plan and oversee testing strategy (unit, integration, end-to-end)
- Execute or coordinate manual and automated testing
- Identify, document, and track defects
- Validate acceptance criteria before sign-off
- Coordinate smoke tests and post-deployment verification
- Contribute to Definition of Done and quality metrics

### Goals
- Catch and prevent quality issues before production
- Maintain high test coverage and reliability
- Enable fast, confident feature releases
- Build quality into the development process

### Typical Communication
- Test planning and strategy discussions with Developers
- Defect tracking and triage in issue systems
- Pre-release validation checkpoints
- Quality metrics and testing reports

### Interaction with Other Roles
- **Developers**: Clarify acceptance criteria and collaborate on testing
- **Release Manager**: Sign-off on release readiness
- **UX Designer**: Validate usability and design acceptance
- **DevOps Engineer**: Coordinate environment setup for testing

---

## DevOps Engineer

### Role Summary
DevOps Engineers manage CI/CD pipelines, deployment automation, and production infrastructure health. They enable rapid, reliable releases and maintain high system availability and observability.

### Responsibilities
- Design and maintain CI/CD pipelines and deployment automation
- Manage infrastructure, environments, and deployments
- Monitor system health, performance, and errors in production
- Implement logging, metrics, and alerting
- Support incident response and troubleshooting
- Collaborate on scalability and reliability improvements
- Document runbooks and operational procedures

### Goals
- Enable fast, safe deployments with minimal manual effort
- Maintain high system uptime and performance
- Reduce time-to-recovery during incidents
- Build reliable, observable, scalable infrastructure

### Typical Communication
- Deployment coordination with Release Managers
- Incident response and on-call communications
- Infrastructure and performance reviews
- Collaboration on automation improvements

### Interaction with Other Roles
- **Release Manager**: Execute deployments and monitor health
- **Developers**: Support environment setup and troubleshooting
- **Project Manager**: Escalate infrastructure or deployment blockers
- **Support Representative**: Triage operational issues

---

## Support Representative

### Role Summary
Support Representatives are the bridge between customers and the delivery team. They gather end-user feedback, report issues and incidents, and ensure customer concerns are understood and addressed by Product and Engineering teams.

### Responsibilities
- Handle customer inquiries and support requests
- Report bugs and gather customer feedback for the team
- Escalate critical incidents to appropriate teams
- Document common issues and contribute to knowledge bases
- Participate in product feedback and feature prioritization discussions
- Provide insights on customer pain points and usability issues

### Goals
- Maximize customer satisfaction and retention
- Surface critical customer issues early to the team
- Reduce support volume through product improvements
- Enable data-driven product decisions based on customer feedback

### Typical Communication
- Customer feedback summaries and trends
- Bug and incident reports to Development team
- Feature requests and enhancement suggestions to Product Manager
- Escalations to Project Manager for critical issues

### Interaction with Other Roles
- **Product Manager**: Share customer insights and feature feedback
- **Project Manager**: Escalate critical customer-impacting issues
- **Developers**: Report bugs and provide reproduction details
- **Release Manager**: Communicate release impacts and known issues to customers

---

## Stakeholder Champion

### Role Summary
Stakeholder Champions represent the interests and viewpoints of key business stakeholders (executives, business units, partners). They ensure business priorities are understood by the delivery team and escalate business-impacting risks or decisions.

### Responsibilities
- Represent stakeholder interests in planning and prioritization
- Provide business context for decisions and trade-offs
- Escalate business-impacting risks or blockers
- Communicate project status and outcomes to stakeholders
- Gather and relay stakeholder feedback to the team
- Support decision gates and approval processes

### Goals
- Ensure alignment between business goals and delivery outcomes
- Prevent surprises and escalations by maintaining transparency
- Enable fast decision-making with clear stakeholder input
- Build trust and accountability with business leadership

### Typical Communication
- Stakeholder updates and status reports
- Business priority and trade-off discussions
- Risk escalations and decision requests
- Post-release retrospectives with stakeholders

### Interaction with Other Roles
- **Project Manager**: Facilitate stakeholder communication and escalations
- **Product Manager**: Align on business priorities and success metrics
- **Developers & QA**: Communicate business context and dependencies
- **Release Manager**: Coordinate stakeholder notifications for releases

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
